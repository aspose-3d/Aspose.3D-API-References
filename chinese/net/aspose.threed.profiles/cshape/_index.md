---
title: "类 CShape"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Profiles.CShape 类。兼容 IFC 的 Cshape 型材，由参数定义。型材的中心位置位于包围盒的中心"
type: docs
weight: 1680
url: /zh/net/aspose.threed.profiles/cshape/
---
## CShape class

兼容 IFC 的 C 形配置文件，由参数定义。配置文件的中心位置位于包围盒的中心。

```csharp
public class CShape : ParameterizedProfile
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [CShape](cshape/)() | `CShape` 的构造函数 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Depth](../../aspose.threed.profiles/cshape/depth/) { get; set; } | 获取或设置型材的深度。 |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | 获取或设置在导出时是否排除此实体。 |
| [Girth](../../aspose.threed.profiles/cshape/girth/) { get; set; } | 获取或设置周长的长度。 |
| [InternalFilletRadius](../../aspose.threed.profiles/cshape/internalfilletradius/) { get; set; } | 获取或设置内部圆角半径。 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | 获取或设置第一个父节点，如果设置了第一个父节点，则此实体将从其他父节点分离。 |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | 获取所有父节点，实体可以附加到多个父节点以实现几何实例化 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | 获取此对象所属的场景 |
| [WallThickness](../../aspose.threed.profiles/cshape/wallthickness/) { get; set; } | 获取或设置墙体的厚度。 |
| [Width](../../aspose.threed.profiles/cshape/width/) { get; set; } | 获取或设置型材的宽度。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本地属性（通过其名称识别） |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | 获取当前实体在其对象空间坐标系中的包围盒。 |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | 获取在渲染器中注册的实体渲染器的键 |
| override [GetExtent](../../aspose.threed.profiles/cshape/getextent/)() | 获取 x 和 y 维度的范围。 |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 获取指定属性的值 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 移除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 移除通过名称识别的指定属性 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 设置指定属性的值 |

### 另请参见

* class [ParameterizedProfile](../parameterizedprofile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


