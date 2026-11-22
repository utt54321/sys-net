# 第 8 讲：Normalization, Dropout, + Implementation

- **所属课程**：10-414/714 Deep Learning Systems（卡内基梅隆大学，2026 秋季）
- **讲次**：第 8 讲（课程页面编号；页面跳过第 24 讲）
- **日期**：2026 年 9 月 17 日（课程页面标注 9/17）
- **授课教师**：Dettmers
- **主题**：Normalization, Dropout, + Implementation
- **本地文件名**：`slides.pdf`（原始文件 `norm_reg.pdf`）
- **原始 slides URL**：https://dlsyscourse.org/slides/norm_reg.pdf
- **录像链接**：https://www.youtube.com/watch?v=ky7qiKyZmnE

## 内容要点

- 归一化：BatchNorm 与 LayerNorm 的计算方式与适用场景
- 训练与推理阶段统计量行为的差异（running mean/var）
- Dropout 的随机失活机制与推理时的缩放
- 上述层的反向传播实现与数值稳定处理

## 相关阅读与资源

- 课程主页（lecture 列表）：https://dlsyscourse.org/lectures/

---
返回：[课程总览](../README.md)