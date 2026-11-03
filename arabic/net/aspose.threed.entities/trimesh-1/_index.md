---
title: "الفئة TriMeshT"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "الفئة Aspose.ThreeD.Entities.TriMesh1T. نسخة عامة من TriMesh للمستخدمين بنوع رأس معرف ثابت."
type: docs
weight: 800
url: /ar/net/aspose.threed.entities/trimesh-1/
---
## TriMesh&lt;T&gt; class

نسخة عامة من [`TriMesh`](../trimesh/) لنوع رأس معرف ثابت للمستخدم

```csharp
public class TriMesh<T> : TriMesh
    where T : struct
```

| معامل | الوصف |
| --- | --- |
| T |  |

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [TriMesh](trimesh/)(string) | تهيئة كائن من [`TriMesh`](../trimesh/) |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Capacity](../../aspose.threed.entities/trimesh/capacity/) { get; } | السعة للقمم المخصصة مسبقًا. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | يحصل أو يعيّن ما إذا كان يجب استبعاد هذا الكائن أثناء التصدير. |
| [IndicesCount](../../aspose.threed.entities/trimesh/indicescount/) { get; } | عدد الفهارس في هذا [`TriMesh`](../trimesh/) |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | يحصل أو يعيّن العقدة الأصلية الأولى، إذا تم تعيين العقدة الأصلية الأولى، سيتم فصل هذا الكائن عن العقد الأصلية الأخرى. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | يحصل على جميع العقد الأصلية، يمكن ربط كائن بعدة عقد أصلية لتكرار الهندسة. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [UnmergedVerticesCount](../../aspose.threed.entities/trimesh/unmergedverticescount/) { get; } | عدد القمم غير المدمجة التي تم تمريرها عبر [`BeginVertex`](../trimesh/beginvertex/) و[`EndVertex`](../trimesh/endvertex/). |
| [VertexDeclaration](../../aspose.threed.entities/trimesh/vertexdeclaration/) { get; } | تخطيط القمم لـ [`TriMesh`](../trimesh/). |
| [VerticesCount](../../aspose.threed.entities/trimesh/verticescount/) { get; } | عدد القمم في هذا [`TriMesh`](../trimesh/) |
| [VerticesSizeInBytes](../../aspose.threed.entities/trimesh/verticessizeinbytes/) { get; } | الحجم الكلي لجميع القمم بالبايت |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromMesh](../../aspose.threed.entities/trimesh-1/frommesh/)(Mesh) | إنشاء TriMesh من كائن شبكة مُعطى مع تخطيط رؤوس يتم إنشاؤه تلقائيًا. |
| [AddTriangle](../../aspose.threed.entities/trimesh/addtriangle/)(int, int, int) | إضافة مثلث جديد |
| [BeginVertex](../../aspose.threed.entities/trimesh/beginvertex/)() | بدء إضافة رأس |
| [EndVertex](../../aspose.threed.entities/trimesh/endvertex/)() | إنهاء إضافة رأس |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | يبحث عن الخاصية. يمكن أن تكون خاصية ديناميكية (تم إنشاؤها بواسطة CreateDynamicProperty/SetProperty) أو خاصية أصلية (محددة باسمها). |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | يحصل على صندوق الحدود للكيان الحالي في نظام إحداثيات مساحة الكائن الخاصة به. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | يحصل على مفتاح عارض الكيان المسجل في العارض. |
| [GetEnumerator](../../aspose.threed.entities/trimesh/getenumerator/)() | احصل على المُعدِّد لتعداد [`Vertex`](../../aspose.threed.utilities/vertex/) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | احصل على قيمة الخاصية المحددة |
| [IndicesToArray](../../aspose.threed.entities/trimesh/indicestoarray/)(out int[]) |  |
| [IndicesToArray](../../aspose.threed.entities/trimesh/indicestoarray/)(out ushort[]) |  |
| [LoadVerticesFromBytes](../../aspose.threed.entities/trimesh/loadverticesfrombytes/)(byte[]) | تحميل الرؤوس من البايتات، يجب أن يكون طول البايتات مضاعفًا صحيحًا لحجم الرأس. |
| [ReadDouble](../../aspose.threed.entities/trimesh/readdouble/)(int, VertexField) | قراءة الحقل المزدوج |
| [ReadFloat](../../aspose.threed.entities/trimesh/readfloat/)(int, VertexField) | قراءة الحقل العائم |
| [ReadFVector2](../../aspose.threed.entities/trimesh/readfvector2/)(int, VertexField) | قراءة حقل vector2 |
| [ReadFVector3](../../aspose.threed.entities/trimesh/readfvector3/)(int, VertexField) | قراءة حقل vector3 |
| [ReadFVector4](../../aspose.threed.entities/trimesh/readfvector4/)(int, VertexField) | قراءة حقل vector4 |
| [ReadVector2](../../aspose.threed.entities/trimesh/readvector2/)(int, VertexField) | قراءة حقل vector2 |
| [ReadVector3](../../aspose.threed.entities/trimesh/readvector3/)(int, VertexField) | قراءة حقل vector3 |
| [ReadVector4](../../aspose.threed.entities/trimesh/readvector4/)(int, VertexField) | قراءة حقل vector4 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | يزيل خاصية ديناميكية. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | إزالة الخاصية المحددة التي تم التعرف عليها بالاسم |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | يضبط قيمة الخاصية المحددة |
| override [ToString](../../aspose.threed.entities/trimesh/tostring/)() | يحصل على التمثيل النصي لـ [`TriMesh`](../trimesh/) |
| [VerticesToArray](../../aspose.threed.entities/trimesh/verticestoarray/)() | تحويل بيانات الرؤوس إلى مصفوفة بايت |
| [VerticesToTypedArray](../../aspose.threed.entities/trimesh-1/verticestotypedarray/)() | تحويل بيانات الرؤوس إلى مصفوفة ذات نوع محدد |
| [Write16bIndicesTo](../../aspose.threed.entities/trimesh/write16bindicesto/)(Stream) | كتابة بيانات الفهارس كعدد صحيح 16‑بت إلى الدفق |
| [Write32bIndicesTo](../../aspose.threed.entities/trimesh/write32bindicesto/)(Stream) | كتابة بيانات الفهارس كعدد صحيح 32‑بت إلى الدفق |
| [WriteVerticesTo](../../aspose.threed.entities/trimesh/writeverticesto/)(Stream) | كتابة بيانات الرؤوس إلى الدفق المحدد |

### انظر أيضًا

* class [TriMesh](../trimesh/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


