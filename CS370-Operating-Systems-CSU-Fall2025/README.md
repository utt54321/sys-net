# CS370: Operating Systems

**中文名**：操作系统
**英文名**：CS370: Operating Systems
**学校**：Colorado State University（科罗拉多州立大学），Department of Computer Science
**教师**：Yashwant Malaiya（Office: Room CSB 356；Office Hours: Wed 3-4 PM；malaiya@colostate.edu）
**学期**：Fall 2025
**课程主页**：https://www.cs.colostate.edu/~cs370/Fall25/index.html
**Schedule 页面**：https://www.cs.colostate.edu/~cs370/Fall25/schedule.html
**授课形式**：Sec 001 周二/周四 14:00-15:15，Biology 136；Sec 801 为线上班（课后 1-2 小时在 Canvas 发布录像）
**助教**：Cameron Suess、Anindya Roy Chowdury、Khondaker Masfiq Reza（研究生 TA）；Wilson Valentine、Kushal Reddy Alimineti、Zacharie Guida（本科 TA）

## 教材与参考书

- **主教材**：Silberschatz, Galvin, Gagne. *Operating Systems Concepts*, 10th Edition. John Wiley & Sons. ISBN-13: 978-1119456339（页面记号 [SCG]/[SGG]）
- Andrew S. Tanenbaum, Herbert Bos. *Modern Operating Systems*, 4th Edition, 2014, Prentice Hall. ISBN 013359162X（记号 [AT]）
- Thomas Anderson, Michael Dahlin. *Operating Systems: Principles & Practice*, 2nd Edition, 2014, Recursive Books. ISBN 0985673524（记号 [AD]）
- Kay Robbins, Steve Robbins. *Unix Systems Programming*, 2nd Edition, Prentice Hall. ISBN 978-0-13-042411-2（记号 [RR]）
- Brian W. Kernighan, Dennis M. Ritchie. *The C Programming Language*, 2nd Edition, Prentice Hall.
- Doug Lea. *Concurrent Programming in Java: Design Principles and Patterns*, 2nd Edition, Prentice Hall.

## 课程简介

CS370 是科罗拉多州立大学计算机科学系的核心本科课程（core undergraduate CS course），目标是理解现代操作系统背后的广泛问题，重点是商业与开源操作系统中使用的关键概念与算法。官方列出的覆盖范围为：操作系统的视角、术语与结构；进程、线程、并发与死锁；CPU 调度算法；死锁与资源管理；内存（地址转换与虚拟内存）；存储体系结构与文件系统；虚拟机、容器与数据中心。时间允许时还会讨论安全与可靠性等进阶主题及最新发展。课程以 Silberschatz/Galvin/Gagne《Operating Systems Concepts》第 10 版为主教材，并辅以 Tanenbaum、Anderson & Dahlin、Robbins 等参考书。考核由每周 Canvas Quiz（1-14）、六次书面作业（HW1-HW6）和贯穿学期的 Term Project（含提案、中期与最终报告及演示）组成，另有期中与综合期末两次考试。官方页面注明日程"Tentative, subject to change"。

## Lecture 索引

