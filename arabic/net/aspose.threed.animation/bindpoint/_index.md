---
title: "الفئة BindPoint"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Animation.BindPoint. عادةً ما يتم إنشاء BindPoint على خاصية كائن؛ بعض أنواع الخصائص تحتوي على حقول مكوّنات متعددة مثل حقل Vector3. سيولد BindPoint قناة لكل حقل مكوّن ويتصل بالحقل إلى واحدة أو أكثر من مثيلات تسلسل الإطار الرئيسي عبر القنوات."
type: docs
weight: 50
url: /ar/net/aspose.threed.animation/bindpoint/
---
## BindPoint class

`BindPoint` عادةً ما يتم إنشاؤه على خاصية كائن، بعض أنواع الخصائص تحتوي على حقول مكوّنات متعددة (مثل حقل Vector3)، `BindPoint` سيولد قناة لكل حقل مكوّن ويتصل بالحقل إلى واحدة أو أكثر من مثيلات تسلسل الإطار الرئيسي عبر القنوات.

```csharp
public class BindPoint : A3DObject
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [BindPoint](bindpoint/)(Scene, Property) | يُهيئ نسخة جديدة من الفئة `BindPoint`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ChannelsCount](../../aspose.threed.animation/bindpoint/channelscount/) { get; } | يحصل على العدد الإجمالي لقنوات الخصائص المعرفة في تخطيط منحنى الرسوم المتحركة هذا. |
| [Item](../../aspose.threed.animation/bindpoint/item/) { get; } |  |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [Property](../../aspose.threed.animation/bindpoint/property/) { get; } | يحصل على الخاصية المرتبطة بـ CurveMapping. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddChannel](../../aspose.threed.animation/bindpoint/addchannel/#addchannel)(string, object) | يضيف خاصية القناة المحددة. |
| [AddChannel](../../aspose.threed.animation/bindpoint/addchannel/#addchannel_1)(string, Type, object) | يضيف خاصية القناة المحددة. |
| [AddChannel&lt;T&gt;](../../aspose.threed.animation/bindpoint/addchannel/#addchannel_2)(string, T) |  |
| [BindKeyframeSequence](../../aspose.threed.animation/bindpoint/bindkeyframesequence/)(string, KeyframeSequence) | ربط تسلسل الإطار الرئيسي بالقناة المحددة. |
| [CreateKeyframeSequence](../../aspose.threed.animation/bindpoint/createkeyframesequence/)(string) | ينشئ منحنى جديدًا ويربطه بالقناة الأولى لتخطيط المنحنى. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | يجد الخاصية. يمكن أن تكون خاصية ديناميكية (Created by CreateDynamicProperty/SetProperty) أو خاصية أصلية (Identified by its name) |
| [GetChannel](../../aspose.threed.animation/bindpoint/getchannel/)(string) | يحصل على القناة بالاسم المحدد. |
| [GetKeyframeSequence](../../aspose.threed.animation/bindpoint/getkeyframesequence/)(string) | يحصل على أول تسلسل للإطار الرئيسي في القناة المحددة. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | احصل على قيمة الخاصية المحددة |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | يزيل خاصية ديناميكية. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | إزالة الخاصية المحددة بالاسم |
| [ResetChannels](../../aspose.threed.animation/bindpoint/resetchannels/)() | يفرغ قنوات الخصائص في تخطيط منحنى الرسوم المتحركة هذا. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | يضبط قيمة الخاصية المحددة |
| override [ToString](../../aspose.threed.animation/bindpoint/tostring/)() | يحوّل الكائن إلى سلسلة |

### انظر أيضًا

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* assembly [Aspose.3D](../../)


