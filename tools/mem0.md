# Mem0.ai

## What It Is

Mem0 is a universal, self-improving memory layer for AI applications that adds long-term memory and personalization to LLMs and AI agents. It enables stateful AI interactions that remember user preferences, adapt to needs, and learn over time.

## What It's Used For

- Adding long-term memory to AI assistants and chatbots
- Creating personalized AI experiences that adapt over time
- Building customer support bots that remember interaction history
- Developing autonomous AI agents with contextual awareness
- Improving response accuracy without increasing prompt size

## Key Features

- **Hybrid Storage** — Combines graph, vector, and key-value stores for optimal memory management
- **Self-Improving Memory** — Memories improve with every interaction
- **Token Efficiency** — Compresses chat history into optimized memory representations
- **Memory Tracking** — Every memory is timestamped, versioned, and exportable
- **Framework Integration** — Built-in support for OpenAI, LangGraph, CrewAI, and more
- **Enterprise Security** — SOC 2 & HIPAA compliant with BYOK encryption
- **Performance** — 26% higher response accuracy vs OpenAI's memory (LOCOMO benchmark)

## How to Get Started

**Python:**

```bash
pip install mem0ai
```

```python
from mem0 import Memory

m = Memory()
m.add("I love hiking and nature photography", user_id="user1")
results = m.search("hobbies", user_id="user1")
```

**JavaScript:**

```bash
npm install mem0ai
```

Integrates with CrewAI, LangGraph, and other agent frameworks with minimal config.

## Pricing

| Plan | Price | Details |
|------|-------|---------|
| Free | $0 | 10K memories, great for testing |
| Pro | Usage-based | Unlimited memories, higher API limits, advanced retrieval |
| Enterprise | Custom | Custom deployment, compliance certifications, dedicated support |

Startup program: Startups under $5M funding can apply for 3 months free Pro access.

## Official Links

- **Website:** [mem0.ai](https://mem0.ai/)
- **GitHub:** [github.com/mem0ai/mem0](https://github.com/mem0ai/mem0)
- **Docs:** [docs.mem0.ai](https://docs.mem0.ai/)
- **PyPI:** [pypi.org/project/mem0ai](https://pypi.org/project/mem0ai/)
- **Pricing:** [mem0.ai/pricing](https://mem0.ai/pricing)
