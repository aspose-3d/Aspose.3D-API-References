---
title: "BoundingBox.BoundingBox"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "منشئ BoundingBox. تهيئة مربع حد محدود بأقصى الزاويتين الدنيا والعليا المعطاة"
type: docs
weight: 10
url: /ar/net/aspose.threed.utilities/boundingbox/boundingbox/
---
## BoundingBox(Vector3, Vector3) {#constructor}

تهيئة صندوق حدود محدود مع الزاوية الدنيا والزاوية العليا المحددة.

```csharp
public BoundingBox(Vector3 minimum, Vector3 maximum)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| الحد الأدنى | Vector3 | الزاوية الدنيا |
| الحد الأقصى | Vector3 | الزاوية العليا |

## أمثلة

الكود التالي يوضح كيفية إنشاء مربع حد من الزاويتين الدنيا والعليا.

```csharp
var minimum = new Vector3(0, 0, 0);
var maximum = new Vector3(10, 10, 10);
var boundingBox = new BoundingBox(minimum, maximum);
Console.WriteLine("Bounding box = " + boundingBox);
```

### انظر أيضًا

* struct [Vector3](../../vector3/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## BoundingBox(double, double, double, double, double, double) {#constructor_1}

تهيئة صندوق حدود محدود مع الزاوية الدنيا والزاوية العليا المحددة.

```csharp
public BoundingBox(double minX, double minY, double minZ, double maxX, double maxY, double maxZ)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| minX | مضاعف | الإحداثي X للزاوية الدنيا |
| minY | مضاعف | الإحداثي Y للزاوية الدنيا |
| minZ | مضاعف | الإحداثي Z للزاوية الدنيا |
| maxX | مضاعف | الزاوية القصوى X |
| maxY | مضاعف | الزاوية القصوى Y |
| maxZ | مضاعف | الزاوية القصوى Z |

## أمثلة

الكود التالي يوضح كيفية إنشاء مربع حد من الزاويتين الدنيا والعليا.

```csharp
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
Console.WriteLine("Bounding box = " + boundingBox);
```

### انظر أيضًا

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


