---
title: "TriMesh.CopyFrom"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة TriMesh. نسخ الـ TriMesh من الإدخال مع تخطيط رأس جديد"
type: docs
weight: 20
url: /ar/net/aspose.threed.entities/trimesh/copyfrom/
---
## TriMesh.CopyFrom method

نسخ الـ [`TriMesh`](../) من الإدخال مع تخطيط رأس جديد

```csharp
public static TriMesh CopyFrom(TriMesh input, VertexDeclaration vd)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| input | TriMesh | TriMesh الإدخال للنسخ |
| vd | VertexDeclaration | إعلان الرأس الجديد للـ TriMesh الناتج |

### قيمة الإرجاع

كائن جديد من TriMesh مع إعلان رأس جديد.

## أمثلة

```csharp
//عرّف إعلان الرأس كـ {FVector3 Position; FVector3 Normal; FVector2 UV}
VertexDeclaration vd = new VertexDeclaration();
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Normal);
vd.AddField(VertexFieldDataType.FVector2, VertexFieldSemantic.UV);
//تحويل شبكة إلى TriMesh، يتم استنتاج التخطيط تلقائيًا من الشبكة المدخلة
var oldTriMesh = TriMesh.FromMesh((new Sphere()).ToMesh());
//الآن أنشئ TriMesh جديدًا من TriMesh القديم، باستخدام تخطيط الذاكرة الصريح المحدد بواسطة vd
var newTriMesh = TriMesh.CopyFrom(oldTriMesh, vd);
```

### انظر أيضًا

* class [VertexDeclaration](../../../aspose.threed.utilities/vertexdeclaration/)
* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)


