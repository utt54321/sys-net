# 第 3 讲：Process Scheduling

- **所属课程**：CS 423 Operating System Design（UIUC，Fall 2026）
- **讲次**：第 3 讲 / 共 22 讲
- **日期**：2026 年 9 月 1 日（课程页面标注 9/1）
- **主题**：Process Scheduling
- **本地文件名**：`slides.pdf`
- **原始 slides URL**：https://cs423-uiuc.github.io/fall26/slides/03.pdf
- **录像链接**：课程页面未提供录像

## 内容要点

- 调度基本指标：周转时间（turnaround）、响应时间（response）、公平性
- FIFO、SJF/STCF、RR 等基本策略及其取舍
- MLFQ 多级反馈队列：优先级动态调整、时间片分配、防饥饿规则
- 调度器实现需要兼顾吞吐与交互延迟

## 相关阅读

- OSTEP CH 7《Scheduling: Introduction》：http://pages.cs.wisc.edu/~remzi/OSTEP/cpu-sched.pdf
- OSTEP CH 8《Scheduling: The Multi-Level Feedback Queue》：http://pages.cs.wisc.edu/~remzi/OSTEP/cpu-sched-mlfq.pdf
- MP：UNIX（9/8 截止）
- C4/延伸阅读：UNIX（ACM DL） —— https://dl.acm.org/doi/10.1145/361011.361061

---
返回：[课程总览](../README.md)