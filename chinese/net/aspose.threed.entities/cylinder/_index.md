---
title: "类 Cylinder"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Entities.Cylinder 类。参数化圆柱体。当 radiusTop/radiusBottom 中的一个为零时，它也可用于表示圆锥体"
type: docs
weight: 360
url: /zh/net/aspose.threed.entities/cylinder/
---
## Cylinder class

参数化圆柱体。当 radiusTop/radiusBottom 中有一个为零时，它也可用于表示圆锥体。

```csharp
public class Cylinder : Primitive
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Cylinder](cylinder/#constructor)() | 初始化 `Cylinder` 类的新实例。 |
| [Cylinder](cylinder/#constructor_1)(double, double) | 初始化 `Cylinder` 类的新实例。 |
| [Cylinder](cylinder/#constructor_2)(double, double, double) | 初始化 `Cylinder` 类的新实例。 |
| [Cylinder](cylinder/#constructor_3)(double, double, double, int, int, bool) | 初始化 `Cylinder` 类的新实例。 |
| [Cylinder](cylinder/#constructor_4)(string, double, double, double, int, int, bool, double, double) | 初始化 `Cylinder` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | 获取或设置此几何体是否可以投射阴影 |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | 获取或设置在导出时是否排除此实体。 |
| [GenerateFanCylinder](../../aspose.threed.entities/cylinder/generatefancylinder/) { get; set; } | 获取或设置当 ThetaLength 小于 2*PI 时是否生成扇形圆柱体，否则模型将不会被裁剪。 |
| [Height](../../aspose.threed.entities/cylinder/height/) { get; set; } | 获取或设置圆柱体的高度。 |
| [HeightSegments](../../aspose.threed.entities/cylinder/heightsegments/) { get; set; } | 获取或设置高度段。 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [OffsetBottom](../../aspose.threed.entities/cylinder/offsetbottom/) { get; set; } | 获取或设置底部侧的顶点变换偏移。 |
| [OffsetTop](../../aspose.threed.entities/cylinder/offsettop/) { get; set; } | 获取或设置顶部侧的顶点变换偏移量。 |
| [OpenEnded](../../aspose.threed.entities/cylinder/openended/) { get; set; } | 获取或设置一个值，指示此 `Cylinder` 是否为开放式。默认值为 false。 |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | 获取或设置第一个父节点，如果设置了第一个父节点，则此实体将从其他父节点分离。 |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | 获取所有父节点，实体可以附加到多个父节点以实现几何实例化 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |
| [RadialSegments](../../aspose.threed.entities/cylinder/radialsegments/) { get; set; } | 获取或设置径向段。 |
| [RadiusBottom](../../aspose.threed.entities/cylinder/radiusbottom/) { get; set; } | 获取或设置圆柱体底部盖的半径。 |
| [RadiusTop](../../aspose.threed.entities/cylinder/radiustop/) { get; set; } | 获取或设置圆柱体顶部盖的半径。 |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | 获取或设置此几何体是否可以接收阴影。 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | 获取此对象所属的场景 |
| [ShearBottom](../../aspose.threed.entities/cylinder/shearbottom/) { get; set; } | 获取或设置底部侧的剪切变换，向量存储以弧度计的 (x 轴, z 轴) 剪切值，默认值为 (0, 0)。 |
| [ShearTop](../../aspose.threed.entities/cylinder/sheartop/) { get; set; } | 获取或设置顶部侧的剪切变换，向量存储以弧度计的 (x 轴, z 轴) 剪切值，默认值为 (0, 0)。 |
| [ThetaLength](../../aspose.threed.entities/cylinder/thetalength/) { get; set; } | 获取或设置 theta 的长度。默认值为 2π。 |
| [ThetaStart](../../aspose.threed.entities/cylinder/thetastart/) { get; set; } | 获取或设置 theta 的起始值。默认值为 0。 |

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
| override [ToMesh](../../aspose.threed.entities/cylinder/tomesh/)() | 将当前对象转换为网格 |

### 另请参见

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


