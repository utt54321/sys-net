# Scalable AI（可扩展人工智能）

| 项目 | 内容 |
|---|---|
| 课程名 | Scalable AI: Bridging Theory, Understanding, and Practice / 可扩展人工智能 |
| 课程号 | EE 290 / 194 |
| 学校 | UC Berkeley（加州大学伯克利分校）EECS |
| 教师 | Prof. Anant Sahai、Prof. Jiantao Jiao |
| 助教 | Haocheng Xi（GSI）、Paul Zhou（GSI）；Venkat Srinivasan（NVIDIA） |
| 学期 | Spring 2026 |
| 上课时间/地点 | 周二、周四 9:30–11:00，521 Cory Hall |
| 课程主页 | https://scalable-ai.eecs.berkeley.edu/S2026/ |
| 录像 | YouTube playlist（需 Berkeley 邮箱访问）：https://www.youtube.com/playlist?list=PLnocShPlK-FtamE4EYyDvPCKGT0DAJOwN |
| 教材 | 无单一教材；以课程 slides 与官方推荐阅读为主（如 How to Scale Your Model / Scaling Book） |
| 课程资源 | `syllabus.pdf`、`research-directions.pdf`（官方 PDF） |

## 课程简介

本课程把大规模 AI 视为一项端到端的工程学科：模型是一张必须被训练、特化、评估、部署、监控并持续迭代的计算图，而这一切都受硬件、数据与服务经济性的硬约束。

课程的中心问题是：当硬件约束、软件栈与优化动态共同决定模型行为与性能时，如何构建、训练并部署大规模 AI 系统。

课程按生命周期展开：体系结构 → 预训练 → 后训练 → 高效推理 → 应用 → 研究前沿（research greenfields）。

课程包含作业（并行/预训练/后训练/推理与服务）、期中检查、小组项目、项目报告与海报展示等环节。

## Lecture 索引

| 编号 | 主题 | 日期 | 材料 |
|---|---|---|---|
| 01 | Course Overview and the Modern AI Stack | 2026-01-20 | `slides.pdf` |
| 02 | All About Performance | 2026-01-22 | `slides.pdf` |
| 03 | Architectures to Break Bottlenecks | 2026-01-29 | `slides.pdf` |
| 04 | Parallelism Strategies | 2026-01-30 | `slides.pdf`；客座：Venkat Srinivasan（NVIDIA） |
| 05 | NeMo AutoModel | 2026-02-03 | 仅 PPTX（未下载）；客座：Hemil Desai、Zhiyu Li |
| 06 | Introduction to Pre-Training | 2026-02-05 | `slides.pdf` |
| 07 | Powering Pre-Training: NeMo Curator | 2026-02-10 | `slides.pdf`；客座：Sarah Yurick、Abhinav Garg |
| 08 | Case Study: The Pre-Training of Nano-V3 | 2026-02-12 | `slides.pdf`；客座：Roger Waleffe（NVIDIA） |
| 09 | Optimizer Fundamentals | 2026-02-17 | `slides.pdf` |
| 10 | Looking To The Future: Emerging Optimizers | 2026-02-19 | 仅 PPTX（未下载）；客座：Boxiang Wang |
| 11 | Looking To The Future: Synthetic Data Powering Pre-Training | 2026-02-24 | `slides-part1.pdf`、`slides-part2.pdf`；客座：Eric Tramel、Maarten Van Segbroeck |
| 12 | Intro To the LLM Post-Training Lifecycle and Evaluation | 2026-02-26 | `slides-part1.pdf`、`slides-part2.pdf` |
| 13 | The Data Powering Post-Training: SFT Data Engineering and RL Environments | 2026-03-03 | `slides.pdf` |
| 14 | NeMo Data Designer Deep Dive | 2026-03-05 | `slides.pdf`；客座：Dhruv Nathawani、Yev Meyer |
| 15 | Reinforcement Learning Algorithms Powering Near-Frontier Post-Training | 2026-03-10 | `slides.pdf` |
| 16 | Case Study: Post-Training of Nemotron-NanoV3 and NeMoRL | 2026-03-12 | `slides-part1.pdf`、`slides-part2.pdf`；客座：Venkat Srinivasan、Gerald Shen |
| 17 | Deployment Preparation: Speculative Decoding, Quantization, Pruning, and NAS | 2026-03-17 | `slides.pdf` |
| 18 | Fundamentals and Overview of High-Performance Inference Frameworks | 2026-03-19 | `slides.pdf` |
| 19 | High-Performance Inference using Dynamo and TRT-LLM | 2026-03-31 | `slides-part1.pdf`、`slides-part2.pdf` |
| 20 | High-Performance Inference using vLLM and SGLang | 2026-04-02 | `slides-part1.pdf` |
| 21 | Fundamentals of Context Engineering | 2026-04-07 | `slides.pdf` |
| 22 | Agentic Applications | 2026-04-09 | `slides.pdf` |
| 23 | Safety Guardrails | 2026-04-14 | `slides.pdf` |
| 24 | Diffusion Language Models | 2026-04-16 | `slides.pdf` |
| 25 | Harness Engineering | 2026-04-21 | `slides.pdf` |
| 26 | Multi-Agent Systems and Architecture | 2026-04-23 | 官方未发布 |

## 目录说明

- `lecture-01` … `lecture-26`：按官方 Consolidated Schedule 的讲次编号建目录；每讲一个 `README.md`，有 PDF 时含 `slides.pdf`（多份则为 `slides-part1.pdf` 等）。
- Lecture 02 在 1 月 27 日另有 Lecture Extension（无独立 slides），已在 L02 README 中注明。
- Lecture 05、10 官方只提供 `.pptx`，按“仅下载真实 PDF”的规则未下载，README 中保留链接说明。
- Lecture 26 官方未提供 slides 链接。
- Lecture 20 官方给出 Part 1 / Part 2 两份 slides，但 `lecture_20_2.pdf` 在服务器上返回 404（页面链接失效），本地只有 Part 1。
- 页面部分链接文件名含下划线（如 `lecture_19_1.pdf`），已按页面实际地址下载。
- 课程根目录的 `syllabus.pdf` 与 `research-directions.pdf` 来自官方 Resources 区。

## 页面结构说明

- 官方日程为 “Consolidated Schedule” 表格，日期、Lecture 标题、Key topics 与 Recommended Readings 均从该表提取。
- 表中还包含 Spring Recess 与各类截止日期（Milestone）行，本归档只对 L1–L26 建讲次目录。

