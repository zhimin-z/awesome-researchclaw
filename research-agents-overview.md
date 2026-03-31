# Research Agents 总览

> 基于调研整理的 AI 自动科研 Agent 项目汇总——按能力、团队、热度分类。

---

## 能力矩阵

`✓` = 核心能力，官方明确支持 · `△` = 部分支持 / human-in-the-loop · `—` = 未明确支持

| # | 项目 | 想 Idea | 做实验 | 写论文 | 画图 | 能力分 | ⭐ Stars |
|---|------|:-------:|:------:|:------:|:----:|:------:|--------:|
| 1 | [AutoResearchClaw](https://github.com/aiming-lab/AutoResearchClaw) | ✓ | ✓ | ✓ | ✓ | 4.0 | ~9.6k |
| 2 | [The AI Scientist](https://github.com/SakanaAI/AI-Scientist) | ✓ | ✓ | ✓ | ✓ | 4.0 | ~12.5k |
| 3 | [The AI Scientist-v2](https://github.com/SakanaAI/AI-Scientist-v2) | ✓ | ✓ | ✓ | △ | 3.5 | ~2.3k |
| 4 | [AI-Researcher](https://github.com/HKUDS/AI-Researcher) | △ | ✓ | ✓ | — | 3.0 | ~4.9k |
| 5 | [OpenLens AI](https://github.com/jarrycyx/openlens-ai) | — | ✓ | ✓ | ✓ | 3.0 | ~251 |
| 6 | [EurekaClaw](https://github.com/eurekaclaw/eurekaclaw) | ✓ | △ | △ | — | 2.5 | ~340 |
| 7 | [Agent Laboratory](https://github.com/SamuelSchmidgall/AgentLaboratory) | — | ✓ | △ | — | 1.5 | ~5.4k |
| 8 | [ResearchAgent](https://github.com/JinheonBaek/ResearchAgent) | ✓ | △ | — | — | 1.5 | ~29 |
| 9 | [GPT Researcher](https://github.com/assafelovic/gpt-researcher) | — | — | △ | — | 0.5 | ~26k |

---

## 项目详情

### 第一梯队：真全流程闭环（Idea → 实验 → 论文 → 图表）

#### 1. AutoResearchClaw

- **链接**：https://github.com/aiming-lab/AutoResearchClaw
- **团队**：aiming-lab
- **Stars**：~9.6k
- **能力**：想 Idea ✓ · 做实验 ✓ · 写论文 ✓ · 画图 ✓
- **简介**：从 idea 到 paper 的全自动 23 阶段研究流水线，支持真实文献检索（OpenAlex / Semantic Scholar / arXiv）、沙箱实验执行、多 Agent peer review、4 层 citation verification，输出 conference-ready LaTeX。

#### 2. The AI Scientist

- **链接**：https://github.com/SakanaAI/AI-Scientist
- **团队**：Sakana AI
- **Stars**：~12.5k
- **能力**：想 Idea ✓ · 做实验 ✓ · 写论文 ✓ · 画图 ✓
- **简介**：首个全周期自动化科学发现 Agent，覆盖 idea generation → literature search → experiment planning → experiment iterations → figure generation → manuscript writing → reviewing。

#### 3. The AI Scientist-v2

- **链接**：https://github.com/SakanaAI/AI-Scientist-v2
- **团队**：Sakana AI
- **Stars**：~2.3k
- **能力**：想 Idea ✓ · 做实验 ✓ · 写论文 ✓ · 画图 △
- **简介**：v1 的升级版，引入 agentic tree search，宣称生成了首个"完全由 AI 写成并通过同行评审接收"的 workshop paper，是当前最接近投稿级闭环的系统。

---

### 第二梯队：实验 + 写作强，但部分环节需人类介入

#### 4. AI-Researcher

- **链接**：https://github.com/HKUDS/AI-Researcher
- **团队**：HKU Data Intelligence Lab（黄超组 / HKUDS）
- **Stars**：~4.9k
- **能力**：想 Idea △ · 做实验 ✓ · 写论文 ✓ · 画图 —
- **简介**：从 concept 到 publication 的全自动科学发现系统，含 Writer Agent 自动撰写完整学术论文；由香港大学黄超（Chao Huang）团队开发。

#### 5. OpenLens AI

- **链接**：https://github.com/jarrycyx/openlens-ai
- **团队**：jarrycyx
- **Stars**：~251
- **能力**：想 Idea — · 做实验 ✓ · 写论文 ✓ · 画图 ✓
- **简介**：给定数据集和 research idea，自动做 literature review → 设计实验 → 分析数据 → 生成带 academic rigor checks 的 LaTeX 论文，偏医学/数据驱动研究。

#### 6. EurekaClaw

- **链接**：https://github.com/eurekaclaw/eurekaclaw
- **团队**：eurekaclaw
- **Stars**：~340
- **能力**：想 Idea ✓ · 做实验 △ · 写论文 △ · 画图 —
- **简介**：2026 年新项目，从问题到 publishable result：crawl literature → generate/stress-test hypotheses → run experiments → write up findings。实验执行模块仍在开发中。

---

### 第三梯队：强工具链 / 半自动系统

#### 7. Agent Laboratory

- **链接**：https://github.com/SamuelSchmidgall/AgentLaboratory
- **团队**：Samuel Schmidgall
- **Stars**：~5.4k
- **能力**：想 Idea — · 做实验 ✓ · 写论文 △ · 画图 —
- **简介**：端到端自主研究工作流，覆盖 literature review → plan → experiments → report writing；接受**人类提供的 research idea**，更像研究助理流水线。

#### 8. ResearchAgent

- **链接**：https://github.com/JinheonBaek/ResearchAgent
- **团队**：Jinheon Baek
- **Stars**：~29
- **能力**：想 Idea ✓ · 做实验 △ · 写论文 — · 画图 —
- **简介**：基于文献的 iterative research idea generation，用多 Agent review/refinement 提高想法质量；强在想 idea 和设计实验方案，不自动执行完整实验。

#### 9. GPT Researcher

- **链接**：https://github.com/assafelovic/gpt-researcher
- **团队**：Assaf Elovic
- **Stars**：~26k
- **能力**：想 Idea — · 做实验 — · 写论文 △ · 画图 —
- **简介**：自主 deep research agent，能进行多步 web 检索并生成 5–6 页研究报告；本质是深度检索 + 报告生成工具，非科研实验闭环。

---

## ResearchClaw 家族（名字直接带 ResearchClaw 的项目）

| 项目 | Stars | 定位 |
|------|------:|------|
| [AutoResearchClaw](https://github.com/aiming-lab/AutoResearchClaw) | ~9.6k | 全自动 idea-to-paper 流水线（主干项目） |
| [ResearchClaw](https://github.com/ymx10086/ResearchClaw) | ~213 | 本地优先 Research OS：论文管理、实验追踪、多渠道接入 |
| [Research Claw](https://github.com/nanoAgentTeam/research-claw) | ~61 | 自托管科研助手：Overleaf 同步、文献搜索、deadline 跟踪 |
| [Noietch/ResearchClaw](https://github.com/Noietch/ResearchClaw) | ~53 | AI-Powered Research 桌面端应用 |
| [Research-Claw](https://github.com/wentorai/Research-Claw) | ~391 | 全栈科研助手："why can't everyone be a PI?" |
| [Prismer](https://github.com/Prismer-AI/Prismer) | ~1k | 自称 "Open Source Research Claw"：PDF/citation graph、LaTeX、多 Agent 协作 |

**不计入独立变种：**
- `researchclaw-skill` — 仅是 AutoResearchClaw 23-stage pipeline 的封装层
- `ResearchClawBench` — Benchmark 评测套件，非 Agent 产品

---

## 平台型 / Swarm 型（补充）

| 项目 | 简介 |
|------|------|
| [ScienceClaw + Infinite](https://github.com/Zaoqu-Liu/ScienceClaw) | 分布式 autonomous scientific investigation 框架，独立 Agent 在共享生态中协同研究 |
| [AgentRxiv](https://agentrxiv.github.io/) | 自主研究 Agent 专用的 preprint server，让不同 Agent 的研究成果可累积复用 |

---

## 快速 Clone

```bash
# 第一梯队：全流程闭环
git clone https://github.com/aiming-lab/AutoResearchClaw.git
git clone https://github.com/SakanaAI/AI-Scientist.git
git clone https://github.com/SakanaAI/AI-Scientist-v2.git

# 第二梯队：实验+写作
git clone https://github.com/HKUDS/AI-Researcher.git
git clone https://github.com/jarrycyx/openlens-ai.git
git clone https://github.com/eurekaclaw/eurekaclaw.git

# 第三梯队：工具链/半自动
git clone https://github.com/SamuelSchmidgall/AgentLaboratory.git
git clone https://github.com/JinheonBaek/ResearchAgent.git
git clone https://github.com/assafelovic/gpt-researcher.git

# ResearchClaw 家族
git clone https://github.com/ymx10086/ResearchClaw.git
git clone https://github.com/nanoAgentTeam/research-claw.git
git clone https://github.com/wentorai/Research-Claw.git
```
