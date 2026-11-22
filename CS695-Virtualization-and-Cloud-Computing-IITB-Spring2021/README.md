# CS695: Virtualization and Cloud Computing

**中文名**：虚拟化与云计算
**英文名**：CS695: Virtualization and Cloud Computing
**学校**：IIT Bombay（印度理工学院孟买分校），Department of Computer Science and Engineering
**教师**：Mythili Vutukuru（mythili@cse.iitb.ac.in）
**学期**：Spring 2021
**课程主页**：https://www.cse.iitb.ac.in/~mythili/teaching/cs695_spring2021/index.html

## 教材与参考书

- 官方页面未指定单一教材；阅读材料以经典论文为主（见 `papers/README.md`）。
- 部分讲次引用 Remzi Arpaci-Dusseau 的 *Operating Systems: Three Easy Pieces*（OSTEP）章节，例如
  VMM 章节：http://pages.cs.wisc.edu/~remzi/OSTEP/vmm-intro.pdf
- 操作系统基础可参考教师本人的 OS 课程讲义：https://www.cse.iitb.ac.in/~mythili/os/

## 课程简介

CS695 是一门面向本科生与研究生开放的研究生级别课程，讲授虚拟化与云计算的基础和进阶概念。课程从操作系统概念回顾开始，系统讲解 VMM 的设计技术、硬件辅助 CPU 虚拟化（KVM/QEMU）、动态二进制翻译实现的全虚拟化、内存虚拟化与 I/O 虚拟化、Xen 半虚拟化，以及虚拟机热迁移、检查点与克隆、容器（namespaces/cgroups）等主题。后半学期转向云计算：云的导论，以及 Dynamo、Bigtable、Haystack、Memcached 等云存储与缓存系统的经典论文。课程强调动手编程，三次编程作业用于巩固课堂所学。选课要求：必须先修过操作系统课程（本科生 CS347/CS333，研究生 CS744），并需要一台原生 Linux 机器完成编程作业。

## 评分方式

| 组成部分 | 权重 |
| --- | --- |
| 期中考试（mid-semester exam） | 20% |
| 期末考试（end-semester exam） | 40% |
| 三次编程作业 | 40%（15% + 15% + 10%） |

页面未给出期中/期末考试的具体日期与地点，仅给出占比（期中 20%、期末 40%）。

## 先修要求

- 操作系统课程为硬性先修：本科生 CS347/CS333，研究生 CS744。
- 需要原生 Linux 环境（编程作业必需）。
- 页面说明：课程包含大量系统编程，具备系统编程兴趣与能力者更合适；不满足条件但希望选课需与教师沟通。

## 编程作业

| 作业 | 截止时间 | 链接 |
| --- | --- | --- |
| Programming Assignment 1 | 2021-02-13（周六）23:55 | https://www.cse.iitb.ac.in/~mythili/teaching/cs695_spring2021/pa/pa1.html |
| Programming Assignment 2 | 2021-03-27（周六）23:59 | https://www.cse.iitb.ac.in/~mythili/teaching/cs695_spring2021/pa/pa2.html |
| Programming Assignment 3 | 2021-04-17（周六）23:59 | https://www.cse.iitb.ac.in/~mythili/teaching/cs695_spring2021/pa/pa3.html |

作业页面需要访问课程站点，本归档只记录链接，不下载作业文件。

## Lecture 索引

