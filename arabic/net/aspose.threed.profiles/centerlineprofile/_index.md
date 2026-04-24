---
title: الفئة CenterLineProfile
second_title: مرجع API Aspose.3D لـ .NET
description: فئة Aspose.ThreeD.Profiles.CenterLineProfile. ملف تعريف خط مركزي متوافق مع IFC
type: docs
weight: 1690
url: /ar/net/aspose.threed.profiles/centerlineprofile/
---
## CenterLineProfile class

ملف تعريف خط المركز المتوافق مع IFC.

```csharp
public class CenterLineProfile : Profile
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [CenterLineProfile](centerlineprofile/)(Curve, double) | ينشئ `CenterLineProfile` جديدًا باستخدام المنحنى المحدد كخط مركزي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Curve](../../aspose.threed.profiles/centerlineprofile/curve/) { get; set; } | منحنى الخط المركزي للملف الشخصي |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | يحصل أو يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | يحصل أو يضبط العقدة الأب الأولى، إذا تم تعيين العقدة الأب الأولى، سيتم فصل هذا الكيان عن باقي العقد الأبوية. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | يحصل على جميع عقد الأب، يمكن إرفاق كيان بعدة عقد أب لتكرار الهندسة. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [Thickness](../../aspose.threed.profiles/centerlineprofile/thickness/) { get; set; } | السُمك المطبق على طول الخط المركزي |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | يبحث عن الخاصية. يمكن أن تكون خاصية ديناميكية (Created by CreateDynamicProperty/SetProperty) أو خاصية أصلية (Identified by its name) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | يحصل على صندوق الحدود للكيان الحالي في نظام إحداثيات مساحة الكائن الخاصة به. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | يحصل على المفتاح الخاص بعارض الكيان المسجل في العارض. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | احصل على قيمة الخاصية المحددة |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | يزيل خاصية ديناميكية. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | إزالة الخاصية المحددة التي تم التعرف عليها بالاسم. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | يضبط قيمة الخاصية المحددة |

### انظر أيضًا

* class [Profile](../profile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


