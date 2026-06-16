---
title: "TriMesh.FromRawData"
second_title: "Aspose.3D for .NET API 参考"
description: "TriMesh 方法。从原始数据创建 TriMesh"
type: docs
weight: 40
url: /zh/net/aspose.threed.entities/trimesh/fromrawdata/
---
## TriMesh.FromRawData method

从原始数据创建 TriMesh

```csharp
public static TriMesh FromRawData(VertexDeclaration vd, byte[] vertices, int[] indices, 
    bool generateVertexMapping)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vd | VertexDeclaration | 顶点声明，必须至少包含一个字段。 |
| vertices | Byte[] | 输入的顶点数据，顶点的最小长度必须大于或等于顶点声明的大小。 |
| indices | Int32[] | 三角形索引 |
| generateVertexMapping | Boolean | 为每个顶点生成 [`Vertex`](../../../aspose.threed.utilities/vertex/)，仅用于序列化/反序列化时并非必需。 |

### 返回值

封装输入字节数组的 [`TriMesh`](../) 实例。

## 备注

返回的 TriMesh 为了性能不会复制输入字节数组，对数组的外部更改将反映到此实例中。

## 示例

以下代码展示了如何从原始字节构建 TriMesh，这在构建自定义 3D 格式时非常有用。

```csharp
var indices = new int[] { 0,  1,  2 };
var vertices = new byte[]{
    0, 0, 0, 191,
    0, 0, 0, 0,
    0, 0, 0, 191,
    0, 0, 0, 191,
    0, 0, 0, 0,
    0, 0, 0, 63,
    0, 0, 0, 63,
    0, 0, 0, 0,
    0, 0, 0, 63
};
VertexDeclaration vd = new VertexDeclaration();
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
var triMesh = TriMesh.FromRawData(vd, vertices, indices, true);
```

### 另请参见

* class [VertexDeclaration](../../../aspose.threed.utilities/vertexdeclaration/)
* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)


