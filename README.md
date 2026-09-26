# Awesome-AI-Agent-Memory-Platform

# Top AI Agent Memory Platform Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Long-Term Agent Memory, Temporal Knowledge Graphs, OS-Style Context Management, Vector Memory Layers & Persistent Agent State*  
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Agent Memory**. These systems give agents durable memory beyond the context window—extracting facts, tracking changes over time, managing tiered context, and retrieving the right memories for long-running tasks.

**Examples** include Mem0, Zep, LangMem, Letta, Graphlit, Ragie, Redis LangCache, Supermemory, MemoryPlugin, Recall.ai Memory, Pinecone, Qdrant Cloud, and Chroma Cloud (the category leaders).

**Open-source emphasis**: Agent memory has strong open options. **Mem0**, **Letta** (ex-MemGPT), **Graphiti** (Zep’s engine), **LangMem**, **Cognee**, and vector databases power most self-hosted memory layers. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Mem0](https://mem0.ai/)**  
  Popular managed memory layer for AI agents—vector + graph + key-value with automatic fact extraction; open-source core available for self-hosting.

- **[Zep](https://www.getzep.com/)**  
  Temporal knowledge-graph memory for agents—tracks when facts change; Graphiti engine is open source.

- **[Letta (Cloud)](https://www.letta.com/)**  
  Hosted runtime for agents with OS-style tiered memory (in-context vs archival) that agents manage via tools.

- **[Graphlit, Ragie, Supermemory](https://www.graphlit.com/)**  
  Knowledge and memory platforms oriented toward RAG, agent context, and persistent retrieval for applications.

- **[Redis LangCache / Redis Cloud Vector, Pinecone, Qdrant Cloud, Chroma Cloud](https://redis.io/)**  
  Managed vector and cache layers widely used as the storage backend for agent memory and semantic retrieval.

- **[LangMem, MemoryPlugin, Recall.ai Memory](https://www.langchain.com/)**  
  Framework-native and specialty memory products for LangGraph stacks, plugins, and conversation/memory capture.

- **[Other commercial agent memory platforms](https://mem0.ai/)**  
  Additional managed memory APIs and knowledge layers for production agents.

## Open-Source GitHub Projects

- **[Mem0](https://github.com/mem0ai/mem0)**  
  Leading open-source (Apache 2.0) memory layer for AI agents—drop-in persistent memory with extraction, vector/graph options, and production-oriented design.

- **[Letta (formerly MemGPT)](https://github.com/letta-ai/letta)**  
  Open-source agent runtime with OS-inspired tiered memory—agents explicitly manage what stays in context vs long-term storage (Apache 2.0).

- **[Graphiti (Zep’s open engine)](https://github.com/getzep/graphiti)**  
  Open-source temporal knowledge graph for agent memory—fact validity windows and time-aware retrieval (MIT/Apache).

- **[LangMem](https://github.com/langchain-ai/langmem)**  
  Open LangGraph-native memory library—semantic, episodic, and procedural memory patterns as an SDK.

- **[Cognee](https://github.com/topoteretes/cognee)**  
  Open graph-first memory and knowledge pipeline for agents—ingest, structure, and query memory with local-first options (Apache 2.0).

- **[Chroma, Qdrant, Weaviate, pgvector](https://github.com/chroma-core/chroma)**  
  Open vector databases used as the storage foundation for custom agent memory and RAG layers.

- **[Supermemory open / MCP memory projects](https://github.com/search?q=supermemory+OR+agent+memory+MCP)**  
  Open and MCP-oriented memory tools optimized for coding agents and multi-session context.

- **[MemGPT research lineage & community forks](https://github.com/search?q=MemGPT+OR+agent+memory+management)**  
  Academic and community implementations of hierarchical and self-managed agent memory.

### Additional Strong Open-Source Options

- **General-purpose memory API**: Mem0 open core for quick integration.
- **Temporal facts**: Graphiti when “when did this change?” matters.
- **Self-managed agents**: Letta for long-running agents that page their own memory.
- **LangGraph stacks**: LangMem for native memory primitives.
- **DIY**: Vector DB + extraction LLM + simple CRUD for lightweight memory.
- Commercial platforms still lead in managed scale, multi-tenant isolation, and zero-ops APIs.

**Frameworks for building custom systems**:  
**Mem0**, **Letta**, **Graphiti**, and **LangMem** are the primary open agent memory layers.  
Pair with **Chroma/Qdrant/pgvector** for storage.  
Commercial services (Mem0 Cloud, Zep, Letta Cloud, Pinecone, etc.) provide hosted reliability and support.  
Many teams self-host Mem0 or Letta for control and use managed vector DBs for scale. Fully open memory stacks are production-viable with careful schema design and retrieval evaluation.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Agent memory stores personal and sensitive conversation data. Apply retention policies, encryption, access control, and user deletion rights (GDPR, etc.). Incorrect or stale memories can cause harmful agent behavior—monitor and allow correction.
- Open-source tools offer data residency and control but require you to operate storage and extraction quality. Commercial platforms shift operational burden to the vendor. Evaluate memory accuracy on your own workloads before production use.

---

**Made for agent builders, AI platform engineers, and teams shipping long-running autonomous agents.**  
Let's expand open agent memory while recognizing the managed reliability and scale that leading commercial memory platforms deliver.
