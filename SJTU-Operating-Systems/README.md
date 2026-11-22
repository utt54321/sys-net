# 操作系统（本科）Operating Systems (Undergraduate) · 上海交通大学 · 2022 春季

| 项目 | 内容 |
| --- | --- |
| 课程名 | Operating Systems (Undergraduate) / 操作系统（本科） |
| 学校 | 上海交通大学，电子信息与电气工程学院 计算机科学与工程系 |
| 教师 | 过敏意（Minyi Guo，guo-my@cs.sjtu.edu.cn）、吴晨涛（Chentao Wu，wuct@cs.sjtu.edu.cn）；助教 Xinyu Wang、Mizhipeng Zhang |
| 学期 | Spring 2022（页面标题） |
| 课程主页 | https://www.cs.sjtu.edu.cn/~wuct/os/index.html |
| 教学大纲/进度 | [syllabus.html](https://www.cs.sjtu.edu.cn/~wuct/os/syllabus.html) |
| 上课时间/地点 | 周一 22:00–23:40、周四 14:00–15:40（页面原文）；下院（Lower Building）312 室 |
| 课时安排 | 共 80 课时（48 讲授 + 32 项目），第 1–16 周 |
| 先修要求 | 程序设计（C/C++/Python/Java）、数据结构、计算机组成 |

## 课程简介

本课程系统介绍操作系统，目标是让学生理解从芯片到应用的整体工作方式。

课程覆盖机器组成（处理器、主存、I/O 架构）与存储层次（缓存、虚拟内存），以及它们在硬件与软件中的实现。

核心内容包括进程、线程、同步、内存管理与文件管理等操作系统机制。

课程配有 8 个上机项目（如 Linux 内核模块、多线程排序、调度算法），并要求学生能作为开发者或系统使用者做出有依据的技术选择。

## 教材与参考书

- **Operating System Concepts（9th Edition，中文版）**，Abraham Silberschatz 等 —— [京东链接](https://item.jd.com/12395269.html)
- **Operating System Concepts（7th Edition）**，Abraham Silberschatz 等 —— [京东链接](https://item.jd.com/10000610.html)
- **Operating System Concepts（7th Edition，中文版）**，Abraham Silberschatz 等 —— [京东链接](https://item.jd.com/10553956.html)
- 课程页面另附教材封面图（OSConcepts / OSConcepts-Chinese / OSConcepts10 / OSConcepts-Chinese9）。

## 讲次索引

| 编号 | 主题 | 日期 | 材料 |
| --- | --- | --- | --- |
| [00](lecture-00-course-introduction/README.md) | 课程介绍 | 未标注 | `introduction.pdf`（未下载） |
| [01](lecture-01-intro-to-operating-systems/README.md) | 操作系统导论 | 未标注 | `lec1-OS.pdf`（未下载） |
| [02](lecture-02-os-structures/README.md) | 操作系统结构 | 未标注 | `lec2-OS.pdf`（未下载） |
| [03](lecture-03-processes/README.md) | 进程 | 未标注 | `lec3-OS.pdf`（未下载） |
| [04](lecture-04-threads/README.md) | 线程 | 未标注 | `lec4-OS.pdf`（未下载） |
| [05](lecture-05-cpu-scheduling/README.md) | CPU 调度 | 未标注 | `lec5-OS.pdf`（未下载） |
| [06](lecture-06-process-synchronization-1/README.md) | 进程同步 I | 未标注 | `lec6-OS.pdf`（未下载） |
| [07](lecture-07-process-synchronization-2/README.md) | 进程同步 II | 未标注 | `lec7-OS.pdf`（未下载） |
| [08](lecture-08-deadlocks/README.md) | 死锁 | 未标注 | `lec8-OS.pdf`（未下载） |
| [09](lecture-09-main-memory/README.md) | 主存管理 | 未标注 | `lec9-OS.pdf`（未下载） |
| [10](lecture-10-virtual-memory/README.md) | 虚拟内存 | 未标注 | `lec10-OS.pdf`（未下载） |
| [11](lecture-11-mass-storage/README.md) | 大容量存储 | 未标注 | `lec11-OS.pdf`（未下载） |
| [12](lecture-12-io-systems/README.md) | I/O 系统 | 未标注 | `lec12-OS.pdf`（未下载） |
| [13](lecture-13-file-system-interface/README.md) | 文件系统接口 | 未标注 | `lec13-OS.pdf`（未下载） |
| [14](lecture-14-file-system-implementation/README.md) | 文件系统实现 | 未标注 | `lec14-OS.pdf`（未下载） |
| [15](lecture-15-file-system-internals/README.md) | 文件系统内部机制 | 未标注 | [slides.pdf](lecture-15-file-system-internals/slides.pdf) |
| [16](lecture-16-virtual-machines/README.md) | 虚拟机 | 未标注 | `lec18-OS.pdf`（未下载） |
| [17](lecture-17-summary/README.md) | 课程总结 | 未标注 | `summary.pdf`（未下载） |

## 作业与考试

- 成绩构成（syllabus 原文）：作业 10%、随堂测验 15%、项目 15%、期末考试 60%。
- 随堂测验：第 1 次 4 月 2 日（第 5 周，第 1–3 章）；第 2 次 4 月 23 日（第 8 周，第 4–7 章）；第 3 次 5 月 14 日（第 11 周，第 8–10 章）。
- 作业按教材章布置（第 1–... 章，逐周截止），题目编号见 [assignments.html](https://www.cs.sjtu.edu.cn/~wuct/os/assignments.html)。
- 项目：第 13–16 周进行，共 8 个，包括 Linux 内核模块、UNIX Shell 编程与任务信息内核模块、多线程/Fork-Join 排序、调度算法等，需提交报告与源码，见 [project.html](https://www.cs.sjtu.edu.cn/~wuct/os/project.html)。
- 迟交：每迟一天扣 10%，最多延 3 天，逾期 72 小时后不再接收；生病需提供医生证明。
- 禁止抄袭：发现抄袭该次作业记零分，并可能追加处理。

## 其他说明

**页面结构说明**：讲义只通过 syllabus 表格逐条链接到 `slides/*.pdf`；`slides/` 目录本身禁止列目录（HTTP 403），无法一次性抓取，只能按表格链接逐个下载。

**编号跳号**：表格中讲次 22「File System Internals」直接复用 `lec14-OS.pdf`（与第 21 讲同一份）；讲次 23「Virtual Machines」直接跳到 `lec18-OS.pdf`，页面不存在 lec15–lec17 的讲义文件。归档按页面行序连续编号，并在对应 README 标注官方讲次号。

**讲次合并**：页面把部分主题合并为一次（如 3-4 Processes、6-7 CPU Scheduling、8-9/10-11 同步、12-13 死锁、14-15 主存、16-17 虚存），每行对应一份讲义，归档为一讲。

**格式**：全部讲义均为 PDF（PDF 1.x），页面未提供 PPT/PPTX 附件，也未提供课堂录像链接。

页面未标注每次课的具体日期，仅有周次与测验日期。

## 目录说明

- 每讲一个 `lecture-NN-<slug>/` 目录，内含该讲 `README.md` 与讲义文件；文件名统一为 ASCII。
- 所有材料版权归原作者与课程方所有，仅用于个人学习归档。
