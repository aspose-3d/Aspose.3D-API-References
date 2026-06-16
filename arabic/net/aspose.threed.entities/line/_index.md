---
title: "الفئة Line"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Entities.Line. الخط المتعدد هو مسار يُعرّف بمجموعة من النقاط باستخدام ControlPoints ومتصلة بواسطة Segments، مما يعني أنه يمكن أن يكون أيضاً مجموعة من القطاعات الخطية المتصلة. الخط عادةً ما يكون كائنًا خطيًا، مما يعني أنه لا يمكن استخدامه لتمثيل منحنى؛ لتمثيل منحنى يُستخدم NurbsCurve."
type: docs
weight: 480
url: /ar/net/aspose.threed.entities/line/
---
## Line class

الخط المتعدد هو مسار يُعرّف بمجموعة من النقاط باستخدام [`ControlPoints`](../geometry/controlpoints/)، ومتصلة بواسطة [`Segments`](./segments/)، مما يعني أنه يمكن أن يكون أيضاً مجموعة من القطاعات الخطية المتصلة. الخط عادةً ما يكون كائنًا خطيًا، مما يعني أنه لا يمكن استخدامه لتمثيل منحنى؛ لتمثيل منحنى، يُستخدم [`NurbsCurve`](../nurbscurve/).

```csharp
public class Line : Curve
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [Line](line/#constructor)() | ينشئ مثيلاً جديداً من الفئة `Line`. |
| [Line](line/#constructor_1)(string) | ينشئ مثيلاً جديداً من الفئة `Line`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Color](../../aspose.threed.entities/curve/color/) { get; set; } | يحصل أو يضبط لون الخط، القيمة الافتراضية هي أبيض (1, 1, 1) |
| [ControlPoints](../../aspose.threed.entities/line/controlpoints/) { get; } | يحصل على جميع نقاط التحكم |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | يحصل أو يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | يحصل أو يعيّن العقدة الأصلية الأولى، إذا تم تعيين العقدة الأصلية الأولى، سيتم فصل هذا الكيان عن العقد الأصلية الأخرى. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | يحصل على جميع العقد الأصلية، يمكن إرفاق كيان بعدة عقد أصلية لتكرار الهندسة. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [Segments](../../aspose.threed.entities/line/segments/) { get; } | يحصل على مقاطع الخط |
| [Visible](../../aspose.threed.entities/line/visible/) { get; set; } | يحصل أو يعيّن ما إذا كانت الهندسة مرئية |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromPoints](../../aspose.threed.entities/line/frompoints/)(params Vector3[]) | إنشاء كائن `Line` من مجموعة من النقاط. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | يجد الخاصية. يمكن أن تكون خاصية ديناميكية (Created by CreateDynamicProperty/SetProperty) أو خاصية أصلية (Identified by its name) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | يحصل على صندوق الحدود للكيان الحالي في نظام إحداثيات مساحة الكائن الخاصة به. |
| override [GetEntityRendererKey](../../aspose.threed.entities/curve/getentityrendererkey/)() | يحصل على مفتاح عارض الكيان المسجل في العارض |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | احصل على قيمة الخاصية المحددة |
| [MakeDefaultIndices](../../aspose.threed.entities/line/makedefaultindices/)() | توليد السلسلة 0,1,2,3....[`ControlPoints`](../geometry/controlpoints/).Length-1 إلى [`Segments`](./segments/) بحيث يمكن استخدام ControlPoints كخط واحد |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | يزيل خاصية ديناميكية. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | إزالة الخاصية المحددة بالاسم |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | يضبط قيمة الخاصية المحددة |

### انظر أيضًا

* class [Curve](../curve/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


