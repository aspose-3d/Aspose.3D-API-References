---
title: "BoundingBox.OverlapsWith"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة BoundingBox. تحقق مما إذا كان الصندوق الحدودي الحالي يتقاطع مع الصندوق الحدودي المحدد"
type: docs
weight: 140
url: /ar/net/aspose.threed.utilities/boundingbox/overlapswith/
---
## BoundingBox.OverlapsWith method

تحقق مما إذا كان صندوق الحدود الحالي يتقاطع مع صندوق الحدود المحدد.

```csharp
public bool OverlapsWith(BoundingBox box)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| صندوق | BoundingBox | الصندوق الحدودي الآخر للاختبار |

### قيمة الإرجاع

صحيح إذا كان الصندوق الحدودي الحالي يتقاطع مع الصندوق المحدد.

## أمثلة

الكود التالي يوضح كيفية التحقق مما إذا كان صندوقان حدّيان يتقاطعان مع بعضهما البعض.

```csharp
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
var bbox2 = new BoundingBox(1, 1, 1, 11, 11, 11);
Console.WriteLine("Bounding box overlaps = " + boundingBox.OverlapsWith(bbox2));
```

### انظر أيضًا

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


