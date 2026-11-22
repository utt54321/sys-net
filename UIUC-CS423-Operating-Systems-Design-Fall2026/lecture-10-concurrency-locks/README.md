# 第 10 讲：Intro to Concurrency, Locks

- **所属课程**：CS 423 Operating System Design（UIUC，Fall 2026）
- **讲次**：第 10 讲 / 共 22 讲
- **日期**：2026 年 10 月 6 日（课程页面标注 10/6）
- **主题**：Intro to Concurrency, Locks
- **本地文件名**：`slides.pdf`
- **原始 slides URL**：https://cs423-uiuc.github.io/fall26/slides/10.pdf
- **录像链接**：课程页面未提供录像

## 内容要点

- 线程与进程的区别：地址空间共享 vs 隔离
- 并发编程 API：pthread_create / join、竞态条件
- 锁的基本实现：test-and-set、compare-and-swap、fetch-and-add
- 自旋锁与阻塞锁的适用场景

## 相关阅读

- OSTEP CH 26《Concurrency: An Introduction》：https://pages.cs.wisc.edu/~remzi/OSTEP/threads-intro.pdf
- OSTEP CH 27《Interlude: Thread API》：https://pages.cs.wisc.edu/~remzi/OSTEP/threads-api.pdf
- OSTEP CH 28《Locks》：https://pages.cs.wisc.edu/~remzi/OSTEP/threads-locks.pdf
- C4 阅读：Mesa monitors（10/13 截止）
- C4/延伸阅读：Mesa monitors（ACM DL） —— https://dl.acm.org/citation.cfm?id=358824

---
返回：[课程总览](../README.md)