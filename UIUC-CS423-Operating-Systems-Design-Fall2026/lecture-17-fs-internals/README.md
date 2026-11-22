# 第 17 讲：FS Internals

- **所属课程**：CS 423 Operating System Design（UIUC，Fall 2026）
- **讲次**：第 17 讲 / 共 22 讲
- **日期**：2026 年 11 月 10 日（课程页面标注 11/10）
- **主题**：FS Internals
- **本地文件名**：`slides.pdf`
- **原始 slides URL**：https://cs423-uiuc.github.io/fall26/slides/17.pdf
- **录像链接**：课程页面未提供录像

## 内容要点

- inode 结构与多级索引（直接/间接块）
- 文件读写路径：open、read、write、close
- 缓存与缓冲：页缓存、写回策略
- 文件系统实现中的空间分配与碎片问题

## 相关阅读

- OSTEP CH 39《Files and Directories》：https://pages.cs.wisc.edu/~remzi/OSTEP/file-intro.pdf
- OSTEP CH 40《File System Implementation》：https://pages.cs.wisc.edu/~remzi/OSTEP/file-implementation.pdf
- MP4 发布
- C4 阅读：FFS（11/17 截止）
- C4/延伸阅读：FFS（ACM DL） —— https://dl.acm.org/citation.cfm?id=990

---
返回：[课程总览](../README.md)