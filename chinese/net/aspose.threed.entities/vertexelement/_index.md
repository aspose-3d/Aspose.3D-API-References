---
title: "类 VertexElement"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Entities.VertexElement 类。顶点元素的基类。顶点元素类型由 VertexElementType 标识。VertexElement 描述顶点元素如何映射到几何表面以及映射信息在内存中的布局。VertexElement 包含法线、UV 或其他类型的信息。"
type: docs
weight: 820
url: /zh/net/aspose.threed.entities/vertexelement/
---
## VertexElement class

顶点元素的基类。顶点元素类型由 VertexElementType 标识。VertexElement 描述顶点元素如何映射到几何表面以及映射信息在内存中的布局。VertexElement 包含法线、UV 或其他类型的信息。

```csharp
public abstract class VertexElement : IIndexedVertexElement
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Indices](../../aspose.threed.entities/vertexelement/indices/) { get; } | 获取索引数据 |
| [MappingMode](../../aspose.threed.entities/vertexelement/mappingmode/) { get; set; } | 获取或设置元素的映射方式。 |
| [Name](../../aspose.threed.entities/vertexelement/name/) { get; set; } | 获取或设置名称。 |
| [ReferenceMode](../../aspose.threed.entities/vertexelement/referencemode/) { get; set; } | 获取或设置元素的引用方式。 |
| [VertexElementType](../../aspose.threed.entities/vertexelement/vertexelementtype/) { get; } | 获取 `VertexElement` 的类型 |

## 方法

| 名称 | 描述 |
| --- | --- |
| abstract [Clear](../../aspose.threed.entities/vertexelement/clear/)() | 清除此顶点元素的所有数据。 |
| [SetIndices](../../aspose.threed.entities/vertexelement/setindices/)(int[]) | 加载索引 |
| override [ToString](../../aspose.threed.entities/vertexelement/tostring/)() | 顶点元素的字符串表示形式。 |

### 另请参见

* interface [IIndexedVertexElement](../iindexedvertexelement/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


