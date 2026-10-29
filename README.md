# tonelloesiqueira.social

Conteúdo de redes sociais da Tonello & Siqueira: posts de Instagram e LinkedIn prontos para publicar, ativos de marca, fotos e os relatórios mensais de desempenho do Instagram.

## Estrutura

```
/photos           — fotos originais (vinhedo, etc.)
/logo             — logomarcas e variações (ts-logo-*)
/instagram
  /01-vinicola-valle-de-uco
  /02-boutique-x-plataforma
  /03-metodo
  /04-modelagem
  /05-caso-vinicola
  /06-intermediacao
  /07-para-quem-vende
  /08-para-quem-compra
  /09-para-quem-compra-ii
  /10-empreendedorismo
  /11-… a /37-…   — tambor (a partir de 18/11): uma pasta por post, numeradas na ordem do calendário;
                    nome = número + série + tema (ex.: 11-termo-earn-out); vagas da série Variável em aberto = `NN-variavel-vazio`
/linkedin             — numeração igual à do Instagram (mesmo tema, mesmo número)
  /02-a-casa
  /03-metodo
  /04-modelagem
  /05-caso-vinicola
  /06-intermediacao
  /07-para-quem-vende
  /08-para-quem-compra
  /09-para-quem-compra-ii
  /10-empreendedorismo
/relatorios
  /instagram
    /2026-10-base     — relatório exploratório de diagnóstico (21/10/2026)
    /2026-10-previa   — prévia de outubro (01 a 21/10) + dados-2026-10-previa.json
    /AAAA-MM          — um por mês de competência (PDF + dados-AAAA-MM.json + prints)
    /seguidores       — base de seguidores por data (AAAA-MM-DD.txt), para identificar entradas e saídas
TS-tambor-posts-11-a-37.pdf   — proposta do tambor (séries, templates e posts 11 a 37)
pp-institucional.pptx, pp-vendedor.pptx, pp-comprador.pptx — decks-base do conteúdo
```

Cada pasta de post (Instagram ou LinkedIn) contém:
- `post-*.png` — imagem(ns) prontas para publicar (Instagram: carrossel)
- `legenda.txt` — legenda + hashtags, pronta para copiar e colar (LinkedIn: `texto.txt` + foto `ts-linkedin-postNN-*.jpg`)
- `CREDITOS.txt` — créditos das fotos do Unsplash, quando houver
- `post-visualizar.html` — pré-visualização no navegador (opcional)

## Calendário — outubro/novembro 2026

| # | Canal | Tema | Data | Status |
|---|-------|------|------|--------|
| 1 | Instagram | Estreia no setor vitivinícola — Valle de Uco | — | Publicado |
| 2 | Instagram | A Casa — Plataforma x Casa de M&A | qua 14/10 | Publicado |
| 3 | Instagram | Método — como conduzimos | ter 20/10 | Publicado |
| 4 | Instagram | Modelagem — metodologia | sex 23/10 | Publicado |
| 5 | Instagram | Caso — a vinícola (anonimizado) | ter 27/10 | Aprovado — 7 telas, aceite do cliente recebido, agendado no Metricool (10:00, publicação automática) |
| 6 | Instagram | Intermediação — a venda | sex 30/10 | Aprovado — 8 telas, agendado no Metricool (10:00, publicação automática) |
| 7 | Instagram | Para quem vende | ter 03/11 | Aprovado — 6 telas, agendado no Metricool (10:00, publicação automática) |
| 8 | Instagram | Para quem compra | sex 06/11 | Aprovado — 6 telas, agendado no Metricool (10:00, publicação automática) |
| 9 | Instagram | Para quem compra II — honorários e negociação | ter 10/11 | Aprovado — 8 telas, OK do Siqueira recebido, agendado no Metricool (10:00, publicação automática) |
| 10 | Instagram | Empreendedorismo — Semana Global do Empreendedorismo (16 a 22/11) | ter 17/11 | Aprovado — 7 telas, agendado no Metricool (10:00, publicação automática) |
| 2 | LinkedIn | A Casa — Plataforma x Casa de M&A (publicação + foto) | qua 14/10 | Publicado |
| 3 | LinkedIn | Método — como conduzimos | qui 22/10 | Aprovado — texto + foto |
| 4 | LinkedIn | Modelagem — metodologia | seg 26/10 | Aprovado — texto técnico (IVS + FAST) + foto |
| 5 | LinkedIn | Caso — a vinícola (anonimizado) | qui 29/10 | Aprovado — texto técnico + foto, aceite do cliente recebido |
| 6 | LinkedIn | Intermediação — a venda | ter 03/11 | Aprovado — texto técnico + foto |
| 7 | LinkedIn | Para quem vende | qui 05/11 | Aprovado — texto técnico + foto |
| 8 | LinkedIn | Para quem compra | seg 09/11 | Aprovado — texto técnico + foto, OK do Siqueira recebido |
| 9 | LinkedIn | Para quem compra II — honorários e negociação | qui 12/11 | Aprovado — texto técnico + foto, OK do Siqueira recebido |
| 10 | LinkedIn | Empreendedorismo — Semana Global do Empreendedorismo (16 a 22/11) | qui 19/11 | Aprovado — texto técnico + foto |

