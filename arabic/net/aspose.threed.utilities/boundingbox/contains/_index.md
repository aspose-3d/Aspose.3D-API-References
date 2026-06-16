---
title: "BoundingBox.Contains"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة BoundingBox. تحقق مما إذا كانت النقطة p داخل الصندوق الحدودي"
type: docs
weight: 100
url: /ar/net/aspose.threed.utilities/boundingbox/contains/
---
## Contains(Vector3) {#contains_1}

تحقق مما إذا كانت النقطة p داخل صندوق الحدود

```csharp
public bool Contains(Vector3 p)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| p | Vector3 | النقطة للاختبار |

### قيمة الإرجاع

صحيح إذا كانت النقطة داخل الصندوق الحدودي

## أمثلة

الكود التالي يوضح كيفية التحقق مما إذا كانت نقطة داخل الصندوق الحدودي.

```csharp
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
var pt = new Vector3(4, 4, 4);
Console.WriteLine("Bounding box overlaps = " + boundingBox.Contains(pt));
```

### انظر أيضًا

* struct [Vector3](../../vector3/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Contains(BoundingBox) {#contains}

صندوق الحدود للتحقق مما إذا كان داخل صندوق الحدود الحالي.

```csharp
public bool Contains(BoundingBox bbox)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| bbox | BoundingBox |  |

### انظر أيضًا

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


