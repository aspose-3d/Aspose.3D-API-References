---
title: "فئة CShape"
second_title: "مرجع Aspose.3D for .NET API"
description: "فئة Aspose.ThreeD.Profiles.CShape. ملف تعريف Cshape متوافق مع IFC معرف بالمعلمات. موضع المركز للملف التعريفي في وسط صندوق الحدود"
type: docs
weight: 1680
url: /ar/net/aspose.threed.profiles/cshape/
---
## CShape class

ملف شخصي شكل C متوافق مع IFC يُحدد بالمعلمات. موضع المركز للملف الشخصي في وسط صندوق الحدود.

```csharp
public class CShape : ParameterizedProfile
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [CShape](cshape/)() | منشئ `CShape` |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Depth](../../aspose.threed.profiles/cshape/depth/) { get; set; } | يحصل أو يضبط عمق الملف التعريفي. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | يحصل أو يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| [Girth](../../aspose.threed.profiles/cshape/girth/) { get; set; } | يحصل أو يضبط طول المحيط. |
| [InternalFilletRadius](../../aspose.threed.profiles/cshape/internalfilletradius/) { get; set; } | يحصل أو يضبط نصف قطر القطع الدائري الداخلي. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | يحصل أو يعيّن العقدة الأصلية الأولى، إذا تم تعيين العقدة الأصلية الأولى، سيتم فصل هذا الكيان عن العقد الأصلية الأخرى. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | يحصل على جميع العقد الأصلية، يمكن إرفاق كيان بعدة عقد أصلية لتكرار الهندسة. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [WallThickness](../../aspose.threed.profiles/cshape/wallthickness/) { get; set; } | يحصل أو يضبط سمك الجدار. |
| [Width](../../aspose.threed.profiles/cshape/width/) { get; set; } | يحصل أو يضبط عرض الملف التعريفي. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | يجد الخاصية. يمكن أن تكون خاصية ديناميكية (Created by CreateDynamicProperty/SetProperty) أو خاصية أصلية (Identified by its name) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | يحصل على صندوق الحدود للكيان الحالي في نظام إحداثيات مساحة الكائن الخاصة به. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | يحصل على مفتاح عارض الكيان المسجل في العارض |
| override [GetExtent](../../aspose.threed.profiles/cshape/getextent/)() | يحصل على الامتداد في بعدي x و y. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | احصل على قيمة الخاصية المحددة |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | يزيل خاصية ديناميكية. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | إزالة الخاصية المحددة بالاسم |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | يضبط قيمة الخاصية المحددة |

### انظر أيضًا

* class [ParameterizedProfile](../parameterizedprofile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


