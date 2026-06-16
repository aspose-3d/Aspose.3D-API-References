---
title: "الفئة MorphTargetDeformer"
second_title: "مرجع Aspose.3D for .NET API"
description: "Aspose.ThreeD.Deformers.MorphTargetDeformer class. يوفر MorphTargetDeformer رسومات متحركة لكل رأس. ينظم MorphTargetDeformer جميع الأهداف عبر MorphTargetChannel حيث يمكن لكل قناة تنظيم أهداف متعددة. أحد الاستخدامات الشائعة لمحول الهدف التشكيلي هو تطبيق تعبيرات الوجه على شخصية. يمكن العثور على مزيد من التفاصيل في https//en.wikipedia.org/wiki/Morph_target_animation"
type: docs
weight: 230
url: /ar/net/aspose.threed.deformers/morphtargetdeformer/
---
## MorphTargetDeformer class

يوفر MorphTargetDeformer رسومات متحركة لكل رأس. ينظم MorphTargetDeformer جميع الأهداف عبر [`MorphTargetChannel`](../morphtargetchannel/)، يمكن لكل قناة تنظيم أهداف متعددة. أحد الاستخدامات الشائعة لمحول الهدف التشكيلي هو تطبيق تعبيرات الوجه على شخصية. يمكن العثور على مزيد من التفاصيل في https://en.wikipedia.org/wiki/Morph_target_animation

```csharp
public class MorphTargetDeformer : Deformer
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [MorphTargetDeformer](morphtargetdeformer/#constructor)() | ينشئ مثيلًا جديدًا من الفئة `MorphTargetDeformer`. |
| [MorphTargetDeformer](morphtargetdeformer/#constructor_1)(string) | ينشئ مثيلًا جديدًا من الفئة `MorphTargetDeformer`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Channels](../../aspose.threed.deformers/morphtargetdeformer/channels/) { get; } | يحصل على جميع القنوات الموجودة في هذا المحول |
| [Item](../../aspose.threed.deformers/morphtargetdeformer/item/) { get; set; } |  |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [Owner](../../aspose.threed.deformers/deformer/owner/) { get; } | يحصل على الهندسة التي تملك هذا المشكّل |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | يجد الخاصية. يمكن أن تكون خاصية ديناميكية (Created by CreateDynamicProperty/SetProperty) أو خاصية أصلية (Identified by its name) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | احصل على قيمة الخاصية المحددة |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | يزيل خاصية ديناميكية. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | إزالة الخاصية المحددة بالاسم |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | يضبط قيمة الخاصية المحددة |

### انظر أيضًا

* class [Deformer](../deformer/)
* namespace [Aspose.ThreeD.Deformers](../../aspose.threed.deformers/)
* assembly [Aspose.3D](../../)


