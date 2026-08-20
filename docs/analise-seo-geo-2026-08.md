# Gold Car — análise de SEO e GEO e pautas do mês

**Data da coleta:** 20 de agosto de 2026
**Fontes:** Ahrefs API v3 (país BR), auditoria do código das 23 páginas do repositório, busca web
**Escopo:** onde o site está na busca hoje, por que está assim, e o que produzir nas próximas quatro semanas.

---

## Resumo

| Pergunta | Resposta |
| --- | --- |
| O site traz cliente por busca orgânica? | Não. **1 palavra-chave posicionada, 0 visitas/mês, 2 backlinks.** |
| Isso é falta de autoridade? | Não. As oficinas que ganham essas buscas têm **DR 0 a 6** — a mesma força da Gold Car. O que elas têm são as páginas certas. |
| Qual é o erro de rota? | O site mira **bairro** ("oficina mecânica Butantã") e essas buscas têm **volume zero**. O brasileiro digita **"perto de mim"**. |
| Qual o maior buraco? | **Auto elétrica.** Está no nome da empresa, soma ~14 mil buscas/mês com dificuldade 0, e não tem **uma única página** no site. |
| E o blog atual? | Mais raso do que parece: **16 dos 19 posts têm entre 296 e 400 palavras** de texto real. |
| Tem alguma boa notícia? | Sim, e é grande: o ChatGPT já cita o site **46 vezes**. Oficinas concorrentes medidas: **zero**. |
| O que fazer este mês? | 4 páginas de serviço, 3 posts e 2 reescritas — lista datada na seção "As pautas do mês". |

**A frase que resume:** a Gold Car construiu um blog tecnicamente correto mirando as buscas erradas, enquanto o serviço que dá nome à empresa não tem página nenhuma. A correção não custa mídia — custa produção.

---

## 1. Onde o site está hoje

| Métrica (Ahrefs, 20/08/2026, BR) | Gold Car |
| --- | --- |
| Palavras-chave orgânicas | 1 |
| Palavras-chave no top 3 | 0 |
| Visitas orgânicas estimadas/mês | 0 |
| Domain Rating | 0,0 |
| Backlinks / domínios que linkam | 2 / 2 |

Os dois links são um diretório sem valor (`localdir.com.br`) e um comentário de spam vendendo serviço de SEO. Não é penalização — é ausência de perfil, o que é normal num domínio de seis meses.

**O importante é o que vem a seguir: link não é o gargalo aqui.** Medimos onze oficinas concorrentes de São Paulo. Quase todas têm entre 450 e 490 domínios referenciadores — todos do mesmo tipo de diretório comprado — e mesmo assim têm DR entre 0 e 6. Uma delas, a `cartecmecanica.com.br`, do próprio Butantã, tem **756 backlinks e zero tráfego**.

| Concorrente | DR | Visitas/mês | Keywords | Backlinks |
| --- | --- | --- | --- | --- |
| socorrodeautossp.com.br | 6,0 | 1.931 | 188 | 906 |
| hightorque.com.br | 16,0 | 1.437 | 252 | 990 |
| akautocenter.com.br | 2,1 | 1.346 | 168 | 833 |
| **centrorodcar.com.br** | **0,0** | **1.220** | 87 | 767 |
| oficinadgarage.com.br | 1,7 | 1.039 | 83 | 144 |
| cartecmecanica.com.br (Butantã) | 0,0 | **0** | 1 | 756 |
| **goldcaroficina.com.br** | **0,0** | **0** | **1** | **2** |

O `centrorodcar.com.br` é a prova mais limpa do diagnóstico: **DR zero, 1.220 visitas por mês.** Dez páginas, todas com "perto de mim" no título, nenhum blog.

---

## 2. O erro de rota: bairro não é como as pessoas buscam

O site tem duas páginas de captação local — `/blog/mecanica-butanta` e `/blog/oficina-mecanica-vila-lageado`. Elas miram termos que ninguém digita:

| Busca | Volume/mês |
| --- | --- |
| oficina mecânica butantã | **0** |
| oficina mecânica zona oeste sp | **0** |
| troca de óleo sp | **0** |
| mecânico são paulo | **0** |
| oficina mecânica são paulo | 70 |

Não é que sejam difíceis. É que **não existem**. Quem precisa de oficina não escreve o bairro — o celular já sabe onde a pessoa está. O que se digita é isto:

