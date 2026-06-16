---
title: "TriMesh.CopyFrom"
second_title: "Aspose.3D for .NET API 参考"
description: "TriMesh 方法。使用新顶点布局从输入复制 TriMesh"
type: docs
weight: 20
url: /zh/net/aspose.threed.entities/trimesh/copyfrom/
---
## TriMesh.CopyFrom method

从输入复制 [`TriMesh`](../) 使用新顶点布局

```csharp
public static TriMesh CopyFrom(TriMesh input, VertexDeclaration vd)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 输入 | TriMesh | 用于复制的输入 TriMesh |
| vd | VertexDeclaration | 输出 TriMesh 的新顶点声明 |

### 返回值

具有新顶点声明的新的 TriMesh 实例。

## 示例

```csharp
//将顶点声明定义为 {FVector3 Position; FVector3 Normal; FVector2 UV}
VertexDeclaration vd = new VertexDeclaration();
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Normal);
vd.AddField(VertexFieldDataType.FVector2, VertexFieldSemantic.UV);
//将 mesh 转换为 TriMesh，布局会自动从输入 mesh 推断
var oldTriMesh = TriMesh.FromMesh((new Sphere()).ToMesh());
//现在使用 vd 定义的显式内存布局，从旧 TriMesh 创建新的 TriMesh
var newTriMesh = TriMesh.CopyFrom(oldTriMesh, vd);
```

### 另请参见

* class [VertexDeclaration](../../../aspose.threed.utilities/vertexdeclaration/)
* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)


