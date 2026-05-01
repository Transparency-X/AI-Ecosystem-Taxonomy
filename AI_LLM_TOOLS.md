# AI & LLM Tools

## Table 1: Productivity & Workspace AI – Enhanced with Decision Criteria

| Tool | Integration Depth | Privacy/Trust Level | Ease of Use (1–5) | Cost (USD) | Best For | Future Viability |
|------|------------------|---------------------|-------------------|------------|----------|------------------|
| **Microsoft 365 Copilot** | Native (Word, Excel, Teams, Outlook) | Enterprise-grade, data stays in tenant | 4 | $30/user/mo | Large orgs, compliance-heavy docs | High – MSFT ecosystem lock-in |
| **Google Workspace AI** | Native (Docs, Gmail, Sheets, Meet) | Google Cloud, standard enterprise | 4 | $20–30/user/mo (+ Business+) | Collaborative teams, email-heavy | High – Gemini improvements |
| **Notion AI** | Native (Notion workspace) | Cloud, SOC2 | 5 | $10/user/mo add-on | Knowledge management, wikis | Medium – niche but sticky |
| **Apple Intelligence** | Native (iOS/macOS apps) | On-device (excellent) | 5 | Free (hardware-limited) | Privacy-first users, photo editing | High – will expand to more apps |
| **Grammarly GO** | Browser extension, desktop, Word | Cloud, opt-out data retention | 5 | $12–15/mo | Professional writing, marketing | Medium – faces Copilot/Gemini competition |

---

## Table 2: Local / Privacy-First AI – Updated with Hardware & Use Case Clarity

| Tool | Local RAG? | GPU Required | Setup Difficulty (1–5) | TCO (first year) | Best For |
|------|------------|--------------|------------------------|------------------|----------|
| **AnythingLLM** | Yes (vector DB) | Optional (CPU works) | 2 | $0 (open source) + hardware | Air-gapped knowledge bases, non-technical local RAG |
| **ChatRTX** | Yes (TensorRT-LLM) | NVIDIA RTX 30+ (8GB VRAM) | 3 | $0 + $300+ GPU | Gamers/developers with existing RTX |
| **Ollama** | No (model runner only) | Optional (CPU/GPU) | 1 (CLI) | $0 + hardware | Developers testing models locally |
| **LM Studio** | No | Optional | 1 (GUI) | $0 + hardware | Non-tech users wanting chat with local models |
| **LocalAI** (added) | Yes (custom) | CPU/GPU | 3 | $0 | Drop-in OpenAI API replacement locally |

**Gap identified:** No tool offers *hybrid* (local model + cloud RAG index) – highlighted for future development.

---

## Table 3: Legal AI – Segmented by Firm Size & Feature Depth

| Tool | Target Firm Size | Key Feature | Westlaw/Lexis Integration | Word Native? | Pricing Model |
|------|------------------|-------------|---------------------------|--------------|---------------|
| **Harvey AI** | AmLaw 200, Magic Circle | Due diligence, deposition support | No (proprietary) | Yes | Enterprise (opaque, >$300M funded) |
| **Spellbook** | Small-to-mid firms | AI redlining, playbook enforcement | No | Yes | Custom per-seat annual |
| **Casetext CoCounsel** | Mid-to-large | Legal research, doc review | Yes (Westlaw) | Limited | Subscription tiers |
| **Lexis+ AI** | All sizes | Research, drafting | Yes (Lexis) | Yes | Published tier pricing |
| **Ivo** | Small-to-mid | Contract review, clause libraries | No | Yes | Demo required |

**Gap:** No affordable solution for solo practitioners (<$50/mo) – market opportunity.

---

## Table 4: Automation & Orchestration – AI Feature Comparison

| Tool | AI Step Types | Multi-Modal? | Self-Hostable | Free Tier Limits | Best For |
|------|---------------|--------------|---------------|------------------|----------|
| **Zapier AI** | Classification, extraction, summarisation, generation | No | No | 100 tasks/mo | Non-technical business automation |
| **Make** | Same plus branching logic | No | No | 1,000 ops/mo | Visual complex workflows |
| **n8n** | All above + custom AI nodes | No | Yes (fair-code) | Unlimited (self-host) | Privacy-conscious, technical teams |
| **Pipedream AI** (added) | Code-first AI steps | No | No | 10,000 invocations/mo | Developers needing serverless AI |

