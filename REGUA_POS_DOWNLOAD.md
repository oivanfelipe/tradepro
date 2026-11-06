# TradePRO: régua de disparos pós-download de ebook (Meta Ads)

> **Somente definição.** Nada foi configurado no RD Station, no WhatsApp nem em conta de anúncios.
> **Decisões do cliente:** disparos de e-mail no **RD Station**; contato por WhatsApp feito pelo **comercial da TradePRO**; **Lite = operações de até ~10 pessoas** como corte da trilha; V4 produz e TradePRO valida; conteúdo só com dados já presentes na LP.

---

## 1. Fluxo no RD Station

**Gatilho:** conversão no formulário do ebook (um fluxo por ebook).
**Campos do formulário (já padrão da LP):** nome, empresa, e-mail corporativo, WhatsApp, segmento (distribuidor/atacadista, indústria, agência, outro) e pessoas na operação de campo (até 10, 11–30, 31–100, 100+).
**Tags/UTM:** `utm_source=meta`, `utm_campaign=ebook-<tema>`, `utm_content=<anúncio>`. Dentro do fluxo: `utm_medium=email` e `utm_campaign=nutri-ebook-<tema>`.

```
Download do ebook X
   │
   ├─ [Segmento = Distribuidor/Atacadista, Indústria ou Agência]  E  [Pessoas ≥ 11]
   │      → TRILHA PROMOTER (e-mail + tarefa de WhatsApp no CRM)
   │         └─ [Pessoas = 100+]  → marcar PRIORIDADE (tratamento humano prioritário, possível Enterprise)
   │
   ├─ [Pessoas = Até 10]  (qualquer segmento atendido)
   │      → TRILHA LITE (só e-mail, low-touch)
   │         └─ [precisa de integração com ERP, ou vários decisores] → reclassificar para PROMOTER
   │
   └─ [Segmento = Outro/varejo]
          → NUTRIÇÃO LEVE (e-mail mensal; sem WhatsApp)
```

**Regra de roteamento:** o corte de ~10 pessoas é a regra padrão, mas o Diagnóstico Comercial diz que a quantidade de promotores não define o produto sozinha. **Exceções que sobem para Promoter:** necessidade de integração com ERP, mais de um decisor, equipe própria e terceirizada ao mesmo tempo.

## 2. Tipos de conteúdo

| # | Tipo | Função | Formato | Canal |
|---|---|---|---|---|
| 1 | **Entrega** | Entregar o ebook | E-mail curto + link | E-mail (RD) |
| 2 | **Microqualificação** | Entender a operação antes de vender | 1 pergunta de diagnóstico | WhatsApp (comercial) |
| 3 | **Demonstração em vídeo** | Mostrar o produto no tema baixado | Vídeo de 60–75 s (roteiros P1 a P5) | E-mail e WhatsApp |
| 4 | **Conteúdo complementar** | Levar ao próximo tema | Carrossel, checklist ou outro ebook | E-mail e Meta |
| 5 | **Prova social** | Reduzir risco percebido | Depoimento (Pegoraro Deycon, First Trade, Simões & Dantas, com autorização) | E-mail, WhatsApp, Meta |
| 6 | **Objeção** | Desmontar a barreira | "Já usamos ERP", "Minha equipe vai resistir", "Já usamos planilha" | E-mail |
| 7 | **Convite à demonstração** | Converter em conversa comercial | CTA direto | E-mail, WhatsApp, Meta |
| 8 | **Encerramento elegante** | Parar sem perder a relação | Mensagem curta | WhatsApp e e-mail |
| 9 | **Remarketing** | Manter a marca presente | Anúncio | Meta |

## 3. Régua por trilha

Os intervalos seguem a cadência de SDR do material de aceleração comercial (D0, D2–3, D5–6, D9–10, D14–15), que o próprio material trata como **hipótese a testar**. **Regra de ouro:** cada disparo traz algo novo; nunca "viu minha mensagem?".

### Trilha Promoter (e-mail + WhatsApp do comercial)
| Quando | Tipo | Canal | CTA | Responsável |
|---|---|---|---|---|
| D0 | 1 Entrega + vídeo de 20 s do tema | E-mail | Ver o conteúdo completo | RD (automático) |
| D0–D1 | 2 Microqualificação | WhatsApp | Responder a pergunta | **Comercial TradePRO** (tarefa criada no RD CRM) |
| D2–3 | 3 Demonstração em vídeo | E-mail | Ver como funciona | RD |
| D5–6 | 4 Conteúdo complementar | E-mail | Ver o checklist | RD |
| D9–10 | 5 Prova social | E-mail e WhatsApp | Conhecer o Promoter | RD + comercial |
| D14–15 | 7 Convite à demonstração | WhatsApp e e-mail | Agendar uma demonstração | Comercial |
| Depois | 8 Encerramento + nutrição mensal | E-mail | n/a | RD |
| Em paralelo (D3+) | 9 Remarketing | Meta | Prova social e "Agendar uma demonstração" | V4 (tráfego) |

