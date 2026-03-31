# Awesome ResearchClaw [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> 🦞 ResearchClaw 生态项目、工具、集成和资源的精选列表——面向 AI 驱动的学术科研。

ResearchClaw 是一个新兴的 AI 科研助手生态系统，涵盖自主论文写作流水线和科研工作流工具。本列表收录了核心项目、扩展、相关工具和学习资源。

👉 如果想看具体的体验，可参考该项目的[开源项目体验报告以及评测打分](https://sustech-genai.github.io/research-claw-arena/)。

[English](README.md)

## 目录

- [项目对比矩阵](#项目对比矩阵)
  - [OpenClaw 生态与科研工具](#openclaw-生态与科研工具)
  - [通用 Research Agent / AI Scientist](#通用-research-agent--ai-scientist)
  - [Deep Research 与框架](#deep-research-与框架)
- [社区与学习](#社区与学习)
- [相关 Awesome 列表](#相关-awesome-列表)

---

## 项目对比矩阵

> **能力列说明：** I = 想法生成 · 图 = 绘图/可视化 · 写 = 写作/成稿 · 实验 = 自动实验/执行 · R = 审稿/rebuttal
> ✓ = README 明确支持 · △ = 间接支持/框架能力 · — = 未见明确说明

### OpenClaw 生态与科研工具

| 项目 | 所有者 | ⭐ Stars | I | 图 | 写 | 实验 | R | 简述 |
|------|-------|---------|---|---|---|-----|---|------|
| [AutoResearchClaw](https://github.com/aiming-lab/AutoResearchClaw) | aiming-lab | ![Stars](https://img.shields.io/github/stars/aiming-lab/AutoResearchClaw?style=flat-square) | △ | ✓ | ✓ | ✓ | ✓ | 23 阶段 idea→paper，自动出 LaTeX、引用校验、实验结果和图表，还有多 agent 审稿。 |
| [ResearchClaw](https://github.com/ymx10086/ResearchClaw) | ymx10086 | ![Stars](https://img.shields.io/github/stars/ymx10086/ResearchClaw?style=flat-square) | — | △ | ✓ | ✓ | — | 本地优先的科研操作系统，带 claims/evidence、experiment tracking、papers、skills、channels。 |
| [research-claw](https://github.com/nanoAgentTeam/research-claw) | nanoAgentTeam | ![Stars](https://img.shields.io/github/stars/nanoAgentTeam/research-claw?style=flat-square) | — | — | ✓ | — | — | 自托管学术助手，管论文、搜文献、跟 deadline、维护 LaTeX/Overleaf。 |
| [Prismer](https://github.com/Prismer-AI/Prismer) | Prismer-AI | ![Stars](https://img.shields.io/github/stars/Prismer-AI/Prismer?style=flat-square) | — | △ | ✓ | ✓ | △ | 从读论文到发论文的研究平台，带 PDF 阅读、Jupyter、LaTeX、代码执行和 citation verification。 |
| [LabClaw](https://github.com/wu-yc/LabClaw) | wu-yc | ![Stars](https://img.shields.io/github/stars/wu-yc/LabClaw?style=flat-square) | — | ✓ | ✓ | ✓ | — | 240 个面向生物、药物、医学、文献和可视化的 OpenClaw 技能包。 |
| [PaperClaw](https://github.com/meowscles69/PaperClaw) | meowscles69 | ![Stars](https://img.shields.io/github/stars/meowscles69/PaperClaw?style=flat-square) | △ | — | ✓ | — | — | 面向学术团队的 27 个技能，偏综述、假设版本管理、grant writing 和知识交接。 |
| [scholar-skill](https://github.com/EESJGong/scholar-skill) | EESJGong | ![Stars](https://img.shields.io/github/stars/EESJGong/scholar-skill?style=flat-square) | — | — | — | — | — | 面向学术阅读、知识链接、反思与 Obsidian 知识演化的 OpenClaw skill。 |
| [openclaw-paper-tools](https://github.com/henry-y/openclaw-paper-tools) | henry-y | ![Stars](https://img.shields.io/github/stars/henry-y/openclaw-paper-tools?style=flat-square) | — | — | — | — | — | 自动抓 HF Daily Papers，并一键送去 SwiftScholar 做深读。 |
| [awesome-claws](https://github.com/LHL3341/awesome-claws) | LHL3341 | ![Stars](https://img.shields.io/github/stars/LHL3341/awesome-claws?style=flat-square) | — | — | — | — | — | OpenClaw 相关产品、skills、社区和生态资源的导航索引。 |
| [awesome-autoresearch](https://github.com/alvinunreal/awesome-autoresearch) | alvinunreal | ![Stars](https://img.shields.io/github/stars/alvinunreal/awesome-autoresearch?style=flat-square) | — | — | — | — | — | Karpathy autoresearch 系分支、research agents、benchmarks 的高信号索引。 |
| [scientify](https://github.com/tsingyuai/scientify) | tsingyuai | ![Stars](https://img.shields.io/github/stars/tsingyuai/scientify?style=flat-square) | ✓ | △ | ✓ | ✓ | — | 强调"持续新陈代谢"的科研系统，持续跟论文、进化假设、跑验证并主动推送。 |
| [OpenClaw-RL](https://github.com/Gen-Verse/OpenClaw-RL) | Gen-Verse | ![Stars](https://img.shields.io/github/stars/Gen-Verse/OpenClaw-RL?style=flat-square) | — | — | — | ✓ | — | 把日常对话变成训练信号，异步强化学习个性化 OpenClaw 或通用 agent。 |
| [ClawTeam-OpenClaw](https://github.com/win4r/ClawTeam-OpenClaw) | win4r | ![Stars](https://img.shields.io/github/stars/win4r/ClawTeam-OpenClaw?style=flat-square) | — | — | — | △ | — | ClawTeam 的 OpenClaw 深度适配 fork，主打 swarm 协作、worktree 和 tmux 隔离。 |
| [x-research-skill](https://github.com/rohunvora/x-research-skill) | rohunvora | ![Stars](https://img.shields.io/github/stars/rohunvora/x-research-skill?style=flat-square) | — | — | △ | — | — | 把 X/Twitter 包成终端研究工具，支持 search、thread follow、monitor 和 briefings。 |
| [openclaw-agents](https://github.com/shenhao-stu/openclaw-agents) | shenhao-stu | ![Stars](https://img.shields.io/github/stars/shenhao-stu/openclaw-agents?style=flat-square) | ✓ | — | ✓ | △ | ✓ | 一键起 9 个专职 agent，内置 Paper Pipeline、Brainstorm、Daily Digest、Rebuttal。 |
| [MemOS-Cloud-OpenClaw-Plugin](https://github.com/MemTensor/MemOS-Cloud-OpenClaw-Plugin) | MemTensor | ![Stars](https://img.shields.io/github/stars/MemTensor/MemOS-Cloud-OpenClaw-Plugin?style=flat-square) | — | — | — | — | — | 官方 MemOS Cloud 生命周期插件，run 前 recall，run 后写回长期记忆。 |
| [openclaw-engram](https://github.com/joshuaswarren/openclaw-engram) | joshuaswarren | ![Stars](https://img.shields.io/github/stars/joshuaswarren/openclaw-engram?style=flat-square) | — | — | — | — | — | 本地优先的 agent 长期记忆层，markdown 存储，混合检索，跨会话保留研究上下文。 |
| [SkillNet](https://github.com/zjunlp/SkillNet) | ZJUNLP | ![Stars](https://img.shields.io/github/stars/zjunlp/SkillNet?style=flat-square) | — | — | — | — | — | 做 skill 的创建、评估、连接和发现，号称可搜 30 万+ community skills。 |
| [OpenClaw-Medical-Skills](https://github.com/FreedomIntelligence/OpenClaw-Medical-Skills) | FreedomIntelligence | ![Stars](https://img.shields.io/github/stars/FreedomIntelligence/OpenClaw-Medical-Skills?style=flat-square) | — | △ | △ | △ | — | 869 个医学/生物医药技能，把通用 agent 往 clinical、genomics、drug discovery 拉。 |
| [Auto-claude-code-research-in-sleep](https://github.com/zhangchenhaobest/Auto-claude-code-research-in-sleep) | zhangchenhaobest | ![Stars](https://img.shields.io/github/stars/zhangchenhaobest/Auto-claude-code-research-in-sleep?style=flat-square) | ✓ | △ | ✓ | ✓ | ✓ | ARIS：纯 Markdown 的轻量研究工作流，主打 cross-model review、idea discovery、experiment automation。 |

### 通用 Research Agent / AI Scientist

| 项目 | 所有者 | ⭐ Stars | I | 图 | 写 | 实验 | R | 简述 |
|------|-------|---------|---|---|---|-----|---|------|
| [AgentLaboratory](https://github.com/SamuelSchmidgall/AgentLaboratory) | SamuelSchmidgall | ![Stars](https://img.shields.io/github/stars/SamuelSchmidgall/AgentLaboratory?style=flat-square) | △ | — | ✓ | ✓ | — | 端到端 autonomous research workflow，目标是把你的研究想法落成完整实验与论文。 |
| [AI-Researcher](https://github.com/HKUDS/AI-Researcher) | HKUDS | ![Stars](https://img.shields.io/github/stars/HKUDS/AI-Researcher?style=flat-square) | ✓ | — | ✓ | ✓ | — | "Autonomous Scientific Innovation"，仓库里明确分了 `research_agent` 和 `paper_agent`。 |
| [AI-Scientist-v2](https://github.com/SakanaAI/AI-Scientist-v2) | SakanaAI | ![Stars](https://img.shields.io/github/stars/SakanaAI/AI-Scientist-v2?style=flat-square) | ✓ | — | △ | ✓ | — | 主打 "Workshop-Level Automated Scientific Discovery via Agentic Tree Search"。 |
| [OmniScientist](https://github.com/tsinghua-fib-lab/OmniScientist) | 清华 FIB Lab | ![Stars](https://img.shields.io/github/stars/tsinghua-fib-lab/OmniScientist?style=flat-square) | ✓ | — | ✓ | ✓ | — | AI Scientist ecosystem，覆盖 idea generation、experiment design、paper writing 的整体蓝图。 |
| [LLM-MM-Agent](https://github.com/usail-hkust/LLM-MM-Agent) | HKUST | ![Stars](https://img.shields.io/github/stars/usail-hkust/LLM-MM-Agent?style=flat-square) | — | ✓ | ✓ | ✓ | — | 数学建模 agent，做问题分析、建模、代码求解、可视化和报告生成。 |
| [Virtual-Scientists](https://github.com/InternScience/Virtual-Scientists) | InternScience | ![Stars](https://img.shields.io/github/stars/InternScience/Virtual-Scientists?style=flat-square) | ✓ | — | — | — | — | ACL 2025 项目，核心卖点是 many-heads 的 scientific idea generation。 |
| [MLGym](https://github.com/facebookresearch/MLGym) | Meta FAIR | ![Stars](https://img.shields.io/github/stars/facebookresearch/MLGym?style=flat-square) | — | — | — | — | — | 面向 AI research agents 的统一框架和 benchmark。 |
| [aira-dojo](https://github.com/facebookresearch/aira-dojo) | Meta FAIR | ![Stars](https://img.shields.io/github/stars/facebookresearch/aira-dojo?style=flat-square) | — | — | — | △ | — | 可扩展的 AI research agent 开发/评测框架，带隔离代码执行环境，直指 fully automated AI research scientist。 |
| [airs-bench](https://github.com/facebookresearch/airs-bench) | Meta FAIR | ![Stars](https://img.shields.io/github/stars/facebookresearch/airs-bench?style=flat-square) | — | — | — | — | — | 用来量化 LLM agents 端到端 AI research 能力的基准。 |
| [deep_research_bench](https://github.com/Ayanami0730/deep_research_bench) | Ayanami0730 | ![Stars](https://img.shields.io/github/stars/Ayanami0730/deep_research_bench?style=flat-square) | — | — | — | — | — | 面向 deep research agents 的综合 benchmark 和 leaderboard。 |

### Deep Research 与框架

| 项目 | 所有者 | ⭐ Stars | I | 图 | 写 | 实验 | R | 简述 |
|------|-------|---------|---|---|---|-----|---|------|
| [open_deep_research](https://github.com/langchain-ai/open_deep_research) | LangChain | ![Stars](https://img.shields.io/github/stars/langchain-ai/open_deep_research?style=flat-square) | — | — | ✓ | — | — | 全开源 deep research agent，跨多模型、多搜索 API、多 MCP，内置 final report 生成。 |
| [DeepResearch](https://github.com/Alibaba-NLP/DeepResearch) | Alibaba-NLP | ![Stars](https://img.shields.io/github/stars/Alibaba-NLP/DeepResearch?style=flat-square) | — | — | △ | — | — | Tongyi Deep Research，当前这批里 star 最高，主打 open-source deep research agent。 |
| [MiroThinker](https://github.com/MiroMindAI/MiroThinker) | MiroMindAI | ![Stars](https://img.shields.io/github/stars/MiroMindAI/MiroThinker?style=flat-square) | — | — | △ | — | — | 面向复杂 research 与 prediction 任务的 deep research agent，BrowseComp 分数很高。 |
| [MiroFlow](https://github.com/MiroMindAI/miroflow) | MiroMindAI | ![Stars](https://img.shields.io/github/stars/MiroMindAI/miroflow?style=flat-square) | — | — | — | — | — | 强调 performance-first 的开源 agent 框架，同环境下尽量把不同模型的 agent 表现做满。 |
| [CognitiveKernel-Pro](https://github.com/Tencent/CognitiveKernel-Pro) | Tencent AI Lab | ![Stars](https://img.shields.io/github/stars/Tencent/CognitiveKernel-Pro?style=flat-square) | — | — | — | △ | — | 腾讯的 Deep Research Agent 框架，同时谈 agent foundation models training。 |
| [simply](https://github.com/google-deepmind/simply) | Google DeepMind | ![Stars](https://img.shields.io/github/stars/google-deepmind/simply?style=flat-square) | ✓ | — | — | ✓ | — | 极简 JAX 研究底座，README 明写可让 agent 读代码、提想法、跑实验、反复迭代。 |

---

## 社区与学习

关于 AI 驱动科研和 ResearchClaw 生态的学习资源。

### 社区

- [AutoResearchClaw Discord](https://discord.gg/u4ksqW5P) — AutoResearchClaw 用户和贡献者的官方社区。
- [OpenClaw 社区](https://github.com/openclaw/openclaw/discussions) — OpenClaw 生态相关讨论。

### 指南与教程

- [AutoResearchClaw 测试指南](https://github.com/aiming-lab/AutoResearchClaw#-were-looking-for-testers) — 用你自己的研究想法试用流水线。
- [ResearchClaw 快速上手](https://ymx10086.github.io/ResearchClaw/) — ResearchClaw 安装和使用的官方文档。
- [AutoResearchClaw 集成指南](https://github.com/aiming-lab/AutoResearchClaw/blob/main/docs/integration-guide.md) — 与 OpenClaw、Claude Code、ACP 代理的集成。

### 精选列表

- [Awesome AI Research Writing](https://github.com/Leey21/awesome-ai-research-writing) — AI 科研写作资源和工具精选。
- [Awesome Research](https://github.com/emptymalei/awesome-research) — 涵盖笔记、写作、演示等的研究工具。

## 相关 Awesome 列表

- [Awesome Claws](https://github.com/LHL3341/awesome-claws) — OpenClaw 相关产品、技能、社区。
- [Awesome Research](https://github.com/emptymalei/awesome-research) — 通用研究工具。

---

## 贡献

欢迎贡献！请先阅读[贡献指南](CONTRIBUTING.md)。

## 许可证

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内，作者已放弃本作品的所有版权及相关权利。
