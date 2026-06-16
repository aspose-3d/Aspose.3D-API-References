---
title: "类 Line"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Entities.Line 类。折线是由一组带有 ControlPoints 的点定义并通过 Segments 连接的路径，这意味着它也可以是一组连接的线段。该线通常是线性对象，这意味着它不能用于表示曲线，如需表示曲线请使用 NurbsCurve。"
type: docs
weight: 480
url: /zh/net/aspose.threed.entities/line/
---
## Line class

折线是由一组带有 [`ControlPoints`](../geometry/controlpoints/) 的点定义，并通过 [`Segments`](./segments/) 连接，这意味着它也可以是一组连接的线段。该线通常是线性对象，这意味着它不能用于表示曲线，如需表示曲线，请使用 [`NurbsCurve`](../nurbscurve/)。

```csharp
public class Line : Curve
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Line](line/#constructor)() | 初始化 `Line` 类的新实例。 |
| [Line](line/#constructor_1)(string) | 初始化 `Line` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Color](../../aspose.threed.entities/curve/color/) { get; set; } | 获取或设置线条的颜色，默认值为白色 (1, 1, 1) |
| [ControlPoints](../../aspose.threed.entities/line/controlpoints/) { get; } | 获取所有控制点 |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | 获取或设置在导出时是否排除此实体。 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | 获取或设置第一个父节点，如果设置了第一个父节点，则此实体将从其他父节点分离。 |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | 获取所有父节点，实体可以附加到多个父节点以实现几何实例化 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | 获取此对象所属的场景 |
| [Segments](../../aspose.threed.entities/line/segments/) { get; } | 获取线的段 |
| [Visible](../../aspose.threed.entities/line/visible/) { get; set; } | 获取或设置几何体是否可见 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [FromPoints](../../aspose.threed.entities/line/frompoints/)(params Vector3[]) | 从一组点构造一个 `Line` 实例。 |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本地属性（通过其名称识别） |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | 获取当前实体在其对象空间坐标系中的包围盒。 |
| override [GetEntityRendererKey](../../aspose.threed.entities/curve/getentityrendererkey/)() | 获取在渲染器中注册的实体渲染器的键 |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 获取指定属性的值 |
| [MakeDefaultIndices](../../aspose.threed.entities/line/makedefaultindices/)() | 生成序列 0,1,2,3....[`ControlPoints`](../geometry/controlpoints/).Length-1 到 [`Segments`](./segments/) 以便将 ControlPoints 用作单条线 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 移除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 移除通过名称识别的指定属性 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 设置指定属性的值 |

### 另请参见

* class [Curve](../curve/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


