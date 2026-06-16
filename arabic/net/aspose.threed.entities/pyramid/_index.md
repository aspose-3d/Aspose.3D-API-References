---
title: "الفئة Pyramid"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Entities.Pyramid. هرم معلمات"
type: docs
weight: 650
url: /ar/net/aspose.threed.entities/pyramid/
---
## Pyramid class

هرم باراميتري.

```csharp
public class Pyramid : Primitive
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [Pyramid](pyramid/#constructor)() | إنشاء نسخة جديدة من الهرم مع مساحة القاعدة الافتراضية(10, 10) والارتفاع الافتراضي(5) |
| [Pyramid](pyramid/#constructor_1)(double, double, double) | إنشاء نسخة جديدة من الهرم مع مساحة قاعدة محددة |
| [Pyramid](pyramid/#constructor_2)(double, double, double, double, double) | إنشاء نسخة جديدة من الهرم مع مساحة قاعدة محددة ومساحة قمة محددة والارتفاع. |
| [Pyramid](pyramid/#constructor_3)(string, double, double, double, double, double) | إنشاء نسخة جديدة من الهرم مع مساحة قاعدة محددة ومساحة قمة محددة والارتفاع. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BottomArea](../../aspose.threed.entities/pyramid/bottomarea/) { get; set; } | مساحة الغطاء السفلي |
| [BottomOffset](../../aspose.threed.entities/pyramid/bottomoffset/) { get; set; } | الإزاحة للقمم السفلية |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | يحصل أو يضبط ما إذا كان هذا الشكل الهندسي يمكنه إلقاء الظل |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | يحصل أو يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| [Height](../../aspose.threed.entities/pyramid/height/) { get; set; } | ارتفاع الهرم |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | يحصل أو يعيّن العقدة الأصلية الأولى، إذا تم تعيين العقدة الأصلية الأولى، سيتم فصل هذا الكيان عن العقد الأصلية الأخرى. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | يحصل على جميع العقد الأصلية، يمكن إرفاق كيان بعدة عقد أصلية لتكرار الهندسة. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | يحصل أو يعيّن ما إذا كانت هذه الهندسة يمكنها استقبال الظل. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [TopArea](../../aspose.threed.entities/pyramid/toparea/) { get; set; } | مساحة الغطاء العلوي |

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
| override [ToMesh](../../aspose.threed.entities/pyramid/tomesh/)() | تحويل الكائن الحالي إلى شبكة |

### انظر أيضًا

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


