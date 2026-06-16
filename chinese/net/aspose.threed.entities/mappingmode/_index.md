---
title: "枚举 MappingMode"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Entities.MappingMode 枚举。确定元素如何映射到表面。MappingMode 定义了 VertexElement 如何映射到几何体的表面。"
type: docs
weight: 500
url: /zh/net/aspose.threed.entities/mappingmode/
---
## MappingMode enumeration

确定元素如何映射到表面。`MappingMode` 定义了 [`VertexElement`](../vertexelement/) 如何映射到几何体的表面。

```csharp
public enum MappingMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| ControlPoint | `0` | 每个数据映射到几何体的控制点。 |
| PolygonVertex | `1` | 数据映射到多边形的顶点。当一个控制点被多个多边形共享，并且数据被映射为 PolygonVertex 时，作为不同多边形顶点的控制点将拥有各自的数据。 |
| Polygon | `2` | 数据映射到多边形。当映射模式为 Polygon 时，每个多边形顶点共享相同的数据。 |
| Edge | `3` | 数据映射到边。当映射为 Edge 时，每个边的端点共享相同的数据。 |
| AllSame | `4` | 一个数据映射到整个表面。无论数据被解释为控制点、 多边形顶点或边端点，数据始终与 AllSame 定义的相同。 |

### 另请参见

* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