| Busca | Volume/mês | Dificuldade | CPC (¢ US$) |
| --- | --- | --- | --- |
| auto elétrica | 9.800 | 0 | 15 |
| auto elétrica perto de mim | 4.400 | 0 | 15 |
| mecânico perto de mim | 3.900 | 0 | **35** |
| mecânica perto de mim | 3.000 | 0 | 25 |
| oficina mecânica perto de mim | 2.000 | 0 | **30** |
| auto elétrica mais próxima | 1.900 | 3 | 15 |
| troca de óleo perto de mim | 1.800 | 0 | 15 |
| auto elétrica próximo a mim | 1.300 | 0 | 15 |
| oficina de carro perto de mim | 1.100 | 0 | 25 |
| auto elétrica perto de mim aberto agora | 900 | 0 | 20 |
| alinhamento e balanceamento perto de mim | 700 | 0 | 25 |
| eletricista automotivo perto de mim | 500 | 0 | 15 |

**Dificuldade 0 em praticamente todas.** E quem ocupa essas primeiras páginas não são redes nacionais — são oficinas de bairro com a mesma autoridade da Gold Car:

| Busca | Quem está no topo | DR | Visitas da página |
| --- | --- | --- | --- |
| auto elétrica perto de mim (4.400) | akautocenter.com.br/auto-eletrica-mais-proximo | **2** | 468 |
| auto elétrica perto de mim | centrorodcar.com.br/auto-eletrica-perto-mim | **0** | 92 |
| oficina mecânica perto de mim (2.000) | centrorodcar.com.br/oficina-mecanica-perto-mim | **0** | 347 |
| oficina mecânica perto de mim | oficinadgarage.com.br (post de blog) | **1** | 799 |
| mecânico perto de mim (3.900) | oficinamecanicariveros.com.br | 19 | 495 |

**A Gold Car não tem uma única página desse tipo.** Nem para auto elétrica, nem para mecânica, nem para troca de óleo.

E auto elétrica não é um serviço que a Gold Car "poderia" oferecer: **está no nome da empresa** e é o segundo item da lista de serviços da home. A soma da família "auto elétrica / eletricista automotivo + perto de mim / mais próxima / aberto agora" passa de **14 mil buscas por mês**, com dificuldade 0. É o maior bolso de demanda acessível da análise inteira, e a cobertura hoje é zero.

---

## 3. O blog é mais raso do que os números sugerem

Medindo só o texto dentro da tag `<article>` — sem menu, rodapé ou dado estruturado, ou seja, o que a pessoa realmente lê:

| Faixa | Quantos posts | Exemplos |
| --- | --- | --- |
| 296 a 400 palavras | **16** | motor-superaquecendo (296), correia-dentada (299), mecanica-butanta (303), bateria-do-carro (309), troca-de-oleo (314) |
| 790 a 875 palavras | 3 | alinhamento-3d (792), barulho-na-suspensao (842), luz-da-injecao (873) |
| 1.175 palavras | 1 | alinhamento-balanceamento |

A mediana do blog é **320 palavras**. Um post de 300 palavras não perde para um de 2.000 por causa do tamanho — perde porque em 300 palavras não cabe tabela, faixa de preço, nem oito perguntas respondidas. Cabe uma introdução e uma lista.

Os três posts de 28 de maio e a reescrita de 30 de junho são de outra categoria e foram a decisão certa. Desde então **não houve nova publicação — doze semanas**.

E há um problema de distribuição pior que o de tamanho: **os dois melhores posts do site não recebem nenhum link interno.** `luz-da-injecao-acesa-o-que-fazer` e `barulho-na-suspensao-quando-levar-na-oficina` estão fora do índice do blog (`blog/index.html` lista 16 dos 19 posts) e não são linkados por nenhuma página. Só existem no `sitemap.xml`. A home, por sua vez, não linka **nenhum** post — tem apenas 4 links internos, dois para `/blog/` e dois para a política de privacidade.

Isso importa muito porque `luz da injeção acesa` tem **9.000 buscas/mês, dificuldade 0 e potencial de tráfego de 8.300 visitas** — o maior número de toda a análise. É o único ativo do site com escala nacional, e está escondido dentro do próprio site.

---

## 4. GEO: a IA já cita a Gold Car — e isso muda a prioridade

Este é o achado que não estava no roteiro. Medindo citações em respostas de IA (Ahrefs, 20/08/2026):

