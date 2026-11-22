# Lecture 02: Parallelism

| 项目 | 内容 |
|---|---|
| 标题 | Parallelism |
| 课程 | CS349D: AI Inference Infrastructure（Stanford University, Spring 2026） |
| 讲次 | Lecture 02（论文研讨） |
| 日期 | Wed Apr 1 |
| 主题 | Parallelism |
| 本地材料 | 本讲为论文研讨课，**无 lecture slides**；论文见 `papers/` |
| 原始页面 | http://web.stanford.edu/class/cs349d/ |
| 录像 | 课程主页未提供录像链接（不下载视频） |

## 内容要点

- 大模型推理中的数据并行、张量并行与流水并行
- FlexFlow：面向分布式深度学习的算子级并行化策略搜索（SOAR）
- Efficiently Scaling Transformer Inference：在延迟/成本约束下选择模型切分方案
- 显存、带宽与跨设备通信开销之间的权衡

## 相关阅读

### Required

- [FlexFlow](https://arxiv.org/abs/1807.05358) — 已下载：`papers/flexflow-1807.05358.pdf`
- [Efficiently Scaling Transformer Inference](https://arxiv.org/abs/2211.05102) — 已下载：`papers/efficiently-scaling-transformer-inference-2211.05102.pdf`

### Optional

- [LoongServe](https://dl.acm.org/doi/10.1145/3694715.3695948) — 未下载（需登录/非 PDF 直链，仅记录链接）
- [Alpa](https://arxiv.org/pdf/2201.12023) — 已下载：`papers/alpa-2201.12023.pdf`
- [Arctic](https://arxiv.org/abs/2507.11830) — 已下载：`papers/arctic-2507.11830.pdf`

