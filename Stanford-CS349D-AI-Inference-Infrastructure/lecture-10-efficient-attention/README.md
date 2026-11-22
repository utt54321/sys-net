# Lecture 10: Efficient Attention

| 项目 | 内容 |
|---|---|
| 标题 | Efficient Attention |
| 课程 | CS349D: AI Inference Infrastructure（Stanford University, Spring 2026） |
| 讲次 | Lecture 10（论文研讨） |
| 日期 | Wed Apr 29 |
| 主题 | Efficient Attention |
| 本地材料 | 本讲为论文研讨课，**无 lecture slides**；论文见 `papers/` |
| 原始页面 | http://web.stanford.edu/class/cs349d/ |
| 录像 | 课程主页未提供录像链接（不下载视频） |

## 内容要点

- FlashAttention：IO 感知的精确注意力计算与分块策略
- FlashInfer：面向 LLM 服务的高性能注意力内核库
- 注意力算子与 GPU 存储层次、并行维度的匹配
- 低精度与新一代硬件上的注意力优化方向（FA3/FA4 为选读）

## 相关阅读

### Required

- [FlashAttention](https://arxiv.org/abs/2205.14135) — 已下载：`papers/flashattention-2205.14135.pdf`
- [FlashInfer](https://arxiv.org/abs/2501.01005) — 已下载：`papers/flashinfer-2501.01005.pdf`

### Optional

- [FA3](https://arxiv.org/abs/2407.08608) — 已下载：`papers/fa3-2407.08608.pdf`
- [FA4](https://arxiv.org/abs/2603.05451) — 已下载：`papers/fa4-2603.05451.pdf`

