---
title: "الفئة Bone"
second_title: "مرجع Aspose.3D for .NET API"
description: "Aspose.ThreeD.Deformers.Bone class. يحدد العظم مجموعة نقاط التحكم في الهندسة ويحدد وزن الخلط لكل نقطة تحكم. لا يمكن استخدام كائن Bone مباشرةً؛ يتم استخدام مثيل SkinDeformer لتشويه الهندسة ويأتي SkinDeformer مع مجموعة من العظام، كل عظم مرتبط بعقدة. ملاحظة: يمكن ربط نقطة تحكم في الهندسة بأكثر من عظم واحد"
type: docs
weight: 190
url: /ar/net/aspose.threed.deformers/bone/
---
## Bone class

يحدد العظم مجموعة نقاط التحكم في الهندسة، ويحدد وزن الخلط لكل نقطة تحكم. لا يمكن استخدام كائن `Bone` مباشرةً، يتم استخدام مثيل [`SkinDeformer`](../skindeformer/) لتشويه الهندسة، ويأتي [`SkinDeformer`](../skindeformer/) مع مجموعة من العظام، كل عظم مرتبط بعقدة. ملاحظة: يمكن ربط نقطة تحكم في الهندسة بأكثر من عظم واحد.

```csharp
public class Bone : A3DObject
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [Bone](bone/#constructor)() | يُنشئ مثيلاً جديداً من الفئة `Bone`. |
| [Bone](bone/#constructor_1)(string) | يُنشئ مثيلاً جديداً من الفئة `Bone`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BoneTransform](../../aspose.threed.deformers/bone/bonetransform/) { get; set; } | يحصل أو يضبط مصفوفة التحويل للعظم. |
| [Item](../../aspose.threed.deformers/bone/item/) { get; set; } |  |
| [LinkMode](../../aspose.threed.deformers/bone/linkmode/) { get; set; } | تشير وضعية ربط العظام إلى الطريقة التي يتم بها ربط العظام بعظامها الأصلية داخل هيكل هرمي. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [Node](../../aspose.threed.deformers/bone/node/) { get; set; } | يحصل أو يضبط العقدة. عقدة العظم هي العظم الذي يلتصق به الجلد، سيستخدم [`SkinDeformer`](../skindeformer/) عقدة العظم لتأثير إزاحة نقاط التحكم. عادةً ما تكون عقدة العظم مرتبطة بـ [`Skeleton`](../../aspose.threed.entities/skeleton/)، لكن ذلك ليس مطلوباً. يُستخدم الـ [`Skeleton`](../../aspose.threed.entities/skeleton/) المرفق عادةً بواسطة برامج DCC لعرض الهيكل العظمي للمستخدم. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [Transform](../../aspose.threed.deformers/bone/transform/) { get; set; } | يحصل أو يضبط مصفوفة التحويل للعقدة التي تحتوي على العظم. |
| [WeightCount](../../aspose.threed.deformers/bone/weightcount/) { get; } | يحصل على عدد الأوزان، يتم توسيعه تلقائياً بواسطة [`SetWeight`](./setweight/). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | يجد الخاصية. يمكن أن تكون خاصية ديناميكية (Created by CreateDynamicProperty/SetProperty) أو خاصية أصلية (Identified by its name) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | احصل على قيمة الخاصية المحددة |
| [GetWeight](../../aspose.threed.deformers/bone/getweight/)(int) | يحصل على الوزن لنقطة التحكم المحددة بالفهرس. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | يزيل خاصية ديناميكية. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | إزالة الخاصية المحددة بالاسم |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | يضبط قيمة الخاصية المحددة |
| [SetWeight](../../aspose.threed.deformers/bone/setweight/)(int, double) | يضبط الوزن لنقطة التحكم المحددة بالفهرس. |

### انظر أيضًا

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Deformers](../../aspose.threed.deformers/)
* assembly [Aspose.3D](../../)


