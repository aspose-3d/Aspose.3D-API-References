---
title: "Mesh 类"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Entities.Mesh 类。网格由许多 n 边多边形组成"
type: docs
weight: 510
url: /zh/net/aspose.threed.entities/mesh/
---
## Mesh class

网格由许多 n 边多边形组成。

```csharp
public class Mesh : Geometry, IEnumerable<int[]>, IMeshConvertible
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Mesh](mesh/#constructor)() | 初始化 `Mesh` 类的新实例。 |
| [Mesh](mesh/#constructor_4)(string) | 初始化 `Mesh` 类的新实例。 |
| [Mesh](mesh/#constructor_1)(TextureData) | 使用指定的高度图构建网格，如果高度图的像素格式包含多个分量，则使用第一个（通常是红色）分量作为高度值 (z)。控制点的 x 和 y 分量为归一化像素坐标。 |
| [Mesh](mesh/#constructor_2)(TextureData, Matrix4) | 使用指定的高度图构建网格，如果高度图的像素格式包含多个分量，则使用第一个（通常是红色）分量作为高度值 (z)。控制点的 x 和 y 分量为归一化像素坐标。 |
| [Mesh](mesh/#constructor_3)(TextureData, bool, Matrix4) | 使用指定的高度图构建网格，如果高度图的像素格式包含多个分量，则使用第一个（通常是红色）分量作为高度值 (z)。控制点的 x 和 y 分量为归一化像素坐标。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/geometry/castshadows/) { get; set; } | 获取或设置此几何体是否可以投射阴影 |
| [ControlPoints](../../aspose.threed.entities/geometry/controlpoints/) { get; } | 获取所有控制点 |
| [Deformers](../../aspose.threed.entities/geometry/deformers/) { get; } | 获取与此几何体关联的所有变形器。 |
| [Edges](../../aspose.threed.entities/mesh/edges/) { get; } | 获取 Mesh 的边。网格中的 Edge 是可选的，因此可能为空。 |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | 获取或设置在导出时是否排除此实体。 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | 获取或设置第一个父节点，如果设置了第一个父节点，则此实体将从其他父节点分离。 |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | 获取所有父节点，实体可以附加到多个父节点以实现几何实例化 |
| [PolygonCount](../../aspose.threed.entities/mesh/polygoncount/) { get; } | 获取多边形的数量 |
| [Polygons](../../aspose.threed.entities/mesh/polygons/) { get; } | 获取网格的多边形定义 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |
| [ReceiveShadows](../../aspose.threed.entities/geometry/receiveshadows/) { get; set; } | 获取或设置此几何体是否可以接收阴影。 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | 获取此对象所属的场景 |
| [VertexElements](../../aspose.threed.entities/geometry/vertexelements/) { get; } | 获取所有顶点元素 |
| [Visible](../../aspose.threed.entities/geometry/visible/) { get; set; } | 获取或设置几何体是否可见 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [DoBoolean](../../aspose.threed.entities/mesh/doboolean/)(BooleanOperation, Mesh, Matrix4?, Mesh, Matrix4?) |  |
| [AddElement](../../aspose.threed.entities/geometry/addelement/)(VertexElement) | 向当前几何体添加已有的顶点元素 |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/)(VertexElementType) | 创建具有指定类型的顶点元素并将其添加到几何体中。 |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/)(VertexElementType, MappingMode, ReferenceMode) | 创建具有指定类型的顶点元素并将其添加到几何体中。 |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/)(TextureMapping) | 创建一个具有给定纹理映射类型的[`VertexElementUV`](../vertexelementuv/)。 |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/)(TextureMapping, MappingMode, ReferenceMode) | 创建一个具有给定纹理映射类型的[`VertexElementUV`](../vertexelementuv/)。 |
| [CreatePolygon](../../aspose.threed.entities/mesh/createpolygon/#createpolygon_2)(int[]) | 使用 *indices* 中定义的所有顶点创建一个新多边形。若要逐顶点创建多边形，请使用[`PolygonBuilder`](../polygonbuilder/)。 |
| [CreatePolygon](../../aspose.threed.entities/mesh/createpolygon/#createpolygon)(int, int, int) | 创建一个具有3个顶点的多边形（三角形） |
| [CreatePolygon](../../aspose.threed.entities/mesh/createpolygon/#createpolygon_3)(int[], int, int) | 使用 *indices* 中定义的所有顶点创建一个新多边形。若要逐顶点创建多边形，请使用[`PolygonBuilder`](../polygonbuilder/)。 |
| [CreatePolygon](../../aspose.threed.entities/mesh/createpolygon/#createpolygon_1)(int, int, int, int) | 创建一个具有4个顶点的多边形（四边形） |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本地属性（通过其名称识别） |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | 获取当前实体在其对象空间坐标系中的包围盒。 |
| [GetDeformers&lt;T&gt;](../../aspose.threed.entities/geometry/getdeformers/)() |  |
| [GetElement](../../aspose.threed.entities/geometry/getelement/)(VertexElementType) | 获取具有指定类型的顶点元素 |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | 获取在渲染器中注册的实体渲染器的键 |
| [GetEnumerator](../../aspose.threed.entities/mesh/getenumerator/)() | 获取每个内部多边形的枚举器。 |
| [GetPolygonSize](../../aspose.threed.entities/mesh/getpolygonsize/)(int) | 获取指定多边形的顶点数量。 |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 获取指定属性的值 |
| [GetVertexElementOfUV](../../aspose.threed.entities/geometry/getvertexelementofuv/)(TextureMapping) | 获取具有给定纹理映射类型的[`VertexElementUV`](../vertexelementuv/)实例 |
| [IsManifold](../../aspose.threed.entities/mesh/ismanifold/)() | 检查当前网格是否为流形网格。此函数不会缓存流形计算结果。 |
| [Optimize](../../aspose.threed.entities/mesh/optimize/#optimize)(bool) | 通过消除重复的控制点来优化网格的内存使用。 |
| [Optimize](../../aspose.threed.entities/mesh/optimize/#optimize_1)(bool, float, float, float) | 通过消除重复的控制点来优化网格的内存使用。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 移除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 移除通过名称识别的指定属性 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 设置指定属性的值 |
| [ToMesh](../../aspose.threed.entities/mesh/tomesh/)() | 从当前实体获取 Mesh 实例。 |
| [Triangulate](../../aspose.threed.entities/mesh/triangulate/)() | 返回三角化后的网格 |
| [operator &amp;](../../aspose.threed.entities/mesh/op_bitwiseand/) | 计算两个网格的交集 |
| [operator &#x7C;](../../aspose.threed.entities/mesh/op_bitwiseor/) | 计算两个网格的并集 |
| [operator -](../../aspose.threed.entities/mesh/op_subtraction/) | 计算两个网格的差集 |

## 示例

在网格中添加多边形：

```csharp
Mesh mesh = new Mesh();
int[] indices = new int[] {0, 1, 2};
mesh.CreatePolygon(indices);
```

遍历网格中的所有多边形：

```csharp
Mesh mesh = new Mesh();
foreach(int[] polygon in mesh)
{
    //处理多边形
}
```

### 另请参见

* class [Geometry](../geometry/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


