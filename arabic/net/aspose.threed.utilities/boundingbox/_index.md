---
title: "هيكل BoundingBox"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "هيكل Aspose.ThreeD.Utilities.BoundingBox. صندوق الحدود المحاذى للمحاور."
type: docs
weight: 2670
url: /ar/net/aspose.threed.utilities/boundingbox/
---
## BoundingBox structure

الصندوق المحيط المحاذى للمحاور

```csharp
public struct BoundingBox
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [BoundingBox](boundingbox/#constructor)(Vector3, Vector3) | تهيئة صندوق حدود محدود مع الزاوية الدنيا والزاوية العليا المحددة. |
| [BoundingBox](boundingbox/#constructor_1)(double, double, double, double, double, double) | تهيئة صندوق حدود محدود مع الزاوية الدنيا والزاوية العليا المحددة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [Infinite](../../aspose.threed.utilities/boundingbox/infinite/) { get; } | صندوق الحدود اللانهائي. |
| static [Null](../../aspose.threed.utilities/boundingbox/null/) { get; } | صندوق الحدود الفارغ. |
| [Center](../../aspose.threed.utilities/boundingbox/center/) { get; } | مركز صندوق الحدود. |
| [Extent](../../aspose.threed.utilities/boundingbox/extent/) { get; } | يحصل على مدى صندوق الحدود. |
| [Maximum](../../aspose.threed.utilities/boundingbox/maximum/) { get; } | الزاوية العليا لصندوق الحدود. |
| [Minimum](../../aspose.threed.utilities/boundingbox/minimum/) { get; } | الزاوية الدنيا لصندوق الحدود. |
| [Size](../../aspose.threed.utilities/boundingbox/size/) { get; } | حجم صندوق الحدود. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromGeometry](../../aspose.threed.utilities/boundingbox/fromgeometry/)(Geometry) | إنشاء صندوق حدود من الهندسة المعطاة. |
| [Contains](../../aspose.threed.utilities/boundingbox/contains/#contains)(BoundingBox) | صندوق الحدود للتحقق مما إذا كان داخل صندوق الحدود الحالي. |
| [Contains](../../aspose.threed.utilities/boundingbox/contains/#contains_1)(Vector3) | تحقق مما إذا كانت النقطة p داخل صندوق الحدود. |
| override [Equals](../../aspose.threed.utilities/boundingbox/equals/)(object) | يحدد ما إذا كان الكائنان متساويين. |
| override [GetHashCode](../../aspose.threed.utilities/boundingbox/gethashcode/)() | يعيد رمز التجزئة لهذا الكائن. |
| [Merge](../../aspose.threed.utilities/boundingbox/merge/#merge)(BoundingBox) | يدمج الصندوق الجديد في صندوق الحدود الحالي. |
| [Merge](../../aspose.threed.utilities/boundingbox/merge/#merge_1)(Vector3) | دمج صندوق الحدود الحالي مع النقطة المحددة. |
| [Merge](../../aspose.threed.utilities/boundingbox/merge/#merge_2)(Vector4) | دمج صندوق الحدود الحالي مع النقطة المحددة. |
| [Merge](../../aspose.threed.utilities/boundingbox/merge/#merge_3)(double, double, double) | دمج صندوق الحدود الحالي مع النقطة المحددة. |
| [OverlapsWith](../../aspose.threed.utilities/boundingbox/overlapswith/)(BoundingBox) | تحقق مما إذا كان صندوق الحدود الحالي يتداخل مع صندوق الحدود المحدد. |
| [Scale](../../aspose.threed.utilities/boundingbox/scale/)() | يحسب القيمة المطلقة لأكبر إحداثي لأي نقطة محتواة. |
| override [ToString](../../aspose.threed.utilities/boundingbox/tostring/)() | يحصل على تمثيل النص لصندوق الحدود. |
| [operator *](../../aspose.threed.utilities/boundingbox/op_multiply/) | تحميل المشغل للضرب، سيتم تحويل الزاوية الدنيا والزاوية العليا لصندوق الحدود الجديد بواسطة المصفوفة. |

## أمثلة

يظهر الكود التالي كيفية الحصول على صندوق احتواء من كائن Entity.

```csharp
var sphere = new Sphere();
var boundingBox = sphere.GetBoundingBox();
Console.WriteLine("Bounding box = " + boundingBox);
```

### انظر أيضًا

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


