---
title: "الفئة ZShape"
second_title: "مرجع Aspose.3D for .NET API"
description: "فئة Aspose.ThreeD.Profiles.ZShape. ملف تعريف Zshape متوافق مع IFC معرف بالمعلمات"
type: docs
weight: 1850
url: /ar/net/aspose.threed.profiles/zshape/
---
## ZShape class

ملف شخصي شكل Z متوافق مع IFC يُحدد بالمعلمات.

```csharp
public class ZShape : ParameterizedProfile
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [ZShape](zshape/)() | منشئ `ZShape` |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Depth](../../aspose.threed.profiles/zshape/depth/) { get; set; } | يحصل أو يضبط طول الويب. |
| [EdgeRadius](../../aspose.threed.profiles/zshape/edgeradius/) { get; set; } | يحصل أو يضبط نصف قطر حافة الشفة. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | يحصل أو يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| [FilletRadius](../../aspose.threed.profiles/zshape/filletradius/) { get; set; } | يحصل أو يضبط نصف قطر القطع الدائري بين الشفة والويب. |
| [FlangeThickness](../../aspose.threed.profiles/zshape/flangethickness/) { get; set; } | يحصل أو يضبط سمك الشفة. |
| [FlangeWidth](../../aspose.threed.profiles/zshape/flangewidth/) { get; set; } | يحصل أو يضبط طول الشفة. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | يحصل أو يعيّن العقدة الأصلية الأولى، إذا تم تعيين العقدة الأصلية الأولى، سيتم فصل هذا الكيان عن العقد الأصلية الأخرى. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | يحصل على جميع العقد الأصلية، يمكن إرفاق كيان بعدة عقد أصلية لتكرار الهندسة. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [WebThickness](../../aspose.threed.profiles/zshape/webthickness/) { get; set; } | يحصل أو يضبط سمك الجدار. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | يجد الخاصية. يمكن أن تكون خاصية ديناميكية (Created by CreateDynamicProperty/SetProperty) أو خاصية أصلية (Identified by its name) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | يحصل على صندوق الحدود للكيان الحالي في نظام إحداثيات مساحة الكائن الخاصة به. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | يحصل على مفتاح عارض الكيان المسجل في العارض |
| override [GetExtent](../../aspose.threed.profiles/zshape/getextent/)() | يحصل على الامتداد في بعدي x و y. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | احصل على قيمة الخاصية المحددة |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | يزيل خاصية ديناميكية. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | إزالة الخاصية المحددة بالاسم |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | يضبط قيمة الخاصية المحددة |

### انظر أيضًا

* class [ParameterizedProfile](../parameterizedprofile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


