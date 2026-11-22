# Advanced Topics in Communication Networks（高级通信网络专题）

| 项目 | 内容 |
|---|---|
| 课程名 | Advanced Topics in Communication Networks / 高级通信网络专题 |
| 课程号 | 227-0575-00L |
| 学校 | ETH Zürich（苏黎世联邦理工学院） |
| 教师 | Prof. Laurent Vanbever；协调人 Romain Jacob；助教 Valerio Torsiello、Ioannis Protogeros、Tibor Schneider 等 |
| 学期 | Fall 2026（Herbstsemester 2026） |
| 课程主页 | https://adv-net.ethz.ch/ |
| 上课时间/地点 | 讲座：周三 14:15–16:00，ETZ E 8；练习：周二 16:15–18:00，ML E 12 |
| 学分/考核 | 6 ECTS；180 分钟闭卷笔试 |
| 教材 | 无指定教材；以讲稿与练习材料为主（课程信息与材料亦发布于 Moodle） |
| 录像 | ETH Video Portal：https://video.ethz.ch/lectures/d-itet/2026/autumn/227-0575-00L |

## 课程简介

本课程从理论与工程两个角度覆盖计算机网络的高级研究课题，核心问题是如何让网络变得更好。

课程沿五条主线展开：可扩展性（数千台路由器、数百万条路由）、可靠性（故障后亚秒级收敛并能形式化验证配置正确性）、灵活性（可编程数据平面，细到每个报文的处理）、性能（流量工程、负载均衡、传输与拥塞控制）以及可持续性（度量并降低网络碳足迹）。

课程还讨论网络如何更好地支撑现代应用（视频流、AI）、新部署形态（空间网络，如 Starlink）与新技术（光网络）。

课程强调动手实践：学生在仿真网络环境中实验这些技术，并在实验中自行实现部分机制。

学期分为两个阶段：约 10 周为课程讲授 + 练习/实验，随后约 4 周为小组项目（每组约 3 人），最后一周进行演示。

先修要求：Communication Networks（227-0120-00L）、Computer Networks（252-0064-00L）或同等课程；具备编程能力。

## Week 索引

| 编号 | 主题 | 日期 | 材料 |
|---|---|---|---|
| 01 | Introduction, Course organization. Routing scalability (Part 1) | 2026-09-16 | 2 份 slides |
| 02 | Routing scalability (Part 2). Forwarding scalability | 2026-09-22 | `slides.pdf` |
| 03 | Fast convergence | 2026-09-29 | `slides.pdf` |
| 04 | Network verification (Part 1): Routing algebras | 2026-10-06 | `slides.pdf` |
| 05 | Network verification (Part 2): Logic-based verification | 2026-10-13 | `slides.pdf` |
| 06 | Programmable data planes (P4) | 2026-10-20 | `slides.pdf` |
| 07 | Load balancing | 2026-10-27 | `slides.pdf` |
| 08 | Transport protocols | 2026-11-03 | `slides.pdf` |
| 09 | Congestion control | 2026-11-10 | `slides.pdf` |
| 10 | Networking for ML | 2026-11-17 | `slides.pdf` |
| 11 | Optics for networking | 2026-11-24 | 未发布 |
| 12 | Video streaming | 2026-12-01 | 未发布 |
| 13 | Space networking | 2026-12-08 | 未发布 |
| 14 | Sustainable networking | 2026-12-15 | 未发布 |

## 目录说明

- `lecture-01` … `lecture-14`：按官方 Week 1–14 建目录；Week 1 的 polybox 包含两份 slides（Introduction 与 Routing scalability Part 1），保存为 `slides-part1.pdf` 与 `slides-part2.pdf`。
- Week 11–14 官方仅给出主题、尚未发布材料，目录中只有 README。
- `exercises/`：Week 2–10 的练习、解答与讲义手稿（Week 6–8 为 GitLab 发布，仅列链接）。
- `exams/`：2021–2026 历年试卷，2024–2026 含官方解答。
- 单讲 README 中给出对应的 2024 transcript 链接。

## 页面结构说明

- 主页以 `Week 1`–`Week 14` 的周列表组织，每周含 Lecture 与 Exercise 两个区块。
- 页面下半部分仍保留 Fall 2025 的日程作为参考（注释块），本归档只取 Fall 2026 部分。
- 讲稿通过 polybox 分享链接分发，需在链接末尾加 `/download` 才能直接获取 PDF（已按此处理）。

