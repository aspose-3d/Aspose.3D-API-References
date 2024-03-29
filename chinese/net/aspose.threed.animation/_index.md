---
title: Aspose.ThreeD.Animation
second_title: Aspose.3D for .NET API 参考
description: Aspose.3D的动画命名空间所有动画相关的类都定义在这个命名空间
type: docs
weight: 20
url: /zh/net/aspose.threed.animation/
---
Aspose.3D的动画命名空间，所有动画相关的类都定义在这个命名空间

## 课程

| 班级 | 描述 |
| --- | --- |
| [AnimationChannel](./animationchannel) | 通道将属性的组件字段映射到一组关键帧序列 |
| [AnimationClip](./animationclip) | 动画剪辑是动画的集合。 场景可以有一个或多个动画剪辑。 |
| [AnimationNode](./animationnode) | Aspose.3D 支持动画层次结构，每个动画可以由多个动画和动画的关键帧定义组成。 [`AnimationNode`](../aspose.threed.animation/animationnode)定义一个属性值随时间的变换，例如动画节点可以用来控制一个节点的变换或其他[`A3DObject`](../aspose.threed/a3dobject)对象的数值属性. |
| [BindPoint](./bindpoint) | 一个[`BindPoint`](../aspose.threed.animation/bindpoint)通常在对象的属性上创建，某些属性类型包含多个组件字段（如 Vector3 字段）， [`BindPoint`](../aspose.threed.animation/bindpoint)将为每个组件字段生成通道，并通过通道将字段连接到一个或多个关键帧序列实例。 |
| [Extrapolation](./extrapolation) | 外推定义了当采样值超出第一个和最后一个关键帧定义的范围时如何做。 |
| [KeyFrame](./keyframe) | 一个关键帧主要由一个时间和一个值来定义，对于一些插值类型，通过计算最终的采样值也使用切线/张力/偏差/连续性。 在非关键帧时间位置的采样值被插值通过前一个和下一个关键帧之间的关键帧 第一个/最后一个关键帧之前/之后的值由[`Extrapolation`](../aspose.threed.animation/extrapolation)类. |
| [KeyframeSequence](./keyframesequence) | 关键帧序列，它描述了采样值随时间的变换。 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [ExtrapolationType](./extrapolationtype) | 外推类型。 |
| [Interpolation](./interpolation) | 关键帧的插值类型。 |
| [StepMode](./stepmode) | 插补步进模式。 |
| [WeightedMode](./weightedmode) | 加权模式。 |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
