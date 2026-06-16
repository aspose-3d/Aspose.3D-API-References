---
title: "الفئة Mesh"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Entities.Mesh. الشبكة مكوّنة من العديد من المضلعات متعددة الأضلاع"
type: docs
weight: 510
url: /ar/net/aspose.threed.entities/mesh/
---
## Mesh class

الشبكة تتكون من العديد من المضلع ذات n أضلاع.

```csharp
public class Mesh : Geometry, IEnumerable<int[]>, IMeshConvertible
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [Mesh](mesh/#constructor)() | يُنشئ مثيلًا جديدًا للفئة `Mesh`. |
| [Mesh](mesh/#constructor_4)(string) | يُنشئ مثيلًا جديدًا للفئة `Mesh`. |
| [Mesh](mesh/#constructor_1)(TextureData) | أنشئ شبكة باستخدام خريطة الارتفاع المحددة، إذا كان تنسيق بكسل خريطة الارتفاع يحتوي على مكونات متعددة، سيتم استخدام المكون الأول (عادةً الأحمر) كقيمة الارتفاع (z). مكونات إحداثيات x و y لنقطة التحكم هي إحداثيات بكسل مُطَبَّقة. |
| [Mesh](mesh/#constructor_2)(TextureData, Matrix4) | أنشئ شبكة باستخدام خريطة الارتفاع المحددة، إذا كان تنسيق بكسل خريطة الارتفاع يحتوي على مكونات متعددة، سيتم استخدام المكون الأول (عادةً الأحمر) كقيمة الارتفاع (z). مكونات إحداثيات x و y لنقطة التحكم هي إحداثيات بكسل مُطَبَّقة. |
| [Mesh](mesh/#constructor_3)(TextureData, bool, Matrix4) | أنشئ شبكة باستخدام خريطة الارتفاع المحددة، إذا كان تنسيق بكسل خريطة الارتفاع يحتوي على مكونات متعددة، سيتم استخدام المكون الأول (عادةً الأحمر) كقيمة الارتفاع (z). مكونات إحداثيات x و y لنقطة التحكم هي إحداثيات بكسل مُطَبَّقة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/geometry/castshadows/) { get; set; } | يحصل أو يضبط ما إذا كان هذا الشكل الهندسي يمكنه إلقاء الظل |
| [ControlPoints](../../aspose.threed.entities/geometry/controlpoints/) { get; } | يحصل على جميع نقاط التحكم |
| [Deformers](../../aspose.threed.entities/geometry/deformers/) { get; } | يحصل على جميع المغيرات المرتبطة بهذا الشكل الهندسي. |
| [Edges](../../aspose.threed.entities/mesh/edges/) { get; } | يحصل على حواف الشبكة. الحافة اختيارية في الشبكة، لذا يمكن أن تكون فارغة. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | يحصل أو يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | يحصل أو يعيّن العقدة الأصلية الأولى، إذا تم تعيين العقدة الأصلية الأولى، سيتم فصل هذا الكيان عن العقد الأصلية الأخرى. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | يحصل على جميع العقد الأصلية، يمكن إرفاق كيان بعدة عقد أصلية لتكرار الهندسة. |
| [PolygonCount](../../aspose.threed.entities/mesh/polygoncount/) { get; } | يحصل على عدد المضلعات |
| [Polygons](../../aspose.threed.entities/mesh/polygons/) { get; } | يحصل على تعريف المضلعات للشبكة |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [ReceiveShadows](../../aspose.threed.entities/geometry/receiveshadows/) { get; set; } | يحصل أو يعيّن ما إذا كانت هذه الهندسة يمكنها استقبال الظل. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [VertexElements](../../aspose.threed.entities/geometry/vertexelements/) { get; } | يحصل على جميع عناصر الرأس |
| [Visible](../../aspose.threed.entities/geometry/visible/) { get; set; } | يحصل أو يعيّن ما إذا كانت الهندسة مرئية |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [DoBoolean](../../aspose.threed.entities/mesh/doboolean/)(BooleanOperation, Mesh, Matrix4?, Mesh, Matrix4?) |  |
| [AddElement](../../aspose.threed.entities/geometry/addelement/)(VertexElement) | يضيف عنصر رأس موجود إلى الهندسة الحالية |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/)(VertexElementType) | ينشئ عنصر رأس بالنوع المحدد ويضيفه إلى الهندسة. |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/)(VertexElementType, MappingMode, ReferenceMode) | ينشئ عنصر رأس بالنوع المحدد ويضيفه إلى الهندسة. |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/)(TextureMapping) | ينشئ [`VertexElementUV`](../vertexelementuv/) بنوع تخطيط القوام المعطى. |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/)(TextureMapping, MappingMode, ReferenceMode) | ينشئ [`VertexElementUV`](../vertexelementuv/) بنوع تخطيط القوام المعطى. |
| [CreatePolygon](../../aspose.threed.entities/mesh/createpolygon/#createpolygon_2)(int[]) | ينشئ مضلعًا جديدًا بجميع الرؤوس المعرفة في *indices*. لإنشاء مضلع رأسًا برأس، يرجى استخدام [`PolygonBuilder`](../polygonbuilder/). |
| [CreatePolygon](../../aspose.threed.entities/mesh/createpolygon/#createpolygon)(int, int, int) | إنشاء مضلع بـ 3 رؤوس (مثلث) |
| [CreatePolygon](../../aspose.threed.entities/mesh/createpolygon/#createpolygon_3)(int[], int, int) | ينشئ مضلعًا جديدًا بجميع الرؤوس المعرفة في *indices*. لإنشاء مضلع رأسًا برأس، يرجى استخدام [`PolygonBuilder`](../polygonbuilder/). |
| [CreatePolygon](../../aspose.threed.entities/mesh/createpolygon/#createpolygon_1)(int, int, int, int) | إنشاء مضلع بـ 4 رؤوس (رباعي) |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | يجد الخاصية. يمكن أن تكون خاصية ديناميكية (Created by CreateDynamicProperty/SetProperty) أو خاصية أصلية (Identified by its name) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | يحصل على صندوق الحدود للكيان الحالي في نظام إحداثيات مساحة الكائن الخاصة به. |
| [GetDeformers&lt;T&gt;](../../aspose.threed.entities/geometry/getdeformers/)() |  |
| [GetElement](../../aspose.threed.entities/geometry/getelement/)(VertexElementType) | يحصل على عنصر رأس بالنوع المحدد |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | يحصل على مفتاح عارض الكيان المسجل في العارض |
| [GetEnumerator](../../aspose.threed.entities/mesh/getenumerator/)() | يحصل على المُعدد لكل المضلعات الداخلية. |
| [GetPolygonSize](../../aspose.threed.entities/mesh/getpolygonsize/)(int) | يحصل على عدد رؤوس المضلع المحدد. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | احصل على قيمة الخاصية المحددة |
| [GetVertexElementOfUV](../../aspose.threed.entities/geometry/getvertexelementofuv/)(TextureMapping) | يحصل على نسخة من [`VertexElementUV`](../vertexelementuv/) بالنوع المعطى لتخطيط القوام |
| [IsManifold](../../aspose.threed.entities/mesh/ismanifold/)() | تحقق مما إذا كانت الشبكة الحالية شبكة متعددة السطوح. هذه الدالة لن تخزن نتيجة حساب التعددية في الذاكرة المؤقتة. |
| [Optimize](../../aspose.threed.entities/mesh/optimize/#optimize)(bool) | حسّن استخدام الذاكرة للشبكة عن طريق إزالة نقاط التحكم المكررة |
| [Optimize](../../aspose.threed.entities/mesh/optimize/#optimize_1)(bool, float, float, float) | حسّن استخدام الذاكرة للشبكة عن طريق إزالة نقاط التحكم المكررة |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | يزيل خاصية ديناميكية. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | إزالة الخاصية المحددة بالاسم |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | يضبط قيمة الخاصية المحددة |
| [ToMesh](../../aspose.threed.entities/mesh/tomesh/)() | يحصل على نسخة الـ Mesh من الكيان الحالي. |
| [Triangulate](../../aspose.threed.entities/mesh/triangulate/)() | إرجاع شبكة مُثلثة |
| [operator &amp;](../../aspose.threed.entities/mesh/op_bitwiseand/) | احسب تقاطع شبكتين |
| [operator &#x7C;](../../aspose.threed.entities/mesh/op_bitwiseor/) | احسب اتحاد شبكتين |
| [operator -](../../aspose.threed.entities/mesh/op_subtraction/) | احسب الفرق بين شبكتين |

## أمثلة

لإضافة مضلع في الشبكة:

```csharp
Mesh mesh = new Mesh();
int[] indices = new int[] {0, 1, 2};
mesh.CreatePolygon(indices);
```

التنقل عبر جميع المضلعات في الشبكة:

```csharp
Mesh mesh = new Mesh();
foreach(int[] polygon in mesh)
{
    //التعامل مع المضلع
}
```

### انظر أيضًا

* class [Geometry](../geometry/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


