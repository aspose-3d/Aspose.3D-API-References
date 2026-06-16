---
title: "Entity.GetBoundingBox"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة Entity. تحصل على صندوق الحدود للكيان الحالي في نظام إحداثيات مساحة الكائن الخاصة به"
type: docs
weight: 50
url: /ar/net/aspose.threed/entity/getboundingbox/
---
## Entity.GetBoundingBox method

يحصل على صندوق الحدود للكيان الحالي في نظام إحداثيات مساحة الكائن الخاصة به.

```csharp
public BoundingBox GetBoundingBox()
```

### قيمة الإرجاع

صندوق الحدود للكيان الحالي في نظام إحداثيات مساحة الكائن الخاصة به.

## أمثلة

الكود التالي يوضح كيفية حساب صندوق الحدود لشكل

```csharp
Entity entity = new Sphere() { Radius = 10 };
var bbox = entity.GetBoundingBox();
Console.WriteLine($"The bounding box of the entity is {bbox.Minimum} ~ {bbox.Maximum}");
```

### انظر أيضًا

* struct [BoundingBox](../../../aspose.threed.utilities/boundingbox/)
* class [Entity](../)
* namespace [Aspose.ThreeD](../../entity/)
* assembly [Aspose.3D](../../../)


