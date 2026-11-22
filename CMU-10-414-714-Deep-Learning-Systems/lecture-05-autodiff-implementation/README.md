# 第 5 讲：Automatic Differentiation Implementation

- **所属课程**：10-414/714 Deep Learning Systems（卡内基梅隆大学，2026 秋季）
- **讲次**：第 5 讲（课程页面编号；页面跳过第 24 讲）
- **日期**：2026 年 9 月 8 日（课程页面标注 9/8）
- **授课教师**：Chen
- **主题**：Automatic Differentiation Implementation
- **本地文件名**：无（该讲以 notebook 形式发布，无 slides PDF）
- **原始 slides URL**：页面未提供 PDF slides（该讲材料为 notebook 或未发布，见「相关阅读与资源」）
- **录像链接**：https://youtu.be/cNADlHfHQHg

## 内容要点

- 从零实现一个自动微分框架：Tensor/Value 节点与算子注册
- 前向执行时记录计算图，反向时按拓扑序传播梯度
- 多维数组（NDArray）后端与广播规则的处理
- 用测试用例验证梯度正确性与计算图复用

## 相关阅读与资源

- 课程主页（lecture 列表）：https://dlsyscourse.org/lectures/
- Notebook（ipynb）：https://github.com/dlsyscourse/lecture5/blob/main/5_automatic_differentiation_implementation.ipynb
- 本讲为 implementation 课，材料以 GitHub notebook 为主，无正式 slides PDF。

---
返回：[课程总览](../README.md)