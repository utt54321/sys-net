# 第 11 讲：Locks

- **所属课程**：CS 423 Operating System Design（UIUC，Fall 2026）
- **讲次**：第 11 讲 / 共 22 讲
- **日期**：2026 年 10 月 8 日（课程页面标注 10/8）
- **主题**：Locks
- **本地文件名**：`slides.pdf`
- **原始 slides URL**：https://cs423-uiuc.github.io/fall26/slides/11.pdf
- **录像链接**：课程页面未提供录像

## 内容要点

- 锁的正确性：互斥与公平性（starvation）
- 基于硬件的原子指令构建锁
- 两阶段锁、细粒度锁与锁粒度权衡
- 使用锁的常见陷阱：死锁、锁护送（lock convoy）

## 相关阅读

- OSTEP CH 28《Locks》：https://pages.cs.wisc.edu/~remzi/OSTEP/threads-locks.pdf
- OSTEP CH 29《Lock-based Concurrent Data Structures》：https://pages.cs.wisc.edu/~remzi/OSTEP/threads-locks-usage.pdf

---
返回：[课程总览](../README.md)