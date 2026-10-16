# Awesome-LLM-Knowledge-Systems

# Top LLM Knowledge Systems Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Personal Knowledge Management, Organizational Context Layers & Agent Memory Systems*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **LLM Knowledge Systems**. These tools transform scattered notes, documents, and organizational knowledge into queryable, AI-augmented knowledge bases — enabling retrieval-augmented generation (RAG), agent memory, and context-aware AI assistants.

**Examples** include Notion AI, Glean, Guru AI, Slite AI, Coda AI, Mem.ai, Capacities, Tana, Roam Research, and Obsidian Sync (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, local-first knowledge management, and transparent agent memory — ideal for researchers, teams, and individuals building vendor-neutral, privacy-preserving knowledge systems.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Notion AI](https://www.notion.so/product/ai)**  
  AI writing assistant and Q&A system integrated into Notion workspace; indexes pages for contextual answers but only within Notion's cloud ecosystem .

- **[Glean](https://www.glean.com/)**  
  Enterprise search and knowledge discovery platform that connects to 100+ SaaS applications to build an organizational knowledge graph with AI-powered answers.

- **[Guru AI](https://www.getguru.com/)**  
  Knowledge management platform with AI-powered verification, card-based content, and Slack/Teams integration for internal team knowledge.

- **[Slite AI](https://slite.com/)**  
  Collaborative knowledge base with AI Q&A, automatic content suggestions, and team wiki features.

- **[Coda AI](https://coda.io/product/ai)**  
  AI-enhanced document platform combining docs, spreadsheets, and automation with AI summarization and content generation.

- **[Mem.ai](https://mem.ai/)**  
  AI-powered note-taking system with automatic organization, smart search, and self-organizing knowledge base capabilities; no self-host option available .

- **[Capacities](https://capacities.io/)**  
  Note-taking app with object-based organization (people, books, ideas) and AI-powered connections between notes.

- **[Tana](https://tana.inc/)**  
  Node-based knowledge management with AI-powered supertags, automatic meeting notes, and structured data capture.

- **[Roam Research](https://roamresearch.com/)**  
  Bi-directional linking note-taking tool with graph database foundation and AI features for networked thought.

- **[Obsidian Sync](https://obsidian.md/sync)**  
  Official sync service for Obsidian's local-first markdown vaults; end-to-end encrypted but AI features require third-party plugins or external tools.

## Open-Source GitHub Projects

- **[Onyx](https://github.com/onyx-dot-app/onyx)**  
  **Open-source alternative to Glean and enterprise ChatGPT** — ingests knowledge from connected applications (Google Drive, Slack, Confluence, etc.) to build an organizational context layer. Features contextual retrieval, advanced RAG, hybrid search, and AI-generated knowledge graphs. Made for security, data privacy, and self-hosting .

- **[Khoj](https://github.com/khoj-ai/khoj)**  
  **Self-hosted AI second brain** — indexes Obsidian vaults, org-mode files, PDFs, Word docs, GitHub repos, and Notion pages. Bring your own LLM (local or cloud). Docker Compose setup in ~30 minutes. AGPL-3.0 licensed. The only serious FOSS option for personal knowledge integration with local filesystems .

- **[OpenNexus](https://github.com/KiriAky107/OpenNexus)**  
  **Local-first AI notebook with knowledge retrieval and auditable agents** — Tauri 2 + Vue 3 desktop app with FastAPI AI Core for RAG, ASR, and agent loops. Features multi-agent collaboration, review/restore note changes, benchmark comparison, and MCP support. Strict security boundaries with path checking and keychain storage .

- **[KaaS (Knowledge as a Service)](https://github.com/Rainer51777/kaas)**  
  **Turns scattered notes, docs, and transcripts into a queryable Markdown wiki** — LLM knowledge-base compiler with MCP access. **No embeddings required** — uses LLM-powered compilation. Self-hosted with Docker, OpenAI-compatible API support (OpenAI, DeepSeek, Ollama, vLLM, Azure). Cross-platform binaries for Linux and macOS .

- **[LLM Wiki](https://github.com/nvk/llm-wiki)**  
  **Topic-based knowledge compiler with session memory** — ingests URLs, files, PDFs, and collections (Git repos, MediaWiki dumps, message archives). Features operational memory layer for session recovery, specialist skills, and collection adapters. Markdown-based, Obsidian-compatible .

- **[MemoryAgent](https://pypi.org/project/memoryagent-lib/)**  
  **Modular memory framework for LLM agents** — tiered memory (working, episodic, semantic, perceptual) with hot/cold storage, archive indexing, and confidence-based retrieval escalation. Local SQLite + sqlite-vec vector search. MIT licensed .

- **[Agent Memory OS](https://pypi.org/project/agent-memory-os/)**  
  **Local-first memory engine for AI agents** — single or multi-agent with shared/private memories, associative recall, memory lifecycle (decay, pinning, expiry), and per-agent recall profiles. SQLite FTS5 as source of truth with optional turbovec vector sidecar. Zero core dependencies .

- **[MemoryOS](https://aihub.caict.ac.cn/codes/BAI-LAB/MemoryOS)**  
  **Large model memory operating system from Beijing University of Posts and Telecommunications** — hierarchical storage with short-term, mid-term, and long-term persona memory. Automated user profile and knowledge updating. Achieved 49% F1 improvement on LoCoMo benchmark. Apache 2.0 licensed .

- **[MemOS](https://pypi.org/project/mem-os-python/)**  
  **TypeScript/Python memory OS with graph storage** — FTS5 search, typed edges, auto-linking, and LangChain/CrewAI/Ollama adapters. Local SQLite storage at ~/.memos/memos.db .

- **[Dewey](https://pkg.go.dev/github.com/unbound-force/dewey/v3)**  
  **MCP server for Obsidian and Logseq vaults** — compiles learnings into knowledge articles, lints for quality issues, promotes drafts after review. Go-based with Homebrew/RPM/go install. SQLite index at .uf/dewey/graph.db .

- **[Griot](https://pypi.org/project/griot-rag/)**  
  **Agent-first knowledge retrieval with MCP server** — indexes GitHub, GitLab, Bitbucket, Azure DevOps, and Gitea platforms. Credential storage in OS keychain. Designed for agent-assisted workflows with read-only tool permissions .

- **[nbrag](https://pypi.org/project/nbrag/)**  
  **Hybrid search RAG with MCP tools** — vector + BM25 → RRF → rerank pipeline. 11 retrieval tools plus navigation. AST-based Python definition finding. Supports HTTP mode for shared server processes .

### Additional Strong Open-Source Options

- **[OmniRAG](https://pypi.org/project/omnirag/)** — Universal RAG combining Liquid + Agentic + Chain architectures. 100% free with HuggingFace models and FAISS. CPU-friendly .
- **[SemantixRAG](https://pypi.org/project/semantixrag/)** — Enterprise RAG with GraphRAG (Neo4j), GuardRail compliance (PII detection, GDPR DSAR), and observability. Full Docker Compose stack .
- **[Flexible GraphRAG MCP](https://pypi.org/project/flexible-graphrag-mcp/)** — MCP server for GraphRAG with 14 data sources (filesystem, Alfresco, SharePoint, Box, Google Drive). OAuth2 bearer token support .
- **[Swafra](https://pypi.org/project/swafra/)** — Leiden-chunked graph-linked semantic memory as MCP server. Local embeddings with fastembed, no database required .
- **[GraphRAG (Microsoft)](https://github.com/microsoft/graphrag)** — MIT-licensed knowledge-graph-based RAG for complex question answering and corpus-level summarization .
- **[LlamaIndex KG](https://github.com/run-llama/llama_index)** — Knowledge graph integration for LlamaIndex with MIT license .
- **[KAG/OpenSPG](https://github.com/OpenSPG/KAG)** — Apache-2.0 licensed knowledge-augmented generation framework .

**Frameworks for building custom systems**: Combine **Onyx** for organizational context, **Khoj** for personal file indexing, **MemoryAgent** or **Agent Memory OS** for agent memory, and **MCP servers** (Dewey, Griot, nbrag) for agent tool integration. For GraphRAG, layer in **Neo4j** with **SemantixRAG** or **Microsoft GraphRAG**. For lightweight personal systems, **KaaS** with Ollama provides a no-embeddings, LLM-compiled wiki.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Knowledge systems handle sensitive personal and organizational data; ensure proper encryption, access controls, and compliance with GDPR/CCPA when self-hosting.
- **License awareness**: Khoj is AGPL-3.0 (network use requires open-sourcing modifications); MemoryOS is Apache-2.0; most others are MIT — verify terms before commercial deployment .
- Local-first tools require your own backup strategy; self-hosted solutions require infrastructure maintenance and security updates.

---

**Made for knowledge workers, researchers, AI engineers, and privacy-conscious organizations.**  
Let's make knowledge systems more open, local-first, and vendor-neutral.
