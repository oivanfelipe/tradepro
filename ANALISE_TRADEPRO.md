# TradePRO — Análise completa e plano de ação (nov/2026)

> **Limites desta análise**
> - **Meta Ads:** a conta `538172087220579` (nome no Windsor: "MobileSys Anuncios", campanhas com prefixo [TP]) foi autorizada e os dados reais estão na seção **0 (Atualização de 05/11)**. As seções 1–7 foram escritas antes disso. Onde houver conflito, vale a seção 0.
> - **Google, GA4, Search Console e RD Station:** continuam fora do Windsor. Google segue só pelos prints.
> - **Google Ads:** análise feita só pelos prints (4 campanhas, período não informado, provavelmente desde a reestruturação de 13/10).
> - **LP:** li o texto extraído. Não medi velocidade, não vi o layout e não testei rastreamento.
> - Onde há benchmark de mercado ou hipótese minha, está marcado como **(hipótese)**.

---

## 0. Atualização de 05/11: dados reais do Meta e respostas do cliente

**Período:** 01/10 a 05/11 (Google, prints) e as campanhas Meta ativas desde 09/10. Fonte Meta: Windsor.

### 0.1 Verba real
| | Gasto | Por dia | Leads | Custo por lead |
|---|---|---|---|---|
| Google (4 campanhas, 36 dias) | R$ 2.236 | R$ 62 | 3 (MQL, todos na marca) | R$ 745 (marca: R$ 94) |
| Meta (3 campanhas, desde 09/10) | R$ 1.189 | R$ 42 | 7 | R$ 170 |
| **Total** | **R$ 3.425** | **R$ 95 (~R$ 2,9 mil/mês)** | **10** | **R$ 343** |

Correção minha: a verba real (~R$ 2,9 mil/mês) bate com o plano de R$ 3 mil. Eu havia lido só o Google (~R$ 2 mil) e achado a verba baixa demais. A divisão real é ~65% Google / 35% Meta.

### 0.2 Meta por campanha (desde 01/10)
| Campanha | Gasto | Impr. | Cliques | LPV | Leads | Custo/lead |
|---|---|---|---|---|---|---|
| [LEADS][LP][Promoter] 09/10 | R$ 734 | 31.147 | 2.378 | 1.530 | 2 | R$ 367 |
| [LEADS][RMK][Vídeos] 14/10 | R$ 195 | 5.501 | 346 | 210 | 0 | — |
| [LEADS][FORM][SUPERMINAS] 20/10 | R$ 260 | 6.821 | 138 | n/a | 5 | R$ 52 |

### 0.3 O que os dados mostram
1. **A campanha de LP está inflada por tráfego lixo do Audience Network.** Só o *rewarded video* teve 3.329 impressões, **1.159 cliques (CTR 35%, CPC R$ 0,04)** e 784 LPV, **0 leads**. Somando o *an_classic*, o Audience Network gerou **61% dos cliques e 62% dos LPV com 13% da verba, e nenhum lead**. Cliques de anúncio de recompensa dentro de jogos são, em geral, acidentais **(hipótese; confirmar pelo tempo de permanência na LP)**. Sem o Audience Network sobram 926 cliques, 588 LPV e 2 leads (0,34% LPV→lead).
2. **O algoritmo foi para o clique barato.** A campanha otimiza para "lead pixel" com apenas 2 eventos. Com tão pouco sinal, a Meta busca o clique mais barato. A tendência confirma: a verba diária caiu de R$ 55–78 (11–14/10) para R$ 5–20 no fim de outubro, enquanto o CPC caiu para R$ 0,08 e o CTR passou de 20%.
3. **O público segmentado por cargo (Trade/Merchandising/Supervisor de Vendas/Gerente Comercial) tem 0 leads** em R$ 207 e 536 LPV. O público aberto Advantage+ teve os 2 leads (anúncio "VD Avatar 30s", R$ 99 por lead), mas também é onde o Audience Network concentra cliques. **Amostra pequena demais para escolher público.**
4. **O remarketing está contaminado.** O público "Visitantes site/LP 30d" inclui o tráfego lixo, e o alcance é de ~4,4 mil pessoas. R$ 195, 0 leads.
5. **O formulário nativo com geolocalização foi o melhor da conta:** o anúncio "Superminas Vídeo 1" no raio de 40 km da Expominas (20–26/10) trouxe **5 leads com R$ 101, ou R$ 20 por lead**. Nos dias do evento (raio 5 km, R$ 115) e no remarketing (R$ 40), **0 leads**. Em 2026, APAS ([LEAD], R$ 291) deu 4 leads a R$ 73 cada. **Evento + formulário nativo + região converte a custo bem menor que LP fria (R$ 367).** Falta saber a qualidade desses leads (SuperMinas é evento de supermercado/varejo, não de distribuidor).
6. **Todo o histórico 2026 da conta:** R$ 6.595 em 18 campanhas, 12 leads (R$ 550 por lead), 10.724 cliques e 2,06 milhões de impressões.

