---
title: BoundingBox.OverlapsWith
second_title: Aspose.3D for .NET API 参考手册
description: BoundingBox 方法。检查当前包围盒是否与指定的包围盒重叠
type: docs
weight: 140
url: /zh/net/aspose.threed.utilities/boundingbox/overlapswith/
---
## BoundingBox.OverlapsWith method

检查当前边界框是否与指定的边界框重叠。

```csharp
public bool OverlapsWith(BoundingBox box)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 盒子 | BoundingBox | 要测试的另一个边界框 |

### 返回值

如果当前包围盒与给定的包围盒重叠，则为 True。

## 示例

以下代码演示如何检查两个包围盒是否相互重叠。

```csharp
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
var bbox2 = new BoundingBox(1, 1, 1, 11, 11, 11);
Console.WriteLine("Bounding box overlaps = " + boundingBox.OverlapsWith(bbox2));
```

### 另请参见

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