| Domínio | ChatGPT | Copilot | Perplexity | Gemini | Google AI Overview |
| --- | --- | --- | --- | --- | --- |
| **goldcaroficina.com.br** | **46** | **7** | 0 | 0 | 0 |
| cartecmecanica.com.br | 0 | 0 | 0 | 0 | 0 |
| meumecanico.com.br | 0 | 0 | 0 | 0 | 0 |
| suaoficinaonline.com.br *(diretório)* | 151 | 14 | 101 | 59 | 47 |

**A Gold Car é citada 46 vezes pelo ChatGPT tendo zero tráfego orgânico.** Contra oficinas concorrentes, já está ganhando. O que sustenta isso é a fundação técnica que já foi feita: HTML estático que não depende de JavaScript, `robots.txt` liberando GPTBot, ClaudeBot, PerplexityBot, Google-Extended e Applebot, dado estruturado válido em 100% das páginas, autoria real com credenciais e FAQ com perguntas em linguagem falada nos 19 posts.

Das 35 buscas do nicho que medimos com dados completos, **27 mostram resposta de IA antes dos links**. Em busca de sintoma isso já é regra. A consequência: **em busca de dúvida o clique está sumindo, e a citação é o que sobra.**

Três coisas travam a escala, e nenhuma é técnica:

**A marca não é dona do próprio nome.** Buscar "Gold Car" devolve a locadora europeia Goldcar, a "Gold Car Veículos" do Reclame Aqui e um app de corridas. Pior: existem um `sites.google.com/view/gold-car-mecanica` e um `goldcar-centro-automotivo.reservio.com` que aparecem **acima do domínio oficial**. Enquanto a entidade estiver ambígua, a IA não sabe de qual Gold Car está falando.

**A citação está concentrada em ChatGPT e Copilot.** Perplexity, Gemini e o AI Overview do Google marcam zero — e essas três se alimentam de diretórios locais (guiabutanta.com, atendevoce.com.br, guiatelefone.com, suaoficinaonline.com.br) onde a Gold Car não está listada em nenhum.

**Falta o dado que a IA recorta.** Onze dos dezenove posts não têm **nenhuma menção a R$**, e justamente os de maior intenção comercial: troca de óleo, revisão, freios, bateria, diagnóstico, suspensão, velas, embreagem, injeção e as duas páginas locais. Nenhum post do site tem bloco de resposta direta logo abaixo do título — as aberturas contextualizam antes de responder. O contraexemplo interno é o `alinhamento-balanceamento`: 24 menções a preço, tabela, 8 perguntas na FAQ. É o único que foi reescrito, e é o melhor ativo do blog.

---

## 5. As pautas do mês

**Critério de entrada.** Só entra o que passa nos três ao mesmo tempo: demanda medida no Ahrefs, serviço que a Gold Car declara fazer, e chance real de aparecer — comprovada pela força de quem já ocupa aquela primeira página. O que tem volume grande mas primeira página de e-commerce ou de rede nacional ficou de fora, e está explicado no fim.

### Semana 1 — 21 a 27 de agosto

**1. Página de serviço: "Auto elétrica perto de mim — Vila Lageado e Butantã"** · *prioridade máxima*

| Busca que a página ataca | Volume/mês |
| --- | --- |
| auto elétrica | 9.800 |
| auto elétrica perto de mim | 4.400 |
| auto elétrica mais próxima | 1.900 |
| auto elétrica próximo a mim | 1.300 |
| auto elétrica perto de mim aberto agora | 900 |
| eletricista automotivo perto de mim | 500 |
| eletricista de carro perto de mim | 700 |

Dificuldade 0 em todas. O primeiro colocado de "auto elétrica perto de mim" é uma oficina **DR 2** que leva 468 visitas/mês só nessa página; o oitavo é uma oficina **DR 0**. A Gold Car faz o serviço, ele está no nome da empresa, e não existe uma linha publicada sobre ele.

Fora do blog, em `/auto-eletrica/`. Com faixa de preço por serviço (diagnóstico elétrico, alternador, motor de partida, bateria), tabela de sintoma → causa → o que fazer, e as perguntas em linguagem falada que o site já sabe escrever.

**2. Consertar a distribuição interna** · *duas horas de trabalho, ganho imediato*

