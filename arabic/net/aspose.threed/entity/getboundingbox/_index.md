---
title: "Entity.GetBoundingBox"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "طريقة Entity. تحصل على صندوق الحدود للكيان الحالي في نظام إحداثيات مساحة كائنه."
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

مربع الحدود للكيان الحالي في نظام إحداثيات مساحة الكائن الخاص به.

## أمثلة

يعرض الكود التالي كيفية حساب مربع الحدود لشكل

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


