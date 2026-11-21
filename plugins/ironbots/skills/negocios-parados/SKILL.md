---
name: negocios-parados
description: Review stalled deals in the user's IronBots CRM pipelines and suggest next steps. Use when the user asks about stuck, stalled or forgotten deals, "negócios parados", "cards parados", or a pipeline review. Optional argument - number of days without movement (default 7).
argument-hint: "[dias]"
---

# Negócios parados no funil

Revise os funis de CRM da conta do IronBots e encontre os negócios sem
movimentação há mais de **$ARGUMENTS** dias (se vazio, use 7).

## Passos

1. Liste os funis da conta e, em cada um, os cards abertos com a data da última
   movimentação.
2. Separe os parados há mais dias que o limite. Agrupe por funil e por etapa.
3. Para cada um, mostre: cliente, etapa, há quantos dias está parado, valor (se houver)
   e o último comentário, quando existir.
4. Sugira um próximo passo concreto por negócio (ex.: mover de etapa, registrar um
   comentário, marcar como perdido).

## Regras

- **Não altere nada sem pedir.** Antes de mover ou comentar, mostre exatamente o que
  vai mudar e espere o "sim". Toda alteração pode ser desfeita depois (peça
  "desfazer a última alteração").
- Mover o card pelo conector **não** dispara a automação daquela etapa (mensagem ao
  cliente, por exemplo). Avise isso quando a etapa de destino tiver automação.
- Responda no idioma da pessoa, começando pelo total e pelos mais antigos.
