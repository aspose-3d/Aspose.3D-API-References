---
title: "DracoFormat.Decode"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة DracoFormat. فك تشفير سحابة النقاط أو الشبكة من اسم الملف المحدد"
type: docs
weight: 10
url: /ar/net/aspose.threed.formats/dracoformat/decode/
---
## Decode(string) {#decode_1}

فك تشفير سحابة النقاط أو الشبكة من اسم الملف المحدد

```csharp
public Geometry Decode(string fileName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fileName | سلسلة | اسم الملف يحتوي على ملف drc |

### قيمة الإرجاع

مثيل [`Mesh`](../../../aspose.threed.entities/mesh/) أو [`PointCloud`](../../../aspose.threed.entities/pointcloud/) يعتمد على محتوى الملف

### استثناءات

| استثناء | شرط |
| --- | --- |
| IOException | يُطرح عندما يفشل القراءة من الملف |

## أمثلة

الكود التالي يوضح كيفية ترميز وفك ترميز Mesh إلى/من مصفوفة بايت:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//ترميز الشبكة إلى تنسيق Draco
byte[] draco = FileFormat.Draco.Encode(mesh);
//فك ترميز الشبكة من تنسيق Draco
Mesh decodedMesh = (Mesh)FileFormat.Draco.Decode(draco);
```

### انظر أيضًا

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)

---

## Decode(byte[]) {#decode}

فك تشفير سحابة النقاط أو الشبكة من بيانات الذاكرة

```csharp
public Geometry Decode(byte[] data)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| بيانات | Byte[] | البايتات الخام للـ drc |

### قيمة الإرجاع

مثيل [`Mesh`](../../../aspose.threed.entities/mesh/) أو [`PointCloud`](../../../aspose.threed.entities/pointcloud/) يعتمد على المحتوى

### استثناءات

| استثناء | شرط |
| --- | --- |
| [ImportException](../../../aspose.threed/importexception/) | يُطرح عندما تكون البيانات مشوهة. |

## أمثلة

الكود التالي يوضح كيفية ترميز وفك ترميز Mesh إلى/من مصفوفة بايت:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//ترميز الشبكة إلى تنسيق Draco
byte[] draco = FileFormat.Draco.Encode(mesh);
//فك ترميز الشبكة من تنسيق Draco
Mesh decodedMesh = (Mesh)FileFormat.Draco.Decode(draco);
```

### انظر أيضًا

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)


