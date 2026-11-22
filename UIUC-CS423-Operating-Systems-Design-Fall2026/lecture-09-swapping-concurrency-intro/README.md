# 第 9 讲：Swapping, Intro to Concurrency

- **所属课程**：CS 423 Operating System Design（UIUC，Fall 2026）
- **讲次**：第 9 讲 / 共 22 讲
- **日期**：2026 年 9 月 29 日（课程页面标注 9/29）
- **主题**：Swapping, Intro to Concurrency
- **本地文件名**：`slides.pdf`
- **原始 slides URL**：https://cs423-uiuc.github.io/fall26/slides/09.pdf
- **录像链接**：课程页面未提供录像

## 内容要点

- 置换策略收尾：LRU 近似与抖动（thrashing）
- 完整虚拟内存系统：TLB + 多级页表 + 交换协同
- 并发引入：线程作为共享地址空间的执行单元
- 并发带来的原子性、可见性与顺序问题

## 相关阅读

- OSTEP CH 22《Beyond Physical Memory: Policies》：https://pages.cs.wisc.edu/~remzi/OSTEP/vm-beyondphys-policy.pdf
- OSTEP CH 23《Complete Virtual Memory Systems》：https://pages.cs.wisc.edu/~remzi/OSTEP/vm-complete.pdf
- OSTEP CH 26《Concurrency: An Introduction》：https://pages.cs.wisc.edu/~remzi/OSTEP/threads-intro.pdf
- C4 阅读：Huge pages（10/6 截止）
- C4/延伸阅读：Huge pages（OSDI'16） —— https://www.usenix.org/system/files/conference/osdi16/osdi16-kwon.pdf

---
返回：[课程总览](../README.md)