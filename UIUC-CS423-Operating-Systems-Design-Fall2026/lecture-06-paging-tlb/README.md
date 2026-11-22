# 第 6 讲：Paging, TLB

- **所属课程**：CS 423 Operating System Design（UIUC，Fall 2026）
- **讲次**：第 6 讲 / 共 22 讲
- **日期**：2026 年 9 月 17 日（课程页面标注 9/17）
- **主题**：Paging, TLB
- **本地文件名**：`slides.pdf`
- **原始 slides URL**：https://cs423-uiuc.github.io/fall26/slides/06.pdf
- **录像链接**：课程页面未提供录像

## 内容要点

- 分页地址转换全过程：VPN → PFN 的页表查找
- 页表项（PTE）字段：有效位、保护位、脏位、访问位
- TLB：地址转换缓存、空间/时间局部性、命中与缺失路径
- TLB 缺失处理与上下文切换时的 TLB 管理

## 相关阅读

- OSTEP CH 18《Paging: Introduction》：https://pages.cs.wisc.edu/~remzi/OSTEP/vm-paging.pdf
- OSTEP CH 19《Paging: Faster Translations (TLBs)》：https://pages.cs.wisc.edu/~remzi/OSTEP/vm-tlbs.pdf

---
返回：[课程总览](../README.md)