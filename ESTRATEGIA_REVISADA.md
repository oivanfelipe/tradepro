# TradePRO: estratégia revisada (06/11/2026)

> **Plano. Nada foi executado em conta.** Substitui, onde houver conflito, a sequência e a verba dos documentos anteriores (`ANALISE_TRADEPRO.md` seções 0.6, 0.7 e 0.11, e `ESTRUTURA_CONTEUDO_POS_DOWNLOAD.md`, que passa a ser a **fase 2**).
> Hipóteses estão marcadas. Onde há número sem fonte, é meu e deve ser validado.

## 1. A lógica

O objetivo não é gerar lead agora. É **formar um público qualificado para o pixel trabalhar**, e só então converter esse público em lead mais barato.

```
Blog (1º) ──► Público qualificado (pixel) ──► Remarketing Meta ──► Ebook (conteúdo-gatilho) ──► CRM (RD) ──► Comercial
   ▲                  ▲
   │                  └── quem viu os vídeos de produto no Meta
Demand Gen (piso) + LinkedIn orgânico + Meta (vídeos de produto)
```

| Etapa | O que faz | Por que nessa ordem |
|---|---|---|
| **Blog** | Valida o tema, o tom e o custo por visita qualificada | Mais rápido e fácil de produzir que o ebook; dá resposta enquanto o ebook é construído |
| **Público pixel** | Guarda quem leu e quem viu vídeo, por tema | É o ativo que torna o remarketing e o lookalike possíveis |
| **Remarketing Meta** | Fala com quem já demonstrou interesse | Público quente tende a custar menos por lead que o frio **(hipótese a medir)** |
| **Ebook** | Conteúdo-gatilho que leva o público quente ao CRM | Barateia o CPL da conta; leva mais tempo, então corre em paralelo |
| **Meta, conteúdo de produto** | Cria demanda nova no público frio e alimenta o público pixel | Os vídeos de produto são o único ativo já pronto |

## 2. Sequência

| Fase | Quando | O que entra |
|---|---|---|
| **1. Blog e público** | Semanas 1 a 4 | Medição, blog (1 post por semana), LinkedIn orgânico, Demand Gen no piso, Meta limpo, vídeos |
| **2. Ebook e remarketing** | Mês 2 | Ebook 1 no ar (LP do ebook), remarketing por público, pós-download |
| **3. Decisão** | Dia 60 | Custo por MQL decide a verba |

## 3. Demand Gen no piso (correção minha)