### 0.4 Diagnóstico da LP, agora com duas fontes
Tráfego "frio" real, sem Audience Network: 588 LPV (Meta) + 376 cliques (Google não-marca) = ~964 visitas, **2 leads**. **Conversão ~0,2%.** Benchmark de LP B2B de demonstração: 1–3% **(hipótese)**. Dois canais diferentes, o mesmo resultado, em audiências distintas. Isso aponta para a **LP/oferta (ou para o rastreio)**, não para um canal. O que contraria: os 3 leads da marca (MQL) convertem na mesma LP, mas são pessoas que já conhecem a TradePRO.

### 0.5 Respostas do cliente e o que mudam
| Resposta | Efeito |
|---|---|
| Os 3 leads do Google **viraram MQL** | A marca é a única fonte validada: 3 MQL a R$ 94. Mas não escala (160 cliques/mês). |
| Período: 01/10 a hoje | Confirmado nas contas acima. |
| "Demand Gen" = **campanha do Google** | Ver 0.7. |
| Verba: "pode sugerir" | Ver 0.6. |
| Meta de clientes: "calcule" | Ver 0.6. |
| Vídeos: "podemos gravar" | Ver 0.8. Já existem vídeos na conta (Avatar 30s, Rogério 18s, 2m19, 4m15); falta demonstração por caso de uso. |

### 0.6 Meta de clientes e verba, calculadas com os dados
**Linha de base:** ~8,3 leads/mês (10 leads em 36 dias) a R$ 343 cada, com R$ 2,9 mil/mês. Sem o funil do RD, uso 5%, 8% e 12% de MQL→cliente **(hipóteses de B2B consultivo; trocar pelo real)**:

| MQL→cliente | Clientes/mês hoje | CAC | MRR novo/mês |
|---|---|---|---|
| 5% | 0,4 | R$ 6,9 mil | R$ 1,1 mil |
| 8% | 0,7 | R$ 4,3 mil | R$ 1,7 mil |
| 12% | 1,0 | R$ 2,9 mil | R$ 2,6 mil |

**Correção de uma leitura anterior:** eu tratei um CAC de R$ 15–25 mil como alarmante. Com ticket de R$ 2.550/mês e o churn simulado de 15% a.a. do planejamento (o real não está medido), o LTV de receita é ~R$ 200 mil. Até R$ 10 mil de CAC (~4 meses de receita) é saudável. **O gargalo é volume e caixa, não unit economics.**

**Para 3 clientes/mês** (cenário do planejamento) são ~38 MQL/mês a 8%. A R$ 343 de CPL seriam R$ 12,9 mil/mês; a R$ 150, R$ 5,6 mil/mês.

**Meta sugerida para o dia 90:**
- **25 MQL/mês com CPL ≤ R$ 180** → R$ 4,5 mil/mês
- Isso rende **1,3 a 3 clientes/mês** (5% a 12%), MRR novo de R$ 3,2 a 7,7 mil/mês
- Guarda-corpo: CAC ≤ R$ 10 mil
- Exige cortar o desperdício (Audience Network, termos amplos do Google) e corrigir a LP, não só aumentar verba

**Verba sugerida:** manter ~R$ 3 mil no mês 1 (realocada, sem dinheiro novo); subir para **R$ 4,5 mil** no mês 2 **se** os gates do mês 1 forem batidos (rastreio validado + custo por MQL ≤ R$ 250); só chegar a R$ 6 mil no mês 3 com dados de MQL→SQL.

