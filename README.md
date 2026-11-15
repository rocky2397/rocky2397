### Hi, I'm Rocky!

**Applied AI engineer in Berlin.** I build LLM agents and RAG systems, and I measure whether they actually work.

Currently **Forward Deployed Engineer at [fonio](https://fonio.ai)**, shipping production voice agents for business customers: n8n/webhook tool integrations, prompt and guardrail design, and end-to-end regression tests that place real phone calls against the deployed models.

---

### Featured projects

| Project | What it does | Highlights |
|---|---|---|
| **[lab2startup](https://github.com/rocky2397/lab2startup)** | Agentic VC sourcing: finds academic AI researchers likely to found startups before they announce anything | LangGraph agents with tiered depth · golden-set eval: 24 researchers, precision and recall 1.0, $0.64 · audit trail per run · product side: built around a fund's monthly sourcing pass, with a next step per candidate (take meeting, monitor, ignore), diffs between runs, a desktop app, and the fund's thesis swappable in a config file without code changes |
| **[prentice](https://github.com/rocky2397/prentice)** | Records a desktop workflow (screen + input events) and turns it into a Claude Code `SKILL.md` that can replay it | Five-stage multimodal pipeline (CLIP, local VLM) · documented trade-offs and limits · product side: private by design (explicit start/stop, models run on-device) and output built to be trusted: it refuses to guess a command and flags uncertain steps for review instead of dropping them |
| **[NormChat](https://github.com/rocky2397/NormChat)** | RAG chat over building-code PDFs (DIN, Eurocode, ÖNORM) with cited passages and in-PDF highlighting | Hybrid search with reranking · per-stage retrieval eval · CI, Docker · product side: evaluated on real questions from a practising structural engineer, each cited source opens the PDF at the highlighted passage, and users bring their own licensed norms |
| **[Forkcast](https://github.com/rocky2397/forkcast)** | Food-inventory PWA: suggests what to cook from what's in your kitchen, learns your taste, and steers toward your daily macros | Blind evals, double-marked by two models and a human: cookable recipes 65% → 92%, usable swaps 33% → 95% · taste ranking replayed on 2,710 real users: 55 → 61 (50 = chance) · Claude vision intake · 214 tests, CI · product side: 31 documented product decisions, onboarding that explains itself, WCAG AA accessibility checks, demo GIF |
| **[claude-automation](https://github.com/rocky2397/claude-automation)** | Reusable GitHub Actions that let Claude prioritize a project board, implement tickets, and open PRs | Agent orchestration in CI · nightly report flags "silent failures" (green jobs that did nothing) · product side: a tester feedback form whose free text becomes ready-to-work tickets, a human merge gate on every PR, and an install checklist for adopting it in any repo |

### What I care about

- **Evals before claims.** Golden sets, LLM judges, and honest "what this does *not* measure" sections.
- **Harness engineering.** The loop, tools, guardrails, and feedback around the model decide whether an agent works in production.
- **Shipping.** Deployed, documented, and reproducible, not just a notebook.

### Background

- 🎓 **MSc Artificial Intelligence**, Maastricht University (NLP, generative AI, computational statistics). Thesis: LoRA/QLoRA fine-tuning and quantization of LLMs for bid-proposal generation, including a human-evaluation app used by 50+ raters
- 🔬 **DFKI** (German Research Center for AI), Information Retrieval group: entity extraction and linking from technical reports to Wikidata
- 🛰️ **European Space Agency**: RAG chatbots over space-economy news and regulations, used by 100+ people
- 📈 Quant research: systematic index-futures strategies and backtesting frameworks

### Stack

`Python` · `TypeScript` · `LangGraph` · `LangChain` · `FastAPI` · `React` · `ChromaDB` · `PyTorch` · `Hugging Face` · `Claude / OpenAI APIs` · `MCP` · `n8n` · `Docker` · `Databricks` · `AWS` · `GitHub Actions`

### Contact

[LinkedIn](https://www.linkedin.com/in/rocky-auer) · open to **Applied AI / AI Engineer** roles in EMEA or remote.
