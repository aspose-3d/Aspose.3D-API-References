---
title: "BoundingBox.FromGeometry"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "طريقة BoundingBox. إنشاء مربع حد من الشكل الهندسي المعطى"
type: docs
weight: 40
url: /ar/net/aspose.threed.utilities/boundingbox/fromgeometry/
---
## BoundingBox.FromGeometry method

إنشاء صندوق حدود من الهندسة المعطاة.

```csharp
public static BoundingBox FromGeometry(Geometry geometry)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| هندسة | هندسة | الشكل الهندسي لحساب مربع الحد |

### قيمة الإرجاع

مربع الحد للشكل الهندسي المعطى

## أمثلة

الكود التالي يوضح كيفية إنشاء مربع حد من كائن الشكل الهندسي.

```csharp
var sphere = (new Sphere()).ToMesh();
var boundingBox = BoundingBox.FromGeometry(sphere);
Console.WriteLine("Bounding box = " + boundingBox);
```

### انظر أيضًا

* class [Geometry](../../../aspose.threed.entities/geometry/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


