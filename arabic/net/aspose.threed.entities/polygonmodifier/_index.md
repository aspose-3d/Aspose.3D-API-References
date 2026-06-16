---
title: "الفئة PolygonModifier"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Entities.PolygonModifier. أدوات لتعديل المضلعات"
type: docs
weight: 620
url: /ar/net/aspose.threed.entities/polygonmodifier/
---
## PolygonModifier class

أدوات لتعديل المضلعات.

```csharp
public class PolygonModifier
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [ApplyTransform](../../aspose.threed.entities/polygonmodifier/applytransform/)(Node, Matrix4) | طبق مصفوفة التحويل على نقاط التحكم في جميع الأشكال الهندسية |
| static [BuildTangentBinormal](../../aspose.threed.entities/polygonmodifier/buildtangentbinormal/#buildtangentbinormal)(Mesh) | سيتم إنشاء المماس والبيّنورمال على الشبكة. الـNormal مطلوب، إذا لم يكن الـNormal موجوداً على الشبكة، سيتم أيضاً إنشاء بيانات الـNormal من الموضع. الـUV مطلوب أيضاً، سيُرفع استثناء إذا لم يتم العثور على UV. |
| static [BuildTangentBinormal](../../aspose.threed.entities/polygonmodifier/buildtangentbinormal/#buildtangentbinormal_1)(Scene) | سيتم إنشاء المماس والبيّنورمال على جميع الشبكات في المشهد. الـNormal مطلوب، إذا لم يكن الـNormal موجوداً على الشبكة، سيتم أيضاً إنشاء بيانات الـNormal من الموضع. الـUV مطلوب أيضاً، سيتم تجاهل الشبكة إذا لم يتم تعريف UV. |
| static [GenerateNormal](../../aspose.threed.entities/polygonmodifier/generatenormal/)(Mesh) | إنشاء بيانات الـNormal من تعريف الـMesh |
| static [GenerateUV](../../aspose.threed.entities/polygonmodifier/generateuv/#generateuv)(Mesh) | إنشاء بيانات الـUV من الشبكة المدخلة المعطاة |
| static [GenerateUV](../../aspose.threed.entities/polygonmodifier/generateuv/#generateuv_1)(Mesh, VertexElementNormal) | إنشاء بيانات الـUV من الشبكة المدخلة المعطاة وبيانات الـNormal المحددة. |
| static [MergeMesh](../../aspose.threed.entities/polygonmodifier/mergemesh/#mergemesh_2)(IList&lt;Node&gt;) |  |
| static [MergeMesh](../../aspose.threed.entities/polygonmodifier/mergemesh/#mergemesh)(Node) | تحويل عقدة كاملة إلى شبكة محوّلة واحدة. عناصر القمة مثل إحداثيات الـnormal/texture غير مدعومة بعد. |
| static [MergeMesh](../../aspose.threed.entities/polygonmodifier/mergemesh/#mergemesh_1)(Scene) | تحويل المشهد بالكامل إلى شبكة محوّلة واحدة. عناصر القمة مثل إحداثيات الـnormal/texture غير مدعومة بعد. |
| static [Scale](../../aspose.threed.entities/polygonmodifier/scale/#scale_1)(Node, Vector3) | قُم بتكبير جميع الأشكال الهندسية (قم بتكبير نقاط التحكم وليس مصفوفة التحويل) في هذه العقدة. |
| static [Scale](../../aspose.threed.entities/polygonmodifier/scale/#scale)(Scene, Vector3) | قُم بتكبير جميع الأشكال (قم بتكبير نقاط التحكم وليس مصفوفة التحويل) في هذا المشهد |
| static [SplitMesh](../../aspose.threed.entities/polygonmodifier/splitmesh/#splitmesh)(Mesh, SplitMeshPolicy) | قسّم الشبكة إلى شبكات فرعية باستخدام [`VertexElementMaterial`](../vertexelementmaterial/). كل شبكة فرعية ستستخدم مادة واحدة فقط. لن يتم تغيير الشبكة الأصلية. |
| static [SplitMesh](../../aspose.threed.entities/polygonmodifier/splitmesh/#splitmesh_2)(Scene, SplitMeshPolicy, bool) | قسّم الشبكة إلى شبكات فرعية باستخدام [`VertexElementMaterial`](../vertexelementmaterial/). كل شبكة فرعية ستستخدم مادة واحدة فقط. نفّذ تقسيم الشبكة على جميع عقد المشهد. |
| static [SplitMesh](../../aspose.threed.entities/polygonmodifier/splitmesh/#splitmesh_1)(Node, SplitMeshPolicy, bool, bool) | قسّم الشبكة إلى شبكات فرعية باستخدام [`VertexElementMaterial`](../vertexelementmaterial/). كل شبكة فرعية ستستخدم مادة واحدة فقط. نفّذ تقسيم الشبكة على عقدة واحدة |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_1)(IList&lt;Vector4&gt;) |  |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate)(Mesh) | حوّل شبكة مبنية على مضلعات إلى شبكة مثلثية كاملة |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_5)(Scene) | حوّل جميع الشبكات المبنية على مضلعات إلى شبكة مثلثية كاملة |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_3)(IList&lt;Vector4&gt;, IList&lt;int[]&gt;) |  |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_2)(IList&lt;Vector4&gt;, int[]) |  |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_4)(IList&lt;Vector4&gt;, IList&lt;int[]&gt;, bool, out Vector3[]) |  |

### انظر أيضًا

* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


