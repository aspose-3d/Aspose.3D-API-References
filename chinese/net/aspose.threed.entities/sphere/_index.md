---
title: "Sphere 类"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Entities.Sphere 类。参数化球体"
type: docs
weight: 730
url: /zh/net/aspose.threed.entities/sphere/
---
## Sphere class

参数化球体。

```csharp
public class Sphere : Primitive
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Sphere](sphere/#constructor)() | 使用默认半径 1 初始化 `Sphere` 的新实例。 |
| [Sphere](sphere/#constructor_1)(double) | 使用指定半径初始化 `Sphere` 类的新实例。 |
| [Sphere](sphere/#constructor_2)(double, int, int) | 使用指定的半径、宽度段和高度段初始化 `Sphere` 类的新实例。 |
| [Sphere](sphere/#constructor_3)(string, double, int, int, double, double, double, double) | 初始化 `Sphere` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | 获取或设置此几何体是否可以投射阴影 |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | 获取或设置在导出时是否排除此实体。 |
| [HeightSegments](../../aspose.threed.entities/sphere/heightsegments/) { get; set; } | 获取或设置高度段。 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | 获取或设置第一个父节点，如果设置了第一个父节点，则此实体将从其他父节点分离。 |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | 获取所有父节点，实体可以附加到多个父节点以实现几何实例化 |
| [PhiLength](../../aspose.threed.entities/sphere/philength/) { get; set; } | 获取或设置 phi 的长度。 |
| [PhiStart](../../aspose.threed.entities/sphere/phistart/) { get; set; } | 获取或设置 phi 起始值。 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |
| [Radius](../../aspose.threed.entities/sphere/radius/) { get; set; } | 获取或设置球体的半径。 |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | 获取或设置此几何体是否可以接收阴影。 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | 获取此对象所属的场景 |
| [ThetaLength](../../aspose.threed.entities/sphere/thetalength/) { get; set; } | 获取或设置 theta 的长度。 |
| [ThetaStart](../../aspose.threed.entities/sphere/thetastart/) { get; set; } | 获取或设置 theta 起始值。 |
| [WidthSegments](../../aspose.threed.entities/sphere/widthsegments/) { get; set; } | 获取或设置宽度段。 |

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
| override [ToMesh](../../aspose.threed.entities/sphere/tomesh/)() | 将当前对象转换为网格 |

### 另请参见

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


