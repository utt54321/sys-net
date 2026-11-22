# Lecture 03 — Techniques to design virtual machine monitors（VMM 设计技术）

| 项目 | 内容 |
| --- | --- |
| 标题 | Techniques to design virtual machine monitors（VMM 设计技术） |
| 所属课程 | CS695: Virtualization and Cloud Computing（IIT Bombay，Spring 2021） |
| 讲次 | Lecture 3 / 16 |
| 日期 | 2021-01-18 |
| 主题 | Techniques to design virtual machine monitors |

## 本地文件

- `slides.pdf` — 原始文件名 `03-vmm.pdf`

## 原始链接

- Slides: https://www.cse.iitb.ac.in/~mythili/teaching/cs695_spring2021/slides_pdf/03-vmm.pdf
- 录像（YouTube）: https://youtu.be/cVFyK1f5lDw

## 内容要点

- VMM/Hypervisor 的职责与分类（Type 1 / Type 2）
- CPU、内存、I/O 三类资源的虚拟化思路
- 陷入-模拟、二进制翻译与硬件辅助
- VMM 设计的性能与兼容性权衡

## 相关阅读

- 论文：Virtual Machine Monitors: Current Technology and Future Trends（本地 `papers/vmmtrends.pdf`，[原始链接](https://www.cse.iitb.ac.in/~mythili/teaching/cs695_spring2021/papers/vmmtrends.pdf)）
- 外部阅读：http://pages.cs.wisc.edu/~remzi/OSTEP/vmm-intro.pdf
- 课程主页：https://www.cse.iitb.ac.in/~mythili/teaching/cs695_spring2021/index.html
