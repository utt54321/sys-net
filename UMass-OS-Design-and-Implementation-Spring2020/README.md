# Operating Systems Design and Implementation

**中文名**：操作系统设计与实现
**英文名**：COMPSCI 577: Operating Systems Design and Implementation
**学校**：University of Massachusetts Amherst（马萨诸塞大学阿默斯特分校），College of Information and Computer Sciences（LASS 实验室）
**教师**：Prashant Shenoy
**学期**：Spring 2020
**课程主页**：https://lass.cs.umass.edu/~shenoy/courses/spring20/
**Lecture 页面**：https://lass.cs.umass.edu/~shenoy/courses/spring20/lectures.html
**视频频道**：https://www.youtube.com/user/UMassOS

## 教材与参考书

- **主教材**：Andrew S. Tanenbaum. *Modern Operating Systems*（页面中的 "AST" 即指该书）
- 课程以 **Minix 3** 与 **Linux** 内核源码为案例讲解操作系统的设计与实现

## 课程简介

本课程通过深入学习操作系统内部实现，使学生掌握操作系统设计与实现的高级概念。课程以一个类 Unix 操作系统为案例，由讲座与动手编程作业组成，覆盖系统调用、设备驱动、CPU 调度、内存管理、文件系统等子系统的设计与实现；时间允许时还会涉及虚拟化与集群调度等进阶主题。课程目标是让学生理解关键 OS 抽象在实际系统中如何实现，能够设计并实现复杂系统软件，并具备开发或修改内核组件（如模块、驱动、文件系统、调度器）的能力。官方页面说明：2020 年春季学期因疫情在春假后转为线上，全部讲座录制后发布，采用"翻转课堂"模式，每周四 14:30-15:30 在线讨论。所有讲座都提供 UMassOS YouTube 频道上的 screencast 与视频录像。

## 先修要求

- 熟练使用 C 语言（OS 内核用 C 编写）。
- 已修读本科操作系统课程（相当于 COMPSCI 377）。
- 同一课堂设本科与研究生两个 section，按学籍选择对应 section。

## Lecture 索引