Três coisas, na ordem: incluir os 3 posts que faltam no índice do blog; linkar da home pelo menos os posts locais e os três longos; e ligar `injecao-eletronica`, `diagnostico-automotivo` e `velas-de-ignicao` para o `luz-da-injecao-acesa`. Hoje o melhor conteúdo do site — o que vale 8.300 visitas de potencial — não recebe link de lugar nenhum.

### Semana 2 — 28 de agosto a 3 de setembro

**3. Página de serviço: "Oficina mecânica perto de mim"** e reposicionamento das duas páginas de bairro

"oficina mecânica perto de mim" tem 2.000 buscas/mês (CPC 30¢), "mecânico perto de mim" 3.900 (CPC 35¢), "mecânica perto de mim" 3.000, "oficina de carro perto de mim" 1.100. Dificuldade 0. Quem está no topo: uma oficina DR 0 e um post de blog DR 1 que sozinho leva 799 visitas/mês.

Junto: tirar `/blog/mecanica-butanta` e `/blog/oficina-mecanica-vila-lageado` da rota de blog e reescrevê-las com alvo "perto de mim", usando o bairro como **prova de proximidade dentro do texto**, não como palavra-chave do título. Elas têm 303 e 307 palavras hoje e miram termos de volume zero.

**4. Reescrever `luz-da-injecao-acesa-o-que-fazer`** · *o maior ativo já publicado*

9.000 buscas/mês, dificuldade 0, potencial de 8.300 visitas, e nenhum concorrente local disputa. Já tem 873 palavras e a melhor abertura do site. Falta: tabela "cor da luz → o que significa → dá para dirigir?", faixa de custo do diagnóstico, FAQ de 4 para 8 perguntas, e "Atualizado em" visível.

### Semana 3 — 4 a 10 de setembro

**5. Página: "Auto elétrica 24 horas / aberto agora"**

900 buscas/mês em "auto elétrica perto de mim aberto agora", CPC 20¢. A oficina que lidera esse termo (`akautocenter`, DR 2) tem uma página só para isso e tira 286 visitas/mês dela. O `socorrodeautossp` construiu o site inteiro em cima de urgência — "24 horas", "aberto agora", "a domicílio" — e é o concorrente com mais tráfego do grupo.

*Antes de produzir:* o horário publicado é segunda a sexta, 9h às 18h. Se a oficina não atende fora disso, esta pauta sai da lista — página de "aberto agora" que não abre gera avaliação ruim, que custa mais caro que o tráfego ganho. Se atende sábado ou emergência, precisa estar no site e no perfil do Google, onde hoje não está.

**6. Post: "Quanto custa alinhamento e balanceamento em São Paulo em 2026"**

700 buscas/mês, potencial de 1.000, CPC 20¢, resposta de IA na primeira página. O caminho está demonstrado: `rbautomotivo.com.br` tem **DR 0** e captura 117 palavras-chave com uma página chamada "Alinhamento e Balanceamento – R$ 230,00". Preço publicado é o atalho mais barato para toda a cauda de "quanto custa" — e é o formato que a IA cita.

### Semana 4 — 11 a 17 de setembro

**7. Página de serviço: "Troca de óleo perto de mim"**

1.800 buscas/mês com mapa do Google na primeira página, mais 17.000 no termo raiz. O post atual tem **314 palavras e zero menção a preço**. Página de serviço nova, com faixa por tipo de óleo e tempo de execução; o post vira o conteúdo de apoio e linka para ela.

**8. Post: "Carro falhando: as 7 causas mais comuns e como identificar cada uma"**

1.500 buscas/mês em "carro falhando" e 1.600 em "carro falhando o que pode ser", resposta de IA na primeira página, zero cobertura no site. Um concorrente (`riveros`) já tira 49 visitas/mês de "carro falhando ao acelerar" com uma página só. Liga com injeção eletrônica e velas de ignição, que já existem — resolve conteúdo e distribuição interna ao mesmo tempo.

### Pautas que dependem de confirmação do cliente

Estas três têm demanda medida, mas a Gold Car **não declara o serviço no site**. Se a oficina faz, entram na frente de metade da lista acima. Se não faz, saem inteiras.

