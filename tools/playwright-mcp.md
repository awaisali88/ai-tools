# Playwright MCP (Microsoft)

## What It Is

Playwright MCP is a Model Context Protocol server by Microsoft that enables LLMs to automate web browsers through structured accessibility data. It provides fast, vision-free browser automation for AI agents without requiring screenshots or visual models.

## What It's Used For

- AI-driven browser automation and web testing
- Web scraping and data extraction
- Form filling and user interaction simulation
- Cross-browser compatibility testing (Chromium, Firefox, WebKit)
- End-to-end test automation in CI/CD pipelines
- Automating repetitive web-based workflows

## Key Features

- **Accessibility-Based** — Uses accessibility trees instead of screenshots for faster, reliable interactions
- **No Vision Models Needed** — Operates entirely on structured text data
- **Deterministic** — Reduces ambiguity common in screenshot-based approaches
- **Multi-Browser** — Chromium, Firefox, and WebKit support
- **Device Emulation** — Emulate specific devices (e.g., iPhone 15)
- **Host Allowlisting** — Configure which domains the browser can access
- **Docker Support** — Run in containers for isolated environments
- **Apache 2.0 Licensed** — Free and open source

## How to Get Started

**Requirements:** Node.js 18+

**VS Code:**

```bash
code --add-mcp '{"name":"playwright","command":"npx","args":["@playwright/mcp@latest"]}'
```

**MCP config (Claude Desktop, Cursor, etc.):**

```json
{
  "mcpServers": {
    "playwright": {
      "command": "npx",
      "args": ["@playwright/mcp@latest"]
    }
  }
}
```

**Docker:**

```bash
docker run -i --rm --init --pull=always mcr.microsoft.com/playwright/mcp
```

If you encounter browser issues, install browsers manually:

```bash
npx playwright install
```

## Pricing

Free and open source (Apache 2.0 license).

## Official Links

- **GitHub:** [github.com/microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp)
- **Playwright:** [playwright.dev](https://playwright.dev)
- **npm:** [@playwright/mcp](https://www.npmjs.com/package/@playwright/mcp)
