---
title: "类 PointCloud"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Entities.PointCloud 类。点云不包含拓扑信息，仅包含控制点和顶点元素。"
type: docs
weight: 600
url: /zh/net/aspose.threed.entities/pointcloud/
---
## PointCloud class

点云不包含拓扑信息，仅包含控制点和顶点元素。

```csharp
public class PointCloud : Geometry
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PointCloud](pointcloud/#constructor)() | `PointCloud` 的构造函数 |
| [PointCloud](pointcloud/#constructor_1)(string) | `PointCloud` 的构造函数 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/geometry/castshadows/) { get; set; } | 获取或设置此几何体是否可以投射阴影 |
| [ControlPoints](../../aspose.threed.entities/geometry/controlpoints/) { get; } | 获取所有控制点 |
| [Deformers](../../aspose.threed.entities/geometry/deformers/) { get; } | 获取与此几何体关联的所有变形器。 |
| [Dimension](../../aspose.threed.entities/pointcloud/dimension/) { get; set; } | 如果点云存在维度值，则表示它是有组织的点云。未指定大小时，视为无组织的点云。有组织的点云意味着它具有类似图像的结构。 |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | 获取或设置在导出时是否排除此实体。 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | 获取或设置第一个父节点，如果设置了第一个父节点，则此实体将从其他父节点分离。 |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | 获取所有父节点，实体可以附加到多个父节点以实现几何实例化 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |
| [ReceiveShadows](../../aspose.threed.entities/geometry/receiveshadows/) { get; set; } | 获取或设置此几何体是否可以接收阴影。 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | 获取此对象所属的场景 |
| [VertexElements](../../aspose.threed.entities/geometry/vertexelements/) { get; } | 获取所有顶点元素 |
| [Visible](../../aspose.threed.entities/geometry/visible/) { get; set; } | 获取或设置几何体是否可见 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [FromGeometry](../../aspose.threed.entities/pointcloud/fromgeometry/#fromgeometry)(Geometry) | 从几何对象创建一个新的 PointCloud 实例 |
| static [FromGeometry](../../aspose.threed.entities/pointcloud/fromgeometry/#fromgeometry_1)(Geometry, int) | 从几何对象创建一个新的点云实例。密度是每单位三角形的点数（单位三角形是网格中表面积最大的三角形）。 |
| [AddElement](../../aspose.threed.entities/geometry/addelement/)(VertexElement) | 向当前几何体添加已有的顶点元素 |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/)(VertexElementType) | 创建具有指定类型的顶点元素并将其添加到几何体中。 |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/)(VertexElementType, MappingMode, ReferenceMode) | 创建具有指定类型的顶点元素并将其添加到几何体中。 |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/)(TextureMapping) | 创建一个具有给定纹理映射类型的[`VertexElementUV`](../vertexelementuv/)。 |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/)(TextureMapping, MappingMode, ReferenceMode) | 创建一个具有给定纹理映射类型的[`VertexElementUV`](../vertexelementuv/)。 |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本地属性（通过其名称识别） |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | 获取当前实体在其对象空间坐标系中的包围盒。 |
| [GetDeformers&lt;T&gt;](../../aspose.threed.entities/geometry/getdeformers/)() |  |
| [GetElement](../../aspose.threed.entities/geometry/getelement/)(VertexElementType) | 获取具有指定类型的顶点元素 |
| override [GetEntityRendererKey](../../aspose.threed.entities/pointcloud/getentityrendererkey/)() | 获取在渲染器中注册的实体渲染器的键 |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 获取指定属性的值 |
| [GetVertexElementOfUV](../../aspose.threed.entities/geometry/getvertexelementofuv/)(TextureMapping) | 获取具有给定纹理映射类型的[`VertexElementUV`](../vertexelementuv/)实例 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 移除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 移除通过名称识别的指定属性 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 设置指定属性的值 |

### 另请参见

* class [Geometry](../geometry/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