| Frente (R$ 4,5 mil) | R$/mês | % |
|---|---|---|
| Google Search (marca 250 + Distribuidores 700 + Dor/Solução refinada 750) | 1.700 | 38% |
| Meta: TOF + vídeo sem Audience Network (700), formulário nativo/eventos (400), remarketing (250), ativo pilar (250) | 1.600 | 36% |
| Google Demand Gen (a partir do mês 2) | 600 | 13% |
| Reserva de teste (evento regional, LinkedIn micro) | 600 | 13% |
| Concorrentes | 0 (pausar) | — |

### 0.7 Demand Gen do Google: validação
**Vale como teste do mês 2, não como aposta agora.**
- **A favor:** cria demanda fora da busca (YouTube, Discover, Gmail), aceita **segmentos personalizados** por palavras-chave e URLs de concorrentes (público com intenção de busca sem a limitação de volume do Search) e **Customer Match** da base. A marca é o que converte, então qualquer coisa que aumente a busca de marca é positiva.
- **Contra:** a verba é pequena, o rastreio ainda não é confiável e o histórico de vídeo no Google foi R$ 17 mil sem lead, porque era CPM de destino. Sem ~30 conversões/mês não há lance por conversão estável.
- **Como testar:** R$ 20/dia (R$ 600/mês), 2 vídeos + 2 imagens, lance de maximizar cliques, depois conversões. Segmentos: (1) pesquisaram "software/sistema de trade marketing", "gestão de promotores", "controle de ruptura" e (2) URLs de Involves, MáximaTech, PDV Mundo. Excluir clientes e leads.
- **Métrica de sucesso:** não é lead direto. É custo por LPV ≤ R$ 1,50, **crescimento semanal de impressões e cliques da busca de marca** e conversões assistidas.
- **Pré-requisito:** rastreio validado e o Meta já limpo.

### 0.8 Vídeos de demonstração (a gravar)
Roteiros por caso de uso, 60–90 s, tela do produto + voz, sem apresentação institucional:
1. **Ruptura em tempo real:** do alerta no campo ao painel do gestor (hook: "Quanto tempo leva para você saber que faltou produto na loja?").
2. **Planejado × realizado:** roteiro de visitas e check-in com geolocalização.
3. **Foto como evidência:** comprovação de execução sem WhatsApp.
4. **Validade e preço:** coleta estruturada no PDV.
5. **Integração Sankhya/WinThor:** do ERP para o campo e de volta.

Usar cada um (a) na LP, (b) no Meta TOF, (c) no WhatsApp da SDR e (d) no LinkedIn orgânico. Gravar numa única sessão de ~3 h com a equipe de implantação.

### 0.9 Ações imediatas (aguardam sua aprovação; não alterei nenhuma conta)
**Meta**
1. Excluir **Audience Network** (e *rewarded video*) de todas as campanhas.
2. Trocar a otimização da campanha de LP: de "lead pixel" (2 eventos) para visita à LP ou, melhor, **formulário nativo com WhatsApp**, que já deu R$ 20–73 por lead.
3. Refazer o remarketing: excluir o tráfego lixo, usar quem assistiu 50%+ do vídeo.
4. Replicar o modelo "evento + região + formulário nativo" para o calendário de feiras de **distribuidores** (ABAD, APAS), não de varejo.
5. Validar no RD a qualidade dos 5 leads do SuperMinas antes de repetir.

**Google**
1. Relatório de termos de pesquisa + lista de negativas; reduzir "solução trade marketing" e "merchandising".
2. Pausar "involves stage"; criar a campanha Distribuidores; tirar "app para promotores" do funil de demo.

**LP**
1. Formulário curto, vídeo no hero, WhatsApp fixo, LP por tema.

**Medição**
1. Exportar do RD os 10 leads de outubro (origem, etapa, MQL/SQL, motivo de perda) e o histórico de MQL→SQL→venda dos últimos 6 meses.

---

## 1. O cliente

**TradePRO Tecnologia:** SaaS de gestão de equipes de campo e execução no PDV. Tem 15+ anos de mercado, 25 mil usuários e receita recorrente. Ticket de referência: ~R$ 2.550/mês (ARR ~R$ 30,6 mil por cliente).

