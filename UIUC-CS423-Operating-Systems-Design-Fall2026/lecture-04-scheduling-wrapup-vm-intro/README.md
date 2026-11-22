# 第 4 讲：Scheduling Wrap-up; Virtual Mem Intro

- **所属课程**：CS 423 Operating System Design（UIUC，Fall 2026）
- **讲次**：第 4 讲 / 共 22 讲
- **日期**：2026 年 9 月 8 日（课程页面标注 9/8）
- **主题**：Scheduling Wrap-up; Virtual Mem Intro
- **本地文件名**：`slides.pdf`
- **原始 slides URL**：https://cs423-uiuc.github.io/fall26/slides/04.pdf
- **录像链接**：课程页面未提供录像

## 内容要点

- 调度收尾：比例份额（lottery / stride）调度的随机化思想
- 地址空间抽象：为什么要为每个进程提供私有地址空间
- 虚拟内存目标：透明、高效、保护
- 从 CPU 虚拟化过渡到内存虚拟化的问题定义

## 相关阅读

- OSTEP CH 9《Scheduling: Proportional Share》：http://pages.cs.wisc.edu/~remzi/OSTEP/cpu-sched-lottery.pdf
- OSTEP CH 13《The Abstraction: Address Spaces》：http://pages.cs.wisc.edu/~remzi/OSTEP/vm-intro.pdf
- MP：Linux APIs（9/15 截止）
- C4/延伸阅读：The Linux API（ACM DL） —— https://dl.acm.org/doi/10.1145/2901318.2901341

---
返回：[课程总览](../README.md)