- **Piso do Google:** US$ 5 por dia por campanha ([ppc.land](https://ppc.land/google-to-enforce-5-minimum-daily-budget-on-demand-gen-campaigns-from-april/)). Pela cotação de ~R$ 5,4 (aproximada, confira), são ~R$ 27. **Usar R$ 30 por dia (~R$ 900 por mês).**
- **Por que isso se sustenta:** a recomendação do Google de US$ 100 por dia ([Google, boas práticas](https://support.google.com/google-ads/answer/14693848)) vale para **lance por conversão**. O objetivo aqui é **tráfego qualificado para formar público**, com lance por cliques. Eu estava aplicando a régua errada.
- **O que esperar:** no piso, a entrega pode oscilar e o Google aprende menos. Por isso o critério é medir toda semana o custo por visita qualificada, e não otimizar por conversão.
- **Configuração:** anúncio de vídeo ou imagem que leva ao blog post; públicos por palavras-chave e URLs de concorrentes; excluir clientes e leads; lance por cliques.
- **Medir:** custo por visita qualificada, % de visitas qualificadas, tamanho do público formado, crescimento da busca de marca.

## 4. Blog

**Cadência:** 1 post por semana nas 4 primeiras semanas, depois 1 por quinzena. A V4 escreve; a TradePRO valida em até 2 dias úteis (sem isso o ritmo quebra).

**Pautas das 4 primeiras semanas** (as mesmas dos ebooks, em versão curta):
1. Ruptura: o problema começa antes da gôndola vazia.
2. 5 sinais de que sua operação de campo perdeu visibilidade.
3. O ERP organiza o negócio. E a ponta?
4. Planilha ou plataforma: quando migrar.

**CTA enquanto o ebook não existe:** "Ver como funciona" (página intermediária com o vídeo) e uma **lista de espera do ebook** (formulário curto no RD). A lista de espera já alimenta o CRM antes do lançamento.

**Cada post** leva um vídeo (corte de P1, P2 etc.), para o mesmo conteúdo gerar também público de quem viu o vídeo.

## 5. LinkedIn orgânico

- Conteúdo rico (carrosséis, posts analíticos, trechos dos artigos), 2 a 3 por semana, sempre com link para o blog e UTM.
- Tom do Manual: "visibilidade", sem "controle".
- A ferramenta de medição (tag do LinkedIn) só coleta público para uso futuro; **não implica anúncio no LinkedIn.**

## 6. Meta: produto + público

| Frente | O que faz | Objetivo |
|---|---|---|
| **Topo: vídeos de produto** | P1, P2, P6 para o ICP, sem Audience Network, 28–55 anos | Demanda nova e público de quem viu o vídeo |
| **Remarketing (a partir do mês 2)** | Visitantes do blog por tema + quem viu 50%+ do vídeo + engajou IG e FB | Levar ao ebook e à demonstração |
| **Ebook** | Anúncio para o público quente | Lead barato no CRM |

Os públicos já existentes ("Visitantes site/LP 30d", "Engajou IG 90d") têm tráfego lixo do Audience Network dentro; o remarketing deve ser refeito com público limpo (10+ s ou 50% de scroll).

## 7. Pixel: eventos e públicos

| Evento | Quando dispara | Público gerado |
|---|---|---|
| **Visita qualificada** | 10+ segundos **ou** 50% de scroll no blog | Quem realmente leu |
| **Leitura recorrente** | 2+ posts em 30 dias | Interesse mais alto |
| **Tema lido** (parâmetro por post) | Ruptura, 5 sinais, ERP, planilha | Mensagem por tema no remarketing |
| **Vídeo 50% e 75%** | ThruPlay parcial | Quem viu o produto |
| **Lista de espera / download** | Formulário do RD | Lead no CRM (excluir do remarketing) |

Sem esses eventos, o blog gera visita, mas não gera público utilizável. Os mesmos eventos alimentam GA4 e Google Ads (listas de remarketing).

## 8. Verba

| | Mês 1 (R$ 3,0 mil) | Mês 2 (R$ 4,5 mil, se o portão 2 fechar) |
|---|---|---|
| Google Search | R$ 1,5 mil | R$ 1,6 mil |
| Demand Gen (piso) | R$ 0,9 mil | R$ 0,9 mil |
| Meta | R$ 0,6 mil | R$ 2,0 mil |

**Ponto de atenção:** em outubro o Google foi a **única** fonte de MQL (4 de 4). O mês 1 corta o Search de R$ 2,0 mil para R$ 1,5 mil. Para proteger, mantenha a marca (R$ 250), concentre o resto em Distribuidores e dor, e **pause os concorrentes** (R$ 190 sem resultado). O Meta cai de R$ 1,0 mil para R$ 0,6 mil, mas o Meta teve 0 MQL e boa parte do gasto foi tráfego lixo.

## 9. Medição e portões

| Portão | Quando | O que precisa ser verdade |
|---|---|---|
| **1** | Fim da semana 2 | Rastreio validado (WhatsApp, evento de visita qualificada, UTM) e 1º post no ar |
| **2** | Fim da semana 4 | Público qualificado formado: **meta de ~1.000 pessoas (hipótese)** para remarketing com folga; a Meta aceita 100, mas a entrega é melhor acima disso |
| **3** | Dia 60 | Ebook no ar e custo por MQL medido, **com CPL do público quente contra o do frio** |

**Indicadores do blog (fase 1):** visitas qualificadas, custo por visita qualificada, tamanho do público (30, 60 e 90 dias), % de leitura recorrente, engajamento por tema.
**Expectativa:** com R$ 30 por dia no Demand Gen mais o orgânico, o público de 1.000 pessoas deve levar ~60 dias **(hipótese; depende do CPC real, que ainda não temos)**. Antes disso, o remarketing roda só com o que já existe (engajados de Instagram e Facebook, vídeo).

## 10. Ações revisadas (21)

| # | Ação | Fase | Quem |
|---|---|---|---|
| 1 | Corrigir a saída para o WhatsApp (site, blog, LPs, ebook) | 1 | V4, TradePRO fornece número |
| 2 | Registrar o formulário do RD (lista de espera e ebook) como conversão no Google, Meta e GA4 | 1 | V4 |
| 3 | UTM padrão em anúncios, e-mails, LinkedIn e blog | 1 | V4 |
| 4 | MQL do RD como conversão no Google Ads | 1 | V4 |
| 5 | LP do ebook (modelo e 2 temas) | 2 | V4 |
| 6 | "Ver como funciona" (vídeo e 3 casos) | 1 | V4 |
| 7 | Ajustar a LP Promoter (Distribuidores, seção Enterprise) | 1 | V4, TradePRO valida |
| 8 | LP Lite sem preço | 2 | V4, TradePRO valida |
| 9 | Blog: CTA, lista de espera e evento de visita qualificada (pixel e GA4) | 1 | V4 |
| 10 | Produzir os ebooks 1 e 2 (lançar o 1 no mês 2) | 1 a 2 | V4 produz, TradePRO valida |
| 11 | Posts do blog (1 por semana por 4 semanas) | 1 | V4 produz, TradePRO valida |
| 12 | Vídeos P1, P2 e L1, com telas reais | 1 | V4 grava, TradePRO fornece as telas |
| 13 | Peças do pós-download (trilhas Promoter, Lite e leve) | 2 | V4, TradePRO valida |
| 14 | Autorizar os 3 depoimentos | 1 | TradePRO |
| 15 | Meta: higiene, vídeos de produto no topo e remarketing do público | 1 a 2 | V4 |
| 16 | Google Search: negativas, Distribuidores, separar Lite, pausar concorrentes | 1 | V4 |
| 17 | Demand Gen no piso (~R$ 30/dia), lance por cliques, para o blog | 1 | V4 |
| 18 | WhatsApp do comercial no CRM, com próxima ação e data | 1 | TradePRO |
| 19 | MQL e SQL no RD CRM (download não é MQL) | 1 | TradePRO, V4 apoia |
| **20** | **LinkedIn orgânico: conteúdo rico (2 a 3 por semana) que leva ao blog** | 1 | V4 |
| **21** | **Públicos qualificados (Meta e Google) por tema, com exclusão de leads e clientes** | 1 a 2 | V4 |

## 11. Riscos

1. **Verba:** o Search perde R$ 0,5 mil por mês, e ele é a única fonte de MQL. Se o MQL cair, a fase 1 sai mais cara do que parece.
2. **Piso do Demand Gen:** entrega instável e pouco aprendizado. Se o custo por visita qualificada ficar alto na semana 3, cortar.
3. **Amostra:** um público de ~1.000 pessoas em 60 dias é uma estimativa, não um fato. Se o CPC real for maior, o prazo estica.
4. **Blog sem CTA forte:** sem o ebook, o post depende de "Ver como funciona" e da lista de espera. Se a lista de espera não converter, o público forma, mas o CRM não cresce até o ebook.
5. **Validação da TradePRO:** um post por semana exige resposta rápida. Sem isso, o blog não valida nada.
6. **Remarketing contaminado:** se os públicos antigos (com Audience Network) forem reaproveitados, o remarketing repete o desperdício.