| Produto | Papel | Motion |
|---|---|---|
| **Promoter** | Motor principal: visitas, rotas, ruptura, validade, preço, fotos, dashboards, integração Sankhya/WinThor | Consultivo (discovery → demo → proposta) |
| **Lite** | Porta de entrada, até ~10 usuários | Low-touch / SDR IA |
| **Enterprise** | Promoter com comitê maior e validação técnica | High-touch |
| Freelance, Sales, Shop | Ecossistema, hoje fora do foco | — |

**Tese do planejamento:** Promoter no centro, distribuidores e atacadistas médios como beachhead, Lite como entrada, e **medir antes de escalar**.

**ICP prioritário:** distribuidores/atacadistas médios de alimentos, bebidas, cosméticos e higiene. Têm equipe de campo recorrente, vários PDVs, ERP ou planilha, e dor de ruptura, validade e produtividade. Prioridade seguinte: agências de trade, depois indústrias.

**Comitê de compra** (cada papel precisa de um argumento diferente):

| Papel | Quer | Teme |
|---|---|---|
| Gestor de Trade (champion) | Visibilidade da execução | Baixa adesão |
| Diretor Comercial (decisor) | ROI, produtividade | Investimento sem retorno |
| TI | Integração, segurança | Complexidade |
| Financeiro | Previsibilidade | Custos ocultos |
| Promotor (usuário) | App simples | App complexo (vira bloqueador) |

**Concorrência:**
- **Involves:** enterprise, forte em IA e Perfect Store, com 19 anúncios Google e 11 Meta.
- **MáximaTech:** dono do atacado-distribuidor, com 96 anúncios Google e zero Meta.
- **PDV Mundo:** intermediário.
- **PDV Info:** entrada, vende "sem fidelidade e com teste grátis".

A TradePRO fica no meio: robustez + proximidade + implantação. Ela tem lacunas em IA, em provas quantitativas públicas e em clareza de posicionamento.

## 2. As ações conectam com a estratégia?

**Onde conecta**
- Os 4 grupos de palavras-chave (Software Trade Marketing, Gestão de Promotores, Execução/Merchandising no PDV, Ruptura e Validade) espelham as dores do ICP e o plano de Search.
- A LP usa a mensagem-mãe ("execução → dado → decisão") e o tom certo: sem "fiscalização" e sem exagero.
- O Search foi escolhido corretamente como primeiro canal, porque 72% das conversões históricas vieram dele.

**Onde não conecta**

| # | Desconexão | Evidência |
|---|---|---|
| 1 | **Não existe campanha de Distribuidores**, mesmo sendo o beachhead e a campanha nº 3 do plano. | Os prints mostram só Solução, Marca, Concorrentes e uma campanha pausada. |
| 2 | **A LP fala com 3 públicos ao mesmo tempo** ("distribuidores, indústrias e agências"), contra a tese de foco em distribuidor. | Texto da LP. |
| 3 | **Uma LP só para 4 temas.** Muitos termos têm IQ 2–4 (merchandising, auditoria de pdv, execução, ruptura no pdv, controle de promotores). | Prints. |
| 4 | **Lite e Promoter estão misturados.** "app/aplicativo para promotores" são ~41 cliques de baixo custo e baixa intenção. É cara de Lite, mas cai no funil de demo consultiva do Promoter. | Prints. |
| 5 | **O único CTA é "agendar demo".** Não há trial, preço, vídeo nem material intermediário. Só ~5% do mercado está pronto para comprar agora. | LP. |
| 6 | **Persona não aparece na mídia.** Não há criativo para o champion (Trade) nem para o decisor (Comercial). | Criativos 01–03 são genéricos "sua equipe está no PDV". |
| 7 | **Plano, budget e forecast não batem.** Plano diz R$ 3 mil/mês, diagnóstico diz R$ 5 mil, os daily budgets somam ~R$ 66,7/dia (~R$ 2 mil/mês). O Forecasting Inside Sales está **zerado**. | PDFs, prints, planilha. |
| 8 | **O Meta foi definido como "suporte" (R$ 900)** e agora a hipótese é torná-lo principal. É uma mudança de estratégia que precisa ser decidida de forma explícita. | Planejamento, bloco 6. |

