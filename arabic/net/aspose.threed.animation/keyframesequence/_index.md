---
title: "الفئة KeyframeSequence"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Animation.KeyframeSequence. تسلسل الإطارات المفتاحية يصف تحويل قيمة مُعينة على مر الزمن"
type: docs
weight: 100
url: /ar/net/aspose.threed.animation/keyframesequence/
---
## KeyframeSequence class

تسلسل الإطارات المفتاحية، يصف تحويل القيمة المعيّنة مع مرور الوقت.

```csharp
public class KeyframeSequence : A3DObject, IEnumerable<KeyFrame>
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [KeyframeSequence](keyframesequence/#constructor)() | تهيئ نسخة جديدة من الفئة `KeyframeSequence`. |
| [KeyframeSequence](keyframesequence/#constructor_1)(string) | تهيئ نسخة جديدة من الفئة `KeyframeSequence`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BindPoint](../../aspose.threed.animation/keyframesequence/bindpoint/) { get; } | يحصل على نقطة ربط الخاصية التي تملك هذا المنحنى |
| [KeyFrames](../../aspose.threed.animation/keyframesequence/keyframes/) { get; } | يحصل على الإطارات المفتاحية لهذا المنحنى. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [PostBehavior](../../aspose.threed.animation/keyframesequence/postbehavior/) { get; } | يحصل على سلوك ما بعد الذي يحدد ما يجب أن تكون عليه القيمة المُعينة بعد الإطار المفتاحي الأخير. |
| [PreBehavior](../../aspose.threed.animation/keyframesequence/prebehavior/) { get; } | يحصل على سلوك ما قبل الذي يحدد ما يجب أن تكون عليه القيمة المُعينة قبل الإطار المفتاحي الأول. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Add](../../aspose.threed.animation/keyframesequence/add/#add)(double, float) | إنشاء إطار مفتاح جديد بالقيمة المحددة |
| [Add](../../aspose.threed.animation/keyframesequence/add/#add_1)(double, float, Interpolation) | إنشاء إطار مفتاح جديد بالقيمة المحددة |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | يجد الخاصية. يمكن أن تكون خاصية ديناميكية (Created by CreateDynamicProperty/SetProperty) أو خاصية أصلية (Identified by its name) |
| [GetEnumerator](../../aspose.threed.animation/keyframesequence/getenumerator/)() | يحصل على المُعدِّ لتجوال جميع إطارات المفاتيح. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | احصل على قيمة الخاصية المحددة |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | يزيل خاصية ديناميكية. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | إزالة الخاصية المحددة بالاسم |
| [Reset](../../aspose.threed.animation/keyframesequence/reset/)() | يزيل جميع إطارات المفاتيح ويعيد ضبط سلوكيات ما بعد/ما قبل. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | يضبط قيمة الخاصية المحددة |

### انظر أيضًا

* class [A3DObject](../../aspose.threed/a3dobject/)
* class [KeyFrame](../keyframe/)
* namespace [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* assembly [Aspose.3D](../../)