### Trilha Lite (somente e-mail, sem consultivo)
| Quando | Tipo | CTA |
|---|---|---|
| D0 | 1 Entrega | Ver o conteúdo completo |
| D2–3 | Vídeo L1 ("Sua operação cresceu além do WhatsApp?") | Ver como começar |
| D6–7 | Conteúdo "organizar sem criar processo pesado" (tema 10) | Ver como começar |
| D10–12 | Vídeo L2 (primeiros passos) | Ver como começar |
| Depois | Nutrição mensal | n/a |

Sem convite à demonstração consultiva no Lite. A migração para o Promoter ocorre por sinal operacional (limite de licenças, crescimento, integração), nunca por tempo.

### Nutrição leve (varejo ou "outro")
E-mail mensal com conteúdo educativo; sem WhatsApp. Quem se identificar como distribuidor, indústria ou agência é reclassificado.

## 4. Gatilhos de comportamento

| Gatilho | Ação |
|---|---|
| Clicou no vídeo ou visitou "Ver como funciona" | Antecipar o tipo 7 (convite) |
| Respondeu no WhatsApp | Comercial assume e registra no CRM com **próxima ação e data** |
| Pediu demonstração | Vai ao CRM; o comercial valida o **SQL na etapa de Discovery** |
| Não abriu nada até D5–6 | Trocar assunto e canal antes de insistir |
| Descadastrou | Encerrar todos os disparos |
| Marcou "100+ pessoas" | Prioridade: contato humano rápido |

## 5. Governança do WhatsApp (comercial da TradePRO)

O material de aceleração comercial registra que hoje a conversa pertence ao WhatsApp pessoal da SDR e a gestão não enxerga o que é dito. Como o contato pós-download será do comercial, vale fixar o mínimo:
1. **Toda conversa gera registro no RD CRM:** origem (ebook e UTM), pergunta feita, resposta, próxima ação com data. Oportunidade sem próxima ação e data não fica aberta.
2. **Tempo até o primeiro contato:** o diagnóstico mostrou espera de 1h59 em contato anterior. A meta recomendada é poucos minutos em horário comercial.
3. **Scripts:** usar o script 4 da cadência ("Manda material" vira microqualificação) e o script 10 (encerramento elegante).
4. **Amostra semanal de conversas** para a gestão avaliar qualidade (checklist: personalizou, criou contexto, fez uma pergunta de diagnóstico, definiu o próximo passo, registrou no CRM).
5. **Respeitar o descadastro e o consentimento** da LP (política de privacidade, LGPD).

## 6. Regras de conteúdo

- **Download não é MQL.** MQL exige perfil compatível (segmento atendido, equipe de campo, contato válido, interesse compatível) e algum sinal de interesse. **SQL** só com fit, dor concreta e próximo passo confirmado pelo comercial.
- **Só dados da LP:** +15 anos, +25 mil usuários, atuação nacional, os 3 depoimentos, as 4 etapas de implantação e a menção a Sankhya e WinThor. Nenhum número sem fonte.
- **Vocabulário do Manual:** "visibilidade", "execução", "decisão". Sem "controle" ou "fiscalização".
- **CTA por estágio:** conteúdo, "Ver o checklist"; consideração, "Ver como funciona"; alta intenção, "Agendar uma demonstração"; Lite, "Ver como começar".
- **Aprovação:** a V4 produz e a **TradePRO valida cada peça**, com atenção a (a) afirmação sobre produto, (b) integração, (c) uso de depoimento e nome de cliente.

## 7. O que medir

| Etapa | Indicador |
|---|---|
| Entrega | Abertura e clique por tipo de conteúdo |
| Engajamento | Visualização do vídeo, resposta no WhatsApp |
| Qualificação | % de ICP entre os downloads, download→MQL |
| Comercial | MQL→SQL, demonstrações realizadas, tempo até o 1º contato |
| Eficiência | Custo por download de ICP, custo por MQL por tema de ebook |

Teste: comparar a régua D0–D15 com uma mais curta, já que os intervalos são hipótese.

## 8. A validar no RD Station (antes de montar)

Não conheço a configuração atual da conta, então precisa confirmar:
1. Se o plano permite **fluxos de automação com ramificação** por campo do formulário (segmento e pessoas na operação).
2. Se o formulário da LP **grava segmento e nº de pessoas** como campos do contato, e se a integração Marketing → CRM cria a **tarefa de WhatsApp** para o comercial.
3. Como o RD trata **duplicidade de contatos e perda de histórico**, que apareceram como dificuldades no material de aceleração comercial.
4. Se há **pontuação de leads** configurada, para sinalizar MQL.
5. Se o **UTM do Meta** chega ao CRM sem perda (1 em cada 10 leads de outubro chegou sem origem).
