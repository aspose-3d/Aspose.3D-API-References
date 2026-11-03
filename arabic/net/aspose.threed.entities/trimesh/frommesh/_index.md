---
title: "TriMesh.FromMesh"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "طريقة TriMesh. إنشاء TriMesh من كائن شبكة معطى مع تخطيط رأس معطى"
type: docs
weight: 30
url: /ar/net/aspose.threed.entities/trimesh/frommesh/
---
## FromMesh(VertexDeclaration, Mesh) {#frommesh_1}

إنشاء TriMesh من كائن شبكة معطى مع تخطيط رأس معطى.

```csharp
public static TriMesh FromMesh(VertexDeclaration declaration, Mesh mesh)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| الإعلان | VertexDeclaration | تعريف نوع Vertex، أو تخطيط الذاكرة |
| شبكة | شبكة | شبكة المصدر |

### قيمة الإرجاع

مثال على TriMesh تم تحويله من شبكة الإدخال مع تخطيط الذاكرة للقمم المحدد

## أمثلة

الكود التالي يوضح كيفية إنشاء TriMesh بتخطيط ذاكرة مخصص، وتصديره إلى ملف.

```csharp
//عرّف إعلان القمة كالتالي {FVector3 Position; FVector3 Normal; FVector2 UV}
VertexDeclaration vd = new VertexDeclaration();
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Normal);
vd.AddField(VertexFieldDataType.FVector2, VertexFieldSemantic.UV);
//حوّل شبكة إلى TriMesh باستخدام تخطيط الذاكرة المحدد
var mesh = (new Sphere()).ToMesh();
var triMesh = TriMesh.FromMesh(vd, mesh);
//احفظه إلى دفق، 115 رأسًا * 32 بايت لكل رأس
using (var stream = new FileStream("output.bin", FileMode.Create))
{
    triMesh.WriteVerticesTo(stream);
    //احفظ الفهارس كـ ushort إلى الدفق، 504 فهرس * 2 بايت لكل فهرس
    triMesh.Write16bIndicesTo(stream);
}
```

### انظر أيضًا

* class [VertexDeclaration](../../../aspose.threed.utilities/vertexdeclaration/)
* class [Mesh](../../mesh/)
* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)

---

## FromMesh(Mesh, bool) {#frommesh}

أنشئ TriMesh من كائن الشبكة المعطى، حيث يعتمد إعلان القمة على بنية شبكة الإدخال.

```csharp
public static TriMesh FromMesh(Mesh mesh, bool useFloat = true)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| شبكة | شبكة |  |
| useFloat | Boolean | استخدم نوع float بدلاً من نوع double لكل مكوّن عنصر القمة. |

### قيمة الإرجاع

الـ [`TriMesh`](../) المُولَّد من الـ [`Mesh`](../../mesh/) المعطى

## أمثلة

الكود التالي يوضح كيفية إنشاء TriMesh بتخطيط ذاكرة مخصص، وتصديره إلى ملف.

```csharp
//عرّف إعلان القمة كالتالي {FVector3 Position; FVector3 Normal; FVector2 UV}
VertexDeclaration vd = new VertexDeclaration();
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Normal);
vd.AddField(VertexFieldDataType.FVector2, VertexFieldSemantic.UV);
//حوّل شبكة إلى TriMesh باستخدام تخطيط الذاكرة المحدد
var mesh = (new Sphere()).ToMesh();
var triMesh = TriMesh.FromMesh(vd, mesh);
//احفظه إلى دفق، 115 رأسًا * 32 بايت لكل رأس
using (var stream = new FileStream("output.bin", FileMode.Create))
{
    triMesh.WriteVerticesTo(stream);
    //احفظ الفهارس كـ ushort إلى الدفق، 504 فهرس * 2 بايت لكل فهرس
    triMesh.Write16bIndicesTo(stream);
}
```

### انظر أيضًا

* class [Mesh](../../mesh/)
* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)


