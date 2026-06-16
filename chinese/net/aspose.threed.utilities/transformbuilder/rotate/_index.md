---
title: "TransformBuilder.Rotate"
second_title: "Aspose.3D for .NET API 参考"
description: "TransformBuilder 方法. 按四元数链式添加旋转"
type: docs
weight: 90
url: /zh/net/aspose.threed.utilities/transformbuilder/rotate/
---
## TransformBuilder.Rotate method

通过四元数进行旋转链式操作

```csharp
public TransformBuilder Rotate(Quaternion q)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| q | 四元数 |  |

## 示例

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Rotate(Quaternion.FromEulerAngle(0, Math.PI, 0));
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### 另请参见

* struct [Quaternion](../../quaternion/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)


