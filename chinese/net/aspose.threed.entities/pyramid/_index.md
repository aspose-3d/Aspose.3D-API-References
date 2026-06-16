---
title: "类 Pyramid"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Entities.Pyramid 类。 参数化金字塔"
type: docs
weight: 650
url: /zh/net/aspose.threed.entities/pyramid/
---
## Pyramid class

参数化金字塔。

```csharp
public class Pyramid : Primitive
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Pyramid](pyramid/#constructor)() | 使用默认底部面积(10, 10)和默认高度(5)构造一个新的金字塔实例 |
| [Pyramid](pyramid/#constructor_1)(double, double, double) | 使用指定的底部面积构造一个新的金字塔实例 |
| [Pyramid](pyramid/#constructor_2)(double, double, double, double, double) | 使用指定的底部面积、顶部面积和高度构造一个新的金字塔实例。 |
| [Pyramid](pyramid/#constructor_3)(string, double, double, double, double, double) | 使用指定的底部面积、顶部面积和高度构造一个新的金字塔实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BottomArea](../../aspose.threed.entities/pyramid/bottomarea/) { get; set; } | 底部盖面的面积 |
| [BottomOffset](../../aspose.threed.entities/pyramid/bottomoffset/) { get; set; } | 底部顶点的偏移 |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | 获取或设置此几何体是否可以投射阴影 |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | 获取或设置在导出时是否排除此实体。 |
| [Height](../../aspose.threed.entities/pyramid/height/) { get; set; } | 金字塔的高度 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | 获取或设置第一个父节点，如果设置了第一个父节点，则此实体将从其他父节点分离。 |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | 获取所有父节点，实体可以附加到多个父节点以实现几何实例化 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | 获取或设置此几何体是否可以接收阴影。 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | 获取此对象所属的场景 |
| [TopArea](../../aspose.threed.entities/pyramid/toparea/) { get; set; } | 顶部盖面的面积 |

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
| override [ToMesh](../../aspose.threed.entities/pyramid/tomesh/)() | 将当前对象转换为网格 |

### 另请参见

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


