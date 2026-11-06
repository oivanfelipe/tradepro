# TradePRO: estrutura da estratégia (06/11/2026)

> **Só a estrutura, sem valores.** Verba, lance, janelas de público, tamanhos, metas, critérios de portão e cadência ficam com o gestor de tráfego (GT), que valida.
> **Plano. Nada foi executado em conta.** Substitui, onde houver conflito, a sequência dos documentos anteriores. O `ESTRUTURA_CONTEUDO_POS_DOWNLOAD.md` descreve a régua da fase 2.

## 1. A lógica

O objetivo é **criar público qualificado** para trabalhar no remarketing e no Meta. Três jornadas rodam para formar esse público. O ebook é **outra estratégia** (geração de leads), numa **segunda fase**, depois de validar o Demand Gen.

```
JORNADA SEARCH + PMAX   Google Search + PMax ─► LPs por produto ─► Conversão (RD / WhatsApp) ─► Comercial ─► SQL

JORNADA DEMAND GEN      LinkedIn orgânico (teste) ─┐
                        Demand Gen ────────────────┴─► Blog estratégico ─┬─► CTA ─► Pré-form RD ─► WhatsApp do comercial
                                                                          └─► Público do pixel ─┐
JORNADA META            Vídeos novos de produto ─► Meta topo (ICP) ─► Público do pixel ───────┴─► Meta: conteúdos (remarketing)

FASE 2 (depois de validar o Demand Gen)
                        Ebook ─► Campanha de leads (Meta, público quente) ─► LP do ebook ─► CRM RD + régua ─► Comercial
```

## 2. As jornadas

### Jornada 1: Search + PMax → LPs por produto
- **Origem:** Google Search (marca, distribuidores, dores do campo) e PMax por produto.
- **Destino:** uma LP por produto (Promoter, versão Distribuidores; Lite, sem preço; Enterprise, a confirmar se tem LP própria).
- **Conversão:** formulário do RD ou WhatsApp, que leva ao contato do comercial, ao Discovery e ao SQL.
- **PMax** entra depois do rastreio validado (condição já definida no planejamento).
- O Lite fica fora do funil do Promoter.

### Jornada 2: Meta com vídeos novos
- **Vídeos novos de produto** (P1, P2, L1 e demais), com telas reais, no topo para o ICP, sem Audience Network.
- Quem viu o vídeo entra no **público do pixel**.
- O Meta entrega **conteúdos** (remarketing) a quem leu o blog ou viu o vídeo.

### Jornada 3: Demand Gen → blog estratégico → WhatsApp
- **Demand Gen** na verba mínima da plataforma, com o objetivo de levar tráfego qualificado ao blog e formar público.
- **LinkedIn orgânico** é um **teste do blog post**: conteúdo rico que leva ao blog, com UTM.
- **Blog:** posts estratégicos no site, sem cadência fixa, com **CTA para o WhatsApp via pré-formulário do RD**. A V4 produz, a TradePRO valida.
- O blog também forma o **público do pixel**: quem leu **já começa a receber conteúdo no Meta**.

### Fase 2: ebook + campanha de leads + régua
- **Quando:** depois de validar o Demand Gen.
- **O que é:** ebook (conteúdo-gatilho), campanha de geração de leads para o público quente no Meta, LP do ebook com formulário do RD, e a régua de CRM (trilhas por perfil).
- **Para quê:** alimentar o CRM e baratear o CPL da conta.
- O ebook pode ser produzido em paralelo, porque leva mais tempo.

## 3. Pixel: eventos e públicos

| Evento | Para que serve |
|---|---|
| Visita qualificada (critério definido pelo GT) | Separar quem leu de quem só passou |
| Tema lido (parâmetro por post) | Conteúdo no Meta por tema |
| Vídeo visto (parciais) | Público de quem viu o produto |
| Pré-formulário do RD (e, na fase 2, download) | Lead no CRM (excluir do remarketing) |

Os mesmos eventos alimentam o GA4 e as listas do Google Ads. Público antigo do Meta tem tráfego do Audience Network; refazer com público limpo.

