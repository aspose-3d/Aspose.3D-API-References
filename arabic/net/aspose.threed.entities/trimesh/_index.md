---
title: "الفئة TriMesh"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Entities.TriMesh. يحتوي TriMesh على بيانات خام يمكن للـ GPU استخدامها مباشرةً. هذه الفئة أداة تساعد في إنشاء شبكة تحتوي فقط على بيانات لكل رأس."
type: docs
weight: 790
url: /ar/net/aspose.threed.entities/trimesh/
---
## TriMesh class

TriMesh يحتوي على بيانات خام يمكن لوحدة معالجة الرسوميات (GPU) استخدامها مباشرة. هذه الفئة أداة للمساعدة في إنشاء شبكة تحتوي فقط على بيانات لكل رأس.

```csharp
public class TriMesh : Entity, IEnumerable<Vertex>
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [TriMesh](trimesh/)(string, VertexDeclaration) | تهيئة نسخة من `TriMesh` |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Capacity](../../aspose.threed.entities/trimesh/capacity/) { get; } | السعة المخصصة مسبقًا للرؤوس. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | يحصل أو يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| [IndicesCount](../../aspose.threed.entities/trimesh/indicescount/) { get; } | عدد الفهارس في هذا `TriMesh` |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | يحصل أو يعيّن العقدة الأصلية الأولى، إذا تم تعيين العقدة الأصلية الأولى، سيتم فصل هذا الكيان عن العقد الأصلية الأخرى. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | يحصل على جميع العقد الأصلية، يمكن إرفاق كيان بعدة عقد أصلية لتكرار الهندسة. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [UnmergedVerticesCount](../../aspose.threed.entities/trimesh/unmergedverticescount/) { get; } | عدد الرؤوس غير المدمجة التي تم تمريرها عبر [`BeginVertex`](./beginvertex/) و[`EndVertex`](./endvertex/). |
| [VertexDeclaration](../../aspose.threed.entities/trimesh/vertexdeclaration/) { get; } | تخطيط الرؤوس لـ `TriMesh`. |
| [VerticesCount](../../aspose.threed.entities/trimesh/verticescount/) { get; } | عدد الرؤوس في هذا `TriMesh` |
| [VerticesSizeInBytes](../../aspose.threed.entities/trimesh/verticessizeinbytes/) { get; } | الحجم الكلي لجميع الرؤوس بالبايت |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [CopyFrom](../../aspose.threed.entities/trimesh/copyfrom/)(TriMesh, VertexDeclaration) | نسخ `TriMesh` من الإدخال مع تخطيط رؤوس جديد |
| static [FromMesh](../../aspose.threed.entities/trimesh/frommesh/#frommesh)(Mesh, bool) | إنشاء TriMesh من كائن شبكة مُعطى، حيث يتم بناء تعريف الرؤوس بناءً على بنية الشبكة المدخلة. |
| static [FromMesh](../../aspose.threed.entities/trimesh/frommesh/#frommesh_1)(VertexDeclaration, Mesh) | إنشاء TriMesh من كائن شبكة مُعطى مع تخطيط رؤوس محدد. |
| static [FromRawData](../../aspose.threed.entities/trimesh/fromrawdata/)(VertexDeclaration, byte[], int[], bool) | إنشاء TriMesh من بيانات خام |
| [AddTriangle](../../aspose.threed.entities/trimesh/addtriangle/)(int, int, int) | إضافة مثلث جديد |
| [BeginVertex](../../aspose.threed.entities/trimesh/beginvertex/)() | بدء إضافة رأس |
| [EndVertex](../../aspose.threed.entities/trimesh/endvertex/)() | إنهاء إضافة رأس |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | يجد الخاصية. يمكن أن تكون خاصية ديناميكية (Created by CreateDynamicProperty/SetProperty) أو خاصية أصلية (Identified by its name) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | يحصل على صندوق الحدود للكيان الحالي في نظام إحداثيات مساحة الكائن الخاصة به. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | يحصل على مفتاح عارض الكيان المسجل في العارض |
| [GetEnumerator](../../aspose.threed.entities/trimesh/getenumerator/)() | احصل على المُعدِّد لتعداد [`Vertex`](../../aspose.threed.utilities/vertex/) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | احصل على قيمة الخاصية المحددة |
| [IndicesToArray](../../aspose.threed.entities/trimesh/indicestoarray/#indicestoarray)(out int[]) |  |
| [IndicesToArray](../../aspose.threed.entities/trimesh/indicestoarray/#indicestoarray_1)(out ushort[]) |  |
| [LoadVerticesFromBytes](../../aspose.threed.entities/trimesh/loadverticesfrombytes/)(byte[]) | تحميل الرؤوس من البايتات، يجب أن يكون طول البايتات مضاعفًا صحيحًا لحجم الرأس. |
| [ReadDouble](../../aspose.threed.entities/trimesh/readdouble/)(int, VertexField) | اقرأ الحقل من نوع double |
| [ReadFloat](../../aspose.threed.entities/trimesh/readfloat/)(int, VertexField) | اقرأ الحقل من نوع float |
| [ReadFVector2](../../aspose.threed.entities/trimesh/readfvector2/)(int, VertexField) | اقرأ الحقل من نوع vector2 |
| [ReadFVector3](../../aspose.threed.entities/trimesh/readfvector3/)(int, VertexField) | قراءة حقل vector3 |
| [ReadFVector4](../../aspose.threed.entities/trimesh/readfvector4/)(int, VertexField) | قراءة حقل vector4 |
| [ReadVector2](../../aspose.threed.entities/trimesh/readvector2/)(int, VertexField) | اقرأ الحقل من نوع vector2 |
| [ReadVector3](../../aspose.threed.entities/trimesh/readvector3/)(int, VertexField) | قراءة حقل vector3 |
| [ReadVector4](../../aspose.threed.entities/trimesh/readvector4/)(int, VertexField) | قراءة حقل vector4 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | يزيل خاصية ديناميكية. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | إزالة الخاصية المحددة بالاسم |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | يضبط قيمة الخاصية المحددة |
| override [ToString](../../aspose.threed.entities/trimesh/tostring/)() | يحصل على تمثيل النص لـ `TriMesh` |
| [VerticesToArray](../../aspose.threed.entities/trimesh/verticestoarray/)() | تحويل بيانات الرؤوس إلى مصفوفة بايت |
| [Write16bIndicesTo](../../aspose.threed.entities/trimesh/write16bindicesto/)(Stream) | اكتب بيانات الفهارس كعدد صحيح 16 بت إلى الدفق |
| [Write32bIndicesTo](../../aspose.threed.entities/trimesh/write32bindicesto/)(Stream) | اكتب بيانات الفهارس كعدد صحيح 32 بت إلى الدفق |
| [WriteVerticesTo](../../aspose.threed.entities/trimesh/writeverticesto/)(Stream) | اكتب بيانات الرؤوس إلى الدفق المحدد |

## أمثلة

الكود التالي يوضح كيفية إنشاء TriMesh بتخطيط ذاكرة مخصص، وتصديره إلى ملف.

```csharp
//عرّف إعلان الرأس كـ {FVector3 Position; FVector3 Normal; FVector2 UV}
VertexDeclaration vd = new VertexDeclaration();
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Normal);
vd.AddField(VertexFieldDataType.FVector2, VertexFieldSemantic.UV);
//حوّل شبكة إلى شبكة ثلاثية الأضلاع باستخدام تخطيط الذاكرة المحدد
var mesh = (new Sphere()).ToMesh();
var triMesh = TriMesh.FromMesh(vd, mesh);
//احفظه إلى الدفق، 115 رأسًا * 32 بايت لكل رأس
using (var stream = new FileStream("output.bin", FileMode.Create))
{
    triMesh.WriteVerticesTo(stream);
    //احفظ الفهارس كـ ushort إلى الدفق، 504 فهرس * 2 بايت لكل فهرس
    triMesh.Write16bIndicesTo(stream);
}
```

### انظر أيضًا

* class [Entity](../../aspose.threed/entity/)
* class [Vertex](../../aspose.threed.utilities/vertex/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


