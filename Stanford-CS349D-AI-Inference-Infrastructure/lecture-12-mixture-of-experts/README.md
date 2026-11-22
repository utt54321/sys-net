# Lecture 12: Mixture of Experts

| 项目 | 内容 |
|---|---|
| 标题 | Mixture of Experts |
| 课程 | CS349D: AI Inference Infrastructure（Stanford University, Spring 2026） |
| 讲次 | Lecture 12（论文研讨） |
| 日期 | Wed May 6 |
| 主题 | Mixture of Experts |
| 本地材料 | 本讲为论文研讨课，**无 lecture slides**；论文见 `papers/` |
| 原始页面 | http://web.stanford.edu/class/cs349d/ |
| 录像 | 课程主页未提供录像链接（不下载视频） |

## 内容要点

- MoE 推理的专家并行与 all-to-all 通信开销
- MegaScale-Infer：面向大规模 MoE 的分离式专家并行
- Helix Parallelism：长上下文 MoE 推理的并行策略
- 专家负载不均衡与放置/路由问题

## 相关阅读

### Required

- [MegaScale-Infer](https://arxiv.org/abs/2504.02263) — 已下载：`papers/megascale-infer-2504.02263.pdf`
- [Helix Parallelism](https://arxiv.org/abs/2507.07120) — 已下载：`papers/helix-parallelism-2507.07120.pdf`

### Optional

- [Original MoE paper](https://arxiv.org/abs/1701.06538) — 已下载：`papers/moe-original-1701.06538.pdf`
- [FlashMoE](https://arxiv.org/abs/2506.04667) — 已下载：`papers/flashmoe-2506.04667.pdf`

