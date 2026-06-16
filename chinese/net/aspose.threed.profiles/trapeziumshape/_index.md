---
title: "类 TrapeziumShape"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Profiles.TrapeziumShape 类。符合 IFC 标准的 Trapezium 形状由参数定义。"
type: docs
weight: 1830
url: /zh/net/aspose.threed.profiles/trapeziumshape/
---
## TrapeziumShape class

兼容 IFC 的梯形形状，由参数定义。

```csharp
public class TrapeziumShape : ParameterizedProfile
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TrapeziumShape](trapeziumshape/)() | `TrapeziumShape` 的构造函数 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BottomXDim](../../aspose.threed.profiles/trapeziumshape/bottomxdim/) { get; set; } | 获取或设置沿 x 轴测量的底线范围。 |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | 获取或设置在导出时是否排除此实体。 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | 获取或设置第一个父节点，如果设置了第一个父节点，则此实体将从其他父节点分离。 |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | 获取所有父节点，实体可以附加到多个父节点以实现几何实例化 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | 获取此对象所属的场景 |
| [TopXDim](../../aspose.threed.profiles/trapeziumshape/topxdim/) { get; set; } | 获取或设置沿 x 轴测量的顶线范围。 |
| [TopXOffset](../../aspose.threed.profiles/trapeziumshape/topxoffset/) { get; set; } | 获取或设置从顶线起点到底线的偏移量。 |
| [YDim](../../aspose.threed.profiles/trapeziumshape/ydim/) { get; set; } | 获取或设置沿 y 轴测量的顶线与底线之间的距离。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本地属性（通过其名称识别） |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | 获取当前实体在其对象空间坐标系中的包围盒。 |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | 获取在渲染器中注册的实体渲染器的键 |
| override [GetExtent](../../aspose.threed.profiles/trapeziumshape/getextent/)() | 获取 x 和 y 维度的范围。 |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 获取指定属性的值 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 移除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 移除通过名称识别的指定属性 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 设置指定属性的值 |

### 另请参见

* class [ParameterizedProfile](../parameterizedprofile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