Instagram: sempre às 10:00 (pico da conta em dias úteis, Metricool). Sem sábados.
LinkedIn: dois dias após o post de Instagram de mesmo número; se cair em fim de semana ou feriado, passa ao dia útil seguinte (sex → seg; 02/11 Finados → ter 03/11).

Posts de Instagram são escritos para funcionar também como Threads (texto autocontido,
sem depender da imagem). Posts de LinkedIn: publicação de texto + uma foto (1080×1350), com o mesmo número do post de Instagram correspondente.
Texto do LinkedIn (padrão desde 16/10/2026, aplicado aos posts 3 a 10): 1.300 a 1.700 caracteres; primeira frase com até ~150 caracteres e autônoma (corte do "ver mais"); parágrafos curtos, de duas ou três linhas; no máximo uma citação de norma por bloco.

## Calendário — tambor (Instagram, posts 11 a 37)

Três posts por semana em dias úteis, às 10:00, com rodízio de cinco séries de template fixo e datas comemorativas de tela única. Pausa de 19/12 a 17/01. Detalhes de séries e templates em `TS-tambor-posts-11-a-37.pdf`.

| # | Data | Série | Post | Pasta |
|---|------|-------|------|-------|
| 11 | qua 18/11 | O termo | T1 — earn-out | `11-termo-earn-out` |
| 12 | seg 23/11 | Antes de responder | A1 — proposta | `12-antes-de-responder-proposta` |
| 13 | qua 25/11 | Pergunta e resposta | P1 — faturamento | `13-pergunta-faturamento` |
| 14 | sex 27/11 | Regra da casa | R1 — dois sócios | `14-regra-dois-socios` |
| 15 | seg 30/11 | Variável | Livro — Steve Jobs | `15-variavel-livro-steve-jobs` |
| 16 | qua 02/12 | O termo | T2 — data-base | `16-termo-data-base` |
| 17 | sex 04/12 | Antes de responder | A2 — exclusividade | `17-antes-de-responder-exclusividade` |
| 18 | seg 07/12 | Pergunta e resposta | P2 — vender parte | `18-pergunta-vender-parte` |
| 19 | qua 09/12 | Data comemorativa | Dia contra a Corrupção | `19-data-dia-contra-corrupcao` |
| 20 | sex 11/12 | Regra da casa | R2 — três abordagens | `20-regra-tres-abordagens` |
| 21 | seg 14/12 | Variável | Livro — Abel Ferreira | `21-variavel-livro-abel-ferreira` |
| 22 | qua 16/12 | O termo | T3 — dívida líquida | `22-termo-divida-liquida` |
| 23 | sex 18/12 | Antes de responder | A3 — balanços | `23-antes-de-responder-balancos` |
| 24 | qua 23/12 | Data comemorativa | Boas festas | `24-data-boas-festas` |
| 25 | seg 18/01 | Pergunta e resposta | P3 — o laudo garante? | `25-pergunta-laudo-garante` |
| 26 | qua 20/01 | Regra da casa | R3 — segundo caminho | `26-regra-segundo-caminho` |
| 27 | sex 22/01 | Variável | Livro — Elon Musk | `27-variavel-livro-elon-musk` |
| 28 | seg 25/01 | O termo | T4 — capital de giro | `28-termo-capital-de-giro` |
| 29 | qua 27/01 | Antes de responder | A4 — investidor | `29-antes-de-responder-investidor` |
| 30 | sex 29/01 | Pergunta e resposta | P4 — funcionários | `30-pergunta-funcionarios` |
| 31 | seg 01/02 | Regra da casa | R4 — preço piso | `31-regra-preco-piso` |
| 32 | qua 03/02 | Variável | vaga em aberto (vídeo ou livro) | `32-variavel-vazio` |
| 33 | sex 05/02 | O termo | T5 — retenção | `33-termo-retencao` |
| 34 | sex 12/02 | Antes de responder | A5 — clientes | `34-antes-de-responder-clientes` |
| 35 | seg 15/02 | Pergunta e resposta | P5 — depende de mim? | `35-pergunta-depende-de-mim` |
| 36 | qua 17/02 | Regra da casa | R5 — sinergias | `36-regra-sinergias` |
| 37 | sex 19/02 | Variável | vaga em aberto (vídeo ou livro) | `37-variavel-vazio` |

