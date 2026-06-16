---
title: "فئة AnimationChannel"
second_title: "مرجع Aspose.3D for .NET API"
description: "فئة Aspose.ThreeD.Animation.AnimationChannel. القناة تُطابق حقل مكوّن الخاصية إلى مجموعة من تسلسلات الإطارات المفتاحية"
type: docs
weight: 20
url: /ar/net/aspose.threed.animation/animationchannel/
---
## AnimationChannel class

قناة تقوم بربط حقل مكوّن الخاصية بمجموعة من سلاسل إطارات المفتاح

```csharp
public class AnimationChannel : KeyframeSequence
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BindPoint](../../aspose.threed.animation/keyframesequence/bindpoint/) { get; } | يحصل على نقطة ربط الخاصية التي تملك هذا المنحنى |
| [ComponentType](../../aspose.threed.animation/animationchannel/componenttype/) { get; } | يحصل على نوع حقل المكوّن |
| [DefaultValue](../../aspose.threed.animation/animationchannel/defaultvalue/) { get; set; } | يحصل أو يعيّن القيمة الافتراضية للقناة. إذا لم يكن للقناة أي تسلسلات إطارات مفتاحية متصلة، سيتم استخدام القيمة الافتراضية أثناء تقييم الرسوم المتحركة. سيناريو واقعي: الرسوم المتحركة تحرك فقط إحداثي x للعقدة، بينما لا يتغير y و z، وبالتالي تُستخدم القيمة الافتراضية أثناء تقييم الترجمة الكاملة. |
| [KeyFrames](../../aspose.threed.animation/keyframesequence/keyframes/) { get; } | يحصل على الإطارات المفتاحية لهذا المنحنى. |
| [KeyframeSequence](../../aspose.threed.animation/animationchannel/keyframesequence/) { get; set; } | يحصل على تسلسل الإطار المفتاح المرتبط داخل هذه القناة |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [PostBehavior](../../aspose.threed.animation/keyframesequence/postbehavior/) { get; } | يحصل على سلوك ما بعد الذي يحدد ما يجب أن تكون عليه القيمة المُعينة بعد الإطار المفتاحي الأخير. |
| [PreBehavior](../../aspose.threed.animation/keyframesequence/prebehavior/) { get; } | يحصل على سلوك ما قبل الذي يحدد ما يجب أن تكون عليه القيمة المُعينة قبل الإطار المفتاحي الأول. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Add](../../aspose.threed.animation/keyframesequence/add/)(double, float) | إنشاء إطار مفتاح جديد بالقيمة المحددة |
| [Add](../../aspose.threed.animation/keyframesequence/add/)(double, float, Interpolation) | إنشاء إطار مفتاح جديد بالقيمة المحددة |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | يجد الخاصية. يمكن أن تكون خاصية ديناميكية (Created by CreateDynamicProperty/SetProperty) أو خاصية أصلية (Identified by its name) |
| [GetEnumerator](../../aspose.threed.animation/keyframesequence/getenumerator/)() | يحصل على المُعدِّ لتجوال جميع إطارات المفاتيح. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | احصل على قيمة الخاصية المحددة |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | يزيل خاصية ديناميكية. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | إزالة الخاصية المحددة بالاسم |
| [Reset](../../aspose.threed.animation/keyframesequence/reset/)() | يزيل جميع إطارات المفاتيح ويعيد ضبط سلوكيات ما بعد/ما قبل. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | يضبط قيمة الخاصية المحددة |

### انظر أيضًا

* class [KeyframeSequence](../keyframesequence/)
* namespace [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* assembly [Aspose.3D](../../)


