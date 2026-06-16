---
title: "الفئة Box"
second_title: "مرجع Aspose.3D for .NET API"
description: "Aspose.ThreeD.Entities.Box الفئة. Box"
type: docs
weight: 290
url: /ar/net/aspose.threed.entities/box/
---
## Box class

صندوق.

```csharp
public class Box : Primitive
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [Box](box/#constructor)() | يُنشئ مثيلاً جديدًا لـ `Box` الفئة. |
| [Box](box/#constructor_1)(double, double, double) | يُنشئ مثيلاً جديدًا لـ `Box` الفئة. |
| [Box](box/#constructor_2)(string, double, double, double, int, int, int) | يُنشئ مثيلاً جديدًا لـ `Box` الفئة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | يحصل أو يضبط ما إذا كان هذا الشكل الهندسي يمكنه إلقاء الظل |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | يحصل أو يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| [Height](../../aspose.threed.entities/box/height/) { get; set; } | يحصل أو يعيّن ارتفاع الصندوق المتّ align على محور y. |
| [HeightSegments](../../aspose.threed.entities/box/heightsegments/) { get; set; } | يحصل أو يعيّن مقاطع الارتفاع. |
| [Length](../../aspose.threed.entities/box/length/) { get; set; } | يحصل أو يعيّن طول الصندوق المتّ align على محور z. |
| [LengthSegments](../../aspose.threed.entities/box/lengthsegments/) { get; set; } | الحصول على أو تعيين مقاطع الطول. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | يحصل أو يعيّن العقدة الأصلية الأولى، إذا تم تعيين العقدة الأصلية الأولى، سيتم فصل هذا الكيان عن العقد الأصلية الأخرى. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | يحصل على جميع العقد الأصلية، يمكن إرفاق كيان بعدة عقد أصلية لتكرار الهندسة. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | يحصل أو يعيّن ما إذا كانت هذه الهندسة يمكنها استقبال الظل. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [Width](../../aspose.threed.entities/box/width/) { get; set; } | يحصل أو يعيّن عرض الصندوق المتّ align على محور x. |
| [WidthSegments](../../aspose.threed.entities/box/widthsegments/) { get; set; } | يحصل أو يعيّن مقاطع العرض |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | يجد الخاصية. يمكن أن تكون خاصية ديناميكية (Created by CreateDynamicProperty/SetProperty) أو خاصية أصلية (Identified by its name) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | يحصل على صندوق الحدود للكيان الحالي في نظام إحداثيات مساحة الكائن الخاصة به. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | يحصل على مفتاح عارض الكيان المسجل في العارض |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | احصل على قيمة الخاصية المحددة |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | يزيل خاصية ديناميكية. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | إزالة الخاصية المحددة بالاسم |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | يضبط قيمة الخاصية المحددة |
| override [ToMesh](../../aspose.threed.entities/box/tomesh/)() | تحويل الكائن الحالي إلى شبكة |

### انظر أيضًا

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