## 4. Etapas e portões

| Etapa | O que entra |
|---|---|
| **1. Base** | WhatsApp com pré-formulário, conversão do RD, UTM |
| **2. Jornadas no ar** | MQL do RD no Google, eventos e públicos; Search e LPs; PMax; vídeos e conteúdos no Meta; blog, Demand Gen e LinkedIn |
| **3. Validação** | Validar o Demand Gen |
| **4. Fase 2** | Campanha de leads e régua de CRM |

**Portões:** (1) rastreio validado; (2) público qualificado formado; (3) Demand Gen validado libera a fase 2.

## 5. Para o GT validar

1. Verba por jornada e o piso do Demand Gen.
2. Entrada do PMax e a estrutura por produto.
3. Lance do Demand Gen: cliques ou conversão.
4. Janelas e tamanho mínimo dos públicos.
5. Critério de visita qualificada e eventos do pixel.
6. Exclusões (leads e clientes) e frequência do remarketing.
7. Critérios para validar o Demand Gen e liberar a fase 2.

## 6. Ações (22)

| # | Ação | Jornada | Quem |
|---|---|---|---|
| 1 | Corrigir a saída para o WhatsApp, com pré-formulário do RD | Base | V4, TradePRO fornece número |
| 2 | Formulário do RD como conversão no Google, Meta e GA4 | Base | V4 |
| 3 | UTM padrão em anúncios, LinkedIn, blog e e-mails | Base | V4 |
| 4 | MQL do RD como conversão no Google Ads | Base | V4 |
| 5 | Eventos do pixel e públicos por tema | Base | V4 |
| 6 | LP Promoter (versão Distribuidores) | Search + PMax | V4, TradePRO valida |
| 7 | LP Lite sem preço | Search + PMax | V4, TradePRO valida |
| 8 | LP Enterprise (a confirmar) | Search + PMax | V4, TradePRO valida |
| 9 | Search: negativas, Distribuidores, separar Lite, pausar concorrentes | Search + PMax | V4 |
| 10 | PMax por produto, depois do rastreio validado | Search + PMax | V4 |
| 11 | Vídeos novos de produto, com telas reais | Meta | V4 grava, TradePRO fornece as telas |
| 12 | Meta: higiene e vídeos no topo | Meta | V4 |
| 13 | Meta: conteúdos para quem leu ou viu | Meta | V4 |
| 14 | Autorizar os 3 depoimentos | Meta | TradePRO |
| 15 | Blog estratégico: CTA para WhatsApp com pré-formulário e evento de visita qualificada | Demand Gen | V4 produz, TradePRO valida |
| 16 | Demand Gen na verba mínima, para o blog | Demand Gen | V4 |
| 17 | LinkedIn orgânico: teste do blog post | Demand Gen | V4 |
| 18 | WhatsApp do comercial no CRM, com próxima ação e data | Comercial | TradePRO |
| 19 | MQL e SQL no RD CRM (download não é MQL) | Comercial | TradePRO, V4 apoia |
| 20 | Ebooks (produção) e LP do ebook | Fase 2 | V4 produz, TradePRO valida |
| 21 | Campanha de geração de leads (Meta, público quente) | Fase 2 | V4 |
| 22 | Régua de CRM pós-download (trilhas por perfil) | Fase 2 | V4, TradePRO valida |

## 7. Riscos

1. **Search como única fonte de MQL hoje.** Qualquer redistribuição de verba pode reduzir o MQL; o GT decide.
2. **PMax antes do rastreio** repetiria o problema do histórico (conversões sem origem no CRM). Por isso entra depois do portão 1.
3. **Demand Gen na verba mínima:** entrega instável e pouco aprendizado; avaliar custo por visita qualificada.
4. **Blog sem ebook:** o CTA depende do WhatsApp e do pré-formulário. Se não converter, o público forma, mas o CRM não cresce até a fase 2.
5. **Validação da TradePRO** dos posts: sem resposta rápida, o blog não valida nada.
6. **Públicos contaminados:** reaproveitar os antigos repete o desperdício do Audience Network.
