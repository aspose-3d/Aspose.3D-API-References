---
title: "类 VertexElementMaterial"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Entities.VertexElementMaterial 类。为指定组件定义材质索引。一个节点可以拥有多个材质，VertexElementMaterial 用于在不同材质中渲染几何体的不同部分"
type: docs
weight: 880
url: /zh/net/aspose.threed.entities/vertexelementmaterial/
---
## VertexElementMaterial class

为指定组件定义材质索引。一个节点可以拥有多个材质，`VertexElementMaterial` 用于在不同材质中渲染几何体的不同部分。

```csharp
public class VertexElementMaterial : VertexElement
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [VertexElementMaterial](vertexelementmaterial/)() | 初始化 `VertexElementMaterial` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Indices](../../aspose.threed.entities/vertexelement/indices/) { get; } | 获取索引数据 |
| [MappingMode](../../aspose.threed.entities/vertexelement/mappingmode/) { get; set; } | 获取或设置元素的映射方式。 |
| [Name](../../aspose.threed.entities/vertexelement/name/) { get; set; } | 获取或设置名称。 |
| [ReferenceMode](../../aspose.threed.entities/vertexelement/referencemode/) { get; set; } | 获取或设置元素的引用方式。 |
| [VertexElementType](../../aspose.threed.entities/vertexelement/vertexelementtype/) { get; } | 获取 [`VertexElement`](../vertexelement/) 的类型 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Clear](../../aspose.threed.entities/vertexelementmaterial/clear/)() | 从直接数组和索引数组中移除所有元素。 |
| [SetIndices](../../aspose.threed.entities/vertexelement/setindices/)(int[]) | 加载索引 |
| override [ToString](../../aspose.threed.entities/vertexelement/tostring/)() | 顶点元素的字符串表示形式。 |

## 示例

以下代码展示了如何为盒子的不同面分配不同的材质。

```csharp
// 创建一个盒子网格（盒子由 6 个平面组成）
Mesh box = (new Box()).ToMesh();
// 在此网格上创建材质元素
VertexElementMaterial mat = (VertexElementMaterial)box.CreateElement(VertexElementType.Material, MappingMode.Polygon, ReferenceMode.Index);
// 并为每个平面指定不同的材质索引
mat.Indices.AddRange(new int[] { 0, 1, 2, 3, 4, 5 });
```

### 另请参见

* class [VertexElement](../vertexelement/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


