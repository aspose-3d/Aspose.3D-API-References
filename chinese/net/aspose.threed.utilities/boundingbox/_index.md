---
title: "Struct BoundingBox"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Utilities.BoundingBox 结构体。轴对齐的边界框"
type: docs
weight: 2670
url: /zh/net/aspose.threed.utilities/boundingbox/
---
## BoundingBox structure

轴对齐包围盒

```csharp
public struct BoundingBox
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [BoundingBox](boundingbox/#constructor)(Vector3, Vector3) | 使用给定的最小角和最大角初始化有限包围盒 |
| [BoundingBox](boundingbox/#constructor_1)(double, double, double, double, double, double) | 使用给定的最小角和最大角初始化有限包围盒 |

## 属性

| 名称 | 描述 |
| --- | --- |
| static [Infinite](../../aspose.threed.utilities/boundingbox/infinite/) { get; } | 无限包围盒 |
| static [Null](../../aspose.threed.utilities/boundingbox/null/) { get; } | 空包围盒 |
| [Center](../../aspose.threed.utilities/boundingbox/center/) { get; } | 边界框的中心。 |
| [Extent](../../aspose.threed.utilities/boundingbox/extent/) { get; } | 获取包围盒的范围。 |
| [Maximum](../../aspose.threed.utilities/boundingbox/maximum/) { get; } | 包围盒的最大角 |
| [Minimum](../../aspose.threed.utilities/boundingbox/minimum/) { get; } | 包围盒的最小角 |
| [Size](../../aspose.threed.utilities/boundingbox/size/) { get; } | 边界框的大小 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [FromGeometry](../../aspose.threed.utilities/boundingbox/fromgeometry/)(Geometry) | 从给定几何体构建边界框 |
| [Contains](../../aspose.threed.utilities/boundingbox/contains/#contains)(BoundingBox) | 用于检查它是否在当前边界框内部的边界框。 |
| [Contains](../../aspose.threed.utilities/boundingbox/contains/#contains_1)(Vector3) | 检查点 p 是否在边界框内部 |
| override [Equals](../../aspose.threed.utilities/boundingbox/equals/)(object) | 确定两个对象是否相等 |
| override [GetHashCode](../../aspose.threed.utilities/boundingbox/gethashcode/)() | 返回此实例的哈希码 |
| [Merge](../../aspose.threed.utilities/boundingbox/merge/#merge)(BoundingBox) | 将新盒合并到当前包围盒中。 |
| [Merge](../../aspose.threed.utilities/boundingbox/merge/#merge_1)(Vector3) | 将当前边界框与给定点合并 |
| [Merge](../../aspose.threed.utilities/boundingbox/merge/#merge_2)(Vector4) | 将当前边界框与给定点合并 |
| [Merge](../../aspose.threed.utilities/boundingbox/merge/#merge_3)(double, double, double) | 将当前边界框与给定点合并 |
| [OverlapsWith](../../aspose.threed.utilities/boundingbox/overlapswith/)(BoundingBox) | 检查当前边界框是否与指定的边界框重叠。 |
| [Scale](../../aspose.threed.utilities/boundingbox/scale/)() | 计算任何包含点的绝对最大坐标值。 |
| override [ToString](../../aspose.threed.utilities/boundingbox/tostring/)() | 获取包围盒的字符串表示形式。 |
| [operator *](../../aspose.threed.utilities/boundingbox/op_multiply/) | 乘法运算符重载，新边界框的最小和最大角将被矩阵变换。 |

## 示例

以下代码展示了如何从 Entity 实例获取边界框。

```csharp
var sphere = new Sphere();
var boundingBox = sphere.GetBoundingBox();
Console.WriteLine("Bounding box = " + boundingBox);
```

### 另请参见

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


