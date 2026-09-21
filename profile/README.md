# bunkernine-ai

Solo research lab on **agentic evaluation and benchmarking** — how to measure agents that plan, use tools, and act over long horizons, not just next-token accuracy.

Current work is the substrate for that: systems we can instrument, constrain, and score.

## Current projects

| Project | What it is |
| --- | --- |
| [canvas-agent](https://github.com/bunkernine-ai/canvas-agent) | Visual workflows, durable agent runs, and an AI-native canvas |
| [aura](https://github.com/bunkernine/aura) | Taste memory for other AIs — linguistic, aesthetic, and behavioral profile over MCP |
| [anyharness](https://github.com/bunkernine-ai/anyharness) | One tool named `harness`: the agent invents a JSON capability inside policy |
| [crm.sdk](https://github.com/bunkernine/crm.sdk) | Typed CRM for agents — contacts, companies, deals, search, reports |

## Focus

Most evals still treat an agent like a chatbot. We care about the rest of the loop:

- **Capability** — did the agent invent or select the right tool, not just call one?
- **Policy** — did it stay inside a closed world when the task was open-ended?
- **Taste and preference** — is “good” more than a gold string?
- **Durable work** — does the run still make sense after pause, resume, and tool I/O?
- **Domain tasks** — CRM-style actions with typed contracts, not free-form SQL.

If you want to follow along, start with the repos above.
