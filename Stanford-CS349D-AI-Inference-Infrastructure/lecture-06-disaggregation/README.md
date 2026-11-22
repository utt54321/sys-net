# Lecture 06: Disaggregation

| 项目 | 内容 |
|---|---|
| 标题 | Disaggregation |
| 课程 | CS349D: AI Inference Infrastructure（Stanford University, Spring 2026） |
| 讲次 | Lecture 06（论文研讨） |
| 日期 | Wed Apr 15 |
| 主题 | Disaggregation |
| 本地材料 | 本讲为论文研讨课，**无 lecture slides**；论文见 `papers/` |
| 原始页面 | http://web.stanford.edu/class/cs349d/ |
| 录像 | 课程主页未提供录像链接（不下载视频） |

## 内容要点

- Prefill 与 decode 两阶段的计算/带宽特征差异
- DistServe：以 goodput 为目标的 prefill/decode 分离部署
- NVIDIA Dynamo：面向分布式推理的框架设计（需注意该阅读为技术博客而非论文）
- KV cache 传输开销与资源配比问题

## 相关阅读

### Required

- [DistServe](https://arxiv.org/abs/2401.09670) — 已下载：`papers/distserve-2401.09670.pdf`
- [Dynamo](https://developer.nvidia.com/blog/introducing-nvidia-dynamo-a-low-latency-distributed-inference-framework-for-scaling-reasoning-ai-models/) — 未下载（需登录/非 PDF 直链，仅记录链接）

### Optional

- [SplitWise](https://arxiv.org/abs/2311.18677) — 已下载：`papers/splitwise-2311.18677.pdf`
- [SarathiServe](https://www.usenix.org/conference/osdi24/presentation/agrawal) — 已下载：`papers/sarathiserve-usenix-osdi24.pdf`

