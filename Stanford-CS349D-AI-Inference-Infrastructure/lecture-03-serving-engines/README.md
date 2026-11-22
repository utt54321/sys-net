# Lecture 03: Serving Engines

| 项目 | 内容 |
|---|---|
| 标题 | Serving Engines |
| 课程 | CS349D: AI Inference Infrastructure（Stanford University, Spring 2026） |
| 讲次 | Lecture 03（论文研讨） |
| 日期 | Mon Apr 6 |
| 主题 | Serving Engines |
| 本地材料 | 本讲为论文研讨课，**无 lecture slides**；论文见 `papers/` |
| 原始页面 | http://web.stanford.edu/class/cs349d/ |
| 录像 | 课程主页未提供录像链接（不下载视频） |

## 内容要点

- vLLM / PagedAttention：用分页式 KV cache 管理消除显存碎片
- SGLang：结构化生成语言与 RadixAttention 前缀复用
- 连续批处理、KV cache 复用与请求调度如何共同决定吞吐与延迟
- 主流 serving engine 的架构对比与工程取舍

## 相关阅读

### Required

- [PagedAttention](https://arxiv.org/abs/2309.06180) — 已下载：`papers/pagedattention-2309.06180.pdf`
- [SGLang](https://arxiv.org/abs/2312.07104) — 已下载：`papers/sglang-2312.07104.pdf`

### Optional

- 无（官方日程未列出选读材料）

