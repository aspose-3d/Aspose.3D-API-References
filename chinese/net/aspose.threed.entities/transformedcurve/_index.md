---
title: "类 TransformedCurve"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Entities.TransformedCurve 类。TransformedCurve 通过使用变换矩阵为曲线提供位置。这允许在 TrimmedCurve 或 CompositeCurve 中执行变换。"
type: docs
weight: 780
url: /zh/net/aspose.threed.entities/transformedcurve/
---
## TransformedCurve class

`TransformedCurve` 通过使用变换矩阵为曲线提供位置。这允许在 [`TrimmedCurve`](../trimmedcurve/) 或 [`CompositeCurve`](../compositecurve/) 中执行变换。

```csharp
public class TransformedCurve : Curve
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TransformedCurve](transformedcurve/#constructor)() | `TransformedCurve` 的构造函数。 |
| [TransformedCurve](transformedcurve/#constructor_1)(Curve, Matrix4) | `TransformedCurve` 的构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BasisCurve](../../aspose.threed.entities/transformedcurve/basiscurve/) { get; set; } | 基础曲线。 |
| [Color](../../aspose.threed.entities/curve/color/) { get; set; } | 获取或设置线条的颜色，默认值为白色 (1, 1, 1) |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | 获取或设置在导出时是否排除此实体。 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | 获取或设置第一个父节点，如果设置了第一个父节点，则此实体将从其他父节点分离。 |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | 获取所有父节点，实体可以附加到多个父节点以实现几何实例化 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | 获取此对象所属的场景 |
| [TransformMatrix](../../aspose.threed.entities/transformedcurve/transformmatrix/) { get; set; } | 变换矩阵。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本地属性（通过其名称识别） |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | 获取当前实体在其对象空间坐标系中的包围盒。 |
| override [GetEntityRendererKey](../../aspose.threed.entities/curve/getentityrendererkey/)() | 获取在渲染器中注册的实体渲染器的键 |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 获取指定属性的值 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 移除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 移除通过名称识别的指定属性 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 设置指定属性的值 |

### 另请参见

* class [Curve](../curve/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