| 编号 | 主题 | 日期 | 材料 |
| --- | --- | --- | --- |
| 01 | Introduction（操作系统导论） | 2025-08-26 | [slides.pdf](lecture-01-introduction/slides.pdf) · [原始链接](https://www.cs.colostate.edu/~cs370/Fall25/lectures/1IntroL1.pdf) |
| 02 | Introduction: C Programming（C 语言回顾） | 2025-08-28 | [slides.pdf](lecture-02-introduction-c/slides.pdf) · [原始链接](https://www.cs.colostate.edu/~cs370/Fall25/lectures/1IntroL2.pdf) |
| 03 | OS Structures（操作系统结构） | 2025-09-02 | [slides.pdf](lecture-03-os-structures/slides.pdf) · [原始链接](https://www.cs.colostate.edu/~cs370/Fall25/lectures/1IntroL3.pdf) |
| 04 | Processes: System Calls（进程与系统调用） | 2025-09-04 | [slides.pdf](lecture-04-system-calls/slides.pdf) · [原始链接](https://www.cs.colostate.edu/~cs370/Fall25/lectures/3ProcessesL4.pdf) |
| 05 | Process Creation（进程创建） | 2025-09-09 | [slides.pdf](lecture-05-process-creation/slides.pdf) · [原始链接](https://www.cs.colostate.edu/~cs370/Fall25/lectures/3ProcessesL5.pdf) |
| 06 | Inter-Process Communication（进程间通信） | 2025-09-11 | [slides.pdf](lecture-06-ipc/slides.pdf) · [原始链接](https://www.cs.colostate.edu/~cs370/Fall25/lectures/3ProcessesL6.pdf) |
| 07 | Threads（线程） | 2025-09-16 | [slides.pdf](lecture-07-threads/slides.pdf) · [原始链接](https://www.cs.colostate.edu/~cs370/Fall25/lectures/4ThreadsL7.pdf) |
| 08 | Scheduling（调度基础） | 2025-09-18 | [slides.pdf](lecture-08-scheduling/slides.pdf) · [原始链接](https://www.cs.colostate.edu/~cs370/Fall25/lectures/5SchedulingL8.pdf) |
| 09 | CPU Scheduling（CPU 调度进阶） | 2025-09-23 | [slides.pdf](lecture-09-cpu-scheduling/slides.pdf) · [原始链接](https://www.cs.colostate.edu/~cs370/Fall25/lectures/5SchedulingL9.pdf) |
| 10 | Synchronization（同步入门） | 2025-09-25 | [slides.pdf](lecture-10-synchronization/slides.pdf) · [原始链接](https://www.cs.colostate.edu/~cs370/Fall25/lectures/6SynchronizationL10.pdf) |
| 11 | Process Synchronization: Critical Sections（临界区） | 2025-09-30 | [slides.pdf](lecture-11-synchronization-critical-sections/slides.pdf) · [原始链接](https://www.cs.colostate.edu/~cs370/Fall25/lectures/6SynchronizationL11.pdf) |
| 12 | Process Synchronization: Semaphores（信号量） | 2025-10-02 | [slides.pdf](lecture-12-synchronization-semaphores/slides.pdf) · [原始链接](https://www.cs.colostate.edu/~cs370/Fall25/lectures/6SynchronizationL12.pdf) |
| 13 | Deadlocks（死锁） | 2025-10-07 | [slides.pdf](lecture-13-deadlocks/slides.pdf) · [原始链接](https://www.cs.colostate.edu/~cs370/Fall25/lectures/8DeadlockL13.pdf) |
| 14 | Midterm Review（期中复习） | 2025-10-09 | [slides.pdf](lecture-14-midterm-review/slides.pdf) · [原始链接](https://www.cs.colostate.edu/~cs370/Fall25/lectures/8MidtermReview.pdf) |
| 15 | Deadlocks: Avoidance and Recovery（死锁避免与恢复） | 2025-10-16 | [slides.pdf](lecture-15-deadlocks-part2/slides.pdf) · [原始链接](https://www.cs.colostate.edu/~cs370/Fall25/lectures/8DeadlockL15.pdf) |
| 16 | Memory Management（内存管理基础） | 2025-10-21 | [slides.pdf](lecture-16-memory-management/slides.pdf) · [原始链接](https://www.cs.colostate.edu/~cs370/Fall25/lectures/9mainmemoryL16.pdf) |
| 17 | Memory Management: Address Spaces（地址空间与分段） | 2025-10-23 | [slides.pdf](lecture-17-memory-management-2/slides.pdf) · [原始链接](https://www.cs.colostate.edu/~cs370/Fall25/lectures/9mainmemoryL17.pdf) |
| 18 | Paging（分页与硬件支持） | 2025-10-28 | [slides.pdf](lecture-18-paging/slides.pdf) · [原始链接](https://www.cs.colostate.edu/~cs370/Fall25/lectures/10virtualmemoryL18.pdf) |
| 19 | Virtual Memory（虚拟内存） | 2025-10-30 | [slides.pdf](lecture-19-virtual-memory/slides.pdf) · [原始链接](https://www.cs.colostate.edu/~cs370/Fall25/lectures/10virtualmemoryL19.pdf) |
| 20 | Virtual Memory: Replacement and Allocation（置换与分配） | 2025-11-04 | [slides.pdf](lecture-20-virtual-memory-2/slides.pdf) · [原始链接](https://www.cs.colostate.edu/~cs370/Fall25/lectures/13filesystemL20.pdf) |
| 21 | File Systems（文件系统概念） | 2025-11-06 | [slides.pdf](lecture-21-file-systems/slides.pdf) · [原始链接](https://www.cs.colostate.edu/~cs370/Fall25/lectures/13filesystemL21.pdf) |
| 22 | Mass Storage（大容量存储） | 2025-11-11 | [slides.pdf](lecture-22-mass-storage/slides.pdf) · [原始链接](https://www.cs.colostate.edu/~cs370/Fall25/lectures/11massstorageL22.pdf) |
| 23 | File System Implementation（文件系统实现） | 2025-11-13 | [slides.pdf](lecture-23-file-system-implementation/slides.pdf) · [原始链接](https://www.cs.colostate.edu/~cs370/Fall25/lectures/14filesystemL23.pdf) |
| 24 | Virtualization（虚拟化） | 2025-11-18 | [slides.pdf](lecture-24-virtualization/slides.pdf) · [原始链接](https://www.cs.colostate.edu/~cs370/Fall25/lectures/18virtualizationL24.pdf) |
| 25 | Mass Storage and Hadoop（分布式存储） | 2025-11-20 | [slides.pdf](lecture-25-hadoop/slides.pdf) · [原始链接](https://www.cs.colostate.edu/~cs370/Fall25/lectures/18virtualizationL25.pdf) |
| 26 | Virtualization and Security（虚拟化与安全） | 2025-12-02 | [slides.pdf](lecture-26-virtualization-security/slides.pdf) · [原始链接](https://www.cs.colostate.edu/~cs370/Fall25/lectures/18virtualizationL26.pdf) |
| 27 | Containers（容器） | 2025-12-04 | [slides.pdf](lecture-27-containers/slides.pdf) · [原始链接](https://www.cs.colostate.edu/~cs370/Fall25/lectures/18virtualizationL27.pdf) |

> 说明：日期取自 schedule 的每周日期区间（每周两讲，按顺序对应周一/周二讲次），官方未逐讲标注具体日期。Lecture 14 为 Midterm Review。

## 复习 / 考试材料（review/）

| 材料 | 说明 | 本地文件 | 原始链接 |
| --- | --- | --- | --- |
| Help Session 1 | 第 1 次习题课（进程/进程创建） | [help-session-1.pdf](review/help-session-1.pdf) | https://www.cs.colostate.edu/~cs370/Fall25/lectures/HelpSession1.pdf |
| Help Session 2 | 第 2 次习题课（调度/同步） | [help-session-2.pdf](review/help-session-2.pdf) | https://www.cs.colostate.edu/~cs370/Fall25/lectures/HelpSession2.pdf |
| Help Session 3 | 第 3 次习题课（期中前答疑） | [help-session-3.pdf](review/help-session-3.pdf) | https://www.cs.colostate.edu/~cs370/Fall25/lectures/HelpSession3.pdf |
| Help Session 4 | 第 4 次习题课（内存管理） | [help-session-4.pdf](review/help-session-4.pdf) | https://www.cs.colostate.edu/~cs370/Fall25/lectures/HelpSession4.pdf |
| Help Session 5 | 第 5 次习题课（文件系统） | [help-session-5.pdf](review/help-session-5.pdf) | https://www.cs.colostate.edu/~cs370/Fall25/lectures/HelpSession5.pdf |
| Midterm Review | 期中复习课（即 Lecture 14，与本目录副本内容相同） | [midterm-review.pdf](review/midterm-review.pdf) | https://www.cs.colostate.edu/~cs370/Fall25/lectures/8MidtermReview.pdf |
| Study Guide (Midterm) | 期中学习指南 | [study-guide-midterm.pdf](review/study-guide-midterm.pdf) | https://www.cs.colostate.edu/~cs370/Fall25/lectures/StudyGuide.mid.pdf |
| Study Guide (Ch 8-18) | 后半学期学习指南 | [study-guide-ch8-18.pdf](review/study-guide-ch8-18.pdf) | https://www.cs.colostate.edu/~cs370/Fall25/lectures/studyguide_ch8-18.pdf |
| Final Review | 期末复习课 slides | [final-review.pdf](review/final-review.pdf) | https://www.cs.colostate.edu/~cs370/Fall25/lectures/FinalReview.pdf |

## 作业、测验与考试

| 类型 | 内容 | 时间 |
| --- | --- | --- |
| Quiz | Quiz 1-14，通过 Canvas 完成（http://info.canvas.colostate.edu/login.aspx） | 每周 |
| HW1 | 动态内存分配（Dynamic memory allocation） | 布置于 W2，due 2025-09-18 |
| HW2 | 进程/线程相关书面作业 | due 2025-10-02 |
| HW3 | CPU 调度 | due 2025-10-16 |
| HW4 | 调度相关 | due 2025-10-30 |
| HW5 | Java 同步 | due 2025-11-13 |
| HW6 | 文件系统 | due 2025-11-20 |
| Term Project | 项目描述（TDD1 due 10/04）、提案 TPBD1（due 10/05）、TPBD2（due 11/01）、最终报告 TPBD3（due 12/01）、12/08-12/11 演示、互评 due 12/13 | 全学期 |
| Midterm | S001：2025-10-14；S801（线上）：2025-10-15 | 第 8 周 |
| Final | 综合期末考：S001 2025-12-16 14:00-16:00；S801 2025-12-17 | 期末周 |
| 成绩发布 | 2025-12-23/24 | — |

假期：2025-11-25、11-27 为 Fall Break。

## 目录结构

```
CS370-Operating-Systems-CSU-Fall2025/
├── README.md
├── lecture-01-introduction/ ... lecture-27-containers/   （27 讲，每讲含 README.md + slides.pdf）
└── review/          （Help Session 1-5、期中/期末复习、两份 Study Guide）
```

## 备注

- `lecture-14-midterm-review/slides.pdf` 与 `review/midterm-review.pdf` 为同一份 Midterm Review PDF（原始文件 `8MidtermReview.pdf`），分别存放在讲次目录与复习目录中。
- 若个别 slides 原链接返回非 PDF 内容，本目录会删除该文件并在对应讲次 README 中注明。
