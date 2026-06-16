---
title: "TriMesh.LoadVerticesFromBytes"
second_title: "Aspose.3D for .NET API 参考"
description: "TriMesh 方法。从字节加载顶点，字节长度必须是顶点大小的整数倍"
type: docs
weight: 160
url: /zh/net/aspose.threed.entities/trimesh/loadverticesfrombytes/
---
## TriMesh.LoadVerticesFromBytes method

从字节加载顶点，字节长度必须是顶点大小的整数倍。

```csharp
public void LoadVerticesFromBytes(byte[] verticesInBytes)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| verticesInBytes | Byte[] |  |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException |  |
| ArgumentException |  |

## 示例

以下代码展示了如何创建一个空的 TriMesh 并手动从原始字节加载顶点。

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
//使用指定的顶点声明创建一个空的 TriMesh
var triMesh = new TriMesh("", vd);
//直接从字节加载顶点
triMesh.LoadVerticesFromBytes(vertices);
triMesh.AddTriangle(0, 1, 2);
```

```csharp
int[] indices = new int[] { 0,  1,  2 };
byte[] vertices = new byte[]{
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
vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
//使用指定的顶点声明创建一个空的 TriMesh
var triMesh = new TriMesh("", vd);
//直接从字节加载顶点
triMesh.loadVerticesFromBytes(vertices);
triMesh.addTriangle(0, 1, 2);
```

### 另请参见

* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)


