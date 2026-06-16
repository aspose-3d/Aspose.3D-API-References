---
title: "类 NurbsDirection"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Entities.NurbsDirection 类。一个 3D NurbsSurface 有两个方向：U 和 V，NurbsDirection 为每个方向定义数据。一个方向实际上是一条 NURBS 曲线，这意味着它同样由其阶次（Order）、节点向量（KnotVectors）以及在 NurbsSurface 中定义的一组加权控制点决定。"
type: docs
weight: 530
url: /zh/net/aspose.threed.entities/nurbsdirection/
---
## NurbsDirection class

一个 3D [`NurbsSurface`](../nurbssurface/) 有两个方向，[`U`](../nurbssurface/u/) 和 [`V`](../nurbssurface/v/)，`NurbsDirection` 为每个方向定义数据。一个方向实际上是一条 NURBS 曲线，这意味着它同样由其 [`Order`](./order/)、[`KnotVectors`](./knotvectors/) 以及一组加权控制点（在 [`NurbsSurface`](../nurbssurface/) 中定义）决定。

```csharp
public class NurbsDirection
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [NurbsDirection](nurbsdirection/)() | 构造 `NurbsDirection` 的新实例 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Count](../../aspose.threed.entities/nurbsdirection/count/) { get; set; } | 获取或设置当前方向的控制点数量。 |
| [Degree](../../aspose.threed.entities/nurbsdirection/degree/) { get; set; } | 获取或设置 NURBS 曲线的次数，次数定义为阶数 - 1。 |
| [Divisions](../../aspose.threed.entities/nurbsdirection/divisions/) { get; set; } | 获取或设置当前方向相邻控制点之间的细分数。 |
| [KnotVectors](../../aspose.threed.entities/nurbsdirection/knotvectors/) { get; } | 获取节点向量，它是一系列参数值，决定控制点在何处以及如何影响 NURBS 曲线。 |
| [Multiplicity](../../aspose.threed.entities/nurbsdirection/multiplicity/) { get; } | 获取重数。 |
| [Order](../../aspose.threed.entities/nurbsdirection/order/) { get; set; } | 获取或设置 NURBS 曲线的阶数，它定义了影响曲线上任意点的邻近控制点数量。 |
| [Type](../../aspose.threed.entities/nurbsdirection/type/) { get; set; } | 获取或设置当前方向的类型。 |

### 另请参见

* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


