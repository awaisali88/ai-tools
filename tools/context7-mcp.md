# Context7 MCP (Upstash)

## What It Is

Context7 is a Model Context Protocol server by Upstash that provides real-time, version-specific library documentation and code examples directly within AI prompts. It prevents LLMs from generating code based on outdated training data by fetching current docs from source repositories.

## What It's Used For

- Preventing hallucinated or outdated API calls in AI-generated code
- Retrieving current documentation for thousands of libraries and frameworks
- Accessing version-specific code examples matching project dependencies
- Enhancing AI code generation accuracy in Cursor, Claude Code, and other MCP clients
- Keeping up with rapidly changing framework APIs

## Key Features

- **Real-Time Docs** — Fetches current documentation for thousands of libraries
- **Version-Specific Examples** — Code examples matching your exact dependency versions
- **Multiple Integration Methods** — Remote HTTP endpoint or local server
- **Automatic Library Matching** — Resolves library names mentioned in prompts
- **30+ MCP Client Support** — Cursor, Claude Code, OpenCode, Windsurf, and more
- **Smart Context Injection** — Automatically fetches relevant docs when libraries are mentioned
- **MIT Licensed** — Open-source MCP server code

## How to Get Started

**Option 1 — Remote server (easiest):**

```json
{
  "mcpServers": {
    "context7": {
      "url": "https://mcp.context7.com/mcp"
    }
  }
}
```

**Option 2 — Local via npx:**

```json
{
  "mcpServers": {
    "context7": {
      "command": "npx",
      "args": ["@upstash/context7-mcp@latest"]
    }
  }
}
```

**Usage:** Include `use context7` in your prompt, or configure automatic triggering in your client.

**API Key (optional):** Visit [context7.com/dashboard](https://context7.com/dashboard) for higher rate limits.

## Pricing

| Plan | Price | Details |
|------|-------|---------|
| Free | $0 | Individual developers, public libraries |
| Pro | $7/month per seat | Team use, higher limits |
| Enterprise | Custom | Contact context7@upstash.com |

## Official Links

- **Website:** [context7.com](https://context7.com)
- **GitHub:** [github.com/upstash/context7](https://github.com/upstash/context7)
- **npm:** [@upstash/context7-mcp](https://www.npmjs.com/package/@upstash/context7-mcp)
- **Blog:** [upstash.com/blog/context7-mcp](https://upstash.com/blog/context7-mcp)
