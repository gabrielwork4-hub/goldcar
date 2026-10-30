# T-02 — Isolar arquivos internos no Cloudflare Pages

**Contexto:** o deploy é Cloudflare **Pages** (projeto `goldcar-site`) e publica a **raiz do repo**. Pages ignora `assets.directory`, `not_found_handling` e `.assetsignore` do `wrangler.jsonc`. Por isso `seo-notas/`, `wrangler.jsonc`, `README.md`, `.gitignore` e `.assetsignore` respondem 200 em produção.
Este documento NÃO deve ir para a branch publicada (`main`); fica nesta branch de plano.

## Opção A (recomendada, sem painel) — testada no preview
Remover os arquivos internos da raiz de `main`. Testado na branch `ao/implementacao-voce-imple/seo-t02-teste` (preview https://279797d5.goldcar-site.pages.dev): deploy OK; `/`, `/blog/`, posts, `/sitemap.xml`, `/robots.txt` = 200; `/nada-xyz` = 404; `/wrangler.jsonc`, `/README.md`, `/seo-notas/...`, `/.gitignore`, `/.assetsignore`, `/_headers` = 404; `_headers` segue valendo (X-Frame-Options presente); 22 URLs do sitemap = 200.
Passos:
1. Guardar as notas fora de `main`: manter `seo-notas/` numa branch de documentação (ex.: `docs/seo-notas`) ou em repo/Drive privado.
2. Em `main`: `git rm -r README.md seo-notas wrangler.jsonc .assetsignore .gitignore` (o README está vazio; `wrangler.jsonc` só tem nome/flags e Pages não depende dele — confirmar no painel que não há `pages_build_output_dir` nem bindings vindos dele).
3. Abrir PR, conferir o preview (comandos abaixo) e mesclar.
Perda: sem `.gitignore` o repo volta a aceitar lixo local — manter um `.gitignore` global no computador, ou manter `.gitignore` aceitando que ele fique público (sem conteúdo sensível).
**Rollback:** `git revert <commit>` de main; Pages redeploya em ~1 min.

## Opção B (painel) — build output directory
1. Mover o site para `public/` num PR (ou manter a raiz e usar build command que copie).
2. Painel Cloudflare → Workers & Pages → `goldcar-site` → Settings → Builds & deployments:
   - Build command: `mkdir -p public && cp -r 404.html _headers _redirects index.html politica-privacidade.html robots.txt sitemap.xml assets blog favicon fotos public/` (se o site continuar na raiz) — ou vazio se já estiver em `public/`.
   - Build output directory: `public`.
3. Fazer a mudança de painel e o merge **no mesmo momento**: se o painel mudar antes do merge, produção cai (não existe `public/`); se o merge ocorrer antes, o Pages continua publicando a raiz (sem `public/` publicado, o deploy falha ou ficam arquivos antigos).
4. Validar o deploy de produção com `curl` (abaixo).
**Rollback:** painel → Build output directory de volta para `/` (vazio) e build command vazio → "Retry deployment" do último deploy bom (ou Rollback no histórico de deployments).
Aviso: a configuração de build vale para todas as branches (previews incluídos); não dá para testar numa branch isolada sem tocar produção, por isso a Opção A é preferível.

## Validação pós-deploy
```
for u in / /blog/ /blog/pastilha-de-freio /sitemap.xml /robots.txt /nada-xyz /wrangler.jsonc /README.md /seo-notas/dados-tecnicos-modo-ia.md; do echo "$u $(curl -s -o /dev/null -w '%{http_code}' https://www.goldcaroficina.com.br$u)"; done
```
Esperado: 200 para os cinco primeiros; 404 para os demais.
