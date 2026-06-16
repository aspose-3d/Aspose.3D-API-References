---
title: "类 CircleShape"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Profiles.CircleShape 类。符合 IFC 的圆形轮廓，可通过 LinearExtrusion 构建网格"
type: docs
weight: 1700
url: /zh/net/aspose.threed.profiles/circleshape/
---
## CircleShape class

符合 IFC 的圆形轮廓，可通过 [`LinearExtrusion`](../../aspose.threed.entities/linearextrusion/) 构建网格

```csharp
public class CircleShape : ParameterizedProfile
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [CircleShape](circleshape/#constructor)() | 使用默认半径 (5) 构造一个 `CircleShape` 轮廓。 |
| [CircleShape](circleshape/#constructor_1)(double) | 使用指定半径构造一个 `CircleShape` 轮廓。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | 获取或设置在导出时是否排除此实体。 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | 获取或设置第一个父节点，如果设置了第一个父节点，则此实体将从其他父节点分离。 |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | 获取所有父节点，实体可以附加到多个父节点以实现几何实例化 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |
| [Radius](../../aspose.threed.profiles/circleshape/radius/) { get; set; } | 获取或设置圆的半径。 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | 获取此对象所属的场景 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本地属性（通过其名称识别） |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | 获取当前实体在其对象空间坐标系中的包围盒。 |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | 获取在渲染器中注册的实体渲染器的键 |
| override [GetExtent](../../aspose.threed.profiles/circleshape/getextent/)() | 获取 x 和 y 维度的范围。 |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 获取指定属性的值 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 移除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 移除通过名称识别的指定属性 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 设置指定属性的值 |

### 另请参见

* class [ParameterizedProfile](../parameterizedprofile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


