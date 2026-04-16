# Awesome MCP

![Awesome](https://raw.githubusercontent.com/abordage/schemas/main/badges/awesome.svg)
[![Last update](https://img.shields.io/github/last-commit/abordage/awesome-mcp?label=last%20update)](README.md)
![Repositories](https://img.shields.io/badge/repositories-1,271-06b6d4)
![Total Stars](https://img.shields.io/badge/total%20stars-915,318-gold)
[![License](https://img.shields.io/github/license/abordage/awesome-mcp)](LICENSE)

**Automated. Curated. Ranked.**

[Model Context Protocol (MCP)](https://modelcontextprotocol.io/) servers, clients, and frameworks — the open standard for connecting AI assistants to external data sources and tools. This awesome list is automatically maintained with daily GitHub API updates. Projects are re-ranked daily based on current activity metrics.

**Daily process:** Merge community PRs → Scan repos → Filter stale projects → Recalculate scores → Rebuild list

- [AI Agents](#ai-agents)
  - [Code Assistants](#code-assistants)
  - [Human-in-the-Loop](#human-in-the-loop)
  - [Multi-Agent](#multi-agent)
  - [Reasoning & Prompts](#reasoning--prompts)
- [AI Memory & RAG](#ai-memory--rag)
  - [Memory](#memory)
  - [RAG](#rag)
- [AI Platforms](#ai-platforms)
- [Aggregators & Gateways](#aggregators--gateways)
  - [Aggregators](#aggregators)
  - [Gateways & Proxies](#gateways--proxies)
  - [Platforms & Registries](#platforms--registries)
- [Browser Automation](#browser-automation)
  - [AI Automation](#ai-automation)
  - [Browser Tools](#browser-tools)
  - [Cloud Services](#cloud-services)
  - [DevTools](#devtools)
  - [Playwright](#playwright)
- [CLI Tools](#cli-tools)
- [CRM & ERP](#crm--erp)
- [Cloud & Infrastructure](#cloud--infrastructure)
  - [AWS](#aws)
  - [Cloud Platforms](#cloud-platforms)
  - [Kubernetes](#kubernetes)
  - [Virtualization & IaC](#virtualization--iac)
- [Communication & Messaging](#communication--messaging)
  - [Apple Messages](#apple-messages)
  - [Email](#email)
  - [Messengers](#messengers)
  - [Notifications](#notifications)
  - [Team Chat](#team-chat)
  - [Voice & Telephony](#voice--telephony)
- [Data & Analytics](#data--analytics)
  - [AI/ML Platforms](#aiml-platforms)
  - [Data APIs](#data-apis)
  - [Data Exploration](#data-exploration)
  - [Data Platforms](#data-platforms)
  - [Jupyter & Notebooks](#jupyter--notebooks)
  - [Visualization](#visualization)
- [Databases](#databases)
  - [Analytics & Warehouses](#analytics--warehouses)
  - [Cache & Key-Value](#cache--key-value)
  - [Cloud Platforms](#cloud-platforms)
  - [Graph Databases](#graph-databases)
  - [Multi-Database Tools](#multi-database-tools)
  - [NoSQL & Document](#nosql--document)
  - [SQL Databases](#sql-databases)
  - [Search Engines](#search-engines)
  - [Spreadsheets & No-Code](#spreadsheets--no-code)
  - [Streaming & Messaging](#streaming--messaging)
  - [Time-Series & Metrics](#time-series--metrics)
  - [Vector Databases](#vector-databases)
- [Developer Tools](#developer-tools)
  - [API Tools](#api-tools)
  - [CI/CD & DevOps](#cicd--devops)
  - [Code Analysis](#code-analysis)
  - [Debuggers](#debuggers)
  - [Design & UI](#design--ui)
  - [Diagrams](#diagrams)
  - [Documentation](#documentation)
  - [IDE & Editors](#ide--editors)
  - [MCP SDKs](#mcp-sdks)
  - [Mobile Development](#mobile-development)
  - [OpenAPI](#openapi)
  - [Package Managers](#package-managers)
  - [Robotics & Automation](#robotics--automation)
  - [Task Management](#task-management)
  - [Testing & QA](#testing--qa)
  - [Utilities](#utilities)
  - [Version Control](#version-control)
- [Embedded & IoT](#embedded--iot)
- [File Systems & Storage](#file-systems--storage)
- [Finance](#finance)
  - [Accounting & Budgeting](#accounting--budgeting)
  - [Crypto & Blockchain](#crypto--blockchain)
  - [Payments & Banking](#payments--banking)
  - [Stock Data & Analytics](#stock-data--analytics)
  - [Trading & Exchanges](#trading--exchanges)
- [Frameworks & SDKs](#frameworks--sdks)
- [Gaming](#gaming)
- [Healthcare & Bioinformatics](#healthcare--bioinformatics)
- [LLM Bridges](#llm-bridges)
- [Location & Maps](#location--maps)
  - [GIS](#gis)
  - [IP Geolocation](#ip-geolocation)
  - [Maps & Navigation](#maps--navigation)
  - [Weather](#weather)
- [MCP Clients](#mcp-clients)
- [Marketing & Analytics](#marketing--analytics)
- [Media Processing](#media-processing)
  - [3D & Animation](#3d--animation)
  - [Audio & Music](#audio--music)
  - [Image Generation](#image-generation)
  - [Image Processing](#image-processing)
  - [Video](#video)
- [Monitoring & Observability](#monitoring--observability)
- [Productivity](#productivity)
  - [Atlassian](#atlassian)
  - [Collaboration](#collaboration)
  - [Documents](#documents)
  - [Google Workspace](#google-workspace)
  - [Helpdesk & Support](#helpdesk--support)
  - [Learning & Flashcards](#learning--flashcards)
  - [Microsoft 365](#microsoft-365)
  - [Note-taking & Docs](#note-taking--docs)
  - [Notion](#notion)
  - [Obsidian](#obsidian)
  - [Project Management](#project-management)
  - [Tasks & Calendar](#tasks--calendar)
  - [Wiki & Collaboration](#wiki--collaboration)
- [Research & Science](#research--science)
- [Sandboxing & Execution](#sandboxing--execution)
- [Search & Extraction](#search--extraction)
  - [Academic Research](#academic-research)
  - [Data APIs](#data-apis)
  - [News & Content](#news--content)
  - [Web Search Engines](#web-search-engines)
- [Security](#security)
  - [Identity & Access](#identity--access)
  - [MCP Security](#mcp-security)
  - [Network & Firewall](#network--firewall)
  - [Pentesting & OSINT](#pentesting--osint)
  - [Reverse Engineering](#reverse-engineering)
  - [SIEM & SecOps](#siem--secops)
- [Social Media](#social-media)
- [Sports](#sports)
- [Text-to-Speech](#text-to-speech)
- [Translation](#translation)
- [Travel & Transport](#travel--transport)
- [Web Scraping](#web-scraping)


## AI Agents

### Code Assistants

- [oraios/serena](https://github.com/oraios/serena) — Semantic code retrieval and editing toolkit ☆`23,007`
- [zilliztech/claude-context](https://github.com/zilliztech/claude-context) — Code search for Claude Code agents ☆`5,939`
- [CodeGraphContext/CodeGraphContext](https://github.com/CodeGraphContext/CodeGraphContext) — Code graph indexing for AI context ☆`2,970`
- [ezyang/codemcp](https://github.com/ezyang/codemcp) — Coding assistant MCP for Claude Desktop ☆`1,615`
- [ref-tools/ref-tools-mcp](https://github.com/ref-tools/ref-tools-mcp) — Reference tools for coding agents ☆`1,079`
- [SDGLBL/mcp-claude-code](https://github.com/SDGLBL/mcp-claude-code) — MCP implementation of Claude Code capabilities and more ☆`298`
- [stippi/code-assistant](https://github.com/stippi/code-assistant) — LLM-powered autonomous coding assistant ☆`160`
- [lamemind/mcp-server-multiverse](https://github.com/lamemind/mcp-server-multiverse) — MCP server for multiverse context management ☆`76`
- [wende/cicada](https://github.com/wende/cicada) — AI Coders search blindly. Be their guide. ☆`35`
- [gabrielmaialva33/winx-code-agent](https://github.com/gabrielmaialva33/winx-code-agent) — MCP-powered code agent for development ☆`26`
- [x51xxx/codex-mcp-tool](https://github.com/x51xxx/codex-mcp-tool) — Claude/Cursor to Codex CLI bridge with multi-turn sessions ☆`21`
- [VertexStudio/developer](https://github.com/VertexStudio/developer) — File editing, shell execution, screen capture ☆`19`
### Human-in-the-Loop

- [ttommyth/interactive-mcp](https://github.com/ttommyth/interactive-mcp) — Interactive MCP server for human-in-the-loop AI ☆`342`
- [RapidataAI/human-use](https://github.com/RapidataAI/human-use) — Enable AI to ask anyone anything ☆`72`
- [gotohuman/gotohuman-mcp-server](https://github.com/gotohuman/gotohuman-mcp-server) — Human approvals for AI agentic workflows ☆`54`
- [nazar256/user-prompt-mcp](https://github.com/nazar256/user-prompt-mcp) — User input requests for Cursor ☆`21`
### Multi-Agent

- [rinadelph/Agent-MCP](https://github.com/rinadelph/Agent-MCP) — Multi-agent AI collaboration framework ☆`1,219`
- [roboticforce/sugar](https://github.com/roboticforce/sugar) — Persistent memory for AI coding agents. Cross-session context, global knowledge, and autonomous task execution. ☆`70`
### Reasoning & Prompts

- [PV-Bhat/vibe-check-mcp-server](https://github.com/PV-Bhat/vibe-check-mcp-server) — Mentor-like feedback tool preventing AI over-engineering ☆`481`
- [Rai220/think-mcp](https://github.com/Rai220/think-mcp) — MCP Server for reasoning ☆`99`
- [hyperb1iss/lucidity-mcp](https://github.com/hyperb1iss/lucidity-mcp) — MCP server for enhanced AI clarity and reasoning ☆`84`
- [YuChenSSR/multi-ai-advisor-mcp](https://github.com/YuChenSSR/multi-ai-advisor-mcp) — council of models for decision ☆`78`
- [nikkoxgonzales/crash-mcp](https://github.com/nikkoxgonzales/crash-mcp) — Structured reasoning with step validation ☆`68`
- [ooples/token-optimizer-mcp](https://github.com/ooples/token-optimizer-mcp) — Token optimization with caching and compression ☆`48`
- [gwbischof/free-will-mcp](https://github.com/gwbischof/free-will-mcp) — Experimental AI self-prompting MCP server ☆`36`
- [vasayxtx/mcp-prompt-engine](https://github.com/vasayxtx/mcp-prompt-engine) — MCP Prompt Engine ☆`16`
- [aquarius-wing/actor-critic-thinking-mcp](https://github.com/aquarius-wing/actor-critic-thinking-mcp) — Dual-perspective thinking analysis server ☆`32`
- [abhinav-mangla/inner-monologue-mcp](https://github.com/abhinav-mangla/inner-monologue-mcp) — Inner Monologue MCP Server ☆`17`
## AI Memory & RAG

### Memory

- [vectorize-io/hindsight](https://github.com/vectorize-io/hindsight) — Hindsight: Agent Memory That Learns ☆`9,337`
- [basicmachines-co/basic-memory](https://github.com/basicmachines-co/basic-memory) — AI conversations that remember context ☆`2,870`
- [gannonh/memento-mcp](https://github.com/gannonh/memento-mcp) — Memento MCP: A Knowledge Graph Memory System for LLMs ☆`413`
- [agentic-box/memora](https://github.com/agentic-box/memora) — Persistent shared memories in SQLite ☆`391`
- [CheMiguel23/MemoryMesh](https://github.com/CheMiguel23/MemoryMesh) — MCP server for knowledge graph memory ☆`339`
- [jean-technologies/jean-memory](https://github.com/jean-technologies/jean-memory) — AI memory with mem0 and graphiti ☆`169`
- [pi22by7/In-Memoria](https://github.com/pi22by7/In-Memoria) — Persistent Intelligence Infrastructure for AI Agents ☆`165`
- [redleaves/context-keeper](https://github.com/redleaves/context-keeper) — Intelligent memory and context for AI agents ☆`143`
- [knowall-ai/mcp-neo4j-agent-memory](https://github.com/knowall-ai/mcp-neo4j-agent-memory) — Memory management using Neo4j graphs ☆`67`
- [peless/claude-thread-continuity](https://github.com/peless/claude-thread-continuity) — Save and restore project context ☆`66`
- [hungryrobot1/MCP-PIF](https://github.com/hungryrobot1/MCP-PIF) — Personal intelligence framework in Haskell ☆`57`
- [ukkit/memcord](https://github.com/ukkit/memcord) — MCP server for memory and context management ☆`41`
- [Yuchen20/Memory-Plus](https://github.com/Yuchen20/Memory-Plus) — Enhanced persistent memory management ☆`56`
- [skydeckai/mcp-server-rememberizer](https://github.com/skydeckai/mcp-server-rememberizer) — An MCP Server to enable global access to Rememberizer ☆`35`
- [JamesANZ/memory-mcp](https://github.com/JamesANZ/memory-mcp) — A simple MCP server that stores and retrieves memories from multiple LLMs. ☆`16`
- [hubertciebiada/context-crystallizer](https://github.com/hubertciebiada/context-crystallizer) — Large repos into AI-consumable knowledge for agents ☆`17`
- [ssmirnovpro/extended-memory-mcp](https://github.com/ssmirnovpro/extended-memory-mcp) — Cross-session persistent memory for Claude Desktop ☆`19`
- [unibaseio/membase-mcp](https://github.com/unibaseio/membase-mcp) — Decentralized memory layer for AI agents ☆`17`
### RAG

- [apecloud/ApeRAG](https://github.com/apecloud/ApeRAG) — Production GraphRAG with multi-modal ☆`1,144`
- [dmayboroda/minima](https://github.com/dmayboroda/minima) — On-premises conversational RAG with configurable containers ☆`1,041`
- [GreatScottyMac/context-portal](https://github.com/GreatScottyMac/context-portal) — Memory bank MCP with knowledge graph ☆`761`
- [graphlit/graphlit-mcp-server](https://github.com/graphlit/graphlit-mcp-server) — Model Context Protocol (MCP) Server for Graphlit Platform ☆`374`
- [hannesrudolph/mcp-ragdocs](https://github.com/hannesrudolph/mcp-ragdocs) — MCP server for RAG document retrieval ☆`257`
- [shinpr/mcp-local-rag](https://github.com/shinpr/mcp-local-rag) — MCP server for local RAG operations ☆`222`
- [ragieai/ragie-mcp-server](https://github.com/ragieai/ragie-mcp-server) — Ragie Model Context Protocol Server ☆`87`
- [needle-ai/needle-mcp](https://github.com/needle-ai/needle-mcp) — Needle MCP Server for easy RAG.Long-term memory for LLMs. ☆`97`
- [run-llama/mcp-server-llamacloud](https://github.com/run-llama/mcp-server-llamacloud) — LlamaCloud managed indexes connection ☆`86`
- [nonatofabio/local_faiss_mcp](https://github.com/nonatofabio/local_faiss_mcp) — Local FAISS MCP - semantic search for Claude/Copilot ☆`27`
- [pinecone-io/assistant-mcp](https://github.com/pinecone-io/assistant-mcp) — Pinecone Assistant MCP server ☆`41`
- [vectara/vectara-mcp](https://github.com/vectara/vectara-mcp) — Open source MCP server for Vectara ☆`27`
- [agentset-ai/mcp-server](https://github.com/agentset-ai/mcp-server) — Agentset MCP Server - Build RAG with Agentic superpowers ☆`26`
- [renl/mcp-rag-local](https://github.com/renl/mcp-rag-local) — Local RAG with Ollama embeddings and ChromaDB ☆`18`
## AI Platforms

- [Kiln-AI/Kiln](https://github.com/Kiln-AI/Kiln) — Build AI systems with Evals, RAG, Agents, fine-tuning ☆`4,753`
- [paiml/paiml-mcp-agent-toolkit](https://github.com/paiml/paiml-mcp-agent-toolkit) — Pragmatic AI Labs toolkit for deterministic agents ☆`148`
- [IBM/wxflows](https://github.com/IBM/wxflows) — watsonx.ai Flows AI app tutorials ☆`117`
- [TheRaLabs/legion-mcp](https://github.com/TheRaLabs/legion-mcp) — MCP server for Legion AI platform ☆`88`
- [ai-1st/deepview-mcp](https://github.com/ai-1st/deepview-mcp) — MCP server for DeepView AI analysis ☆`67`
- [PromptExecution/just-mcp](https://github.com/PromptExecution/just-mcp) — mcp server for just ☆`48`
- [atlanhq/agent-toolkit](https://github.com/atlanhq/agent-toolkit) — Atlan AI Agent Toolkit ☆`29`
- [OctoMind-dev/octomind-mcp](https://github.com/OctoMind-dev/octomind-mcp) — An MCP server for octomind tools, resources and prompts ☆`22`
- [StitchAI/stitch-ai-mcp](https://github.com/StitchAI/stitch-ai-mcp) — Decentralized Knowledge Hub for AI ☆`37`
- [DumplingAI/mcp-server-dumplingai](https://github.com/DumplingAI/mcp-server-dumplingai) — MCP (Model Context Protocol) server for Dumpling AI ☆`29`
- [sequa-ai/sequa-mcp](https://github.com/sequa-ai/sequa-mcp) — MCP server for Sequa AI platform ☆`21`
- [PV-Bhat/gemsuite-mcp](https://github.com/PV-Bhat/gemsuite-mcp) — MCP server for GemSuite tools ☆`29`
- [iflytek/ifly-workflow-mcp-server](https://github.com/iflytek/ifly-workflow-mcp-server) — MCP server for iFlytek workflows ☆`27`
## Aggregators & Gateways

### Aggregators

- [mindsdb/mindsdb](https://github.com/mindsdb/mindsdb) — Query Engine for AI Analytics - self-reasoning agents on live data ☆`38,988`
- [metatool-ai/metamcp](https://github.com/metatool-ai/metamcp) — MCP Aggregator, Orchestrator, Middleware, Gateway in one docker ☆`2,216`
- [mcpjungle/MCPJungle](https://github.com/mcpjungle/MCPJungle) — Self-hosted MCP Gateway for AI agents ☆`963`
- [1mcp-app/agent](https://github.com/1mcp-app/agent) — Unified MCP server aggregator ☆`413`
- [K-Dense-AI/claude-skills-mcp](https://github.com/K-Dense-AI/claude-skills-mcp) — Claude Agent Skills vector search ☆`375`
- [Intelligent-Internet/gemini-cli-mcp-openai-bridge](https://github.com/Intelligent-Internet/gemini-cli-mcp-openai-bridge) — Gemini CLI to MCP/OpenAI bridge ☆`137`
- [sitbon/magg](https://github.com/sitbon/magg) — Magg: The MCP Aggregator ☆`133`
- [wanaku-ai/wanaku](https://github.com/wanaku-ai/wanaku) — Wanaku MCP Router ☆`109`
- [badkk/awesome-crypto-mcp-servers](https://github.com/badkk/awesome-crypto-mcp-servers) — A collection of crypto MCP servers. ☆`131`
- [portel-dev/ncp](https://github.com/portel-dev/ncp) — Natural Context Provider with smart MCP tool loading ☆`81`
- [askbudi/roundtable](https://github.com/askbudi/roundtable) — Zero-config MCP unifying multiple AI coding assistants ☆`99`
- [nguyenvanduocit/all-in-one-model-context-protocol](https://github.com/nguyenvanduocit/all-in-one-model-context-protocol) — GitLab, Jira, Confluence, YouTube ☆`103`
- [VeriTeknik/pluggedin-mcp](https://github.com/VeriTeknik/pluggedin-mcp) — Plugged.in MCP Server manages all your other MCPs in one MCP. ☆`50`
- [hamidra/yamcp](https://github.com/hamidra/yamcp) — Local MCP workspace organization ☆`65`
- [membranehq/mcp-server](https://github.com/membranehq/mcp-server) — MCP Server for Membrane ☆`35`
- [gotoolkits/mcp-difyworkflow-server](https://github.com/gotoolkits/mcp-difyworkflow-server) — MCP server for Dify workflow invocation ☆`59`
- [bh-rat/context-awesome](https://github.com/bh-rat/context-awesome) — awesome-lists now available as MCP server for you agent. ☆`47`
- [waystation-ai/mcp](https://github.com/waystation-ai/mcp) — No-code secure MCP integration hub ☆`45`
- [wojtyniak/mcp-mcp](https://github.com/wojtyniak/mcp-mcp) — Meta-MCP for tool discovery and provisioning ☆`22`
- [nazar256/combine-mcp](https://github.com/nazar256/combine-mcp) — MCP aggregator combining multiple servers into one interface ☆`32`
- [glenngillen/mcpmcp-server](https://github.com/glenngillen/mcpmcp-server) — MCP server aggregator and router ☆`31`
- [agree-able/room-mcp](https://github.com/agree-able/room-mcp) — Coordinate agents using rooms ☆`22`
### Gateways & Proxies

- [apache/apisix](https://github.com/apache/apisix) — The Cloud-Native API Gateway and AI Gateway ☆`16,453`
- [sparfenyuk/mcp-proxy](https://github.com/sparfenyuk/mcp-proxy) — A bridge between Streamable HTTP and stdio MCP transports ☆`2,426`
- [stacklok/toolhive](https://github.com/stacklok/toolhive) — Runtime and gateway for deploying MCP servers in containers ☆`1,716`
- [tbxark/mcp-proxy](https://github.com/tbxark/mcp-proxy) — Aggregate multiple MCP servers via HTTP ☆`677`
- [smart-mcp-proxy/mcpproxy-go](https://github.com/smart-mcp-proxy/mcpproxy-go) — Supercharge AI Agents, Safely ☆`187`
- [ssut/Remote-MCP](https://github.com/ssut/Remote-MCP) — Type-safe solution for remote MCP communication ☆`205`
- [sxhxliang/mcp-access-point](https://github.com/sxhxliang/mcp-access-point) — Convert any web server to MCP instantly ☆`169`
- [toolprint/hypertool-mcp](https://github.com/toolprint/hypertool-mcp) — Expose tools based on Agent Persona ☆`151`
- [VeriTeknik/pluggedin-mcp-proxy](https://github.com/VeriTeknik/pluggedin-mcp-proxy) — Unified MCP proxy managing multiple MCPs ☆`127`
- [tigranbs/mcgravity](https://github.com/tigranbs/mcgravity) — Proxy for composing multiple MCP servers into one endpoint ☆`93`
- [universal-mcp/universal-mcp](https://github.com/universal-mcp/universal-mcp) — Middleware for API applications ☆`25`
- [pyroprompts/mcp-stdio-to-streamable-http-adapter](https://github.com/pyroprompts/mcp-stdio-to-streamable-http-adapter) — STDIO to Streamable HTTP proxy ☆`26`
- [webrix-ai/secure-mcp-gateway](https://github.com/webrix-ai/secure-mcp-gateway) — Secure OAuth gateway for MCP authentication ☆`18`
- [nick1udwig/ws-mcp](https://github.com/nick1udwig/ws-mcp) — MCP server with WebSocket transport ☆`19`
### Platforms & Registries

- [archestra-ai/archestra](https://github.com/archestra-ai/archestra) — Enterprise AI Platform with guardrails, MCP registry, gateway & orchestrator ☆`3,564`
- [metorial/metorial](https://github.com/metorial/metorial) — Connect any AI model to 600+ integrations; powered by MCP ☆`3,248`
- [chatmcp/mcpso](https://github.com/chatmcp/mcpso) — directory for Awesome MCP Servers ☆`1,993`
- [julien040/anyquery](https://github.com/julien040/anyquery) — SQL queries for GitHub, Notion, +40 more ☆`1,664`
- [jaw9c/awesome-remote-mcp-servers](https://github.com/jaw9c/awesome-remote-mcp-servers) — Remote MCP Servers ☆`1,042`
- [boltmcp/boltmcp](https://github.com/boltmcp/boltmcp) — Open standard and registry for converting web APIs into MCP servers ☆`343`
- [milisp/mcp-linker](https://github.com/milisp/mcp-linker) — Sync MCP configs across clients ☆`304`
- [liuyoshio/mcp-compass](https://github.com/liuyoshio/mcp-compass) — MCP discovery and recommendation ☆`229`
- [integromat/make-mcp-server](https://github.com/integromat/make-mcp-server) — Make MCP Server ☆`154`
- [Jeamee/MCPHub-Desktop](https://github.com/Jeamee/MCPHub-Desktop) — Desktop APP for Discover and Install MCP Servers ☆`148`
- [juspay/neurolink](https://github.com/juspay/neurolink) — Universal AI platform with MCP and multi-provider support ☆`79`
- [matthewdcage/cursor-mcp-installer](https://github.com/matthewdcage/cursor-mcp-installer) — Install MCPs in Cursor from git URL ☆`75`
- [rust-mcp-stack/mcp-discovery](https://github.com/rust-mcp-stack/mcp-discovery) — CLI for discovering MCP server capabilities ☆`82`
- [useparagon/paragon-mcp](https://github.com/useparagon/paragon-mcp) — Access 130+ SaaS integrations via ActionKit ☆`46`
- [VeyraX/veyrax-mcp](https://github.com/VeyraX/veyrax-mcp) — VeyraX unified tool access via single MCP ☆`49`
## Browser Automation

### AI Automation

- [Skyvern-AI/skyvern](https://github.com/Skyvern-AI/skyvern) — Automate browser based workflows with AI ☆`21,161`
- [nottelabs/notte](https://github.com/nottelabs/notte) — Framework to build web agents ☆`1,932`
- [imprvhub/mcp-browser-agent](https://github.com/imprvhub/mcp-browser-agent) — MCP server for autonomous browser automation with Claude ☆`37`
- [getrupt/ashra-mcp](https://github.com/getrupt/ashra-mcp) — A Model Context Protocol server for Ashra ☆`60`
- [desplega-ai/qa-use](https://github.com/desplega-ai/qa-use) — Agent-first E2E testing CLI ☆`20`
### Browser Tools

- [BrowserMCP/mcp](https://github.com/BrowserMCP/mcp) — Browser control for AI applications ☆`6,350`
- [kontext-security/browser-use-mcp-server](https://github.com/kontext-security/browser-use-mcp-server) — Browse the web, directly from Cursor etc. ☆`818`
- [ndthanhdev/mcp-browser-kit](https://github.com/ndthanhdev/mcp-browser-kit) — AI assistants interact with local browser ☆`51`
- [onllm-dev/onUI](https://github.com/onllm-dev/onUI) — Browser extension and MCP server for annotation-first UI pair programming with AI agents ☆`43`
- [BB-fat/browser-use-rs](https://github.com/BB-fat/browser-use-rs) — Rust-based browser automation MCP server ☆`34`
### Cloud Services

- [browserbase/mcp-server-browserbase](https://github.com/browserbase/mcp-server-browserbase) — Browser control with Browserbase ☆`3,258`
- [hyperbrowserai/mcp](https://github.com/hyperbrowserai/mcp) — A MCP server implementation for hyperbrowser ☆`755`
- [browserstack/mcp-server](https://github.com/browserstack/mcp-server) — BrowserStack's Official MCP Server ☆`136`
- [kernel/kernel-mcp-server](https://github.com/kernel/kernel-mcp-server) — Secure cloud-browser automation on Kernel ☆`28`
### DevTools

- [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp) — Chrome DevTools for coding agents ☆`35,330`
- [eyalzh/browser-control-mcp](https://github.com/eyalzh/browser-control-mcp) — Browser control via extension for AI agents ☆`268`
- [mozilla/firefox-devtools-mcp](https://github.com/mozilla/firefox-devtools-mcp) — MCP server for Firefox DevTools integration ☆`114`
### Playwright

- [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) — Playwright MCP server ☆`30,917`
- [executeautomation/mcp-playwright](https://github.com/executeautomation/mcp-playwright) — MCP server for Playwright browser testing ☆`5,436`
- [VikashLoomba/MCP-Server-Playwright](https://github.com/VikashLoomba/MCP-Server-Playwright) — MCP server for browser automation using Playwright ☆`284`
- [blackwhite084/playwright-plus-python-mcp](https://github.com/blackwhite084/playwright-plus-python-mcp) — Enhanced Playwright browser automation ☆`183`
- [kimtth/mcp-aoai-web-browsing](https://github.com/kimtth/mcp-aoai-web-browsing) — Azure OpenAI with Playwright browser control ☆`32`
## CLI Tools

- [wonderwhy-er/DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP) — Terminal control, file search, diff editing ☆`5,901`
- [IBM/mcp-cli](https://github.com/IBM/mcp-cli) — Feature-rich CLI for interacting with MCP servers ☆`1,945`
- [rusiaaman/wcgw](https://github.com/rusiaaman/wcgw) — Shell and coding agent on mcp clients ☆`655`
- [ferrislucas/iterm-mcp](https://github.com/ferrislucas/iterm-mcp) — iTerm command execution for REPL/CLI ☆`549`
- [baryhuang/mcp-remote-macos-use](https://github.com/baryhuang/mcp-remote-macos-use) — AI agent for full Mac control ☆`473`
- [peakmojo/applescript-mcp](https://github.com/peakmojo/applescript-mcp) — Execute AppleScript for Mac control ☆`448`
- [wong2/mcp-cli](https://github.com/wong2/mcp-cli) — A CLI inspector for the Model Context Protocol ☆`429`
- [tufantunc/ssh-mcp](https://github.com/tufantunc/ssh-mcp) — SSH control for Linux servers ☆`386`
- [classfang/ssh-mcp-server](https://github.com/classfang/ssh-mcp-server) — SSH MCP server included in official repo ☆`324`
- [claude-did-this/MCPControl](https://github.com/claude-did-this/MCPControl) — MCP server for Windows OS automation ☆`313`
- [nickgnd/tmux-mcp](https://github.com/nickgnd/tmux-mcp) — A MCP server for our beloved terminal multiplexer tmux. ☆`259`
- [g0t4/mcp-server-commands](https://github.com/g0t4/mcp-server-commands) — MCP server to run commands (runProcess tool) ☆`224`
- [domdomegg/computer-use-mcp](https://github.com/domdomegg/computer-use-mcp) — Full computer control for AI models ☆`213`
- [dvcrn/mcp-server-siri-shortcuts](https://github.com/dvcrn/mcp-server-siri-shortcuts) — MCP for calling Siri Shorcuts from LLMs ☆`183`
- [tumf/mcp-shell-server](https://github.com/tumf/mcp-shell-server) — Shell execution with whitelisted commands ☆`173`
- [MladenSU/cli-mcp-server](https://github.com/MladenSU/cli-mcp-server) — CLI with secure execution and custom policies ☆`168`
- [AB498/computer-control-mcp](https://github.com/AB498/computer-control-mcp) — Mouse, keyboard, OCR via PyAutoGUI ☆`136`
- [automateyournetwork/pyATS_MCP](https://github.com/automateyournetwork/pyATS_MCP) — An MCP Server for pyATS (experimental) ☆`70`
- [sonirico/mcp-shell](https://github.com/sonirico/mcp-shell) — Secure, auditable shell commands for AI ☆`71`
- [inercia/MCPShell](https://github.com/inercia/MCPShell) — Use shell scripts as MCP tools ☆`62`
- [NakaokaRei/swift-mcp-gui](https://github.com/NakaokaRei/swift-mcp-gui) — Keyboard and mouse control on macOS ☆`57`
- [nihalxkumar/arch-mcp](https://github.com/nihalxkumar/arch-mcp) — Arch Linux MCP (Model Context Protocol) Server ☆`36`
- [ooples/mcp-console-automation](https://github.com/ooples/mcp-console-automation) — MCP for AI-driven console automation and monitoring ☆`28`
- [maxim-saplin/mcp_safe_local_python_executor](https://github.com/maxim-saplin/mcp_safe_local_python_executor) — Safe Python executor from smolagents ☆`44`
- [InsForge/insforge-mcp](https://github.com/InsForge/insforge-mcp) — MCP server for InsForge - full-stack builders for coding agents ☆`23`
- [PhialsBasement/CMD-MCP-Server](https://github.com/PhialsBasement/CMD-MCP-Server) — CMD command execution for Claude agents ☆`24`
- [Beer-Bears/scaffold](https://github.com/Beer-Bears/scaffold) — Structural RAG system for large codebases ☆`16`
- [erniebrodeur/mcp-grep](https://github.com/erniebrodeur/mcp-grep) — simple mcp server to wrap the local instance of grep. ☆`24`
- [JoshuaRileyDev/mac-apps-launcher](https://github.com/JoshuaRileyDev/mac-apps-launcher) — Launch and manage macOS applications ☆`18`
## CRM & ERP

- [ivnvxd/mcp-server-odoo](https://github.com/ivnvxd/mcp-server-odoo) — MCP server for Odoo ERP integration ☆`244`
- [GeLi2001/shopify-mcp](https://github.com/GeLi2001/shopify-mcp) — Shopify API for Claude and Cursor ☆`194`
- [smn2gnt/MCP-Salesforce](https://github.com/smn2gnt/MCP-Salesforce) — MCP Salesforce connector ☆`173`
- [tsmztech/mcp-server-salesforce](https://github.com/tsmztech/mcp-server-salesforce) — Salesforce MCP Server ☆`152`
- [augmnt/augments-mcp-server](https://github.com/augmnt/augments-mcp-server) — MCP server for Augments AI platform ☆`120`
- [baryhuang/mcp-hubspot](https://github.com/baryhuang/mcp-hubspot) — HubSpot CRM integration for AI assistants ☆`121`
- [tomaspavlin/rohlik-mcp](https://github.com/tomaspavlin/rohlik-mcp) — Shop groceries on Rohlik Group platforms ☆`106`
- [mafzaal/d365fo-client](https://github.com/mafzaal/d365fo-client) — Client for Microsoft Dynamics 365 F&O ☆`27`
- [AiondaDotCom/mcp-salesforce](https://github.com/AiondaDotCom/mcp-salesforce) — Complete MCP (Model Context Protocol) server for Salesforce integration with Claude Desktop. Provides seamless OAuth authentication, universal CRUD operations on any Salesforce object. ☆`16`
## Cloud & Infrastructure

### AWS

- [awslabs/mcp](https://github.com/awslabs/mcp) — AWS MCP servers for AI assistants ☆`8,782`
- [alexei-led/aws-mcp-server](https://github.com/alexei-led/aws-mcp-server) — AWS CLI in containerized environment ☆`181`
- [aarora79/aws-cost-explorer-mcp-server](https://github.com/aarora79/aws-cost-explorer-mcp-server) — MCP server for understanding AWS spend ☆`126`
- [rishikavikondala/mcp-server-aws](https://github.com/rishikavikondala/mcp-server-aws) — MCP server for AWS resource operations ☆`127`
- [aws-samples/sample-mcp-server-s3](https://github.com/aws-samples/sample-mcp-server-s3) — Retrieve PDFs and data from AWS S3 ☆`78`
- [aws-powertools/powertools-mcp](https://github.com/aws-powertools/powertools-mcp) — Powertools for AWS's official MCP Server ☆`43`
- [localstack/localstack-mcp-server](https://github.com/localstack/localstack-mcp-server) — LocalStack AWS emulation ☆`23`
- [baryhuang/mcp-server-aws-resources-python](https://github.com/baryhuang/mcp-server-aws-resources-python) — Run boto3 code to manage AWS resources ☆`24`
- [trilogy-group/aws-pricing-mcp](https://github.com/trilogy-group/aws-pricing-mcp) — AWS EC2 pricing search by CPU, RAM, network ☆`20`
### Cloud Platforms

- [cloudflare/mcp-server-cloudflare](https://github.com/cloudflare/mcp-server-cloudflare) — Cloudflare services management ☆`3,612`
- [microsoft/azure-devops-mcp](https://github.com/microsoft/azure-devops-mcp) — Azure DevOps integration for AI agents ☆`1,571`
- [TencentCloudBase/CloudBase-MCP](https://github.com/TencentCloudBase/CloudBase-MCP) — Connect CloudBase to AI agents ☆`991`
- [GoogleCloudPlatform/cloud-run-mcp](https://github.com/GoogleCloudPlatform/cloud-run-mcp) — MCP server to deploy apps to Cloud Run ☆`591`
- [babelcloud/gbox](https://github.com/babelcloud/gbox) — AI control for Android, browser, desktop ☆`172`
- [aliyun/alibaba-cloud-ops-mcp-server](https://github.com/aliyun/alibaba-cloud-ops-mcp-server) — AlibabaCloud CloudOps MCP Server ☆`109`
- [aliyun/alibabacloud-devops-mcp-server](https://github.com/aliyun/alibabacloud-devops-mcp-server) — MCP server for Alibaba Yunxiao DevOps platform ☆`93`
- [heroku/heroku-mcp-server](https://github.com/heroku/heroku-mcp-server) — Heroku Platform MCP Server using the Heroku CLI ☆`77`
- [vantage-sh/vantage-mcp-server](https://github.com/vantage-sh/vantage-mcp-server) — Fetch costs and usage from Vantage ☆`79`
- [dkruyt/mcp-hetzner](https://github.com/dkruyt/mcp-hetzner) — Hetzner Cloud management ☆`95`
- [aliyun/alibabacloud-dataworks-mcp-server](https://github.com/aliyun/alibabacloud-dataworks-mcp-server) — Alibaba Cloud DataWorks API integration ☆`35`
- [aliyun/alibabacloud-hologres-mcp-server](https://github.com/aliyun/alibabacloud-hologres-mcp-server) — MCP server for Alibaba Hologres data warehouse ☆`32`
- [aantti/mcp-netbird](https://github.com/aantti/mcp-netbird) — Netbird network management ☆`45`
- [kestra-io/mcp-server-python](https://github.com/kestra-io/mcp-server-python) — Python MCP for Kestra AI Agents ☆`24`
- [call518/MCP-OpenStack-Ops](https://github.com/call518/MCP-OpenStack-Ops) — MCP server providing OpenStack project management ☆`23`
- [redis/mcp-redis-cloud](https://github.com/redis/mcp-redis-cloud) — MCP server for Redis Cloud database operations ☆`39`
- [qiniu/qiniu-mcp-server](https://github.com/qiniu/qiniu-mcp-server) — Qiniu Cloud storage, CDN, and media processing ☆`35`
- [api7/apisix-mcp](https://github.com/api7/apisix-mcp) — APISIX gateway for LLM integration ☆`36`
- [Azure-Samples/mcp](https://github.com/Azure-Samples/mcp) — Samples and resources for Azure MCP ☆`40`
- [pibblokto/cert-manager-mcp-server](https://github.com/pibblokto/cert-manager-mcp-server) — MCP Server for cert-manager ☆`23`
- [hardik-id/azure-resource-graph-mcp-server](https://github.com/hardik-id/azure-resource-graph-mcp-server) — Azure Resource Graph query interface ☆`17`
- [higress-group/higress-ops-mcp-server](https://github.com/higress-group/higress-ops-mcp-server) — Higress API gateway configuration management ☆`22`
- [kocierik/consul-mcp-server](https://github.com/kocierik/consul-mcp-server) — A consul MCP Server (modelcontextprotocol) ☆`16`
### Kubernetes

- [containers/kubernetes-mcp-server](https://github.com/containers/kubernetes-mcp-server) — Kubernetes and OpenShift management ☆`1,445`
- [Flux159/mcp-server-kubernetes](https://github.com/Flux159/mcp-server-kubernetes) — MCP Server for kubernetes management commands ☆`1,377`
- [rohitg00/kubectl-mcp-server](https://github.com/rohitg00/kubectl-mcp-server) — Kubernetes cluster chat with Claude/Cursor ☆`869`
- [weibaohui/k8m](https://github.com/weibaohui/k8m) — Mini Kubernetes AI Dashboard ☆`806`
- [strowk/mcp-k8s-go](https://github.com/strowk/mcp-k8s-go) — Go-based Kubernetes connection ☆`379`
- [vfarcic/dot-ai](https://github.com/vfarcic/dot-ai) — Deploy apps to any Kubernetes cluster ☆`311`
- [alexei-led/k8s-mcp-server](https://github.com/alexei-led/k8s-mcp-server) — Kubernetes cluster management ☆`207`
- [reza-gholizade/k8s-mcp-server](https://github.com/reza-gholizade/k8s-mcp-server) — Kubernetes cluster management ☆`153`
- [weibaohui/kom](https://github.com/weibaohui/kom) — Kubernetes SDK wrapping kubectl ☆`148`
- [silenceper/mcp-k8s](https://github.com/silenceper/mcp-k8s) — Kubernetes cluster interaction ☆`143`
- [portainer/portainer-mcp](https://github.com/portainer/portainer-mcp) — Portainer container management ☆`138`
- [StacklokLabs/mkp](https://github.com/StacklokLabs/mkp) — MKP Kubernetes MCP server ☆`57`
- [cyclops-ui/mcp-cyclops](https://github.com/cyclops-ui/mcp-cyclops) — Cyclops Kubernetes management ☆`30`
- [wenhuwang/mcp-k8s-eye](https://github.com/wenhuwang/mcp-k8s-eye) — Kubernetes diagnosis and management ☆`28`
### Virtualization & IaC

- [hashicorp/terraform-mcp-server](https://github.com/hashicorp/terraform-mcp-server) — Terraform ecosystem integration for AI ☆`1,327`
- [nwiizo/tfmcp](https://github.com/nwiizo/tfmcp) — Terraform AI-assisted infrastructure ☆`362`
- [1Panel-dev/mcp-1panel](https://github.com/1Panel-dev/mcp-1panel) — MCP server for 1Panel management ☆`146`
- [kocierik/mcp-nomad](https://github.com/kocierik/mcp-nomad) — A nomad MCP Server (modelcontextprotocol) ☆`47`
- [bright8192/esxi-mcp-server](https://github.com/bright8192/esxi-mcp-server) — MCP server for VMware ESXi management ☆`57`
- [jokemanfire/mcp-containerd](https://github.com/jokemanfire/mcp-containerd) — Use mcp to manage containerd(developing) ☆`53`
- [openstack-kr/python-openstackmcp-server](https://github.com/openstack-kr/python-openstackmcp-server) — openstack mcp server ☆`18`
- [severity1/terraform-cloud-mcp](https://github.com/severity1/terraform-cloud-mcp) — Terraform Cloud API integration ☆`23`
## Communication & Messaging

### Apple Messages

- [mattt/iMCP](https://github.com/mattt/iMCP) — Access Messages, Contacts, Reminders on Mac ☆`1,371`
- [carterlasalle/mac_messages_mcp](https://github.com/carterlasalle/mac_messages_mcp) — MCP server for secure iMessage database access on macOS ☆`269`
- [hannesrudolph/imessage-query-fastmcp-mcp-server](https://github.com/hannesrudolph/imessage-query-fastmcp-mcp-server) — Safe iMessage database queries ☆`77`
- [wyattjoh/imessage-mcp](https://github.com/wyattjoh/imessage-mcp) — iMessage data reading from macOS ☆`24`
### Email

- [elie222/inbox-zero](https://github.com/elie222/inbox-zero) — AI email assistant for inbox zero ☆`10,458`
- [MadLlama25/fastmail-mcp](https://github.com/MadLlama25/fastmail-mcp) — Access to Fastmail API for AI assistants ☆`106`
- [ZilongXue/claude-post](https://github.com/ZilongXue/claude-post) — Email management via natural language ☆`112`
- [mailtrap/mailtrap-mcp](https://github.com/mailtrap/mailtrap-mcp) — Official mailtrap.io MCP server ☆`58`
- [Shy2593666979/mcp-server-email](https://github.com/Shy2593666979/mcp-server-email) — Email with attachments for Gmail, Outlook, QQ ☆`74`
- [mailgun/mailgun-mcp-server](https://github.com/mailgun/mailgun-mcp-server) — Mailgun API integration ☆`52`
- [egyptianego17/email-mcp-server](https://github.com/egyptianego17/email-mcp-server) — Send emails with attachments via SMTP ☆`27`
### Messengers

- [lharries/whatsapp-mcp](https://github.com/lharries/whatsapp-mcp) — WhatsApp MCP server ☆`5,510`
- [chigwell/telegram-mcp](https://github.com/chigwell/telegram-mcp) — MCP server for Telegram messaging ☆`934`
- [line/line-bot-mcp-server](https://github.com/line/line-bot-mcp-server) — LINE Messaging API for AI agents ☆`574`
- [chaindead/telegram-mcp](https://github.com/chaindead/telegram-mcp) — Telegram dialogs, messages, drafts, statuses ☆`317`
- [ztxtxwd/open-feishu-mcp-server](https://github.com/ztxtxwd/open-feishu-mcp-server) — Feishu/Lark OAuth and document management ☆`85`
- [areweai/tsgram-mcp](https://github.com/areweai/tsgram-mcp) — Telegram for local Claude Code debug ☆`88`
- [pubnub/pubnub-mcp-server](https://github.com/pubnub/pubnub-mcp-server) — PubNub Model Context Protocol Server ☆`30`
- [mjknowles/matrix-mcp-server](https://github.com/mjknowles/matrix-mcp-server) — Matrix server integration and chat ☆`39`
- [DLHellMe/telegram-mcp-server](https://github.com/DLHellMe/telegram-mcp-server) — Scrape and analyze Telegram content ☆`30`
### Notifications

- [gitmotion/ntfy-me-mcp](https://github.com/gitmotion/ntfy-me-mcp) — MCP server for ntfy push notifications ☆`56`
- [Cactusinhand/mcp_server_notify](https://github.com/Cactusinhand/mcp_server_notify) — Send system notification when Agent task is done. ☆`51`
- [aahl/mcp-notify](https://github.com/aahl/mcp-notify) — Notify to Weixin, Telegram, Bark, Lark, DingTalk ☆`31`
- [infobip/mcp](https://github.com/infobip/mcp) — Infobip Remote MCP Servers Documentation ☆`29`
- [teddyzxcv/ntfy-mcp](https://github.com/teddyzxcv/ntfy-mcp) — MCP server for ntfy push notifications ☆`44`
- [AshikNesin/pushover-mcp](https://github.com/AshikNesin/pushover-mcp) — A MCP implementation for sending notifications via Pushover ☆`34`
### Team Chat

- [korotovsky/slack-mcp-server](https://github.com/korotovsky/slack-mcp-server) — MCP server for Slack workspace integration ☆`1,535`
- [chatmcp/mcp-server-chatsum](https://github.com/chatmcp/mcp-server-chatsum) — Query and Summarize your chat messages. ☆`1,034`
- [joinly-ai/joinly](https://github.com/joinly-ai/joinly) — Make your meetings accessible to AI Agents ☆`492`
- [SaseQ/discord-mcp](https://github.com/SaseQ/discord-mcp) — MCP server for Discord integration ☆`263`
- [v-3/discordmcp](https://github.com/v-3/discordmcp) — Discord MCP Server for Claude Integration ☆`196`
- [discourse/discourse-mcp](https://github.com/discourse/discourse-mcp) — MCP client for Discourse sites ☆`52`
- [zencoderai/slack-mcp-server](https://github.com/zencoderai/slack-mcp-server) — Slack workspace interaction and messaging ☆`66`
- [jagan-shanmugam/mattermost-mcp-host](https://github.com/jagan-shanmugam/mattermost-mcp-host) — Mattermost integration with LangGraph agent ☆`31`
### Voice & Telephony

- [gerkensm/callcenter.js-mcp](https://github.com/gerkensm/callcenter.js-mcp) — Callcenter.JS AI Voice Agent VOIP Connector, MCP + CLI ☆`18`
## Data & Analytics

### AI/ML Platforms

- [MigoXLab/dingo](https://github.com/MigoXLab/dingo) — AI data, model, app quality evaluation ☆`677`
- [evalstate/mcp-hfspace](https://github.com/evalstate/mcp-hfspace) — HuggingFace Spaces integration ☆`385`
- [YanxingLiu/dify-mcp-server](https://github.com/YanxingLiu/dify-mcp-server) — Model Context Protocol (MCP) Server for dify workflows ☆`275`
- [0xshellming/mcp-summarizer](https://github.com/0xshellming/mcp-summarizer) — MCP Server for AI Summarization ☆`159`
- [ChronulusAI/chronulus-mcp](https://github.com/ChronulusAI/chronulus-mcp) — Chronulus AI forecasting and prediction agents ☆`108`
- [optuna/optuna-mcp](https://github.com/optuna/optuna-mcp) — Optuna hyperparameter optimization ☆`73`
- [zenml-io/mcp-zenml](https://github.com/zenml-io/mcp-zenml) — ZenML MLOps platform connection ☆`44`
- [arrismo/kaggle-mcp](https://github.com/arrismo/kaggle-mcp) — MCP server for Kaggle ☆`35`
- [kumo-ai/kumo-rfm-mcp](https://github.com/kumo-ai/kumo-rfm-mcp) — MCP server to query KumoRFM in your agentic flows ☆`31`
- [privetin/dataset-viewer](https://github.com/privetin/dataset-viewer) — MCP server for Hugging Face dataset viewer ☆`30`
- [HumanSignal/label-studio-mcp-server](https://github.com/HumanSignal/label-studio-mcp-server) — MCP server for Label Studio data labeling ☆`30`
### Data APIs

- [YangLiangwei/PersonalizationMCP](https://github.com/YangLiangwei/PersonalizationMCP) — Personal data hub for AI from Steam, YouTube, Bilibili ☆`51`
- [anshumax/world_bank_mcp_server](https://github.com/anshumax/world_bank_mcp_server) — World Bank open data API ☆`46`
- [explorium-ai/mcp-explorium](https://github.com/explorium-ai/mcp-explorium) — Explorium B2B Data - MCP Server ☆`21`
### Data Exploration

- [reading-plus-ai/mcp-server-data-exploration](https://github.com/reading-plus-ai/mcp-server-data-exploration) — Interactive CSV data exploration ☆`532`
- [kdqed/zaturn](https://github.com/kdqed/zaturn) — Data Analysis With Vibes ☆`73`
- [brightlikethelight/networkx-mcp-server](https://github.com/brightlikethelight/networkx-mcp-server) — First NetworkX MCP server for graph analysis in AI conversations | Community & Enterprise editions | Graph algorithms • Network analysis • MCP integration ☆`16`
- [santoshray02/csv-editor](https://github.com/santoshray02/csv-editor) — AI-powered CSV data manipulation and analysis ☆`22`
### Data Platforms

- [dbt-labs/dbt-mcp](https://github.com/dbt-labs/dbt-mcp) — A MCP (Model Context Protocol) server for interacting with dbt. ☆`538`
- [kubeflow/mcp-apache-spark-history-server](https://github.com/kubeflow/mcp-apache-spark-history-server) — Apache Spark History Server bridge ☆`150`
- [microsoft/fabric-rti-mcp](https://github.com/microsoft/fabric-rti-mcp) — Fabric Real-Time Intelligence server ☆`109`
- [keboola/mcp-server](https://github.com/keboola/mcp-server) — Model Context Protocol (MCP) Server for the Keboola Platform ☆`84`
- [acryldata/mcp-server-datahub](https://github.com/acryldata/mcp-server-datahub) — Official MCP server for DataHub ☆`72`
- [RafaelCartenet/mcp-databricks-server](https://github.com/RafaelCartenet/mcp-databricks-server) — AI agents interact with Databricks ☆`40`
- [JordiNeil/mcp-databricks-server](https://github.com/JordiNeil/mcp-databricks-server) — MCP Server for Databricks ☆`47`
- [thoughtspot/mcp-server](https://github.com/thoughtspot/mcp-server) — The ThoughtSpot MCP Server ☆`30`
- [aywengo/kafka-schema-reg-mcp](https://github.com/aywengo/kafka-schema-reg-mcp) — Kafka Schema Registry management ☆`30`
- [growthbook/growthbook-mcp](https://github.com/growthbook/growthbook-mcp) — GrowthBook flags and experiments ☆`22`
- [syucream/lightdash-mcp-server](https://github.com/syucream/lightdash-mcp-server) — Access to Lightdash analytics ☆`25`
- [yangkyeongmo/mcp-server-openmetadata](https://github.com/yangkyeongmo/mcp-server-openmetadata) — OpenMetadata integration for data catalog ☆`23`
- [mattijsdp/dbt-docs-mcp](https://github.com/mattijsdp/dbt-docs-mcp) — dbt documentation interaction ☆`23`
- [datumnova/ms-fabric-mcp](https://github.com/datumnova/ms-fabric-mcp) —  ☆`16`
- [ognis1205/mcp-server-unitycatalog](https://github.com/ognis1205/mcp-server-unitycatalog) — Unity Catalog AI Model Context Protocol Server ☆`16`
### Jupyter & Notebooks

- [datalayer/jupyter-mcp-server](https://github.com/datalayer/jupyter-mcp-server) — Model Context Protocol (MCP) Server for Jupyter. ☆`1,017`
- [jjsantos01/jupyter-notebook-mcp](https://github.com/jjsantos01/jupyter-notebook-mcp) — A Model Context Protocol (MCP) for Jupyter Notebook ☆`126`
- [phisanti/MCPR](https://github.com/phisanti/MCPR) — AI agents in interactive R sessions ☆`24`
### Visualization

- [antvis/mcp-server-chart](https://github.com/antvis/mcp-server-chart) — 25+ visual charts using @antvis for data analysis ☆`3,966`
- [hustcc/mcp-echarts](https://github.com/hustcc/mcp-echarts) — ECharts visual charts with AI ☆`223`
- [isaacwasserman/mcp-vegalite-server](https://github.com/isaacwasserman/mcp-vegalite-server) — MCP server for Vega-Lite data visualization ☆`96`
- [palewire/datawrapper-mcp](https://github.com/palewire/datawrapper-mcp) — Create Datawrapper charts with AI ☆`34`
## Databases

### Analytics & Warehouses

- [ClickHouse/mcp-clickhouse](https://github.com/ClickHouse/mcp-clickhouse) — Connect ClickHouse to your AI assistants. ☆`753`
- [motherduckdb/mcp-server-motherduck](https://github.com/motherduckdb/mcp-server-motherduck) — Local MCP server for DuckDB and MotherDuck ☆`464`
- [Snowflake-Labs/mcp](https://github.com/Snowflake-Labs/mcp) — Snowflake Cortex AI and SQL orchestration ☆`274`
- [isaacwasserman/mcp-snowflake-server](https://github.com/isaacwasserman/mcp-snowflake-server) — MCP server for Snowflake database queries ☆`180`
- [ktanaka101/mcp-server-duckdb](https://github.com/ktanaka101/mcp-server-duckdb) — DuckDB database interaction ☆`172`
- [ergut/mcp-bigquery-server](https://github.com/ergut/mcp-bigquery-server) — MCP server for Google BigQuery integration ☆`137`
- [LucasHild/mcp-server-bigquery](https://github.com/LucasHild/mcp-server-bigquery) — Google BigQuery database access ☆`125`
- [pab1it0/adx-mcp-server](https://github.com/pab1it0/adx-mcp-server) — MCP server for Azure Data Explorer ☆`54`
- [aliyun/alibabacloud-adb-mysql-mcp-server](https://github.com/aliyun/alibabacloud-adb-mysql-mcp-server) — AnalyticDB for MySQL MCP Server ☆`31`
- [lishenxydlgzs/aws-athena-mcp](https://github.com/lishenxydlgzs/aws-athena-mcp) — MCP server to run AWS Athena queries ☆`40`
### Cache & Key-Value

- [redis/mcp-redis](https://github.com/redis/mcp-redis) — MCP server for Redis database operations ☆`484`
- [aliyun/alibabacloud-tablestore-mcp-server](https://github.com/aliyun/alibabacloud-tablestore-mcp-server) — MCP server for Alibaba Tablestore NoSQL ☆`155`
- [upstash/mcp-server](https://github.com/upstash/mcp-server) — Upstash Model Context Server ☆`53`
### Cloud Platforms

- [instantdb/instant](https://github.com/instantdb/instant) — Modern Firebase with real-time database ☆`10,106`
- [supabase-community/supabase-mcp](https://github.com/supabase-community/supabase-mcp) — Connect Supabase to your AI assistants ☆`2,612`
- [alexander-zuev/supabase-mcp-server](https://github.com/alexander-zuev/supabase-mcp-server) — MCP server for Supabase database and auth ☆`817`
- [neondatabase/mcp-server-neon](https://github.com/neondatabase/mcp-server-neon) — Neon Management API and databases ☆`580`
- [gannonh/firebase-mcp](https://github.com/gannonh/firebase-mcp) — Model Context Protocol (MCP) server for Firebase. ☆`244`
- [JoshuaRileyDev/supabase-mcp-server](https://github.com/JoshuaRileyDev/supabase-mcp-server) — MCP server for Supabase database operations ☆`50`
- [Aiven-Open/mcp-aiven](https://github.com/Aiven-Open/mcp-aiven) — Model Context Protocol server for Aiven ☆`16`
- [niledatabase/nile-mcp-server](https://github.com/niledatabase/nile-mcp-server) — Nile Database tenants, users, auth for LLMs ☆`17`
### Graph Databases

- [neo4j-contrib/mcp-neo4j](https://github.com/neo4j-contrib/mcp-neo4j) — Neo4j Labs Model Context Protocol servers ☆`935`
- [neo4j-contrib/gds-agent](https://github.com/neo4j-contrib/gds-agent) — Neo4j Graph Data Science tools ☆`78`
- [da-okazaki/mcp-neo4j-server](https://github.com/da-okazaki/mcp-neo4j-server) — mcp-neo4j-server ☆`58`
- [FalkorDB/FalkorDB-MCPServer](https://github.com/FalkorDB/FalkorDB-MCPServer) — Connect LLMs to FalkorDB ☆`34`
- [ravenwits/mcp-server-arangodb](https://github.com/ravenwits/mcp-server-arangodb) — ArangoDB database interaction ☆`46`
### Multi-Database Tools

- [googleapis/mcp-toolbox](https://github.com/googleapis/mcp-toolbox) — Open source database MCP toolbox ☆`14,601`
- [bytebase/dbhub](https://github.com/bytebase/dbhub) — Token-efficient multi-database MCP ☆`2,580`
- [damms005/devdb-vscode](https://github.com/damms005/devdb-vscode) — Zero-config VS Code database extension ☆`1,363`
- [Canner/wren-engine](https://github.com/Canner/wren-engine) — Semantic engine for MCP clients and AI ☆`646`
- [centralmind/gateway](https://github.com/centralmind/gateway) — Universal database MCP for LLMs ☆`523`
- [runekaagaard/mcp-alchemy](https://github.com/runekaagaard/mcp-alchemy) — MCP server for SQLAlchemy database operations ☆`400`
- [FreePeak/db-mcp-server](https://github.com/FreePeak/db-mcp-server) — MCP server for database operations ☆`365`
- [executeautomation/mcp-database-server](https://github.com/executeautomation/mcp-database-server) — Connect to SQLite, SQL Server, PostgreSQL ☆`340`
- [XGenerationLab/xiyan_mcp_server](https://github.com/XGenerationLab/xiyan_mcp_server) — Natural language database queries ☆`232`
- [s2-streamstore/s2-sdk-typescript](https://github.com/s2-streamstore/s2-sdk-typescript) — TypeScript SDK for S2, the durable streams API ☆`28`
- [schemacrawler/SchemaCrawler-AI-MCP-Server-Usage](https://github.com/schemacrawler/SchemaCrawler-AI-MCP-Server-Usage) — How to use SchemaCrawler AI MCP Server ☆`23`
- [prisma/mcp](https://github.com/prisma/mcp) — Prisma database workflows ☆`41`
- [fireproof-storage/mcp-database-server](https://github.com/fireproof-storage/mcp-database-server) — Store and load JSON documents from LLM tool use ☆`32`
- [datastrato/mcp-server-gravitino](https://github.com/datastrato/mcp-server-gravitino) — MCP server for Apache Gravitino ☆`21`
### NoSQL & Document

- [mongodb-js/mongodb-mcp-server](https://github.com/mongodb-js/mongodb-mcp-server) — Connect to MongoDB and Atlas clusters ☆`1,003`
- [kiliczsh/mcp-mongo-server](https://github.com/kiliczsh/mcp-mongo-server) — A Model Context Protocol Server for MongoDB ☆`277`
- [furey/mongodb-lens](https://github.com/furey/mongodb-lens) — MongoDB Lens: Full Featured MCP Server for MongoDB Databases ☆`201`
- [QuantGeekDev/mongo-mcp](https://github.com/QuantGeekDev/mongo-mcp) — A mongo db server for the model context protocol (MCP) ☆`174`
- [datastax/astra-db-mcp](https://github.com/datastax/astra-db-mcp) — An MCP server for Astra DB workloads ☆`39`
- [Couchbase-Ecosystem/mcp-server-couchbase](https://github.com/Couchbase-Ecosystem/mcp-server-couchbase) — Couchbase database cluster integration ☆`31`
### SQL Databases

- [crystaldba/postgres-mcp](https://github.com/crystaldba/postgres-mcp) — Postgres with read/write access and performance ☆`2,542`
- [benborla/mcp-server-mysql](https://github.com/benborla/mcp-server-mysql) — MCP server for MySQL database operations ☆`1,541`
- [designcomputer/mysql_mcp_server](https://github.com/designcomputer/mysql_mcp_server) — Secure MySQL database interaction ☆`1,218`
- [subnetmarco/pgmcp](https://github.com/subnetmarco/pgmcp) — An MCP server to query any Postgres database in natural language. ☆`528`
- [apache/doris-mcp-server](https://github.com/apache/doris-mcp-server) — Apache Doris MCP Server ☆`280`
- [wenb1n-dev/mysql_mcp_server_pro](https://github.com/wenb1n-dev/mysql_mcp_server_pro) — Enhanced MySQL with anomaly analysis ☆`252`
- [StarRocks/mcp-server-starrocks](https://github.com/StarRocks/mcp-server-starrocks) — StarRocks MCP (Model Context Protocol) Server ☆`166`
- [MariaDB/mcp](https://github.com/MariaDB/mcp) — MariaDB MCP (Model Context Protocol) server implementation ☆`163`
- [call518/MCP-PostgreSQL-Ops](https://github.com/call518/MCP-PostgreSQL-Ops) — PostgreSQL operations and monitoring ☆`147`
- [f4ww4z/mcp-mysql-server](https://github.com/f4ww4z/mcp-mysql-server) — A Model Context Protocol server for MySQL database operations ☆`159`
- [tuannvm/mcp-trino](https://github.com/tuannvm/mcp-trino) — High-performance Trino MCP in Go ☆`102`
- [oceanbase/awesome-oceanbase-mcp](https://github.com/oceanbase/awesome-oceanbase-mcp) — MCP Server for OceanBase database and its tools ☆`101`
- [jparkerweb/mcp-sqlite](https://github.com/jparkerweb/mcp-sqlite) — Comprehensive SQLite interaction ☆`97`
- [hannesrudolph/sqlite-explorer-fastmcp-mcp-server](https://github.com/hannesrudolph/sqlite-explorer-fastmcp-mcp-server) — Read-only SQLite database access ☆`104`
- [wenb1n-dev/SmartDB_MCP](https://github.com/wenb1n-dev/SmartDB_MCP) — Universal database MCP for MySQL, PostgreSQL, Oracle and more ☆`93`
- [donghao1393/mcp-dbutils](https://github.com/donghao1393/mcp-dbutils) — Multi-database connector for SQLite, MySQL, PostgreSQL ☆`87`
- [Teradata/teradata-mcp-server](https://github.com/Teradata/teradata-mcp-server) — Teradata database integration ☆`46`
- [aliyun/alibabacloud-rds-openapi-mcp-server](https://github.com/aliyun/alibabacloud-rds-openapi-mcp-server) — MCP server for RDS Services via OPENAPI. ☆`52`
- [Zhwt/go-mcp-mysql](https://github.com/Zhwt/go-mcp-mysql) — Go-based MCP server for MySQL ☆`51`
- [pingcap/pytidb](https://github.com/pingcap/pytidb) — TiDB AI SDK for apps and agents ☆`32`
- [singlestore-labs/mcp-server-singlestore](https://github.com/singlestore-labs/mcp-server-singlestore) — SingleStore database management API ☆`31`
- [ydb-platform/ydb-mcp](https://github.com/ydb-platform/ydb-mcp) — MCP server for YDB distributed database ☆`25`
- [isdaniel/pgtuner_mcp](https://github.com/isdaniel/pgtuner_mcp) — provides AI-powered PostgreSQL performance tuning capabilities. ☆`22`
- [panasenco/mcp-sqlite](https://github.com/panasenco/mcp-sqlite) — SQLite with Datasette metadata support ☆`18`
- [ahmedmustahid/postgres-mcp-server](https://github.com/ahmedmustahid/postgres-mcp-server) — MCP server for PostgreSQL ☆`31`
- [OpenLinkSoftware/mcp-sqlalchemy-server](https://github.com/OpenLinkSoftware/mcp-sqlalchemy-server) — ODBC server with FastAPI and SQLAlchemy ☆`23`
- [Xexr/mcp-libsql](https://github.com/Xexr/mcp-libsql) — MCP server for libSQL database ☆`20`
- [Dataring-engineering/mcp-server-trino](https://github.com/Dataring-engineering/mcp-server-trino) — MCP Server for Trino ☆`18`
- [c4pt0r/mcp-server-tidb](https://github.com/c4pt0r/mcp-server-tidb) — mcp server for tidb ☆`23`
- [abel9851/mcp-server-mariadb](https://github.com/abel9851/mcp-server-mariadb) — An mcp server that provides read-only access to MariaDB. ☆`19`
### Search Engines

- [elastic/mcp-server-elasticsearch](https://github.com/elastic/mcp-server-elasticsearch) — Elasticsearch queries and index management ☆`643`
- [cr7258/elasticsearch-mcp-server](https://github.com/cr7258/elasticsearch-mcp-server) — Elasticsearch and OpenSearch interaction ☆`266`
- [meilisearch/meilisearch-mcp](https://github.com/meilisearch/meilisearch-mcp) — Meilisearch interaction via LLM interfaces ☆`185`
- [opensearch-project/opensearch-mcp-server-py](https://github.com/opensearch-project/opensearch-mcp-server-py) — OpenSearch cluster interaction for AI ☆`120`
- [vectorize-io/vectorize-mcp-server](https://github.com/vectorize-io/vectorize-mcp-server) — Official Vectorize MCP Server ☆`105`
- [algolia/mcp](https://github.com/algolia/mcp) — MCP servers for interacting with Algolia ☆`28`
- [suhail-ak-2/mcp-typesense-server](https://github.com/suhail-ak-2/mcp-typesense-server) — Typesense search for AI assistants ☆`19`
### Spreadsheets & No-Code

- [baserow/baserow](https://github.com/baserow/baserow) — No-code database, apps, agents with AI ☆`4,647`
- [xing5/mcp-google-sheets](https://github.com/xing5/mcp-google-sheets) — Google Drive and Sheets integration ☆`807`
- [domdomegg/airtable-mcp-server](https://github.com/domdomegg/airtable-mcp-server) — Airtable bases integration for AI systems ☆`436`
- [rashidazarang/airtable-mcp](https://github.com/rashidazarang/airtable-mcp) — Airtable integration for AI applications ☆`77`
- [edwinbernadus/nocodb-mcp-server](https://github.com/edwinbernadus/nocodb-mcp-server) — nocodb mcp server ☆`66`
- [freema/mcp-gsheets](https://github.com/freema/mcp-gsheets) — Google Sheets read, write, manipulate ☆`52`
- [felores/airtable-mcp](https://github.com/felores/airtable-mcp) — Manage Airtable bases and records ☆`73`
### Streaming & Messaging

- [confluentinc/mcp-confluent](https://github.com/confluentinc/mcp-confluent) — MCP server for Confluent Kafka platform ☆`149`
- [tuannvm/kafka-mcp-server](https://github.com/tuannvm/kafka-mcp-server) — Apache Kafka server in Go ☆`48`
- [kenliao94/mcp-server-rabbitmq](https://github.com/kenliao94/mcp-server-rabbitmq) — MCP server for interacting with RabbitMQ ☆`37`
### Time-Series & Metrics

- [GreptimeTeam/greptimedb](https://github.com/GreptimeTeam/greptimedb) — Unified observability DB for metrics, logs, traces ☆`6,162`
- [pab1it0/prometheus-mcp-server](https://github.com/pab1it0/prometheus-mcp-server) — MCP server for Prometheus metrics ☆`412`
- [VictoriaMetrics/mcp-victorialogs](https://github.com/VictoriaMetrics/mcp-victorialogs) — VictoriaLogs log management integration ☆`65`
- [influxdata/influxdb3_mcp_server](https://github.com/influxdata/influxdb3_mcp_server) — MCP Server for InfluxDB 3 ☆`29`
- [GreptimeTeam/greptimedb-mcp-server](https://github.com/GreptimeTeam/greptimedb-mcp-server) — A Model Context Protocol (MCP) server for GreptimeDB ☆`27`
- [apache/iotdb-mcp-server](https://github.com/apache/iotdb-mcp-server) — Apache IoTDB MCP Server ☆`36`
- [idoru/influxdb-mcp-server](https://github.com/idoru/influxdb-mcp-server) — An MCP Server for querying InfluxDB ☆`35`
### Vector Databases

- [qdrant/mcp-server-qdrant](https://github.com/qdrant/mcp-server-qdrant) — Official Qdrant vector database MCP ☆`1,345`
- [chroma-core/chroma-mcp](https://github.com/chroma-core/chroma-mcp) — Chroma vector database capabilities ☆`534`
- [zilliztech/mcp-server-milvus](https://github.com/zilliztech/mcp-server-milvus) — Model Context Protocol Servers for Milvus ☆`226`
- [weaviate/mcp-server-weaviate](https://github.com/weaviate/mcp-server-weaviate) — MCP (Model Context Protocol) server for Weaviate ☆`161`
- [pinecone-io/pinecone-mcp](https://github.com/pinecone-io/pinecone-mcp) — Connect Pinecone to AI assistants ☆`64`
- [privetin/chroma](https://github.com/privetin/chroma) — MCP server for Chroma ☆`41`
## Developer Tools

### API Tools

- [tadata-org/fastapi_mcp](https://github.com/tadata-org/fastapi_mcp) — Expose FastAPI endpoints as MCP tools ☆`11,806`
- [WordPress/mcp-adapter](https://github.com/WordPress/mcp-adapter) — Bridge Abilities API to MCP ☆`887`
- [zcaceres/fetch-mcp](https://github.com/zcaceres/fetch-mcp) — A flexible HTTP fetching Model Context Protocol server. ☆`739`
- [automation-ai-labs/mcp-link](https://github.com/automation-ai-labs/mcp-link) — Convert Any OpenAPI V3 API to MCP Server ☆`602`
- [blurrah/mcp-graphql](https://github.com/blurrah/mcp-graphql) — Model Context Protocol server for GraphQL ☆`380`
- [apollographql/apollo-mcp-server](https://github.com/apollographql/apollo-mcp-server) — Apollo MCP Server ☆`277`
- [postmanlabs/postman-mcp-server](https://github.com/postmanlabs/postman-mcp-server) — Connect your AI to your APIs on Postman ☆`214`
- [MFYDev/ghost-mcp](https://github.com/MFYDev/ghost-mcp) — Interact with Ghost CMS via LLM ☆`168`
- [delano/postman-mcp-server](https://github.com/delano/postman-mcp-server) — An MCP server that provides access to Postman. ☆`147`
- [webflow/mcp-server](https://github.com/webflow/mcp-server) — Model Context Protocol (MCP) server for the Webflow Data API. ☆`123`
- [hostinger/api-mcp-server](https://github.com/hostinger/api-mcp-server) — MCP server for Hostinger API integration ☆`83`
- [ivo-toby/contentful-mcp](https://github.com/ivo-toby/contentful-mcp) — Contentful CMS Management API ☆`61`
- [shannonlal/mcp-postman](https://github.com/shannonlal/mcp-postman) — MCP Server for running Postman Collections with Newman ☆`83`
- [shanejonas/openrpc-mcp-server](https://github.com/shanejonas/openrpc-mcp-server) — JSON-RPC via OpenRPC ☆`43`
- [Kong/mcp-konnect](https://github.com/Kong/mcp-konnect) — Interact with Kong Konnect APIs ☆`40`
- [Omedia/mcp-server-drupal](https://github.com/Omedia/mcp-server-drupal) — Drupal MCP module companion ☆`50`
- [hannesj/mcp-graphql-schema](https://github.com/hannesj/mcp-graphql-schema) — GraphQL Schema Model Context Protocol Server ☆`45`
- [Arize-ai/text-to-graphql-mcp](https://github.com/Arize-ai/text-to-graphql-mcp) — MCP server for text-to-GraphQL conversion ☆`23`
- [xxxbrian/mcp-rquest](https://github.com/xxxbrian/mcp-rquest) — Browser-like HTTP with TLS fingerprinting ☆`44`
- [hijaz/postmancer](https://github.com/hijaz/postmancer) — REST client replacing Postman/Insomnia ☆`28`
- [Jktfe/serveMyAPI](https://github.com/Jktfe/serveMyAPI) — MCP server for custom API serving ☆`24`
- [fotoetienne/gqai](https://github.com/fotoetienne/gqai) — Turn any GraphQL endpoint into a set of MCP tools ☆`22`
- [drestrepom/mcp_graphql](https://github.com/drestrepom/mcp_graphql) — Interact with GraphQL APIs via MCP tools ☆`20`
### CI/CD & DevOps

- [czlonkowski/n8n-mcp](https://github.com/czlonkowski/n8n-mcp) — Build n8n workflows with AI assistants ☆`18,216`
- [leonardsellem/n8n-mcp-server](https://github.com/leonardsellem/n8n-mcp-server) — Tools for interacting with n8n API ☆`1,601`
- [ckreiling/mcp-server-docker](https://github.com/ckreiling/mcp-server-docker) — MCP server for Docker ☆`699`
- [utensils/mcp-nixos](https://github.com/utensils/mcp-nixos) — MCP-NixOS - Model Context Protocol Server for NixOS resources ☆`572`
- [QuantGeekDev/docker-mcp](https://github.com/QuantGeekDev/docker-mcp) — A docker MCP Server (modelcontextprotocol) ☆`469`
- [TencentEdgeOne/edgeone-pages-mcp](https://github.com/TencentEdgeOne/edgeone-pages-mcp) — Deploy HTML to EdgeOne Pages with public URL ☆`409`
- [jamsocket/forevervm](https://github.com/jamsocket/forevervm) — Stateful AI code sandboxes ☆`228`
- [yangkyeongmo/mcp-server-apache-airflow](https://github.com/yangkyeongmo/mcp-server-apache-airflow) — MCP server for Apache Airflow workflows ☆`158`
- [nacos-group/nacos-mcp-router](https://github.com/nacos-group/nacos-mcp-router) — MCP server discovery, install, and proxy ☆`176`
- [DefangLabs/defang](https://github.com/DefangLabs/defang) — MCP server for Defang cloud deployment ☆`151`
- [docker/hub-mcp](https://github.com/docker/hub-mcp) — Docker Hub MCP Server ☆`135`
- [jfrog/mcp-jfrog](https://github.com/jfrog/mcp-jfrog) — JFrog Platform repository management ☆`115`
- [OctopusDeploy/mcp-server](https://github.com/OctopusDeploy/mcp-server) — Octopus Deploy Official MCP Server ☆`95`
- [CircleCI-Public/mcp-server-circleci](https://github.com/CircleCI-Public/mcp-server-circleci) — MCP server for CircleCI CI/CD pipeline integration ☆`83`
- [Vortiago/mcp-azure-devops](https://github.com/Vortiago/mcp-azure-devops) — AI assistants with Azure DevOps ☆`79`
- [buildkite/buildkite-mcp-server](https://github.com/buildkite/buildkite-mcp-server) — Official MCP Server for Buildkite. ☆`50`
- [harness/mcp-server](https://github.com/harness/mcp-server) — This is the official repo for the Harness MCP server ☆`44`
- [call518/MCP-Airflow-API](https://github.com/call518/MCP-Airflow-API) — Apache Airflow API integration ☆`43`
- [bitrise-io/bitrise-mcp](https://github.com/bitrise-io/bitrise-mcp) — Bitrise CI/CD app and build management ☆`37`
- [IvanAmador/vercel-ai-docs-mcp](https://github.com/IvanAmador/vercel-ai-docs-mcp) — Vercel AI SDK documentation search ☆`48`
- [launchdarkly/mcp-server](https://github.com/launchdarkly/mcp-server) — LaunchDarkly's Model Context Protocol (MCP) Server ☆`20`
- [endorhq/cli](https://github.com/endorhq/cli) — Sandboxed environments for favorite services via MCP ☆`26`
- [leosepulveda/mcp-n8n](https://github.com/leosepulveda/mcp-n8n) — Complete n8n API integration for Claude Desktop and Cursor - 100 workflow templates with intelligent matching ☆`20`
- [axliupore/mcp-code-runner](https://github.com/axliupore/mcp-code-runner) — MCP server for executing code in Docker containers ☆`17`
### Code Analysis

- [bgauryy/octocode-mcp](https://github.com/bgauryy/octocode-mcp) — MCP server for semantic code search and context generation ☆`789`
- [SonarSource/sonarqube-mcp-server](https://github.com/SonarSource/sonarqube-mcp-server) — SonarQube MCP Server ☆`536`
- [admica/FileScopeMCP](https://github.com/admica/FileScopeMCP) — Codebase dependency diagrams ☆`288`
- [janreges/ai-distiller](https://github.com/janreges/ai-distiller) — Fast tool for extracting essential public information from code ☆`149`
- [st3v3nmw/sourcerer-mcp](https://github.com/st3v3nmw/sourcerer-mcp) — Semantic code search reducing token waste ☆`111`
- [micl2e2/code-to-tree](https://github.com/micl2e2/code-to-tree) — Source code to AST tree conversion ☆`82`
- [codacy/codacy-mcp-server](https://github.com/codacy/codacy-mcp-server) — Codacy's MCP Server implementation ☆`56`
- [CodeLogicIncEngineering/codelogic-mcp-server](https://github.com/CodeLogicIncEngineering/codelogic-mcp-server) — Codelogic software dependency analysis ☆`36`
- [azer/react-analyzer-mcp](https://github.com/azer/react-analyzer-mcp) — React code analysis and docs generation ☆`57`
- [cqfn/aibolit-mcp-server](https://github.com/cqfn/aibolit-mcp-server) — Aibolit Java static analyzer for AI agents ☆`25`
- [PromptExecution/rust-cargo-docs-rag-mcp](https://github.com/PromptExecution/rust-cargo-docs-rag-mcp) — MCP tools for Rust Context Engineering (rustdocs, rust analyzer) ☆`17`
- [vezlo/src-to-kb](https://github.com/vezlo/src-to-kb) — Convert source code to LLM ready knowledge base ☆`30`
- [j4c0bs/mcp-server-sql-analyzer](https://github.com/j4c0bs/mcp-server-sql-analyzer) — MCP server for SQL static analysis. ☆`30`
- [kandrwmrtn/cplusplus_mcp](https://github.com/kandrwmrtn/cplusplus_mcp) — MCP server for C++ codebase analysis using libclang ☆`27`
- [kuberstar/qartez-mcp](https://github.com/kuberstar/qartez-mcp) — Semantic code intelligence MCP server with 27 tools for project maps, symbol search, impact analysis, call hierarchies, architecture boundaries, and safe refactoring. Built in Rust. ([Website](https://qartez.dev))
### Debuggers

- [jasonjmcghee/claude-debugs-for-you](https://github.com/jasonjmcghee/claude-debugs-for-you) — Interactive debugging via MCP and VS Code ☆`507`
- [cameroncooke/reloaderoo](https://github.com/cameroncooke/reloaderoo) — Powerful MCP debugging proxy and CLI inspection tool. ☆`119`
- [stass/lldb-mcp](https://github.com/stass/lldb-mcp) — LLDB MCP server ☆`92`
- [pansila/mcp_server_gdb](https://github.com/pansila/mcp_server_gdb) — MCP Server to expose the GDB debugging capabilities ☆`63`
### Design & UI

- [GLips/Figma-Context-MCP](https://github.com/GLips/Figma-Context-MCP) — Figma layout info for AI coding agents ☆`14,374`
- [grab/cursor-talk-to-figma-mcp](https://github.com/grab/cursor-talk-to-figma-mcp) — Cursor and Figma communication ☆`6,656`
- [21st-dev/magic-mcp](https://github.com/21st-dev/magic-mcp) — Frontend development with AI like Magic ☆`4,721`
- [Jpisnice/shadcn-ui-mcp-server](https://github.com/Jpisnice/shadcn-ui-mcp-server) — MCP server for shadcn/ui component library ☆`2,746`
- [hustcc/mcp-mermaid](https://github.com/hustcc/mcp-mermaid) — Generate mermaid diagram and chart with AI MCP dynamically. ☆`525`
- [public-ui/kolibri](https://github.com/public-ui/kolibri) — The accessible HTML-Standard ☆`254`
- [mastergo-design/mastergo-magic-mcp](https://github.com/mastergo-design/mastergo-magic-mcp) — Connect MasterGo to AI assistants ☆`242`
- [storybookjs/mcp](https://github.com/storybookjs/mcp) — MCP server for Storybook UI component library ☆`227`
- [YuChenSSR/mindmap-mcp-server](https://github.com/YuChenSSR/mindmap-mcp-server) — mindmap, mcp server, artifact ☆`227`
- [freema/mcp-design-system-extractor](https://github.com/freema/mcp-design-system-extractor) — MCP server for extracting design system components ☆`60`
- [starwind-ui/starwind-ui-mcp](https://github.com/starwind-ui/starwind-ui-mcp) — Starwind UI for Cursor and Windsurf ☆`34`
- [modao-dev/modao-proto-mcp](https://github.com/modao-dev/modao-proto-mcp) — Connect Modao Proto to AI clients ☆`51`
- [themesberg/flowbite-mcp](https://github.com/themesberg/flowbite-mcp) — Figma to code with Flowbite ☆`33`
- [themeselection/flyonui-mcp](https://github.com/themeselection/flyonui-mcp) — MCP server for flyonUI ☆`30`
- [heilgar/shadcn-ui-mcp-server](https://github.com/heilgar/shadcn-ui-mcp-server) — MCP server for shadcn/ui component library ☆`23`
- [kapilduraphe/webflow-mcp-server](https://github.com/kapilduraphe/webflow-mcp-server) — Webflow MCP server ☆`21`
### Diagrams

- [jinzcdev/markmap-mcp-server](https://github.com/jinzcdev/markmap-mcp-server) — Markdown to interactive mind maps ☆`196`
- [veelenga/claude-mermaid](https://github.com/veelenga/claude-mermaid) — MCP Server to previewing mermaid diagrams with live reload ☆`127`
- [apeyroux/mcp-xmind](https://github.com/apeyroux/mcp-xmind) — Analyze and query XMind mind maps ☆`67`
- [Narasimhaponnada/mermaid-mcp](https://github.com/Narasimhaponnada/mermaid-mcp) — MCP server for Mermaid diagram generation ☆`42`
### Documentation

- [upstash/context7](https://github.com/upstash/context7) — Up-to-date code docs for LLMs ☆`52,822`
- [lingodotdev/lingo.dev](https://github.com/lingodotdev/lingo.dev) — MCP server for Lingo localization platform ☆`5,402`
- [MicrosoftDocs/mcp](https://github.com/MicrosoftDocs/mcp) — Microsoft Learn MCP for LLMs ☆`1,553`
- [kimsungwhee/apple-docs-mcp](https://github.com/kimsungwhee/apple-docs-mcp) — Apple Developer Documentation search ☆`1,225`
- [andrea9293/mcp-documentation-server](https://github.com/andrea9293/mcp-documentation-server) — Document management with Gemini ☆`305`
- [szeider/consult7](https://github.com/szeider/consult7) — MCP server to consult a language model with large context size ☆`293`
- [Govcraft/rust-docs-mcp-server](https://github.com/Govcraft/rust-docs-mcp-server) — Rust documentation lookup ☆`270`
- [khromov/svelte-llm-mcp](https://github.com/khromov/svelte-llm-mcp) — Svelte developer documentation as an MCP and in llms.txt format ☆`159`
- [mrjoshuak/godoc-mcp](https://github.com/mrjoshuak/godoc-mcp) — go doc mcp server ☆`114`
- [yikakia/godoc-mcp-server](https://github.com/yikakia/godoc-mcp-server) — Go package docs from pkg.go.dev ☆`35`
- [tosin2013/mcp-adr-analysis-server](https://github.com/tosin2013/mcp-adr-analysis-server) — AI-powered ADR and architecture analysis ☆`25`
- [V0v1kkk/DotNetMetadataMcpServer](https://github.com/V0v1kkk/DotNetMetadataMcpServer) — .NET type metadata for AI coding agents ☆`25`
- [yWorks/mcp-typescribe](https://github.com/yWorks/mcp-typescribe) — TypeScript library support for LLMs ☆`44`
- [inkeep/mcp-server-python](https://github.com/inkeep/mcp-server-python) — Inkeep MCP Server ☆`25`
- [Excoriate/mcp-terragrunt-docs](https://github.com/Excoriate/mcp-terragrunt-docs) — Terragrunt documentation context ☆`21`
- [oborchers/mcp-server-docy](https://github.com/oborchers/mcp-server-docy) — Documentation access capabilities ☆`19`
- [augmentedivan/fabric-mcp-server](https://github.com/augmentedivan/fabric-mcp-server) — Fabric patterns with AI agents ☆`19`
- [idachev/mcp-javadc](https://github.com/idachev/mcp-javadc) — MCP server for decompiling Java .class files to source ☆`16`
### IDE & Editors

- [getsentry/XcodeBuildMCP](https://github.com/getsentry/XcodeBuildMCP) — MCP server for Xcode build operations ☆`5,216`
- [isaacphi/mcp-language-server](https://github.com/isaacphi/mcp-language-server) — MCP server implementing Language Server Protocol ☆`1,511`
- [JetBrains/mcp-jetbrains](https://github.com/JetBrains/mcp-jetbrains) — MCP server for JetBrains IDE integration ☆`947`
- [r-huijts/xcode-mcp-server](https://github.com/r-huijts/xcode-mcp-server) — Xcode project management ☆`371`
- [juehang/vscode-mcp-server](https://github.com/juehang/vscode-mcp-server) — VS Code editing features for LLM coding ☆`347`
- [bigcodegen/mcp-neovim-server](https://github.com/bigcodegen/mcp-neovim-server) — Control Neovim via MCP ☆`305`
- [biegehydra/BifrostMCP](https://github.com/biegehydra/BifrostMCP) — VS Code semantic tools via MCP ☆`208`
- [tumf/mcp-text-editor](https://github.com/tumf/mcp-text-editor) — Line-oriented text editing for LLM tools ☆`185`
- [hechtcarmel/jetbrains-index-mcp-plugin](https://github.com/hechtcarmel/jetbrains-index-mcp-plugin) — JetBrains plugin for MCP index integration ☆`158`
- [Tritlo/lsp-mcp](https://github.com/Tritlo/lsp-mcp) — An MCP server that lets you interact with LSP servers ☆`122`
- [marimo-team/codemirror-mcp](https://github.com/marimo-team/codemirror-mcp) — CodeMirror MCP extension ☆`79`
- [hloiseau/mcp-gopls](https://github.com/hloiseau/mcp-gopls) — Go LSP server via gopls ☆`77`
- [ShenghaiWang/xcodebuild](https://github.com/ShenghaiWang/xcodebuild) — Xcode iOS build with error feedback ☆`83`
- [hechtcarmel/jetbrains-debugger-mcp-plugin](https://github.com/hechtcarmel/jetbrains-debugger-mcp-plugin) — JetBrains debugger control via MCP ☆`57`
- [linw1995/nvim-mcp](https://github.com/linw1995/nvim-mcp) — MCP server for Neovim integration ☆`49`
- [laurynas-biveinis/elisp-dev-mcp](https://github.com/laurynas-biveinis/elisp-dev-mcp) — Emacs Elisp development tools for LLMs ☆`39`
- [AB498/code-context-provider-mcp](https://github.com/AB498/code-context-provider-mcp) — Code context and analysis for AI ☆`22`
### MCP SDKs

- [PrefectHQ/fastmcp](https://github.com/PrefectHQ/fastmcp) — Python framework for building MCP servers and clients ☆`24,564`
- [mark3labs/mcp-go](https://github.com/mark3labs/mcp-go) — Go implementation of MCP ☆`8,591`
- [QuantGeekDev/mcp-framework](https://github.com/QuantGeekDev/mcp-framework) — TypeScript framework with auto-discovery ☆`907`
- [bhauman/clojure-mcp](https://github.com/bhauman/clojure-mcp) — Clojure MCP ☆`731`
- [php-mcp/laravel](https://github.com/php-mcp/laravel) — Laravel SDK for building MCP servers ☆`471`
- [opgginc/laravel-mcp-server](https://github.com/opgginc/laravel-mcp-server) — Laravel package for MCP servers ☆`332`
- [Epistates/turbomcp](https://github.com/Epistates/turbomcp) — High-performance MCP framework ☆`77`
- [oatpp/oatpp-mcp](https://github.com/oatpp/oatpp-mcp) — C++ MCP implementation for Oat++ framework ☆`49`
- [reflagcom/javascript](https://github.com/reflagcom/javascript) — JS/TS SDKs for Reflag ☆`22`
- [Super-I-Tech/mcp_plexus](https://github.com/Super-I-Tech/mcp_plexus) — Multi-tenant MCP framework built on FastMCP ☆`29`
- [stephencme/create-mcp-ts](https://github.com/stephencme/create-mcp-ts) — TypeScript MCP server template ☆`21`
### Mobile Development

- [mobile-next/mobile-mcp](https://github.com/mobile-next/mobile-mcp) — Mobile automation for iOS, Android, emulators ☆`4,553`
- [joshuayoes/ios-simulator-mcp](https://github.com/joshuayoes/ios-simulator-mcp) — MCP server for interacting with the iOS simulator ☆`1,874`
- [minhalvp/android-mcp-server](https://github.com/minhalvp/android-mcp-server) — Android device control via adb ☆`727`
- [hyperb1iss/droidmind](https://github.com/hyperb1iss/droidmind) — Control your Android devices with AI using Model Context Protocol ☆`384`
- [InditexTech/mcp-server-simulator-ios-idb](https://github.com/InditexTech/mcp-server-simulator-ios-idb) — MCP server for iOS simulator via IDB ☆`302`
- [mhmzdev/figma-flutter-mcp](https://github.com/mhmzdev/figma-flutter-mcp) — Figma design tokens for Flutter code agents ☆`229`
- [zillow/auto-mobile](https://github.com/zillow/auto-mobile) — Mobile automation tools with MCP ☆`79`
- [JoshuaRileyDev/simulator-mcp-server](https://github.com/JoshuaRileyDev/simulator-mcp-server) — MCP server for iOS Simulator control ☆`52`
- [Tommertom/awesome-ionic-mcp](https://github.com/Tommertom/awesome-ionic-mcp) — Ionic and Capacitor mobile app development ☆`37`
- [XixianLiang/HarmonyOS-mcp-server](https://github.com/XixianLiang/HarmonyOS-mcp-server) — MCP server for manipulating HarmonyOS next devices. ☆`33`
- [ambar/simctl-mcp](https://github.com/ambar/simctl-mcp) — MCP server for iOS Simulator control ☆`19`
### OpenAPI

- [janwilmake/openapi-mcp-server](https://github.com/janwilmake/openapi-mcp-server) — Complex OpenAPI exploration with plain language ☆`887`
- [ckanthony/openapi-mcp](https://github.com/ckanthony/openapi-mcp) — Dockerized OpenAPI to MCP conversion ☆`182`
- [twilio-labs/mcp](https://github.com/twilio-labs/mcp) — OpenAPI to MCP tools and Twilio APIs ☆`102`
- [kadykov/mcp-openapi-schema-explorer](https://github.com/kadykov/mcp-openapi-schema-explorer) — Token-efficient OpenAPI/Swagger exploration ☆`71`
- [zaizaizhao/mcp-swagger-server](https://github.com/zaizaizhao/mcp-swagger-server) — OpenAPI/Swagger to MCP conversion ☆`63`
- [ReAPI-com/mcp-openapi](https://github.com/ReAPI-com/mcp-openapi) — OpenAPI specification MCP server. ☆`84`
- [baryhuang/mcp-server-any-openapi](https://github.com/baryhuang/mcp-server-any-openapi) — Call APIs via semantic search ☆`82`
- [hannesj/mcp-openapi-schema](https://github.com/hannesj/mcp-openapi-schema) — OpenAPI Schema Model Context Protocol Server ☆`47`
- [criteo/openapi-to-mcp](https://github.com/criteo/openapi-to-mcp) — An MCP server for your API ☆`30`
### Package Managers

- [Artmann/package-registry-mcp](https://github.com/Artmann/package-registry-mcp) — NPM, Cargo, PyPi, NuGet package search ☆`37`
- [arvindand/maven-tools-mcp](https://github.com/arvindand/maven-tools-mcp) — Maven Central dependency intelligence for JVM build tools ☆`19`
- [Bigsy/maven-mcp-server](https://github.com/Bigsy/maven-mcp-server) — Maven build and dependency tools ☆`32`
- [jeannier/homebrew-mcp](https://github.com/jeannier/homebrew-mcp) — Homebrew package management ☆`28`
- [subelsky/bundler_mcp](https://github.com/subelsky/bundler_mcp) — MCP server for Ruby Bundler integration ☆`19`
### Robotics & Automation

- [trycua/cua](https://github.com/trycua/cua) — MCP server for CUA platform ☆`13,483`
- [robotmcp/ros-mcp-server](https://github.com/robotmcp/ros-mcp-server) — ROS robot control with Claude and GPT ☆`1,163`
- [omni-mcp/isaac-sim-mcp](https://github.com/omni-mcp/isaac-sim-mcp) — Isaac Simulation MCP Extension and Server ☆`148`
- [wise-vision/ros2_mcp](https://github.com/wise-vision/ros2_mcp) — ROS 2 robotics AI bridge ☆`72`
- [abrinsmead/mindpilot-mcp](https://github.com/abrinsmead/mindpilot-mcp) — Visualize code and architect new systems ☆`85`
- [lpigeon/unitree-go2-mcp-server](https://github.com/lpigeon/unitree-go2-mcp-server) — MCP server for Unitree Go2 robot control ☆`77`
- [Yutarop/ros-mcp](https://github.com/Yutarop/ros-mcp) — MCP server for ROS to control robots via topics, services, and actions. ☆`31`
### Task Management

- [cjo4m06/mcp-shrimp-task-manager](https://github.com/cjo4m06/mcp-shrimp-task-manager) — Task manager with chain-of-thought and reflection ☆`2,082`
- [amxv/mcp-manager](https://github.com/amxv/mcp-manager) — Web UI to manage MCP servers in Claude ☆`286`
### Testing & QA

- [refreshdotdev/web-eval-agent](https://github.com/refreshdotdev/web-eval-agent) — Autonomous web application evaluation ☆`1,236`
- [debugg-ai/debugg-ai-mcp](https://github.com/debugg-ai/debugg-ai-mcp) — AI-managed end-to-end testing ☆`59`
- [QAInsights/jmeter-mcp-server](https://github.com/QAInsights/jmeter-mcp-server) — JMeter AI workflow integration ☆`63`
- [SmartBear/smartbear-mcp](https://github.com/SmartBear/smartbear-mcp) — SmartBear's official MCP Server ☆`28`
- [mrexodia/user-feedback-mcp](https://github.com/mrexodia/user-feedback-mcp) — Human-in-the-loop workflow for Cursor ☆`52`
- [reportportal/reportportal-mcp-server](https://github.com/reportportal/reportportal-mcp-server) — MCP server for ReportPortal ☆`20`
- [hungthai1401/bruno-mcp](https://github.com/hungthai1401/bruno-mcp) — MCP Server for running Bruno Collections ☆`41`
- [Hypersequent/qasphere-mcp](https://github.com/Hypersequent/qasphere-mcp) — MCP Server for QA Sphere TMS ☆`21`
- [QAInsights/k6-mcp-server](https://github.com/QAInsights/k6-mcp-server) — k6 MCP server ☆`24`
### Utilities

- [anaisbetts/mcp-installer](https://github.com/anaisbetts/mcp-installer) — An MCP server that installs other MCP servers for you ☆`1,519`
- [githejie/mcp-server-calculator](https://github.com/githejie/mcp-server-calculator) — A Model Context Protocol server for calculating. ☆`148`
- [jsdelivr/globalping-mcp-server](https://github.com/jsdelivr/globalping-mcp-server) — Remote network commands for LLMs ☆`53`
- [zazencodes/random-number-mcp](https://github.com/zazencodes/random-number-mcp) — MCP server for random number generation ☆`48`
- [NON906/omniparser-autogui-mcp](https://github.com/NON906/omniparser-autogui-mcp) — Automatic operation of on-screen GUI. ☆`67`
- [Mtehabsim/ScreenPilot](https://github.com/Mtehabsim/ScreenPilot) — AI device control like a human ☆`53`
- [newtype-01/prompthouse-mcp](https://github.com/newtype-01/prompthouse-mcp) — Personal prompt library manager ☆`52`
- [andybrandt/mcp-simple-timeserver](https://github.com/andybrandt/mcp-simple-timeserver) — Current time check for Claude via MCP ☆`28`
- [bharathvaj-ganesan/whois-mcp](https://github.com/bharathvaj-ganesan/whois-mcp) — MCP Server for whois lookups. ☆`52`
- [wrenchpilot/it-tools-mcp](https://github.com/wrenchpilot/it-tools-mcp) — 121+ IT tools for developers and sysadmins ☆`20`
- [SecretiveShell/MCP-timeserver](https://github.com/SecretiveShell/MCP-timeserver) — Datetime info for agentic systems ☆`41`
- [ofek/pycli-mcp](https://github.com/ofek/pycli-mcp) — MCP server for any Python command line application ☆`22`
- [FelixFoster/mcp-enhance-prompt](https://github.com/FelixFoster/mcp-enhance-prompt) — AI-powered prompt enhancement and generation ☆`24`
- [ZeparHyfar/mcp-datetime](https://github.com/ZeparHyfar/mcp-datetime) — A MCP server for datetime formatting and file name generation. ☆`27`
### Version Control

- [github/github-mcp-server](https://github.com/github/github-mcp-server) — GitHub's official MCP Server ☆`28,889`
- [idosal/git-mcp](https://github.com/idosal/git-mcp) — Free remote MCP for any GitHub project ☆`7,925`
- [gitkraken/gk-cli](https://github.com/gitkraken/gk-cli) — GitKraken CLI Releases and Documentation ☆`397`
- [Tiberriver256/mcp-server-azure-devops](https://github.com/Tiberriver256/mcp-server-azure-devops) — An MCP server for Azure DevOps ☆`362`
- [adhikasp/mcp-git-ingest](https://github.com/adhikasp/mcp-git-ingest) — GitHub repository content reading ☆`303`
- [puravparab/Gitingest-MCP](https://github.com/puravparab/Gitingest-MCP) — mcp server for gitingest ☆`137`
- [kopfrechner/gitlab-mr-mcp](https://github.com/kopfrechner/gitlab-mr-mcp) — MCP server for GitLab merge requests and issues ☆`87`
- [oschina/mcp-gitee](https://github.com/oschina/mcp-gitee) — MCP server for Gitee repositories ☆`55`
- [ddukbg/github-enterprise-mcp](https://github.com/ddukbg/github-enterprise-mcp) — github-enterprise-mcp ☆`30`
- [Ryan0204/github-repo-mcp](https://github.com/Ryan0204/github-repo-mcp) — GitHub repository reading ☆`25`
- [kurdin/github-repos-manager-mcp](https://github.com/kurdin/github-repos-manager-mcp) — GitHub Repos Manager MCP Server for MCP clients ☆`20`
## Embedded & IoT

- [tevonsb/homeassistant-mcp](https://github.com/tevonsb/homeassistant-mcp) — A MCP server for Home Assistant ☆`566`
- [lamaalrajih/kicad-mcp](https://github.com/lamaalrajih/kicad-mcp) — KiCad integration for Mac, Windows, Linux ☆`428`
- [Extelligence-ai/bagel](https://github.com/Extelligence-ai/bagel) — Chat with robotics, drone, IoT data ☆`378`
- [recursechat/mcp-server-apple-shortcuts](https://github.com/recursechat/mcp-server-apple-shortcuts) — Apple Shortcuts automation on macOS ☆`313`
- [voska/hass-mcp](https://github.com/voska/hass-mcp) — Home Assistant MCP Server ☆`286`
- [hao-cyber/phone-mcp](https://github.com/hao-cyber/phone-mcp) — Control Android phone via ADB ☆`224`
- [jeff-nasseri/mikrotik-mcp](https://github.com/jeff-nasseri/mikrotik-mcp) — MCP server for Mikrotik ☆`151`
- [horw/esp-mcp](https://github.com/horw/esp-mcp) — ESP32 commands and getting started ☆`147`
- [thingsboard/thingsboard-mcp](https://github.com/thingsboard/thingsboard-mcp) — MCP server for ThingsBoard IoT platform interaction ☆`95`
- [FradSer/mcp-server-apple-events](https://github.com/FradSer/mcp-server-apple-events) — Native integration with Apple Reminders and Calendar ☆`85`
- [vishalmysore/choturobo](https://github.com/vishalmysore/choturobo) — Arduino robotics with AI integration ☆`78`
- [yoelbassin/gr-mcp](https://github.com/yoelbassin/gr-mcp) — MCP server for GNU Radio ☆`38`
- [yiwenlu66/PiloTY](https://github.com/yiwenlu66/PiloTY) — AI pilot for PTY operations - control terminals via MCP ☆`33`
- [LGDiMaggio/predictive-maintenance-mcp](https://github.com/LGDiMaggio/predictive-maintenance-mcp) — AI predictive maintenance and fault diagnosis via MCP ☆`25`
- [chrisgleissner/c64bridge](https://github.com/chrisgleissner/c64bridge) — MCP server to control and program the Commodore 64 Ultimate or VICE. ☆`24`
- [johannesPettersson80/codesys-mcp-toolkit](https://github.com/johannesPettersson80/codesys-mcp-toolkit) — CODESYS industrial automation platform ☆`42`
- [OctoEverywhere/mcp](https://github.com/OctoEverywhere/mcp) — 3D printing live status and control ☆`33`
- [aqara/aqara-mcp-server](https://github.com/aqara/aqara-mcp-server) — Aqara's official MCP Server ☆`32`
- [kukapay/opcua-mcp](https://github.com/kukapay/opcua-mcp) — An MCP server that connects to OPC UA-enabled industrial systems. ☆`26`
- [MiddlePoint-Solutions/mcp-on-android-tv](https://github.com/MiddlePoint-Solutions/mcp-on-android-tv) — MCP server on Android TV with ADB ☆`22`
- [kukapay/modbus-mcp](https://github.com/kukapay/modbus-mcp) — Industrial Modbus data for AI ☆`23`
- [thinq-connect/thinqconnect-mcp](https://github.com/thinq-connect/thinqconnect-mcp) — ThinQ Connect MCP Server ☆`23`
- [Hypijump31/bluetooth-mcp-server](https://github.com/Hypijump31/bluetooth-mcp-server) — bluetooth-mcp-server for Claude AI ☆`21`
## File Systems & Storage

- [mark3labs/mcp-filesystem-server](https://github.com/mark3labs/mcp-filesystem-server) — Go filesystem operations via MCP ☆`630`
- [cyberchitta/llm-context.py](https://github.com/cyberchitta/llm-context.py) — Python library for LLM context management ☆`298`
- [isaacphi/mcp-gdrive](https://github.com/isaacphi/mcp-gdrive) — Google Drive file reading ☆`272`
- [8b-is/smart-tree](https://github.com/8b-is/smart-tree) — Context-aware AI-crafted replacement for tree command ☆`233`
- [rust-mcp-stack/rust-mcp-filesystem](https://github.com/rust-mcp-stack/rust-mcp-filesystem) — Fast async filesystem operations ☆`144`
- [efforthye/fast-filesystem-mcp](https://github.com/efforthye/fast-filesystem-mcp) — High-performance MCP server for file operations ☆`48`
- [vespo92/TrueNasCoreMCP](https://github.com/vespo92/TrueNasCoreMCP) — A working TrueNAS Core MCP Server ☆`23`
- [Tencent/cos-mcp](https://github.com/Tencent/cos-mcp) — Tencent Cloud COS storage integration ☆`32`
- [Xuanwo/mcp-server-opendal](https://github.com/Xuanwo/mcp-server-opendal) — Model Context Protocol Server for Apache OpenDAL ☆`34`
- [exoticknight/mcp-file-merger](https://github.com/exoticknight/mcp-file-merger) — MCP server for merging multiple files into one ☆`26`
## Finance

### Accounting & Budgeting

- [XeroAPI/xero-mcp-server](https://github.com/XeroAPI/xero-mcp-server) — Xero accounting API integration ☆`245`
- [akutishevsky/lunchmoney-mcp](https://github.com/akutishevsky/lunchmoney-mcp) — MCP server for Lunch Money budgeting app ☆`58`
- [iiAtlas/hledger-mcp](https://github.com/iiAtlas/hledger-mcp) — A local MCP server for interacting with the HLedger cli ☆`54`
- [minhyeoky/mcp-server-ledger](https://github.com/minhyeoky/mcp-server-ledger) — MCP server for Ledger CLI double-entry accounting ☆`47`
- [openMF/mcp-mifosx](https://github.com/openMF/mcp-mifosx) — Model Context Protocol - MCP for Mifos X ☆`21`
- [john-zhang-dev/xero-mcp](https://github.com/john-zhang-dev/xero-mcp) — Interact with Xero accounting ☆`18`
### Crypto & Blockchain

- [mcpdotdirect/evm-mcp-server](https://github.com/mcpdotdirect/evm-mcp-server) — EVM network interaction for LLMs ☆`373`
- [base/base-mcp](https://github.com/base/base-mcp) — MCP server for Base blockchain integration ☆`344`
- [armorwallet/armor-crypto-mcp](https://github.com/armorwallet/armor-crypto-mcp) — Blockchain swaps and strategic planning ☆`184`
- [aaronjmars/web3-research-mcp](https://github.com/aaronjmars/web3-research-mcp) — Deep Research for crypto - free & fully local ☆`147`
- [kukapay/crypto-indicators-mcp](https://github.com/kukapay/crypto-indicators-mcp) — Cryptocurrency technical analysis indicators ☆`122`
- [alchemyplatform/alchemy-mcp-server](https://github.com/alchemyplatform/alchemy-mcp-server) — Alchemy blockchain API for AI agents ☆`81`
- [Bankless/onchain-mcp](https://github.com/Bankless/onchain-mcp) — Bringing the bankless onchain API to MCP ☆`77`
- [QuantGeekDev/coincap-mcp](https://github.com/QuantGeekDev/coincap-mcp) — A coincap mcp server to access crypto data from coincap API ☆`91`
- [getAlby/mcp](https://github.com/getAlby/mcp) — Bitcoin Lightning wallet via Nostr ☆`64`
- [heurist-network/heurist-mesh-mcp-server](https://github.com/heurist-network/heurist-mesh-mcp-server) — Blockchain and web3 via Heurist Mesh ☆`64`
- [bnb-chain/bnbchain-mcp](https://github.com/bnb-chain/bnbchain-mcp) — BNB Chain, BSC, opBNB, Greenfield ☆`58`
- [kukapay/cryptopanic-mcp-server](https://github.com/kukapay/cryptopanic-mcp-server) — Provide latest cryptocurrency news to AI agents. ☆`69`
- [AbdelStark/bitcoin-mcp](https://github.com/AbdelStark/bitcoin-mcp) — Bitcoin & Lightning Network MCP Server. ☆`73`
- [twelvedata/mcp](https://github.com/twelvedata/mcp) — MCP server for real-time financial market data access ☆`64`
- [GoPlausible/algorand-mcp](https://github.com/GoPlausible/algorand-mcp) — Algorand Local Model Context Protocol (Server & Client) ☆`44`
- [coinpaprika/dexpaprika-mcp](https://github.com/coinpaprika/dexpaprika-mcp) — MCP server for DEX trading data and crypto token analytics ☆`41`
- [norman-finance/norman-mcp-server](https://github.com/norman-finance/norman-mcp-server) — AI-powered bookkeeping and tax automation via MCP ☆`39`
- [shinzo-labs/coinmarketcap-mcp](https://github.com/shinzo-labs/coinmarketcap-mcp) — MCP Implementation for CoinMarketCap ☆`51`
- [kukapay/crypto-feargreed-mcp](https://github.com/kukapay/crypto-feargreed-mcp) — Crypto Fear & Greed Index data ☆`53`
- [kukapay/whale-tracker-mcp](https://github.com/kukapay/whale-tracker-mcp) — A mcp server for tracking cryptocurrency whale transactions. ☆`52`
- [anjor/coinmarket-mcp-server](https://github.com/anjor/coinmarket-mcp-server) — MCP server for CoinMarketCap cryptocurrency data ☆`47`
- [kukapay/crypto-sentiment-mcp](https://github.com/kukapay/crypto-sentiment-mcp) — Cryptocurrency sentiment analysis ☆`47`
- [wowinter13/solscan-mcp](https://github.com/wowinter13/solscan-mcp) — Solana transaction queries ☆`40`
- [maestro-org/maestro-mcp-server](https://github.com/maestro-org/maestro-mcp-server) — Maestro MCP Server for Bitcoin ☆`22`
- [noditlabs/nodit-mcp-server](https://github.com/noditlabs/nodit-mcp-server) — Blockchain data via Nodit Web3 API ☆`21`
- [kukapay/dune-analytics-mcp](https://github.com/kukapay/dune-analytics-mcp) — A mcp server that bridges Dune Analytics data to AI agents. ☆`40`
- [ahnlabio/bicscan-mcp](https://github.com/ahnlabio/bicscan-mcp) — BICScan MCP Server ☆`16`
- [kukapay/uniswap-trader-mcp](https://github.com/kukapay/uniswap-trader-mcp) — Uniswap token swaps for AI agents ☆`35`
- [hive-intel/hive-crypto-mcp](https://github.com/hive-intel/hive-crypto-mcp) — Hive Intelligence Crypto MCP | The Ultimate Cryptocurrency MCP for AI Assistants - Unified access to crypto, DeFi, and Web3 analytics ☆`17`
- [longmans/coin_api_mcp](https://github.com/longmans/coin_api_mcp) — CoinMarketCap cryptocurrency data ☆`37`
- [kukapay/hyperliquid-info-mcp](https://github.com/kukapay/hyperliquid-info-mcp) — MCP server for Hyperliquid DEX data ☆`27`
- [kukapay/jupiter-mcp](https://github.com/kukapay/jupiter-mcp) — Jupiter DEX token swaps on Solana ☆`26`
- [kukapay/kukapay-mcp-servers](https://github.com/kukapay/kukapay-mcp-servers) — Suite of MCP servers from Kukapay ☆`22`
- [devonmojito/ton-blockchain-mcp](https://github.com/devonmojito/ton-blockchain-mcp) — TON blockchain interaction ☆`26`
- [pwh-pwh/coin-mcp-server](https://github.com/pwh-pwh/coin-mcp-server) — Cryptocurrency info via Bitget API ☆`28`
- [thirdweb-dev/ai](https://github.com/thirdweb-dev/ai) — Blockchain data, wallet, and smart contracts ☆`20`
- [kukapay/rug-check-mcp](https://github.com/kukapay/rug-check-mcp) — An MCP server that detects potential risks in Solana meme tokens. ☆`19`
- [kukapay/token-minter-mcp](https://github.com/kukapay/token-minter-mcp) — ERC-20 token minting for AI agents ☆`18`
- [Codex-Data/codex-mcp](https://github.com/Codex-Data/codex-mcp) — A Model Context Protocol server for the Codex API ☆`23`
- [syronlabs/stellar-mcp](https://github.com/syronlabs/stellar-mcp) — A Stellar MCP to interact with Horizon API and Soroban ☆`18`
- [kukapay/crypto-orderbook-mcp](https://github.com/kukapay/crypto-orderbook-mcp) — An MCP server that analyzes order book depth and imbalance across major crypto exchanges. ☆`16`
- [magnetai/mcp-free-usdc-transfer](https://github.com/magnetai/mcp-free-usdc-transfer) — Free USDC transfer via Coinbase CDP ☆`20`
- [janswist/mcp-dexscreener](https://github.com/janswist/mcp-dexscreener) — Dexscreener on-chain price checking ☆`17`
### Payments & Banking

- [stripe/ai](https://github.com/stripe/ai) — One-stop shop for building AI-powered products and businesses with Stripe. ☆`1,472`
- [razorpay/razorpay-mcp-server](https://github.com/razorpay/razorpay-mcp-server) — Razorpay's Official MCP Server ☆`218`
- [paypal/agent-toolkit](https://github.com/paypal/agent-toolkit) — PayPal Agent ☆`185`
- [square/square-mcp-server](https://github.com/square/square-mcp-server) — A Model Context Protocol (MCP) server for square ☆`99`
- [PaddleHQ/paddle-mcp-server](https://github.com/PaddleHQ/paddle-mcp-server) — Interact with Paddle API ☆`46`
- [atharvagupta2003/mcp-stripe](https://github.com/atharvagupta2003/mcp-stripe) — Stripe payments, customers, and refunds ☆`44`
- [ramp-public/ramp_mcp](https://github.com/ramp-public/ramp_mcp) — ramp_mcp ☆`32`
- [qonto/qonto-mcp-server](https://github.com/qonto/qonto-mcp-server) — Qonto MCP Server ☆`26`
- [Fewsats/fewsats-mcp](https://github.com/Fewsats/fewsats-mcp) — Fewsats MCP server ☆`22`
### Stock Data & Analytics

- [financial-datasets/mcp-server](https://github.com/financial-datasets/mcp-server) — Financial Datasets stock market API ☆`1,961`
- [massive-com/mcp_massive](https://github.com/massive-com/mcp_massive) — An MCP server for Massive.com Financial Market Data ☆`299`
- [stefanoamorelli/sec-edgar-mcp](https://github.com/stefanoamorelli/sec-edgar-mcp) — A SEC EDGAR MCP (Model Context Protocol) Server ☆`251`
- [narumiruna/yfinance-mcp](https://github.com/narumiruna/yfinance-mcp) — MCP server for Yahoo Finance stock data and news ☆`121`
- [jjlabsio/korea-stock-mcp](https://github.com/jjlabsio/korea-stock-mcp) — MCP Server for Korean stock analysis ☆`116`
- [OctagonAI/octagon-mcp-server](https://github.com/OctagonAI/octagon-mcp-server) — Public filings, earnings, financial analysis ☆`115`
- [HuggingAGI/mcp-baostock-server](https://github.com/HuggingAGI/mcp-baostock-server) — MCP server for BaoStock Chinese stock market data ☆`95`
- [berlinbra/alpha-vantage-mcp](https://github.com/berlinbra/alpha-vantage-mcp) — MCP Server for Alpha Advantage API ☆`95`
- [Adity-star/mcp-yfinance-server](https://github.com/Adity-star/mcp-yfinance-server) — Real-time stock data with yfinance ☆`50`
- [AgentX-ai/yahoo-finance-server](https://github.com/AgentX-ai/yahoo-finance-server) — Yahoo Finance stock data and news ☆`44`
- [zlinzzzz/finData-mcp-server](https://github.com/zlinzzzz/finData-mcp-server) — Financial data from Tushare, Wind, DataYes ☆`56`
- [JamesANZ/prediction-market-mcp](https://github.com/JamesANZ/prediction-market-mcp) — Polymarket, PredictIt, Kalshi data ☆`33`
- [OctagonAI/octagon-vc-agents](https://github.com/OctagonAI/octagon-vc-agents) — AI-driven venture capitalist agents ☆`23`
### Trading & Exchanges

- [alpacahq/alpaca-mcp-server](https://github.com/alpacahq/alpaca-mcp-server) — Trade stocks, ETFs, crypto, options ☆`649`
- [ferdousbhai/investor-agent](https://github.com/ferdousbhai/investor-agent) — Investor agent building via MCP ☆`322`
- [ariadng/metatrader-mcp-server](https://github.com/ariadng/metatrader-mcp-server) — MetaTrader trading platform for AI LLMs ☆`212`
- [doggybee/mcp-server-ccxt](https://github.com/doggybee/mcp-server-ccxt) — Cryptocurrency exchange integration via CCXT ☆`133`
- [kukapay/freqtrade-mcp](https://github.com/kukapay/freqtrade-mcp) — Freqtrade crypto trading bot ☆`114`
- [taylorwilsdon/quantconnect-mcp](https://github.com/taylorwilsdon/quantconnect-mcp) — QuantConnect trading orchestration ☆`93`
- [ferdousbhai/tasty-agent](https://github.com/ferdousbhai/tasty-agent) — Let Claude manage your tastytrade portfolio. ☆`61`
- [QuantConnect/mcp-server](https://github.com/QuantConnect/mcp-server) — QuantConnect algo trading interaction ☆`69`
- [trade-it-inc/trade-it-mcp](https://github.com/trade-it-inc/trade-it-mcp) — Trade It stocks and crypto trading ☆`49`
- [ozgureyilmaz/polymarket-mcp](https://github.com/ozgureyilmaz/polymarket-mcp) — Polymarket prediction markets data ☆`48`
- [ethancod1ng/binance-mcp-server](https://github.com/ethancod1ng/binance-mcp-server) — Binance exchange API integration ☆`30`
- [mektigboy/server-hyperliquid](https://github.com/mektigboy/server-hyperliquid) — Hyperliquid DEX trading integration ☆`44`
- [laukikk/alpaca-mcp](https://github.com/laukikk/alpaca-mcp) — Alpaca stock and crypto trading ☆`32`
- [ferdousbhai/wsb-analyst-mcp](https://github.com/ferdousbhai/wsb-analyst-mcp) — MCP server for analyzing WallStreetBets ☆`24`
- [paperinvest/mcp-server](https://github.com/paperinvest/mcp-server) — Paper trading platform integration ☆`22`
- [solangii/upbit-mcp-server](https://github.com/solangii/upbit-mcp-server) — MCP(Model Context Protocol) server for Upbit ☆`18`
## Frameworks & SDKs

- [mastra-ai/mastra](https://github.com/mastra-ai/mastra) — TypeScript AI agent framework with RAG ☆`23,041`
- [lastmile-ai/mcp-agent](https://github.com/lastmile-ai/mcp-agent) — Build agents with MCP and workflow patterns ☆`8,268`
- [quarkiverse/quarkus-mcp-servers](https://github.com/quarkiverse/quarkus-mcp-servers) — Model Context Protocol Servers in Quarkus ☆`186`
- [posit-dev/mcptools](https://github.com/posit-dev/mcptools) — Model Context Protocol For R ☆`167`
- [agentrpc/agentrpc](https://github.com/agentrpc/agentrpc) — Universal RPC layer for AI agents ☆`130`
- [vishalmysore/a2ajava](https://github.com/vishalmysore/a2ajava) — Google A2A protocol for Spring Boot ☆`101`
- [strowk/foxy-contexts](https://github.com/strowk/foxy-contexts) — Library for MCP context servers ☆`114`
- [tesla0225/mcp-create](https://github.com/tesla0225/mcp-create) — Dynamic MCP server creation and management ☆`97`
- [mcpdotdirect/template-mcp-server](https://github.com/mcpdotdirect/template-mcp-server) — Template to quickly set up your own MCP server ☆`73`
- [abap-ai/mcp](https://github.com/abap-ai/mcp) — ABAP MCP - Model Context Protocol - Server SDK ☆`62`
- [domdomegg/programmatic-mcp-prototype](https://github.com/domdomegg/programmatic-mcp-prototype) — Programmatic MCP tool composition ☆`41`
- [particlefuture/1mcpserver](https://github.com/particlefuture/1mcpserver) — Auto-discover and configure MCP servers ☆`44`
- [mcpx-dev/mcp-badges](https://github.com/mcpx-dev/mcp-badges) — Get your projects MCP (Model Context Protocol) badges ☆`29`
- [boost-community/boost-mcp](https://github.com/boost-community/boost-mcp) — Supply chain security for AI dependencies ☆`16`
## Gaming

- [Coding-Solo/godot-mcp](https://github.com/Coding-Solo/godot-mcp) — MCP server for Godot game engine ☆`3,082`
- [IvanMurzak/Unity-MCP](https://github.com/IvanMurzak/Unity-MCP) — AI-powered bridge connecting LLMs to Unity Editor ☆`2,158`
- [CoderGamester/mcp-unity](https://github.com/CoderGamester/mcp-unity) — MCP server for Unity game engine integration ☆`1,594`
- [quazaai/UnityMCPIntegration](https://github.com/quazaai/UnityMCPIntegration) — Enable AI Agents to Control Unity ☆`149`
- [playcanvas/editor-mcp-server](https://github.com/playcanvas/editor-mcp-server) — MCP Server for AI automation of the PlayCanvas Editor ☆`105`
- [codemaestroai/advanced-unity-mcp](https://github.com/codemaestroai/advanced-unity-mcp) — Advanced Unity game engine integration ☆`89`
- [opgginc/opgg-mcp](https://github.com/opgginc/opgg-mcp) — MCP server for OP.GG game data (LoL, TFT, Valorant) ☆`88`
- [pab1it0/chess-mcp](https://github.com/pab1it0/chess-mcp) — MCP server for Chess.com player data, games and statistics ☆`69`
- [sawa-zen/vrchat-mcp](https://github.com/sawa-zen/vrchat-mcp) — VRChat API interaction ☆`55`
- [kkjdaniel/bgg-mcp](https://github.com/kkjdaniel/bgg-mcp) — MCP server for BoardGameGeek data ☆`34`
- [jalpp/chessagine-mcp](https://github.com/jalpp/chessagine-mcp) — Advanced chess analysis capabilities ☆`24`
- [jiayao/mcp-chess](https://github.com/jiayao/mcp-chess) — MCP server for playing chess against AI ☆`22`
- [jifrozen0110/mcp-riot](https://github.com/jifrozen0110/mcp-riot) — League of Legends MCP Server ☆`21`
## Healthcare & Bioinformatics

- [genomoncology/biomcp](https://github.com/genomoncology/biomcp) — BioMCP: Biomedical Model Context Protocol ☆`490`
- [the-momentum/apple-health-mcp-server](https://github.com/the-momentum/apple-health-mcp-server) — Apple Health data queries with DuckDB ☆`156`
- [wso2/fhir-mcp-server](https://github.com/wso2/fhir-mcp-server) — FHIR healthcare API integration ☆`110`
- [JamesANZ/medical-mcp](https://github.com/JamesANZ/medical-mcp) — MCP server for medical data processing ☆`85`
- [ChristianHinge/dicom-mcp](https://github.com/ChristianHinge/dicom-mcp) — DICOM server (PACS) interaction ☆`90`
- [the-momentum/fhir-mcp-server](https://github.com/the-momentum/fhir-mcp-server) — FHIR MCP Server for handling medical data standard. ☆`74`
- [OHNLP/omop_mcp](https://github.com/OHNLP/omop_mcp) — MCP server for OMOP medical data standard ☆`34`
- [srijanshukla18/xray](https://github.com/srijanshukla18/xray) — MCP server for X-ray analysis ☆`48`
- [cafferychen777/ChatSpatial](https://github.com/cafferychen777/ChatSpatial) — Spatial transcriptomics via natural language (Python/R) ☆`30`
- [longevity-genie/biothings-mcp](https://github.com/longevity-genie/biothings-mcp) — MCP (Model Context Protocol) server for biothings ☆`31`
- [akutishevsky/withings-mcp](https://github.com/akutishevsky/withings-mcp) — MCP server for Withings health data integration ☆`17`
- [tomekkorbak/oura-mcp-server](https://github.com/tomekkorbak/oura-mcp-server) — MCP server for Oura API integration ☆`38`
- [longevity-genie/gget-mcp](https://github.com/longevity-genie/gget-mcp) — Bioinformatic gget functions ☆`27`
- [longevity-genie/opengenes-mcp](https://github.com/longevity-genie/opengenes-mcp) — MCP for the open-genes ☆`17`
## LLM Bridges

- [jamubc/gemini-mcp-tool](https://github.com/jamubc/gemini-mcp-tool) — MCP server for Gemini CLI with large file analysis ☆`2,163`
- [perplexityai/modelcontextprotocol](https://github.com/perplexityai/modelcontextprotocol) — Official Perplexity API MCP server ☆`2,089`
- [DMontgomery40/deepseek-mcp-server](https://github.com/DMontgomery40/deepseek-mcp-server) — MCP server for DeepSeek language models ☆`316`
- [nesquikm/mcp-rubber-duck](https://github.com/nesquikm/mcp-rubber-duck) — MCP bridge to query multiple OpenAI-compatible LLMs ☆`155`
- [pyroprompts/any-chat-completions-mcp](https://github.com/pyroprompts/any-chat-completions-mcp) — MCP Server for using any LLM as a Tool ☆`151`
- [choplin/mcp-gemini-cli](https://github.com/choplin/mcp-gemini-cli) — MCP server for Gemini CLI integration ☆`101`
- [deepfates/mcp-replicate](https://github.com/deepfates/mcp-replicate) — Model Context Protocol server for Replicate's API ☆`94`
- [eLyiN/gemini-bridge](https://github.com/eLyiN/gemini-bridge) — Bridge AI agents to Google Gemini via CLI ☆`90`
- [pierrebrunelle/mcp-server-openai](https://github.com/pierrebrunelle/mcp-server-openai) — Query OpenAI models from Claude via MCP ☆`80`
- [kamelirzouni/MCP-server-Deepseek_R1](https://github.com/kamelirzouni/MCP-server-Deepseek_R1) — Connect Claude Desktop with DeepSeek ☆`70`
- [mzxrai/mcp-openai](https://github.com/mzxrai/mcp-openai) — Chat with OpenAI models from Claude Desktop ☆`71`
- [ruixingshi/deepseek-thinker-mcp](https://github.com/ruixingshi/deepseek-thinker-mcp) — DeepSeek reasoning for MCP-enabled clients ☆`68`
- [amidabuddha/unichat-mcp-server](https://github.com/amidabuddha/unichat-mcp-server) — Unified chat across multiple LLM providers ☆`37`
- [merterbak/Grok-MCP](https://github.com/merterbak/Grok-MCP) — MCP server for xAI Grok API with tool calling and vision ☆`24`
- [andybrandt/mcp-simple-openai-assistant](https://github.com/andybrandt/mcp-simple-openai-assistant) — Use OpenAI GPTs assistants from Claude ☆`37`
- [kamelirzouni/MCP-server-Qwen_Max](https://github.com/kamelirzouni/MCP-server-Qwen_Max) — MCP server for Qwen Max model ☆`24`
- [HyperbolicLabs/hyperbolic-mcp](https://github.com/HyperbolicLabs/hyperbolic-mcp) — MCP Server for Claude ☆`19`
- [billster45/mcp-chatgpt-responses](https://github.com/billster45/mcp-chatgpt-responses) — MCP server for OpenAI ChatGPT API with Responses API ☆`16`
## Location & Maps

### GIS

- [jjsantos01/qgis_mcp](https://github.com/jjsantos01/qgis_mcp) — Model Context Protocol (MCP) that allows LLMs to use QGIS Desktop ☆`903`
- [mahdin75/gis-mcp](https://github.com/mahdin75/gis-mcp) — MCP server connecting LLMs to GIS capabilities ☆`134`
- [JordanGunn/gdal-mcp](https://github.com/JordanGunn/gdal-mcp) — Geospatial analysis with epistemic reasoning ☆`64`
- [mahdin75/geoserver-mcp](https://github.com/mahdin75/geoserver-mcp) — GeoServer geospatial integration ☆`69`
- [webcoderz/MCP-Geo](https://github.com/webcoderz/MCP-Geo) — Geocoding MCP server with GeoPY! ☆`32`
### IP Geolocation

- [briandconnelly/mcp-server-ipinfo](https://github.com/briandconnelly/mcp-server-ipinfo) — IP Geolocation Server for MCP ☆`43`
- [iplocate/mcp-server-iplocate](https://github.com/iplocate/mcp-server-iplocate) — IP geolocation, proxy detection via IPLocate.io API ☆`17`
### Maps & Navigation

- [baidu-maps/mcp](https://github.com/baidu-maps/mcp) — Baidu Map MCP Server ☆`421`
- [mapbox/mcp-server](https://github.com/mapbox/mcp-server) — Mapbox Model Context Protocol (MCP) server ☆`331`
- [jagan-shanmugam/open-streetmap-mcp](https://github.com/jagan-shanmugam/open-streetmap-mcp) — MCP server for OpenStreetMap data ☆`182`
- [tomtom-international/tomtom-mcp](https://github.com/tomtom-international/tomtom-mcp) — TomTom location, search, routing ☆`45`
- [PinMeTo/pinmeto-location-mcp](https://github.com/PinMeTo/pinmeto-location-mcp) — PinMeTo MCP server that enables users with authorized credentials to unlock their data ☆`16`
- [stadiamaps/stadiamaps-mcp-server-ts](https://github.com/stadiamaps/stadiamaps-mcp-server-ts) — Stadia Maps API integration in TypeScript ☆`21`
- [kukapay/nearby-search-mcp](https://github.com/kukapay/nearby-search-mcp) — Nearby place search with IP-based location ☆`22`
### Weather

- [isdaniel/mcp_weather_server](https://github.com/isdaniel/mcp_weather_server) — Weather info via Open-Meteo API ☆`47`
- [TimLukaHorstmann/mcp-weather](https://github.com/TimLukaHorstmann/mcp-weather) — AccuWeather hourly and daily forecasts ☆`31`
- [sjanaX01/weather-mcp-server](https://github.com/sjanaX01/weather-mcp-server) — A simple minimal weather mcp server :) ☆`21`
- [mschneider82/mcp-openweather](https://github.com/mschneider82/mcp-openweather) — mcp server for openweather free api ☆`16`
## MCP Clients

- [Upsonic/Upsonic](https://github.com/Upsonic/Upsonic) — Build autonomous AI agents in Python. ☆`7,825`
- [genkit-ai/genkit](https://github.com/genkit-ai/genkit) — AI app framework for JavaScript and Go ☆`5,793`
- [ravitemer/mcphub.nvim](https://github.com/ravitemer/mcphub.nvim) — MCP client for Neovim with intuitive server management ☆`1,760`
- [SecretiveShell/MCP-Bridge](https://github.com/SecretiveShell/MCP-Bridge) — OpenAI-compatible endpoint calling MCP tools ☆`922`
- [Lucassssss/eechat](https://github.com/Lucassssss/eechat) — Local AI chat application ☆`337`
- [EvalsOne/MCP-connect](https://github.com/EvalsOne/MCP-connect) — Cloud AI access to local Stdio MCP servers ☆`236`
- [AI-QL/chat-mcp](https://github.com/AI-QL/chat-mcp) — Desktop chat app with MCP support ☆`244`
- [3choff/mcp-chatbot](https://github.com/3choff/mcp-chatbot) — CLI chatbot with MCP integration demo ☆`248`
- [johannesbrandenburger/typst-mcp](https://github.com/johannesbrandenburger/typst-mcp) — MCP server for Typst markup-based typesetting system ☆`142`
- [tanaikech/ToolsForMCPServer](https://github.com/tanaikech/ToolsForMCPServer) — MCP server built with Google Apps Script for Gemini CLI ☆`100`
- [xzq-xu/jvm-mcp-server](https://github.com/xzq-xu/jvm-mcp-server) — JVM-based MCP server implementation ☆`82`
- [ckanthony/gin-mcp](https://github.com/ckanthony/gin-mcp) — Enable MCP features for any Gin API with a line of code ☆`73`
- [php-mcp/client](https://github.com/php-mcp/client) — Core PHP implementation for the Model Context Protocol (MCP) Client ☆`55`
- [zacharypodbela/django-rest-framework-mcp](https://github.com/zacharypodbela/django-rest-framework-mcp) — MCP server for Django REST Framework ☆`43`
- [rakesh-eltropy/mcp-client](https://github.com/rakesh-eltropy/mcp-client) — REST API and CLI client for MCP with LangChain ☆`50`
## Marketing & Analytics

- [pipeboard-co/meta-ads-mcp](https://github.com/pipeboard-co/meta-ads-mcp) — MCP server to manage Facebook and Instagram Ads (Meta Ads) ☆`779`
- [gomarble-ai/facebook-ads-mcp-server](https://github.com/gomarble-ai/facebook-ads-mcp-server) — Facebook and Instagram Ads management ☆`268`
- [open-strategy-partners/osp_marketing_tools](https://github.com/open-strategy-partners/osp_marketing_tools) — MCP server for marketing automation tools ☆`265`
- [cnych/seo-mcp](https://github.com/cnych/seo-mcp) — SEO tool based on Ahrefs data ☆`238`
- [proxy-intell/facebook-ads-library-mcp](https://github.com/proxy-intell/facebook-ads-library-mcp) — Facebook Ads Library search and access ☆`203`
- [surendranb/google-analytics-mcp](https://github.com/surendranb/google-analytics-mcp) — Google Analytics 4 data access ☆`199`
- [stape-io/google-tag-manager-mcp-server](https://github.com/stape-io/google-tag-manager-mcp-server) — MCP server for Google Tag Manager ☆`135`
- [gomarble-ai/google-ads-mcp-server](https://github.com/gomarble-ai/google-ads-mcp-server) — Google Ads performance data analysis ☆`114`
- [microsoft/clarity-mcp-server](https://github.com/microsoft/clarity-mcp-server) — Microsoft Clarity integration ☆`77`
- [builtwith/builtwith-mcp](https://github.com/builtwith/builtwith-mcp) — BuiltWith MCP Server ☆`40`
- [amekala/ads-mcp](https://github.com/amekala/ads-mcp) — MCP server for managing ad campaigns across Google Ads, Meta Ads, LinkedIn Ads, and TikTok Ads. 100+ tools for campaign creation, performance analysis, keyword research, and budget optimization. Works with ChatGPT, Claude, Gemini CLI, Cursor, Codex, and Windsurf. ☆`31`
- [rafaelstz/adobe-commerce-dev-mcp](https://github.com/rafaelstz/adobe-commerce-dev-mcp) — Adobe Commerce Dev MCP Server ☆`26`
- [Kiran1689/storyblok-mcp-server](https://github.com/Kiran1689/storyblok-mcp-server) — MCP server for Storyblok CMS management ☆`40`
- [metricool/mcp-metricool](https://github.com/metricool/mcp-metricool) — Metricool API integration ☆`35`
- [AdsMCP/tiktok-ads-mcp-server](https://github.com/AdsMCP/tiktok-ads-mcp-server) — TikTok Ads Marketing API integration via MCP ☆`26`
- [gvaibhav/TAM-MCP-Server](https://github.com/gvaibhav/TAM-MCP-Server) — Market sizing and TAM/SAM analysis ☆`29`
- [MarketplaceAdPros/amazon-ads-mcp-server](https://github.com/MarketplaceAdPros/amazon-ads-mcp-server) — MCP Server to interact with Amazon Ads ☆`20`
- [jonathan-politzki/smartlead-mcp-server](https://github.com/jonathan-politzki/smartlead-mcp-server) — Smartlead MCP deployment ☆`17`
## Media Processing

### 3D & Animation

- [ahujasid/blender-mcp](https://github.com/ahujasid/blender-mcp) — Blender 3D modeling with Claude AI ☆`19,820`
- [AIDC-AI/Pixelle-MCP](https://github.com/AIDC-AI/Pixelle-MCP) — Multimodal AIGC with ComfyUI + MCP ☆`952`
- [samuelgursky/davinci-resolve-mcp](https://github.com/samuelgursky/davinci-resolve-mcp) — MCP server integration for DaVinci Resolve ☆`811`
- [abhiemj/manim-mcp-server](https://github.com/abhiemj/manim-mcp-server) — Manim animation code execution ☆`581`
- [8beeeaaat/touchdesigner-mcp](https://github.com/8beeeaaat/touchdesigner-mcp) — MCP server for TouchDesigner ☆`275`
- [diivi/aseprite-mcp](https://github.com/diivi/aseprite-mcp) — MCP server for interacting with the Aseprite API ☆`143`
- [pranav-deshmukh/blender-mcp](https://github.com/pranav-deshmukh/blender-mcp) — Blender 3D modeling integration ☆`96`
- [PatrickPalmer/MayaMCP](https://github.com/PatrickPalmer/MayaMCP) — Autodesk Maya 3D integration ☆`67`
- [wilsonchenghy/ShaderToy-MCP](https://github.com/wilsonchenghy/ShaderToy-MCP) — Create and explore GLSL shaders on ShaderToy ☆`43`
### Audio & Music

- [elevenlabs/elevenlabs-mcp](https://github.com/elevenlabs/elevenlabs-mcp) — The official ElevenLabs MCP server ☆`1,309`
- [varunneal/spotify-mcp](https://github.com/varunneal/spotify-mcp) — MCP to connect your LLM with Spotify. ☆`595`
- [Simon-Kansara/ableton-live-mcp-server](https://github.com/Simon-Kansara/ableton-live-mcp-server) — Ableton Live OSC control ☆`375`
- [marcelmarais/spotify-mcp-server](https://github.com/marcelmarais/spotify-mcp-server) — Lightweight MCP server for Spotify ☆`294`
- [tiianhk/MaxMSP-MCP-Server](https://github.com/tiianhk/MaxMSP-MCP-Server) — MCP (Model Context Protocol) Server for Max (Max/MSP/Jitter) ☆`202`
- [adamjmurray/producer-pal](https://github.com/adamjmurray/producer-pal) — AI music production assistant for Ableton Live ☆`124`
- [dschuler36/reaper-mcp-server](https://github.com/dschuler36/reaper-mcp-server) — An MCP Server for interacting with Reaper projects. ☆`93`
- [SkyworkAI/Mureka-mcp](https://github.com/SkyworkAI/Mureka-mcp) — AI lyrics, song, and music generation ☆`88`
- [imprvhub/mcp-claude-spotify](https://github.com/imprvhub/mcp-claude-spotify) — Spotify interaction for Claude Desktop ☆`32`
- [TwelveTake-Studios/reaper-mcp](https://github.com/TwelveTake-Studios/reaper-mcp) —  ☆`16`
- [vsaez/mcp-spotify-player](https://github.com/vsaez/mcp-spotify-player) — MCP server to manage Spotify from MCP clients ☆`18`
### Image Generation

- [shinpr/mcp-image](https://github.com/shinpr/mcp-image) — AI image generation with Gemini 3 ☆`98`
- [SureScaleAI/openai-gpt-image-mcp](https://github.com/SureScaleAI/openai-gpt-image-mcp) — OpenAI GPT-4o image generation and editing ☆`100`
- [awkoy/replicate-flux-mcp](https://github.com/awkoy/replicate-flux-mcp) — MCP server for Replicate Flux image and SVG generation ☆`98`
- [Flyworks-AI/flyworks-mcp](https://github.com/Flyworks-AI/flyworks-mcp) — Fast and free zeroshot lipsync MCP server ☆`94`
- [GenWaveLLC/svgmaker-mcp](https://github.com/GenWaveLLC/svgmaker-mcp) — MCP server for SVG generation ☆`62`
- [apinetwork/piapi-mcp-server](https://github.com/apinetwork/piapi-mcp-server) — PiAPI media: Midjourney, Flux, Kling ☆`69`
- [hamflx/imagen3-mcp](https://github.com/hamflx/imagen3-mcp) — MCP server for Google Imagen 3 image generation ☆`61`
- [recraft-ai/mcp-recraft-server](https://github.com/recraft-ai/mcp-recraft-server) — Recraft API integration ☆`53`
- [InhiblabCore/mcp-image-compression](https://github.com/InhiblabCore/mcp-image-compression) — High-performance image compression service ☆`31`
- [WaveSpeedAI/mcp-server](https://github.com/WaveSpeedAI/mcp-server) — Image and video generation with WaveSpeed AI ☆`26`
- [zxkane/mcp-server-amazon-bedrock](https://github.com/zxkane/mcp-server-amazon-bedrock) — Amazon Bedrock Nova Canvas image generation ☆`24`
### Image Processing

- [steipete/Peekaboo](https://github.com/steipete/Peekaboo) — macOS screenshot and window capture MCP server ☆`3,124`
- [sunriseapps/imagesorcery-mcp](https://github.com/sunriseapps/imagesorcery-mcp) — Image processing operations ☆`303`
- [IDEA-Research/DINO-X-MCP](https://github.com/IDEA-Research/DINO-X-MCP) — MCP server for DINO-X vision model ☆`118`
- [groundlight/mcp-vision](https://github.com/groundlight/mcp-vision) — Computer vision models as MCP servers ☆`54`
- [MoussaabBadla/code-screenshot-mcp](https://github.com/MoussaabBadla/code-screenshot-mcp) — Generate code screenshots ☆`43`
- [nota/gyazo-mcp-server](https://github.com/nota/gyazo-mcp-server) — Official Model Context Protocol server for Gyazo ☆`25`
- [stass/exif-mcp](https://github.com/stass/exif-mcp) — MCP server to extract image metadata (EXIF, XMP, etc) ☆`36`
- [screenshotone/mcp](https://github.com/screenshotone/mcp) — A simple implementation of an MCP server for the ScreenshotOne API ☆`36`
- [upnorthmedia/ScreenshotMCP](https://github.com/upnorthmedia/ScreenshotMCP) — Website screenshot capture and optimization ☆`28`
- [magarcia/mcp-server-giphy](https://github.com/magarcia/mcp-server-giphy) — Giphy GIF integration ☆`28`
- [flowy11/imagician](https://github.com/flowy11/imagician) — A MCP server for image edition ☆`18`
### Video

- [kimtaeyoon83/mcp-server-youtube-transcript](https://github.com/kimtaeyoon83/mcp-server-youtube-transcript) — YouTube video transcript downloader ☆`521`
- [ZubeidHendricks/youtube-mcp-server](https://github.com/ZubeidHendricks/youtube-mcp-server) — YouTube API and video management ☆`494`
- [anaisbetts/mcp-youtube](https://github.com/anaisbetts/mcp-youtube) — A Model-Context Protocol Server for YouTube ☆`515`
- [eat-pray-ai/yutu](https://github.com/eat-pray-ai/yutu) — The AI-powered toolkit that grows your YouTube channel on autopilot. ☆`440`
- [burningion/video-editing-mcp](https://github.com/burningion/video-editing-mcp) — MCP Interface for Video Jungle ☆`260`
- [muxinc/mux-node-sdk](https://github.com/muxinc/mux-node-sdk) — Mux Video and Data API wrapper ☆`178`
- [Laksh-star/mcp-server-tmdb](https://github.com/Laksh-star/mcp-server-tmdb) — MCP Server with TMDB ☆`66`
- [nabid-pf/youtube-video-summarizer-mcp](https://github.com/nabid-pf/youtube-video-summarizer-mcp) — YouTube video captions and summarization ☆`58`
- [video-db/agent-toolkit](https://github.com/video-db/agent-toolkit) — MCP toolkit for video database operations ☆`49`
- [tan-yong-sheng/ai-vision-mcp](https://github.com/tan-yong-sheng/ai-vision-mcp) — Image and video analysis capabilities ☆`47`
- [raveenb/fal-mcp-server](https://github.com/raveenb/fal-mcp-server) — Fal.ai image, video, music generation ☆`42`
- [marcindulak/stt-mcp-server-linux](https://github.com/marcindulak/stt-mcp-server-linux) — Local speech-to-text for Tmux on Linux ☆`22`
- [omergocmen/json2video-mcp-server](https://github.com/omergocmen/json2video-mcp-server) — json2video API integration ☆`25`
- [sinjab/mcp_youtube_extract](https://github.com/sinjab/mcp_youtube_extract) — YouTube clip information extraction ☆`19`
- [TSavo/creatify-mcp](https://github.com/TSavo/creatify-mcp) — MCP server for AI video generation ☆`21`
- [13rac1/videocapture-mcp](https://github.com/13rac1/videocapture-mcp) — MCP server to capture images from webcam or video source ☆`17`
## Monitoring & Observability

- [grafana/mcp-grafana](https://github.com/grafana/mcp-grafana) — MCP server for Grafana ☆`2,824`
- [getsentry/sentry-mcp](https://github.com/getsentry/sentry-mcp) — An MCP server for interacting with Sentry via LLMs. ☆`636`
- [mpeirone/zabbix-mcp-server](https://github.com/mpeirone/zabbix-mcp-server) — MCP server for Zabbix monitoring with 40+ tools ☆`196`
- [comet-ml/opik-mcp](https://github.com/comet-ml/opik-mcp) — MCP server for Opik LLM evaluation platform ☆`203`
- [VictoriaMetrics/mcp-victoriametrics](https://github.com/VictoriaMetrics/mcp-victoriametrics) — VictoriaMetrics monitoring integration ☆`150`
- [langfuse/mcp-server-langfuse](https://github.com/langfuse/mcp-server-langfuse) — MCP server for Langfuse LLM observability ☆`160`
- [grafana/loki-mcp](https://github.com/grafana/loki-mcp) — An MCP ( Model Context Protocol ) Server for Grafana Loki ☆`119`
- [dynatrace-oss/dynatrace-mcp](https://github.com/dynatrace-oss/dynatrace-mcp) — MCP server for Dynatrace Observability ☆`106`
- [PagerDuty/pagerduty-mcp-server](https://github.com/PagerDuty/pagerduty-mcp-server) — PagerDuty official MCP server ☆`62`
- [seekrays/mcp-monitor](https://github.com/seekrays/mcp-monitor) — MCP server monitoring tool ☆`80`
- [last9/last9-mcp-server](https://github.com/last9/last9-mcp-server) — Last9 MCP Server ☆`54`
- [GeLi2001/datadog-mcp-server](https://github.com/GeLi2001/datadog-mcp-server) — MCP server interacts with the official Datadog API ☆`66`
- [metoro-io/metoro-mcp-server](https://github.com/metoro-io/metoro-mcp-server) — Metoro MCP Server ☆`49`
- [tjhop/prometheus-mcp-server](https://github.com/tjhop/prometheus-mcp-server) — MCP server for LLMs to interact with Prometheus ☆`44`
- [Rootly-AI-Labs/rootly-mcp-server](https://github.com/Rootly-AI-Labs/rootly-mcp-server) — Rootly MCP server ☆`41`
- [mcpcap/mcpcap](https://github.com/mcpcap/mcpcap) — Network analysis for the AI age ☆`34`
- [inspektor-gadget/ig-mcp-server](https://github.com/inspektor-gadget/ig-mcp-server) — Container and Kubernetes debugging with AI ☆`24`
- [RedHatInsights/insights-mcp](https://github.com/RedHatInsights/insights-mcp) — Red Hat Insights AI connection ☆`18`
- [MindscapeHQ/mcp-server-raygun](https://github.com/MindscapeHQ/mcp-server-raygun) — Raygun error investigation for AI ☆`20`
- [mhajder/librenms-mcp](https://github.com/mhajder/librenms-mcp) — MCP server for LibreNMS management ☆`21`
- [tgeselle/bugsnag-mcp](https://github.com/tgeselle/bugsnag-mcp) — MCP server for Bugsnag error monitoring ☆`20`
- [Pratyay/mac-monitor-mcp](https://github.com/Pratyay/mac-monitor-mcp) — MCP server for macOS system monitoring ☆`20`
- [ntk148v/alertmanager-mcp-server](https://github.com/ntk148v/alertmanager-mcp-server) — MCP server for Prometheus Alertmanager integration ☆`17`
- [tumf/grafana-loki-mcp](https://github.com/tumf/grafana-loki-mcp) — Grafana Loki MCP Repository ☆`24`
- [emicklei/mcp-log-proxy](https://github.com/emicklei/mcp-log-proxy) — a web logging proxy for MCP client-server communication ☆`28`
## Productivity

### Atlassian

- [sooperset/mcp-atlassian](https://github.com/sooperset/mcp-atlassian) — MCP server for Atlassian tools (Confluence, Jira) ☆`4,942`
- [aashari/mcp-server-atlassian-bitbucket](https://github.com/aashari/mcp-server-atlassian-bitbucket) — Atlassian Bitbucket repositories and PRs ☆`140`
- [nguyenvanduocit/jira-mcp](https://github.com/nguyenvanduocit/jira-mcp) — Jira issues and sprints via Go MCP ☆`86`
- [aashari/mcp-server-atlassian-jira](https://github.com/aashari/mcp-server-atlassian-jira) — Atlassian Jira projects, issues and sprints ☆`64`
- [aashari/mcp-server-atlassian-confluence](https://github.com/aashari/mcp-server-atlassian-confluence) — Atlassian Confluence spaces and pages ☆`50`
- [phuc-nt/mcp-atlassian-server](https://github.com/phuc-nt/mcp-atlassian-server) — Jira and Confluence integration ☆`51`
- [KS-GEN-AI/jira-mcp-server](https://github.com/KS-GEN-AI/jira-mcp-server) — A test of jira mcp server ☆`25`
- [rahulthedevil/Jira-Context-MCP](https://github.com/rahulthedevil/Jira-Context-MCP) — Jira tickets info for AI coding agents ☆`25`
### Collaboration

- [evalstate/mcp-miro](https://github.com/evalstate/mcp-miro) — MCP server for Miro whiteboard manipulation and sticky creation ☆`109`
- [orellazri/coda-mcp](https://github.com/orellazri/coda-mcp) — MCP Server for Coda ☆`56`
- [hiromitsusasaki/raindrop-io-mcp-server](https://github.com/hiromitsusasaki/raindrop-io-mcp-server) — Raindrop.io bookmark management ☆`72`
- [k-jarzyna/mcp-miro](https://github.com/k-jarzyna/mcp-miro) — Miro integration for Model Context Protocol ☆`62`
- [kintone/mcp-server](https://github.com/kintone/mcp-server) — kintone official MCP server ☆`42`
- [Fibery-inc/fibery-mcp-server](https://github.com/Fibery-inc/fibery-mcp-server) — MCP server for Fibery workspace integration ☆`30`
### Documents

- [zcaceres/markdownify-mcp](https://github.com/zcaceres/markdownify-mcp) — Convert almost anything to Markdown ☆`2,590`
- [vivekVells/mcp-pandoc](https://github.com/vivekVells/mcp-pandoc) — MCP server for document format conversion using pandoc. ☆`527`
- [onebirdrocks/ebook-mcp](https://github.com/onebirdrocks/ebook-mcp) — MCP server for ebook processing ☆`358`
- [baruchiro/paperless-mcp](https://github.com/baruchiro/paperless-mcp) — MCP server for Paperless-NGX document management ☆`88`
- [PSPDFKit/nutrient-dws-mcp-server](https://github.com/PSPDFKit/nutrient-dws-mcp-server) — Nutrient Document Web Services ☆`63`
- [Unstructured-IO/UNS-MCP](https://github.com/Unstructured-IO/UNS-MCP) — MCP server for Unstructured document processing ☆`43`
- [vgnshiyer/apple-books-mcp](https://github.com/vgnshiyer/apple-books-mcp) — Apple Books MCP Server ☆`45`
- [esignaturescom/mcp-server-esignatures](https://github.com/esignaturescom/mcp-server-esignatures) — eSignatures.com document signing ☆`36`
- [danielkennedy1/pdf-tools-mcp](https://github.com/danielkennedy1/pdf-tools-mcp) — MCP server for PDF manipulation (merge, extract, snippets) ☆`31`
- [gpetraroli/mcp_pdf_reader](https://github.com/gpetraroli/mcp_pdf_reader) — An MCP server to extraxt/search text from pdf ☆`31`
- [thechandanbhagat/cv-forge](https://github.com/thechandanbhagat/cv-forge) — MCP to tailored CV based on job description ☆`25`
- [intsig-textin/textin-mcp](https://github.com/intsig-textin/textin-mcp) — OCR and document-to-Markdown conversion ☆`28`
### Google Workspace

- [taylorwilsdon/google_workspace_mcp](https://github.com/taylorwilsdon/google_workspace_mcp) — MCP server for Google Workspace integration ☆`2,123`
- [MarkusPfundstein/mcp-gsuite](https://github.com/MarkusPfundstein/mcp-gsuite) — MCP Server to interact with Google Gsuite prodcuts ☆`486`
- [v-3/google-calendar](https://github.com/v-3/google-calendar) — Google Calendar events and scheduling ☆`70`
- [baryhuang/mcp-headless-gmail](https://github.com/baryhuang/mcp-headless-gmail) — Gmail without local credentials ☆`56`
- [giuseppe-coco/Google-Workspace-MCP-Server](https://github.com/giuseppe-coco/Google-Workspace-MCP-Server) — Gmail, Calendar, and Drive integration ☆`28`
### Helpdesk & Support

- [echelon-ai-labs/servicenow-mcp](https://github.com/echelon-ai-labs/servicenow-mcp) — MCP Server for ServiceNow ☆`241`
- [effytech/freshdesk_mcp](https://github.com/effytech/freshdesk_mcp) — Freshdesk support ticket integration ☆`57`
- [modesty/fluent-mcp](https://github.com/modesty/fluent-mcp) — MCP server for Fluent (ServiceNow SDK) ☆`24`
- [quickchatai/quickchat-ai-mcp](https://github.com/quickchatai/quickchat-ai-mcp) — The Quickchat AI MCP server ☆`23`
### Learning & Flashcards

- [ankimcp/anki-mcp-server](https://github.com/ankimcp/anki-mcp-server) — MCP server for Anki spaced repetition flashcards ☆`225`
- [scorzeth/anki-mcp-server](https://github.com/scorzeth/anki-mcp-server) — An MCP server for Anki ☆`179`
- [jinzcdev/leetcode-mcp-server](https://github.com/jinzcdev/leetcode-mcp-server) — MCP server for LeetCode problems and solutions ☆`107`
- [rember/rember-mcp](https://github.com/rember/rember-mcp) — A Model Context Protocol (MCP) server for Rember. ☆`63`
- [nietus/anki-mcp](https://github.com/nietus/anki-mcp) — MCP server for anki ☆`39`
- [doggybee/mcp-server-leetcode](https://github.com/doggybee/mcp-server-leetcode) — MCP server for LeetCode coding challenges ☆`40`
- [spacholski1225/anki-connect-mcp](https://github.com/spacholski1225/anki-connect-mcp) — MCP implementation for Anki Web ☆`18`
### Microsoft 365

- [haris-musa/excel-mcp-server](https://github.com/haris-musa/excel-mcp-server) — Excel file manipulation ☆`3,699`
- [Softeria/ms-365-mcp-server](https://github.com/Softeria/ms-365-mcp-server) — Microsoft 365 and Office via Graph API ☆`622`
- [InditexTech/mcp-teams-server](https://github.com/InditexTech/mcp-teams-server) — MCP server for Microsoft Teams integration ☆`368`
- [merill/lokka](https://github.com/merill/lokka) — MCP for Microsoft 365 and Graph ☆`235`
- [sbroenne/mcp-server-excel](https://github.com/sbroenne/mcp-server-excel) — Excel MCP Server - 23 tools for AI-powered automation ☆`119`
- [pnp/cli-microsoft365-mcp-server](https://github.com/pnp/cli-microsoft365-mcp-server) — Manage Microsoft 365 using MCP server ☆`98`
- [Norcim133/OutlookMCPServer](https://github.com/Norcim133/OutlookMCPServer) — MCP Server for msgraph - mail, calendar, files ☆`17`
### Note-taking & Docs

- [RafalWilinski/mcp-apple-notes](https://github.com/RafalWilinski/mcp-apple-notes) — RAG over Apple Notes for Claude ☆`377`
- [lostintangent/gistpad-mcp](https://github.com/lostintangent/gistpad-mcp) — Personal knowledge and daily notes management ☆`189`
- [Vortiago/mcp-outline](https://github.com/Vortiago/mcp-outline) — AI assistants with Outline docs ☆`137`
- [entanglr/zettelkasten-mcp](https://github.com/entanglr/zettelkasten-mcp) — MCP server implementing Zettelkasten knowledge management ☆`148`
- [gornskew/lisply-mcp](https://github.com/gornskew/lisply-mcp) — Manage Lisply lisp-speaking backends ☆`48`
- [2slides/mcp-2slides](https://github.com/2slides/mcp-2slides) — MCP Server for 2slides - AI agent for PPT generation ☆`28`
- [akseyh/bear-mcp-server](https://github.com/akseyh/bear-mcp-server) — MCP Server integration for Bear note app ☆`44`
- [Harry-027/JotDown](https://github.com/Harry-027/JotDown) — An MCP Server in Rust for creating Notion pages & mdBooks with LLMs ☆`21`
- [Piotr1215/mcp-obsidian](https://github.com/Piotr1215/mcp-obsidian) — simple mcp server for interacting with local obsidian notes ☆`21`
- [ONLYOFFICE/docspace-mcp](https://github.com/ONLYOFFICE/docspace-mcp) — DocSpace MCP Server ☆`20`
- [danield137/mcp-workflowy](https://github.com/danield137/mcp-workflowy) — An MCP server for workflowy ☆`27`
- [joshylchen/zettelkasten](https://github.com/joshylchen/zettelkasten) — Comprehensive AI-powered knowledge management system implementing the Zettelkasten method. Features atomic note creation, full-text search, AI-powered CEQRC workflows (Capture→Explain→Question→Refine→Connect), intelligent link discovery, and multi-interface access (CLI, API, Web UI, MCP). Perfect for researchers, students, and knowledge workers. ☆`23`
### Notion

- [makenotion/notion-mcp-server](https://github.com/makenotion/notion-mcp-server) — Official Notion MCP Server ☆`4,219`
- [suekou/mcp-notion-server](https://github.com/suekou/mcp-notion-server) — MCP server for Notion API with Markdown conversion ☆`879`
- [danhilse/notion_mcp](https://github.com/danhilse/notion_mcp) — Notion integration with advanced formatting ☆`207`
- [Badhansen/notion-mcp](https://github.com/Badhansen/notion-mcp) — Notion workspace management ☆`29`
### Obsidian

- [MarkusPfundstein/mcp-obsidian](https://github.com/MarkusPfundstein/mcp-obsidian) — Obsidian integration via REST API plugin ☆`3,376`
- [bitbonsai/mcpvault](https://github.com/bitbonsai/mcpvault) — Lightweight Obsidian vault access ☆`1,086`
- [StevenStavrakis/obsidian-mcp](https://github.com/StevenStavrakis/obsidian-mcp) — A simple MCP server for Obsidian ☆`678`
### Project Management

- [mondaycom/mcp](https://github.com/mondaycom/mcp) — AI agents with secure data access ☆`395`
- [jerhadf/linear-mcp-server](https://github.com/jerhadf/linear-mcp-server) — MCP server for Linear issue tracking ☆`344`
- [makeplane/plane-mcp-server](https://github.com/makeplane/plane-mcp-server) — Plane's Official Model Context Protocol Server ☆`193`
- [roychri/mcp-server-asana](https://github.com/roychri/mcp-server-asana) — MCP server for Asana task and project management ☆`137`
- [its-dart/dart-mcp-server](https://github.com/its-dart/dart-mcp-server) — Dart AI Model Context Protocol (MCP) server ☆`127`
- [taskade/mcp](https://github.com/taskade/mcp) — MCP server for Taskade project management ☆`120`
- [tacticlaunch/mcp-linear](https://github.com/tacticlaunch/mcp-linear) — MCP server for Linear project management ☆`133`
- [useshortcut/mcp-server-shortcut](https://github.com/useshortcut/mcp-server-shortcut) — The MCP server for Shortcut ☆`97`
- [tonyzorin/youtrack-mcp](https://github.com/tonyzorin/youtrack-mcp) — YouTrack server, ARM64 and AMD64 ☆`84`
- [georgeantonopoulos/Basecamp-MCP-Server](https://github.com/georgeantonopoulos/Basecamp-MCP-Server) — Basecamp 3+ project management ☆`82`
- [feuerdev/keep-mcp](https://github.com/feuerdev/keep-mcp) — MCP server for Google Keep ☆`71`
- [aikts/yandex-tracker-mcp](https://github.com/aikts/yandex-tracker-mcp) — Yandex Tracker MCP Server with OAuth2 support ☆`62`
- [m0xai/trello-mcp-server](https://github.com/m0xai/trello-mcp-server) — A simple yet powerful MCP server for Trello. ☆`52`
- [taazkareem/clickup-mcp-server](https://github.com/taazkareem/clickup-mcp-server) — ClickUp MCP Server - project management with AI ☆`29`
- [EduBase/MCP](https://github.com/EduBase/MCP) — MCP server for EduBase e-learning platform ☆`25`
- [kelvin6365/plane-mcp-server](https://github.com/kelvin6365/plane-mcp-server) — MCP server for Plane.so project management ☆`38`
- [kocakli/Trello-Desktop-MCP](https://github.com/kocakli/Trello-Desktop-MCP) — Trello integration for Claude Desktop via MCP ☆`23`
- [Teamwork/mcp](https://github.com/Teamwork/mcp) — Teamwork.com MCP server ☆`17`
- [Prat011/mcp-server-monday](https://github.com/Prat011/mcp-server-monday) — MCP Server to interact with Monday.com boards and items ☆`34`
- [bivex/kanboard-mcp](https://github.com/bivex/kanboard-mcp) — MCP server for Kanboard project management integration ☆`21`
### Tasks & Calendar

- [screenpipe/screenpipe](https://github.com/screenpipe/screenpipe) — AI app store with 24/7 desktop history ☆`18,214`
- [nspady/google-calendar-mcp](https://github.com/nspady/google-calendar-mcp) — MCP integration for Google Calendar to manage events. ☆`1,093`
- [Doist/todoist-ai](https://github.com/Doist/todoist-ai) — Todoist tools for AI agents ☆`448`
- [abhiz123/todoist-mcp-server](https://github.com/abhiz123/todoist-mcp-server) — Todoist natural language task management ☆`386`
- [Omar-V2/mcp-ical](https://github.com/Omar-V2/mcp-ical) — Interact with MacOS Calendar ☆`299`
- [zcaceres/gtasks-mcp](https://github.com/zcaceres/gtasks-mcp) — A Google Tasks Model Context Protocol Server for Claude ☆`124`
- [alexarevalo9/ticktick-mcp-server](https://github.com/alexarevalo9/ticktick-mcp-server) — TickTick task management ☆`70`
- [dominik1001/caldav-mcp](https://github.com/dominik1001/caldav-mcp) — CalDAV calendar sync ☆`62`
- [stanislavlysenko0912/todoist-mcp-server](https://github.com/stanislavlysenko0912/todoist-mcp-server) — Todoist Rest API and Sync API ☆`60`
- [jen6/ticktick-mcp](https://github.com/jen6/ticktick-mcp) — TickTick task management with filtering ☆`65`
- [awwaiid/mcp-server-taskwarrior](https://github.com/awwaiid/mcp-server-taskwarrior) — MCP Server for TaskWarrior! ☆`46`
- [takumi0706/google-calendar-mcp](https://github.com/takumi0706/google-calendar-mcp) — Google Calendar for Claude Desktop ☆`56`
- [arpitbatra123/mcp-googletasks](https://github.com/arpitbatra123/mcp-googletasks) — MCP server for Google Tasks management ☆`35`
- [urbanogardun/things3-mcp](https://github.com/urbanogardun/things3-mcp) — MCP server for Things3 integration on macOS ☆`21`
- [flesler/mcp-tasks](https://github.com/flesler/mcp-tasks) — Efficient task management with views ☆`41`
- [jbrinkman/valkey-ai-tasks](https://github.com/jbrinkman/valkey-ai-tasks) — MCP server for task management with Valkey persistence ☆`25`
- [hichana/goalstory-mcp](https://github.com/hichana/goalstory-mcp) — Goal tracking with AI-powered storytelling ☆`18`
- [Danielpeter-99/calcom-mcp](https://github.com/Danielpeter-99/calcom-mcp) — A FastMCP server for interacting with the Cal.com API. This enables LLMs to manage event types, create bookings, and access Cal.com scheduling data programmatically. ☆`16`
### Wiki & Collaboration

- [anyproto/anytype-mcp](https://github.com/anyproto/anytype-mcp) — AI with Anytype encrypted local data ☆`379`
- [ProfessionalWiki/MediaWiki-MCP-Server](https://github.com/ProfessionalWiki/MediaWiki-MCP-Server) — Connect AI with any MediaWiki ☆`75`
- [HenryHaoson/Yuque-MCP-Server](https://github.com/HenryHaoson/Yuque-MCP-Server) — Yuque mcp server ☆`59`
- [yuna0x0/hackmd-mcp](https://github.com/yuna0x0/hackmd-mcp) — HackMD note-taking integration ☆`55`
## Research & Science

- [oOo0oOo/lean-lsp-mcp](https://github.com/oOo0oOo/lean-lsp-mcp) — Lean Theorem Prover MCP ☆`360`
- [szeider/mcp-solver](https://github.com/szeider/mcp-solver) — Constraint optimization and solving ☆`160`
- [NellyW8/MCP4EDA](https://github.com/NellyW8/MCP4EDA) — RTL-to-GDSII automation with LLM ☆`83`
- [SecretiveShell/MCP-wolfram-alpha](https://github.com/SecretiveShell/MCP-wolfram-alpha) — Wolfram Alpha computational intelligence ☆`74`
- [Pantheon-Security/notebooklm-mcp-secure](https://github.com/Pantheon-Security/notebooklm-mcp-secure) — Secure NotebookLM MCP with 14 security layers ☆`53`
- [neuromechanist/matlab-mcp-tools](https://github.com/neuromechanist/matlab-mcp-tools) —  ☆`17`
- [IO-Aerospace-software-engineering/mcp-server](https://github.com/IO-Aerospace-software-engineering/mcp-server) — An aerospace server who implements model context protocol ☆`16`
## Sandboxing & Execution

- [superradcompany/microsandbox](https://github.com/superradcompany/microsandbox) — secure, local, cross-platform and programmable sandboxes for AI agents ☆`5,407`
- [dagger/container-use](https://github.com/dagger/container-use) — MCP server for container orchestration ☆`3,725`
- [e2b-dev/mcp-server](https://github.com/e2b-dev/mcp-server) — E2B code execution for Claude ☆`389`
- [Automata-Labs-team/code-sandbox-mcp](https://github.com/Automata-Labs-team/code-sandbox-mcp) — Secure code sandbox in Docker ☆`319`
- [bazinga012/mcp_code_executor](https://github.com/bazinga012/mcp_code_executor) — Execute Python in Conda environment ☆`214`
- [hopx-ai/mcp](https://github.com/hopx-ai/mcp) — Execute code in isolated cloud containers ☆`162`
- [alfonsograziano/node-code-sandbox-mcp](https://github.com/alfonsograziano/node-code-sandbox-mcp) — MCP server for Node.js code sandbox execution ☆`152`
- [gradion-ai/ipybox](https://github.com/gradion-ai/ipybox) — Python code execution sandbox with MCP tool calling ☆`74`
- [yepcode/mcp-server-js](https://github.com/yepcode/mcp-server-js) — JavaScript MCP server framework by YepCode ☆`43`
- [r33drichards/mcp-js](https://github.com/r33drichards/mcp-js) — MCP server exposing V8 JavaScript runtime for AI agents ☆`43`
- [hileamlakB/Python-Runtime-Interpreter-MCP-Server](https://github.com/hileamlakB/Python-Runtime-Interpreter-MCP-Server) — Safe Python runtime interpreter ☆`27`
- [gwbischof/outsource-mcp](https://github.com/gwbischof/outsource-mcp) — Give your AI assistant its own AI assistants. ☆`28`
## Search & Extraction

### Academic Research

- [blazickjp/arxiv-mcp-server](https://github.com/blazickjp/arxiv-mcp-server) — arXiv paper search and analysis ☆`2,539`
- [JackKuo666/Google-Scholar-MCP-Server](https://github.com/JackKuo666/Google-Scholar-MCP-Server) — Search Google Scholar papers ☆`286`
- [andybrandt/mcp-simple-arxiv](https://github.com/andybrandt/mcp-simple-arxiv) — arXiv paper search and reading ☆`189`
- [reading-plus-ai/mcp-server-deep-research](https://github.com/reading-plus-ai/mcp-server-deep-research) — Comprehensive research with reports ☆`209`
- [andybrandt/mcp-simple-pubmed](https://github.com/andybrandt/mcp-simple-pubmed) — PubMed medical research search ☆`163`
- [adityak74/mcp-scholarly](https://github.com/adityak74/mcp-scholarly) — A MCP server to search for accurate academic articles. ☆`178`
- [kaliaboi/mcp-zotero](https://github.com/kaliaboi/mcp-zotero) — Zotero collections for Claude Desktop ☆`158`
- [takashiishida/arxiv-latex-mcp](https://github.com/takashiishida/arxiv-latex-mcp) — MCP server for arXiv LaTeX paper retrieval ☆`123`
- [JackKuo666/PubMed-MCP-Server](https://github.com/JackKuo666/PubMed-MCP-Server) — Search and analyze PubMed articles ☆`107`
- [OctagonAI/octagon-deep-research-mcp](https://github.com/OctagonAI/octagon-deep-research-mcp) — AI-powered comprehensive research and analysis ☆`87`
- [akalaric/mcp-wolframalpha](https://github.com/akalaric/mcp-wolframalpha) — Wolfram Alpha integration for Python ☆`78`
- [HzaCode/OneCite](https://github.com/HzaCode/OneCite) — Parse and format academic references ☆`56`
- [szeider/mcp-dblp](https://github.com/szeider/mcp-dblp) — Access DBLP computer science bibliography ☆`32`
- [prashalruchiranga/arxiv-mcp-server](https://github.com/prashalruchiranga/arxiv-mcp-server) — arXiv API via natural language ☆`40`
- [drAbreu/alex-mcp](https://github.com/drAbreu/alex-mcp) — MCP server for OpenAlex ☆`39`
- [hbg/mcp-paperswithcode](https://github.com/hbg/mcp-paperswithcode) — MCP interface for PapersWithCode API ☆`21`
- [mochow13/google-scholar-mcp](https://github.com/mochow13/google-scholar-mcp) — MCP server for Google Scholar written in TypeScript ☆`20`
- [JackKuo666/bioRxiv-MCP-Server](https://github.com/JackKuo666/bioRxiv-MCP-Server) — Access bioRxiv papers ☆`22`
### Data APIs

- [cantian-ai/bazi-mcp](https://github.com/cantian-ai/bazi-mcp) — Bazi Chinese astrology information ☆`356`
- [Rudra-ravi/wikipedia-mcp](https://github.com/Rudra-ravi/wikipedia-mcp) — Retrieve Wikipedia information ☆`231`
- [ahonn/mcp-server-gsc](https://github.com/ahonn/mcp-server-gsc) — Google Search Console data access ☆`204`
- [hellokaton/unsplash-mcp-server](https://github.com/hellokaton/unsplash-mcp-server) — A MCP server for Unsplash image search. ☆`214`
- [deadletterq/mcp-opennutrition](https://github.com/deadletterq/mcp-opennutrition) — MCP server for nutrition data and analysis ☆`175`
- [OpenDataMCP/OpenDataMCP](https://github.com/OpenDataMCP/OpenDataMCP) — Connect any Open Data to any LLM with Model Context Protocol. ☆`148`
- [cswkim/discogs-mcp-server](https://github.com/cswkim/discogs-mcp-server) — MCP Server for Discogs ☆`94`
- [damionrashford/RivalSearchMCP](https://github.com/damionrashford/RivalSearchMCP) — MCP server for competitive search analysis ☆`71`
- [8enSmith/mcp-open-library](https://github.com/8enSmith/mcp-open-library) — MCP server for Open Library book and author search ☆`67`
- [yuna0x0/anilist-mcp](https://github.com/yuna0x0/anilist-mcp) — AniList MCP server for accessing anime and manga data ☆`72`
- [zoomeye-ai/mcp_zoomeye](https://github.com/zoomeye-ai/mcp_zoomeye) — MCP server for ZoomEye network asset information ☆`70`
- [riemannzeta/patent_mcp_server](https://github.com/riemannzeta/patent_mcp_server) — FastMCP Server for USPTO data ☆`52`
- [cameronrye/openzim-mcp](https://github.com/cameronrye/openzim-mcp) — MCP server for OpenZIM archive access ☆`54`
- [anysiteio/anysite-mcp-server](https://github.com/anysiteio/anysite-mcp-server) — LinkedIn data access ☆`60`
- [Linked-API/linkedapi-mcp](https://github.com/Linked-API/linkedapi-mcp) — LinkedIn account control and data retrieval ☆`46`
- [zzaebok/mcp-wikidata](https://github.com/zzaebok/mcp-wikidata) — Wikidata API implementation ☆`42`
- [djalal/quran-mcp-server](https://github.com/djalal/quran-mcp-server) — Quran.com verses, translations, tafsir ☆`62`
- [r-huijts/rijksmuseum-mcp](https://github.com/r-huijts/rijksmuseum-mcp) — Rijksmuseum artwork exploration ☆`66`
- [0xDAEF0F/job-searchoor](https://github.com/0xDAEF0F/job-searchoor) — A simple MCP server that delivers you jobs based on your needs ☆`60`
- [yamanoku/baseline-mcp-server](https://github.com/yamanoku/baseline-mcp-server) — Web API Baseline status information ☆`36`
- [imprvhub/mcp-domain-availability](https://github.com/imprvhub/mcp-domain-availability) — MCP server to check domain availability ☆`44`
- [amurshak/congressMCP](https://github.com/amurshak/congressMCP) — US Congress data for AI agents ☆`28`
- [mikechao/metmuseum-mcp](https://github.com/mikechao/metmuseum-mcp) — Met Museum art collection discovery ☆`26`
- [kehvinbehvin/json-mcp-filter](https://github.com/kehvinbehvin/json-mcp-filter) — JSON MCP server to filter only relevant data for your LLM ☆`23`
- [DappierAI/dappier-mcp](https://github.com/DappierAI/dappier-mcp) — MCP server for Dappier AI integration ☆`39`
- [adawalli/nexus](https://github.com/adawalli/nexus) — MCP Server to make searching openrouter easy ☆`19`
- [Himalayas-App/himalayas-mcp](https://github.com/Himalayas-App/himalayas-mcp) — A Model Context Protocol (MCP) server that provides access to remote job listings and company information from Himalayas.app. ☆`16`
- [JamesANZ/us-legal-mcp](https://github.com/JamesANZ/us-legal-mcp) — An MCP server that provides comprehensive US legislation. ☆`22`
- [delorenj/mcp-server-ticketmaster](https://github.com/delorenj/mcp-server-ticketmaster) — Ticketmaster Discovery API ☆`24`
- [r-huijts/opentk-mcp](https://github.com/r-huijts/opentk-mcp) — MCP server for Dutch parliamentary data via OpenTK ☆`20`
- [joelio/stocky](https://github.com/joelio/stocky) — An MCP server for searching and downloading stock photography. ☆`18`
- [siva010928/multi-chat-mcp-server](https://github.com/siva010928/multi-chat-mcp-server) — MCP server for multi-chat capabilities ☆`21`
- [AshwinSundar/congress_gov_mcp](https://github.com/AshwinSundar/congress_gov_mcp) — Query US Congress.gov API ☆`19`
- [angheljf/nyt](https://github.com/angheljf/nyt) — MCP server for New York Times article search ☆`18`
### News & Content

- [lfnovo/content-core](https://github.com/lfnovo/content-core) — Extract what matters from any media source ☆`147`
- [erithwik/mcp-hn](https://github.com/erithwik/mcp-hn) — MCP Server for Hackernews ☆`71`
- [imprvhub/mcp-rss-aggregator](https://github.com/imprvhub/mcp-rss-aggregator) — RSS feed aggregation for Claude Desktop ☆`24`
- [pskill9/hn-server](https://github.com/pskill9/hn-server) — Hacker news MCP server ☆`38`
- [format37/youtube_mcp](https://github.com/format37/youtube_mcp) — youtube transcriber mcp server ☆`30`
- [the0807/GeekNews-MCP-Server](https://github.com/the0807/GeekNews-MCP-Server) — GeekNews MCP Server ☆`16`
### Web Search Engines

- [exa-labs/exa-mcp-server](https://github.com/exa-labs/exa-mcp-server) — Exa MCP for web search and web crawling! ☆`4,251`
- [tavily-ai/tavily-mcp](https://github.com/tavily-ai/tavily-mcp) — Real-time search, extract, map and crawl ☆`1,763`
- [nickclyde/duckduckgo-mcp-server](https://github.com/nickclyde/duckduckgo-mcp-server) — MCP server for DuckDuckGo search ☆`988`
- [Aas-ee/open-webSearch](https://github.com/Aas-ee/open-webSearch) — MCP server for open web search ☆`992`
- [brave/brave-search-mcp-server](https://github.com/brave/brave-search-mcp-server) — Brave Search with AI summarization ☆`902`
- [mrkrsl/web-search-mcp](https://github.com/mrkrsl/web-search-mcp) — Local web search for Claude Desktop ☆`768`
- [ihor-sokoliuk/mcp-searxng](https://github.com/ihor-sokoliuk/mcp-searxng) — MCP Server for SearXNG ☆`643`
- [pskill9/web-search](https://github.com/pskill9/web-search) — Web search using free google search (NO API KEYS REQUIRED) ☆`442`
- [kagisearch/kagimcp](https://github.com/kagisearch/kagimcp) — Official Kagi search MCP server ☆`361`
- [jae-jae/g-search-mcp](https://github.com/jae-jae/g-search-mcp) — Parallel Google search with summaries ☆`260`
- [fatwang2/search1api-mcp](https://github.com/fatwang2/search1api-mcp) — MCP server for web search and crawl via Search1API ☆`172`
- [serpapi/serpapi-mcp](https://github.com/serpapi/serpapi-mcp) — SerpApi MCP Server for Google and other search engine results ☆`125`
- [nkapila6/mcp-local-rag](https://github.com/nkapila6/mcp-local-rag) — RAG-like web search via MCP ☆`122`
- [ChanMeng666/server-google-news](https://github.com/ChanMeng666/server-google-news) — MCP server for Google News integration ☆`121`
- [mikechao/brave-search-mcp](https://github.com/mikechao/brave-search-mcp) — MCP server for Brave Search with filtering options ☆`114`
- [SecretiveShell/MCP-searxng](https://github.com/SecretiveShell/MCP-searxng) — SearXNG search for agentic systems ☆`116`
- [tanigami/mcp-server-perplexity](https://github.com/tanigami/mcp-server-perplexity) — Perplexity API chat with citations ☆`91`
- [ConechoAI/openai-websearch-mcp](https://github.com/ConechoAI/openai-websearch-mcp) — openai websearch tool as mcp server ☆`87`
- [gleanwork/mcp-server](https://github.com/gleanwork/mcp-server) — MCP server for Glean API integration ☆`56`
- [leehanchung/bing-search-mcp](https://github.com/leehanchung/bing-search-mcp) — MCP Server for Bing Search API ☆`79`
- [zhsama/duckduckgo-mcp-server](https://github.com/zhsama/duckduckgo-mcp-server) — MCP server for DuckDuckGo web search ☆`74`
- [isnow890/naver-search-mcp](https://github.com/isnow890/naver-search-mcp) — MCP server for Naver search integration ☆`60`
- [pwilkin/mcp-searxng-public](https://github.com/pwilkin/mcp-searxng-public) — Query public SearXNG instances ☆`41`
- [OvertliDS/mcp-searxng-enhanced](https://github.com/OvertliDS/mcp-searxng-enhanced) — SearXNG web search with category awareness ☆`36`
- [ubie-oss/mcp-vertexai-search](https://github.com/ubie-oss/mcp-vertexai-search) — A MCP server for Vertex AI Search ☆`35`
- [Tomatio13/mcp-server-tavily](https://github.com/Tomatio13/mcp-server-tavily) — MCP Server for Tavily API integration ☆`48`
- [ac3xx/mcp-servers-kagi](https://github.com/ac3xx/mcp-servers-kagi) — A Model Context Protocol server implementation for Kagi's API ☆`44`
- [garylab/serper-mcp-server](https://github.com/garylab/serper-mcp-server) — A Serper MCP Server ☆`32`
- [mnhlt/WebSearch-MCP](https://github.com/mnhlt/WebSearch-MCP) — MCP server for web search integration ☆`32`
- [parallel-web/search-mcp](https://github.com/parallel-web/search-mcp) —  ☆`16`
## Security

### Identity & Access

- [auth0/auth0-mcp-server](https://github.com/auth0/auth0-mcp-server) — Auth0 tenant management via natural language ☆`100`
- [box-community/mcp-server-box](https://github.com/box-community/mcp-server-box) — Enterprise content access in Box ☆`99`
- [firstorderai/authenticator_mcp](https://github.com/firstorderai/authenticator_mcp) — Authenticator App for AI agents ☆`36`
- [atomicchonk/roadrecon_mcp_server](https://github.com/atomicchonk/roadrecon_mcp_server) — Azure AD ROADrecon analysis for Claude ☆`50`
- [sshaaf/keycloak-mcp-server](https://github.com/sshaaf/keycloak-mcp-server) — MCP server for Keycloak identity and access management ☆`40`
- [kapilduraphe/okta-mcp-server](https://github.com/kapilduraphe/okta-mcp-server) — Okta MCP Server ☆`20`
- [hieuttmmo/entraid-mcp-server](https://github.com/hieuttmmo/entraid-mcp-server) — EntraID via Microsoft Graph API ☆`36`
- [ChristophEnglisch/keycloak-model-context-protocol](https://github.com/ChristophEnglisch/keycloak-model-context-protocol) — Keycloak user and realm management ☆`41`
- [descope-sample-apps/descope-mcp-server-stdio](https://github.com/descope-sample-apps/descope-mcp-server-stdio) — Descope user management and audits ☆`29`
### MCP Security

- [eqtylab/mcp-guardian](https://github.com/eqtylab/mcp-guardian) — Manage / Proxy / Secure your MCP Servers ☆`197`
- [kapilduraphe/mcp-watch](https://github.com/kapilduraphe/mcp-watch) — Security scanner for MCP servers ☆`126`
- [postralai/masquerade](https://github.com/postralai/masquerade) — The Privacy Firewall for LLMs ☆`75`
- [82ch/MCP-Dandan](https://github.com/82ch/MCP-Dandan) — MCP security with real-time proxying ☆`63`
- [AIM-Intelligence/AIM-MCP](https://github.com/AIM-Intelligence/AIM-MCP) — AIM MCP Server :: Guard and Protect your MCPs & AI Chatting ☆`20`
- [cromwellian/hippycampus](https://github.com/cromwellian/hippycampus) — REST endpoint to MCP conversion ☆`20`
- [kontext-security/attestable-mcp-server](https://github.com/kontext-security/attestable-mcp-server) — Hardware attestation for MCP server integrity ☆`18`
### Network & Firewall

- [vespo92/OPNSenseMCP](https://github.com/vespo92/OPNSenseMCP) — MCP Server for OPNSense to act as IaC proxy ☆`45`
- [intruder-io/intruder-mcp](https://github.com/intruder-io/intruder-mcp) — An MCP server to let AI agents control Intruder ☆`24`
### Pentesting & OSINT

- [PortSwigger/mcp-server](https://github.com/PortSwigger/mcp-server) — MCP Server for Burp ☆`676`
- [BurtTheCoder/mcp-maigret](https://github.com/BurtTheCoder/mcp-maigret) — Maigret OSINT user account collection ☆`238`
- [BurtTheCoder/mcp-shodan](https://github.com/BurtTheCoder/mcp-shodan) — MCP server for Shodan - device search, IP recon, CVE intel ☆`122`
- [BurtTheCoder/mcp-virustotal](https://github.com/BurtTheCoder/mcp-virustotal) — VirusTotal API queries ☆`118`
- [roadwy/cve-search_mcp](https://github.com/roadwy/cve-search_mcp) — CVE database security queries ☆`94`
- [mobb-dev/bugsy](https://github.com/mobb-dev/bugsy) — Automatic security vulnerability remediation for your code. ☆`66`
- [GitGuardian/ggmcp](https://github.com/GitGuardian/ggmcp) — Scan and remediate hardcoded secrets ☆`34`
- [StacklokLabs/osv-mcp](https://github.com/StacklokLabs/osv-mcp) — An MCP server for OSV ☆`31`
- [BurtTheCoder/mcp-dnstwist](https://github.com/BurtTheCoder/mcp-dnstwist) — DNS fuzzing for phishing detection ☆`48`
- [nickpending/mcp-recon](https://github.com/nickpending/mcp-recon) — Tellix conversational recon interface ☆`25`
- [gnlds/mcp-cve-intelligence-server-lite](https://github.com/gnlds/mcp-cve-intelligence-server-lite) — CVE intelligence from NVD, MITRE, GitHub ☆`19`
### Reverse Engineering

- [LaurieWired/GhidraMCP](https://github.com/LaurieWired/GhidraMCP) — MCP Server for Ghidra ☆`8,408`
- [mrexodia/ida-pro-mcp](https://github.com/mrexodia/ida-pro-mcp) — IDA Pro reverse engineering with AI ☆`7,487`
- [zinja-coder/jadx-ai-mcp](https://github.com/zinja-coder/jadx-ai-mcp) — Plugin for JADX to integrate MCP server ☆`1,777`
- [symgraph/GhidrAssistMCP](https://github.com/symgraph/GhidrAssistMCP) — An MCP extension for Ghidra ☆`573`
- [zinja-coder/apktool-mcp-server](https://github.com/zinja-coder/apktool-mcp-server) — APK Tool for Android reverse engineering ☆`361`
- [fosdickio/binary_ninja_mcp](https://github.com/fosdickio/binary_ninja_mcp) — Binary Ninja plugin for LLM integration ☆`314`
- [radareorg/radare2-mcp](https://github.com/radareorg/radare2-mcp) — MCP stdio server for radare2 ☆`205`
- [13bm/GhidraMCP](https://github.com/13bm/GhidraMCP) — Active Socket based MCP Server for Ghidra ☆`105`
- [zboralski/ida-headless-mcp](https://github.com/zboralski/ida-headless-mcp) — Headless IDA Pro binary analysis via Model Context Protocol ☆`102`
- [pullkitsan/mobsf-mcp-server](https://github.com/pullkitsan/mobsf-mcp-server) — MobSF APK and IPA security scanning ☆`18`
### SIEM & SecOps

- [beelzebub-labs/beelzebub](https://github.com/beelzebub-labs/beelzebub) — Low-code honeypot with AI virtualization ☆`1,951`
- [MorDavid/BloodHound-MCP-AI](https://github.com/MorDavid/BloodHound-MCP-AI) — BloodHound integration with AI through MCP ☆`352`
- [gbrigandi/mcp-server-wazuh](https://github.com/gbrigandi/mcp-server-wazuh) — MCP Server for Wazuh SIEM ☆`195`
- [securityfortech/secops-mcp](https://github.com/securityfortech/secops-mcp) — All-in-one security testing toolbox via MCP ☆`192`
- [CrowdStrike/falcon-mcp](https://github.com/CrowdStrike/falcon-mcp) — CrowdStrike Falcon security analysis ☆`137`
- [cycodehq/cycode-cli](https://github.com/cycodehq/cycode-cli) — SAST, SCA, Secrets, IaC security scanning ☆`98`
- [panther-labs/mcp-panther](https://github.com/panther-labs/mcp-panther) — Detections, alerts, and log queries ☆`43`
- [slouchd/cyberchef-api-mcp-server](https://github.com/slouchd/cyberchef-api-mcp-server) — CyberChef API MCP Server ☆`39`
- [qianniuspace/mcp-security-audit](https://github.com/qianniuspace/mcp-security-audit) — MCP server for security auditing ☆`52`
- [Gaffx/volatility-mcp](https://github.com/Gaffx/volatility-mcp) — This repo hosts an MCP server for volatility3.x ☆`45`
- [fr0gger/MCP_Security](https://github.com/fr0gger/MCP_Security) — This is a repository to experiment with MCP for security ☆`47`
- [Contrast-Security-OSS/mcp-contrast](https://github.com/Contrast-Security-OSS/mcp-contrast) — MCP Server for Contrast Security ☆`18`
- [Spathodea-Network/opencti-mcp](https://github.com/Spathodea-Network/opencti-mcp) — OpenCTI threat intelligence platform ☆`38`
## Social Media

- [iFurySt/RedNote-MCP](https://github.com/iFurySt/RedNote-MCP) — MCP server for accessing RedNote(XiaoHongShu, xhs). ☆`1,042`
- [karanb192/reddit-mcp-buddy](https://github.com/karanb192/reddit-mcp-buddy) — Clean Reddit data: posts, search, users ☆`605`
- [adhikasp/mcp-twikit](https://github.com/adhikasp/mcp-twikit) — Twitter interaction via MCP ☆`231`
- [34892002/bilibili-mcp-js](https://github.com/34892002/bilibili-mcp-js) — Bilibili video search MCP service ☆`161`
- [Seym0n/tiktok-mcp](https://github.com/Seym0n/tiktok-mcp) — Model Context Protocol (MCP) with TikTok integration ☆`147`
- [trypeggy/instagram_dm_mcp](https://github.com/trypeggy/instagram_dm_mcp) — Instagram Direct messages MCP ☆`157`
- [HagaiHen/facebook-mcp-server](https://github.com/HagaiHen/facebook-mcp-server) — Facebook posts, comments, insights automation ☆`142`
- [king-of-the-grackles/reddit-research-mcp](https://github.com/king-of-the-grackles/reddit-research-mcp) — Reddit research with structured insights ☆`106`
- [Xquik-dev/x-twitter-scraper](https://github.com/Xquik-dev/x-twitter-scraper) — X API integration with 40+ tools, webhooks & MCP server ☆`46`
- [anwerj/youtube-uploader-mcp](https://github.com/anwerj/youtube-uploader-mcp) — Upload/Schedule videos on Youtube with the help of AI ☆`38`
- [LuniaKunal/mcp-twitter](https://github.com/LuniaKunal/mcp-twitter) — Manage your twitter account using mcp ☆`58`
- [ertiqah/linkedin-mcp-runner](https://github.com/ertiqah/linkedin-mcp-runner) — LinkedIn content analysis and posting ☆`30`
- [jaipandya/producthunt-mcp-server](https://github.com/jaipandya/producthunt-mcp-server) — MCP server for Product Hunt data access ☆`43`
- [AbdelStark/nostr-mcp](https://github.com/AbdelStark/nostr-mcp) — Nostr posting and interaction ☆`37`
- [macrocosm-os/macrocosmos-mcp](https://github.com/macrocosm-os/macrocosmos-mcp) — The MCP for macrocosmos subnets. ☆`28`
- [laulauland/bluesky-context-server](https://github.com/laulauland/bluesky-context-server) — Bluesky MCP server ☆`30`
- [jonathan-politzki/mcp-writer-substack](https://github.com/jonathan-politzki/mcp-writer-substack) — Bridge Substack writings to Claude ☆`28`
- [mbelinky/x-mcp-server](https://github.com/mbelinky/x-mcp-server) — MCP server to post on x.com with OAuth v1 and v2 ☆`20`
## Sports

- [r-huijts/strava-mcp](https://github.com/r-huijts/strava-mcp) — Strava fitness data integration ☆`340`
- [rishijatia/fantasy-pl-mcp](https://github.com/rishijatia/fantasy-pl-mcp) — Fantasy Premier League MCP Server ☆`68`
- [guillochon/mlb-api-mcp](https://github.com/guillochon/mlb-api-mcp) — MCP server for MLB baseball statistics ☆`44`
- [mikechao/balldontlie-mcp](https://github.com/mikechao/balldontlie-mcp) — MCP server for NBA, NFL, MLB sports data ☆`23`
- [yeonupark/mcp-soccer-data](https://github.com/yeonupark/mcp-soccer-data) — Real-time football data ☆`30`
- [lenwood/cfbd-mcp-server](https://github.com/lenwood/cfbd-mcp-server) — An MCP server enabling CFBD API queries within Claude Desktop. ☆`26`
- [tomekkorbak/strava-mcp-server](https://github.com/tomekkorbak/strava-mcp-server) — MCP server for Strava API integration ☆`20`
- [kw510/strava-mcp](https://github.com/kw510/strava-mcp) — MCP server with Strava OAuth on Cloudflare Workers ☆`26`
- [r-huijts/firstcycling-mcp](https://github.com/r-huijts/firstcycling-mcp) — MCP server for professional cycling data from FirstCycling ☆`18`
- [RobSpectre/mvf1](https://github.com/RobSpectre/mvf1) — Python package and CLI for MultiViewer For F1 ☆`18`
## Text-to-Speech

- [mbailey/voicemode](https://github.com/mbailey/voicemode) — Natural (2-way) voice conversations with Claude Code ☆`1,053`
- [mberg/kokoro-tts-mcp](https://github.com/mberg/kokoro-tts-mcp) — Kokoro Text to Speech (TTS) MCP Server ☆`76`
## Translation

- [caol64/wenyan-mcp](https://github.com/caol64/wenyan-mcp) — Markdown formatting and translation to Chinese ☆`1,176`
- [aymericzip/intlayer](https://github.com/aymericzip/intlayer) — MCP server for Intlayer internationalization ☆`684`
- [DeepLcom/deepl-mcp-server](https://github.com/DeepLcom/deepl-mcp-server) — Translation with DeepL API ☆`100`
- [translated/lara-mcp](https://github.com/translated/lara-mcp) — Lara Translate API with language detection ☆`79`
- [mmntm/weblate-mcp](https://github.com/mmntm/weblate-mcp) —  ☆`18`
## Travel & Transport

- [openbnb-org/mcp-server-airbnb](https://github.com/openbnb-org/mcp-server-airbnb) — Search Airbnb using your AI Agent ☆`424`
- [cobanov/teslamate-mcp](https://github.com/cobanov/teslamate-mcp) — MCP server for TeslaMate vehicle data and analytics ☆`126`
- [r-huijts/ns-mcp-server](https://github.com/r-huijts/ns-mcp-server) — MCP server for Dutch Railways (NS) travel information ☆`52`
- [pab1it0/tripadvisor-mcp](https://github.com/pab1it0/tripadvisor-mcp) — MCP server for Tripadvisor location data and reviews ☆`54`
- [sunsetcoder/flightradar24-mcp-server](https://github.com/sunsetcoder/flightradar24-mcp-server) — Model Context Protocol server for Flight Tracking ☆`46`
- [KyrieTangSheng/mcp-server-nationalparks](https://github.com/KyrieTangSheng/mcp-server-nationalparks) — US National Parks info via NPS API ☆`39`
- [Pradumnasaraf/aviationstack-mcp](https://github.com/Pradumnasaraf/aviationstack-mcp) — MCP for AviationStack API - real-time flight data ☆`18`
- [campertunity/mcp-server](https://github.com/campertunity/mcp-server) —  ☆`16`
- [mfukushim/map-traveler-mcp](https://github.com/mfukushim/map-traveler-mcp) — Virtual traveler library for MCP ☆`23`
- [variflight/variflight-mcp](https://github.com/variflight/variflight-mcp) — Variflight services implementation ☆`24`
- [JordanDalton/DoorDash-MCP-Server](https://github.com/JordanDalton/DoorDash-MCP-Server) — MCP server for DoorDash delivery service integration ☆`22`
## Web Scraping

- [ScrapeGraphAI/Scrapegraph-ai](https://github.com/ScrapeGraphAI/Scrapegraph-ai) — Python scraper based on AI ☆`23,311`
- [firecrawl/firecrawl-mcp-server](https://github.com/firecrawl/firecrawl-mcp-server) — Web scraping and search for LLM clients ☆`6,066`
- [brightdata/brightdata-mcp](https://github.com/brightdata/brightdata-mcp) — All-in-one public web access solution ☆`2,298`
- [apify/apify-mcp-server](https://github.com/apify/apify-mcp-server) — MCP server for Apify web scraping and data extraction ☆`1,077`
- [jae-jae/fetcher-mcp](https://github.com/jae-jae/fetcher-mcp) — Playwright web page content fetching ☆`1,022`
- [etsd-tech/mcp-pointer](https://github.com/etsd-tech/mcp-pointer) — DOM element pointing for agents ☆`571`
- [apify/mcp-server-rag-web-browser](https://github.com/apify/mcp-server-rag-web-browser) — A MCP Server for the RAG Web Browser Actor ☆`204`
- [tinyfish-io/agentql-mcp](https://github.com/tinyfish-io/agentql-mcp) — AgentQL data extraction integration ☆`160`
- [just-every/mcp-read-website-fast](https://github.com/just-every/mcp-read-website-fast) — Fast webpage to markdown conversion ☆`144`
- [scrapeless-ai/scrapeless-mcp-server](https://github.com/scrapeless-ai/scrapeless-mcp-server) — Scrapeless Mcp Server ☆`160`
- [pskill9/website-downloader](https://github.com/pskill9/website-downloader) — MCP server to download entire websites ☆`150`
- [just-every/mcp-screenshot-website-fast](https://github.com/just-every/mcp-screenshot-website-fast) — Fast webpage screenshots for LLMs ☆`105`
- [oxylabs/oxylabs-mcp](https://github.com/oxylabs/oxylabs-mcp) — Official Oxylabs MCP integration ☆`94`
- [cyberchitta/scrapling-fetch-mcp](https://github.com/cyberchitta/scrapling-fetch-mcp) — Access bot-protected websites ☆`77`
- [crawlbase/crawlbase-mcp](https://github.com/crawlbase/crawlbase-mcp) — MCP server connecting AI agents with real-time web data ☆`54`
- [djannot/puppeteer-vision-mcp](https://github.com/djannot/puppeteer-vision-mcp) — Web scraping with AI-driven interaction handling ☆`48`
- [supadata-ai/mcp](https://github.com/supadata-ai/mcp) — Video and web scraping for Claude ☆`45`
- [puremd/puremd-mcp](https://github.com/puremd/puremd-mcp) — Unblock, scrape, and search tools for MCP clients ☆`60`
- [ananddtyagi/webpage-screenshot-mcp](https://github.com/ananddtyagi/webpage-screenshot-mcp) — MCP server for webpage screenshot capture ☆`54`
- [webscraping-ai/webscraping-ai-mcp-server](https://github.com/webscraping-ai/webscraping-ai-mcp-server) — MCP server for AI-powered web scraping ☆`41`
- [pragmar/mcp-server-webcrawl](https://github.com/pragmar/mcp-server-webcrawl) — Web crawler data and archives connection ☆`38`
- [Decodo/mcp-web-scraper](https://github.com/Decodo/mcp-web-scraper) — Decodo web scraping for MCP clients ☆`23`
- [levz0r/html-to-markdown-mcp](https://github.com/levz0r/html-to-markdown-mcp) — HTML to Markdown converter using Turndown ☆`24`
- [wong2/mcp-jina-reader](https://github.com/wong2/mcp-jina-reader) — Jina Reader MCP Server ☆`47`
- [DevEnterpriseSoftware/scrapi-mcp](https://github.com/DevEnterpriseSoftware/scrapi-mcp) — MCP server for using ScrAPI to scrape web pages. ☆`18`


---

## 🏆 Top 100 by Stars

> The most starred projects in this list, sorted by GitHub stars.

1. [upstash/context7](https://github.com/upstash/context7) — Up-to-date code docs for LLMs ☆`52,822`
1. [mindsdb/mindsdb](https://github.com/mindsdb/mindsdb) — Query Engine for AI Analytics - self-reasoning agents on live data ☆`38,988`
1. [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp) — Chrome DevTools for coding agents ☆`35,330`
1. [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) — Playwright MCP server ☆`30,917`
1. [github/github-mcp-server](https://github.com/github/github-mcp-server) — GitHub's official MCP Server ☆`28,889`
1. [PrefectHQ/fastmcp](https://github.com/PrefectHQ/fastmcp) — Python framework for building MCP servers and clients ☆`24,564`
1. [ScrapeGraphAI/Scrapegraph-ai](https://github.com/ScrapeGraphAI/Scrapegraph-ai) — Python scraper based on AI ☆`23,311`
1. [mastra-ai/mastra](https://github.com/mastra-ai/mastra) — TypeScript AI agent framework with RAG ☆`23,041`
1. [oraios/serena](https://github.com/oraios/serena) — Semantic code retrieval and editing toolkit ☆`23,007`
1. [Skyvern-AI/skyvern](https://github.com/Skyvern-AI/skyvern) — Automate browser based workflows with AI ☆`21,161`
1. [ahujasid/blender-mcp](https://github.com/ahujasid/blender-mcp) — Blender 3D modeling with Claude AI ☆`19,820`
1. [czlonkowski/n8n-mcp](https://github.com/czlonkowski/n8n-mcp) — Build n8n workflows with AI assistants ☆`18,216`
1. [screenpipe/screenpipe](https://github.com/screenpipe/screenpipe) — AI app store with 24/7 desktop history ☆`18,214`
1. [apache/apisix](https://github.com/apache/apisix) — The Cloud-Native API Gateway and AI Gateway ☆`16,453`
1. [googleapis/mcp-toolbox](https://github.com/googleapis/mcp-toolbox) — Open source database MCP toolbox ☆`14,601`
1. [GLips/Figma-Context-MCP](https://github.com/GLips/Figma-Context-MCP) — Figma layout info for AI coding agents ☆`14,374`
1. [trycua/cua](https://github.com/trycua/cua) — MCP server for CUA platform ☆`13,483`
1. [tadata-org/fastapi_mcp](https://github.com/tadata-org/fastapi_mcp) — Expose FastAPI endpoints as MCP tools ☆`11,806`
1. [elie222/inbox-zero](https://github.com/elie222/inbox-zero) — AI email assistant for inbox zero ☆`10,458`
1. [instantdb/instant](https://github.com/instantdb/instant) — Modern Firebase with real-time database ☆`10,106`
1. [vectorize-io/hindsight](https://github.com/vectorize-io/hindsight) — Hindsight: Agent Memory That Learns ☆`9,337`
1. [awslabs/mcp](https://github.com/awslabs/mcp) — AWS MCP servers for AI assistants ☆`8,782`
1. [mark3labs/mcp-go](https://github.com/mark3labs/mcp-go) — Go implementation of MCP ☆`8,591`
1. [LaurieWired/GhidraMCP](https://github.com/LaurieWired/GhidraMCP) — MCP Server for Ghidra ☆`8,408`
1. [lastmile-ai/mcp-agent](https://github.com/lastmile-ai/mcp-agent) — Build agents with MCP and workflow patterns ☆`8,268`
1. [idosal/git-mcp](https://github.com/idosal/git-mcp) — Free remote MCP for any GitHub project ☆`7,925`
1. [Upsonic/Upsonic](https://github.com/Upsonic/Upsonic) — Build autonomous AI agents in Python. ☆`7,825`
1. [mrexodia/ida-pro-mcp](https://github.com/mrexodia/ida-pro-mcp) — IDA Pro reverse engineering with AI ☆`7,487`
1. [grab/cursor-talk-to-figma-mcp](https://github.com/grab/cursor-talk-to-figma-mcp) — Cursor and Figma communication ☆`6,656`
1. [BrowserMCP/mcp](https://github.com/BrowserMCP/mcp) — Browser control for AI applications ☆`6,350`
1. [GreptimeTeam/greptimedb](https://github.com/GreptimeTeam/greptimedb) — Unified observability DB for metrics, logs, traces ☆`6,162`
1. [firecrawl/firecrawl-mcp-server](https://github.com/firecrawl/firecrawl-mcp-server) — Web scraping and search for LLM clients ☆`6,066`
1. [zilliztech/claude-context](https://github.com/zilliztech/claude-context) — Code search for Claude Code agents ☆`5,939`
1. [wonderwhy-er/DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP) — Terminal control, file search, diff editing ☆`5,901`
1. [genkit-ai/genkit](https://github.com/genkit-ai/genkit) — AI app framework for JavaScript and Go ☆`5,793`
1. [lharries/whatsapp-mcp](https://github.com/lharries/whatsapp-mcp) — WhatsApp MCP server ☆`5,510`
1. [executeautomation/mcp-playwright](https://github.com/executeautomation/mcp-playwright) — MCP server for Playwright browser testing ☆`5,436`
1. [superradcompany/microsandbox](https://github.com/superradcompany/microsandbox) — secure, local, cross-platform and programmable sandboxes for AI agents ☆`5,407`
1. [lingodotdev/lingo.dev](https://github.com/lingodotdev/lingo.dev) — MCP server for Lingo localization platform ☆`5,402`
1. [getsentry/XcodeBuildMCP](https://github.com/getsentry/XcodeBuildMCP) — MCP server for Xcode build operations ☆`5,216`
1. [sooperset/mcp-atlassian](https://github.com/sooperset/mcp-atlassian) — MCP server for Atlassian tools (Confluence, Jira) ☆`4,942`
1. [Kiln-AI/Kiln](https://github.com/Kiln-AI/Kiln) — Build AI systems with Evals, RAG, Agents, fine-tuning ☆`4,753`
1. [21st-dev/magic-mcp](https://github.com/21st-dev/magic-mcp) — Frontend development with AI like Magic ☆`4,721`
1. [baserow/baserow](https://github.com/baserow/baserow) — No-code database, apps, agents with AI ☆`4,647`
1. [mobile-next/mobile-mcp](https://github.com/mobile-next/mobile-mcp) — Mobile automation for iOS, Android, emulators ☆`4,553`
1. [exa-labs/exa-mcp-server](https://github.com/exa-labs/exa-mcp-server) — Exa MCP for web search and web crawling! ☆`4,251`
1. [makenotion/notion-mcp-server](https://github.com/makenotion/notion-mcp-server) — Official Notion MCP Server ☆`4,219`
1. [antvis/mcp-server-chart](https://github.com/antvis/mcp-server-chart) — 25+ visual charts using @antvis for data analysis ☆`3,966`
1. [dagger/container-use](https://github.com/dagger/container-use) — MCP server for container orchestration ☆`3,725`
1. [haris-musa/excel-mcp-server](https://github.com/haris-musa/excel-mcp-server) — Excel file manipulation ☆`3,699`
1. [cloudflare/mcp-server-cloudflare](https://github.com/cloudflare/mcp-server-cloudflare) — Cloudflare services management ☆`3,612`
1. [archestra-ai/archestra](https://github.com/archestra-ai/archestra) — Enterprise AI Platform with guardrails, MCP registry, gateway & orchestrator ☆`3,564`
1. [MarkusPfundstein/mcp-obsidian](https://github.com/MarkusPfundstein/mcp-obsidian) — Obsidian integration via REST API plugin ☆`3,376`
1. [browserbase/mcp-server-browserbase](https://github.com/browserbase/mcp-server-browserbase) — Browser control with Browserbase ☆`3,258`
1. [metorial/metorial](https://github.com/metorial/metorial) — Connect any AI model to 600+ integrations; powered by MCP ☆`3,248`
1. [steipete/Peekaboo](https://github.com/steipete/Peekaboo) — macOS screenshot and window capture MCP server ☆`3,124`
1. [Coding-Solo/godot-mcp](https://github.com/Coding-Solo/godot-mcp) — MCP server for Godot game engine ☆`3,082`
1. [CodeGraphContext/CodeGraphContext](https://github.com/CodeGraphContext/CodeGraphContext) — Code graph indexing for AI context ☆`2,970`
1. [basicmachines-co/basic-memory](https://github.com/basicmachines-co/basic-memory) — AI conversations that remember context ☆`2,870`
1. [grafana/mcp-grafana](https://github.com/grafana/mcp-grafana) — MCP server for Grafana ☆`2,824`
1. [Jpisnice/shadcn-ui-mcp-server](https://github.com/Jpisnice/shadcn-ui-mcp-server) — MCP server for shadcn/ui component library ☆`2,746`
1. [supabase-community/supabase-mcp](https://github.com/supabase-community/supabase-mcp) — Connect Supabase to your AI assistants ☆`2,612`
1. [zcaceres/markdownify-mcp](https://github.com/zcaceres/markdownify-mcp) — Convert almost anything to Markdown ☆`2,590`
1. [bytebase/dbhub](https://github.com/bytebase/dbhub) — Token-efficient multi-database MCP ☆`2,580`
1. [crystaldba/postgres-mcp](https://github.com/crystaldba/postgres-mcp) — Postgres with read/write access and performance ☆`2,542`
1. [blazickjp/arxiv-mcp-server](https://github.com/blazickjp/arxiv-mcp-server) — arXiv paper search and analysis ☆`2,539`
1. [sparfenyuk/mcp-proxy](https://github.com/sparfenyuk/mcp-proxy) — A bridge between Streamable HTTP and stdio MCP transports ☆`2,426`
1. [brightdata/brightdata-mcp](https://github.com/brightdata/brightdata-mcp) — All-in-one public web access solution ☆`2,298`
1. [metatool-ai/metamcp](https://github.com/metatool-ai/metamcp) — MCP Aggregator, Orchestrator, Middleware, Gateway in one docker ☆`2,216`
1. [jamubc/gemini-mcp-tool](https://github.com/jamubc/gemini-mcp-tool) — MCP server for Gemini CLI with large file analysis ☆`2,163`
1. [IvanMurzak/Unity-MCP](https://github.com/IvanMurzak/Unity-MCP) — AI-powered bridge connecting LLMs to Unity Editor ☆`2,158`
1. [taylorwilsdon/google_workspace_mcp](https://github.com/taylorwilsdon/google_workspace_mcp) — MCP server for Google Workspace integration ☆`2,123`
1. [perplexityai/modelcontextprotocol](https://github.com/perplexityai/modelcontextprotocol) — Official Perplexity API MCP server ☆`2,089`
1. [cjo4m06/mcp-shrimp-task-manager](https://github.com/cjo4m06/mcp-shrimp-task-manager) — Task manager with chain-of-thought and reflection ☆`2,082`
1. [chatmcp/mcpso](https://github.com/chatmcp/mcpso) — directory for Awesome MCP Servers ☆`1,993`
1. [financial-datasets/mcp-server](https://github.com/financial-datasets/mcp-server) — Financial Datasets stock market API ☆`1,961`
1. [beelzebub-labs/beelzebub](https://github.com/beelzebub-labs/beelzebub) — Low-code honeypot with AI virtualization ☆`1,951`
1. [IBM/mcp-cli](https://github.com/IBM/mcp-cli) — Feature-rich CLI for interacting with MCP servers ☆`1,945`
1. [nottelabs/notte](https://github.com/nottelabs/notte) — Framework to build web agents ☆`1,932`
1. [joshuayoes/ios-simulator-mcp](https://github.com/joshuayoes/ios-simulator-mcp) — MCP server for interacting with the iOS simulator ☆`1,874`
1. [zinja-coder/jadx-ai-mcp](https://github.com/zinja-coder/jadx-ai-mcp) — Plugin for JADX to integrate MCP server ☆`1,777`
1. [tavily-ai/tavily-mcp](https://github.com/tavily-ai/tavily-mcp) — Real-time search, extract, map and crawl ☆`1,763`
1. [ravitemer/mcphub.nvim](https://github.com/ravitemer/mcphub.nvim) — MCP client for Neovim with intuitive server management ☆`1,760`
1. [stacklok/toolhive](https://github.com/stacklok/toolhive) — Runtime and gateway for deploying MCP servers in containers ☆`1,716`
1. [julien040/anyquery](https://github.com/julien040/anyquery) — SQL queries for GitHub, Notion, +40 more ☆`1,664`
1. [ezyang/codemcp](https://github.com/ezyang/codemcp) — Coding assistant MCP for Claude Desktop ☆`1,615`
1. [leonardsellem/n8n-mcp-server](https://github.com/leonardsellem/n8n-mcp-server) — Tools for interacting with n8n API ☆`1,601`
1. [CoderGamester/mcp-unity](https://github.com/CoderGamester/mcp-unity) — MCP server for Unity game engine integration ☆`1,594`
1. [microsoft/azure-devops-mcp](https://github.com/microsoft/azure-devops-mcp) — Azure DevOps integration for AI agents ☆`1,571`
1. [MicrosoftDocs/mcp](https://github.com/MicrosoftDocs/mcp) — Microsoft Learn MCP for LLMs ☆`1,553`
1. [benborla/mcp-server-mysql](https://github.com/benborla/mcp-server-mysql) — MCP server for MySQL database operations ☆`1,541`
1. [korotovsky/slack-mcp-server](https://github.com/korotovsky/slack-mcp-server) — MCP server for Slack workspace integration ☆`1,535`
1. [anaisbetts/mcp-installer](https://github.com/anaisbetts/mcp-installer) — An MCP server that installs other MCP servers for you ☆`1,519`
1. [isaacphi/mcp-language-server](https://github.com/isaacphi/mcp-language-server) — MCP server implementing Language Server Protocol ☆`1,511`
1. [stripe/ai](https://github.com/stripe/ai) — One-stop shop for building AI-powered products and businesses with Stripe. ☆`1,472`
1. [containers/kubernetes-mcp-server](https://github.com/containers/kubernetes-mcp-server) — Kubernetes and OpenShift management ☆`1,445`
1. [Flux159/mcp-server-kubernetes](https://github.com/Flux159/mcp-server-kubernetes) — MCP Server for kubernetes management commands ☆`1,377`
1. [mattt/iMCP](https://github.com/mattt/iMCP) — Access Messages, Contacts, Reminders on Mac ☆`1,371`
1. [damms005/devdb-vscode](https://github.com/damms005/devdb-vscode) — Zero-config VS Code database extension ☆`1,363`
1. [qdrant/mcp-server-qdrant](https://github.com/qdrant/mcp-server-qdrant) — Official Qdrant vector database MCP ☆`1,345`

## Contributing

Please see [CONTRIBUTING](.github/CONTRIBUTING.md) for details.

## Feedback

Found something wrong? Open an issue or submit a pull request — contributions are welcome!

## Credits

- [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers)
- [punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers)
- [appcypher/awesome-mcp-servers](https://github.com/appcypher/awesome-mcp-servers)
- [wong2/awesome-mcp-servers](https://github.com/wong2/awesome-mcp-servers)
- [All Contributors](https://github.com/abordage/awesome-mcp/graphs/contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE) for more information.
