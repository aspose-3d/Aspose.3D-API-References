---
title: "الفئة Geometry"
second_title: "مرجع Aspose.3D for .NET API"
description: "Aspose.ThreeD.Entities.Geometry class. الفئة الأساسية لجميع الكائنات الهندسية القابلة للتصوير مثل Mesh NurbsSurface Patch وغيرها"
type: docs
weight: 410
url: /ar/net/aspose.threed.entities/geometry/
---
## Geometry class

الفئة الأساسية لجميع الكائنات الهندسية القابلة للتصوير (مثل [`Mesh`](../mesh/), [`NurbsSurface`](../nurbssurface/), [`Patch`](../patch/) وغيرها).

فئة `Geometry` الأساسية تدعم: **Control point management**، تحدد نقاط التحكم البنية المكانية ثلاثية الأبعاد الأساسية للجيومتري، الأنواع الهندسية المختلفة لها طريقة مختلفة لتعريف نماذج ثلاثية الأبعاد ملموسة. **Vertex element definition**، تطبق عناصر الرأس معلومات إضافية مثل المتجهات العمودية/إحداثيات uv/ألوان الرأس على الجيومتري، راجع [`VertexElement`](../vertexelement/) للمزيد من التفاصيل.**Object deforming**، يمكن ربط [`Deformer`](../../aspose.threed.deformers/deformer/) لتحريك شكل الجيومتري.

```csharp
public class Geometry : Entity
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [Geometry](geometry/)(string) | ينشئ مثيلاً جديداً من فئة `Geometry`. |

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
| [VertexElements](../../aspose.threed.entities/geometry/vertexelements/) { get; } | يحصل على جميع عناصر الرأس |
| [Visible](../../aspose.threed.entities/geometry/visible/) { get; set; } | يحصل أو يعيّن ما إذا كانت الهندسة مرئية |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddElement](../../aspose.threed.entities/geometry/addelement/)(VertexElement) | يضيف عنصر رأس موجود إلى الهندسة الحالية |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/#createelement)(VertexElementType) | ينشئ عنصر رأس بالنوع المحدد ويضيفه إلى الهندسة. |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/#createelement_1)(VertexElementType, MappingMode, ReferenceMode) | ينشئ عنصر رأس بالنوع المحدد ويضيفه إلى الهندسة. |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/#createelementuv)(TextureMapping) | ينشئ [`VertexElementUV`](../vertexelementuv/) بنوع تخطيط القوام المعطى. |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/#createelementuv_1)(TextureMapping, MappingMode, ReferenceMode) | ينشئ [`VertexElementUV`](../vertexelementuv/) بنوع تخطيط القوام المعطى. |
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

* class [Entity](../../aspose.threed/entity/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