Séries: **O termo** (azul + branca, sem foto) · **Antes de responder** (capa com foto do sócio + branca) · **Pergunta e resposta** (azul + branca, sem foto) · **Regra da casa** (foto em coluna + branca) · **Variável** (tela única azul: livro, notícia ou vídeo; vídeos podem ocupar as vagas da série). Pastas de série: `post-01.png`, `post-02.png`, `legenda.txt`; livro e data comemorativa: `post-01.png`, `legenda.txt`, `CREDITOS.txt`.

## Relatórios mensais do Instagram

Emitidos entre os dias 1 e 5 de cada mês, sobre o mês anterior (competência), pela skill `ts-relatorio-instagram-mensal` (plugin tonello-advisory): comando `/ts-relatorio-instagram-mensal outubro 2026`, com os prints C1 a C3 do Insights anexados. Cada pasta `relatorios/instagram/AAAA-MM/` guarda o PDF, o `dados-AAAA-MM.json` (extração do Metricool, cálculos, metas do mês seguinte e checklist) e os prints. O JSON do mês é a base de comparação do mês seguinte — não apagar.

## Acompanhamento de seguidores

Nem o Metricool nem a API do Instagram identificam quem deixou de seguir; só o total diário (IGEV01). A lista nominal vem do download oficial de dados da Meta (instagram.com › Mais › Sua atividade › Baixar suas informações › Seguidores e seguindo, formato HTML; arquivo `followers_1.html`). Cada extração vira `relatorios/instagram/seguidores/AAAA-MM-DD.txt` e é comparada com a anterior. Base inicial: `2026-10-28.txt` (88 seguidores, extraída de capturas de tela).

## Padrão de marca

Conteúdo segue o sistema de design **Padrão** da Tonello & Siqueira: navy `#194E7C` /
bronze `#B0863C`, serifa de sistema (Georgia) nos títulos e corpo, sans de sistema em
caixa-alta nos rótulos. Voz institucional no plural ("nós"), sem emoji, sem exclamações.
Ver `_ds/` ou o repositório do design system para referência completa.
