---
title: "类 Geometry"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Entities.Geometry 类。所有可渲染几何对象的基类，例如 Mesh、NurbsSurface、Patch 等。"
type: docs
weight: 410
url: /zh/net/aspose.threed.entities/geometry/
---
## Geometry class

所有可渲染几何对象的基类（如 [`Mesh`](../mesh/)、[`NurbsSurface`](../nurbssurface/)、[`Patch`](../patch/) 等）。

`Geometry` 基类支持：**Control point management**，控制点定义几何体的基础 3D 空间结构，不同的几何类型有不同的方式来定义具体的 3D 模型。**Vertex element definition**，顶点元素为几何体添加额外信息，如法线/UV 坐标/顶点颜色，详见 [`VertexElement`](../vertexelement/)。**Object deforming**，[`Deformer`](../../aspose.threed.deformers/deformer/) 可以绑定以动画化几何体的形状。

```csharp
public class Geometry : Entity
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Geometry](geometry/)(string) | 初始化 `Geometry` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/geometry/castshadows/) { get; set; } | 获取或设置此几何体是否可以投射阴影 |
| [ControlPoints](../../aspose.threed.entities/geometry/controlpoints/) { get; } | 获取所有控制点 |
| [Deformers](../../aspose.threed.entities/geometry/deformers/) { get; } | 获取与此几何体关联的所有变形器。 |
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
| [AddElement](../../aspose.threed.entities/geometry/addelement/)(VertexElement) | 向当前几何体添加已有的顶点元素 |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/#createelement)(VertexElementType) | 创建具有指定类型的顶点元素并将其添加到几何体中。 |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/#createelement_1)(VertexElementType, MappingMode, ReferenceMode) | 创建具有指定类型的顶点元素并将其添加到几何体中。 |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/#createelementuv)(TextureMapping) | 创建一个具有给定纹理映射类型的[`VertexElementUV`](../vertexelementuv/)。 |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/#createelementuv_1)(TextureMapping, MappingMode, ReferenceMode) | 创建一个具有给定纹理映射类型的[`VertexElementUV`](../vertexelementuv/)。 |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本地属性（通过其名称识别） |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | 获取当前实体在其对象空间坐标系中的包围盒。 |
| [GetDeformers&lt;T&gt;](../../aspose.threed.entities/geometry/getdeformers/)() |  |
| [GetElement](../../aspose.threed.entities/geometry/getelement/)(VertexElementType) | 获取具有指定类型的顶点元素 |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | 获取在渲染器中注册的实体渲染器的键 |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 获取指定属性的值 |
| [GetVertexElementOfUV](../../aspose.threed.entities/geometry/getvertexelementofuv/)(TextureMapping) | 获取具有给定纹理映射类型的[`VertexElementUV`](../vertexelementuv/)实例 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 移除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 移除通过名称识别的指定属性 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 设置指定属性的值 |

### 另请参见

* class [Entity](../../aspose.threed/entity/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