| 编号 | 主题 | 日期 | 材料 |
| --- | --- | --- | --- |
| 01 | Introduction to the course | 2021-01-07 | [slides.pdf](lecture-01-intro/slides.pdf) · [原始链接](https://www.cse.iitb.ac.in/~mythili/teaching/cs695_spring2021/slides_pdf/01-intro.pdf) |
| 02 | Review of concepts from operating systems | 2021-01-11 | [slides.pdf](lecture-02-os-review/slides.pdf) · [原始链接](https://www.cse.iitb.ac.in/~mythili/teaching/cs695_spring2021/slides_pdf/02-OS-review.pdf) |
| 03 | Techniques to design virtual machine monitors | 2021-01-18 | [slides.pdf](lecture-03-vmm-design/slides.pdf) · [原始链接](https://www.cse.iitb.ac.in/~mythili/teaching/cs695_spring2021/slides_pdf/03-vmm.pdf) |
| 04 | Hardware-assisted CPU virtualization in KVM/QEMU | 2021-01-18 | [slides.pdf](lecture-04-hwvirt-kvm-qemu/slides.pdf) · [原始链接](https://www.cse.iitb.ac.in/~mythili/teaching/cs695_spring2021/slides_pdf/04-hwvirt-kvmqemu.pdf) |
| 05 | Full virtualization via dynamic binary translation | 2021-01-25 | [slides.pdf](lecture-05-fullvirt-binary-translation/slides.pdf) · [原始链接](https://www.cse.iitb.ac.in/~mythili/teaching/cs695_spring2021/slides_pdf/05-fullvirt.pdf) |
| 06 | Memory virtualization techniques | 2021-01-25 | [slides.pdf](lecture-06-memory-virtualization/slides.pdf) · [原始链接](https://www.cse.iitb.ac.in/~mythili/teaching/cs695_spring2021/slides_pdf/06-memvirt.pdf) |
| 07 | I/O virtualization techniques | 2021-02-01 | [slides.pdf](lecture-07-io-virtualization/slides.pdf) · [原始链接](https://www.cse.iitb.ac.in/~mythili/teaching/cs695_spring2021/slides_pdf/07-iovirt.pdf) |
| 08 | Paravirtualization in Xen | 2021-02-01 | [slides.pdf](lecture-08-paravirt-xen/slides.pdf) · [原始链接](https://www.cse.iitb.ac.in/~mythili/teaching/cs695_spring2021/slides_pdf/08-paravirt-xen.pdf) |
| 09 | VM live migration | 2021-02-08 | [slides.pdf](lecture-09-live-migration/slides.pdf) · [原始链接](https://www.cse.iitb.ac.in/~mythili/teaching/cs695_spring2021/slides_pdf/09-vm-migration.pdf) |
| 10 | VM checkpointing and cloning | 2021-03-08 | [slides.pdf](lecture-10-checkpoint-cloning/slides.pdf) · [原始链接](https://www.cse.iitb.ac.in/~mythili/teaching/cs695_spring2021/slides_pdf/10-vm-checkpoint-cloning.pdf) |
| 11 | Containers: namespaces, cgroups, frameworks | 2021-03-15 | [slides.pdf](lecture-11-containers/slides.pdf) · [原始链接](https://www.cse.iitb.ac.in/~mythili/teaching/cs695_spring2021/slides_pdf/11-containers.pdf) |
| 12 | Introduction to the cloud | 2021-03-22 | [slides.pdf](lecture-12-cloud-intro/slides.pdf) · [原始链接](https://www.cse.iitb.ac.in/~mythili/teaching/cs695_spring2021/slides_pdf/12-cloud-intro.pdf) |
| 13 | Cloud storage: key-value stores: Dynamo | 2021-03-22 | [slides.pdf](lecture-13-dynamo/slides.pdf) · [原始链接](https://www.cse.iitb.ac.in/~mythili/teaching/cs695_spring2021/slides_pdf/13-dynamo.pdf) |
| 14 | Cloud storage: semi-structured data: Bigtable | 2021-03-29 | [slides.pdf](lecture-14-bigtable/slides.pdf) · [原始链接](https://www.cse.iitb.ac.in/~mythili/teaching/cs695_spring2021/slides_pdf/14-bigtable.pdf) |
| 15 | Cloud storage: application-specific optimizations: Haystack | 2021-04-05 | [slides.pdf](lecture-15-haystack/slides.pdf) · [原始链接](https://www.cse.iitb.ac.in/~mythili/teaching/cs695_spring2021/slides_pdf/15-haystack.pdf) |
| 16 | Cloud storage: caching: Memcache | 2021-04-12 | [slides.pdf](lecture-16-memcache/slides.pdf) · [原始链接](https://www.cse.iitb.ac.in/~mythili/teaching/cs695_spring2021/slides_pdf/16-memcache.pdf) |

## 论文（papers/）

共 16 篇指定论文，其中 15 篇已下载，按讲次整理见 [papers/README.md](papers/README.md)；SnowFlock 一篇原站链接已失效。
LWN 文章（Using the KVM API、Namespaces in operation、CGroups 文档）、
OSTEP 章节与 IITB OS 课程讲义属于外部链接，仅记录在各讲 README 中。

## 目录结构

```
CS695-Virtualization-and-Cloud-Computing-IITB-Spring2021/
├── README.md
├── lecture-01-intro/ ... lecture-16-memcache/   （16 讲，每讲含 README.md + slides.pdf）
└── papers/          （15 篇论文 + README.md；另有 1 篇原站失效）
```

## 备注

- 页面没有单独的 review/ 目录材料；期中/期末复习以论文与 slides 为主。
- 第 3、4 讲、第 5、6 讲、第 7、8 讲、第 12、13 讲在页面上为同一天的两讲（日期相同）。
- 第 1 讲 References 为空，第 2 讲仅指向外部 OS 讲义，第 12 讲 References 为空。
