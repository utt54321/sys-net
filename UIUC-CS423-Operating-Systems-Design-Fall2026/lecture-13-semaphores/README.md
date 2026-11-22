# 第 13 讲：Semaphore

- **所属课程**：CS 423 Operating System Design（UIUC，Fall 2026）
- **讲次**：第 13 讲 / 共 22 讲
- **日期**：2026 年 10 月 15 日（课程页面标注 10/15）
- **主题**：Semaphore
- **本地文件名**：`slides.pdf`
- **原始 slides URL**：https://cs423-uiuc.github.io/fall26/slides/13.pdf
- **录像链接**：课程页面未提供录像

## 内容要点

- 信号量：P/V（sem_wait / sem_post）原语
- 用信号量实现互斥与顺序控制
- 经典同步问题：生产者-消费者、读者-写者、哲学家就餐
- 常见并发缺陷：原子性违反、顺序违反、死锁

## 相关阅读

- OSTEP CH 31《Semaphores》：https://pages.cs.wisc.edu/~remzi/OSTEP/threads-sema.pdf
- OSTEP CH 32《Common Concurrency Problems》：https://pages.cs.wisc.edu/~remzi/OSTEP/threads-bugs.pdf

---
返回：[课程总览](../README.md)