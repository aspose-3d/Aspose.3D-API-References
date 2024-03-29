---
title: MappingMode
second_title: Aspose.3D for .NET API 参考
description: 确定元素如何映射到表面 的MappingMode./mappingmode定义如何VertexElement./vertexelement映射到几何体的表面
type: docs
weight: 440
url: /zh/net/aspose.threed.entities/mappingmode/
---
## MappingMode enumeration

确定元素如何映射到表面。 的[`MappingMode`](../mappingmode)定义如何[`VertexElement`](../vertexelement)映射到几何体的表面。

```csharp
public enum MappingMode
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| ControlPoint | `0` | 每个数据都映射到几何的控制点。 |
| PolygonVertex | `1` | 数据映射到多边形的顶点 当一个控制点被多个多边形共享时，数据映射为PolygonVertex，作为不同多边形顶点的控制点会有自己的data |
| Polygon | `2` | 数据映射到多边形。 映射模式为时，每个多边形顶点共享相同的数据Polygon. |
| Edge | `3` | 数据映射到边缘。 映射时每个边缘端点共享相同的数据Edge. |
| AllSame | `4` | 一个数据映射到整个表面。 任何数据被解释为控制点/多边形顶点/边缘端点，数据始终与定义的相同AllSame. |

### 也可以看看

* 命名空间 [Aspose.ThreeD.Entities](../../aspose.threed.entities)
* 部件 [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
