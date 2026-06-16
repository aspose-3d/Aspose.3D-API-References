---
title: "类 PolygonModifier"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Entities.PolygonModifier 类。用于修改多边形的实用工具。"
type: docs
weight: 620
url: /zh/net/aspose.threed.entities/polygonmodifier/
---
## PolygonModifier class

用于修改多边形的实用工具

```csharp
public class PolygonModifier
```

## 方法

| 名称 | 描述 |
| --- | --- |
| static [ApplyTransform](../../aspose.threed.entities/polygonmodifier/applytransform/)(Node, Matrix4) | 对所有几何体的控制点应用变换矩阵 |
| static [BuildTangentBinormal](../../aspose.threed.entities/polygonmodifier/buildtangentbinormal/#buildtangentbinormal)(Mesh) | 这将在 mesh 上创建切线和副法线。需要 Normal，如果 mesh 上不存在 Normal，它还会根据位置创建 Normal 数据。UV 也必须存在，如果未找到 UV，将抛出异常。 |
| static [BuildTangentBinormal](../../aspose.threed.entities/polygonmodifier/buildtangentbinormal/#buildtangentbinormal_1)(Scene) | 这将在场景的所有 mesh 上创建切线和副法线。需要 Normal，如果某个 mesh 上不存在 Normal，它还会根据位置创建 Normal 数据。UV 也必须存在，如果未定义 UV，则该 mesh 将被忽略。 |
| static [GenerateNormal](../../aspose.threed.entities/polygonmodifier/generatenormal/)(Mesh) | 从 Mesh 定义生成 Normal 数据 |
| static [GenerateUV](../../aspose.threed.entities/polygonmodifier/generateuv/#generateuv)(Mesh) | 从给定的输入 mesh 生成 UV 数据 |
| static [GenerateUV](../../aspose.threed.entities/polygonmodifier/generateuv/#generateuv_1)(Mesh, VertexElementNormal) | 从给定的输入 mesh 和指定的 Normal 数据生成 UV 数据。 |
| static [MergeMesh](../../aspose.threed.entities/polygonmodifier/mergemesh/#mergemesh_2)(IList&lt;Node&gt;) |  |
| static [MergeMesh](../../aspose.threed.entities/polygonmodifier/mergemesh/#mergemesh)(Node) | 将整个节点转换为单个已变换的 mesh。尚不支持顶点元素，如法线/纹理坐标。 |
| static [MergeMesh](../../aspose.threed.entities/polygonmodifier/mergemesh/#mergemesh_1)(Scene) | 将整个场景转换为单个已变换的 mesh。尚不支持顶点元素，如法线/纹理坐标。 |
| static [Scale](../../aspose.threed.entities/polygonmodifier/scale/#scale_1)(Node, Vector3) | 在此节点中缩放所有几何体（缩放控制点而非变换矩阵） |
| static [Scale](../../aspose.threed.entities/polygonmodifier/scale/#scale)(Scene, Vector3) | 在此场景中缩放所有几何体（缩放控制点而不是变换矩阵） |
| static [SplitMesh](../../aspose.threed.entities/polygonmodifier/splitmesh/#splitmesh)(Mesh, SplitMeshPolicy) | 通过[`VertexElementMaterial`](../vertexelementmaterial/)将网格拆分为子网格。每个子网格只使用一种材质。原始网格不会被更改。 |
| static [SplitMesh](../../aspose.threed.entities/polygonmodifier/splitmesh/#splitmesh_2)(Scene, SplitMeshPolicy, bool) | 通过[`VertexElementMaterial`](../vertexelementmaterial/)将网格拆分为子网格。每个子网格只使用一种材质。对场景的所有节点执行网格拆分。 |
| static [SplitMesh](../../aspose.threed.entities/polygonmodifier/splitmesh/#splitmesh_1)(Node, SplitMeshPolicy, bool, bool) | 通过[`VertexElementMaterial`](../vertexelementmaterial/)将网格拆分为子网格。每个子网格只使用一种材质。在单个节点上执行网格拆分。 |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_1)(IList&lt;Vector4&gt;) |  |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate)(Mesh) | 将基于多边形的网格转换为完整的三角形网格 |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_5)(Scene) | 将所有基于多边形的网格转换为完整的三角形网格 |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_3)(IList&lt;Vector4&gt;, IList&lt;int[]&gt;) |  |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_2)(IList&lt;Vector4&gt;, int[]) |  |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_4)(IList&lt;Vector4&gt;, IList&lt;int[]&gt;, bool, out Vector3[]) |  |

### 另请参见

* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


