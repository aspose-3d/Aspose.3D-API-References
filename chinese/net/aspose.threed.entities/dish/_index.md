---
title: "类 Dish"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Entities.Dish 类。参数化 Dish"
type: docs
weight: 370
url: /zh/net/aspose.threed.entities/dish/
---
## Dish class

参数化抛物面。

```csharp
public class Dish : Primitive
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Dish](dish/#constructor)() | 创建一个具有默认半径(10)和默认高度(5)的新 Dish 实例 |
| [Dish](dish/#constructor_1)(double, double) | 创建一个具有指定半径和高度的新 Dish 实例 |
| [Dish](dish/#constructor_2)(string, double, double, int, int) | 创建一个具有指定半径和高度的新 Dish 实例 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | 获取或设置此几何体是否可以投射阴影 |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | 获取或设置在导出时是否排除此实体。 |
| [Height](../../aspose.threed.entities/dish/height/) { get; set; } | Dish 的高度 |
| [HeightSegments](../../aspose.threed.entities/dish/heightsegments/) { get; set; } | 获取或设置高度段 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | 获取或设置第一个父节点，如果设置了第一个父节点，则此实体将从其他父节点分离。 |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | 获取所有父节点，实体可以附加到多个父节点以实现几何实例化 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |
| [Radius](../../aspose.threed.entities/dish/radius/) { get; set; } | Dish 的半径 |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | 获取或设置此几何体是否可以接收阴影。 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | 获取此对象所属的场景 |
| [WidthSegments](../../aspose.threed.entities/dish/widthsegments/) { get; set; } | 获取或设置宽度段 |

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
| override [ToMesh](../../aspose.threed.entities/dish/tomesh/)() | 将当前对象转换为网格 |

### 另请参见

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


