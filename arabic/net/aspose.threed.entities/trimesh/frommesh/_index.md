---
title: "TriMesh.FromMesh"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة TriMesh. إنشاء TriMesh من كائن شبكة مُعطى مع تخطيط رأس مُحدد"
type: docs
weight: 30
url: /ar/net/aspose.threed.entities/trimesh/frommesh/
---
## FromMesh(VertexDeclaration, Mesh) {#frommesh_1}

إنشاء TriMesh من كائن شبكة مُعطى مع تخطيط رؤوس محدد.

```csharp
public static TriMesh FromMesh(VertexDeclaration declaration, Mesh mesh)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| الإعلان | VertexDeclaration | تعريف نوع Vertex، أو تخطيط الذاكرة |
| شبكة | Mesh | شبكة المصدر |

### قيمة الإرجاع

مثيل من TriMesh تم تحويله من شبكة الإدخال مع تخطيط ذاكرة رأس محدد

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

* class [VertexDeclaration](../../../aspose.threed.utilities/vertexdeclaration/)
* class [Mesh](../../mesh/)
* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)

---

## FromMesh(Mesh, bool) {#frommesh}

إنشاء TriMesh من كائن شبكة مُعطى، حيث يتم بناء تعريف الرؤوس بناءً على بنية الشبكة المدخلة.

```csharp
public static TriMesh FromMesh(Mesh mesh, bool useFloat = true)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| شبكة | Mesh |  |
| useFloat | Boolean | استخدم نوع float بدلاً من نوع double لكل مكوّن عنصر رأس. |

### قيمة الإرجاع

الـ [`TriMesh`](../) المولد من [`Mesh`](../../mesh/) المعطى

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

* class [Mesh](../../mesh/)
* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)