## 3. Resultados (Google Ads, prints)

| Campanha | Invest. | Cliques | CTR | CPC | Conv. | Status |
|---|---|---|---|---|---|---|
| [LP][MQL] Soluções Trade Marketing | R$ 1.716 | 376 | 6,6% | R$ 4,56 | **0** | Ativa |
| [MARCA] TradePRO | R$ 283 | 160 | 21,2% | R$ 1,77 | **3** | Ativa |
| [CONCORRENTES] Teste | R$ 194 | 54 | 7,5% | R$ 3,60 | **0** | Ativa |
| [SEARCH LEADS][LP] | R$ 42 | 32 | 12,7% | R$ 1,32 | 0 | Pausada |
| **Total** | **R$ 2.236** | **622** | | | **3** | |

### Leitura

1. **100% das conversões vieram da marca**, que consome 12,7% da verba. As 3 conversões foram em `[trade pro]`. Quem converte é quem já conhece a TradePRO. Isso apoia a sua tese: SaaS pouco conhecido não converte por busca fria.
2. **Zero conversão em 376 cliques não-marca.** Com 0 de 376, a taxa de conversão real da LP nessa campanha é provavelmente **abaixo de ~1%** (regra dos três: limite superior ≈ 0,8%). Se fosse 2%, a chance de ver 0 seria ~0,05%. Duas explicações possíveis: a LP converte mal para tráfego frio, ou o rastreamento falha. O diagnóstico já alertava que "Enviar formulário de lead" tinha problema. **Preciso separar essas duas antes de qualquer conclusão.**
3. **Concentração de gasto:** 8 palavras fazem 80% do investimento da campanha de Solução. Só "solução trade marketing" é 30% (R$ 521, CPC R$ 4,61). "Solução" é um termo amplo e atrai quem busca consultoria ou agência. "merchandising no pdv", IQ 3, é a 2ª maior (R$ 222), e merchandising atrai vaga de emprego, agência e curso. Isso é **hipótese; falta o relatório de termos de pesquisa para confirmar.**
4. **O universo de busca é minúsculo.** Só ~5,7 mil impressões não-marca no período, e ~30 das 69 palavras têm menos de 10 impressões. Search captura demanda que existe, e aqui ela é pequena. Mesmo com orçamento ilimitado, o teto de volume é baixo.
5. **Concorrentes:** "involves stage" gastou R$ 121 (62% da campanha) com IQ 1. Quem busca "involves stage" costuma ser cliente procurando login ou suporte. Todos os termos têm IQ 1.
6. **Marca:** CPC de R$ 1,54–1,77 em busca exata da própria marca é alto. **(hipótese)** há concorrente leiloando "tradepro". Verificar em Informações do leilão.
7. **Rastreamento:** a coluna "Rastreados" é 0 na campanha principal e 3 na de marca. Sem o ciclo campanha → RD Station → venda, não dá para dizer o que é bom.

### A conta que não fecha

O forecast do planejamento diz: R$ 3 mil/mês → CPA R$ 800 → 3 clientes/mês. Ele parece tratar **custo por lead** como **custo por cliente**. Com os dados reais:

- Custo por conversão atual (blended): **R$ 745**. Só na marca: **R$ 94**.
- Se 3–5% dos leads virarem cliente **(hipótese de B2B consultivo)**, o CAC fica em **R$ 15–25 mil**.
- Com R$ 2.236 investidos você tem ~3 leads, ou **0,1–0,15 cliente**.
- Para 3 clientes/mês seriam ~60–100 leads/mês. A R$ 300 de CPL, são **R$ 18–30 mil/mês**.

**Verba e meta estão desalinhadas em uma ordem de grandeza.** Antes de qualquer tática, é preciso resolver isso, seja subindo verba, baixando a meta de mídia ou assumindo outros canais (indicação, outbound, eventos) como motor principal.

Teto de CPL tolerável para CAC de R$ 10 mil (~4 meses de receita): R$ 200 / R$ 300 / R$ 500 se lead→cliente for 2% / 3% / 5%.

## 4. Por que a geração de demanda é baixa (hipóteses, em ordem de impacto)

