<div align="center">

```
█████╗ ██╗    ███████╗███╗   ██╗ ██████╗ ██╗███╗   ██╗███████╗███████╗██████╗
██╔══██╗██║    ██╔════╝████╗  ██║██╔════╝ ██║████╗  ██║██╔════╝██╔════╝██╔══██╗
███████║██║    █████╗  ██╔██╗ ██║██║  ███╗██║██╔██╗ ██║█████╗  █████╗  ██████╔╝
██╔══██║██║    ██╔══╝  ██║╚██╗██║██║   ██║██║██║╚██╗██║██╔══╝  ██╔══╝  ██╔══██╗
██║  ██║██║    ███████╗██║ ╚████║╚██████╔╝██║██║ ╚████║███████╗███████╗██║  ██║
╚═╝  ╚═╝╚═╝    ╚══════╝╚═╝  ╚═══╝ ╚═════╝ ╚═╝╚═╝  ╚═══╝╚══════╝╚══════╝╚═╝  ╚═╝
```

### AI Engineer · LLMs in Production · LangChain · RAG · LangGraph

[![LinkedIn](https://img.shields.io/badge/LinkedIn-paulopraganaa-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/paulopraganaa/)
[![GitHub](https://img.shields.io/badge/GitHub-pragana12-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/pragana12)

</div>

---

## About

I build AI systems that solve real business problems — not demos that work only in controlled environments.

My focus is on **LLMs in production**: agents that actually run, RAG pipelines that retrieve what matters, and workflows that integrate cleanly with legacy corporate systems (ERP, BPM, databases).

Currently building production AI systems at  **ZDT Nexus**, autonomous agents, RAG pipelines, and process automation for enterprise clients in Brazil.

---

## What I Build

**Autonomous Agents** — Multi-step agents with LangGraph, custom tool routing, persistent memory and production-grade error handling.

**RAG Systems** — Custom chunking strategies, semantic + hybrid retrieval, vector stores (PGVector, ChromaDB, FAISS). Not just "embed and retrieve" — context-aware pipelines calibrated for each use case.

**LLM Integrations** — OpenAI, Anthropic, local models via Ollama. API layer with FastAPI, streaming, cost tracking, logging.

**Process Automation** — Human-in-the-loop workflows, RPA pipelines, ERP integrations (TOTVS Protheus / Fluig).

---

## Stack

```python
stack = {
    "agents":    ["LangChain", "LangGraph", "ReAct", "Tool Calling"],
    "llms":      ["OpenAI", "Anthropic", "Ollama", "Gemini"],
    "rag":       ["PGVector", "ChromaDB", "FAISS", "Semantic + Hybrid Retrieval"],
    "backend":   ["Python", "FastAPI", "PostgreSQL", "Supabase"],
    "infra":     ["AWS", "Docker", "Docker Swarm", "EC2"],
    "erp":       ["TOTVS Protheus", "TOTVS Fluig", "REST Integrations"],
}
```

---

## Selected Projects

### Athena — Enterprise AI Agent for TOTVS Protheus
AI agent that answers business questions by dynamically generating SQL queries against a TOTVS ERP with hundreds of tables and domain-specific business rules.

The core challenge: how to pass complex context to an LLM without prompt bloat and hallucination. Solution: a custom RAG node in the LangGraph flow that retrieves the exact query template and business rules relevant to each question — using semantic-delimiter-based chunking (`#----------#`) instead of fixed-size chunks. Reduced query generation errors by ~70%.

`LangGraph` `LangChain` `RAG` `PGVector` `FastAPI` `Python` `TOTVS Protheus`

---

### GITIA — Human-in-the-Loop Platform (Guaraves)
Replaced TOTVS Fluig with a custom BPM/ECM platform integrating AI-powered process automation. Built end-to-end: process mapping, backend architecture, AI integration, and internal adoption.

Result: automated dozens of internal workflows for a 3,000+ employee company, reducing manual intervention and process cycle times significantly.

`Python` `FastAPI` `PostgreSQL` `AI Automation` `BPM` `Human-in-the-Loop`

---

### J.A.R.V.I.S. — Personal AI Assistant
Personal autonomous assistant with persistent memory, multi-tool routing, and local LLM support via Ollama. Built with LangGraph for explicit state control and ReAct pattern for tool decision-making.

`LangGraph` `LangChain` `Ollama` `ReAct` `Memory` `Python`

---

## GitHub Stats

<div align="center">

![Paulo's GitHub stats](https://github-readme-stats.vercel.app/api?username=pragana12&show_icons=true&count_private=true&hide_border=true&title_color=ffffff&icon_color=ffffff&text_color=c9d1d9&bg_color=0d1117)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=pragana12&layout=compact&hide_border=true&title_color=ffffff&text_color=c9d1d9&bg_color=0d1117)

</div>

---

## Currently

- Building production AI systems at **ZDT Nexus**
- Exploring **multi-agent orchestration** with LangGraph and Paperclip
- Writing about **LLMs in production** — the gap between what works in demos and what works at scale

---

<div align="center">

*"The difference between a PoC and production is everything that happens after the demo works."*

</div>
