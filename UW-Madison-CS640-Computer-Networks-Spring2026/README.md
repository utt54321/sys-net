# CS 640 Introduction to Computer Networks（Spring 2026）

## 基本信息

| 项目 | 内容 |
| --- | --- |
| 课程名 | CS 640 Introduction to Computer Networks（计算机网络导论） |
| 学校 | University of Wisconsin–Madison（威斯康星大学麦迪逊分校） |
| 教师 | Ming Liu（mgliu@cs.wisc.edu，7673 Morgridge Hall，office hours 预约制） |
| 助教 | Peichen Guo（pguo36@wisc.edu，周四 16:00–17:00，Morgridge Hall TA lounge） |
| 学期 | Spring 2026 |
| 上课时间/地点 | 周二、周四 14:30–15:45，Psychology 107 |
| 学分/先修 | 3 学分；先修 CS 400 |
| 课程主页 | https://pages.cs.wisc.edu/~mgliu/CS640/S26/syllabus.html |
| 讲义目录 | https://pages.cs.wisc.edu/~mgliu/CS640/S26/lectures/ |
| 作业页面 | https://pages.cs.wisc.edu/~mgliu/CS640/S26/assignments.html |

## 教材与参考书

- **指定教材**：Larry Peterson & Bruce Davie, *Computer Networks: A Systems Approach*, 6th edition（开源在线版）
- **参考书**：Kurose & Ross, *Computer Networking: A Top-Down Approach*, 8th ed., Pearson, 2022
- **参考书**：Tanenbaum, Feamster & Wetherall, *Computer Networks*, 6th ed., Pearson, 2019
- **参考书**：W. Richard Stevens, *TCP/IP Illustrated, Volume 1: The Protocols*, 2nd ed., Addison-Wesley, 2011

## 课程简介

本课程是计算机网络导论，适合本科生与初入研究生阶段的学生，从概念与实现两个角度讲解计算机网络与网络协议。课程重点是构成 Internet 的基础思想、体系结构、协议与软件，覆盖 Peterson & Davie 教材的绝大部分内容，包括网络系统设计原则、协议分层、物理层与数据链路层、命名与编址、二层交换与 Internet 路由、TCP/IP 设计与实现、网络应用。课程强调动手实践，包含 4 个必做 Lab（1–2 人一组）。

## Lecture 索引

| 编号 | 主题 | 日期 | 材料 | 教材章节 |
| --- | --- | --- | --- | --- |
| 01 | Course logistics. Networks overview | 01/20 | slides.pdf | P&D 第 1 章（1.1, 1.2） |
| 02 | Computer networks--a sw and hw perspective | 01/22 | slides.pdf | P&D 第 1 章（1.3, 1.4） |
| 03 | Network performance analysis | 01/27 | slides.pdf | P&D 第 1 章（1.5） |
| 04 | Encoding | 01/29 | slides.pdf | P&D 第 2 章（2.1, 2.2） |
| 05 | Framing and error handling | 02/03 | slides.pdf | P&D 第 2 章（2.3.1, 2.3.2, 2.4） |
| 06 | L2 switching | 02/10 | slides.pdf | P&D 第 3 章（3.1.1, 3.2.1, 3.2.2, 3.2.3） |
| 07 | Ethernet | 02/12 | slides.pdf | P&D 第 2 章（2.6） |
| 08 | L2 reliable transmission | 02/17 | slides.pdf | P&D 第 2 章（2.5.1, 2.5.2） |
| 09 | IP introduction | 02/19 | slides.pdf | P&D 第 3 章（3.3.1, 3.3.2, 3.3.4） |
| 10 | Efficient addressing | 02/24 | slides.pdf | P&D 第 3 章（3.3.3, 3.3.5–3.3.8） |
| 11 | Distance vector routing | 02/26 | slides.pdf | P&D 第 3 章（3.4.1, 3.4.2） |
| 12 | Link state routing | 03/03 | slides.pdf | P&D 第 3 章（3.4.3, 3.4.4） |
| 13 | Software-defined networking | 03/05 | slides.pdf | OpenFlow 论文（ACM SIGCOMM'08） |
| 14 | Inter-domain routing | 03/10 | slides.pdf | P&D 第 4 章（4.1） |
| 15 | NAT, IPv6, and Multicast | 03/12 | slides.pdf | P&D 第 4 章（4.2.1–4.2.3, 4.3.1） |
| 16 | Transport introduction | 03/17 | slides.pdf | P&D 第 5 章（5.1, 5.2.1, 5.2.2） |
| 17 | TCP connection management | 03/19 | slides.pdf | P&D 第 5 章（5.2.3） |
| 18 | TCP reliability support (I) | 03/24 | slides.pdf | P&D 第 2、5 章（2.5.2, 5.2.4） |
| 19 | TCP reliability support (II) | 03/26 | slides.pdf | P&D 第 2、5 章（2.5.2, 5.2.4） |
| 20 | TCP congestion control (I) | 04/07 | slides.pdf | P&D 第 5、6 章（5.2.4–5.2.6, 6.4.2） |
| 21 | TCP congestion control (II) | 04/09 | slides.pdf | P&D 第 5、6 章（5.2.4–5.2.6, 6.4.2） |
| 22 | TCP congestion control (III) | 04/14 | slides.pdf | DCTCP 论文（SIGCOMM'10） |
| 23 | TCP in-network support | 04/16 | slides.pdf | P&D 第 6 章（6.2, 6.4.1） |
| 24 | Linux networking stack and infrastructure services | 04/21 | slides.pdf | Linux 网络栈（SIGCOMM'21）+ P&D 第 9 章（9.3） |
| 25 | Lab4 Review | 04/23 | slides.pdf | N/A |
| 26 | Network applications | 04/28 | slides.pdf | P&D 第 9 章（9.1, 9.4.2, 9.4.3） |
| 27 | Computer networks--beyond Internet. Closing remarks | 04/30 | slides.pdf | N/A |

> 对应关系说明：syllabus 的 Notes 列给出 L1–L27，`lectures/` 目录下文件名为 `L1.pdf`–`L27.pdf`，两者编号一一对应，因此讲次主题直接取自 syllabus 的 Topics 列。02/05 无课、03/31 与 04/02 为 Spring Break。

## 作业与考试

### 成绩构成

| 项目 | 占比 |
| --- | --- |
| Labs（4 个） | 50% |
| Quizzes | 15% |
| Exams（1 次期末） | 35% |

### Labs

| Lab | 主题 | 发布 | 截止 |
| --- | --- | --- | --- |
| Lab1 | Sockets, Mininet, and Performance | Jan. 29 | Feb. 10 |
| Lab2 | Forwarding and Switching | Feb. 17 | Mar. 3 |
| Lab3 | Routing | Mar. 10 | Mar. 27 |
| Lab4 | TCP | Mar. 27 | Apr. 30 |

### 考试与测验

- Quiz 1：02/12；Quiz 2：03/05；Quiz 3：03/26；Quiz 4：04/23（均在课堂进行）
- Final Exam：05/08（周五）

## 目录结构

- `lecture-NN-<slug>/`：第 NN 讲，含 `README.md` 与 `slides.pdf`
- 论文阅读（OpenFlow、DCTCP、Linux 网络栈）均为 ACM DL 链接，需机构登录，仅在第 13/22/24 讲 README 中列出

> 说明：课程页面未提供 lecture 录像；Lab 与 Quiz 的具体材料在 Canvas / 课程页面，未随本归档下载。