# Lecture 09: Context Management

| 项目 | 内容 |
|---|---|
| 标题 | Context Management |
| 课程 | CS349D: AI Inference Infrastructure（Stanford University, Spring 2026） |
| 讲次 | Lecture 09（论文研讨） |
| 日期 | Mon Apr 27 |
| 主题 | Context Management |
| 本地材料 | 本讲为论文研讨课，**无 lecture slides**；论文见 `papers/` |
| 原始页面 | http://web.stanford.edu/class/cs349d/ |
| 录像 | 课程主页未提供录像链接（不下载视频） |

## 内容要点

- 长上下文场景下 KV cache 的容量与复用问题
- MoonCake：以 KVCache 为中心的分离式推理架构
- CacheGen：KV cache 的压缩与流式加载
- 上下文缓存分层（GPU/CPU/远端存储）的代价模型

## 相关阅读

### Required

- [MoonCake](https://arxiv.org/abs/2407.00079) — 已下载：`papers/mooncake-2407.00079.pdf`
- [CacheGen](https://arxiv.org/abs/2310.07240) — 已下载：`papers/cachegen-2310.07240.pdf`

### Optional

- [Strata](https://arxiv.org/abs/2508.18572) — 已下载：`papers/strata-2508.18572.pdf`

