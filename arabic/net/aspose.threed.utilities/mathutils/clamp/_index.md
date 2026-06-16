---
title: "MathUtils.Clamp"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة MathUtils. تقيد القيمة إلى النطاق الحد الأدنى والحد الأقصى"
type: docs
weight: 20
url: /ar/net/aspose.threed.utilities/mathutils/clamp/
---
## MathUtils.Clamp method

تقييد القيمة إلى النطاق [min, max]

```csharp
public static double Clamp(double val, double min, double max)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| val | Double | القيمة لتقيدها. |
| min | Double | القيمة الدنيا. |
| max | Double | القيمة القصوى. |

### قيمة الإرجاع

القيمة بين [min, max]

## أمثلة

```csharp
var val = 195;
//قيد القيمة إلى [0, 100]
var clampedValue = MathUtils.Clamp(val, 0, 100);
//سيتم إخراج 100
Console.WriteLine($"Value = {val}");
```

### انظر أيضًا

* class [MathUtils](../)
* namespace [Aspose.ThreeD.Utilities](../../mathutils/)
* assembly [Aspose.3D](../../../)


