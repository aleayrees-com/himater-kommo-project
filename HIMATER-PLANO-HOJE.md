# HIMATER - Plano de Execucao (06/05/2026)

## Regras oficiais fechadas

- Atribuicao: origem `V4` e first-touch imutavel.
- Orcamentos Enviados: etapas `ORÇAMENTO ENVIADO` e `FOLLOW UP - ORÇAMENTO`.
- Data recomendada: primeira entrada do lead em uma dessas etapas.
- Canal Google: `utm_source=google` na URL/origem.
- Canal Meta: primeira mensagem igual aos gatilhos aprovados.
- Sem Canal: quando nao for Google nem Meta.

## Gatilhos Meta aprovados

- `Ola! Vi seu anuncio e quero mais informacoes, por favor.`
- `Ola, quero saber mais sobre os materiais!`
- `Ola! Tenho interesse e queria mais informacoes, por favor.`

## Checklist de hoje

- [x] Validar regra oficial de Orcamentos Enviados.
- [x] Definir regra de canal Google/Meta.
- [x] Definir regra de atribuicao V4 first-touch.
- [x] Atualizar nomenclatura visual para Orcamentos Enviados no dashboard.
- [ ] Mapear endpoint Kommo que alimentara Orcamentos Enviados.
- [ ] Implementar coleta de Orcamentos Enviados por etapa no Kommo.
- [ ] Implementar normalizacao por canal (Google/Meta/Sem Canal).
- [ ] Separar metricas de Orcamentos Enviados por canal.
- [ ] Separar metricas de Vendas por canal.
- [ ] Validar numeros contra dados brutos do Kommo.
- [ ] Validar filtros de periodo e canal.

## Validacao minima (QA rapido)

- Escolher 10 leads de teste (4 Google, 4 Meta, 2 Sem Canal).
- Conferir origem no historico do lead e manter first-touch.
- Conferir se entrou em `ORÇAMENTO ENVIADO` ou `FOLLOW UP - ORÇAMENTO`.
- Conferir data da primeira mudanca para a etapa de orcamento.
- Conferir se os totais por canal batem com o consolidado.
