---
title: "الفئة KeyFrame"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Animation.KeyFrame. يتم تعريف إطار المفتاح أساسًا بواسطة الوقت والقيمة لبعض أنواع الاستيفاء، كما يتم استخدام المماس/الشد/التحيز/الاستمرارية عند حساب القيمة العينية النهائية. القيم العينية في موضع زمني غير إطار مفتاح يتم استيفاؤها بواسطة إطارات المفاتيح بين الإطار السابق واللاحق. القيم قبل/بعد الإطار الأول/الأخير يتم حسابها بواسطة فئة Extrapolation."
type: docs
weight: 90
url: /ar/net/aspose.threed.animation/keyframe/
---
## KeyFrame class

يتم تعريف إطار المفتاح أساسًا بواسطة الوقت والقيمة، لبعض أنواع الاستيفاء يتم أيضًا استخدام المماس/الشد/التحيز/الاستمرارية عند حساب القيمة العينية النهائية. القيم العينية في موضع زمني غير إطار-مفتاح يتم استيفاؤها بواسطة إطارات-المفاتيح بين الإطار السابق واللاحق. القيم قبل/بعد الإطار الأول/الأخير يتم حسابها بواسطة الفئة [`Extrapolation`](../extrapolation/).

```csharp
public class KeyFrame
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [KeyFrame](keyframe/)(KeyframeSequence, double) | إنشاء إطار مفتاح جديد على المنحنى المحدد |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Bias](../../aspose.threed.animation/keyframe/bias/) { get; set; } | يحصل أو يضبط الانحياز المستخدم في منحنى TCB |
| [Continuity](../../aspose.threed.animation/keyframe/continuity/) { get; set; } | يحصل أو يضبط الاستمرارية المستخدمة في منحنى TCB |
| [Flat](../../aspose.threed.animation/keyframe/flat/) { get; set; } | احصل أو اضبط ما إذا كان إطار المفتاح مسطحًا. يجب أن يكون إطار المفتاح مسطحًا إذا كان الإطار التالي أو السابق له نفس القيمة. إطار المفتاح المسطح له مماس مسطح واستيفاء ثابت. |
| [IndependentTangent](../../aspose.threed.animation/keyframe/independenttangent/) { get; set; } | يحصل أو يضبط أن المماس الخارج والمماس الداخل التالي مستقلان. |
| [Interpolation](../../aspose.threed.animation/keyframe/interpolation/) { get; set; } | يحصل أو يضبط نوع استيفاء المفتاح، list.data[index] يحدد الخوارزمية التي تُحسب بها القيمة العينية. |
| [NextInTangent](../../aspose.threed.animation/keyframe/nextintangent/) { get; set; } | يحصل أو يضبط المماس الداخل (اليسار) التالي على هذا الإطار المفتاح. |
| [NextInWeight](../../aspose.threed.animation/keyframe/nextinweight/) { get; set; } | يحصل أو يضبط الوزن الداخل (اليسار) التالي على هذا الإطار المفتاح. |
| [OutTangent](../../aspose.threed.animation/keyframe/outtangent/) { get; set; } | يحصل أو يضبط المماس الخارج (اليمين) على هذا الإطار المفتاح. |
| [OutWeight](../../aspose.threed.animation/keyframe/outweight/) { get; set; } | يحصل أو يضبط الوزن الخارج (اليمين) على هذا الإطار المفتاح. |
| [StepMode](../../aspose.threed.animation/keyframe/stepmode/) { get; set; } | يحصل أو يضبط وضع خطوة المفتاح. إذا كان نوع الاستيفاء ثابتًا، فإن list.data[index] يحدد أي قيمة لإطار المفتاح ستُستخدم أثناء الاستيفاء. قيمة PreviousValue تعني استخدام قيمة إطار المفتاح الأيسر، وقيمة NextValue تعني استخدام قيمة إطار المفتاح الأيمن التالي. |
| [TangentWeightMode](../../aspose.threed.animation/keyframe/tangentweightmode/) { get; set; } | يحصل أو يضبط وضع وزن المماس للمفتاح. يمكن تخصيص المماس الخارج أو المماس الداخل التالي عن طريق اختيار [`WeightedMode`](../weightedmode/) الصحيح. |
| [Tension](../../aspose.threed.animation/keyframe/tension/) { get; set; } | يحصل أو يضبط التوتر المستخدم في منحنى TCB. |
| [Time](../../aspose.threed.animation/keyframe/time/) { get; set; } | يحصل أو يضبط موضع الوقت لإطار المفتاح list.data[index]، مقاسًا بالثواني. |
| [TimeIndependentTangent](../../aspose.threed.animation/keyframe/timeindependenttangent/) { get; set; } | يحصل أو يضبط أن المماس غير معتمد على الزمن. |
| [Value](../../aspose.threed.animation/keyframe/value/) { get; set; } | يحصل أو يضبط قيمة إطار المفتاح. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [ToString](../../aspose.threed.animation/keyframe/tostring/)() | يحصل على التمثيل النصي لإطار المفتاح. |

### انظر أيضًا

* namespace [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* assembly [Aspose.3D](../../)


