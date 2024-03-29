---
title: TrimmedCurve
second_title: Aspose.3D لمرجع .NET API
description: منحنى محدد قام بقص منحنى الأساس عند كلا الطرفين.
type: docs
weight: 750
url: /ar/net/aspose.threed.entities/trimmedcurve/
---
## TrimmedCurve class

منحنى محدد قام بقص منحنى الأساس عند كلا الطرفين.

```csharp
public class TrimmedCurve : Curve
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [TrimmedCurve](trimmedcurve)() | منشئ[`TrimmedCurve`](../trimmedcurve) |

## الخصائص

| اسم | وصف |
| --- | --- |
| [BasisCurve](../../aspose.threed.entities/trimmedcurve/basiscurve) { get; set; } | منحنى الأساس المراد قطعه . |
| [Color](../../aspose.threed.entities/curve/color) { get; set; } | الحصول على لون الخط أو تعيينه ، القيمة الافتراضية هي الأبيض (1 ، 1 ، 1) |
| [Excluded](../../aspose.threed/entity/excluded) { get; set; } | الحصول على أو تعيين ما إذا كان سيتم استبعاد هذا الكيان أثناء التصدير. |
| [First](../../aspose.threed.entities/trimmedcurve/first) { get; set; } | يمكن أن تكون نقطة النهاية الأولى المراد اقتطاعها نقطة ديكارتية أو معلمة حقيقية. |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | الحصول على الاسم أو تعيينه . |
| [ParentNode](../../aspose.threed/entity/parentnode) { get; set; } | الحصول على العقدة الأصلية الأولى أو تعيينها ، إذا تم تعيين العقدة الأصلية الأولى ، فسيتم فصل هذا الكيان عن العقد الأصلية الأخرى. |
| [ParentNodes](../../aspose.threed/entity/parentnodes) { get; } | للحصول على جميع العقد الأصلية ، يمكن إرفاق كيان بالعقد الأصلية المتعددة من أجل هندسة instancing |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | الحصول على مجموعة من كافة الخصائص . |
| [SameDirection](../../aspose.threed.entities/trimmedcurve/samedirection) { get; set; } | الحصول على أو تحديد ما إذا كانت النتيجة المقتصة تستخدم نفس اتجاه منحنى الأساس. |
| [Scene](../../aspose.threed/sceneobject/scene) { get; } | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [Second](../../aspose.threed.entities/trimmedcurve/second) { get; set; } | يمكن أن تكون نقطة النهاية الثانية المراد اقتطاعها نقطة ديكارتية أو معلمة حقيقية. |

## طُرق

| اسم | وصف |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | البحث عن الخاصية. يمكن أن تكون خاصية ديناميكية (تم إنشاؤها بواسطة CreateDynamicProperty / SetProperty) أو خاصية أصلية (محددة باسمها) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox)() | الحصول على المربع المحيط للكيان الحالي في نظام إحداثيات مساحة الكائن. |
| override [GetEntityRendererKey](../../aspose.threed.entities/curve/getentityrendererkey)() | الحصول على مفتاح عارض الكيان المسجل في العارض |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | الحصول على قيمة الخاصية المحددة |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | يزيل خاصية ديناميكية . |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | إزالة الخاصية المحددة المحددة بالاسم |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | يحدد قيمة الخاصية المحددة |

### أنظر أيضا

* class [Curve](../curve)
* مساحة الاسم [Aspose.ThreeD.Entities](../../aspose.threed.entities)
* المجسم [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