| # | Hipótese | Tipo | Como validar |
|---|---|---|---|
| H1 | **Só captura, não cria.** 100% da mídia é Search para uma categoria pequena e desconhecida. | Estrutural | Já evidenciada (conv só na marca) |
| H2 | **Verba incompatível com a meta** (seção 3). | Estrutural | Meta de clientes/mês + CAC aceitável |
| H3 | **Rastreamento cego.** | Medição | Teste de envio do formulário, GTM, import de conversão offline do RD |
| H4 | **Oferta com fricção alta:** só demo, formulário com 7 campos obrigatórios (incluindo WhatsApp, segmento e nº de pessoas), sem preço, sem vídeo. | CRO | A/B de formulário curto e de vídeo na dobra |
| H5 | **Intenção misturada:** termos amplos e "merchandising" com phrase match sem negativas. | Search | Termos de pesquisa + lista de negativas |
| H6 | **Message match fraco:** 1 LP para 4 temas, IQ 2–4. | CRO/Search | LPs por tema; IQ após 14 dias |
| H7 | **Marca sem autoridade:** poucas provas públicas, só 3 depoimentos, logos sem nome. | Marca | Cases com número; share de busca de marca |
| H8 | **Vazamento pós-lead:** cliente oculto mostrou discovery superficial e dependência do técnico. O diagnóstico cita 1h59 de espera. | Vendas | Tempo de resposta, taxa de conexão, show rate |
| H9 | **Janela curta de dados:** reestruturação em 13/10, ~3 semanas, amostra pequena. | Estatística | Não decidir por keyword com <30 cliques |

## 5. Validação das suas ideias

### Vídeos explicativos e demonstrativos — **VALIDADO, prioridade 1**
É a ideia com melhor relação impacto/esforço. Sem trial, sem preço e com marca desconhecida, o vídeo **é** o trial. Um vídeo serve a vários usos ao mesmo tempo:
- Meta: topo de funil, e a base de quem assistiu vira audiência de remarketing.
- LP: no hero, substituindo parte da barreira de "agendar demo".
- SDR: no WhatsApp, o "manda material" vira vídeo de 90s.
- LinkedIn orgânico e e-mail para a base.

**Formatos:** (a) 15–30s por dor ("Sua equipe está no PDV. Mas você sabe o que está acontecendo?"); (b) 60–90s de demonstração por caso de uso (ruptura em tempo real, planejado × realizado, foto como evidência); (c) um vídeo de depoimento por case (Pegoraro Deycon, 10+ anos; Simões & Dantas, +1.000 colaboradores; First Trade).

### Blog + "Demand Gen" — **PARCIALMENTE VALIDADO**
- **Sim** para profundidade: SaaS desconhecido precisa de educação e de prova.
- **Não** como motor principal: blog em SEO leva 4–9 meses **(hipótese)** e o volume de busca da categoria é pequeno. A cadência do plano (2 posts/mês) é tímida demais para ranquear e fraca demais como ativo de demanda.
- **Como fazer funcionar:** menos posts, mais fortes, **distribuídos com mídia paga**.
  - 3–4 ativos pilares para distribuidor: *custo da ruptura e da validade no PDV*, *calculadora/planilha de perda*, *diagnóstico de maturidade da execução em campo*, *planilha vs. plataforma: quando migrar*. Isso converte melhor que pedir demo.
  - Páginas de fundo de funil: "melhor software de trade marketing", "alternativa à Involves", "TradePRO vs planilha". Também ajudam em busca por IA (GEO).
- **Pergunta:** "Demand Gen" aqui é o tipo de campanha do Google ou geração de demanda via conteúdo? Se for o tipo de campanha, não recomendo agora: o histórico de YouTube/vídeo teve R$ 17 mil sem lead, por erro de configuração (CPM em vez de conversão), e o plano diz para aguardar o rastreamento.

### Meta como canal principal — **VALIDADO COM CONDIÇÕES**
**A favor:**
- Concorrentes quase ausentes (MáximaTech 0 anúncios, PDV Info 0, PDV Mundo 2).
- A campanha Lite entregou CPC R$ 0,30 e frequência saudável (4,26), então escala sem saturar.
- WhatsApp funcionou historicamente (R$ 5–21 por conversa), mas boa parte foi recrutamento.
- Marca desconhecida precisa de reach qualificado, e Search não faz isso.

