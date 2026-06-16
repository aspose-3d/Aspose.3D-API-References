---
title: "الفئة TransformBuilder"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Utilities.TransformBuilder. يُستخدم TransformBuilder لبناء مصفوفة التحويل عبر سلسلة من التحويلات"
type: docs
weight: 2860
url: /ar/net/aspose.threed.utilities/transformbuilder/
---
## TransformBuilder class

يُستخدم `TransformBuilder` لبناء مصفوفة التحويل عبر سلسلة من التحويلات.

```csharp
public class TransformBuilder
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [TransformBuilder](transformbuilder/#constructor)(ComposeOrder) | إنشاء `TransformBuilder` مع مصفوفة تحويل هوية أولية وترتيب تجميع محدد |
| [TransformBuilder](transformbuilder/#constructor_1)(Matrix4, ComposeOrder) | إنشاء `TransformBuilder` مع مصفوفة تحويل أولية وترتيب تجميع محدد |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ComposeOrder](../../aspose.threed.utilities/transformbuilder/composeorder/) { get; set; } | الحصول أو تعيين ترتيب تجميع السلسلة. |
| [Matrix](../../aspose.threed.utilities/transformbuilder/matrix/) { get; set; } | الحصول أو تعيين قيمة المصفوفة الحالية. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Append](../../aspose.threed.utilities/transformbuilder/append/)(Matrix4) | إلحاق مصفوفة التحويل الجديدة إلى سلسلة التحويل. |
| [Compose](../../aspose.threed.utilities/transformbuilder/compose/)(Matrix4) | إلحاق أو إلحاق مسبق للمعامل إلى المصفوفة الداخلية. |
| [Prepend](../../aspose.threed.utilities/transformbuilder/prepend/)(Matrix4) | إلحاق مسبق للمصفوفة التحويلية الجديدة إلى سلسلة التحويل. |
| [Rearrange](../../aspose.threed.utilities/transformbuilder/rearrange/)(Axis, Axis, Axis) | إعادة ترتيب تخطيط المحور. |
| [Reset](../../aspose.threed.utilities/transformbuilder/reset/)() | إعادة تعيين التحويل إلى مصفوفة الهوية |
| [Rotate](../../aspose.threed.utilities/transformbuilder/rotate/)(Quaternion) | سلسلة دوران باستخدام رباعية |
| [RotateDegree](../../aspose.threed.utilities/transformbuilder/rotatedegree/#rotatedegree)(double, Vector3) | سلسلة تحويل دوران بالدرجات |
| [RotateDegree](../../aspose.threed.utilities/transformbuilder/rotatedegree/#rotatedegree_1)(Vector3, RotationOrder) | إلحاق دوران بترتيب محدد |
| [RotateEulerDegree](../../aspose.threed.utilities/transformbuilder/rotateeulerdegree/)(double, double, double) | سلسلة دوران باستخدام زوايا أويلر بالدرجات |
| [RotateEulerRadian](../../aspose.threed.utilities/transformbuilder/rotateeulerradian/#rotateeulerradian)(Vector3) | سلسلة دوران باستخدام زوايا أويلر بالراديان |
| [RotateEulerRadian](../../aspose.threed.utilities/transformbuilder/rotateeulerradian/#rotateeulerradian_1)(double, double, double) | سلسلة دوران باستخدام زوايا أويلر بالراديان |
| [RotateRadian](../../aspose.threed.utilities/transformbuilder/rotateradian/#rotateradian)(double, Vector3) | سلسلة تحويل دوران بالراديان |
| [RotateRadian](../../aspose.threed.utilities/transformbuilder/rotateradian/#rotateradian_1)(Vector3, RotationOrder) | إلحاق دوران بترتيب محدد |
| [Scale](../../aspose.threed.utilities/transformbuilder/scale/#scale_1)(double) | سلسلة مصفوفة تحويل قياس مع مكوّن مُقاس بـ s |
| [Scale](../../aspose.threed.utilities/transformbuilder/scale/#scale)(Vector3) | سلسلة تحويل قياس |
| [Scale](../../aspose.threed.utilities/transformbuilder/scale/#scale_2)(double, double, double) | سلسلة مصفوفة تحويل قياس |
| [Translate](../../aspose.threed.utilities/transformbuilder/translate/#translate)(Vector3) | سلسلة تحويل إزاحة |
| [Translate](../../aspose.threed.utilities/transformbuilder/translate/#translate_1)(double, double, double) | سلسلة تحويل إزاحة |

## أمثلة

الكود التالي يوضح كيفية إنشاء مصفوفة باستخدام مجموعة من العمليات

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Translate(10, 20, 0);
tb.Scale(10, 10, 10);
tb.RotateEulerDegree(90, 0, 0);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### انظر أيضًا

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


