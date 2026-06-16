---
title: "类 VertexElementUV"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Entities.VertexElementUV 类。 定义指定组件的 UV 坐标。 一个几何体可以拥有多个 VertexElementUV 元素，并且每个元素都有不同的 TextureMappings。"
type: docs
weight: 960
url: /zh/net/aspose.threed.entities/vertexelementuv/
---
## VertexElementUV class

定义指定组件的 UV 坐标。 一个几何体可以拥有多个 `VertexElementUV` 元素，并且每个元素都有不同的 [`TextureMapping`](../texturemapping/)。

```csharp
public class VertexElementUV : VertexElementVector4
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [VertexElementUV](vertexelementuv/#constructor)() | 初始化 `VertexElementUV` 类的新实例。 默认的纹理映射类型是 Diffuse |
| [VertexElementUV](vertexelementuv/#constructor_1)(TextureMapping) | 初始化 `VertexElementUV` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Data](../../aspose.threed.entities/vertexelementvector4/data/) { get; } | 获取顶点数据 |
| [Indices](../../aspose.threed.entities/vertexelement/indices/) { get; } | 获取索引数据 |
| [MappingMode](../../aspose.threed.entities/vertexelement/mappingmode/) { get; set; } | 获取或设置元素的映射方式。 |
| [Name](../../aspose.threed.entities/vertexelement/name/) { get; set; } | 获取或设置名称。 |
| [ReferenceMode](../../aspose.threed.entities/vertexelement/referencemode/) { get; set; } | 获取或设置元素的引用方式。 |
| [VertexElementType](../../aspose.threed.entities/vertexelement/vertexelementtype/) { get; } | 获取 [`VertexElement`](../vertexelement/) 的类型 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddData](../../aspose.threed.entities/vertexelementuv/adddata/#adddata)(IEnumerable&lt;Vector2&gt;) |  |
| [AddData](../../aspose.threed.entities/vertexelementuv/adddata/#adddata_1)(IEnumerable&lt;Vector3&gt;) |  |
| override [Clear](../../aspose.threed.entities/vertexelementvector4/clear/)() | 从直接数组和索引数组中移除所有元素。 |
| [CopyTo](../../aspose.threed.entities/vertexelementvector4/copyto/)(VertexElementVector4) | 将数据复制到指定元素 |
| [SetData](../../aspose.threed.entities/vertexelementvector4/setdata/)(Vector4[]) | 加载数据 |
| [SetIndices](../../aspose.threed.entities/vertexelement/setindices/)(int[]) | 加载索引 |
| override [ToString](../../aspose.threed.entities/vertexelement/tostring/)() | 顶点元素的字符串表示形式。 |

### 另请参见

* class [VertexElementVector4](../vertexelementvector4/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


