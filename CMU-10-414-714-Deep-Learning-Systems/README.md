# 10-414/714 Deep Learning Systems

## 基本信息

| 项目 | 内容 |
| --- | --- |
| 课程名 | 10-414/714 Deep Learning Systems（深度学习系统） |
| 学校 | Carnegie Mellon University（卡内基梅隆大学） |
| 教师 | Tim Dettmers（dettmers@cmu.edu）、Tianqi Chen（tqchen@cmu.edu） |
| 学期 | 2026 秋季（页面 2026 版课表，录像为 2022 版公开课） |
| 课程主页 | https://dlsyscourse.org/lectures/ |
| 作业页面 | https://dlsyscourse.org/assignments/ |

## 教材与参考书

- 课程无正式指定教材；核心材料为课堂 slides 与配套 Jupyter notebook（GitHub 仓库 dlsyscourse/*）。
- 公开课提供 2022 版完整 lecture 录像（YouTube），用于补充复习。
- 推荐背景阅读：*Dive into Deep Learning*（d2l.ai）、PyTorch 官方文档与教程。

## 课程简介

本课程系统讲解深度学习系统的构建方法：学生将从零实现一个功能完整的深度学习库，而不是仅仅调用现成框架。课程从机器学习基础与反向传播出发，讲解自动微分、神经网络库抽象、CPU/GPU 硬件加速、卷积网络、循环网络与 Transformer。后半程覆盖大模型训练、生成模型、预训练模型定制与模型部署。课程强调动手实现，配套 5 次 notebook 作业（mugrade 自动评分）与一个期末项目。

## Lecture 索引

| 编号 | 主题 | 日期 | 材料 |
| --- | --- | --- | --- |
| 1 | Introduction / Logistics | 8/25 | slides.pdf |
| 2 | ML Refresher / Softmax Regression | 8/27 | slides.pdf |
| 3 | Manual Neural Networks / Backprop | 9/1 | slides.pdf |
| 4 | Automatic Differentiation | 9/3 | slides.pdf |
| 5 | Automatic Differentiation Implementation | 9/8 | notebook |
| 6 | Optimization | 9/10 | slides.pdf |
| 7 | Neural Network Library Abstractions | 9/15 | slides.pdf |
| 8 | Normalization, Dropout, + Implementation | 9/17 | slides.pdf |
| 9 | NN Library Implementation | 9/22 | notebook |
| 10 | Hardware Acceleration for Linear Algebra | 9/24 | slides.pdf |
| 11 | Convolutional Networks | 9/29 | slides.pdf |
| 12 | Hardware Acceleration + GPUs | 10/1 | slides.pdf |
| 13 | Hardware Acceleration Implementation | 10/6 | notebook |
| 14 | Convoluations Network Implementation | 10/8 | notebook |
| 15 | Sequence Modeling + RNNs | 10/20 | slides.pdf |
| 16 | Sequence Modeling Implementation | 10/22 | notebook |
| 17 | Transformers and Autoregressive Models | 10/27 | slides.pdf |
| 18 | Transformers Implementation | 10/29 | slides.pdf |
| 19 | Training Large Models | 11/5 | slides.pdf |
| 20 | Generative Models | 11/10 | slides.pdf |
| 21 | Generative Models Implementation | 11/12 | notebook |
| 22 | Customize Pretrained Models | 11/17 | slides.pdf |
| 23 | Model Deployment | 11/19 | 无 slides |
| 25 | Future Directions / Q&A | 11/24 | 无 slides |

> 页面中 10/13、10/15 为 Fall Break，11/3 为 Democracy Day，11/26 为 Thanksgiving，均无课；12/1、12/3 为学生项目汇报；页面讲次编号从 23 直接跳到 25（无第 24 讲）。

## 作业与考试

| 项目 | 发布 | 截止 |
| --- | --- | --- |
| Homework 0（mugrade 上手） | 8/27/26 | 9/10/26 |
| Homework 1 | 9/08/26 | 9/22/26 |
| Homework 2 | 9/22/26 | 10/08/26 |
| Homework 3 | 10/08/26 | 10/29/26 |
| Homework 4 | 10/29/26 | 11/19/26 |
| Homework 4 Extra（仅 714） | 10/29/26 | 11/19/26 |
| Final project | 见课程 assignments 页面 | — |

所有作业 23:59（美东时间）截止，迟交自动消耗 late days（2 天后关闭提交）。作业以 Jupyter notebook + GitHub repo 形式发布，提交通过 mugrade 自动评分系统；除提交答案外还需提交最终代码。

## 目录结构

- `lecture-NN-<slug>/`：第 NN 讲，含 `README.md`；有 PDF slides 的讲次另含 `slides.pdf`
- 以 notebook 形式发布的讲次（5、9、13、14、16、21）无 slides.pdf，README 中给出 notebook 链接
- 视频一律只记录链接，不下载

> 页面结构说明：slides 链接均为 dlsyscourse.org 上的直接 PDF，无 Google Slides/Drive 链接，均可直下。