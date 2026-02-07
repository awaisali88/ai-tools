# Claude Code (Anthropic)

## What It Is

Claude Code is an agentic coding tool by Anthropic that lives in your terminal, understands your entire codebase, and helps you code faster through natural language commands. It can edit files, run commands, handle git workflows, and automate development tasks.

## What It's Used For

- Writing and implementing features from high-level descriptions
- Bug fixes, refactoring, and code migrations
- Explaining complex code and performing code reviews
- Git workflows, commit generation, and PR creation
- Running tests and debugging across files
- Automating development workflows with custom skills

## Key Features

- **Terminal-Native CLI** — Full IDE-like capabilities directly in your terminal
- **IDE Integrations** — VS Code extension, JetBrains support, and web interface at claude.ai/code
- **Deep Codebase Understanding** — Reads and navigates your entire project structure
- **Direct File Editing** — Modifies code, creates files, runs commands autonomously
- **GitHub Integration** — GitHub Actions for automated code review and CI/CD
- **Custom Slash Commands** — Create domain-specific commands for your workflow
- **Hooks & Automation** — Pre/post tool-use hooks for custom workflows
- **Multi-Platform** — Terminal, web, iOS, Slack integration

## How to Get Started

**Install (recommended):**

macOS (Homebrew), Windows (WinGet), or Linux native binary — see [official docs](https://docs.anthropic.com/en/docs/claude-code) for platform-specific instructions.

**Legacy npm install:**

```bash
npm install -g @anthropic-ai/claude-code
```

**Run:**

```bash
cd your-project
claude
```

Requires Node.js 18+ and a paid Claude subscription.

## Pricing

| Plan | Price | Details |
|------|-------|---------|
| Claude Pro | $20/month | Claude Code access with usage limits |
| Claude Max | $100-200/month | 5x-20x token capacity, max priority |
| Claude Team | $150/person/month | Team collaboration features |

## Official Links

- **Docs:** [docs.anthropic.com/en/docs/claude-code](https://docs.anthropic.com/en/docs/claude-code)
- **GitHub:** [github.com/anthropics/claude-code](https://github.com/anthropics/claude-code)
- **npm:** [npmjs.com/package/@anthropic-ai/claude-code](https://www.npmjs.com/package/@anthropic-ai/claude-code)
- **Pricing:** [claude.ai/pricing](https://claude.ai/pricing)
