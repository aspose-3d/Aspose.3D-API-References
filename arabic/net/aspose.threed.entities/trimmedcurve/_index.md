---
title: "فئة TrimmedCurve"
second_title: "مرجع Aspose.3D for .NET API"
description: "Aspose.ThreeD.Entities.TrimmedCurve فئة. منحنى محدود يقتطع المنحنى الأساسي عند الطرفين."
type: docs
weight: 810
url: /ar/net/aspose.threed.entities/trimmedcurve/
---
## TrimmedCurve class

منحنى محدود يقطع المنحنى الأساسي عند الطرفين.

```csharp
public class TrimmedCurve : Curve
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [TrimmedCurve](trimmedcurve/)() | منشئ `TrimmedCurve` |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BasisCurve](../../aspose.threed.entities/trimmedcurve/basiscurve/) { get; set; } | المنحنى الأساسي الذي سيتم تقطيعه. |
| [Color](../../aspose.threed.entities/curve/color/) { get; set; } | يحصل أو يضبط لون الخط، القيمة الافتراضية هي أبيض (1, 1, 1) |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | يحصل أو يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| [First](../../aspose.threed.entities/trimmedcurve/first/) { get; set; } | نقطة النهاية الأولى للتقليم، يمكن أن تكون نقطة ديكارتية أو معامل حقيقي. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | يحصل أو يعيّن العقدة الأصلية الأولى، إذا تم تعيين العقدة الأصلية الأولى، سيتم فصل هذا الكيان عن العقد الأصلية الأخرى. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | يحصل على جميع العقد الأصلية، يمكن إرفاق كيان بعدة عقد أصلية لتكرار الهندسة. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [SameDirection](../../aspose.threed.entities/trimmedcurve/samedirection/) { get; set; } | يحصل أو يضبط ما إذا كانت النتيجة المقطوعة تستخدم نفس اتجاه المنحنى الأساسي. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [Second](../../aspose.threed.entities/trimmedcurve/second/) { get; set; } | نقطة النهاية الثانية للتقليم، يمكن أن تكون نقطة ديكارتية أو معامل حقيقي. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | يجد الخاصية. يمكن أن تكون خاصية ديناميكية (Created by CreateDynamicProperty/SetProperty) أو خاصية أصلية (Identified by its name) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | يحصل على صندوق الحدود للكيان الحالي في نظام إحداثيات مساحة الكائن الخاصة به. |
| override [GetEntityRendererKey](../../aspose.threed.entities/curve/getentityrendererkey/)() | يحصل على مفتاح عارض الكيان المسجل في العارض |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | احصل على قيمة الخاصية المحددة |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | يزيل خاصية ديناميكية. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | إزالة الخاصية المحددة بالاسم |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | يضبط قيمة الخاصية المحددة |

### انظر أيضًا

* class [Curve](../curve/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


