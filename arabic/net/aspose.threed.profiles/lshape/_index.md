---
title: LShape
second_title: Aspose.3D لمرجع .NET API
description: ملف تعريف على شكل حرف L متوافق مع IFC والذي تم تحديده بواسطة المعلمات.
type: docs
weight: 1580
url: /ar/net/aspose.threed.profiles/lshape/
---
## LShape class

ملف تعريف على شكل حرف L متوافق مع IFC والذي تم تحديده بواسطة المعلمات.

```csharp
public class LShape : ParameterizedProfile
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [LShape](lshape)() | منشئ[`LShape`](../lshape) |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Depth](../../aspose.threed.profiles/lshape/depth) { get; set; } | الحصول على عمق ملف التعريف أو تحديده . |
| [EdgeRadius](../../aspose.threed.profiles/lshape/edgeradius) { get; set; } | الحصول على أو تحديد نصف قطر الحافة. |
| [Excluded](../../aspose.threed/entity/excluded) { get; set; } | الحصول على أو تعيين ما إذا كان سيتم استبعاد هذا الكيان أثناء التصدير. |
| [FilletRadius](../../aspose.threed.profiles/lshape/filletradius) { get; set; } | الحصول على أو تحديد نصف قطر الشريحة. |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | الحصول على الاسم أو تعيينه . |
| [ParentNode](../../aspose.threed/entity/parentnode) { get; set; } | الحصول على العقدة الأصلية الأولى أو تعيينها ، إذا تم تعيين العقدة الأصلية الأولى ، فسيتم فصل هذا الكيان عن العقد الأصلية الأخرى. |
| [ParentNodes](../../aspose.threed/entity/parentnodes) { get; } | للحصول على جميع العقد الأصلية ، يمكن إرفاق كيان بالعقد الأصلية المتعددة من أجل هندسة instancing |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | الحصول على مجموعة من كافة الخصائص . |
| [Scene](../../aspose.threed/sceneobject/scene) { get; } | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [Thickness](../../aspose.threed.profiles/lshape/thickness) { get; set; } | الحصول على أو تحديد سمك الجدار الثابت. |
| [Width](../../aspose.threed.profiles/lshape/width) { get; set; } | الحصول على أو تحديد عرض ملف التعريف . |

## طُرق

| اسم | وصف |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | البحث عن الخاصية. يمكن أن تكون خاصية ديناميكية (تم إنشاؤها بواسطة CreateDynamicProperty / SetProperty) أو خاصية أصلية (محددة باسمها) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox)() | الحصول على المربع المحيط للكيان الحالي في نظام إحداثيات مساحة الكائن. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey)() | الحصول على مفتاح عارض الكيان المسجل في العارض |
| override [GetExtent](../../aspose.threed.profiles/lshape/getextent)() | الحصول على المدى في البعد x و y . |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | الحصول على قيمة الخاصية المحددة |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | يزيل خاصية ديناميكية . |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | إزالة الخاصية المحددة المحددة بالاسم |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | يحدد قيمة الخاصية المحددة |

### أنظر أيضا

* class [ParameterizedProfile](../parameterizedprofile)
* مساحة الاسم [Aspose.ThreeD.Profiles](../../aspose.threed.profiles)
* المجسم [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
