---
title: "الفئة MorphTargetChannel"
second_title: "مرجع Aspose.3D for .NET API"
description: "Aspose.ThreeD.Deformers.MorphTargetChannel class. يُستخدم MorphTargetChannel بواسطة MorphTargetDeformer لتنظيم الهندسات الهدف. بعض صيغ الملفات مثل FBX تدعم قنوات متعددة بالتوازي."
type: docs
weight: 220
url: /ar/net/aspose.threed.deformers/morphtargetchannel/
---
## MorphTargetChannel class

يُستخدم MorphTargetChannel بواسطة [`MorphTargetDeformer`](../morphtargetdeformer/) لتنظيم الهندسات الهدف. بعض صيغ الملفات مثل FBX تدعم قنوات متعددة بالتوازي.

```csharp
public class MorphTargetChannel : A3DObject
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [MorphTargetChannel](morphtargetchannel/#constructor)() | يُنشئ مثيلاً جديداً من الفئة `MorphTargetChannel`. |
| [MorphTargetChannel](morphtargetchannel/#constructor_1)(string) | يُنشئ مثيلاً جديداً من الفئة `MorphTargetChannel`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ChannelWeight](../../aspose.threed.deformers/morphtargetchannel/channelweight/) { get; set; } | يحصل أو يضبط وزن المشكّل لهذه القناة. الوزن يتراوح بين 0.0 و 1.0. |
| [Item](../../aspose.threed.deformers/morphtargetchannel/item/) { get; set; } |  |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [Targets](../../aspose.threed.deformers/morphtargetchannel/targets/) { get; } | يحصل على جميع الأهداف المرتبطة بالقناة. |
| [Weights](../../aspose.threed.deformers/morphtargetchannel/weights/) { get; } | يحصل على قيم الوزن الكاملة للهندسات الهدف. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | يجد الخاصية. يمكن أن تكون خاصية ديناميكية (Created by CreateDynamicProperty/SetProperty) أو خاصية أصلية (Identified by its name) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | احصل على قيمة الخاصية المحددة |
| [GetWeight](../../aspose.threed.deformers/morphtargetchannel/getweight/)(Shape) | يحصل على الوزن للهدف المحدد، إذا لم يكن الهدف تابعاً لهذه القناة، يتم إرجاع القيمة الافتراضية 0. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | يزيل خاصية ديناميكية. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | إزالة الخاصية المحددة بالاسم |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | يضبط قيمة الخاصية المحددة |
| [SetWeight](../../aspose.threed.deformers/morphtargetchannel/setweight/)(Shape, double) | يضبط الوزن للهدف المحدد، القيمة الافتراضية هي 1، يجب أن يكون النطاق بين 0~1. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [DefaultWeight](../../aspose.threed.deformers/morphtargetchannel/defaultweight/) | الوزن الافتراضي للهدف التشكيلي. |

## ملاحظات

الوزن بين 0 و 1.0، والوزن الافتراضي للهدف هو 0.0؛

### انظر أيضًا

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Deformers](../../aspose.threed.deformers/)
* assembly [Aspose.3D](../../)


