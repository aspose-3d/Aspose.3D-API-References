---
title: "الفئة Patch"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Entities.Patch. الرقعة هي سطح نمذجة بارامتري مشابه لـ NurbsSurface وهو أيضًا معرف بواسطة اتجاهي PatchDirection هما U و V. لكن الفرق بين Patch و NurbsSurface هو أن منحنى PatchDirection يمكن أن يكون أحد Bezier أو QuadraticBezier أو BasisSpline أو CardinalSpline أو Linear"
type: docs
weight: 560
url: /ar/net/aspose.threed.entities/patch/
---
## Patch class

الـ `Patch` هو سطح نمذجة بارامتري، مشابه لـ [`NurbsSurface`](../nurbssurface/)، وهو أيضًا معرف بواسطة اثنين من [`PatchDirection`](../patchdirection/)، الـ [`U`](./u/) والـ [`V`](./v/). لكن الفرق بين `Patch` و [`NurbsSurface`](../nurbssurface/) هو أن منحنى [`PatchDirection`](../patchdirection/) يمكن أن يكون أحد Bezier أو QuadraticBezier أو BasisSpline أو CardinalSpline أو Linear

```csharp
public class Patch : Geometry
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [Patch](patch/#constructor)() | يُنشئ مثلاً جديداً من الفئة `Patch`. |
| [Patch](patch/#constructor_1)(string) | يُنشئ مثلاً جديداً من الفئة `Patch`. |

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
| [U](../../aspose.threed.entities/patch/u/) { get; } | يحصل على اتجاه u. |
| [V](../../aspose.threed.entities/patch/v/) { get; } | يحصل على اتجاه v. |
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

### انظر أيضًا

* class [Geometry](../geometry/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


