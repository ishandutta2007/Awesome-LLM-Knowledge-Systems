# Awesome-LLM-Knowledge-Systems

## Top LLM Knowledge Systems Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Personal Knowledge Management, Organizational Context Layers & Agent Memory Systems*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **LLM Knowledge Systems**. These tools transform scattered notes, documents, and organizational knowledge into queryable, AI-augmented knowledge bases — enabling retrieval-augmented generation (RAG), agent memory, and context-aware AI assistants.



**Examples** include Notion AI, Glean, Guru AI, Slite AI, Coda AI, Mem.ai, Capacities, Tana, Roam Research, and Obsidian Sync (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, local-first knowledge management, and transparent agent memory — ideal for researchers, teams, and individuals building vendor-neutral, privacy-preserving knowledge systems.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

  - [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

### Sector Overview & Market Dynamics

**Market size:** The knowledge-management software market is estimated at **$20.1B in 2024** and forecast to reach **$62.2B by 2033 (13.6% CAGR)** by Grand View Research (Mordor Intelligence models a smaller $13.7B for 2025, 18.3% CAGR to 2031) — while the AI-native slice, generative AI in enterprise knowledge management & search, is the fast lane: **$6.18B in 2025 → $27.4B by 2031 at ~28.6% CAGR**.

**Fragmentation vs. concentration:** Classic KM tooling is a **moderately fragmented** market — no winner-take-all dynamic, with a long tail of point solutions (Notion, Obsidian, Roam, Slite) coexisting alongside broader suites, and Mordor rating provider concentration as "medium." The newer AI search / organizational-knowledge layer is **moderately concentrated and platform-led** — Microsoft 365 Copilot, Google, AWS, Salesforce and Glean take most of the enterprise mind-share — but it is not yet winner-take-all: specialists and open-source alternatives keep winning segments.

Pricing verified as of October 2026. Rows are **sorted by company size (descending)** — latest publicly known revenue/valuation figures (estimates from third parties are marked as such). "Free tier" states the exact free-forever limits, or the length/limits of the free trial when no free plan exists.

| Product | Company Size (revenue / valuation) | Description | Pricing (cheapest paid plan) | Free Tier / Trial Limits |
| --- | --- | --- | --- | --- |
| **[Notion AI](https://www.notion.so/product/ai)** | **≈$11B valuation (Jan 2026)**; $500M+ annualized revenue (2025) | AI writing assistant and Q&A system integrated into Notion workspace; indexes pages for contextual answers but only within Notion's cloud ecosystem. | **Business (AI included): $20/seat/mo billed annually** ($24/mo monthly); standalone AI credit packs at **$10 per 1,000 monthly credits**. | **Free plan**: unlimited blocks for a 1-person workspace; **1,000-block cap** for workspaces with 2+ members; 10 guests; files ≤5 MB; limited complimentary AI answers. **30-day** Business trial for eligible teams. |
| **[Glean](https://www.glean.com/)** | **≈$7.2B valuation (Jun 2025)**; $100M+ ARR (FY ending Jan 2025) | Enterprise search and knowledge discovery platform that connects to 100+ SaaS applications to build an organizational knowledge graph with AI-powered answers. | **Enterprise contract, sales-quoted** — no public self-serve per-seat price published. | **No free-forever plan**; demo-led **time-boxed POC trial arranged with sales** (duration/limits not published; confirmed only via sales in the website terms). |
| **[Coda AI](https://coda.io/product/ai)** *(now Superhuman Docs)* | **≈$1.4B valuation (2021 Series D)**; acquired by Grammarly (Dec 2024) | AI-enhanced document platform combining docs, spreadsheets, and automation with AI summarization and content generation (acquired by Grammarly, 2024). | **Pro: $12/Doc Maker/mo billed annually** ($15 monthly); **Business: $33/Doc Maker/mo annual**; editors & viewers free. | **Free plan**: unlimited members; shared docs capped at **50 objects and 1,000 table rows**, **1 GB/doc** attachments, **10 MB/file**; AI on a limited free credit allotment. |
| **[Roam Research](https://roamresearch.com/)** | ≈$200M valuation (2020); ≈$5M revenue (2024 est.) | Bi-directional linking note-taking tool with graph database foundation and AI features for networked thought. | **Pro: $165/yr per user** (≈$13.75/mo); or **$15/mo** billed monthly. | **No free-forever plan**; **31-day free trial**. |
| **[Mem.ai](https://mem.ai/)** | ≈$110M valuation (Nov 2022, $23.5M round) | AI-powered note-taking system with automatic organization, smart search, and self-organizing knowledge base capabilities; no self-host option available. Now positioned as an AI "chief of staff" (Mem Agent). | **Mem Plus: $9/mo** (monthly billing shown). | **Free plan**: **25 messages** to Mem Agent + **25 new notes per month**. |
| **[Tana](https://tana.inc/)** | ≈$100M valuation (Feb 2025, $14M Series A) | Node-based knowledge management with AI-powered supertags, automatic meeting notes, and structured data capture. | **Pro: $20/user/mo early-bird** ($30/user/mo regular rate). | **Free plan**: **5 AI-transcribed/summarized meetings/mo**, **1 connected calendar**, **50 AI queries**; **30-day Pro trial**, no credit card. |
| **[Guru AI](https://www.getguru.com/)** | ≈$63M revenue (2023, 3rd-party est.); ~$30M total funding | Knowledge management platform with AI-powered verification, card-based content, and Slack/Teams integration for internal team knowledge. | **Custom scoped contract (sales-quoted)** — the former public Starter ($10/seat class) per-seat tiers are no longer listed. | **No public free plan currently** (the earlier Starter tier was free for the **first 10 users**); **no published trial length** on the live pricing page. |
| **[Obsidian Sync](https://obsidian.md/sync)** | ≈$25M ARR (2026, unverified est.); independent & user-supported | Official sync service for Obsidian's local-first markdown vaults; end-to-end encrypted but AI features require third-party plugins or external tools. | **Sync Standard: $4/user/mo billed annually** ($5 monthly) — 1 vault, 1 GB storage, 5 MB max file, 1 month version history. | **Obsidian app is free forever** for personal and commercial use (local-first markdown, no device limits); the **Sync service itself has no free tier**; optional one-time **$25 Catalyst** license. |
| **[Slite AI](https://slite.com/)** | ≈$5.5M revenue (2024 est.); ~32 employees | Collaborative knowledge base with AI Q&A, automatic content suggestions, and team wiki features. | **Basic: $10/user/mo billed annually**; **Pro: $20/user/mo billed annually** (30 AI questions/mo on Basic; 50 credits/seat/mo on Pro). | **No free-forever plan**; **14-day free trial**, no credit card, full Basic/Pro feature access. |
| **[Capacities](https://capacities.io/)** | ≈$0.4M revenue (2025 est.); bootstrapped, ~4 employees | Note-taking app with object-based organization (people, books, ideas) and AI-powered connections between notes. | **Pro: $9.99/mo billed yearly** (Believer tier from $12.49/mo; students 40% off ≈ $5.99/mo). | **Free plan**: unlimited spaces, objects and blocks; sync on all devices; **5 GB total media storage, then 100 MB/mo**. |

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
