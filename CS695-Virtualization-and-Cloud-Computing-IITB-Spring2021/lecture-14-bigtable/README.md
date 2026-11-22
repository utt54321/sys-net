# Lecture 14 — Cloud storage: semi-structured data: Bigtable（Bigtable 半结构化存储）

| 项目 | 内容 |
| --- | --- |
| 标题 | Cloud storage: semi-structured data: Bigtable（Bigtable 半结构化存储） |
| 所属课程 | CS695: Virtualization and Cloud Computing（IIT Bombay，Spring 2021） |
| 讲次 | Lecture 14 / 16 |
| 日期 | 2021-03-29 |
| 主题 | Cloud storage: semi-structured data: Bigtable |

## 本地文件

- `slides.pdf` — 原始文件名 `14-bigtable.pdf`

## 原始链接

- Slides: https://www.cse.iitb.ac.in/~mythili/teaching/cs695_spring2021/slides_pdf/14-bigtable.pdf
- 录像（YouTube）: https://youtu.be/vHTGhYK7Xjo

## 内容要点

- 稀疏、分布式、持久化的多维有序映射
- Tablet 划分与 SSTable/Memtable
- 依赖 GFS 与 Chubby 的分层设计
- LSM 树式的写入路径

## 相关阅读

- 论文：Bigtable: A Distributed Storage System for Structured Data（本地 `papers/bigtable.pdf`，[原始链接](https://www.cse.iitb.ac.in/~mythili/teaching/cs695_spring2021/papers/bigtable.pdf)）
- 论文：The Chubby lock service for loosely-coupled distributed systems（本地 `papers/chubby.pdf`，[原始链接](https://www.cse.iitb.ac.in/~mythili/teaching/cs695_spring2021/papers/chubby.pdf)）
- 论文：The Google File System（本地 `papers/gfs.pdf`，[原始链接](https://www.cse.iitb.ac.in/~mythili/teaching/cs695_spring2021/papers/gfs.pdf)）

- 课程主页：https://www.cse.iitb.ac.in/~mythili/teaching/cs695_spring2021/index.html
