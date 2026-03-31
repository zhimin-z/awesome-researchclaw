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
- [ResearchRabbit](https://www.researchrabbit.ai/) — "Spotify for research" — collection-based paper discovery with AI recommendations.

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
- [Awesome Research](https://github.com/emptymalei/awesome-research) — Research tools covering note-taking, writing, presentation, and more.

## Related Awesome Lists

- [Awesome Claws](https://github.com/LHL3341/awesome-claws) — OpenClaw-related products, skills, communities.
- [Awesome Research](https://github.com/emptymalei/awesome-research) — General research tools.

---

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the author has waived all copyright and related or neighboring rights to this work.
