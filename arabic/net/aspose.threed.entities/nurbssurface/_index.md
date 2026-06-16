---
title: "الفئة NurbsSurface"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Entities.NurbsSurface. NurbsSurface هو سطح ممثل بـ NURBSNonuniform rational basis spline. يتم تعريف NurbsSurface بواسطة اثنين من NurbsDirectionU و V. يُستخدم المكوّن w في نقطة التحكم كوزن لنقاط التحكم بغض النظر عن ما إذا كان نوع الاتجاه ثنائي الأبعاد أو ثلاثي الأبعاد."
type: docs
weight: 540
url: /ar/net/aspose.threed.entities/nurbssurface/
---
## NurbsSurface class

`NurbsSurface` هو سطح ممثل بـ [NURBS(Non-uniform rational basis spline)](https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline)، يتم تعريف `NurbsSurface` بواسطة اثنين من [`NurbsDirection`](../nurbsdirection/)[`U`](./u/) و [`V`](./v/). يُستخدم المكوّن w في نقطة التحكم كوزن لنقطة التحكم بغض النظر عن ما إذا كان نوع الاتجاه ثنائي الأبعاد أو ثلاثي الأبعاد.

```csharp
public class NurbsSurface : Geometry, IMeshConvertible
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [NurbsSurface](nurbssurface/#constructor)() | يُهيئ مثلاً جديدًا من الفئة `NurbsSurface`. |
| [NurbsSurface](nurbssurface/#constructor_1)(string) | يُهيئ مثلاً جديدًا من الفئة `NurbsSurface`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/geometry/castshadows/) { get; set; } | يحصل أو يضبط ما إذا كان هذا الشكل الهندسي يمكنه إلقاء الظل |
| [ControlPoints](../../aspose.threed.entities/geometry/controlpoints/) { get; } | يحصل على جميع نقاط التحكم |
| [Deformers](../../aspose.threed.entities/geometry/deformers/) { get; } | يحصل على جميع المغيرات المرتبطة بهذا الشكل الهندسي. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | يحصل أو يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | يحصل أو يعيّن العقدة الأصلية الأولى، إذا تم تعيين العقدة الأصلية الأولى، سيتم فصل هذا الكيان عن العقد الأصلية الأخرى. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | يحصل على جميع العقد الأصلية، يمكن إرفاق كيان بعدة عقد أصلية لتكرار الهندسة. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [ReceiveShadows](../../aspose.threed.entities/geometry/receiveshadows/) { get; set; } | يحصل أو يعيّن ما إذا كانت هذه الهندسة يمكنها استقبال الظل. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [U](../../aspose.threed.entities/nurbssurface/u/) { get; } | يحصل على اتجاه U لسطح NURBS. |
| [V](../../aspose.threed.entities/nurbssurface/v/) { get; } | يحصل على اتجاه V لسطح NURBS. |
| [VertexElements](../../aspose.threed.entities/geometry/vertexelements/) { get; } | يحصل على جميع عناصر الرأس |
| [Visible](../../aspose.threed.entities/geometry/visible/) { get; set; } | يحصل أو يعيّن ما إذا كانت الهندسة مرئية |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddElement](../../aspose.threed.entities/geometry/addelement/)(VertexElement) | يضيف عنصر رأس موجود إلى الهندسة الحالية |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/)(VertexElementType) | ينشئ عنصر رأس بالنوع المحدد ويضيفه إلى الهندسة. |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/)(VertexElementType, MappingMode, ReferenceMode) | ينشئ عنصر رأس بالنوع المحدد ويضيفه إلى الهندسة. |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/)(TextureMapping) | ينشئ [`VertexElementUV`](../vertexelementuv/) بنوع تخطيط القوام المعطى. |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/)(TextureMapping, MappingMode, ReferenceMode) | ينشئ [`VertexElementUV`](../vertexelementuv/) بنوع تخطيط القوام المعطى. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | يجد الخاصية. يمكن أن تكون خاصية ديناميكية (Created by CreateDynamicProperty/SetProperty) أو خاصية أصلية (Identified by its name) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | يحصل على صندوق الحدود للكيان الحالي في نظام إحداثيات مساحة الكائن الخاصة به. |
| [GetDeformers&lt;T&gt;](../../aspose.threed.entities/geometry/getdeformers/)() |  |
| [GetElement](../../aspose.threed.entities/geometry/getelement/)(VertexElementType) | يحصل على عنصر رأس بالنوع المحدد |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | يحصل على مفتاح عارض الكيان المسجل في العارض |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | احصل على قيمة الخاصية المحددة |
| [GetVertexElementOfUV](../../aspose.threed.entities/geometry/getvertexelementofuv/)(TextureMapping) | يحصل على نسخة من [`VertexElementUV`](../vertexelementuv/) بالنوع المعطى لتخطيط القوام |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | يزيل خاصية ديناميكية. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | إزالة الخاصية المحددة بالاسم |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | يضبط قيمة الخاصية المحددة |
| [ToMesh](../../aspose.threed.entities/nurbssurface/tomesh/)() | حوّل سطح NURBS إلى الشبكة. |

### انظر أيضًا

* class [Geometry](../geometry/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