| Pauta | Demanda | Por que vale |
| --- | --- | --- |
| **Ar-condicionado automotivo** | ~7.000/mês somando o cluster, todo com mapa na SERP | Sazonal e subindo agora: "conserto de ar condicionado automotivo" vai de **1.500 em agosto para 2.484 em dezembro (+66%)**. Página leva de 6 a 12 semanas para posicionar — publicada em agosto, chega pronta em outubro |
| **Troca de óleo de câmbio automático** | 2.000 nacional + 900 com mapa | **CPC de 40 centavos, o mais alto de todo o levantamento.** É o serviço que o mercado mais paga para anunciar |
| **Retífica de turbina** | 10 a 50/mês | Volume irrelevante, mas a primeira página é a mais fraca que medimos (oficinas DR 0, 4, 7 e 8) e o tíquete é alto. Vale por lead, nunca por tráfego |

**Sobre turbina, um alerta.** É o diferencial que a empresa anuncia no próprio nome, e a busca genérica praticamente não existe: "conserto de turbina" tem 10/mês, "oficina especializada em turbina" tem 10, "retífica de turbina" tem 10. A demanda real é **por modelo**:

| Busca | Volume/mês |
| --- | --- |
| turbina toro diesel | 200 |
| turbina pajero sport 2.5 diesel | 100 |
| turbina fiat toro diesel | 80 |
| turbina da toro diesel | 70 |
| turbina toro diesel 2.0 | 70 |
| turbina fiat toro diesel 2017 | 60 |
| mangueira turbina toro diesel | 60 |

A Fiat Toro concentra cerca de **540 buscas/mês** somando as variações; a Pajero Sport, outras 150. Escrever "turbina" genérico não alcança ninguém. "Turbina da Toro diesel: sintomas, causa e quanto custa" alcança quem tem o carro e o problema.

### O que ficou de fora, e por quê

| Tema | Volume | Motivo |
| --- | --- | --- |
| amortecedor, pastilha de freio, correia dentada, embreagem | 22.000 a 55.000 | primeira página é de loja de peça — quem busca quer comprar, não consertar |
| alinhamento e balanceamento (termo raiz) | 15.000 | topo é Porto Seguro (DR 83) e DPaschoal (DR 43). Ataque só a cauda: "perto de mim" e "quanto custa" |
| scanner automotivo | 24.000 | volume enganoso: a intenção é comprar o aparelho |
| eletricista perto de mim | 7.100 | é eletricista residencial, não automotivo |
| termos com bairro | 0 | ver seção 2 |

---

## 6. Correções que valem mais que pauta nova

Ordenadas por retorno sobre esforço. As quatro primeiras são de baixo esforço.

| # | O que fazer | Por que | Esforço |
| --- | --- | --- | --- |
| 1 | **Expandir o `sameAs` e replicar nos 19 posts.** Hoje são 3 perfis, só na home. Incluir o CID do Google Meu Negócio, YouTube, LinkedIn, Reclame Aqui | É o mecanismo pelo qual a IA separa a oficina da locadora Goldcar. Sem isso, a citação não escala | Baixo |
| 2 | **Usar um nome só, em todo lugar.** O código traz três: "Gold Car Mecânica, Auto Elétrica & Motores" (home), "Gold Car Mecânica" (21 páginas) e "Auto Elétrica e Turbina" no branding | Nome divergente quebra a consolidação da entidade no Google e na IA | Baixo |
| 3 | **Alinhar o número de avaliações.** O código declara nota 5,0 com **48 avaliações**; a página diz **"mais de 60"** | Dado estruturado que contradiz a página derruba a exibição das estrelinhas | Baixo |
| 4 | **Marcar os depoimentos como `Review`.** São 9 depoimentos nominais visíveis na home e nenhum está marcado | Nota agregada sem nenhuma avaliação marcada é candidata a ação manual do Google | Baixo |
| 5 | **Consolidar os perfis paralelos.** O `sites.google.com/view/gold-car-mecanica` e o `goldcar-centro-automotivo.reservio.com` aparecem acima do domínio oficial | Estão competindo com o próprio site pela marca | Baixo |
| 6 | **Listar a oficina nos diretórios locais** — guiabutanta, atendevoce, guiatelefone, suaoficinaonline | É a via para Perplexity, Gemini e AI Overview, onde hoje o placar é zero | Médio |
| 7 | **Bloco "resposta rápida" de 40 a 60 palavras logo abaixo do H1**, nos 19 posts | Nenhum post tem. É a correção de maior retorno por hora investida em citação por IA | Médio |
| 8 | **Faixa de preço nos 11 posts que não têm nenhum R$** | "Quanto custa" é a pergunta que mais gera citação com o nome da marca | Médio |
| 9 | **Padronizar o tipo do negócio no dado estruturado.** 19 páginas usam `AutoRepair` com identificador; 4 usam `LocalBusiness` sem identificador | As 4 criam uma entidade separada em vez de reforçar a principal | Baixo |
| 10 | **Mostrar "Atualizado em" com data visível** e sincronizar com o dado estruturado. Hoje 14 posts nunca foram revisados e nenhum exibe data de atualização | Sinal de frescor que a IA lê | Baixo |
| 11 | **Atualizar o `lastmod` do sitemap**, parado em 11 e 30 de junho | Baixo | Baixo |
| 12 | **Remover o link duplicado da fonte do Google** (linhas 61 e 62 do `index.html`, e em todos os posts) e dar `width`/`height` às 6 imagens da home que não têm | Perda pequena de desempenho e risco de layout saltando ao carregar | Baixo |

