# ENGR-E 516 Engineering Cloud Computing（工程云计算）· Indiana University · Fall 2025

| 项目 | 内容 |
| --- | --- |
| 课程名 | Engineering Cloud Computing / 工程云计算（ENGR-E 516） |
| 学校 | Indiana University Bloomington，Luddy School of Informatics, Computing, and Engineering |
| 教师 | Prateek Sharma（Luddy 4126，office hour 周三 16:00–17:00）；助教 Abdul Rehman |
| 学期 | Fall 2025（页面生成于 2025-08-22） |
| 课程主页 | https://homes.luddy.indiana.edu/prateeks/cloud-course.html |
| 阅读材料页 | [readings.html](https://homes.luddy.indiana.edu/prateeks/cloud/readings.html) |
| 上课时间/地点 | 周一、周三 9:35–11:00，Global Studies (GA) 1112 |
| 先修要求 | 无官方先修课，但要求较强的系统编程与调试能力 |

## 课程简介

本课程讲授云计算的基本概念、工程原理与实践技能，同时关注“云上的应用”与“云平台本身的设计”两个视角，内容横跨操作系统、计算机网络与分布式系统。

课程希望帮助学习者理解云的运行机制，以及如何以较低成本在云上高效运行应用；会讨论 MapReduce 式并行数据处理、键值存储与缓存等典型云应用。

课程还会分析拥有数十万台服务器的大规模云平台在高效运维上面临的挑战，涵盖硬件虚拟化、分布式资源管理与软件定义数据中心等优化技术。

课程会介绍 Amazon EC2、Google Cloud Platform、Microsoft Azure 等主流云平台，并涉及无服务器计算、边缘云与可持续计算等新方向。

课程以白板讲授为主，每讲由两位学生记录课堂笔记；作业为多个不带脚手架代码的编程项目与论文阅读。

## 教材与参考书

- **DS**：*Distributed Systems: Principles and Paradigms*, 3rd Edition，Maarten van Steen & Andrew S. Tanenbaum —— [官方在线版](https://www.distributed-systems.net/index.php/books/distributed-systems-3rd-edition-2017/)
- **CCTP**：*Cloud Computing: Theory and Practice*, 2nd Edition，Dan C. Marinescu
- **OSTEP（页面写作 OS3EP）**：*Operating Systems: Three Easy Pieces*，Remzi H. Arpaci-Dusseau & Andrea C. Arpaci-Dusseau —— [ostep.org](http://pages.cs.wisc.edu/~remzi/OSTEP/)
- 论文阅读清单：见 [readings.html](https://homes.luddy.indiana.edu/prateeks/cloud/readings.html)，已下载的论文见本课程 `papers/` 目录。

## 讲次索引

| 编号 | 主题 | 日期 | 材料 |
| --- | --- | --- | --- |
| [01](lecture-01-course-intro/README.md) | 课程介绍与课程安排 | 未标注 | [slides.pdf](lecture-01-course-intro/slides.pdf) |
| [02](lecture-02-intro-cloud-computing/README.md) | 云计算导论 | 未标注 | [slides.pdf](lecture-02-intro-cloud-computing/slides.pdf) |
| [03](lecture-03-intro-continued/README.md) | 云计算导论（续） | 未标注 | 无 |
| [04](lecture-04-os-system-calls/README.md) | 操作系统：系统调用 | 未标注 | [slides.pdf](lecture-04-os-system-calls/slides.pdf) |
| [05](lecture-05-os-concurrency/README.md) | 操作系统：并发 | 未标注 | [slides.pdf](lecture-05-os-concurrency/slides.pdf) |
| [06](lecture-06-networks/README.md) | 计算机网络 | 未标注 | [slides.pdf](lecture-06-networks/slides.pdf) |
| [07](lecture-07-socket-programming/README.md) | 网络：套接字编程 | 未标注 | [slides-2-networks.pdf](lecture-07-socket-programming/slides-2-networks.pdf) |
| [08](lecture-08-client-server-modeling/README.md) | 客户端-服务器建模 | 未标注 | [slides.pdf](lecture-08-client-server-modeling/slides.pdf) |
| [09](lecture-09-queueing-theory/README.md) | 排队论（M/M/1） | 未标注 | [slides.pdf](lecture-09-queueing-theory/slides.pdf) |
| [10](lecture-10-parallel-scaling/README.md) | 并行扩展 | 未标注 | [slides.pdf](lecture-10-parallel-scaling/slides.pdf) |
| [11](lecture-11-elastic-scaling/README.md) | 弹性扩展 | 未标注 | [slides-6-scaling.pdf](lecture-11-elastic-scaling/slides-6-scaling.pdf) |
| [12](lecture-12-map-reduce/README.md) | MapReduce 并行数据处理 | 未标注 | [slides-mapreduce-1.pdf](lecture-12-map-reduce/slides-mapreduce-1.pdf)、[slides-mapreduce-2.pdf](lecture-12-map-reduce/slides-mapreduce-2.pdf) |
| [13](lecture-13-cloud-infrastructure/README.md) | 云基础设施（IaaS） | 未标注 | [slides.pdf](lecture-13-cloud-infrastructure/slides.pdf) |
| [14](lecture-14-os-virtualization/README.md) | 操作系统级虚拟化 | 未标注 | [slides.pdf](lecture-14-os-virtualization/slides.pdf) |
| [15](lecture-15-cloud-storage/README.md) | 云存储 | 未标注 | [slides.pdf](lecture-15-cloud-storage/slides.pdf) |
| [16](lecture-16-functions-as-a-service/README.md) | 函数即服务（FaaS） | 未标注 | [slides.pdf](lecture-16-functions-as-a-service/slides.pdf) |
| [17](lecture-17-hardware-virtualization/README.md) | 硬件虚拟化 | 未标注 | [slides.pdf](lecture-17-hardware-virtualization/slides.pdf) |
| [18](lecture-18-cpu-virtualization/README.md) | CPU 虚拟化 | 未标注 | [slides.pdf](lecture-18-cpu-virtualization/slides.pdf) |
| [19](lecture-19-paravirtualization/README.md) | 半虚拟化（Xen） | 未标注 | [slides.pdf](lecture-19-paravirtualization/slides.pdf) |
| [20](lecture-20-memory-virtualization/README.md) | 内存虚拟化 | 未标注 | [slides.pdf](lecture-20-memory-virtualization/slides.pdf) |
| [21](lecture-21-live-migration/README.md) | 虚拟机热迁移 | 未标注 | [slides.pdf](lecture-21-live-migration/slides.pdf) |
| [22](lecture-22-cluster-management/README.md) | 集群管理 | 未标注 | [slides.pdf](lecture-22-cluster-management/slides.pdf) |
| [23](lecture-23-transient-computing/README.md) | 瞬时（抢占式）计算 | 未标注 | [slides.pdf](lecture-23-transient-computing/slides.pdf) |
| [24](lecture-24-serverless-part2/README.md) | 无服务器计算（续） | 未标注 | [slides.pdf](lecture-24-serverless-part2/slides.pdf) |
| [25](lecture-25-containers-vs-vms/README.md) | 容器与虚拟机对比 | 未标注 | [slides.pdf](lecture-25-containers-vs-vms/slides.pdf) |
| [26](lecture-26-energy-and-carbon/README.md) | 能效与碳排放 | 未标注 | [slides.pdf](lecture-26-energy-and-carbon/slides.pdf) |
| [27](lecture-27-course-wrapup/README.md) | 课程总结 | 未标注 | 无 |

## 作业与考试

- 评分构成（页面注明可能调整）：编程作业 4 个共 40%；作业与阅读 10%；期中考试 20%；期末考试 20%；课堂笔记与参与 10%。
- 编程作业（约）：0 简单键值存储（进程与套接字）；1 生产者/消费者队列系统；2 用 API 在 GCP 虚拟机上部署作业 1；3 基于函数的 MapReduce；4 LXC 资源控制器。
- 作业不提供 starter code 或模板，多数语言不限，但最后一次作业需要熟练的 C 系统编程能力；无小组作业。
- 迟交政策：全学期共 4 天 late-day，用完后不再接受迟交。
- 考试内容侧重虚拟化技术、云性能与成本权衡，以及把课堂技术应用到新兴云服务与场景的能力。
- 页面明确禁止使用大语言模型等生成式 AI 工具完成作业。

## 其他说明

官方日程表使用 A0–A6、B1–B2、F3–F4、C1–C4、D1–D6、E2 这类模块编号（同一编号在表中重复出现，如两处 B1）。本归档按页面自上而下的顺序连续编号为 lecture-01…lecture-27，并在每讲 README 中标注官方编号。

部分讲次复用同一份 slides：A2 与 A1 相同、A6 与 A5 相同、F4 与 F3 相同；归档时在对应目录内另存一份并注明来源。

官方页面未标注每次课的具体日期，也未提供课堂录像链接，因此本归档不写日期、不下载视频。

## 目录说明

- 每讲一个 `lecture-NN-<slug>/` 目录，内含该讲 `README.md` 与讲义文件；文件名统一为 ASCII。
- `papers/` 存放官方阅读材料（论文）的 PDF，索引见 `papers/README.md`。
- 所有材料版权归原作者与课程方所有，仅用于个人学习归档。
