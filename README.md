# Awesome-Long-Term-Memory-Platform

## Top Long-Term Memory Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on AI Agent Memory, Persistent Context, Knowledge Graphs, Vector Stores & Cross-Session Recall*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Long-Term Memory** in AI systems. These tools give agents and applications persistent memory beyond the context window—storing facts, preferences, conversation history, and structured knowledge so models can recall and reason across sessions.



**Examples** include Mem0, Zep, Letta, Supermemory, Graphlit, Redis Enterprise, Pinecone, Qdrant, Weaviate Cloud, and Astra DB (the category leaders).



**Open-source emphasis**: This category is unusually strong in open source. **Mem0**, **Zep (Graphiti)**, **Letta** (formerly MemGPT), **Qdrant**, **Weaviate**, and related projects provide production-capable self-hosted memory layers and vector/graph stores. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Mem0](https://mem0.ai/)**  

  Popular managed memory layer for AI agents and apps that automatically extracts, stores, and retrieves user facts and preferences across sessions (also available open-source/self-hosted).



- **[Zep](https://www.getzep.com/)**  

  Long-term memory platform built around a temporal knowledge graph, enabling agents to reason about facts that change over time (open-source Graphiti engine + cloud offering).



- **[Letta](https://www.letta.com/)**  

  Agent runtime and memory system (evolved from MemGPT) where stateful agents manage their own tiered memory, tools, and long-running identity (open-source core + hosted options).



- **[Supermemory](https://supermemory.ai/)**  

  Context and memory infrastructure for AI agents with hosted APIs, SDKs, and self-hosting paths.



- **[Graphlit](https://www.graphlit.com/)**  

  Platform for ingesting unstructured content into knowledge graphs and memory usable by AI applications.



- **[Redis Enterprise](https://redis.io/)**  

  Enterprise Redis offering with vector search, semantic caching, and data structures frequently used as a high-performance memory/store layer for AI.



- **[Pinecone](https://www.pinecone.io/)**  

  Managed vector database widely used for semantic memory, RAG, and long-term embedding storage at scale.



- **[Qdrant Cloud](https://qdrant.tech/)**  

  Managed offering of the open-source Qdrant vector database for similarity search and AI memory workloads.



- **[Weaviate Cloud](https://weaviate.io/)**  

  Managed Weaviate vector and hybrid search platform supporting semantic memory and knowledge retrieval.



- **[Astra DB (DataStax)](https://www.datastax.com/)**  

  Serverless database (Cassandra + vector capabilities) used for scalable AI memory and retrieval applications.



## Open-Source GitHub Projects

- **[Mem0](https://github.com/mem0ai/mem0)**  

  Open-source memory layer for AI agents: extract, store, update, and search memories with hybrid vector/graph approaches; self-hostable and framework-agnostic.



- **[Zep / Graphiti](https://github.com/getzep/graphiti)**  

  Open-source temporal knowledge graph engine underlying Zep—stores facts with validity intervals so agents can reason about what was true when.



- **[Letta (formerly MemGPT)](https://github.com/letta-ai/letta)**  

  Open-source framework for building stateful agents with OS-inspired memory management (core, archival, and self-editing memory).



- **[Qdrant](https://github.com/qdrant/qdrant)**  

  High-performance open-source vector database designed for similarity search, filtering, and AI memory/RAG workloads.



- **[Weaviate](https://github.com/weaviate/weaviate)**  

  Open-source vector search engine with hybrid search, modules, and strong support for semantic memory applications.



- **[Milvus / Zilliz open components](https://github.com/milvus-io/milvus)**  

  Open-source vector database frequently used as a backend for long-term embedding memory at scale.



- **[Chroma](https://github.com/chroma-core/chroma)**  

  Open-source embedding database popular for local and lightweight AI memory and RAG prototypes.



- **[LangMem and LangChain memory utilities](https://github.com/)**  

  Open memory tools and patterns within the LangChain/LangGraph ecosystem for agent memory management.



- **[Redis (Search & vector capabilities)](https://github.com/redis/redis)**  

  Open-source Redis with modules supporting vector similarity and secondary indexing for fast memory stores.



- **[Cognee, Hindsight, and other open memory frameworks](https://github.com/)**  

  Emerging open projects focused on graph + vector memory, embedded stores, and agent-centric long-term recall.



### Additional Strong Open-Source Options

- Starting with **Mem0** for the simplest drop-in, multi-user memory API with large community support.

- Choosing **Zep/Graphiti** when temporal facts and evolving knowledge graphs matter.

- Adopting **Letta** when you want agents that actively manage their own long-horizon memory.

- Pairing any memory layer with **Qdrant**, **Weaviate**, or **Milvus** for scalable vector storage.

- Accepting that fully managed multi-tenant isolation, enterprise SLAs, and polished hosted consoles still favor commercial offerings (Mem0 Cloud, Zep Cloud, Pinecone, Weaviate Cloud, Redis Enterprise, etc.).

- Focusing open-source efforts on transparent, self-hosted memory that keeps sensitive conversation data under your control.



**Frameworks for building custom systems**: Capture conversations/events → extract facts (Mem0-style or LLM) → store in vector DB (Qdrant/Weaviate) and/or temporal graph (Graphiti) → retrieve relevant memories into the prompt or agent context → optionally let the agent edit its own memory (Letta-style). Suitable for production agents, personal assistants, and privacy-sensitive deployments. Many teams combine open cores with managed vector/graph services for operational simplicity.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Long-term memory systems store personal and conversational data and must comply with privacy regulations. Open-source deployments require proper security, access control, and data governance. Memory quality depends on extraction and retrieval design—hallucinated or stale facts remain a risk. This list is not security or compliance advice.



---

**Made for AI engineers, agent builders, and teams who need reliable cross-session memory.**

Let's keep agent memory persistent, inspectable, and as open as practical.
