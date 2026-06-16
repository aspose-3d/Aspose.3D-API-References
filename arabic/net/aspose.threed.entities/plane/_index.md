---
title: "الفئة Plane"
second_title: "مرجع Aspose.3D for .NET API"
description: "فئة Aspose.ThreeD.Entities.Plane. سطح معلم"
type: docs
weight: 590
url: /ar/net/aspose.threed.entities/plane/
---
## Plane class

سطح باراميتري.

```csharp
public class Plane : Primitive
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [Plane](plane/#constructor)() | يُنشئ نسخة جديدة من `Plane` بالحجم الافتراضي 1x1. |
| [Plane](plane/#constructor_1)(double, double) | يُنشئ نسخة جديدة من `Plane`. |
| [Plane](plane/#constructor_2)(string, double, double, int, int) | يُنشئ نسخة جديدة من `Plane`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | يحصل أو يضبط ما إذا كان هذا الشكل الهندسي يمكنه إلقاء الظل |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | يحصل أو يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| [Length](../../aspose.threed.entities/plane/length/) { get; set; } | الحصول على أو تعيين طول السطح. |
| [LengthSegments](../../aspose.threed.entities/plane/lengthsegments/) { get; set; } | الحصول على أو تعيين مقاطع الطول. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | يحصل أو يعيّن العقدة الأصلية الأولى، إذا تم تعيين العقدة الأصلية الأولى، سيتم فصل هذا الكيان عن العقد الأصلية الأخرى. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | يحصل على جميع العقد الأصلية، يمكن إرفاق كيان بعدة عقد أصلية لتكرار الهندسة. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | يحصل أو يعيّن ما إذا كانت هذه الهندسة يمكنها استقبال الظل. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [Up](../../aspose.threed.entities/plane/up/) { get; set; } | الحصول على أو تعيين المتجه العلوي للسطح، القيمة الافتراضية هي (0, 1, 0)، وهذا يؤثر على إنشاء السطح. |
| [Width](../../aspose.threed.entities/plane/width/) { get; set; } | الحصول على أو تعيين عرض السطح. |
| [WidthSegments](../../aspose.threed.entities/plane/widthsegments/) { get; set; } | الحصول على أو تعيين مقاطع العرض. |

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
| override [ToMesh](../../aspose.threed.entities/plane/tomesh/)() | تحويل الكائن الحالي إلى شبكة |

### انظر أيضًا

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


