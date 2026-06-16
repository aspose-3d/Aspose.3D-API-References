---
title: "类 VertexDeclaration"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Utilities.VertexDeclaration 类。自定义顶点结构的声明"
type: docs
weight: 2910
url: /zh/net/aspose.threed.utilities/vertexdeclaration/
---
## VertexDeclaration class

自定义顶点结构的声明

```csharp
public sealed class VertexDeclaration : IComparable<VertexDeclaration>, IEnumerable<VertexField>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [VertexDeclaration](vertexdeclaration/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Count](../../aspose.threed.utilities/vertexdeclaration/count/) { get; } | 获取此 `VertexDeclaration` 中定义的所有字段的计数 |
| [Item](../../aspose.threed.utilities/vertexdeclaration/item/) { get; } |  |
| [Sealed](../../aspose.threed.utilities/vertexdeclaration/sealed/) { get; } | 当 `VertexDeclaration` 被 [`TriMesh`](../../aspose.threed.entities/trimesh-1/) 或 [`TriMesh`](../../aspose.threed.entities/trimesh/) 使用后将被封闭，不再允许修改。 |
| [Size](../../aspose.threed.utilities/vertexdeclaration/size/) { get; } | 顶点结构的字节大小。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [FromGeometry](../../aspose.threed.utilities/vertexdeclaration/fromgeometry/)(Geometry, bool) | 基于 [`Geometry`](../../aspose.threed.entities/geometry/) 的布局创建 `VertexDeclaration`。 |
| static [FromType&lt;T&gt;](../../aspose.threed.utilities/vertexdeclaration/fromtype/)() |  |
| [AddField](../../aspose.threed.utilities/vertexdeclaration/addfield/)(VertexFieldDataType, VertexFieldSemantic, int, string) | 添加新的顶点字段 |
| [Clear](../../aspose.threed.utilities/vertexdeclaration/clear/)() | 清除所有字段。 |
| [CompareTo](../../aspose.threed.utilities/vertexdeclaration/compareto/)(VertexDeclaration) | 将此实例与指定对象进行比较，并返回它们相对值的指示。 |
| override [Equals](../../aspose.threed.utilities/vertexdeclaration/equals/)(object) | 确定此实例和指定对象（该对象也必须是 `VertexDeclaration` 对象）是否具有相同的值。 |
| [GetEnumerator](../../aspose.threed.utilities/vertexdeclaration/getenumerator/)() | 获取枚举器以遍历此实例中的所有顶点字段。 |
| override [GetHashCode](../../aspose.threed.utilities/vertexdeclaration/gethashcode/)() | 返回此字符串的哈希码。 |
| override [ToString](../../aspose.threed.utilities/vertexdeclaration/tostring/)() | `VertexDeclaration` 的字符串表示 |

### 另请参见

* class [VertexField](../vertexfield/)
* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


