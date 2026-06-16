---
title: "الفئة NurbsDirection"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Entities.NurbsDirection. تمثل سطح NurbsSurface ثلاثي الأبعاد اتجاهين U و V، وتحدد NurbsDirection البيانات لكل اتجاه. الاتجاه هو في الواقع منحنى NURBS يعني أنه أيضاً يُحدد بترتيبه Order، وسلاسل العقد KnotVectors، ومجموعة من نقاط التحكم المرجحة المعرفة في NurbsSurface"
type: docs
weight: 530
url: /ar/net/aspose.threed.entities/nurbsdirection/
---
## NurbsDirection class

سطح ثلاثي الأبعاد [`NurbsSurface`](../nurbssurface/) له اتجاهان، الـ[`U`](../nurbssurface/u/) وال[`V`](../nurbssurface/v/)، الـ`NurbsDirection` يحدد البيانات لكل اتجاه. الاتجاه هو في الواقع منحنى NURBS، وهذا يعني أنه أيضاً يُحدد بـ[`Order`](./order/)، و[`KnotVectors`](./knotvectors/)، ومجموعة من نقاط التحكم المرجحة (المعرفة في [`NurbsSurface`](../nurbssurface/)).

```csharp
public class NurbsDirection
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [NurbsDirection](nurbsdirection/)() | أنشئ مثيلاً جديداً لـ `NurbsDirection` |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Count](../../aspose.threed.entities/nurbsdirection/count/) { get; set; } | يحصل أو يعيّن عدد نقاط التحكم في الاتجاه الحالي. |
| [Degree](../../aspose.threed.entities/nurbsdirection/degree/) { get; set; } | الحصول على أو تعيين درجة منحنى NURBS، حيث تُعرّف الدرجة بأنها الترتيب - 1. |
| [Divisions](../../aspose.threed.entities/nurbsdirection/divisions/) { get; set; } | يحصل أو يعيّن عدد الأقسام بين نقاط التحكم المتجاورة في الاتجاه الحالي. |
| [KnotVectors](../../aspose.threed.entities/nurbsdirection/knotvectors/) { get; } | الحصول على متجه العقد، وهو تسلسل من قيم المعامل التي تحدد أين وكيف تؤثر نقاط التحكم على منحنى NURBS. |
| [Multiplicity](../../aspose.threed.entities/nurbsdirection/multiplicity/) { get; } | الحصول على التعددية. |
| [Order](../../aspose.threed.entities/nurbsdirection/order/) { get; set; } | الحصول على أو تعيين ترتيب منحنى NURBS، حيث يحدد عدد نقاط التحكم القريبة التي تؤثر على أي نقطة معينة في المنحنى. |
| [Type](../../aspose.threed.entities/nurbsdirection/type/) { get; set; } | يحصل أو يعيّن نوع الاتجاه الحالي. |

### انظر أيضًا

* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


