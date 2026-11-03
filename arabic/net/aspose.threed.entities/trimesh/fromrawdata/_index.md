---
title: "TriMesh.FromRawData"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "طريقة TriMesh. إنشاء TriMesh من بيانات خام"
type: docs
weight: 40
url: /ar/net/aspose.threed.entities/trimesh/fromrawdata/
---
## TriMesh.FromRawData method

إنشاء TriMesh من بيانات خام

```csharp
public static TriMesh FromRawData(VertexDeclaration vd, byte[] vertices, int[] indices, 
    bool generateVertexMapping)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| vd | VertexDeclaration | إعلان الـ Vertex، يجب أن يحتوي على حقل واحد على الأقل. |
| الرؤوس | Byte[] | بيانات الـ vertex المدخلة، الحد الأدنى لطول الرؤوس يجب أن يكون أكبر أو يساوي حجم إعلان الـ vertex |
| indices | Int32[] | فهارس المثلثات |
| generateVertexMapping | Boolean | إنشاء [`Vertex`](../../../aspose.threed.utilities/vertex/) لكل رأس، وهذا غير ضروري فقط للتسلسل/إلغاء التسلسل. |

### قيمة الإرجاع

الـ [`TriMesh`](../) التي احتوت مصفوفة البايت المدخلة.

## ملاحظات

الـ TriMesh المعاد لن ينسخ مصفوفة البايت المدخلة لأداء أفضل، وستنعكس التغييرات الخارجية على المصفوفة على هذه النسخة.

## أمثلة

الكود التالي يوضح كيفية إنشاء TriMesh من بايتات خام، وهذا مفيد عند بناء تنسيق 3D الخاص بك.

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
var triMesh = TriMesh.FromRawData(vd, vertices, indices, true);
```

### انظر أيضًا

* class [VertexDeclaration](../../../aspose.threed.utilities/vertexdeclaration/)
* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)


