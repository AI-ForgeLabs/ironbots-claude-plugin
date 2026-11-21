---
name: resumo-do-dia
description: Daily briefing of the user's IronBots account (today's schedule, unassigned customer conversations, overdue services and stalled deals). Use when the user asks for a summary of the day, "resumo do dia", "como está hoje", or what needs attention in IronBots.
---

# Resumo do dia no IronBots

Monte um resumo curto do que precisa de atenção hoje na conta do IronBots da pessoa,
usando as ferramentas do servidor MCP `ironbots`. **Só leitura:** não altere nada
neste fluxo. Se algo pedir ação, sugira e pergunte antes.

## O que levantar

1. **Agenda de hoje:** os compromissos do dia, no fuso da empresa (o campo `fuso`
   vem nas respostas da agenda). Destaque os próximos e os que estão sem confirmação.
2. **Atendimento:** conversas sem responsável e as que esperam resposta há mais tempo.
3. **Serviços:** os atrasados e os que vencem hoje, com o responsável de cada um.
4. **Funil de vendas:** negócios parados há mais de 7 dias.

Se uma ferramenta não aparecer, o cargo ou o plano da pessoa não inclui aquela área.
Diga isso em uma linha e siga com o resto, sem tentar contornar.

## Como responder

- No idioma da pessoa.
- Comece pelos números (ex.: "3 compromissos, 2 conversas sem dono, 1 serviço atrasado").
- Depois, uma seção curta por área, só com o que pede ação. Área sem pendência
  vira uma linha ("Serviços: nada atrasado").
- Termine com até 3 sugestões de próximo passo e pergunte se a pessoa quer que
  você faça alguma delas.
