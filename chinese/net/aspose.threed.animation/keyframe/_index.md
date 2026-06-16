---
title: "类 KeyFrame"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Animation.KeyFrame 类。关键帧主要由时间和值定义，对于某些插值类型，还会使用切线/张力/偏差/连续性来计算最终的采样值。非关键帧时间位置的采样值由前后关键帧之间的关键帧进行插值。第一个/最后一个关键帧之前/之后的值由 Extrapolation 类计算"
type: docs
weight: 90
url: /zh/net/aspose.threed.animation/keyframe/
---
## KeyFrame class

关键帧主要由时间和值定义，对于某些插值类型，切线/张力/偏差/连续性也用于计算最终的采样值。非关键帧时间位置的采样值由前后关键帧之间的关键帧进行插值。第一个/最后一个关键帧之前/之后的值由 [`Extrapolation`](../extrapolation/) 类计算。

```csharp
public class KeyFrame
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [KeyFrame](keyframe/)(KeyframeSequence, double) | 在指定曲线上创建新的关键帧 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Bias](../../aspose.threed.animation/keyframe/bias/) { get; set; } | 获取或设置 TCB 样条中使用的偏差 |
| [Continuity](../../aspose.threed.animation/keyframe/continuity/) { get; set; } | 获取或设置 TCB 样条中使用的连续性 |
| [Flat](../../aspose.threed.animation/keyframe/flat/) { get; set; } | 获取或设置关键帧是否为平坦。如果下一个或上一个关键帧具有相同的值，则关键帧应为平坦。平坦的关键帧具有平坦的切线和固定的插值。 |
| [IndependentTangent](../../aspose.threed.animation/keyframe/independenttangent/) { get; set; } | 获取或设置外切线和下一个内切线相互独立。 |
| [Interpolation](../../aspose.threed.animation/keyframe/interpolation/) { get; set; } | 获取或设置关键帧的插值类型，list.data[index] 定义了计算采样值的算法。 |
| [NextInTangent](../../aspose.threed.animation/keyframe/nextintangent/) { get; set; } | 获取或设置此关键帧的下一个内切线（左）。 |
| [NextInWeight](../../aspose.threed.animation/keyframe/nextinweight/) { get; set; } | 获取或设置此关键帧的下一个内切线（左）权重。 |
| [OutTangent](../../aspose.threed.animation/keyframe/outtangent/) { get; set; } | 获取或设置此关键帧的外切线（右）。 |
| [OutWeight](../../aspose.threed.animation/keyframe/outweight/) { get; set; } | 获取或设置此关键帧的外切线（右）权重。 |
| [StepMode](../../aspose.threed.animation/keyframe/stepmode/) { get; set; } | 获取或设置关键帧的步进模式。如果插值类型为 Constant，list.data[index] 决定在插值期间使用哪个关键帧的值。PreviousValue 表示使用左侧关键帧的值，NextValue 表示使用下一个右侧关键帧的值。 |
| [TangentWeightMode](../../aspose.threed.animation/keyframe/tangentweightmode/) { get; set; } | 获取或设置键的切线权重模式。可以通过选择正确的[`WeightedMode`](../weightedmode/)来自定义出切线或下一个入切线。 |
| [Tension](../../aspose.threed.animation/keyframe/tension/) { get; set; } | 获取或设置在 TCB 样条中使用的张力 |
| [Time](../../aspose.threed.animation/keyframe/time/) { get; set; } | 获取或设置 list.data[index] 键帧的时间位置，以秒为单位。 |
| [TimeIndependentTangent](../../aspose.threed.animation/keyframe/timeindependenttangent/) { get; set; } | 获取或设置切线是否与时间无关 |
| [Value](../../aspose.threed.animation/keyframe/value/) { get; set; } | 获取或设置关键帧的值。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [ToString](../../aspose.threed.animation/keyframe/tostring/)() | 获取关键帧的字符串表示形式 |

### 另请参见

* namespace [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* assembly [Aspose.3D](../../)


