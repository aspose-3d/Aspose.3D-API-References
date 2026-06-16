---
title: "Struct BoundingBox"
second_title: "مرجع Aspose.3D for .NET API"
description: "هيكل Aspose.ThreeD.Utilities.BoundingBox. صندوق الحدود المحاذى للمحاور"
type: docs
weight: 2670
url: /ar/net/aspose.threed.utilities/boundingbox/
---
## BoundingBox structure

صندوق الحدود المحاذي للمحاور

```csharp
public struct BoundingBox
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [BoundingBox](boundingbox/#constructor)(Vector3, Vector3) | تهيئة صندوق إحاطة محدود مع الزاوية الدنيا والزاوية العليا المحددتين |
| [BoundingBox](boundingbox/#constructor_1)(double, double, double, double, double, double) | تهيئة صندوق إحاطة محدود مع الزاوية الدنيا والزاوية العليا المحددتين |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [Infinite](../../aspose.threed.utilities/boundingbox/infinite/) { get; } | صندوق الإحاطة اللانهائي |
| static [Null](../../aspose.threed.utilities/boundingbox/null/) { get; } | صندوق الإحاطة الفارغ |
| [Center](../../aspose.threed.utilities/boundingbox/center/) { get; } | مركز صندوق الحدود. |
| [Extent](../../aspose.threed.utilities/boundingbox/extent/) { get; } | يحصل على مدى صندوق الإحاطة. |
| [Maximum](../../aspose.threed.utilities/boundingbox/maximum/) { get; } | الزاوية القصوى لصندوق الإحاطة |
| [Minimum](../../aspose.threed.utilities/boundingbox/minimum/) { get; } | الزاوية الدنيا لصندوق الإحاطة |
| [Size](../../aspose.threed.utilities/boundingbox/size/) { get; } | حجم صندوق الحدود |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromGeometry](../../aspose.threed.utilities/boundingbox/fromgeometry/)(Geometry) | إنشاء صندوق حدود من الهندسة المعطاة |
| [Contains](../../aspose.threed.utilities/boundingbox/contains/#contains)(BoundingBox) | صندوق الحدود للتحقق مما إذا كان داخل صندوق الحدود الحالي. |
| [Contains](../../aspose.threed.utilities/boundingbox/contains/#contains_1)(Vector3) | تحقق مما إذا كانت النقطة p داخل صندوق الحدود |
| override [Equals](../../aspose.threed.utilities/boundingbox/equals/)(object) | يحدد ما إذا كان الكائنان متساويين |
| override [GetHashCode](../../aspose.threed.utilities/boundingbox/gethashcode/)() | يعيد قيمة التجزئة لهذا الكائن |
| [Merge](../../aspose.threed.utilities/boundingbox/merge/#merge)(BoundingBox) | يدمج الصندوق الجديد في صندوق الإحاطة الحالي. |
| [Merge](../../aspose.threed.utilities/boundingbox/merge/#merge_1)(Vector3) | دمج صندوق الحدود الحالي مع النقطة المعطاة |
| [Merge](../../aspose.threed.utilities/boundingbox/merge/#merge_2)(Vector4) | دمج صندوق الحدود الحالي مع النقطة المعطاة |
| [Merge](../../aspose.threed.utilities/boundingbox/merge/#merge_3)(double, double, double) | دمج صندوق الحدود الحالي مع النقطة المعطاة |
| [OverlapsWith](../../aspose.threed.utilities/boundingbox/overlapswith/)(BoundingBox) | تحقق مما إذا كان صندوق الحدود الحالي يتقاطع مع صندوق الحدود المحدد. |
| [Scale](../../aspose.threed.utilities/boundingbox/scale/)() | يحسب القيمة المطلقة لأكبر إحداثي لأي نقطة محتواة. |
| override [ToString](../../aspose.threed.utilities/boundingbox/tostring/)() | يحصل على تمثيل النص لصندوق الإحاطة. |
| [operator *](../../aspose.threed.utilities/boundingbox/op_multiply/) | تجاوز المشغل للضرب، سيتم تحويل الزاويتين الدنيا والعليا لصندوق الحدود الجديد بواسطة المصفوفة. |

## أمثلة

الكود التالي يوضح كيفية الحصول على صندوق حدود من كائن Entity.

```csharp
var sphere = new Sphere();
var boundingBox = sphere.GetBoundingBox();
Console.WriteLine("Bounding box = " + boundingBox);
```

### انظر أيضًا

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


