---
layout: page
title: 面向目标检测的感知不确定性量化与评测支撑
description: 基于证据理论构建自动驾驶目标检测可靠性评估信号
importance: 1
category: research
related_publications: false
---

该项目聚焦自动驾驶目标检测在 corner case 下的高置信度误检风险，尝试在主检测结果之外构建可解释的风险评估信号，用于支撑模型可靠性分析。

主要工作：

- 基于 Dirichlet 证据理论设计目标检测不确定性量化指标。
- 使用 CODA、BDD100K 等极端场景数据集筛选和整理评测样本。
- 解析 JSON 标注文件，拆分并对齐预测结果与标注数据。
- 支撑不确定性量化结果的批量评估与可靠性分析。

关键词：Autonomous Driving, Object Detection, Uncertainty Quantification, Reliability Evaluation.
