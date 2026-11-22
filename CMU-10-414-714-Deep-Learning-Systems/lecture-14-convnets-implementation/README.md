# 第 14 讲：Convoluations Network Implementation

- **所属课程**：10-414/714 Deep Learning Systems（卡内基梅隆大学，2026 秋季）
- **讲次**：第 14 讲（课程页面编号；页面跳过第 24 讲）
- **日期**：2026 年 10 月 8 日（课程页面标注 10/8）
- **授课教师**：Dettmers
- **主题**：Convoluations Network Implementation
- **本地文件名**：无（该讲以 notebook 形式发布，无 slides PDF）
- **原始 slides URL**：页面未提供 PDF slides（该讲材料为 notebook 或未发布，见「相关阅读与资源」）
- **录像链接**：https://youtu.be/7kclgMIcMq0

## 内容要点

- 卷积的高效实现：直接卷积、im2col + GEMM、Winograd
- 卷积反向传播（对输入与对权重）的推导
- 内存占用与计算量的权衡
- 用 notebook 逐步实现并对比性能

## 相关阅读与资源

- 课程主页（lecture 列表）：https://dlsyscourse.org/lectures/
- Notebook（ipynb）：https://github.com/dlsyscourse/public_notebooks/blob/main/convolution_implementation.ipynb
- 代码（py）：https://github.com/dlsyscourse/public_notebooks/blob/main/conv.py
- 本讲为 implementation 课，材料以 GitHub notebook 为主，无正式 slides PDF。

---
返回：[课程总览](../README.md)