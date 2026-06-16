---
title: "BoundingBox.BoundingBox"
second_title: "مرجع Aspose.3D for .NET API"
description: "منشئ BoundingBox. تهيئة صندوق حدود محدود مع الزاوية الدنيا والزاوية العليا المعطاة"
type: docs
weight: 10
url: /ar/net/aspose.threed.utilities/boundingbox/boundingbox/
---
## BoundingBox(Vector3, Vector3) {#constructor}

تهيئة صندوق إحاطة محدود مع الزاوية الدنيا والزاوية العليا المحددتين

```csharp
public BoundingBox(Vector3 minimum, Vector3 maximum)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| الحد الأدنى | Vector3 | الزاوية الدنيا |
| الحد الأقصى | Vector3 | الزاوية القصوى |

## أمثلة

الكود التالي يوضح كيفية إنشاء صندوق حدود من الزوايا الدنيا والعليا.

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

تهيئة صندوق إحاطة محدود مع الزاوية الدنيا والزاوية العليا المحددتين

```csharp
public BoundingBox(double minX, double minY, double minZ, double maxX, double maxY, double maxZ)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| minX | Double | X للزاوية الدنيا |
| minY | Double | Y للزاوية الدنيا |
| minZ | Double | Z للزاوية الدنيا |
| maxX | Double | X للزاوية العليا |
| maxY | Double | Y للزاوية العليا |
| maxZ | Double | Z للزاوية العليا |

## أمثلة

الكود التالي يوضح كيفية إنشاء صندوق حدود من الزوايا الدنيا والعليا.

```csharp
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
Console.WriteLine("Bounding box = " + boundingBox);
```

### انظر أيضًا

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


