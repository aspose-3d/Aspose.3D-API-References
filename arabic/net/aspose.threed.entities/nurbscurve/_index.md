---
title: "الفئة NurbsCurve"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Entities.NurbsCurve. منحنى NURBS هو منحنى يُمثَّل بـ NURBSNonuniform rational basis spline. يُعرَّف منحنى NURBS بترتيبه ومجموعة من نقاط التحكم ذات الوزن (ControlPoints) ومجموعة من متجهات العقد (KnotVectors). يُستخدم المكوّن w في نقطة التحكم كوزن لنقطة التحكم سواء كان TwoDimensional أو ThreeDimensional."
type: docs
weight: 520
url: /ar/net/aspose.threed.entities/nurbscurve/
---
## NurbsCurve class

[NURBS curve](https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline) is a curve represented by NURBS(Non-uniform rational basis spline), A NURBS curve is defined by its [`Order`](./order/), a set of weighted [`ControlPoints`](../geometry/controlpoints/) and a [`KnotVectors`](./knotvectors/) The w component in control point is used as control point's weight, whatever it is a TwoDimensional or ThreeDimensional

```csharp
public class NurbsCurve : Curve
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [NurbsCurve](nurbscurve/#constructor)() | ينشئ مثيلًا جديدًا من الفئة `NurbsCurve`. |
| [NurbsCurve](nurbscurve/#constructor_1)(string) | ينشئ مثيلًا جديدًا من الفئة `NurbsCurve`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Color](../../aspose.threed.entities/curve/color/) { get; set; } | يحصل أو يضبط لون الخط، القيمة الافتراضية هي أبيض (1, 1, 1) |
| [ControlPoints](../../aspose.threed.entities/nurbscurve/controlpoints/) { get; } | يحصل على جميع نقاط التحكم |
| [CurveType](../../aspose.threed.entities/nurbscurve/curvetype/) { get; set; } | الحصول على أو تعيين نوع المنحنى. |
| [Degree](../../aspose.threed.entities/nurbscurve/degree/) { get; set; } | الحصول على أو تعيين درجة منحنى NURBS، حيث تُعرّف الدرجة بأنها الترتيب - 1. |
| [Dimension](../../aspose.threed.entities/nurbscurve/dimension/) { get; set; } | الحصول على أو تعيين أبعاد المنحنى. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | يحصل أو يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| [KnotVectors](../../aspose.threed.entities/nurbscurve/knotvectors/) { get; } | الحصول على متجه العقد، وهو تسلسل من قيم المعامل التي تحدد أين وكيف تؤثر نقاط التحكم على منحنى NURBS. |
| [Multiplicity](../../aspose.threed.entities/nurbscurve/multiplicity/) { get; } | الحصول على التعددية. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [Order](../../aspose.threed.entities/nurbscurve/order/) { get; set; } | الحصول على أو تعيين ترتيب منحنى NURBS، حيث يحدد عدد نقاط التحكم القريبة التي تؤثر على أي نقطة معينة في المنحنى. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | يحصل أو يعيّن العقدة الأصلية الأولى، إذا تم تعيين العقدة الأصلية الأولى، سيتم فصل هذا الكيان عن العقد الأصلية الأخرى. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | يحصل على جميع العقد الأصلية، يمكن إرفاق كيان بعدة عقد أصلية لتكرار الهندسة. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [Rational](../../aspose.threed.entities/nurbscurve/rational/) { get; set; } | الحصول على أو تعيين ما إذا كان منطقيًا، هذه القيمة تشير إلى ما إذا كان هذا `NurbsCurve` منحنىًا منطقيًا أو غير منطقي. الـ B-spline غير المنطقي هو حالة خاصة من الـ B-splines المنطقية. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | يحصل على المشهد الذي ينتمي إليه هذا الكائن |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Evaluate](../../aspose.threed.entities/nurbscurve/evaluate/)(int) | تقييم منحنى NURBS |
| [EvaluateAt](../../aspose.threed.entities/nurbscurve/evaluateat/)(double) | تقييم نقطة المنحنى في الموضع المحدد |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | يجد الخاصية. يمكن أن تكون خاصية ديناميكية (Created by CreateDynamicProperty/SetProperty) أو خاصية أصلية (Identified by its name) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | يحصل على صندوق الحدود للكيان الحالي في نظام إحداثيات مساحة الكائن الخاصة به. |
| override [GetEntityRendererKey](../../aspose.threed.entities/curve/getentityrendererkey/)() | يحصل على مفتاح عارض الكيان المسجل في العارض |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | احصل على قيمة الخاصية المحددة |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | يزيل خاصية ديناميكية. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | إزالة الخاصية المحددة بالاسم |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | يضبط قيمة الخاصية المحددة |

### انظر أيضًا

* class [Curve](../curve/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


