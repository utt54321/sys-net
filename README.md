# 系统与网络课程资料库

本目录收录 13 门操作系统 / 计算机网络 / 分布式系统 / AI 系统类课程，按课程 → 讲次 → 材料三层组织：

```
<课程>/
├── README.md              课程总览（教师、学期、教材、简介、lecture 索引表、作业考试）
├── lecture-NN-<topic>/
│   ├── README.md          本讲主题、日期、原始链接、录像、内容要点、相关阅读
│   └── slides.pdf         官方 slides（有则下载；多个文件时幻灯片分卷命名）
├── papers/                指定论文 / 阅读材料（部分课程）
├── exercises/             练习、习题课材料（部分课程）
├── review/                复习与考试材料（部分课程）
└── exams/                 历年考试卷（ETH）
```

无法直接下载的材料（YouTube 录像、GitLab 仓库、需登录的 ACM/LMS 页面等）统一记录在对应 README 的「原始链接 / 相关阅读」中。

## 课程索引

| # | 课程 | 学校 | 学期 | 讲次 | PDF | 特色目录 |
|---|------|------|------|------|-----|----------|
| 1 | [CS370: Operating Systems](CS370-Operating-Systems-CSU-Fall2025/README.md) | Colorado State University | Fall 2025 | 27 | 36 | `review/`（Help Session、复习指南） |
| 2 | [Operating Systems Design and Implementation](UMass-OS-Design-and-Implementation-Spring2020/README.md) | UMass Amherst | Spring 2020 | 22 | 44 | `review/`（含 scribe notes） |
| 3 | [CS695: Virtualization and Cloud Computing](CS695-Virtualization-and-Cloud-Computing-IITB-Spring2021/README.md) | IIT Bombay | Spring 2021 | 16 | 31 | `papers/`（15 篇经典论文） |
| 4 | [ENGR-E 516: Cloud Computing](ENGR-E516-Cloud-Computing-Indiana-Fall2025/README.md) | Indiana University | Fall 2025 | 27 | 34 | `papers/`（8 篇论文） |
| 5 | [Operating Systems（操作系统）](SJTU-Operating-Systems/README.md) | 上海交通大学 | Spring 2022 | 18 | 18 | — |
| 6 | [15-410: OS Design and Implementation](CMU-15-410-OS-Design-and-Implementation-Fall2019/README.md) | Carnegie Mellon University | Fall 2019 | 38 | 46 | — |
| 7 | [CS 423: Operating Systems Design](UIUC-CS423-Operating-Systems-Design-Fall2026/README.md) | UIUC | Fall 2026 | 22 | 26 | `exercises/` `papers/` `review/` |
| 8 | [10-414/714: Deep Learning Systems](CMU-10-414-714-Deep-Learning-Systems/README.md) | Carnegie Mellon University | — | 24 | 16 | — |
| 9 | [CS 640: Introduction to Computer Networks](UW-Madison-CS640-Computer-Networks-Spring2026/README.md) | UW–Madison | Spring 2026 | 27 | 27 | — |
| 10 | [CS349D: AI Inference Infrastructure](Stanford-CS349D-AI-Inference-Infrastructure/README.md) | Stanford University | Spring 2026 | 19 | 43 | `papers/`（论文研讨课） |
| 11 | [CSCI-GA.2262: Data Communications & Networks](NYU-CSCI-GA-2262-Data-Communications-Networks-Spring2026/README.md) | New York University | Spring 2026 | 15 | 15 | — |
| 12 | [Scalable AI: Bridging Theory, Understanding, and Practice](Berkeley-Scalable-AI-Spring2026/README.md) | UC Berkeley | Spring 2026 | 26 | 29 | — |
| 13 | [Advanced Topics in Communication Networks](ETH-Advanced-Topics-Communication-Networks-Fall2026/README.md) | ETH Zürich | Fall 2026 | 14 | 36 | `exercises/` `exams/` |

合计 **295 个讲次目录、401 份 PDF**。

## 使用说明

- 每个 lecture 目录都能独立阅读：README 说明本讲主题、原始出处与延伸阅读，slides 为官方原始文件。
- 论文研讨类课程（Stanford CS349D、CS695、ENGR-E516）的必读/选读论文已集中在 `papers/`，并在每讲 README 中标注必读（required）与选读（optional）。
- 官方尚未发布或链接失效的材料，均在对应 README 中标注原因，未用占位文件填充。

## 已知缺口

- UIUC CS423 第 20–22 讲、部分 MP slides 与模拟题：官方站点 404，未发布。
- CMU 15-410 第 36/37 讲：原链接指向 CMU 登录页，需校内认证。
- ETH Week 11–14：官方日程已列主题但尚未发布 slides（目录与占位说明已建）。
- Stanford CS349D 为论文研讨课，无 slides；以 `papers/` 中的论文代替。
- 少数材料（YouTube 录像、GitLab 仓库、ACM DL 论文、Google Docs）无法离线保存，仅在 README 中保留链接。

## 来源

课程清单来自飞书文档《系统+网络》：https://nrj73nk2h4.feishu.cn/docx/X63ydMNxMoqCKBxLatQc7OOsnZf
