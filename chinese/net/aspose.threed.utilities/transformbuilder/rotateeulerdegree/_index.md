---
title: "TransformBuilder.RotateEulerDegree"
second_title: "Aspose.3D for .NET API 参考"
description: "TransformBuilder 方法. 按欧拉角（度）链式添加旋转"
type: docs
weight: 110
url: /zh/net/aspose.threed.utilities/transformbuilder/rotateeulerdegree/
---
## TransformBuilder.RotateEulerDegree method

通过欧拉角（度）进行旋转链式操作

```csharp
public TransformBuilder RotateEulerDegree(double degX, double degY, double degZ)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| degX | Double |  |
| degY | Double |  |
| degZ | Double |  |

## 示例

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateEulerDegree(0, 90, 0);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### 另请参见

* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)


