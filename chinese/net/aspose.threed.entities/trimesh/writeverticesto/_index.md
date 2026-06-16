---
title: "TriMesh.WriteVerticesTo"
second_title: "Aspose.3D for .NET API 参考"
description: "TriMesh 方法。将顶点数据写入指定的流"
type: docs
weight: 290
url: /zh/net/aspose.threed.entities/trimesh/writeverticesto/
---
## TriMesh.WriteVerticesTo method

将顶点数据写入指定的流

```csharp
public void WriteVerticesTo(Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 将写入顶点数据的流 |

## 示例

```csharp
//将 mesh 转换为 TriMesh，布局会自动从输入 mesh 推断
var triMesh = TriMesh.FromMesh(new Sphere().ToMesh());
//将其保存到流中，115 个顶点 * 每顶点 32 字节
var stream = new MemoryStream();
triMesh.WriteVerticesTo(stream);
//将索引以 ushort 保存到流中，504 个索引 * 每索引 2 字节
triMesh.Write16bIndicesTo(stream);
```

### 另请参见

* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)


