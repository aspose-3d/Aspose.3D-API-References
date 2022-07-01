---
title: PointCloud
second_title: Aspose.3D for .NET API 参考
description: 点云不包含拓扑信息只包含控制点和顶点元素
type: docs
weight: 540
url: /zh/net/aspose.threed.entities/pointcloud/
---
## PointCloud class

点云不包含拓扑信息，只包含控制点和顶点元素。

```csharp
public class PointCloud : Geometry
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [PointCloud](pointcloud#constructor)() | [`PointCloud`](../pointcloud) |
| [PointCloud](pointcloud#constructor_1)(string) | [`PointCloud`](../pointcloud) |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/geometry/castshadows) { get; set; } | 获取或设置此几何是否可以投射阴影 |
| [ControlPoints](../../aspose.threed.entities/geometry/controlpoints) { get; } | 获取所有控制点 |
| [Deformers](../../aspose.threed.entities/geometry/deformers) { get; } | 获取与此几何体关联的所有变形器。 |
| [Excluded](../../aspose.threed/entity/excluded) { get; set; } | 获取或设置是否在导出时排除该实体。 |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | 获取或设置名称。 |
| [ParentNode](../../aspose.threed/entity/parentnode) { get; set; } | 获取或设置第一个父节点，如果设置了第一个父节点，该实体将与其他父节点分离。 |
| [ParentNodes](../../aspose.threed/entity/parentnodes) { get; } | 获取所有父节点，一个实体可以附加到多个父节点进行几何实例化 |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | 获取所有属性的集合。 |
| [ReceiveShadows](../../aspose.threed.entities/geometry/receiveshadows) { get; set; } | 获取或设置此几何体是否可以接收阴影。 |
| [Scene](../../aspose.threed/sceneobject/scene) { get; } | 获取该对象所属的场景 |
| [VertexElements](../../aspose.threed.entities/geometry/vertexelements) { get; } | 获取所有顶点元素 |
| [Visible](../../aspose.threed.entities/geometry/visible) { get; set; } | 获取或设置几何是否可见 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [FromGeometry](../../aspose.threed.entities/pointcloud/fromgeometry#fromgeometry)(Geometry) | 从几何对象创建新的 PointCloud 实例 |
| static [FromGeometry](../../aspose.threed.entities/pointcloud/fromgeometry#fromgeometry_1)(Geometry, int) | 从几何对象创建一个新的点云实例。 密度是每单位三角形的点数（单位三角形是网格中表面积最大的三角形） |
| [AddElement](../../aspose.threed.entities/geometry/addelement)(VertexElement) | 将现有顶点元素添加到当前几何体 |
| [CreateElement](../../aspose.threed.entities/geometry/createelement)(VertexElementType) | 创建具有指定类型的顶点元素并将其添加到几何图形中。 |
| [CreateElement](../../aspose.threed.entities/geometry/createelement)(VertexElementType, MappingMode, ReferenceMode) | 创建具有指定类型的顶点元素并将其添加到几何图形中。 |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv)(TextureMapping) | 创建具有给定纹理映射类型的[`VertexElementUV`](../vertexelementuv)。 |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv)(TextureMapping, MappingMode, ReferenceMode) | 创建具有给定纹理映射类型的[`VertexElementUV`](../vertexelementuv)。 |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | 查找属性。 可以是动态属性（由 CreateDynamicProperty/SetProperty 创建） 或本机属性（由其名称标识） |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox)() | 获取当前实体在其对象空间坐标系中的边界框。 |
| [GetDeformers&lt;T&gt;](../../aspose.threed.entities/geometry/getdeformers)() |  |
| [GetElement](../../aspose.threed.entities/geometry/getelement)(VertexElementType) | 获取指定类型的顶点元素 |
| override [GetEntityRendererKey](../../aspose.threed.entities/pointcloud/getentityrendererkey)() | 获取在渲染器中注册的实体渲染器的key |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | 获取指定属性的值 |
| [GetVertexElementOfUV](../../aspose.threed.entities/geometry/getvertexelementofuv)(TextureMapping) | 得到一个 [`VertexElementUV`](../vertexelementuv) 具有给定纹理映射类型的实例 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | 删除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | 删除名称标识的指定属性 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | 设置指定属性的值 |

### 也可以看看

* class [Geometry](../geometry)
* 命名空间 [Aspose.ThreeD.Entities](../../aspose.threed.entities)
* 部件 [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->