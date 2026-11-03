---
title: "BoundingBox.OverlapsWith"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "طريقة BoundingBox. تحقق مما إذا كان مربع الحد الحالي يتقاطع مع مربع الحد المحدد"
type: docs
weight: 140
url: /ar/net/aspose.threed.utilities/boundingbox/overlapswith/
---
## BoundingBox.OverlapsWith method

تحقق مما إذا كان صندوق الحدود الحالي يتداخل مع صندوق الحدود المحدد.

```csharp
public bool OverlapsWith(BoundingBox box)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| box | BoundingBox | مربع الحد الآخر للاختبار |

### قيمة الإرجاع

صحيح إذا كان مربع الحد الحالي يتقاطع مع المربع المعطى.

## أمثلة

الكود التالي يوضح كيفية التحقق مما إذا كان مربعا الحد يتقاطعان مع بعضهما البعض.

```csharp
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
var bbox2 = new BoundingBox(1, 1, 1, 11, 11, 11);
Console.WriteLine("Bounding box overlaps = " + boundingBox.OverlapsWith(bbox2));
```

### انظر أيضًا

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