**Contra / riscos:**
- Histórico de R$ 45,7 mil com **1,7% em leads comerciais**, pixel quebrado e 43% em reach puro. O problema foi a medição e a estrutura, não necessariamente o canal.
- Lead nativo do Meta costuma ser pior em B2B **(hipótese)**.
- O público é pequeno, e com orçamento baixo o algoritmo não aprende com evento de lead.

**Como fazer certo:**
- **Públicos:** lista de contas do projeto SDR (Prioridade A/B) como Custom Audience (e-mail/telefone de decisores), mais lookalike da base de clientes e interesses (ABAD, APAS, Sankhya, WinThor, TOTVS).
- **Estrutura em 3 camadas:**
  - **Topo:** vídeos de dor e demo, otimizados para ThruPlay ou visita à LP (landing page view), **nunca reach puro**.
  - **Meio:** remarketing de quem viu 50%+ do vídeo ou visitou a LP, com cases e ativo pilar.
  - **Fundo:** quem viu a LP e não converteu, com "veja a demo em 3 minutos" e WhatsApp.
- **Pré-requisito:** pixel + Conversions API validados e UTM padronizado antes de gastar. Sem isso, repete o erro de 2023–2025.
- **Meta de aprendizado:** medir pelo CRM, não pelo painel da Meta.

### LinkedIn — **CONCORDO: não agora, por razão diferente de "caro"**
O problema histórico (R$ 45,5 mil, 7 leads em 4 anos) foi operação: eram "Boost de post", nunca Campaign Manager com segmentação por cargo. Para o ticket de R$ 2.550/mês, CPL de R$ 300–700 **(benchmark, hipótese)** só fecha com lead→cliente ≥ 5%. **Revisitar na fase 3** com Matched Audiences da lista SDR e um teste pequeno e fechado, com critério de parada. Antes disso, LinkedIn orgânico + social selling da SDR custa quase nada e atinge os mesmos cargos.

## 6. Plano de ação estruturado

### Fase 0 — Semana 1: destravar a medição (bloqueia todo o resto)
| Ação | Dono | Critério de pronto |
|---|---|---|
| Testar ponta a ponta: envio do form → GTM → Google Ads → RD Station (capturar GCLID/UTM em campo oculto) | Tráfego | Conversão real aparece com origem no RD |
| Pixel Meta + Conversions API na LP e eventos de vídeo | Tráfego | Eventos validados no Gerenciador |
| Definir **o que é "conversão"**: formulário ≠ MQL | Marketing + Comercial | Regra escrita no RD |
| Preencher a planilha Forecasting com o real de set/out | Tráfego | Linha de base fechada |
| Responder: quantos clientes novos nos últimos 12 meses e por qual origem | Cliente | Número real |

### Fase 1 — Dias 1–30: limpar Google e preparar a base
**Google Ads**
1. Ler o **relatório de termos de pesquisa**. Negativar: vaga, emprego, curso, grátis, pdf, faculdade, salário, "o que é", agência, consultoria, "como ser promotor".
2. Tirar "solução trade marketing" de phrase ampla: passar para exata ou baixar o lance. Revisar "merchandising no pdv" e "gestão de merchandising" (IQ 3). **Não pausar por CTR ou amostra de menos de 30 cliques.**
3. **Criar a campanha Distribuidores** (beachhead): "software/sistema para distribuidor", "gestão de equipe externa distribuidora", "força de campo distribuidor", ligada a uma LP específica.
4. **Separar Lite:** tirar "app/aplicativo para promotores" da campanha Promoter e mandar para uma LP Lite (autoatendimento ou low-touch).
5. **Concorrentes:** pausar "involves stage"; manter só termos com intenção de troca ("alternativa a…") e **negativar "login", "suporte", "entrar"**.
6. **Marca:** checar Informações do leilão (concorrente no termo?). Manter, é onde a conversão acontece.

**LP (CRO)**
1. Variantes por tema: Distribuidor/ruptura-validade, Gestão de promotores, Sistema trade marketing.
2. Headline focada em **distribuidor** na versão principal.
3. Vídeo de demo de 60–90s no hero. WhatsApp fixo no mobile. Formulário curto (nome, e-mail, WhatsApp, nº de pessoas) com o resto qualificado depois.
4. CTA secundário de baixo compromisso (ativo pilar ou "ver demo gravada").
5. Velocidade mobile: WebP e scripts em defer (já apontado no diagnóstico).
6. Mostrar logos com nome, e dois depoimentos em vídeo.

