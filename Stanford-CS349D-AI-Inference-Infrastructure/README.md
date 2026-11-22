# CS349D: AI Inference Infrastructure（人工智能推理基础设施）

| 项目 | 内容 |
|---|---|
| 课程名 | CS349D: AI Inference Infrastructure / 人工智能推理基础设施 |
| 学校 | Stanford University（斯坦福大学） |
| 教师 | Christos Kozyrakis（Instructor）；助教 Zhiqiang Xie、Swapnil Gandhi |
| 学期 | Spring 2026 |
| 上课时间/地点 | 周一、周三 13:30–14:50，160-124 |
| 课程主页 | http://web.stanford.edu/class/cs349d/ |
| 课程类型 | 论文研讨课（research seminar），无 lecture slides |
| 教材 | 无固定教材；采用论文阅读清单（每讲 required/optional） |

## 课程简介

随着大语言模型（LLM）与 agentic AI 的快速普及，高效推理已成为关键的系统挑战。本课程是一门研究型研讨课，聚焦大规模 AI 推理背后的基础设施与系统，涵盖在生产环境中高效、低成本地服务 LLM 所需的技术、架构与工程决策。

课程以论文讨论为主：学生需在课前阅读 required 论文并在 Gradescope 提交摘要，每讲由两名学生负责介绍论文并主持讨论，另有两名学生负责记录笔记；部分讲次邀请工业界专家做 guest lecture。

课程的另一条主线是动手实现：学生将逐步构建一个 mini serving engine，在真实负载上达到可接受的性能，并通过四个里程碑叠加数据/张量并行、连续批处理与 PagedAttention、上下文缓存与 chunked prefill，以及一个高级特性。

暂定评分：coursework 50%、主讲一次 25%、课堂参与 25%。

## Lecture 索引

| 编号 | 主题 | 日期 | 材料 |
|---|---|---|---|
| 01 | Introduction | Mon Mar 30 | 论文 3 篇（见 `papers/`） |
| 02 | Parallelism | Wed Apr 1 | 论文 5 篇（见 `papers/`） |
| 03 | Serving Engines | Mon Apr 6 | 论文 2 篇（见 `papers/`） |
| 04 | Programming Assignment Meeting 1 | Wed Apr 8 | 无指定论文；编程作业答疑 |
| 05 | Batching | Mon Apr 13 | 论文 2 篇（见 `papers/`） |
| 06 | Disaggregation | Wed Apr 15 | 论文 4 篇（见 `papers/`） |
| 07 | Speculative Decoding | Mon Apr 20 | 论文 2 篇（见 `papers/`） |
| 08 | SGLang (Ying Sheng, founder of RadixArk) | Wed Apr 22 | 无指定论文；客座讲座 |
| 09 | Context Management | Mon Apr 27 | 论文 3 篇（见 `papers/`） |
| 10 | Efficient Attention | Wed Apr 29 | 论文 4 篇（见 `papers/`） |
| 11 | Hybrid LLMs | Mon May 4 | 论文 3 篇（见 `papers/`） |
| 12 | Mixture of Experts | Wed May 6 | 论文 4 篇（见 `papers/`） |
| 13 | Programming Assignment Meeting 2 | Mon May 11 | 无指定论文；编程作业答疑 |
| 14 | Load Balancing & Routing | Wed May 13 | 论文 2 篇（见 `papers/`） |
| 15 | Agentic Workflows | Mon May 18 | 论文 4 篇（见 `papers/`） |
| 16 | Memory | Wed May 20 | 论文 4 篇（见 `papers/`） |
| 17 | Reinforcement Learning | Wed May 27 | 论文 3 篇（见 `papers/`） |
| 18 | Multi-tenancy | Mon Jun 1 | 论文 3 篇（见 `papers/`） |
| 19 | Project Presentations | Wed Jun 3 | 无指定论文；项目展示 |

## Mini Serving Engine 里程碑

| 里程碑 | 内容 | 截止日期 | 对应讲次 |
|---|---|---|---|
| Milestone 1 | 数据并行与张量并行（提升吞吐、支持更大模型） | 2026-04-20 | Lecture 07 |
| Milestone 2 | 连续批处理与 PagedAttention（提升资源利用率） | 2026-05-04 | Lecture 11 |
| Milestone 3 | 上下文缓存与分块 prefill（降低延迟、提升吞吐） | 2026-05-18 | Lecture 15 |
| Milestone 4 | 高级特性：投机解码 / 层次化上下文缓存 / prefill-decode 分离 / 自选特性 | 2026-06-01 | Lecture 18 |

课程提供 starter notebook、benchmark 脚本与共享实验环境；后续里程碑必须在之前里程碑的基础上增量实现，所有特性需保持兼容。

## 目录结构

- `lecture-01` … `lecture-19`：19 个有编号的讲次（跳过 5 月 25 日 Memorial Day 无课），含 1 次客座讲座（Lecture 08）与 1 次项目展示（Lecture 19），无 slides。
- `papers/`：全部 required/optional 论文（共 43 个本地 PDF），按讲次分组，见 `papers/README.md`。

## 备注

- 课程日程由 `schedule.js` 渲染，本归档据该文件整理（`http://web.stanford.edu/class/cs349d/schedule.js`）。
- ACM Digital Library 与部分 USENIX 会议页无可直链 PDF 的条目仅保留链接。
- 本课程不提供讲稿（slides），因此各讲目录仅有 README。

