# IronBots for Claude Code

Connect Claude Code to your [IronBots](https://ironbots.com.br) account. IronBots is an
all-in-one platform for small and medium businesses: CRM and sales pipelines,
scheduling, a shared customer-service inbox for WhatsApp and Instagram, AI agents
that answer customers, services, inventory, marketing and an internal team chat.

With this plugin, Claude reads and organizes your account with exactly the
permissions of your role. **No tool sends messages to your customers.** Every change
asks for confirmation, and almost all of them can be undone for 7 days. Actions that
can't be undone (deleting for good, turning on an agent, publishing) wait for **your
approval inside IronBots**: the AI asks, you get a notification, and only your click
runs it. The account administrator can also set these to "never" or "allow".

## Install

```
/plugin marketplace add AI-ForgeLabs/ironbots-claude-plugin
/plugin install ironbots@ironbots
```

Then run `/mcp`, choose **ironbots** and **Authenticate**. Your browser opens the
IronBots sign-in screen: sign in and click **Allow**. No API key is needed.

## What's included

- **MCP server** `https://ironbots.com.br/api/mcp`: tools for contacts, schedule, CRM,
  customer service, services (including setting up spaces, boards with columns,
  automations between boards and projects), inventory, marketing, team chat and AI
  agents. The tools you see depend on your role and plan.
- **`/ironbots:resumo-do-dia`**: daily briefing (schedule, unassigned conversations,
  overdue services, stalled deals). Read only.
- **`/ironbots:negocios-parados [days]`**: review of stalled deals with suggested next
  steps. Read only unless you approve a change.

## Requirements

- An active IronBots account. External partner accounts cannot connect.
- Claude Code with a plan that allows MCP servers.

## Links

- Documentation: https://ironbots.com.br/conector-claude
- Privacy policy: https://ironbots.com.br/privacidade
- Terms of use: https://ironbots.com.br/termos
- Support: suporte@ironbots.com.br

---

## Em português

Conecte o Claude Code à sua conta do IronBots: clientes, agenda, CRM, atendimento,
serviços (inclusive criar espaços, quadros, automações entre quadros e projetos),
estoque, marketing, chat da equipe e agentes de IA, sempre com as permissões do
seu cargo. Nenhuma ferramenta manda mensagem para os seus clientes. O que não tem
volta (apagar de vez, ligar agente, publicar) espera a sua aprovação no IronBots: a IA
pede, você recebe o aviso e só o seu clique executa.

Instalação: os dois comandos acima e, depois, `/mcp` → **ironbots** → **Authenticate**.
Entre na sua conta do IronBots e clique em **Permitir**.

Passo a passo completo: https://ironbots.com.br/conector-claude

## License and trademarks

The contents of this repository are licensed under the [Apache License 2.0](LICENSE).
The license does not grant permission to use the IronBots name, logo or trademarks
(see section 6 of the license). Using the IronBots service requires an IronBots
account and is governed by the IronBots Terms of Use.
