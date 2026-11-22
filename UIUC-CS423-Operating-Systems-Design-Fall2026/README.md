# CS 423 Operating System Design（Fall 2026）

## 基本信息

| 项目 | 内容 |
| --- | --- |
| 课程名 | CS 423 Operating System Design（操作系统设计） |
| 学校 | University of Illinois Urbana-Champaign（伊利诺伊大学厄巴纳-香槟分校） |
| 教师 | Ram Alagappan（ramn@illinois.edu，3122 Siebel Center） |
| 助教 | Owen Cochell、Pengcheng Wang |
| 学期 | Fall 2026 |
| 上课时间 | 周二 / 周四 14:00–15:15，2100 Sidney Lu Mechanical Engineering Building |
| 课程主页 | https://cs423-uiuc.github.io/fall26/index.html |
| 论坛 | Piazza |

## 教材与参考书

- **指定教材**：*Operating Systems: Three Easy Pieces*，Remzi H. Arpaci-Dusseau 与 Andrea C. Arpaci-Dusseau（免费在线版：http://pages.cs.wisc.edu/~remzi/OSTEP/ ）
- **选读**：*Virtual Machines*，James E. Smith 与 Ravi Nair，Elsevier / Morgan Kaufmann，2005
- **选读**：*Linux Kernel Development*（第 3 版），Robert Love，2010（对完成 MP 有帮助）

## 课程简介

本课程是 CS 341 之后的操作系统设计进阶课程，讲解操作系统的主要功能，并通过一系列需要修改操作系统内核代码的 Machine Problems 让学生分析其实现。课程主题包括调度、进程与线程同步、并发、内存管理技术，以及文件与存储系统。课堂以原理讲授与论文讨论（C4 阅读）结合，配套 5 个内核编程 MP、一次期中考试和一次期末考试。4 学分版本还需每周完成并总结与课程内容相关的文献阅读。

## Lecture 索引

| 编号 | 主题 | 日期 | 材料 |
| --- | --- | --- | --- |
| 01 | Course Intro | 8/25 | [lecture-01-course-intro](lecture-01-course-intro/) · slides.pdf |
| 02 | Process & Mechanism | 8/27 | [lecture-02-process-mechanism](lecture-02-process-mechanism/) · slides.pdf |
| 03 | Process Scheduling | 9/1 | [lecture-03-process-scheduling](lecture-03-process-scheduling/) · slides.pdf |
| 04 | Scheduling Wrap-up; Virtual Mem Intro | 9/8 | [lecture-04-scheduling-wrapup-vm-intro](lecture-04-scheduling-wrapup-vm-intro/) · slides.pdf |
| 05 | Segmentation, Paging | 9/10 | [lecture-05-segmentation-paging](lecture-05-segmentation-paging/) · slides.pdf |
| 06 | Paging, TLB | 9/17 | [lecture-06-paging-tlb](lecture-06-paging-tlb/) · slides.pdf |
| 07 | TLBs & More Page Tables | 9/22 | [lecture-07-tlb-page-tables](lecture-07-tlb-page-tables/) · slides.pdf |
| 08 | Swapping | 9/24 | [lecture-08-swapping](lecture-08-swapping/) · slides.pdf |
| 09 | Swapping, Intro to Concurrency | 9/29 | [lecture-09-swapping-concurrency-intro](lecture-09-swapping-concurrency-intro/) · slides.pdf |
| 10 | Intro to Concurrency, Locks | 10/6 | [lecture-10-concurrency-locks](lecture-10-concurrency-locks/) · slides.pdf |
| 11 | Locks | 10/8 | [lecture-11-locks](lecture-11-locks/) · slides.pdf |
| 12 | CVs | 10/13 | [lecture-12-condition-variables](lecture-12-condition-variables/) · slides.pdf |
| 13 | Semaphore | 10/15 | [lecture-13-semaphores](lecture-13-semaphores/) · slides.pdf |
| 14 | IO Devices | 10/29 | [lecture-14-io-devices](lecture-14-io-devices/) · slides.pdf |
| 15 | Devices & RAID | 11/3 | [lecture-15-devices-raid](lecture-15-devices-raid/) · slides.pdf |
| 16 | RAID & FS Internals | 11/5 | [lecture-16-raid-fs-internals](lecture-16-raid-fs-internals/) · slides.pdf |
| 17 | FS Internals | 11/10 | [lecture-17-fs-internals](lecture-17-fs-internals/) · slides.pdf |
| 18 | Journaling & LFS | 11/17 | [lecture-18-journaling-lfs](lecture-18-journaling-lfs/) · slides.pdf |
| 19 | LFS & NFS | 11/19 | [lecture-19-lfs-nfs](lecture-19-lfs-nfs/) · slides.pdf |
| 20 | NFS & AFS | 12/1 | [lecture-20-nfs-afs](lecture-20-nfs-afs/) · 仅链接 |
| 21 | GFS | 12/3 | [lecture-21-gfs](lecture-21-gfs/) · 仅链接 |
| 22 | Final Review | 12/8 | [lecture-22-final-review](lecture-22-final-review/) · 仅链接 |

> **页面结构异常（归档时）**：课程页面给出了 `slides/20.pdf`、`slides/21.pdf`、`slides/22.pdf`（第 20–22 讲）以及 MP3 讲解 slides、期中/期末模拟题、kernel-debugging 的链接，但这些文件在站点的 GitHub 仓库中尚不存在，访问返回 HTTP 404，因此未下载到本地，仅在各讲 README 与 `review/`、`exercises/` 中保留原始链接。

## 作业与考试

| 项目 | 说明 | 占比 |
| --- | --- | --- |
| Machine Problems（MP0–MP4） | 5 个，需独立完成，不允许迟交；合计 40%（示例分配 4%、9%、9%、9%、9%） | 40% |
| Midterm | 10/22（地点待定），占 20% | 20% |
| Final | 期末周（12/11–12/17 之间，待定），占 30% | 30% |
| Participation | 课堂讨论与 Piazza 参与，占 10% | 10% |

MP 关键时间点（页面标注）：MP0 9/14 截止、MP1 9/30 截止、MP2 10/20 截止、MP3 11/11 截止、MP4 12/9 截止（均为 23:59 CT）。C4 论文阅读每周一次，4 学分学生必须完成。

## 目录结构

- `lecture-NN-<slug>/`：第 NN 讲，含 `README.md`；已获取 slides 的讲次另含 `slides.pdf`（第 20–22 讲 slides 在站点上尚不存在）
- `exercises/`：MP0–MP4 讲解 slides 与内核调试（kernel debugging）slides
- `review/`：期中/期末模拟题与答案
- `papers/`：可直链下载的指定论文（ACM DL 论文无法直下，链接见各讲 README）

> 说明：OSTEP 章节 PDF 一律只保留链接，不随课程归档下载；视频（YouTube）只列链接。