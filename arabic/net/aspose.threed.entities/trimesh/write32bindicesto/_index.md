---
title: "TriMesh.Write32bIndicesTo"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة TriMesh. كتابة بيانات الفهارس كعدد صحيح 32 بت إلى المجرى"
type: docs
weight: 280
url: /ar/net/aspose.threed.entities/trimesh/write32bindicesto/
---
## TriMesh.Write32bIndicesTo method

اكتب بيانات الفهارس كعدد صحيح 32 بت إلى الدفق

```csharp
public void Write32bIndicesTo(Stream stream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| stream | Stream |  |

## أمثلة

```csharp
//تحويل شبكة إلى TriMesh، يتم استنتاج التخطيط تلقائيًا من الشبكة المدخلة
var triMesh = TriMesh.FromMesh(new Sphere().ToMesh());
//احفظه إلى الدفق، 115 رأسًا * 32 بايت لكل رأس
var stream = new MemoryStream();
triMesh.WriteVerticesTo(stream);
//احفظ الفهارس كـ ushort إلى الدفق، 504 فهرس * 2 بايت لكل فهرس
triMesh.Write32bIndicesTo(stream);
```

### انظر أيضًا

* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)


