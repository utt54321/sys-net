# 第 7 讲：TLBs & More Page Tables

- **所属课程**：CS 423 Operating System Design（UIUC，Fall 2026）
- **讲次**：第 7 讲 / 共 22 讲
- **日期**：2026 年 9 月 22 日（课程页面标注 9/22）
- **主题**：TLBs & More Page Tables
- **本地文件名**：`slides.pdf`
- **原始 slides URL**：https://cs423-uiuc.github.io/fall26/slides/07.pdf
- **录像链接**：课程页面未提供录像

## 内容要点

- 多级页表：用层级结构压缩页表空间开销
- 反向页表与哈希页表等替代设计
- 大页（huge pages）与页表遍历成本
- 现代地址翻译架构（EMT 论文）的工程实践

## 相关阅读

- OSTEP CH 19《Paging: Faster Translations (TLBs)》：https://pages.cs.wisc.edu/~remzi/OSTEP/vm-tlbs.pdf
- OSTEP CH 20《Paging: Smaller Tables》：https://pages.cs.wisc.edu/~remzi/OSTEP/vm-smalltables.pdf
- C4 阅读：New Translation Arch（9/29 截止）
- C4/延伸阅读：New Translation Arch（EMT） —— https://tianyin.github.io/pub/emt.pdf

---
返回：[课程总览](../README.md)