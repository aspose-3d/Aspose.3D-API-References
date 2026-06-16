---
title: "结构体 EndPoint"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Entities.EndPoint 结构体。用于修剪曲线的端点可以是参数值或笛卡尔点"
type: docs
weight: 390
url: /zh/net/aspose.threed.entities/endpoint/
---
## EndPoint structure

用于修剪曲线的端点，可以是参数值或笛卡尔点。

```csharp
public struct EndPoint
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EndPoint](endpoint/#constructor_1)(double) | 从实数参数构造 `EndPoint`。 |
| [EndPoint](endpoint/#constructor)(Vector3) | 从笛卡尔点构造 `EndPoint`。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AsPoint](../../aspose.threed.entities/endpoint/aspoint/) { get; } | 获取端点作为笛卡尔点，或抛出异常。 |
| [AsValue](../../aspose.threed.entities/endpoint/asvalue/) { get; } | 获取端点作为实数参数，或抛出异常。 |
| [IsCartesianPoint](../../aspose.threed.entities/endpoint/iscartesianpoint/) { get; } | 端点是笛卡尔点吗？ |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [FromDegree](../../aspose.threed.entities/endpoint/fromdegree/)(double) | 创建一个以度为单位的端点。 |
| static [FromRadian](../../aspose.threed.entities/endpoint/fromradian/)(double) | 创建一个以弧度为单位的端点。 |
| override [ToString](../../aspose.threed.entities/endpoint/tostring/)() | 返回当前端点的字符串表示。 |

### 另请参见

* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


