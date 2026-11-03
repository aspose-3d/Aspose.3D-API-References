---
title: "MathUtils.Clamp"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "طريقة MathUtils. قيد القيمة إلى النطاق الحد الأدنى الحد الأقصى"
type: docs
weight: 20
url: /ar/net/aspose.threed.utilities/mathutils/clamp/
---
## MathUtils.Clamp method

قيد القيمة إلى النطاق [الحد الأدنى، الحد الأقصى]

```csharp
public static double Clamp(double val, double min, double max)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| val | مضاعف | القيمة لتقييدها. |
| min | مضاعف | القيمة الدنيا. |
| max | مضاعف | القيمة القصوى. |

### قيمة الإرجاع

القيمة بين [الحد الأدنى، الحد الأقصى]

## أمثلة

```csharp
var val = 195;
//قيد القيمة إلى [0, 100]
var clampedValue = MathUtils.Clamp(val, 0, 100);
//سيعرض هذا 100
Console.WriteLine($"Value = {val}");
```

### انظر أيضًا

* class [MathUtils](../)
* namespace [Aspose.ThreeD.Utilities](../../mathutils/)
* assembly [Aspose.3D](../../../)


