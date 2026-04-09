---
title: BoundingBox.OverlapsWith
second_title: مرجع API Aspose.3D لـ .NET
description: طريقة BoundingBox. تحقق مما إذا كان الصندوق الحدودي الحالي يتداخل مع الصندوق الحدودي المحدد
type: docs
weight: 140
url: /ar/net/aspose.threed.utilities/boundingbox/overlapswith/
---
## BoundingBox.OverlapsWith method

تحقق مما إذا كان مربع الحد الحالي يتقاطع مع مربع الحد المحدد.

```csharp
public bool OverlapsWith(BoundingBox box)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| صندوق | BoundingBox | صندوق الاحتواء الآخر للاختبار |

### قيمة الإرجاع

صحيح إذا كان الصندوق الحدودي الحالي يتداخل مع الصندوق المعطى.

## Examples

الكود التالي يوضح كيفية التحقق مما إذا كان صندوقان حدّيان يتداخلان مع بعضهما البعض.

```csharp
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
var bbox2 = new BoundingBox(1, 1, 1, 11, 11, 11);
Console.WriteLine("Bounding box overlaps = " + boundingBox.OverlapsWith(bbox2));
```

### انظر أيضًا

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


