# 🗺️ The AI & Agent Ecosystem Taxonomy 

> A research project by **[Transparency X]**  
> *"💡 Driving open-source initiatives for accountability, security, and civic empowerment."*

## 📖 About This Project
The AI landscape has evolved rapidly from simple chatbots to autonomous cloud swarms capable of massive parallel execution. As these tools integrate deeper into our workflows—both in software development and non-technical fields—the need for clear categorization, security auditing, and transparent accountability is critical.

This repository serves as a **living research hub** mapping the AI/LLM tool ecosystem. We evaluate these tools not just on their capabilities, but on their **data privacy, vendor lock-in, and societal impact**.

```
AI-Ecosystem-Taxonomy/
├── README.md                      # Project overview, taxonomy summary, and getting started
├── CONTRIBUTING.md                # Guidelines for community contributions
├── LICENSE                        # Open-source license (e.g., MIT or Apache 2.0)
├── 📁 docs/                       # Core research and methodology documentation
│   ├── taxonomy-methodology.md    # Detailed explanation of the 5-Level AI Taxonomy
│   ├── accountability-metrics.md  # How we measure data privacy, bias, and security
│   └── Glossary.md                # Definitions (RAG, Swarms, ReAct, etc.)
├── 📁 use-cases/                  # Deep dives into specific applications
│   ├── 📁 developer/              # Developer & Engineering use cases
│   │   ├── L1-general-llms.md
│   │   ├── L3-local-agents.md
│   │   └── L5-cloud-swarms.md
│   └── 📁 non-developer/          # Business, Civic, Legal & Creative use cases
│       ├── L1-conversational.md   # Copywriting, translations, policy drafting
│       ├── L3-local-analysis.md   # Local financial analysis, private legal doc QA
│       └── L5-autonomous-civic.md # Large-scale policy auditing, automated journalism swarms
├── 📁 security-and-audits/        # Transparency X's core accountability work
│   ├── data-telemetry-reports/    # Investigations into what data tools like Cursor or Warp phone home
│   ├── cloud-agent-security.md    # Risks of autonomous cloud agents executing malicious code
│   └── vendor-lock-in-analysis.md # Open-source vs. closed-source tool comparisons
├── 📁 roadmaps/                   # Project planning
│   ├── 2026-project-plan.md       # Milestones and upcoming research phases
│   └── call-for-research.md       # Open bounties/requests for community research
└── 📁 scripts/                    # Utility scripts for researchers
    └── api_terms_monitor.py       # Script to track changes in vendor ToS and Data Privacy pages
```

## 📊 The 5-Level Taxonomy (Dev & Non-Dev)

We classify AI tools based on their level of autonomy, context awareness, and execution capability. 

| Level | Category | Developer Use Case | Non-Developer / Civic Use Case | Transparency X Focus |
| :--- | :--- | :--- | :--- | :--- |
| **1** | **General LLMs** | System architecture, standalone scripts (ChatGPT, Claude) | Brainstorming, policy drafting, translation (Jasper, Gemini) | Prompt injection risks, training data bias. |
| **2** | **Inline Assistants** | Autocompleting code, generating unit tests (Copilot) | Inline writing suggestions, email drafting (Grammarly GO, Notion AI) | PII leakage in text autocomplete. |
| **3** | **Local Agents** | Multi-file codebase refactoring (Cursor, Windsurf) | Local data analysis on sensitive Excel/PDF files (ChatRTX) | Telemetry tracking, local file indexing privacy. |
| **4** | **Gatekeeper Bots** | Automated PR review & security audits (Sweep.dev) | Automated legal contract review, compliance checking | False positives/negatives in compliance audits. |
| **5** | **Cloud Swarms** | Asynchronous bug fixing, massive parallel audits (Warp Oz, Kimi Swarm) | Massive public policy sentiment analysis, automated OSINT swarms | Financial runway risks, autonomous malicious execution. |

## 🚀 Future Project Plan (Roadmap)

Our research is divided into three key phases under the Transparency X initiative:

### Phase 1: Mapping & Categorization (Current)
- Complete the 5-Level taxonomy documentation.
- Compile an exhaustive list of active tools across both Developer and Non-Developer sectors.
- Establish standardized terminology for agentic workflows (ReAct, Swarms, RAG).

### Phase 2: Security & Accountability Audits 
- **Telemetry Investigations:** Do tools like Cursor, Warp, or Copilot send proprietary local data back to vendor servers? We will packet-sniff and audit their data trails.
- **Bias & Output Audits:** Testing gatekeeper bots (Level 4) to see if they introduce or ignore critical vulnerabilities.
- **Open-Source Alternatives:** Highlighting and championing open-source alternatives (like OpenHands) over proprietary black-box systems.

### Phase 3: Civic Empowerment & Non-Dev Adoption
- Publish guides on how NGOs and civic journalists can leverage Level 5 Swarm technology for OSINT (Open Source Intelligence) and massive public data audits.
- Provide frameworks for secure, local-only AI deployments (Level 3) for legal and healthcare professionals dealing with highly sensitive citizen data.

## 🤝 Getting Involved
Transparency X relies on community collaboration. Whether you are a software engineer, a security researcher, a legal expert, or an open-source advocate, we need your help!

- **Submit a Tool:** Open a Pull Request to add a new AI tool to our taxonomy tables.
- **Audit a Service:** Read our `accountability-metrics.md` and submit a security report on an AI agent you use.
- **Join the Discussion:** Head over to the Issues tab to join our ongoing debates on AI accountability.

## ⚖️ License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
