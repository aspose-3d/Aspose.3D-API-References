---
title: "TriMesh.FromMesh"
second_title: "Aspose.3D for .NET API 参考"
description: "TriMesh 方法。使用给定的顶点布局从指定的 mesh 对象创建 TriMesh"
type: docs
weight: 30
url: /zh/net/aspose.threed.entities/trimesh/frommesh/
---
## FromMesh(VertexDeclaration, Mesh) {#frommesh_1}

使用给定的顶点布局从指定的网格对象创建 TriMesh。

```csharp
public static TriMesh FromMesh(VertexDeclaration declaration, Mesh mesh)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 声明 | VertexDeclaration | Vertex 的类型定义或内存布局 |
| 网格 | 网格 | 源网格 |

### 返回值

TriMesh 实例，由输入网格转换而来，使用指定的顶点内存布局

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

* class [VertexDeclaration](../../../aspose.threed.utilities/vertexdeclaration/)
* class [Mesh](../../mesh/)
* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)

---

## FromMesh(Mesh, bool) {#frommesh}

根据给定的网格对象创建 TriMesh，顶点声明基于输入网格的结构。

```csharp
public static TriMesh FromMesh(Mesh mesh, bool useFloat = true)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 网格 | 网格 |  |
| useFloat | Boolean | 对每个顶点元素组件使用 float 类型而不是 double 类型。 |

### 返回值

由给定的 [`Mesh`](../../mesh/) 生成的 [`TriMesh`](../)

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

* class [Mesh](../../mesh/)
* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)


