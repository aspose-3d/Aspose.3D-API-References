---
title: "الفئة RectangleShape"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Profiles.RectangleShape. شكل مستطيل متوافق مع IFC مع زوايا مستديرة"
type: docs
weight: 1800
url: /ar/net/aspose.threed.profiles/rectangleshape/
---
## RectangleShape class

شكل مستطيل متوافق مع IFC مع زوايا مستديرة.

```csharp
public class RectangleShape : ParameterizedProfile
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [RectangleShape](rectangleshape/#constructor)() | منشئ `RectangleShape` |
| [RectangleShape](rectangleshape/#constructor_1)(double, double) | منشئ `RectangleShape` بأبعاد محددة على المحور x والمحور y. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | يحصل أو يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | يحصل أو يعيّن العقدة الأصلية الأولى، إذا تم تعيين العقدة الأصلية الأولى، سيتم فصل هذا الكيان عن العقد الأصلية الأخرى. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | يحصل على جميع العقد الأصلية، يمكن إرفاق كيان بعدة عقد أصلية لتكرار الهندسة. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [RoundingRadius](../../aspose.threed.profiles/rectangleshape/roundingradius/) { get; set; } | يحصل أو يعيّن نصف قطر الأقواس الدائرية لجميع الزوايا الأربعة، مقاسًا بالدرجات. القيمة الافتراضية هي 0.0 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [XDim](../../aspose.threed.profiles/rectangleshape/xdim/) { get; set; } | يحصل أو يعيّن امتداد المستطيل في اتجاه محور x. القيمة الافتراضية هي 2.0 |
| [YDim](../../aspose.threed.profiles/rectangleshape/ydim/) { get; set; } | يحصل أو يعيّن امتداد المستطيل في اتجاه محور y. القيمة الافتراضية هي 2.0 |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | يجد الخاصية. يمكن أن تكون خاصية ديناميكية (Created by CreateDynamicProperty/SetProperty) أو خاصية أصلية (Identified by its name) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | يحصل على صندوق الحدود للكيان الحالي في نظام إحداثيات مساحة الكائن الخاصة به. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | يحصل على مفتاح عارض الكيان المسجل في العارض |
| override [GetExtent](../../aspose.threed.profiles/rectangleshape/getextent/)() | يحصل على الامتداد في بعدي x و y. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | احصل على قيمة الخاصية المحددة |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | يزيل خاصية ديناميكية. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | إزالة الخاصية المحددة بالاسم |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | يضبط قيمة الخاصية المحددة |

### انظر أيضًا

* class [ParameterizedProfile](../parameterizedprofile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


