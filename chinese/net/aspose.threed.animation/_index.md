---
title: "Aspose.ThreeD.Animation"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.3D 的动画命名空间，所有与动画相关的类都定义在此命名空间中"
type: docs
weight: 20
url: /zh/net/aspose.threed.animation/
---
Aspose.3D 的动画命名空间，所有与动画相关的类都定义在此命名空间中

## 类

| 类 | 描述 |
| --- | --- |
| [AnimationChannel](./animationchannel/) | 通道将属性的组件字段映射到一组关键帧序列 |
| [AnimationClip](./animationclip/) | 动画剪辑是动画的集合。场景可以拥有一个或多个动画剪辑。 |
| [AnimationNode](./animationnode/) | Aspose.3D 支持动画层次结构，每个动画可以由多个动画及其关键帧定义组成。[`AnimationNode`](../aspose.threed.animation/animationnode/) 定义属性值随时间的变化，例如，动画节点可用于控制节点的变换或其他 [`A3DObject`](../aspose.threed/a3dobject/) 对象的数值属性。 |
| [BindPoint](./bindpoint/) | [`BindPoint`](../aspose.threed.animation/bindpoint/) 通常在对象的属性上创建，某些属性类型包含多个组件字段（如 Vector3 字段），[`BindPoint`](../aspose.threed.animation/bindpoint/) 将为每个组件字段生成通道，并通过这些通道将字段连接到一个或多个关键帧序列实例。 |
| [Extrapolation](./extrapolation/) | 外推定义了当采样值超出由首帧和尾帧定义的范围时的处理方式。 |
| [KeyFrame](./keyframe/) | 关键帧主要由时间和值定义，对于某些插值类型，还会使用切线/张力/偏差/连续性来计算最终的采样值。非关键帧时间位置的采样值由前后关键帧之间的关键帧进行插值。首帧/尾帧之前或之后的值由 [`Extrapolation`](../aspose.threed.animation/extrapolation/) 类计算。 |
| [KeyframeSequence](./keyframesequence/) | 关键帧序列，描述采样值随时间的变化。 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [ExtrapolationType](./extrapolationtype/) | 外推类型。 |
| [Interpolation](./interpolation/) | 关键帧的插值类型。 |
| [StepMode](./stepmode/) | 插值步进模式。 |
| [WeightedMode](./weightedmode/) | 加权模式。 |


