---
title: "类 UShape"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Profiles.UShape 类。符合 IFC 标准的 Ushape 由参数定义。"
type: docs
weight: 1840
url: /zh/net/aspose.threed.profiles/ushape/
---
## UShape class

兼容 IFC 的 U 形，由参数定义。

```csharp
public class UShape : ParameterizedProfile
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [UShape](ushape/)() | `UShape` 的构造函数 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Depth](../../aspose.threed.profiles/ushape/depth/) { get; set; } | 获取或设置腹板的长度。 |
| [EdgeRadius](../../aspose.threed.profiles/ushape/edgeradius/) { get; set; } | 获取或设置法兰边缘的半径。 |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | 获取或设置在导出时是否排除此实体。 |
| [FilletRadius](../../aspose.threed.profiles/ushape/filletradius/) { get; set; } | 获取或设置翼缘与腹板之间的圆角半径。 |
| [FlangeThickness](../../aspose.threed.profiles/ushape/flangethickness/) { get; set; } | 获取或设置翼缘的厚度。 |
| [FlangeWidth](../../aspose.threed.profiles/ushape/flangewidth/) { get; set; } | 获取或设置翼缘的长度。 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | 获取或设置第一个父节点，如果设置了第一个父节点，则此实体将从其他父节点分离。 |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | 获取所有父节点，实体可以附加到多个父节点以实现几何实例化 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | 获取此对象所属的场景 |
| [WebThickness](../../aspose.threed.profiles/ushape/webthickness/) { get; set; } | 获取或设置腹板的厚度。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本地属性（通过其名称识别） |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | 获取当前实体在其对象空间坐标系中的包围盒。 |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | 获取在渲染器中注册的实体渲染器的键 |
| override [GetExtent](../../aspose.threed.profiles/ushape/getextent/)() | 获取 x 和 y 维度的范围。 |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 获取指定属性的值 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 移除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 移除通过名称识别的指定属性 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 设置指定属性的值 |

### 另请参见

* class [ParameterizedProfile](../parameterizedprofile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


