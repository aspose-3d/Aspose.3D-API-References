---
title: "هيكل Quaternion"
second_title: "مرجع Aspose.3D for .NET API"
description: "هيكل Aspose.ThreeD.Utilities.Quaternion. عادةً ما يُستخدم Quaternion لإجراء التدوير في الرسوميات الحاسوبية"
type: docs
weight: 2810
url: /ar/net/aspose.threed.utilities/quaternion/
---
## Quaternion structure

عادةً ما يُستخدم الكواترن لتطبيق الدوران في الرسومات الحاسوبية.

```csharp
public struct Quaternion
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [Quaternion](quaternion/)(double, double, double, double) | يقوم بتهيئة نسخة جديدة من الفئة `Quaternion`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Length](../../aspose.threed.utilities/quaternion/length/) { get; } | يحصل على طول الـ Quaternion |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromAngleAxis](../../aspose.threed.utilities/quaternion/fromangleaxis/)(double, Vector3) | ينشئ Quaternion حول المحور المحدد ويدور في اتجاه عقارب الساعة |
| static [FromEulerAngle](../../aspose.threed.utilities/quaternion/fromeulerangle/#fromeulerangle)(Vector3) | ينشئ Quaternion من زاوية إيلر المحددة |
| static [FromEulerAngle](../../aspose.threed.utilities/quaternion/fromeulerangle/#fromeulerangle_1)(double, double, double) | ينشئ Quaternion من زاوية إيلر المحددة |
| static [FromRotation](../../aspose.threed.utilities/quaternion/fromrotation/)(Vector3, Vector3) | ينشئ كواتيرنيون يدور من الاتجاه الأصلي إلى الاتجاه الوجهة |
| static [Interpolate](../../aspose.threed.utilities/quaternion/interpolate/)(float, Quaternion, Quaternion) | يملئ هذا الكواتيرنيون بالقيمة المتوسطة بين معاملات الكواتيرنيون المعطاة عندما يكون t بين القيم من وإلى |
| static [Slerp](../../aspose.threed.utilities/quaternion/slerp/)(double, Quaternion, Quaternion) | أجرِ استيفاءً خطيًا كرويًا بين قيمتين |
| [Concat](../../aspose.threed.utilities/quaternion/concat/)(Quaternion) | ادمج كواتيرنيونين |
| [Conjugate](../../aspose.threed.utilities/quaternion/conjugate/)() | يرجع كواتيرنيون مرافق للكواتيرنيون الحالي |
| [Dot](../../aspose.threed.utilities/quaternion/dot/)(Quaternion) | ناتج الضرب النقطي |
| override [Equals](../../aspose.threed.utilities/quaternion/equals/)(object) | تحقق مما إذا كان كواتيرنيونان متساويان |
| [EulerAngles](../../aspose.threed.utilities/quaternion/eulerangles/)() | يحول الكواتيرنيون إلى دوران ممثل بزايا أويلر. جميع المكونات بالراديان |
| override [GetHashCode](../../aspose.threed.utilities/quaternion/gethashcode/)() | يحصل على قيمة التجزئة للكواتيرنيون |
| [Inverse](../../aspose.threed.utilities/quaternion/inverse/)() | يرجع كواتيرنيون معكوس للكواتيرنيون الحالي |
| [Normalize](../../aspose.threed.utilities/quaternion/normalize/)() | قم بتطبيع الكواتيرنيون |
| [ToAngleAxis](../../aspose.threed.utilities/quaternion/toangleaxis/)(out double, out Vector3) |  |
| [ToMatrix](../../aspose.threed.utilities/quaternion/tomatrix/#tomatrix)() | حوّل الدوران الممثل بالكواتيرنيون إلى مصفوفة تحويل. |
| [ToMatrix](../../aspose.threed.utilities/quaternion/tomatrix/#tomatrix_1)(Vector3) | حوّل الدوران الممثل بالكواتيرنيون إلى مصفوفة تحويل. |
| override [ToString](../../aspose.threed.utilities/quaternion/tostring/)() | يحصل على تمثيل الكواتيرنيون كسلسلة نصية |
| [operator +](../../aspose.threed.utilities/quaternion/op_addition/) | إعادة تحميل العامل للـ + |
| [operator /](../../aspose.threed.utilities/quaternion/op_division/) | إعادة تعريف العامل / |
| [operator ==](../../aspose.threed.utilities/quaternion/op_equality/) | عامل المساواة للكواتيرنيون |
| [operator !=](../../aspose.threed.utilities/quaternion/op_inequality/) | عامل عدم المساواة للكواتيرنيون |
| [operator *](../../aspose.threed.utilities/quaternion/op_multiply/#op_multiply_1) | إعادة تعريف العامل * (5 عوامل) |

## الحقول

| الاسم | الوصف |
| --- | --- |
| static readonly [Identity](../../aspose.threed.utilities/quaternion/identity/) | كواتيرنيون الهوية. |
| [W](../../aspose.threed.utilities/quaternion/w/) | المكوّن w. |
| [X](../../aspose.threed.utilities/quaternion/x/) | المكوّن x. |
| [Y](../../aspose.threed.utilities/quaternion/y/) | المكوّن y. |
| [Z](../../aspose.threed.utilities/quaternion/z/) | المكوّن z. |

### انظر أيضًا

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


