---
title: "الفئة CompositeCurve"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Entities.CompositeCurve. CompositeCurve يتكون من عدة مقاطع من المنحنيات."
type: docs
weight: 320
url: /ar/net/aspose.threed.entities/compositecurve/
---
## CompositeCurve class

`CompositeCurve` يتكون من عدة مقاطع من المنحنيات.

```csharp
public class CompositeCurve : Curve
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [CompositeCurve](compositecurve/)() | منشئ `CompositeCurve` |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Color](../../aspose.threed.entities/curve/color/) { get; set; } | يحصل أو يضبط لون الخط، القيمة الافتراضية هي أبيض (1, 1, 1) |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | يحصل أو يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | يحصل أو يعيّن العقدة الأصلية الأولى، إذا تم تعيين العقدة الأصلية الأولى، سيتم فصل هذا الكيان عن العقد الأصلية الأخرى. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | يحصل على جميع العقد الأصلية، يمكن إرفاق كيان بعدة عقد أصلية لتكرار الهندسة. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [Segments](../../aspose.threed.entities/compositecurve/segments/) { get; } | مقاطع المنحنى. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddSegment](../../aspose.threed.entities/compositecurve/addsegment/)(Curve, bool) | أضف مقطعاً جديداً إلى المنحنى الحالي. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | يجد الخاصية. يمكن أن تكون خاصية ديناميكية (Created by CreateDynamicProperty/SetProperty) أو خاصية أصلية (Identified by its name) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | يحصل على صندوق الحدود للكيان الحالي في نظام إحداثيات مساحة الكائن الخاصة به. |
| override [GetEntityRendererKey](../../aspose.threed.entities/curve/getentityrendererkey/)() | يحصل على مفتاح عارض الكيان المسجل في العارض |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | احصل على قيمة الخاصية المحددة |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | يزيل خاصية ديناميكية. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | إزالة الخاصية المحددة بالاسم |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | يضبط قيمة الخاصية المحددة |

## الأعضاء الأخرى

| الاسم | الوصف |
| --- | --- |
| class [Segment](../../aspose.threed.entities/compositecurve.segment) |  |

### انظر أيضًا

* class [Curve](../curve/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