**Future trend:** Agentic workflows (human-in-the-loop) expected in all by Q4 2026.

---

## Table 5: AI-Native IDEs & Coding Assistants – Enhanced with Benchmark-Ready Metrics

| Tool | Agentic Multi-File Edits? | Context Window (approx) | Local Model Support? | Price (Pro) | Open Source? |
|------|----------------------------|--------------------------|----------------------|-------------|--------------|
| **Cursor** | Yes (Agent Mode) | 200k tokens (Claude) + codebase | No (cloud models only) | $20/mo | No (VS Code fork) |
| **Windsurf** | Yes (Cascade) | 128k | No | $15/mo | No |
| **GitHub Copilot** | Limited (Workspace preview) | 8k-128k depending on model | No | $10/mo | No |
| **Codeium** | No | 128k | No (proprietary) | $12/mo | No |
| **Continue.dev** | No (plugins only) | Model-dependent | Yes (Ollama, etc.) | $0 | Yes (MIT) |
| **Aider** | Yes (architect mode) | Model-dependent | Yes (any OpenAI-compatible) | API costs only | Yes (GPL) |
| **Devin** | Yes (full autonomous) | Unknown | No | Enterprise (waitlist) | No |

**Benchmark note:** See Table 9 for a proposed test harness.

---

## Table 6: Multi-Agent & Specialized Platforms – Maturity Assessment

| Tool | Production-Ready? | Sandboxing | Tool Use | Best Use Case | Risk Level |
|------|------------------|------------|----------|---------------|------------|
| **OpenHands** | No (beta) | Docker-based | Yes (configurable) | Research, prototypes | Medium (can delete files) |
| **Kimi Swarm** | No (research) | Unknown | Limited | Benchmarking swarms | High (unstable) |
| **Warp Oz** | Beta | Terminal sandbox | Yes (commands) | DevOps workflows | Low (human approval) |
| **Devin** | Limited access | Proprietary | Yes (full) | Enterprise POCs | Medium (costly mistakes) |

**Conclusion:** Do not use for production until at least Q1 2027.

---

## Table 7: NEW – Decision Matrix with Weighted Scoring (Sample)

*For a hypothetical “privacy-conscious legal researcher with $200/mo budget”:*

| Tool | Privacy (30%) | Legal Fit (30%) | Cost (20%) | Ease (10%) | Integration (10%) | **Weighted Score** |
|------|---------------|----------------|------------|------------|-------------------|--------------------|
| Spellbook | 60 | 90 | 70 | 80 | 90 (Word) | **76** |
| Lexis+ AI | 50 | 95 | 60 | 70 | 85 | **71** |
| AnythingLLM (local) | 100 | 40 | 100 | 60 | 30 | **68** |
| Casetext CoCounsel | 50 | 95 | 50 | 70 | 70 | **65** |

*Full interactive version recommended as a web tool.*

---

## Table 8: NEW – Persona-to-Tool Chain Workflows

| Persona | Workflow Description | Tool Chain |
|---------|----------------------|-------------|
| Privacy‑conscious PhD student | Lit review, summarising PDFs, annotating notes | Zotero → AnythingLLM (local, Llama 3) → Obsidian with Smart Connections |
| Solo legal practitioner (low budget) | Contract redlining, client Q&A | Word + Spellbook (trial) → Docusign → LocalAI (for client document Q&A) |
| Mid-size enterprise legal team | Due diligence, regulatory compliance | SharePoint + MSFT Copilot → Harvey (for high-risk docs) → Lexis+ AI for research |
| Indie developer ( solo ) | Build & deploy a web app | Cursor Agent (for scaffolding) → GitHub Copilot Free (for inline) → Warp Oz (terminal) → n8n (self-host for CI) |
| Data science team (regulated) | Local model training + documentation | Ollama for experiments → Continue.dev + local LLM in VSCode → MkDocs + Grammarly GO |

