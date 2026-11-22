# 第 21 讲：GFS

- **所属课程**：CS 423 Operating System Design（UIUC，Fall 2026）
- **讲次**：第 21 讲 / 共 22 讲
- **日期**：2026 年 12 月 3 日（课程页面标注 12/3）
- **主题**：GFS
- **本地文件名**：（未下载，见下方原始链接）
- **原始 slides URL**：https://cs423-uiuc.github.io/fall26/slides/21.pdf
- **录像链接**：课程页面未提供录像

## 内容要点

- GFS 设计目标：大文件、廉价商用机器、容错
- 单 Master + ChunkServer 架构与 chunk 副本
- 租约（lease）、追加（append）与记录追加原子性
- 面向数据中心顺序扫描的工作负载优化

## 相关阅读

- OSTEP CH 49《Sun's Network File System (NFS)》：https://pages.cs.wisc.edu/~remzi/OSTEP/dist-nfs.pdf
- OSTEP CH 45《Data Integrity and Protection》：https://pages.cs.wisc.edu/~remzi/OSTEP/file-integrity.pdf
- C4/延伸阅读：GFS 论文（SOSP 2003） —— https://research.google.com/archive/gfs-sosp2003.pdf

> 注意：该讲义的原始链接在归档时无法下载为有效 PDF（HTTP 404），仅保留链接。

---
返回：[课程总览](../README.md)