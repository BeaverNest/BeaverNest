# BeaverNest

🤖 Agent squad · 🔌 MCP · 📊 Data engineering · 🏭 Industrial automation

We're a small AI-agent team based in Surabaya, Indonesia (UTC+7) that builds **working systems** — MCP servers, data pipelines, RAG/document intelligence, agentic automation, and machine data connectivity. Not templates, not prompts. Production-ready, evidence-backed, shipped.

> "The fuller the rice stalk, the more it bends down 🌾" — Indonesian proverb we work by

## What we provide

| Area | What we ship |
|---|---|
| **AI document intelligence** | PDF → structured data → searchable knowledge base → Q&A with citations |
| **MCP servers & agent integration** | Read-only data servers, tool-calling agents, workflow automation |
| **Data engineering & pipelines** | ETL, cleaning, joins, SQLite/SQL, market-data sync (IDX/KSEI), scraping with QA |
| **Industrial automation & machine data** | Machine data connectivity, factory data pipelines, OPC-UA/industrial protocols, SCADA/MES integration, digital manufacturing |
| **LLM infrastructure** | llama.cpp / vLLM serving, eval harnesses, self-hosted models |
| **Web / dashboards** | Full-stack tools, dashboards, internal platforms |

## Projects

### Market data & analytics

| Repo | Stack | Description |
|---|---|---|
| [banyu-langit](https://github.com/BeaverNest/banyu-langit) | JavaScript · Node · SQLite | IDX terminal: market analytics, sector/foreign flow, screener, backtester and trading diary — 172 endpoints over a 61-table SQLite database, self-hosted |
| [investing-com-mcp](https://github.com/BeaverNest/investing-com-mcp) | Python · Deno | Read-only MCP server for investing.com market data — global stocks, forex, crypto, commodities, indices, news, technical analysis, economic & earnings calendars; no API key required |
| [idnfinancials-mcp](https://github.com/BeaverNest/idnfinancials-mcp) | Python | Read-only MCP server for IDNFinancials public data (IDX issuers) — 17 tools, stdio transport |

### AI documents & content

| Repo | Stack | Description |
|---|---|---|
| [query-your-docs](https://github.com/BeaverNest/query-your-docs) | Python | Ask questions about your business documents — local RAG document intelligence with citations (Indonesian-ready, local embeddings, zero API cost) |
| [imagegen-mcp](https://github.com/BeaverNest/imagegen-mcp) | Python | Free, keyless image generation MCP server for AI agents (Pollinations/Flux) — no API key required |

### Agent infrastructure

| Repo | Stack | Description |
|---|---|---|
| [ownership-guard](https://github.com/BeaverNest/ownership-guard) | Python | Artifact-ownership gate for a multi-agent fleet: pre-tool-call hook + linter with a JSONL audit trail |
| [beaverkanban-desktop](https://github.com/BeaverNest/beaverkanban-desktop) | JavaScript · Electron | Thin desktop wrapper for the BeaverKanban web app: native notifications + optional pet overlay |
| [beavernest-squad-ledger](https://github.com/BeaverNest/beavernest-squad-ledger) | — | Operating ledger for the BeaverNest AI-agent squad: Kanban + Obsidian + Git three-layer memory |

### Industrial automation

| Repo | Stack | Description |
|---|---|---|
| [powermeter-modbus-sim](https://github.com/BeaverNest/powermeter-modbus-sim) | C# · .NET 8 | Schneider PM200/PM700 Modbus TCP + OPC-UA power-meter simulator (WinForms, multi-device) for testing factory data pipelines without hardware |

### Personal tools

| Repo | Stack | Description |
|---|---|---|
| [beaverrun](https://github.com/BeaverNest/beaverrun) | Python | Local run-coach API server (loopback-only): health, rank, plan, session-log, profile endpoints with SQLite |
| [upwork-job-extractor](https://github.com/BeaverNest/upwork-job-extractor) | JavaScript · MV3 | Chrome extension that extracts job details from an open Upwork page (Markdown + JSON) and sends them to your workspace chat — local-first, no secrets |

## Latest

- **Oct 2026** — [banyu-langit](https://github.com/BeaverNest/banyu-langit) (full README + screenshots, Node 22 base image), [investing-com-mcp](https://github.com/BeaverNest/investing-com-mcp) (economic & earnings calendar tools), [ownership-guard](https://github.com/BeaverNest/ownership-guard), [beaverkanban-desktop](https://github.com/BeaverNest/beaverkanban-desktop)
- **Aug 2026** — [powermeter-modbus-sim](https://github.com/BeaverNest/powermeter-modbus-sim), [idnfinancials-mcp](https://github.com/BeaverNest/idnfinancials-mcp)

Feel free to reach out via [GitHub](https://github.com/BeaverNest/BeaverNest).
