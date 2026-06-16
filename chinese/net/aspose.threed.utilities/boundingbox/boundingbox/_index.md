---
title: "BoundingBox.BoundingBox"
second_title: "Aspose.3D for .NET API 参考"
description: "BoundingBox 构造函数。使用给定的最小角和最大角初始化有限边界框"
type: docs
weight: 10
url: /zh/net/aspose.threed.utilities/boundingbox/boundingbox/
---
## BoundingBox(Vector3, Vector3) {#constructor}

使用给定的最小角和最大角初始化有限包围盒

```csharp
public BoundingBox(Vector3 minimum, Vector3 maximum)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 最小 | Vector3 | 最小角 |
| 最大 | Vector3 | 最大角点 |

## 示例

以下代码展示了如何根据最小角和最大角构建边界框。

```csharp
var minimum = new Vector3(0, 0, 0);
var maximum = new Vector3(10, 10, 10);
var boundingBox = new BoundingBox(minimum, maximum);
Console.WriteLine("Bounding box = " + boundingBox);
```

### 另请参见

* struct [Vector3](../../vector3/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## BoundingBox(double, double, double, double, double, double) {#constructor_1}

使用给定的最小角和最大角初始化有限包围盒

```csharp
public BoundingBox(double minX, double minY, double minZ, double maxX, double maxY, double maxZ)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| minX | Double | 最小角的 X 坐标 |
| minY | Double | 最小角的 Y 坐标 |
| minZ | Double | 最小角的 Z 坐标 |
| maxX | Double | 最大角的 X 坐标 |
| maxY | Double | 最大角的 Y 坐标 |
| maxZ | Double | 最大角的 Z 坐标 |

## 示例

以下代码展示了如何根据最小角和最大角构建边界框。

```csharp
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
Console.WriteLine("Bounding box = " + boundingBox);
```

### 另请参见

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


