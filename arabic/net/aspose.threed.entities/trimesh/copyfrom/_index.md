---
title: "TriMesh.CopyFrom"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "طريقة TriMesh. نسخ TriMesh من الإدخال مع تخطيط قمة جديد"
type: docs
weight: 20
url: /ar/net/aspose.threed.entities/trimesh/copyfrom/
---
## TriMesh.CopyFrom method

انسخ الـ [`TriMesh`](../) من الإدخال مع تخطيط قمة جديد

```csharp
public static TriMesh CopyFrom(TriMesh input, VertexDeclaration vd)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| إدخال | TriMesh | TriMesh الإدخال للنسخ |
| vd | VertexDeclaration | إعلان القمة الجديد لـ TriMesh الناتج |

### قيمة الإرجاع

مثال جديد من TriMesh مع تعريف رأس جديد.

## أمثلة

```csharp
//عرّف إعلان القمة كالتالي {FVector3 Position; FVector3 Normal; FVector2 UV}
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


