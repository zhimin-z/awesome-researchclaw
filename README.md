# Awesome ResearchClaw [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> 🦞 A curated list of ResearchClaw ecosystem projects, tools, integrations, and resources for AI-powered academic research.

ResearchClaw is an emerging ecosystem of AI-powered research assistants, autonomous paper-writing pipelines, and scientific workflow tools. This list covers the core projects, extensions, related tools, and learning resources.

[中文](README_zh.md)

## Contents

- [Core Projects](#core-projects)
- [Autonomous Research Pipelines](#autonomous-research-pipelines)
- [Research Assistants & Workflow Tools](#research-assistants--workflow-tools)
- [OpenClaw Ecosystem](#openclaw-ecosystem)
- [Skills & Plugins](#skills--plugins)
- [Channels & Integrations](#channels--integrations)
- [Literature Search & Discovery](#literature-search--discovery)
- [Citation & Reference Management](#citation--reference-management)
- [Experiment Tracking & Reproducibility](#experiment-tracking--reproducibility)
- [LaTeX & Writing Tools](#latex--writing-tools)
- [Data Sources & APIs](#data-sources--apis)
- [Community & Learning](#community--learning)
- [Related Awesome Lists](#related-awesome-lists)

---

## Core Projects

The foundational projects in the ResearchClaw ecosystem.

- [ResearchClaw](https://github.com/ymx10086/ResearchClaw) — Local-first Research OS: paper management, literature search, experiment tracking, multi-agent collaboration, Overleaf sync, and multi-channel access (CLI / Web UI / Telegram / Feishu / QQ / DingTalk).
- [AutoResearchClaw](https://github.com/aiming-lab/AutoResearchClaw) — Fully autonomous 23-stage research pipeline. Chat an idea, get a conference-ready paper with real citations, sandbox experiments, and multi-agent peer review. ⭐ 9.6k+
- [Research Claw (nanoAgentTeam)](https://github.com/nanoAgentTeam/research-claw) — Self-hosted AI research assistant with Overleaf sync, multi-agent collaboration, literature search, and multi-channel (Telegram, Feishu, QQ, DingTalk) support.

## Autonomous Research Pipelines

End-to-end systems that automate the research process from idea to paper.

- [AutoResearchClaw](https://github.com/aiming-lab/AutoResearchClaw) — 23-stage pipeline: idea → literature survey → hypothesis → experiments → paper → peer review. Supports OpenClaw, Claude Code, ACP agents.
- [AI Scientist](https://github.com/SakanaAI/AI-Scientist) — Sakana AI's automated research pioneer; full-cycle scientific discovery agent.
- [AutoResearch](https://github.com/karpathy/autoresearch) — Andrej Karpathy's end-to-end research automation framework.
- [FARS](https://analemma.ai/blog/introducing-fars/) — Fully Automated Research System by Analemma.
- [Auto-claude-code-research-in-sleep (ARIS)](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep) — Lightweight Markdown-only skills for autonomous ML research: cross-model review loops, idea discovery, experiment automation.
- [Scientify](https://github.com/tsingyuai/scientify) — OpenClaw-native research automation plugin with 6-phase pipeline: literature survey → deep analysis → implementation plan → code generation → automated review → experiments.
- [ScienceClaw](https://github.com/Zaoqu-Liu/ScienceClaw) — OpenClaw-based AI research team / scientific workflow assistant.

## Research Assistants & Workflow Tools

Interactive assistants and tools that help researchers throughout their workflow.

- [ResearchClaw](https://github.com/ymx10086/ResearchClaw) — Full research OS with claim/evidence graph, experiment tracking, workflow stages, and project dashboards.
- [Elicit](https://elicit.com/) — AI research assistant; automates literature reviews, systematic reviews, data extraction.
- [Consensus](https://consensus.app/) — AI search engine that finds insights directly from research papers.
- [Jenni AI](https://jenni.ai/) — AI academic writing assistant with in-text citations, PDF analysis, and 2,600+ citation styles.
- [ResearchRabbit](https://www.researchrabbit.ai/) — "Spotify for research" — collection-based paper discovery with AI recommendations.
- [Scite AI](https://scite.ai/) — Smart Citation analysis: see how papers have been cited (supporting, contrasting, mentioning).
- [Perplexity AI](https://www.perplexity.ai/) — AI-powered search engine with source-backed answers; useful for initial research exploration.

## OpenClaw Ecosystem

Projects and tools in the broader OpenClaw ecosystem that complement ResearchClaw.

- [OpenClaw](https://github.com/openclaw/openclaw) — The AI gateway / personal assistant platform that ResearchClaw integrates with.
- [Awesome Claws](https://github.com/LHL3341/awesome-claws) — Curated list of OpenClaw-related products, skills, communities, and ecosystem resources.
- [MetaClaw](https://pypi.org/project/metaclaw/) — Self-learning skill system; AutoResearchClaw uses it to learn from past runs and improve future pipeline quality.
- [ACPX](https://github.com/openclaw/acpx) — Agent Client Protocol — enables AutoResearchClaw to use any ACP-compatible agent (Claude, Codex, Copilot, Gemini, etc.) as its LLM backend.
- [MimicLaw](https://github.com/memovai/mimiclaw) — Compact assistant project in the Claw ecosystem.
- [EverMemOS](https://github.com/EverMind-AI/EverMemOS) — Long-term memory OS for 24/7 OpenClaw agents; includes OpenClaw plugin and Live2D integration.

## Skills & Plugins

Reusable skills and plugins that extend ResearchClaw capabilities.

### Built-in Skills (ResearchClaw)

- `arxiv` — arXiv paper search and download
- `citation_network` — Citation network exploration and visualization
- `experiment_tracker` — Experiment lifecycle management
- `figure_generator` — Academic figure generation
- `literature_review` — Automated literature review workflow
- `paper_summarizer` — Paper summarization and key insight extraction
- `research_notes` — Structured note-taking (paper notes, idea notes, experiment notes)
- `research_workflows` — Multi-stage research workflow management
- `pdf` / `docx` / `pptx` / `xlsx` — Document format support

### AutoResearchClaw Multi-Agent Subsystems

- **CodeAgent** — Multi-phase code generation for experiments
- **BenchmarkAgent** — Automatic dataset discovery and baseline comparison
- **FigureAgent** — 5-agent pipeline: Planner → CodeGen → Renderer → Critic → Integrator
- **Sentinel Watchdog** — Background quality monitor: NaN/Inf detection, citation scoring, anti-fabrication

## Channels & Integrations

Connect ResearchClaw to messaging platforms and collaboration tools.

- [LangBot](https://github.com/langbot-app/LangBot) — Multi-platform IM bot: Discord, Slack, Telegram, WeChat, Feishu, DingTalk, QQ — integrates with OpenClaw.
- [openclaw-wechat](https://github.com/freestylefly/openclaw-wechat) — WeChat integration for OpenClaw.
- [wecom-openclaw-plugin](https://github.com/11haonb/wecom-openclaw-plugin) — Enterprise WeCom channel integration.
- [openclaw-waha-plugin](https://github.com/omernesh/openclaw-waha-plugin) — WhatsApp channel plugin via WAHA.
- [openclaw-kakao-talkchannel-plugin](https://github.com/kakao-bart-lee/openclaw-kakao-talkchannel-plugin) — KakaoTalk channel plugin.
- [openclaw-channel-plugin-ztm](https://github.com/clawparty-ai/openclaw-channel-plugin-ztm) — ZTM (Zero Trust Mesh) P2P messaging channel.

## Literature Search & Discovery

Tools and APIs for finding and discovering academic papers.

- [Semantic Scholar](https://www.semanticscholar.org/) — AI-powered academic search engine; free API available.
- [OpenAlex](https://openalex.org/) — Open catalog of the world's scholarly papers, authors, and institutions.
- [arXiv](https://arxiv.org/) — Open-access preprint repository for STEM fields.
- [Connected Papers](https://www.connectedpapers.com/) — Visual graph of papers related to a seed paper.
- [Inciteful](https://inciteful.xyz/) — Citation network analysis for literature exploration.
- [Litmaps](https://www.litmaps.com/) — Interactive citation maps for literature review.
- [Google Scholar](https://scholar.google.com/) — Broad scholarly literature search.
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/) — Biomedical and life sciences literature database.
- [Publish or Perish](https://harzing.com/resources/publish-or-perish) — Free desktop tool for citation analysis from Google Scholar.
- [Scholarly](https://pypi.org/project/scholarly/) — Python library for Google Scholar scraping.

## Citation & Reference Management

Tools for managing references, citations, and bibliographies.

- [Zotero](https://www.zotero.org/) — Free, open-source reference manager with browser integration.
- [Mendeley](https://www.mendeley.com/) — Reference manager with academic social network features.
- [EndNote](https://endnote.com/) — Professional reference management tool.
- [CrossRef](https://www.crossref.org/) — DOI registration and metadata retrieval.
- [DataCite](https://datacite.org/) — DOI registration for research data.

## Experiment Tracking & Reproducibility

Tools for tracking experiments, managing results, and ensuring reproducibility.

- [MLflow](https://mlflow.org/) — Open-source platform for the ML lifecycle.
- [Weights & Biases](https://wandb.ai/) — ML experiment tracking, dataset versioning, model management.
- [DVC](https://dvc.org/) — Data Version Control for ML projects.
- [Papers with Code](https://paperswithcode.com/) — Free resource linking papers, code, datasets, and benchmarks.

## LaTeX & Writing Tools

Tools for academic writing, LaTeX compilation, and document preparation.

- [Overleaf](https://www.overleaf.com/) — Collaborative online LaTeX editor.
- [LaTeX Workshop (VS Code)](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) — Full-featured LaTeX extension for VS Code.
- [Writefull](https://www.writefull.com/) — AI-powered academic writing feedback.
- [Grammarly](https://www.grammarly.com/) — Writing assistant with grammar, clarity, and tone suggestions.

## Data Sources & APIs

APIs and data sources used by ResearchClaw for literature and citation data.

| Source | Type | Access |
|--------|------|--------|
| [OpenAlex API](https://docs.openalex.org/) | Scholarly metadata | Free, open |
| [Semantic Scholar API](https://api.semanticscholar.org/) | Paper search & citations | Free (rate-limited) |
| [arXiv API](https://info.arxiv.org/help/api/) | Preprints | Free, open |
| [CrossRef API](https://www.crossref.org/documentation/retrieve-metadata/) | DOI metadata | Free (polite pool) |
| [DataCite API](https://support.datacite.org/docs/api) | Research data DOIs | Free |
| [PubMed API (E-utilities)](https://www.ncbi.nlm.nih.gov/books/NBK25501/) | Biomedical literature | Free |
| [CORE API](https://core.ac.uk/services/api) | Open access papers | Free |

## Community & Learning

Resources for learning about AI-powered research and the ResearchClaw ecosystem.

### Communities

- [AutoResearchClaw Discord](https://discord.gg/u4ksqW5P) — Official community for AutoResearchClaw users and contributors.
- [OpenClaw Community](https://github.com/openclaw/openclaw/discussions) — Discussions around the OpenClaw ecosystem.

### Guides & Tutorials

- [AutoResearchClaw Testing Guide](https://github.com/aiming-lab/AutoResearchClaw#-were-looking-for-testers) — Try the pipeline with your own research idea.
- [ResearchClaw Quick Start](https://ymx10086.github.io/ResearchClaw/) — Official docs for ResearchClaw setup and usage.
- [AutoResearchClaw Integration Guide](https://github.com/aiming-lab/AutoResearchClaw/blob/main/docs/integration-guide.md) — Integrating with OpenClaw, Claude Code, ACP agents.

### Curated Lists

- [Awesome AI Research Writing](https://github.com/Leey21/awesome-ai-research-writing) — Curated AI research writing resources and tools.
- [Awesome Scientific Writing](https://github.com/writing-resources/awesome-scientific-writing) — Distraction-free scientific writing with Markdown, reStructuredText, and Jupyter.
- [Awesome Research](https://github.com/emptymalei/awesome-research) — Research tools covering note-taking, writing, presentation, and more.

## Related Awesome Lists

- [Awesome Claws](https://github.com/LHL3341/awesome-claws) — OpenClaw-related products, skills, communities.
- [Awesome Research](https://github.com/emptymalei/awesome-research) — General research tools.
- [Awesome Deep Learning](https://github.com/ChristosChristofidis/awesome-deep-learning) — Deep learning resources.
- [Awesome Generative AI](https://github.com/steven2358/awesome-generative-ai) — Generative AI tools and resources.
- [Papers We Love](https://github.com/papers-we-love/papers-we-love) — Papers from the CS community to read and discuss.

---

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the author has waived all copyright and related or neighboring rights to this work.
