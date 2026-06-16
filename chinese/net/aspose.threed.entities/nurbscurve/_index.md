---
title: "类 NurbsCurve"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Entities.NurbsCurve 类。NURBS 曲线是一种由 NURBSNonuniform 有理基函数样条表示的曲线。NURBS 曲线由其阶、加权控制点集合和节点向量定义。控制点中的 w 分量用作控制点的权重，无论它是二维还是三维。"
type: docs
weight: 520
url: /zh/net/aspose.threed.entities/nurbscurve/
---
## NurbsCurve class

[NURBS curve](https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline) is a curve represented by NURBS(Non-uniform rational basis spline), A NURBS curve is defined by its [`Order`](./order/), a set of weighted [`ControlPoints`](../geometry/controlpoints/) and a [`KnotVectors`](./knotvectors/) The w component in control point is used as control point's weight, whatever it is a TwoDimensional or ThreeDimensional

```csharp
public class NurbsCurve : Curve
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [NurbsCurve](nurbscurve/#constructor)() | 初始化 `NurbsCurve` 类的新实例。 |
| [NurbsCurve](nurbscurve/#constructor_1)(string) | 初始化 `NurbsCurve` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Color](../../aspose.threed.entities/curve/color/) { get; set; } | 获取或设置线条的颜色，默认值为白色 (1, 1, 1) |
| [ControlPoints](../../aspose.threed.entities/nurbscurve/controlpoints/) { get; } | 获取所有控制点 |
| [CurveType](../../aspose.threed.entities/nurbscurve/curvetype/) { get; set; } | 获取或设置曲线的类型。 |
| [Degree](../../aspose.threed.entities/nurbscurve/degree/) { get; set; } | 获取或设置 NURBS 曲线的次数，次数定义为阶数 - 1。 |
| [Dimension](../../aspose.threed.entities/nurbscurve/dimension/) { get; set; } | 获取或设置曲线的维度。 |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | 获取或设置在导出时是否排除此实体。 |
| [KnotVectors](../../aspose.threed.entities/nurbscurve/knotvectors/) { get; } | 获取节点向量，它是一系列参数值，决定控制点在何处以及如何影响 NURBS 曲线。 |
| [Multiplicity](../../aspose.threed.entities/nurbscurve/multiplicity/) { get; } | 获取重数。 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [Order](../../aspose.threed.entities/nurbscurve/order/) { get; set; } | 获取或设置 NURBS 曲线的阶数，它定义了影响曲线上任意点的邻近控制点数量。 |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | 获取或设置第一个父节点，如果设置了第一个父节点，则此实体将从其他父节点分离。 |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | 获取所有父节点，实体可以附加到多个父节点以实现几何实例化 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |
| [Rational](../../aspose.threed.entities/nurbscurve/rational/) { get; set; } | 获取或设置它是否为有理的，此值指示此 `NurbsCurve` 是有理样条还是非有理样条。非有理 B 样条是有理 B 样条的特例。 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | 获取此对象所属的场景 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Evaluate](../../aspose.threed.entities/nurbscurve/evaluate/)(int) | 评估 NURBS 曲线 |
| [EvaluateAt](../../aspose.threed.entities/nurbscurve/evaluateat/)(double) | 在指定位置评估曲线的点 |
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


