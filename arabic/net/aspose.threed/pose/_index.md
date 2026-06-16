---
title: "الفئة Pose"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Pose. تُستخدم الوضعية لتخزين مصفوفة التحويل عندما يتم تكسية الهندسة. الوضعية هي مجموعة من BonePose، كل BonePose يحفظ معلومات التحويل المحددة لعقدة العظم"
type: docs
weight: 1650
url: /ar/net/aspose.threed/pose/
---
## Pose class

تُستخدم الوضعية لتخزين مصفوفة التحويل عندما يتم تكسية الهندسة. الوضعية هي مجموعة من [`BonePose`](../bonepose/)، كل [`BonePose`](../bonepose/) يحفظ معلومات التحويل المحددة لعقدة العظم.

```csharp
public class Pose : A3DObject
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [Pose](pose/#constructor)() | يُنشئ نسخة جديدة من الفئة `Pose`. |
| [Pose](pose/#constructor_1)(string) | يُنشئ نسخة جديدة من الفئة `Pose`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BonePoses](../../aspose.threed/pose/boneposes/) { get; } | يحصل على جميع [`BonePose`](../bonepose/). |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [PoseType](../../aspose.threed/pose/posetype/) { get; set; } | يحصل أو يحدد نوع الوضعية. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddBonePose](../../aspose.threed/pose/addbonepose/#addbonepose)(Node, Matrix4) | يحفظ مصفوفة تحويل الوضعية لعقدة العظم المحددة. يُفترض وجود مصفوفة تحويل عالمية. |
| [AddBonePose](../../aspose.threed/pose/addbonepose/#addbonepose_1)(Node, Matrix4, bool) | يحفظ مصفوفة تحويل الوضعية لعقدة العظم المحددة. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | يجد الخاصية. يمكن أن تكون خاصية ديناميكية (Created by CreateDynamicProperty/SetProperty) أو خاصية أصلية (Identified by its name) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | احصل على قيمة الخاصية المحددة |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | يزيل خاصية ديناميكية. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | إزالة الخاصية المحددة بالاسم |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | يضبط قيمة الخاصية المحددة |

### انظر أيضًا

* class [A3DObject](../a3dobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


