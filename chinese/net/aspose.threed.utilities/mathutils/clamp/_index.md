---
title: "MathUtils.Clamp"
second_title: "Aspose.3D for .NET API 参考"
description: "MathUtils 方法。将值限制在范围 min max 之间"
type: docs
weight: 20
url: /zh/net/aspose.threed.utilities/mathutils/clamp/
---
## MathUtils.Clamp method

将值限制在范围 [min, max] 内

```csharp
public static double Clamp(double val, double min, double max)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| val | Double | 要限制的值。 |
| min | Double | 最小值。 |
| max | Double | 最大值。 |

### 返回值

位于 [min, max] 之间的值

## 示例

```csharp
var val = 195;
//将值限制在 [0, 100] 之间
var clampedValue = MathUtils.Clamp(val, 0, 100);
//这将输出 100
Console.WriteLine($"Value = {val}");
```

### 另请参见

* class [MathUtils](../)
* namespace [Aspose.ThreeD.Utilities](../../mathutils/)
* assembly [Aspose.3D](../../../)


