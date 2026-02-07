# OpenClaw

## What It Is

OpenClaw (formerly Clawdbot/Moltbot) is a self-hosted, open-source personal AI assistant that runs as a 24/7 Node.js service on your machine. It functions as an autonomous agent that can browse the web, read/write files, execute shell commands, and integrate with 50+ platforms and services.

## What It's Used For

- Building autonomous AI agents for real-world task automation
- Creating personal AI assistants for productivity, research, and monitoring
- Connecting AI to chat platforms (WhatsApp, Discord, Telegram, Slack, Signal, Teams)
- Automating workflows across smart home devices, productivity tools, and APIs
- Self-hosted alternative to commercial AI assistants with full data control

## Key Features

- **50+ Integrations** — Chat providers, AI models, productivity tools, smart home, and more
- **24/7 Daemon** — Runs continuously as a background service
- **Multi-LLM Support** — Claude, OpenAI, local models via Ollama
- **Messaging Platforms** — WhatsApp, Telegram, Discord, Slack, Signal, iMessage, Teams
- **Autonomous Execution** — Web browsing, file operations, shell commands
- **Extensible Skills** — Community skills or build your own
- **Git Integration** — Infrastructure-as-code deployments
- **Canvas UI** — Live rendered canvas you control

## How to Get Started

**Requirements:** Node.js v22+, pnpm

**Global install:**

```bash
npm install -g openclaw@latest
openclaw onboard --install-daemon
```

**From source:**

```bash
git clone https://github.com/openclaw/openclaw.git
cd openclaw
pnpm install
pnpm ui:build
pnpm build
```

**Docker:** Also available as a container for isolated execution.

## Pricing

The software is 100% free and open source. Operating costs depend on LLM API usage:

| Usage Level | Estimated Monthly Cost |
|-------------|----------------------|
| Light | $10-30 |
| Typical | $30-70 |
| Heavy automation | $100-150+ |

Costs can be reduced using open-source models (Ollama), free API tiers, or existing Claude Pro/ChatGPT subscriptions.

## Official Links

- **Website:** [openclaw.ai](https://openclaw.ai/)
- **GitHub:** [github.com/openclaw/openclaw](https://github.com/openclaw/openclaw)
- **Docs:** [docs.openclaw.ai](https://docs.openclaw.ai/)
- **npm:** [npmjs.com/package/openclaw](https://www.npmjs.com/package/openclaw)
