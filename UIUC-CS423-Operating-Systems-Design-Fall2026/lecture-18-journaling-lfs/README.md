# 第 18 讲：Journaling & LFS

- **所属课程**：CS 423 Operating System Design（UIUC，Fall 2026）
- **讲次**：第 18 讲 / 共 22 讲
- **日期**：2026 年 11 月 17 日（课程页面标注 11/17）
- **主题**：Journaling & LFS
- **本地文件名**：`slides.pdf`
- **原始 slides URL**：https://cs423-uiuc.github.io/fall26/slides/18.pdf
- **录像链接**：课程页面未提供录像

## 内容要点

- 崩溃一致性问题的来源：断电/崩溃导致的多块更新不原子
- FSCK：事后扫描与修复
- 日志（journaling）：预写日志、redo/undo、检查点
- 日志提交策略与性能权衡

## 相关阅读

- OSTEP CH 42《Crash Consistency: FSCK and Journaling》：https://pages.cs.wisc.edu/~remzi/OSTEP/file-journaling.pdf
- OSTEP CH 43《Log-structured File Systems》：https://pages.cs.wisc.edu/~remzi/OSTEP/file-lfs.pdf
- C4 阅读：LFS（12/1 截止）
- C4/延伸阅读：LFS（ACM DL） —— https://dl.acm.org/citation.cfm?id=121137

---
返回：[课程总览](../README.md)