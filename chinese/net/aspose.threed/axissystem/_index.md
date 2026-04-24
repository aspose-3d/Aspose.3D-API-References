---
title: 类 AxisSystem
second_title: Aspose.3D for .NET API 参考手册
description: Aspose.ThreeD.AxisSystem 类。轴系统是坐标系的上向量和前向量的组合
type: docs
weight: 150
url: /zh/net/aspose.threed/axissystem/
---
## AxisSystem class

轴系是坐标系统、上向量和前向量的组合。

```csharp
public class AxisSystem
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [AxisSystem](axissystem/#constructor)(Axis, Axis?) |  |
| [AxisSystem](axissystem/#constructor_1)(CoordinateSystem, Axis) | 构造一个新的 axis system |
| [AxisSystem](axissystem/#constructor_2)(CoordinateSystem, Axis, Axis) | 构造一个新的 axis system |
| [AxisSystem](axissystem/#constructor_3)(CoordinateSystem?, Axis?, Axis?) |  |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CoordinateSystem](../../aspose.threed/axissystem/coordinatesystem/) { get; } | 获取此 axis system 的坐标系。 |
| [Front](../../aspose.threed/axissystem/front/) { get; } | 获取此 axis system 的前向量 |
| [Up](../../aspose.threed/axissystem/up/) { get; } | 获取此 axis system 的上向量。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [FromAssetInfo](../../aspose.threed/axissystem/fromassetinfo/)(AssetInfo) | 从[`AssetInfo`](../assetinfo/)创建`AxisSystem` |
| [TransformTo](../../aspose.threed/axissystem/transformto/)(AxisSystem) | 创建一个矩阵，用于将当前 axis system 转换为目标 axis system。 |

### 另请参见

* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


