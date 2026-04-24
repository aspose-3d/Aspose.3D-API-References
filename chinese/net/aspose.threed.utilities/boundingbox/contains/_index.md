---
title: BoundingBox.Contains
second_title: Aspose.3D for .NET API 参考手册
description: BoundingBox 方法。检查点 p 是否在包围盒内部
type: docs
weight: 100
url: /zh/net/aspose.threed.utilities/boundingbox/contains/
---
## Contains(Vector3) {#contains_1}

检查点 p 是否在边界框内部

```csharp
public bool Contains(Vector3 p)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| p | Vector3 | 要测试的点 |

### 返回值

如果点在包围盒内部，则为 True。

## 示例

以下代码演示如何检查点是否在包围盒内部。

```csharp
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
var pt = new Vector3(4, 4, 4);
Console.WriteLine("Bounding box overlaps = " + boundingBox.Contains(pt));
```

### 另请参见

* struct [Vector3](../../vector3/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Contains(BoundingBox) {#contains}

用于检查它是否在当前边界框内部的边界框。

```csharp
public bool Contains(BoundingBox bbox)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bbox | BoundingBox |  |

### 另请参见

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