---

## 7. O que precisa vir do cliente para destravar

Sem estes itens, parte da lista fica bloqueada ou vira chute — e não vamos publicar chute.

1. **Faixas de preço reais por serviço.** Bloqueia as correções 7 e 8 e metade das pautas. É o insumo mais importante da lista.
2. **A oficina faz ar-condicionado automotivo, câmbio automático e alinhamento?** Define três pautas.
3. **Atende fora de segunda a sexta, 9h às 18h?** Define a pauta de "aberto agora".
4. **Número real de avaliações no Google** e o link do perfil com o identificador.
5. **Acesso ao Search Console.** Hoje todo número de tráfego neste documento é estimativa do Ahrefs, não dado real da Gold Car.
6. **Confirmação de que o Google Sites e o Reservio são da oficina.** Se forem, consolidar; se não forem, é uso indevido da marca.
7. **Logs do Cloudflare filtrados por robô de IA.** A observabilidade já está ligada. É a única forma de saber quais páginas o ChatGPT está lendo — hoje sabemos que cita 3 páginas, não quais.

---

## 8. Riscos

**O Google Meu Negócio decide mais que o site, e está fora desta análise.** Nas buscas de maior valor comercial, o mapa aparece acima de tudo. Nenhuma página do site ganha do perfil do Google ali. Se o perfil estiver incompleto ou com categoria errada, todo o trabalho de conteúdo rende menos. Recomendo auditá-lo antes de a Semana 3 começar.

**Página nova não posiciona em 30 dias.** A expectativa honesta para as páginas de "perto de mim" é posição 8 a 20 em 90 dias, não top 3. Os concorrentes têm domínio mais velho. Top 3 é meta de 6 a 12 meses, e só com publicação constante.

**Publicar preço expõe a oficina a comparação.** É a contrapartida real da recomendação. Faixa ("de R$ X a R$ Y, conforme o porte do carro") resolve sem tabelar, e é o que a concorrente DR 0 fez para capturar 117 palavras-chave.

**Doze semanas sem publicar é o risco silencioso.** Nada nesta lista funciona sem cadência. Duas publicações por mês, constantes, valem mais que oito num mês e nada em três.

---

## 9. Fontes e limites

**Consultado em 20 de agosto de 2026.** Volume de busca, dificuldade, CPC e posições mudam; reconferir antes de decidir orçamento.

**Todo número de tráfego é estimativa do Ahrefs**, incluindo os dos concorrentes. Sem Search Console da Gold Car, não há dado real de impressão e clique.

**Acentuação muda o volume, e isso afetou a análise.** "luz da injecao acesa" (sem acento) devolve 200 buscas/mês; "luz da injeção acesa" devolve **9.000**. Os números deste documento usam a grafia acentuada onde ela existe. Se você vir números menores em levantamentos anteriores, é essa a causa.

**Corrigimos uma medição divergente.** Três medições de tamanho dos posts deram resultados diferentes: uma contou a página inteira (1.300 a 3.700 palavras), outra contou o texto com menu e rodapé (600 a 750). A que usamos conta só o que está dentro da tag `<article>` — o texto que a pessoa lê — e dá **296 a 400 palavras** para 16 dos 19 posts. É a mais conservadora e a mais correta para julgar profundidade.

**Não foi coberto:** Google Meu Negócio, avaliações e Maps (o Ahrefs não expõe); Core Web Vitals medido em produção; mídia paga; qual das páginas o ChatGPT cita (o relatório de marca vem contaminado pelos homônimos, e registramos como sem dado em vez de estimar); e o `robots.txt` publicado — validamos o arquivo do repositório, não o que está no ar.
