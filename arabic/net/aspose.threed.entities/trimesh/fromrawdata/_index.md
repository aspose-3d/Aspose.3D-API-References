---
title: "TriMesh.FromRawData"
second_title: "مرجع Aspose.3D for .NET API"
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
| الرؤوس | Byte[] | بيانات الـ vertex المدخلة، الحد الأدنى لطول الـ vertices يجب أن يكون أكبر أو يساوي حجم إعلان الـ vertex |
| المؤشرات | Int32[] | مؤشرات المثلثات |
| generateVertexMapping | Boolean | إنشاء [`Vertex`](../../../aspose.threed.utilities/vertex/) لكل vertex، وهو غير ضروري للتسلسل/إلغاء التسلسل فقط. |

### قيمة الإرجاع

المثيل [`TriMesh`](../) الذي يضم مصفوفة الـ byte المدخلة.

## ملاحظات

الـ TriMesh المرتجع لن ينسخ مصفوفة الـ byte المدخلة لأداء أفضل، وستنعكس التغييرات الخارجية على المصفوفة على هذا المثيل.

## أمثلة

الكود التالي يوضح كيفية إنشاء TriMesh من بايتات خام، وهذا مفيد عند بناء تنسيق 3D الخاص بك

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