**Produção**
- 3 vídeos de dor (15–30s), 2 demos (60–90s), 1 depoimento.
- 1 ativo pilar (calculadora ou diagnóstico de maturidade).

### Fase 2 — Dias 31–60: criar demanda e medir
- **Meta (teste estruturado):** as 3 camadas acima, em 2–3 criativos por camada e 2 públicos (lista SDR e interesse), sempre separando teste de escala.
- **Google:** consolidar o que sobreviver à limpeza; reavaliar PMax só com rastreamento validado.
- **SDR:** subir a lista A/B como Custom Audience (ABM-lite). Usar vídeo no "manda material". Medir tempo de resposta (meta: poucos minutos, hoje 1h59).
- **Sem amostra:** sem decisão de pausar ou escalar com menos de ~30 cliques por item ou 1 ciclo completo.

### Fase 3 — Dias 61–90: validar e decidir escala
- Decidir a alocação final entre Search, Meta e orgânico **pelo custo por SQL**, não por lead.
- Testar LinkedIn **só se** houver caixa e as audiências da SDR estiverem prontas.
- Eventos e parcerias de ERP (Sankhya, WinThor/TOTVS) como motor paralelo. A APAS 2026 teve CPA de R$ 21,73 e nunca foi replicada.
- Programa de indicação estruturado: o plano diz que já gera venda, mas não há processo.

### Alocação sugerida (a ajustar com a verba real)
| | Run-rate atual (~R$ 2 mil) | R$ 3 mil | R$ 5 mil |
|---|---|---|---|
| Google Search (marca + não-marca + distribuidores) | R$ 1.100 | R$ 1.500 | R$ 2.250 |
| Meta (vídeo + remarketing) | R$ 700 | R$ 1.100 | R$ 2.000 |
| Produção (vídeo/ativo) | à parte | à parte | à parte |
| Reserva de teste (LinkedIn/eventos) | R$ 200 | R$ 400 | R$ 750 |

### KPIs (um por camada)
- **Medição:** % de leads com origem preenchida (meta 100%).
- **Search:** custo por MQL, IQ dos termos principais, % de cliques não-marca com intenção correta.
- **Meta:** custo por ThruPlay, custo por LPV, % de retenção de vídeo, leads do remarketing.
- **LP:** taxa de conversão visita→lead por tema.
- **Comercial:** tempo até a 1ª resposta, MQL→SQL, show rate de demo, custo por SQL.

## 7. Perguntas para eu melhorar a análise

1. **Meta Ads:** a conta 538172087220579 precisa ser autorizada no Windsor (https://onboard.windsor.ai?datasource=facebook). Dá para fazer? Se preferir, o conector **Meta Ads** do Claude também precisa de autorização. Idem para Google Ads, GA4 e Search Console da TradePRO.
2. **Verba:** qual é o orçamento real para os próximos 90 dias? O plano diz R$ 3 mil, o diagnóstico R$ 5 mil, os daily budgets somam ~R$ 2 mil. Posso realocar para Meta?
3. **Meta de negócio:** quantos clientes novos por mês a mídia precisa gerar? Quantos entraram nos últimos 12 meses e por qual origem (indicação, outbound, eventos, inbound)?
4. **Conversão:** o que é a "Conv." do Google Ads (envio de formulário? clique no WhatsApp?)? As 3 conversões da marca viraram MQL ou eram clientes atuais?
5. **Período dos prints:** são desde 13/10? Qual o intervalo exato?
6. **RD Station:** consigo ver volume de leads, MQL, SQL e vendas de set/out por origem?
7. **Ativos:** dá para gravar demos do produto? Existem vídeos prontos? Os depoimentos e logos têm autorização de uso?
8. **"Demand Gen":** é o tipo de campanha do Google ou geração de demanda por conteúdo?
9. **Lite:** qual a prioridade? O preço do Lite pode ficar público?
10. **Responsável de conteúdo:** quem produz e aprova? O plano marca isso como risco.
