---
title: "الفئة Ellipse"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Entities.Ellipse. تحدد الـ Ellipse مجموعة من النقاط التي تشكل شكل القطع الناقص"
type: docs
weight: 380
url: /ar/net/aspose.threed.entities/ellipse/
---
## Ellipse class

`Ellipse` يحدد مجموعة من النقاط التي تشكل شكل القطع الناقص.

```csharp
public class Ellipse : Curve
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [Ellipse](ellipse/#constructor)() | منشئ `Ellipse` |
| [Ellipse](ellipse/#constructor_1)(double, double) | منشئ `Ellipse` |

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
| [SemiAxis1](../../aspose.threed.entities/ellipse/semiaxis1/) { get; set; } | نصف القطر على المحور X |
| [SemiAxis2](../../aspose.threed.entities/ellipse/semiaxis2/) { get; set; } | نصف القطر على المحور Y |

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


