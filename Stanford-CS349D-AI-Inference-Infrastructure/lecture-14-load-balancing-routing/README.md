# Lecture 14: Load Balancing & Routing

| 项目 | 内容 |
|---|---|
| 标题 | Load Balancing & Routing |
| 课程 | CS349D: AI Inference Infrastructure（Stanford University, Spring 2026） |
| 讲次 | Lecture 14（论文研讨） |
| 日期 | Wed May 13 |
| 主题 | Load Balancing & Routing |
| 本地材料 | 本讲为论文研讨课，**无 lecture slides**；论文见 `papers/` |
| 原始页面 | http://web.stanford.edu/class/cs349d/ |
| 录像 | 课程主页未提供录像链接（不下载视频） |

## 内容要点

- 请求级全局调度与负载均衡的目标（尾延迟、利用率、SLO）
- Preble：面向 LLM 服务的全局请求调度器
- LLMSELECTOR：多模型/多实例场景下的模型与实例选择
- cache-aware 路由与队列状态感知的调度策略

## 相关阅读

### Required

- [Preble](https://arxiv.org/abs/2407.00023) — 已下载：`papers/preble-2407.00023.pdf`
- [LLMSELECTOR](https://arxiv.org/abs/2502.14815) — 已下载：`papers/llmselector-2502.14815.pdf`

### Optional

- 无（官方日程未列出选读材料）

