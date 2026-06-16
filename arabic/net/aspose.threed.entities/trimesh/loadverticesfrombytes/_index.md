---
title: "TriMesh.LoadVerticesFromBytes"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة TriMesh. تحميل الرؤوس من بايتات؛ يجب أن يكون طول البايتات مضاعفًا صحيحًا لحجم الرأس"
type: docs
weight: 160
url: /ar/net/aspose.threed.entities/trimesh/loadverticesfrombytes/
---
## TriMesh.LoadVerticesFromBytes method

تحميل الرؤوس من البايتات، يجب أن يكون طول البايتات مضاعفًا صحيحًا لحجم الرأس.

```csharp
public void LoadVerticesFromBytes(byte[] verticesInBytes)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| verticesInBytes | Byte[] |  |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException |  |
| ArgumentException |  |

## أمثلة

يعرض الكود التالي كيفية إنشاء TriMesh فارغ وتحميل الرؤوس يدويًا من بايتات خام.

```csharp
var indices = new int[] { 0,  1,  2 };
var vertices = new byte[]{
    0, 0, 0, 191,
    0, 0, 0, 0,
    0, 0, 0, 191,
    0, 0, 0, 191,
    0, 0, 0, 0,
    0, 0, 0, 63,
    0, 0, 0, 63,
    0, 0, 0, 0,
    0, 0, 0, 63
};
VertexDeclaration vd = new VertexDeclaration();
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
//إنشاء TriMesh فارغ مع تعريف رأس محدد
var triMesh = new TriMesh("", vd);
//تحميل الرؤوس مباشرةً من البايتات
triMesh.LoadVerticesFromBytes(vertices);
triMesh.AddTriangle(0, 1, 2);
```

```csharp
int[] indices = new int[] { 0,  1,  2 };
byte[] vertices = new byte[]{
    0, 0, 0, 191,
    0, 0, 0, 0,
    0, 0, 0, 191,
    0, 0, 0, 191,
    0, 0, 0, 0,
    0, 0, 0, 63,
    0, 0, 0, 63,
    0, 0, 0, 0,
    0, 0, 0, 63
};
VertexDeclaration vd = new VertexDeclaration();
vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
//إنشاء TriMesh فارغ مع تعريف رأس محدد
var triMesh = new TriMesh("", vd);
//تحميل الرؤوس مباشرةً من البايتات
triMesh.loadVerticesFromBytes(vertices);
triMesh.addTriangle(0, 1, 2);
```

### انظر أيضًا

* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)


