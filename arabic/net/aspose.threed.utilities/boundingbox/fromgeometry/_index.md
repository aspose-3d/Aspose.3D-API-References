---
title: "BoundingBox.FromGeometry"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة BoundingBox. إنشاء صندوق حدود من الهندسة المعطاة"
type: docs
weight: 40
url: /ar/net/aspose.threed.utilities/boundingbox/fromgeometry/
---
## BoundingBox.FromGeometry method

إنشاء صندوق حدود من الهندسة المعطاة

```csharp
public static BoundingBox FromGeometry(Geometry geometry)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| هندسة | هندسة | الهندسة لحساب صندوق الحدود |

### قيمة الإرجاع

صندوق الحدود للهندسة المعطاة

## أمثلة

الكود التالي يوضح كيفية إنشاء صندوق حدود من كائن هندسة.

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


