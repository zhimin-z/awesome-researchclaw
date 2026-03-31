# Awesome ResearchClaw [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> 🦞 ResearchClaw 生态项目、工具、集成和资源的精选列表——面向 AI 驱动的学术科研。

ResearchClaw 是一个新兴的 AI 科研助手生态系统，涵盖自主论文写作流水线和科研工作流工具。本列表收录了核心项目、扩展、相关工具和学习资源。

[English](README.md)

## 目录

- [核心项目](#核心项目)
- [自主科研流水线](#自主科研流水线)
- [科研助手与工作流工具](#科研助手与工作流工具)
- [OpenClaw 生态](#openclaw-生态)
- [技能与插件](#技能与插件)
- [社区与学习](#社区与学习)
- [相关 Awesome 列表](#相关-awesome-列表)

---

## 核心项目

ResearchClaw 生态的基础项目。

- [ResearchClaw](https://github.com/ymx10086/ResearchClaw) — 本地优先的 Research OS：论文管理、文献检索、实验追踪、多 Agent 协作、Overleaf 同步、多渠道接入（CLI / Web UI / Telegram / 飞书 / QQ / 钉钉）。
- [AutoResearchClaw](https://github.com/aiming-lab/AutoResearchClaw) — 全自动 23 阶段科研流水线。输入一个想法，输出会议级论文——含真实引用、沙箱实验、多 Agent 同行评审。⭐ 9.6k+
- [Research Claw (nanoAgentTeam)](https://github.com/nanoAgentTeam/research-claw) — 自托管 AI 科研助手，支持 Overleaf 同步、多 Agent 协作、文献检索、多渠道交互（Telegram、飞书、QQ、钉钉）。

## 自主科研流水线

端到端自动化科研系统——从想法到论文。

- [AutoResearchClaw](https://github.com/aiming-lab/AutoResearchClaw) — 23 阶段流水线：想法 → 文献综述 → 假设 → 实验 → 论文 → 同行评审。支持 OpenClaw、Claude Code、ACP 代理。
- [AI Scientist](https://github.com/SakanaAI/AI-Scientist) — Sakana AI 的自动化科研先驱；全周期科学发现 Agent。
- [AutoResearch](https://github.com/karpathy/autoresearch) — Andrej Karpathy 的端到端科研自动化框架。
- [FARS](https://analemma.ai/blog/introducing-fars/) — Analemma 的全自动科研系统。
- [Auto-claude-code-research-in-sleep (ARIS)](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep) — 轻量级纯 Markdown 技能，用于自主 ML 研究：跨模型审阅循环、想法发现、实验自动化。
- [Scientify](https://github.com/tsingyuai/scientify) — OpenClaw 原生科研自动化插件，6 阶段流水线：文献综述 → 深度分析 → 实施计划 → 代码生成 → 自动审阅 → 实验。
- [ScienceClaw](https://github.com/Zaoqu-Liu/ScienceClaw) — 基于 OpenClaw 的 AI 科研团队 / 科研工作流助手。

## 科研助手与工作流工具

帮助研究人员贯穿工作流的交互式助手和工具。

- [ResearchClaw](https://github.com/ymx10086/ResearchClaw) — 完整的 Research OS，含声明/证据图谱、实验追踪、工作流阶段、项目仪表板。
- [Elicit](https://elicit.com/) — AI 科研助手；自动化文献综述、系统综述、数据提取。
- [Consensus](https://consensus.app/) — AI 搜索引擎，直接从研究论文中发现洞察。
- [ResearchRabbit](https://www.researchrabbit.ai/) — "科研版 Spotify"——基于集合的论文发现与 AI 推荐。

## OpenClaw 生态

OpenClaw 大生态中与 ResearchClaw 互补的项目和工具。

- [OpenClaw](https://github.com/openclaw/openclaw) — ResearchClaw 集成的 AI 网关 / 个人助手平台。
- [Awesome Claws](https://github.com/LHL3341/awesome-claws) — OpenClaw 相关产品、技能、社区和生态资源精选列表。
- [MetaClaw](https://pypi.org/project/metaclaw/) — 自学习技能系统；AutoResearchClaw 用它从历史运行中学习并提升流水线质量。
- [ACPX](https://github.com/openclaw/acpx) — Agent Client Protocol——让 AutoResearchClaw 使用任何 ACP 兼容 Agent（Claude、Codex、Copilot、Gemini 等）作为 LLM 后端。
- [MimicLaw](https://github.com/memovai/mimiclaw) — Claw 生态中的紧凑型助手项目。
- [EverMemOS](https://github.com/EverMind-AI/EverMemOS) — 7×24 OpenClaw Agent 的长期记忆系统；含 OpenClaw 插件和 Live2D 集成。

## 技能与插件

扩展 ResearchClaw 能力的可复用技能和插件。

### 内置技能（ResearchClaw）

- `arxiv` — arXiv 论文搜索与下载
- `citation_network` — 引用网络探索与可视化
- `experiment_tracker` — 实验生命周期管理
- `figure_generator` — 学术图表生成
- `literature_review` — 自动化文献综述工作流
- `paper_summarizer` — 论文总结与关键洞察提取
- `research_notes` — 结构化笔记（论文笔记、想法笔记、实验笔记）
- `research_workflows` — 多阶段科研工作流管理
- `pdf` / `docx` / `pptx` / `xlsx` — 文档格式支持

### AutoResearchClaw 多 Agent 子系统

- **CodeAgent** — 多阶段实验代码生成
- **BenchmarkAgent** — 自动数据集发现与基线对比
- **FigureAgent** — 5-Agent 流水线：规划 → 代码生成 → 渲染 → 评审 → 集成
- **Sentinel Watchdog** — 后台质量监控：NaN/Inf 检测、引用评分、反造假

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
