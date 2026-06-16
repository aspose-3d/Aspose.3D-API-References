---
title: "类 RectangleShape"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Profiles.RectangleShape 类。兼容 IFC 的带圆角的矩形形状"
type: docs
weight: 1800
url: /zh/net/aspose.threed.profiles/rectangleshape/
---
## RectangleShape class

兼容 IFC 的带圆角矩形形状。

```csharp
public class RectangleShape : ParameterizedProfile
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [RectangleShape](rectangleshape/#constructor)() | `RectangleShape` 的构造函数 |
| [RectangleShape](rectangleshape/#constructor_1)(double, double) | `RectangleShape` 的构造函数，使用在 x 和 y 轴上的指定尺寸。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | 获取或设置在导出时是否排除此实体。 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | 获取或设置第一个父节点，如果设置了第一个父节点，则此实体将从其他父节点分离。 |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | 获取所有父节点，实体可以附加到多个父节点以实现几何实例化 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |
| [RoundingRadius](../../aspose.threed.profiles/rectangleshape/roundingradius/) { get; set; } | 获取或设置所有四个角的圆弧半径，单位为度。默认值为 0.0 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | 获取此对象所属的场景 |
| [XDim](../../aspose.threed.profiles/rectangleshape/xdim/) { get; set; } | 获取或设置矩形在 x 轴方向的范围。默认值为 2.0 |
| [YDim](../../aspose.threed.profiles/rectangleshape/ydim/) { get; set; } | 获取或设置矩形在 y 轴方向的范围。默认值为 2.0 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本地属性（通过其名称识别） |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | 获取当前实体在其对象空间坐标系中的包围盒。 |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | 获取在渲染器中注册的实体渲染器的键 |
| override [GetExtent](../../aspose.threed.profiles/rectangleshape/getextent/)() | 获取 x 和 y 维度的范围。 |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 获取指定属性的值 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 移除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 移除通过名称识别的指定属性 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 设置指定属性的值 |

### 另请参见

* class [ParameterizedProfile](../parameterizedprofile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


