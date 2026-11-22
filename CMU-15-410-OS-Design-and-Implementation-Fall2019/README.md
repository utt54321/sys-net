# 15-410/605 Operating System Design and Implementation（操作系统设计与实现）· CMU · Fall 2019

| 项目 | 内容 |
| --- | --- |
| 课程名 | 15-410/605 Operating System Design and Implementation / 操作系统设计与实现 |
| 学校 | Carnegie Mellon University，School of Computer Science（Computer Science Department） |
| 教师 | Dave Eckhardt（Teaching Professor of CS，de0u@andrew.cmu.edu）、Dave O'Hallaron（Professor of CS and ECE，droh@cs.cmu.edu） |
| 学期 | Fall 2019（页面末次修改 2019-12-05） |
| 课程主页 | https://www.cs.cmu.edu/~410-f19/ |
| 讲义页 | [lecture.html](https://www.cs.cmu.edu/~410-f19/lecture.html) |
| 其他页面 | [Syllabus](https://www.cs.cmu.edu/~410-f19/syllabus.html) · [Schedule](https://www.cs.cmu.edu/~410-f19/schedule.html) · [Projects](https://www.cs.cmu.edu/~410-f19/projects.html) · [Homeworks](https://www.cs.cmu.edu/~410-f19/homeworks.html) |

## 课程简介

15-410 是 CMU 的操作系统设计与实现课程，核心是让学生从零开始实现一个能在真实硬件（及 Simics 模拟器）上运行的小型内核。

课程覆盖进程与线程、同步、死锁、虚拟内存、文件系统、保护与安全、多核一致性、虚拟化与调度等主题，强调并发与底层调试能力。

课程围绕 4 个循序渐进的项目展开：内核引导、线程库与内核线程、虚拟内存、文件系统（PebPeb）；部分项目允许两人组队。

课堂使用自编讲义与板书讨论，官方页面提供 PDF/PPT/ODP 三种格式，本归档只保存 PDF。

## 教材与参考书

- **官方教材**：*Operating System Concepts*（Silberschatz, Galvin, Gagne），页面说明第 6–10 版均可，9 版/10 版最常用；部分主题（如同步）会用补充材料讲授。
- **补充教材**：*Operating Systems: Principles and Practice*（Anderson & Dahlin），schedule 页给出按 1st/2nd edition 的阅读对照表。
- 阅读作业对照表见 [schedule.html](https://www.cs.cmu.edu/~410-f19/schedule.html)，按 First/Second/Third/Fourth wave 划分。

## 讲次索引

| 编号 | 主题 | 日期 | 材料 |
| --- | --- | --- | --- |
| [01](lecture-01-course-overview/README.md) | 课程总览：OS 思维、课程介绍、Boot Camp | 2019-08-26（周一） | [slides-01a-os-frame-of-mind.pdf](lecture-01-course-overview/slides-01a-os-frame-of-mind.pdf)、[slides-01b-15410-intro.pdf](lecture-01-course-overview/slides-01b-15410-intro.pdf)、[slides-01c-boot-camp.pdf](lecture-01-course-overview/slides-01c-boot-camp.pdf) |
| [02](lecture-02-stack/README.md) | 栈与函数调用约定 | 2019-08-28（周三） | [slides.pdf](lecture-02-stack/slides.pdf) |
| [03](lecture-03-questions-hardware/README.md) | 答疑与硬件基础 | 2019-08-30（周五） | [slides-03a-questions.pdf](lecture-03-questions-hardware/slides-03a-questions.pdf)、[slides-03b-hardware.pdf](lecture-03-questions-hardware/slides-03b-hardware.pdf) |
| [04](lecture-04-process/README.md) | 进程 | 2019-09-04（周三） | [slides.pdf](lecture-04-process/slides.pdf) |
| [05](lecture-05-project1/README.md) | 项目一 | 2019-09-06（周五） | [slides.pdf](lecture-05-project1/slides.pdf) |
| [06](lecture-06-debugging-thread/README.md) | 调试与线程 | 2019-09-09（周一） | [slides-06a-debugging.pdf](lecture-06-debugging-thread/slides-06a-debugging.pdf)、[slides-06b-thread.pdf](lecture-06-debugging-thread/slides-06b-thread.pdf) |
| [07](lecture-07-define-synchronization-1/README.md) | C 预处理器与同步（一） | 2019-09-11（周三） | [slides-07a-define.pdf](lecture-07-define-synchronization-1/slides-07a-define.pdf)、[slides-07b-synchronization-1.pdf](lecture-07-define-synchronization-1/slides-07b-synchronization-1.pdf) |
| [08](lecture-08-errors-synchronization-2/README.md) | 错误处理与同步（二） | 2019-09-13（周五） | [slides-08a-errors.pdf](lecture-08-errors-synchronization-2/slides-08a-errors.pdf)、[slides-08b-synchronization-2.pdf](lecture-08-errors-synchronization-2/slides-08b-synchronization-2.pdf) |
| [09](lecture-09-include-synchronization-3/README.md) | 头文件组织与同步（三） | 2019-09-16（周一） | [slides-09a-include.pdf](lecture-09-include-synchronization-3/slides-09a-include.pdf)、[slides-09b-synchronization-3.pdf](lecture-09-include-synchronization-3/slides-09b-synchronization-3.pdf) |
| [10](lecture-10-project2-version-control/README.md) | 项目二与版本控制 | 2019-09-18（周三） | [slides-10a-project2.pdf](lecture-10-project2-version-control/slides-10a-project2.pdf)、[slides-10b-version-control.pdf](lecture-10-project2-version-control/slides-10b-version-control.pdf) |
| [11](lecture-11-paradise-lost-yield/README.md) | Paradise Lost 与 yield | 2019-09-20（周五） | [slides-11a-paradise-lost.pdf](lecture-11-paradise-lost-yield/slides-11a-paradise-lost.pdf)、[slides-11b-yield.pdf](lecture-11-paradise-lost-yield/slides-11b-yield.pdf) |
| [12](lecture-12-deadlock-1/README.md) | 死锁（一） | 2019-09-23（周一） | [slides.pdf](lecture-12-deadlock-1/slides.pdf) |
| [13](lecture-13-deadlock-2/README.md) | 死锁（二） | 2019-09-25（周三） | [slides.pdf](lecture-13-deadlock-2/slides.pdf) |
| [14](lecture-14-virtual-memory-1/README.md) | 虚拟内存（一） | 2019-09-27（周五） | [slides.pdf](lecture-14-virtual-memory-1/slides.pdf) |
| [15](lecture-15-virtual-memory-2/README.md) | 虚拟内存（二） | 2019-09-30（周一） | [slides.pdf](lecture-15-virtual-memory-2/slides.pdf) |
| [16](lecture-16-virtual-memory-3/README.md) | 虚拟内存（三） | 2019-10-02（周三） | [slides.pdf](lecture-16-virtual-memory-3/slides.pdf) |
| [17](lecture-17-project3/README.md) | 项目三 | 2019-10-04（周五） | [slides.pdf](lecture-17-project3/slides.pdf) |
| [18](lecture-18-review-executables/README.md) | 期中复习与可执行文件 | 2019-10-07（周一） | [slides-18a-review.pdf](lecture-18-review-executables/slides-18a-review.pdf)、[slides-18b-executables.pdf](lecture-18-review-executables/slides-18b-executables.pdf) |
| [19](lecture-19-storage/README.md) | 存储设备 | 2019-10-09（周三） | [slides.pdf](lecture-19-storage/slides.pdf) |
| [20](lecture-20-bootstrapping/README.md) | 引导与启动 | 2019-10-11（周五） | [slides.pdf](lecture-20-bootstrapping/slides.pdf) |
| [21](lecture-21-exam-feedback/README.md) | 期中考试讲评 | 2019-10-16（周三） | [slides.pdf](lecture-21-exam-feedback/slides.pdf) |
| [22](lecture-22-ipc-rpc/README.md) | IPC 与 RPC | 2019-10-21（周一） | [slides.pdf](lecture-22-ipc-rpc/slides.pdf) |
| [23](lecture-23-filesystem-interface/README.md) | 文件系统（接口） | 2019-10-28（周一） | [slides.pdf](lecture-23-filesystem-interface/slides.pdf) |
| [24](lecture-24-filesystem-internals/README.md) | 文件系统（内部实现） | 2019-10-30（周三） | [slides.pdf](lecture-24-filesystem-internals/slides.pdf) |
| [25](lecture-25-transactions-filesystem/README.md) | 事务（文件系统视角） | 2019-11-01（周五） | [slides.pdf](lecture-25-transactions-filesystem/slides.pdf) |
| [26](lecture-26-protection/README.md) | 保护 | 2019-11-04（周一） | [slides.pdf](lecture-26-protection/slides.pdf) |
| [27](lecture-27-security-1/README.md) | 安全（一） | 2019-11-06（周三） | [slides.pdf](lecture-27-security-1/slides.pdf) |
| [28](lecture-28-security-2/README.md) | 安全（二） | 2019-11-08（周五） | [slides.pdf](lecture-28-security-2/slides.pdf) |
| [29](lecture-29-parallelism-coherence/README.md) | 并行与缓存一致性 | 2019-11-11（周一） | [slides.pdf](lecture-29-parallelism-coherence/slides.pdf) |
| [30](lecture-30-consistency/README.md) | 内存一致性模型 | 2019-11-13（周三） | [slides.pdf](lecture-30-consistency/slides.pdf) |
| [31](lecture-31-synchronization/README.md) | 多核同步 | 2019-11-15（周五） | [slides.pdf](lecture-31-synchronization/slides.pdf) |
| [32](lecture-32-virtualization-pebpeb/README.md) | 虚拟化与项目四 | 2019-11-18（周一） | [slides-32a-virtualization.pdf](lecture-32-virtualization-pebpeb/slides-32a-virtualization.pdf)、[slides-32b-project4-pebpeb.pdf](lecture-32-virtualization-pebpeb/slides-32b-project4-pebpeb.pdf) |
| [33](lecture-33-scheduling/README.md) | 调度 | 2019-11-20（周三） | [slides.pdf](lecture-33-scheduling/slides.pdf) |
| [34](lecture-34-os-structure/README.md) | 操作系统结构 | 2019-11-22（周五） | [slides.pdf](lecture-34-os-structure/slides.pdf) |
| [35](lecture-35-merkle-trees-hashfs/README.md) | Merkle 树与文件系统（板书讨论） | 2019-11-25（周一） | 无 |
| [36](lecture-36-windows-device-drivers/README.md) | Windows 设备驱动 | 2019-12-02（周一） | `slides.pdf`（未下载） |
| [37](lecture-37-transactions-database/README.md) | 事务（数据库视角） | 2019-12-04（周三） | `slides.pdf`（未下载） |
| [38](lecture-38-review/README.md) | 期末复习 | 2019-12-06（周五） | [slides.pdf](lecture-38-review/slides.pdf) |

## 作业与考试

- 课程项目：Project 0（引导与栈）→ Project 1（内核与加载）→ Project 2（线程库与内核线程）→ Project 3（虚拟内存）→ Project 4（PebPeb 文件系统）。
- Project 2/3/4 可注册搭档组队完成（Project 2/3 要求使用版本控制系统）；Project 3/4 设有 hurdle 门槛要求。
- 作业（homeworks）与阅读任务见 [homeworks.html](https://www.cs.cmu.edu/~410-f19/homeworks.html)；另有一次期中考试（晚间举行）和期末考试。
- 期中考试后有专门一讲做考试讲评（第 21 讲 Exam Feedback）；期末复习见第 38 讲。
- 官方 FAQ 说明课程容量有限，选课/旁听需导师介入，注册 Wait list 并非先到先得。

## 其他说明

**版式说明**：官方讲义页表格把同一上课日拆成多行（如 L01a/L01b/L01c），每行一份讲义。本归档按讲义编号 L01–L38 建立 38 个讲次目录，同一天的多份讲义放在同一目录下，文件名加 `01a/01b/01c` 前缀。

**格式**：页面同时提供 ODP/PPT/PDF，本归档只下载 PDF；第 29–31 讲官方同时提供 PPTX，未下载。

**无 PDF 的讲次**：第 35 讲「Merkle Trees and file systems」是板书讨论（chalk talk），只提供 4 张 JPEG 板书照片，未下载图片，仅在 README 列出链接；第 34 讲另附 `.tgz` 示例代码，未下载。

**日期笔误**：官方表格把 2019-10-25（“No class today, Tartan Community Day”）与 2019-10-30（Filesystem Internals，对应第 24 讲）两行误写成 2018 年；本归档按 2019 年处理。

**下载失败**：第 36 讲（L36_Drivers.pdf）与第 37 讲（L37_Transactions.pdf）的官方链接现在返回 CMU Shibboleth 登录页（`text/html`）而非 PDF，无法下载，已在对应讲次 README 记录；其余 46 份讲义 PDF 均校验为有效 `%PDF` 文件。

官方页面未提供课堂录像链接。

## 目录说明

- 每讲一个 `lecture-NN-<slug>/` 目录，内含该讲 `README.md` 与讲义文件；文件名统一为 ASCII。
- 所有材料版权归原作者与课程方所有，仅用于个人学习归档。
