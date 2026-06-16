---
title: "TriMesh.WriteVerticesTo"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة TriMesh. كتابة بيانات الرؤوس إلى الدفق المحدد"
type: docs
weight: 290
url: /ar/net/aspose.threed.entities/trimesh/writeverticesto/
---
## TriMesh.WriteVerticesTo method

اكتب بيانات الرؤوس إلى الدفق المحدد

```csharp
public void WriteVerticesTo(Stream stream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| stream | Stream | المجرى الذي سيتم كتابة بيانات الرؤوس إليه |

## أمثلة

```csharp
//تحويل شبكة إلى TriMesh، يتم استنتاج التخطيط تلقائيًا من الشبكة المدخلة
var triMesh = TriMesh.FromMesh(new Sphere().ToMesh());
//احفظه إلى الدفق، 115 رأسًا * 32 بايت لكل رأس
var stream = new MemoryStream();
triMesh.WriteVerticesTo(stream);
//احفظ الفهارس كـ ushort إلى الدفق، 504 فهرس * 2 بايت لكل فهرس
triMesh.Write16bIndicesTo(stream);
```

### انظر أيضًا

* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)


