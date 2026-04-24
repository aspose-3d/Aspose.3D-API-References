---
title: Mesh.Triangulate
second_title: Aspose.3D for .NET API 参考手册
description: Mesh 方法。返回三角化网格
type: docs
weight: 120
url: /zh/net/aspose.threed.entities/mesh/triangulate/
---
## Mesh.Triangulate method

返回三角化网格

```csharp
public Mesh Triangulate()
```

### 返回值

如果当前网格已经三角化，则返回当前网格；否则将计算并返回新的三角化网格

## 示例

以下代码展示了如何对网格进行三角化：

```csharp
//平面网格只有一个具有4个控制点的多边形
var mesh = (new Plane()).ToMesh();
//三角化后，新网格的矩形将变为2个三角形。
var triangulated = mesh.Triangulate();
```

### 另请参见

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


