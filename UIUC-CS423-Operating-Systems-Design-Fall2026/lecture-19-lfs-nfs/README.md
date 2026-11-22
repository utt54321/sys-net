# 第 19 讲：LFS & NFS

- **所属课程**：CS 423 Operating System Design（UIUC，Fall 2026）
- **讲次**：第 19 讲 / 共 22 讲
- **日期**：2026 年 11 月 19 日（课程页面标注 11/19）
- **主题**：LFS & NFS
- **本地文件名**：`slides.pdf`
- **原始 slides URL**：https://cs423-uiuc.github.io/fall26/slides/19.pdf
- **录像链接**：课程页面未提供录像

## 内容要点

- 日志收尾：元数据日志与全数据日志的差异
- LFS：把所有写入顺序化为追加日志
- inode 映射表与段清理（segment cleaning）
- LFS 的写放大与清理策略

## 相关阅读

- OSTEP CH 43《Log-structured File Systems》：https://pages.cs.wisc.edu/~remzi/OSTEP/file-lfs.pdf

---
返回：[课程总览](../README.md)