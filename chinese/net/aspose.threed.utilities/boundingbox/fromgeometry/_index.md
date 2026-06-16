---
title: "BoundingBox.FromGeometry"
second_title: "Aspose.3D for .NET API 参考"
description: "BoundingBox 方法。根据给定的几何体构建边界框"
type: docs
weight: 40
url: /zh/net/aspose.threed.utilities/boundingbox/fromgeometry/
---
## BoundingBox.FromGeometry method

从给定几何体构建边界框

```csharp
public static BoundingBox FromGeometry(Geometry geometry)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 几何 | Geometry | 用于计算边界框的几何体 |

### 返回值

给定几何体的边界框

## 示例

以下代码展示了如何从几何实例构建边界框。

```csharp
var sphere = (new Sphere()).ToMesh();
var boundingBox = BoundingBox.FromGeometry(sphere);
Console.WriteLine("Bounding box = " + boundingBox);
```

### 另请参见

* class [Geometry](../../../aspose.threed.entities/geometry/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


