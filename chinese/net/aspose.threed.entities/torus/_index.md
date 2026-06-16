---
title: "类 Torus"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Entities.Torus 类。参数化 Torus"
type: docs
weight: 770
url: /zh/net/aspose.threed.entities/torus/
---
## Torus class

参数化环面。

```csharp
public class Torus : Primitive
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Torus](torus/#constructor)() | 初始化 `Torus` 类的新实例。 |
| [Torus](torus/#constructor_1)(double, double) | 初始化 `Torus` 类的新实例。 |
| [Torus](torus/#constructor_2)(double, double, double) | 初始化 `Torus` 类的新实例。 |
| [Torus](torus/#constructor_3)(string, double, double, int, int, double) | 初始化 `Torus` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Arc](../../aspose.threed.entities/torus/arc/) { get; set; } | 获取或设置弧。 |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | 获取或设置此几何体是否可以投射阴影 |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | 获取或设置在导出时是否排除此实体。 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | 获取或设置第一个父节点，如果设置了第一个父节点，则此实体将从其他父节点分离。 |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | 获取所有父节点，实体可以附加到多个父节点以实现几何实例化 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |
| [RadialSegments](../../aspose.threed.entities/torus/radialsegments/) { get; set; } | 获取或设置径向段。 |
| [Radius](../../aspose.threed.entities/torus/radius/) { get; set; } | 获取或设置 Torus 的半径。 |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | 获取或设置此几何体是否可以接收阴影。 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | 获取此对象所属的场景 |
| [Tube](../../aspose.threed.entities/torus/tube/) { get; set; } | 获取或设置管的半径。 |
| [TubularSegments](../../aspose.threed.entities/torus/tubularsegments/) { get; set; } | 获取或设置管状段。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本地属性（通过其名称识别） |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | 获取当前实体在其对象空间坐标系中的包围盒。 |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | 获取在渲染器中注册的实体渲染器的键 |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 获取指定属性的值 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 移除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 移除通过名称识别的指定属性 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 设置指定属性的值 |
| override [ToMesh](../../aspose.threed.entities/torus/tomesh/)() | 将当前对象转换为网格 |

### 另请参见

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