| 编号 | 主题 | 日期 | 材料 |
| --- | --- | --- | --- |
| 01 | Introduction | 2020-01-21 | [slides.pdf](lecture-01-introduction/slides.pdf) · [原始链接](https://lass.cs.umass.edu/~shenoy/courses/spring20/lectures/Lec01.pdf) |
| 02 | Architecture Concepts | 2020-01-23 | [slides.pdf](lecture-02-architecture-concepts/slides.pdf) · [notes.pdf](lecture-02-architecture-concepts/notes.pdf) · [原始链接](https://lass.cs.umass.edu/~shenoy/courses/spring20/lectures/Lec02.pdf) |
| 03 | Microkernels | 2020-01-28 | [slides.pdf](lecture-03-microkernels/slides.pdf) · [notes.pdf](lecture-03-microkernels/notes.pdf) · [原始链接](https://lass.cs.umass.edu/~shenoy/courses/spring20/lectures/Lec03.pdf) |
| 04 | Microkernels and Minix | 2020-01-30 | [slides.pdf](lecture-04-microkernels-minix/slides.pdf) · [notes.pdf](lecture-04-microkernels-minix/notes.pdf) · [原始链接](https://lass.cs.umass.edu/~shenoy/courses/spring20/lectures/Lec04.pdf) |
| 05 | OS Boot Process | 2020-02-04 | [slides.pdf](lecture-05-os-boot/slides.pdf) · [notes.pdf](lecture-05-os-boot/notes.pdf) · [原始链接](https://lass.cs.umass.edu/~shenoy/courses/spring20/lectures/Lec05.pdf) |
| 06 | System and Kernel Calls | 2020-02-06 | [slides.pdf](lecture-06-system-kernel-calls/slides.pdf) · [notes.pdf](lecture-06-system-kernel-calls/notes.pdf) · [原始链接](https://lass.cs.umass.edu/~shenoy/courses/spring20/lectures/Lec06.pdf) |
| 07 | CPU Scheduling | 2020-02-11 | [slides.pdf](lecture-07-cpu-scheduling/slides.pdf) · [notes.pdf](lecture-07-cpu-scheduling/notes.pdf) · [原始链接](https://lass.cs.umass.edu/~shenoy/courses/spring20/lectures/Lec07.pdf) |
| 08 | Process Management I | 2020-02-13 | [slides.pdf](lecture-08-process-management/slides.pdf) · [notes.pdf](lecture-08-process-management/notes.pdf) · [原始链接](https://lass.cs.umass.edu/~shenoy/courses/spring20/lectures/Lec08.pdf) |
| 09 | Linux Architecture | 2020-02-20 | [slides.pdf](lecture-09-linux-architecture/slides.pdf) · [notes.pdf](lecture-09-linux-architecture/notes.pdf) · [原始链接](https://lass.cs.umass.edu/~shenoy/courses/spring20/lectures/Lec09.pdf) |
| 10 | Memory Management Refresher | 2020-02-25 | [slides.pdf](lecture-10-memory-management/slides.pdf) · [notes.pdf](lecture-10-memory-management/notes.pdf) · [原始链接](https://lass.cs.umass.edu/~shenoy/courses/spring20/lectures/Lec10.pdf) |
| 11 | Minix Memory Management | 2020-02-27 | [slides.pdf](lecture-11-minix-memory/slides.pdf) · [notes.pdf](lecture-11-minix-memory/notes.pdf) · [原始链接](https://lass.cs.umass.edu/~shenoy/courses/spring20/lectures/Lec11.pdf) |
| 12 | Virtualization - Part 1 | 2020-03-03 | [slides.pdf](lecture-12-virtualization-1/slides.pdf) · [notes.pdf](lecture-12-virtualization-1/notes.pdf) · [原始链接](https://lass.cs.umass.edu/~shenoy/courses/spring20/lectures/Lec12.pdf) |
| 13 | Virtualization - Part 2 | 2020-03-05 | [slides.pdf](lecture-13-virtualization-2/slides.pdf) · [notes.pdf](lecture-13-virtualization-2/notes.pdf) · [原始链接](https://lass.cs.umass.edu/~shenoy/courses/spring20/lectures/Lec13.pdf) |
| 14 | Linux Kernel - Part 2 | 2020-03-12 | [slides.pdf](lecture-14-linux-kernel-2/slides.pdf) · [notes.pdf](lecture-14-linux-kernel-2/notes.pdf) · [原始链接](https://lass.cs.umass.edu/~shenoy/courses/spring20/lectures/Lec14.pdf) |
| 15 | I/O and Device Drivers - Overview | 2020-03-24（建议观看日期） | [slides.pdf](lecture-15-io-device-drivers/slides.pdf) · [notes.pdf](lecture-15-io-device-drivers/notes.pdf) · [原始链接](https://lass.cs.umass.edu/~shenoy/courses/spring20/lectures/Lec15.pdf) |
| 16 | Minix I/O and Device Drivers | 2020-03-26（建议观看日期） | [slides.pdf](lecture-16-minix-io/slides.pdf) · [notes.pdf](lecture-16-minix-io/notes.pdf) · [原始链接](https://lass.cs.umass.edu/~shenoy/courses/spring20/lectures/Lec16.pdf) |
| 17 | File System Overview | 2020-03-31（建议观看日期） | [slides.pdf](lecture-17-file-system/slides.pdf) · [notes.pdf](lecture-17-file-system/notes.pdf) · [原始链接](https://lass.cs.umass.edu/~shenoy/courses/spring20/lectures/Lec17.pdf) |
| 18 | Minix File System and File Server | 2020-04-02（建议观看日期） | [slides.pdf](lecture-18-minix-file-system/slides.pdf) · [notes.pdf](lecture-18-minix-file-system/notes.pdf) · [原始链接](https://lass.cs.umass.edu/~shenoy/courses/spring20/lectures/Lec18.pdf) |
| 19 | Minix Networking | 2020-04-07（建议观看日期） | [slides.pdf](lecture-19-minix-networking/slides.pdf) · [notes.pdf](lecture-19-minix-networking/notes.pdf) · [原始链接](https://lass.cs.umass.edu/~shenoy/courses/spring20/lectures/Lec19.pdf) |
| 20 | Linux - Synchronization and Timers | 2020-04-09（建议观看日期） | [slides.pdf](lecture-20-linux-sync-timers/slides.pdf) · [notes.pdf](lecture-20-linux-sync-timers/notes.pdf) · [原始链接](https://lass.cs.umass.edu/~shenoy/courses/spring20/lectures/Lec20.pdf) |
| 21 | Memory Management in Linux | 2020-04-14（建议观看日期） | [slides.pdf](lecture-21-linux-memory/slides.pdf) · [notes.pdf](lecture-21-linux-memory/notes.pdf) · [原始链接](https://lass.cs.umass.edu/~shenoy/courses/spring20/lectures/Lec21.pdf) |
| 22 | Linux I/O | 2020-04-16（建议观看日期） | [slides.pdf](lecture-22-linux-io/slides.pdf) · [notes.pdf](lecture-22-linux-io/notes.pdf) · [原始链接](https://lass.cs.umass.edu/~shenoy/courses/spring20/lectures/Lec22.pdf) |

> 说明：Lecture 15-22 在页面上标注为 "virt"（录播）讲次，日期列给出的是 "Suggested view date"（建议观看日期），README 中照录。2020-02-18 为 Virtual Monday 无课，2020-03-17/19 为 Spring Break。

## 复习 / 考试材料（review/）

| 材料 | 说明 | 本地文件 | 原始链接 |
| --- | --- | --- | --- |
| Midterm Study Guide | 期中考试学习指南（2020-03-10 期中考试，19:00-20:30，CS bldg 142） | [study-guide-midterm.pdf](review/study-guide-midterm.pdf) | https://lass.cs.umass.edu/~shenoy/courses/spring20/lectures/study-guide.pdf |

## 作业、实验与考试

| 类型 | 内容 | 时间 |
| --- | --- | --- |
| Lab 0 | 不计分实验，无截止日期 | 2020-01-30 发放 |
| Lab 1 | 实验一 | due 2020-02-20 23:59 |
| Lab 2 | 实验二 | due 2020-03-05 23:59 |
| Lab 3 | 实验三 | due 2020-04-07 23:59 |
| Final Project | 期末项目 | due 2020-04-24 23:59 |
| Midterm | 期中考试（晚间 19:00-20:30，Room CS bldg 142），配 Study Guide | 2020-03-10 |

## 目录结构

```
UMass-OS-Design-and-Implementation-Spring2020/
├── README.md
├── lecture-01-introduction/ ... lecture-22-linux-io/   （22 讲，每讲含 README.md + slides.pdf，除第 1 讲外均有 notes.pdf）
└── review/          （期中 Study Guide）
```

## 备注

- 第 1 讲页面只有 "Notes" 文字而没有链接，因此 `lecture-01-introduction/` 不包含 `notes.pdf`；其余 21 讲均提供 scribe notes 并已下载。
- 第 20-22 讲页面提供 Screencast 链接，但 "Video" 仅为文字（无链接），已在各讲 README 中注明。
- 页面结构异常：`lectures/Lec03.pdf` 与 `lectures/Lec04.pdf` 两个链接返回的是**同一份 PDF**（字节数 1920769，MD5 完全相同），即 Lecture 4 "Microkernels and Minix" 的幻灯片实际与 Lecture 3 相同，原站未单独上传该讲 slides。已在 `lecture-04-microkernels-minix/README.md` 中标注。
- 录像一律只记录链接，未下载视频文件。
