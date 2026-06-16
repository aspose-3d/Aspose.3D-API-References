---
title: "الفئة Sphere"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Entities.Sphere. كرة مُعلمة"
type: docs
weight: 730
url: /ar/net/aspose.threed.entities/sphere/
---
## Sphere class

كرة باراميتري.

```csharp
public class Sphere : Primitive
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [Sphere](sphere/#constructor)() | ينشئ مثيلاً جديداً من `Sphere` بنصف قطر افتراضي 1. |
| [Sphere](sphere/#constructor_1)(double) | ينشئ مثيلاً جديداً من الفئة `Sphere` بنصف قطر محدد. |
| [Sphere](sphere/#constructor_2)(double, int, int) | ينشئ مثيلاً جديداً من الفئة `Sphere` بنصف قطر محدد، مقاطع العرض ومقاطع الارتفاع. |
| [Sphere](sphere/#constructor_3)(string, double, int, int, double, double, double, double) | ينشئ مثيلاً جديداً من الفئة `Sphere`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | يحصل أو يضبط ما إذا كان هذا الشكل الهندسي يمكنه إلقاء الظل |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | يحصل أو يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| [HeightSegments](../../aspose.threed.entities/sphere/heightsegments/) { get; set; } | يحصل أو يضبط مقاطع الارتفاع. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | يحصل أو يعيّن العقدة الأصلية الأولى، إذا تم تعيين العقدة الأصلية الأولى، سيتم فصل هذا الكيان عن العقد الأصلية الأخرى. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | يحصل على جميع العقد الأصلية، يمكن إرفاق كيان بعدة عقد أصلية لتكرار الهندسة. |
| [PhiLength](../../aspose.threed.entities/sphere/philength/) { get; set; } | يحصل أو يضبط طول phi. |
| [PhiStart](../../aspose.threed.entities/sphere/phistart/) { get; set; } | يحصل أو يضبط بداية phi. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [Radius](../../aspose.threed.entities/sphere/radius/) { get; set; } | يحصل أو يضبط نصف قطر الكرة. |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | يحصل أو يعيّن ما إذا كانت هذه الهندسة يمكنها استقبال الظل. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [ThetaLength](../../aspose.threed.entities/sphere/thetalength/) { get; set; } | يحصل أو يضبط طول theta. |
| [ThetaStart](../../aspose.threed.entities/sphere/thetastart/) { get; set; } | يحصل أو يضبط بداية theta. |
| [WidthSegments](../../aspose.threed.entities/sphere/widthsegments/) { get; set; } | الحصول على أو تعيين مقاطع العرض. |

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
| override [ToMesh](../../aspose.threed.entities/sphere/tomesh/)() | تحويل الكائن الحالي إلى شبكة |

### انظر أيضًا

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


