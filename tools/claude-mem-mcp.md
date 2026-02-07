# Claude Mem MCP

## What It Is

Claude Mem MCP is a Claude Code plugin that automatically captures, compresses, and stores everything Claude does during coding sessions, then injects relevant context back into future sessions. It solves the "amnesia problem" where AI agents forget previous work between sessions.

## What It's Used For

- Maintaining persistent memory across multiple Claude Code sessions
- Automatically recording tool usage, decisions, and observations
- Semantic search across past sessions to find relevant context
- Building institutional knowledge within coding projects
- Reducing repetitive context-setting in new sessions

## Key Features

- **Persistent Storage** — Captures everything Claude does and stores it in SQLite + FTS5 + ChromaDB
- **Intelligent Memory Search** — Natural language queries (e.g., "What bugs did we fix last session?")
- **Progressive Disclosure** — Layered memory retrieval that shows token costs upfront
- **5 MCP Tools** — 3-layer workflow: search index, review, then fetch details
- **Skill-Based Search** — Filter by concept, file, type (decision, bugfix, etc.), and timeline
- **Privacy Controls** — Private tags to exclude sensitive content from memory
- **Web UI** — View and manage memories at `http://localhost:37777`
- **Cross-Platform** — Windows, macOS, and Linux

## How to Get Started

**Option 1 — Plugin marketplace (recommended):**

```
/plugin marketplace add thedotmack/claude-mem
/plugin install claude-mem
```

**Option 2 — Manual install:**

```bash
git clone https://github.com/thedotmack/claude-mem.git
cd claude-mem
npm install
npm run build
npm run worker:start
```

## Pricing

Free and open source (AGPL-3.0 license). No paid tiers.

## Official Links

- **GitHub:** [github.com/thedotmack/claude-mem](https://github.com/thedotmack/claude-mem)
- **npm:** [npmjs.com/package/claude-mem](https://www.npmjs.com/package/claude-mem)