---

## Table 9: NEW – Total Cost of Ownership (TCO) Comparison (12 months, 1 user)

| Tool | Subscription | API Costs | Hardware (amortised) | Training Time (hrs @ $50) | **Total TCO** | Break-even vs Cloud |
|------|--------------|-----------|----------------------|----------------------------|---------------|---------------------|
| **Cursor Pro** | $240 | $0 (unless API key) | $0 (cloud) | 2 ($100) | $340 | N/A |
| **Ollama + Continue.dev** | $0 | $0 (local) | $300 (GPU upgrade) | 8 ($400) | $700 | After 8 months (vs $90/mo cloud API) |
| **GitHub Copilot + Claude API** | $120 | $600 (10M tokens/mo @ $15/1M) | $0 | 1 ($50) | $770 | N/A |
| **Spellbook** | $1,200 (est.) | $0 | $0 | 4 ($200) | $1,400 | Cheaper than hiring junior paralegal |

**Note:** Local solutions become cheaper if you already own the GPU.

---

## Table 10: NEW – Future Roadmap (12–18 months) for Key Categories

| Category | Expected Shift | Tools to Watch | Impact |
|----------|----------------|----------------|--------|
| **On-device LLMs** | 100B+ models on Apple A19/M5, Qualcomm Snapdragon 9 | Apple Intelligence Gen 2, local Llama 4 | Kills cloud assistants for many daily tasks |
| **Agentic workflows** | Human-in-the-loop becomes default in Zapier, Make, n8n | Microsoft Copilot Studio, Google Vertex AI Agent | Low-code agents replace RPA |
| **Legal AI commoditisation** | Solo practitioner tier (<$50/mo) | Spellbook Solo, new entrants (e.g., Robin AI) | Opens market outside AmLaw |
| **Open-source agent safety** | Sandboxing standards emerge | OpenHands + Open Interpreter | Enterprises adopt open agents |
| **Unified local+cloud hybrid** | First product to market | Unknown (Apple? MSFT?) | Bridges privacy & power |

---

## Table 11: NEW – Benchmark Harness for Coding Assistants (Proposed Metrics)

| Metric | Description | Ideal Target | How to Measure |
|--------|-------------|--------------|----------------|
| **Task success rate** | % of coding tasks (refactor, debug, unit test) completed without human correction | >85% | Run 20 standard tasks, count failures |
| **Latency to first suggestion** | Time from cursor placement to inline completion | <300ms | Automated UI test |
| **Code correctness** | Pass rate of generated unit tests | >90% | Run pytest on generated code |
| **Edit distance** | Levenshtein ratio vs optimal solution | >0.8 | Compare to gold-standard refactor |
| **Hallucination rate** | % of suggestions that introduce new bugs | <5% | Static analysis before/after |

**Implementation plan:** Open-source a Docker container with 50 representative tasks (Python/JS). Users can run against Cursor, Windsurf, Copilot, Continue, Aider.

---

## Summary of Updates Made

| Original Table | Updates / New Columns | New Tables Added |
|----------------|----------------------|------------------|
| Productivity & Workspace AI | Added Integration Depth, Privacy, Ease of Use, Future Viability | – |
| Local / Privacy-First | Added RAG flag, Setup Difficulty, TCO | – |
| Legal AI | Added Firm Size, Westlaw integration, Word native | – |
| Automation | Added AI Step Types, Multi-modal, Self-hostable | – |
| AI-Native IDEs | Added Agentic flag, Context window, Local model support | – |
| Multi-Agent | Added Production-ready, Sandboxing, Risk Level | – |
| – | – | Decision Matrix (Table 7) |
| – | – | Persona Workflows (Table 8) |
| – | – | TCO Comparison (Table 9) |
| – | – | Future Roadmap (Table 10) |
| – | – | Benchmark Harness (Table 11) |

These tables are now **actionable** for procurement, technical evaluation, and strategic planning.
