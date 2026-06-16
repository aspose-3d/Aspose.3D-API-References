---
title: "فئة TransformedCurve"
second_title: "مرجع Aspose.3D for .NET API"
description: "Aspose.ThreeD.Entities.TransformedCurve فئة. يمنح TransformedCurve منحنىً موضعاً باستخدام مصفوفة تحويل. هذا يسمح بأداء تحويل داخل TrimmedCurve أو CompositeCurve."
type: docs
weight: 780
url: /ar/net/aspose.threed.entities/transformedcurve/
---
## TransformedCurve class

`TransformedCurve` يمنح منحنىً موضعاً باستخدام مصفوفة تحويل. هذا يسمح بأداء تحويل داخل [`TrimmedCurve`](../trimmedcurve/) أو [`CompositeCurve`](../compositecurve/).

```csharp
public class TransformedCurve : Curve
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [TransformedCurve](transformedcurve/#constructor)() | منشئ `TransformedCurve` |
| [TransformedCurve](transformedcurve/#constructor_1)(Curve, Matrix4) | منشئ `TransformedCurve` |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BasisCurve](../../aspose.threed.entities/transformedcurve/basiscurve/) { get; set; } | منحنى الأساس. |
| [Color](../../aspose.threed.entities/curve/color/) { get; set; } | يحصل أو يضبط لون الخط، القيمة الافتراضية هي أبيض (1, 1, 1) |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | يحصل أو يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | يحصل أو يعيّن العقدة الأصلية الأولى، إذا تم تعيين العقدة الأصلية الأولى، سيتم فصل هذا الكيان عن العقد الأصلية الأخرى. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | يحصل على جميع العقد الأصلية، يمكن إرفاق كيان بعدة عقد أصلية لتكرار الهندسة. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [TransformMatrix](../../aspose.threed.entities/transformedcurve/transformmatrix/) { get; set; } | مصفوفة التحويل. |

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


