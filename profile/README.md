# AllocContext

**Portfolio-aware crypto context for AI agents** — deterministic JSON over MCP.
Holdings-scoped market, sentiment, macro, and regime; optional allocation analysis.
**Self-host via PyPI** (stdio MCP + optional local ingest).

Privacy: nothing stored · one-time read-only · pass-through only.

Not financial advice.

## Repositories

| Repo | Role |
|------|------|
| [**alloc-context**](https://github.com/AllocContext/alloc-context) | Core MCP — ingest, rollup, stdio MCP, self-host |
| [**alloc-context-orchestrator**](https://github.com/AllocContext/alloc-context-orchestrator) | Optional multi-engine evaluation (local/ad-hoc) |
| [**alloc-context-operator**](https://github.com/AllocContext/alloc-context-operator) | Archived — email digest layer (retired) |

Hosted MCP at `mcp.alloc-context.com` is **retired**. Install and run locally.

## Get started

- **Cursor / agents:** [cursor-mcp.md](https://github.com/AllocContext/alloc-context/blob/main/docs/cursor-mcp.md)
- **Self-host:** [self-hosting.md](https://github.com/AllocContext/alloc-context/blob/main/docs/self-hosting.md) or [docker-self-host.md](https://github.com/AllocContext/alloc-context/blob/main/docs/docker-self-host.md)
- **LangChain:** [langchain-mcp-adapters](https://github.com/langchain-ai/langchain-mcp-adapters) + stdio MCP
- **Architecture:** [deterministic-context-mcp-pattern.md](https://github.com/AllocContext/alloc-context/blob/main/docs/deterministic-context-mcp-pattern.md)

Registry: `io.github.AllocContext/alloc-context` · PyPI: `alloc-context` · License: [MIT](https://github.com/AllocContext/alloc-context/blob/main/LICENSE)

## Contributing

Issues welcome for bugs and MCP API feedback. See
[CONTRIBUTING.md](https://github.com/AllocContext/alloc-context/blob/main/CONTRIBUTING.md).
