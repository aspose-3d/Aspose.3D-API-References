---
title: "TriMesh 类"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Entities.TriMesh 类。TriMesh 包含可直接由 GPU 使用的原始数据。此类是一个实用工具，用于帮助构建仅包含每顶点数据的网格。"
type: docs
weight: 790
url: /zh/net/aspose.threed.entities/trimesh/
---
## TriMesh class

TriMesh 包含可直接被 GPU 使用的原始数据。此类是一个实用工具，用于帮助构建仅包含每顶点数据的网格。

```csharp
public class TriMesh : Entity, IEnumerable<Vertex>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TriMesh](trimesh/)(string, VertexDeclaration) | 初始化 `TriMesh` 实例 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Capacity](../../aspose.threed.entities/trimesh/capacity/) { get; } | 预分配顶点的容量。 |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | 获取或设置在导出时是否排除此实体。 |
| [IndicesCount](../../aspose.threed.entities/trimesh/indicescount/) { get; } | 此 `TriMesh` 中索引的数量 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | 获取或设置第一个父节点，如果设置了第一个父节点，则此实体将从其他父节点分离。 |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | 获取所有父节点，实体可以附加到多个父节点以实现几何实例化 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | 获取此对象所属的场景 |
| [UnmergedVerticesCount](../../aspose.threed.entities/trimesh/unmergedverticescount/) { get; } | 通过 [`BeginVertex`](./beginvertex/) 和 [`EndVertex`](./endvertex/) 传入的未合并顶点的数量。 |
| [VertexDeclaration](../../aspose.threed.entities/trimesh/vertexdeclaration/) { get; } | `TriMesh` 的顶点布局。 |
| [VerticesCount](../../aspose.threed.entities/trimesh/verticescount/) { get; } | 此 `TriMesh` 中顶点的数量 |
| [VerticesSizeInBytes](../../aspose.threed.entities/trimesh/verticessizeinbytes/) { get; } | 所有顶点的总大小（字节） |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [CopyFrom](../../aspose.threed.entities/trimesh/copyfrom/)(TriMesh, VertexDeclaration) | 使用新的顶点布局从输入复制 `TriMesh` |
| static [FromMesh](../../aspose.threed.entities/trimesh/frommesh/#frommesh)(Mesh, bool) | 根据给定的网格对象创建 TriMesh，顶点声明基于输入网格的结构。 |
| static [FromMesh](../../aspose.threed.entities/trimesh/frommesh/#frommesh_1)(VertexDeclaration, Mesh) | 使用给定的顶点布局从指定的网格对象创建 TriMesh。 |
| static [FromRawData](../../aspose.threed.entities/trimesh/fromrawdata/)(VertexDeclaration, byte[], int[], bool) | 从原始数据创建 TriMesh |
| [AddTriangle](../../aspose.threed.entities/trimesh/addtriangle/)(int, int, int) | 添加一个新三角形 |
| [BeginVertex](../../aspose.threed.entities/trimesh/beginvertex/)() | 开始添加顶点 |
| [EndVertex](../../aspose.threed.entities/trimesh/endvertex/)() | 结束添加顶点 |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本地属性（通过其名称识别） |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | 获取当前实体在其对象空间坐标系中的包围盒。 |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | 获取在渲染器中注册的实体渲染器的键 |
| [GetEnumerator](../../aspose.threed.entities/trimesh/getenumerator/)() | 获取枚举器以枚举 [`Vertex`](../../aspose.threed.utilities/vertex/) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 获取指定属性的值 |
| [IndicesToArray](../../aspose.threed.entities/trimesh/indicestoarray/#indicestoarray)(out int[]) |  |
| [IndicesToArray](../../aspose.threed.entities/trimesh/indicestoarray/#indicestoarray_1)(out ushort[]) |  |
| [LoadVerticesFromBytes](../../aspose.threed.entities/trimesh/loadverticesfrombytes/)(byte[]) | 从字节加载顶点，字节长度必须是顶点大小的整数倍。 |
| [ReadDouble](../../aspose.threed.entities/trimesh/readdouble/)(int, VertexField) | 读取 double 字段 |
| [ReadFloat](../../aspose.threed.entities/trimesh/readfloat/)(int, VertexField) | 读取 float 字段 |
| [ReadFVector2](../../aspose.threed.entities/trimesh/readfvector2/)(int, VertexField) | 读取 vector2 字段 |
| [ReadFVector3](../../aspose.threed.entities/trimesh/readfvector3/)(int, VertexField) | 读取 vector3 字段 |
| [ReadFVector4](../../aspose.threed.entities/trimesh/readfvector4/)(int, VertexField) | 读取 vector4 字段 |
| [ReadVector2](../../aspose.threed.entities/trimesh/readvector2/)(int, VertexField) | 读取 vector2 字段 |
| [ReadVector3](../../aspose.threed.entities/trimesh/readvector3/)(int, VertexField) | 读取 vector3 字段 |
| [ReadVector4](../../aspose.threed.entities/trimesh/readvector4/)(int, VertexField) | 读取 vector4 字段 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 移除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 移除通过名称识别的指定属性 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 设置指定属性的值 |
| override [ToString](../../aspose.threed.entities/trimesh/tostring/)() | 获取 `TriMesh` 的字符串表示 |
| [VerticesToArray](../../aspose.threed.entities/trimesh/verticestoarray/)() | 将顶点数据转换为字节数组 |
| [Write16bIndicesTo](../../aspose.threed.entities/trimesh/write16bindicesto/)(Stream) | 将索引数据以 16 位整数写入流 |
| [Write32bIndicesTo](../../aspose.threed.entities/trimesh/write32bindicesto/)(Stream) | 将索引数据以 32 位整数写入流 |
| [WriteVerticesTo](../../aspose.threed.entities/trimesh/writeverticesto/)(Stream) | 将顶点数据写入指定的流 |

## 示例

以下代码展示了如何使用自定义内存布局创建 TriMesh 并将其导出到文件。

```csharp
//将顶点声明定义为 {FVector3 Position; FVector3 Normal; FVector2 UV}
VertexDeclaration vd = new VertexDeclaration();
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Normal);
vd.AddField(VertexFieldDataType.FVector2, VertexFieldSemantic.UV);
//使用指定的内存布局将网格转换为 tri-mesh
var mesh = (new Sphere()).ToMesh();
var triMesh = TriMesh.FromMesh(vd, mesh);
//将其保存到流中，115 个顶点 * 每顶点 32 字节
using (var stream = new FileStream("output.bin", FileMode.Create))
{
    triMesh.WriteVerticesTo(stream);
    //将索引以 ushort 保存到流中，504 个索引 * 每索引 2 字节
    triMesh.Write16bIndicesTo(stream);
}
```

### 另请参见

* class [Entity](../../aspose.threed/entity/)
* class [Vertex](../../aspose.threed.utilities/vertex/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


