# Awesome ResearchClaw [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> 🦞 A curated list of ResearchClaw ecosystem projects, tools, integrations, and resources for AI-powered academic research.

ResearchClaw is an emerging ecosystem of AI-powered research assistants, autonomous paper-writing pipelines, and scientific workflow tools. This list covers the core projects, extensions, related tools, and learning resources.

👉 For hands-on experience reports and evaluation scores, check out the [Research Claw Arena](https://sustech-genai.github.io/research-claw-arena/).

[中文](README_zh.md)

## Contents

- [OpenClaw Ecosystem & Research Tools](#openclaw-ecosystem--research-tools)
- [Research Agents & AI Scientists](#research-agents--ai-scientists)
- [Deep Research & Frameworks](#deep-research--frameworks)
- [Community & Learning](#community--learning)
- [Related Awesome Lists](#related-awesome-lists)

---

> **Capability columns:** I = Idea generation · Fig = Figure / visualization · Write = Writing / drafting · Exp = Experiment / execution · R = Review / rebuttal
> ✓ = Explicitly supported · △ = Indirect / framework capability · — = Not mentioned

## OpenClaw Ecosystem & Research Tools

Projects directly related to the OpenClaw ecosystem — core platforms, skill libraries, plugins, and curated lists.

| Project | Owner | ⭐ Stars | I | Fig | Write | Exp | R | Description |
|---------|-------|---------|---|-----|-------|-----|---|-------------|
| [AutoResearchClaw](https://github.com/aiming-lab/AutoResearchClaw) | aiming-lab | ![Stars](https://img.shields.io/github/stars/aiming-lab/AutoResearchClaw?style=flat-square) | △ | ✓ | ✓ | ✓ | ✓ | 23-stage idea → paper pipeline with auto LaTeX, citation verification, experiments, figures, and multi-agent peer review. |
| [ResearchClaw](https://github.com/ymx10086/ResearchClaw) | ymx10086 | ![Stars](https://img.shields.io/github/stars/ymx10086/ResearchClaw?style=flat-square) | — | △ | ✓ | ✓ | — | Local-first Research OS with claims/evidence graph, experiment tracking, paper management, skills, and multi-channel access. |
| [Research Claw](https://github.com/nanoAgentTeam/research-claw) | nanoAgentTeam | ![Stars](https://img.shields.io/github/stars/nanoAgentTeam/research-claw?style=flat-square) | — | — | ✓ | — | — | Self-hosted academic assistant — paper management, literature search, deadline tracking, and LaTeX/Overleaf sync. |
| [Prismer](https://github.com/Prismer-AI/Prismer) | Prismer-AI | ![Stars](https://img.shields.io/github/stars/Prismer-AI/Prismer?style=flat-square) | — | △ | ✓ | ✓ | △ | End-to-end research platform with PDF reading, Jupyter, LaTeX, code execution, and citation verification. |
| [LabClaw](https://github.com/wu-yc/LabClaw) | wu-yc | ![Stars](https://img.shields.io/github/stars/wu-yc/LabClaw?style=flat-square) | — | ✓ | ✓ | ✓ | — | 240 OpenClaw skills for biology, pharmacology, medicine, literature, and visualization. |
| [PaperClaw](https://github.com/meowscles69/PaperClaw) | meowscles69 | ![Stars](https://img.shields.io/github/stars/meowscles69/PaperClaw?style=flat-square) | △ | — | ✓ | — | — | 27 skills for academic teams — literature reviews, hypothesis versioning, grant writing, and knowledge handoffs. |
| [scholar-skill](https://github.com/EESJGong/scholar-skill) | EESJGong | ![Stars](https://img.shields.io/github/stars/EESJGong/scholar-skill?style=flat-square) | — | — | — | — | — | OpenClaw skill for academic reading, knowledge linking, reflection, and Obsidian knowledge evolution. |
| [openclaw-paper-tools](https://github.com/henry-y/openclaw-paper-tools) | henry-y | ![Stars](https://img.shields.io/github/stars/henry-y/openclaw-paper-tools?style=flat-square) | — | — | — | — | — | Auto-fetches HF Daily Papers and one-click deep reading via SwiftScholar. |
| [Awesome Claws](https://github.com/LHL3341/awesome-claws) | LHL3341 | ![Stars](https://img.shields.io/github/stars/LHL3341/awesome-claws?style=flat-square) | — | — | — | — | — | Curated index of OpenClaw-related products, skills, communities, and ecosystem resources. |
| [awesome-autoresearch](https://github.com/alvinunreal/awesome-autoresearch) | alvinunreal | ![Stars](https://img.shields.io/github/stars/alvinunreal/awesome-autoresearch?style=flat-square) | — | — | — | — | — | High-signal index of Karpathy autoresearch forks, research agents, and benchmarks. |
| [Scientify](https://github.com/tsingyuai/scientify) | tsingyuai | ![Stars](https://img.shields.io/github/stars/tsingyuai/scientify?style=flat-square) | ✓ | △ | ✓ | ✓ | — | "Continuous metabolism" research system — tracks papers, evolves hypotheses, runs validation, and pushes updates proactively. |
| [OpenClaw-RL](https://github.com/Gen-Verse/OpenClaw-RL) | Gen-Verse | ![Stars](https://img.shields.io/github/stars/Gen-Verse/OpenClaw-RL?style=flat-square) | — | — | — | ✓ | — | Turns daily conversations into training signal; async reinforcement learning to personalize OpenClaw or any agent. |
| [ClawTeam-OpenClaw](https://github.com/win4r/ClawTeam-OpenClaw) | win4r | ![Stars](https://img.shields.io/github/stars/win4r/ClawTeam-OpenClaw?style=flat-square) | — | — | — | △ | — | ClawTeam's deep-adapted OpenClaw fork — swarm coordination, worktree isolation, and tmux multi-agent management. |
| [x-research-skill](https://github.com/rohunvora/x-research-skill) | rohunvora | ![Stars](https://img.shields.io/github/stars/rohunvora/x-research-skill?style=flat-square) | — | — | △ | — | — | Wraps X/Twitter as a terminal research tool — search, thread following, monitoring, and sourced briefings. |
| [openclaw-agents](https://github.com/shenhao-stu/openclaw-agents) | shenhao-stu | ![Stars](https://img.shields.io/github/stars/shenhao-stu/openclaw-agents?style=flat-square) | ✓ | — | ✓ | △ | ✓ | One-command setup for 9 specialized agents with Paper Pipeline, Brainstorm, Daily Digest, and Rebuttal built in. |
| [MemOS-Cloud-OpenClaw-Plugin](https://github.com/MemTensor/MemOS-Cloud-OpenClaw-Plugin) | MemTensor | ![Stars](https://img.shields.io/github/stars/MemTensor/MemOS-Cloud-OpenClaw-Plugin?style=flat-square) | — | — | — | — | — | Official MemOS Cloud lifecycle plugin — recall before run, write back to long-term memory after run. |
| [openclaw-engram](https://github.com/joshuaswarren/openclaw-engram) | joshuaswarren | ![Stars](https://img.shields.io/github/stars/joshuaswarren/openclaw-engram?style=flat-square) | — | — | — | — | — | Local-first long-term memory layer for agents — markdown storage, hybrid retrieval, cross-session research context. |
| [SkillNet](https://github.com/zjunlp/SkillNet) | ZJUNLP | ![Stars](https://img.shields.io/github/stars/zjunlp/SkillNet?style=flat-square) | — | — | — | — | — | Skill creation, evaluation, connection, and discovery infrastructure — searches 300k+ community skills. |
| [OpenClaw-Medical-Skills](https://github.com/FreedomIntelligence/OpenClaw-Medical-Skills) | FreedomIntelligence | ![Stars](https://img.shields.io/github/stars/FreedomIntelligence/OpenClaw-Medical-Skills?style=flat-square) | — | △ | △ | △ | — | 869 medical/biomedical skills spanning clinical, genomics, and drug discovery domains. |
| [ARIS](https://github.com/zhangchenhaobest/Auto-claude-code-research-in-sleep) | zhangchenhaobest | ![Stars](https://img.shields.io/github/stars/zhangchenhaobest/Auto-claude-code-research-in-sleep?style=flat-square) | ✓ | △ | ✓ | ✓ | ✓ | Lightweight Markdown-only research workflow — cross-model review loops, idea discovery, and experiment automation. |

## Research Agents & AI Scientists

General-purpose autonomous research agents, AI scientist systems, and research benchmarks.

| Project | Owner | ⭐ Stars | I | Fig | Write | Exp | R | Description |
|---------|-------|---------|---|-----|-------|-----|---|-------------|
| [AgentLaboratory](https://github.com/SamuelSchmidgall/AgentLaboratory) | SamuelSchmidgall | ![Stars](https://img.shields.io/github/stars/SamuelSchmidgall/AgentLaboratory?style=flat-square) | △ | — | ✓ | ✓ | — | End-to-end autonomous research workflow — turns your research ideas into complete experiments and papers. |
| [AI-Researcher](https://github.com/HKUDS/AI-Researcher) | HKUDS | ![Stars](https://img.shields.io/github/stars/HKUDS/AI-Researcher?style=flat-square) | ✓ | — | ✓ | ✓ | — | Autonomous Scientific Innovation with dedicated `research_agent` and `paper_agent` modules. |
| [AI-Scientist-v2](https://github.com/SakanaAI/AI-Scientist-v2) | SakanaAI | ![Stars](https://img.shields.io/github/stars/SakanaAI/AI-Scientist-v2?style=flat-square) | ✓ | — | △ | ✓ | — | Workshop-level automated scientific discovery via agentic tree search. |
| [OmniScientist](https://github.com/tsinghua-fib-lab/OmniScientist) | Tsinghua FIB Lab | ![Stars](https://img.shields.io/github/stars/tsinghua-fib-lab/OmniScientist?style=flat-square) | ✓ | — | ✓ | ✓ | — | AI Scientist ecosystem covering idea generation, experiment design, and paper writing as a holistic blueprint. |
| [LLM-MM-Agent](https://github.com/usail-hkust/LLM-MM-Agent) | HKUST | ![Stars](https://img.shields.io/github/stars/usail-hkust/LLM-MM-Agent?style=flat-square) | — | ✓ | ✓ | ✓ | — | Mathematical modeling agent — problem analysis, modeling, code solving, visualization, and report generation. |
| [Virtual-Scientists](https://github.com/InternScience/Virtual-Scientists) | InternScience | ![Stars](https://img.shields.io/github/stars/InternScience/Virtual-Scientists?style=flat-square) | ✓ | — | — | — | — | ACL 2025 project — many-heads multi-agent scientific idea generation. |
| [MLGym](https://github.com/facebookresearch/MLGym) | Meta FAIR | ![Stars](https://img.shields.io/github/stars/facebookresearch/MLGym?style=flat-square) | — | — | — | — | — | Unified framework and benchmark for AI research agents. |
| [aira-dojo](https://github.com/facebookresearch/aira-dojo) | Meta FAIR | ![Stars](https://img.shields.io/github/stars/facebookresearch/aira-dojo?style=flat-square) | — | — | — | △ | — | Extensible AI research agent development and evaluation framework with isolated code execution. |
| [AIRS-Bench](https://github.com/facebookresearch/airs-bench) | Meta FAIR | ![Stars](https://img.shields.io/github/stars/facebookresearch/airs-bench?style=flat-square) | — | — | — | — | — | Benchmark for quantifying end-to-end AI research abilities of LLM agents. |
| [DeepResearch Bench](https://github.com/Ayanami0730/deep_research_bench) | Ayanami0730 | ![Stars](https://img.shields.io/github/stars/Ayanami0730/deep_research_bench?style=flat-square) | — | — | — | — | — | Comprehensive benchmark and leaderboard for deep research agents. |

## Deep Research & Frameworks

Deep research agents and foundational frameworks for agent-driven scientific exploration.

| Project | Owner | ⭐ Stars | I | Fig | Write | Exp | R | Description |
|---------|-------|---------|---|-----|-------|-----|---|-------------|
| [open_deep_research](https://github.com/langchain-ai/open_deep_research) | LangChain | ![Stars](https://img.shields.io/github/stars/langchain-ai/open_deep_research?style=flat-square) | — | — | ✓ | — | — | Fully open-source deep research agent — multi-model, multi-search API, MCP support, and built-in report generation. |
| [DeepResearch](https://github.com/Alibaba-NLP/DeepResearch) | Alibaba-NLP | ![Stars](https://img.shields.io/github/stars/Alibaba-NLP/DeepResearch?style=flat-square) | — | — | △ | — | — | Tongyi Deep Research — the highest-starred open-source deep research agent in this list. |
| [MiroThinker](https://github.com/MiroMindAI/MiroThinker) | MiroMindAI | ![Stars](https://img.shields.io/github/stars/MiroMindAI/MiroThinker?style=flat-square) | — | — | △ | — | — | Deep research agent for complex research and prediction tasks; top BrowseComp scores (74.0 / 88.2). |
| [MiroFlow](https://github.com/MiroMindAI/miroflow) | MiroMindAI | ![Stars](https://img.shields.io/github/stars/MiroMindAI/miroflow?style=flat-square) | — | — | — | — | — | Performance-first open-source agent framework — #1 on 5+ benchmarks, supports MiroThinker, Claude, Kimi, OpenAI. |
| [CognitiveKernel-Pro](https://github.com/Tencent/CognitiveKernel-Pro) | Tencent AI Lab | ![Stars](https://img.shields.io/github/stars/Tencent/CognitiveKernel-Pro?style=flat-square) | — | — | — | △ | — | Tencent's deep research agent framework with agent foundation model training. |
| [Simply](https://github.com/google-deepmind/simply) | Google DeepMind | ![Stars](https://img.shields.io/github/stars/google-deepmind/simply?style=flat-square) | ✓ | — | — | ✓ | — | Minimal JAX research codebase — designed for agents to read code, propose ideas, run experiments, and iterate. |

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
