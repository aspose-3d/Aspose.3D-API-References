---
title: "فئة Shape"
second_title: "مرجع Aspose.3D for .NET API"
description: "Aspose.ThreeD.Entities.Shape فئة. يصف الشكل التشوه على مجموعة من نقاط التحكم وهو مشابه لـ cluster deformer في Maya. على سبيل المثال يمكننا إضافة شكل إلى هندسة مُنشأة. والشكل والهندسة لديهما نفس المعلومات الطوبولوجية لكن مواضع نقاط التحكم مختلفة. مع اختلاف مقدار التأثير، تقوم الهندسة بتنفيذ تأثير التشوه."
type: docs
weight: 700
url: /ar/net/aspose.threed.entities/shape/
---
## Shape class

الشكل يصف التشوه على مجموعة من نقاط التحكم، وهو مشابه لمُشَكِّل التجمع (cluster deformer) في Maya. على سبيل المثال، يمكننا إضافة شكل إلى هندسة مُنشأة. ويتشارك الشكل والهندسة نفس المعلومات الطوبولوجية لكن بمواقع مختلفة لنقاط التحكم. مع اختلاف مستويات التأثير، تُنفّذ الهندسة تأثير التشوه.

```csharp
public class Shape : Geometry
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [Shape](shape/#constructor)() | يُهيئ مثيلاً جديداً من الفئة `Shape`. |
| [Shape](shape/#constructor_1)(string) | يُهيئ مثيلاً جديداً من الفئة `Shape`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/geometry/castshadows/) { get; set; } | يحصل أو يضبط ما إذا كان هذا الشكل الهندسي يمكنه إلقاء الظل |
| [ControlPoints](../../aspose.threed.entities/geometry/controlpoints/) { get; } | يحصل على جميع نقاط التحكم |
| [Deformers](../../aspose.threed.entities/geometry/deformers/) { get; } | يحصل على جميع المغيرات المرتبطة بهذا الشكل الهندسي. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | يحصل أو يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| [Indices](../../aspose.threed.entities/shape/indices/) { get; } | يحصل على الفهارس. |
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
| static [FromControlPoints](../../aspose.threed.entities/shape/fromcontrolpoints/)(params Vector3[]) | أنشئ شكلاً بنقاط تحكم محددة مع فهارس افتراضية. |
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


