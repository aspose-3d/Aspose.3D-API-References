---
title: "DracoFormat.Decode"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
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
| fileName | String | اسم الملف يحتوي على ملف drc |

### قيمة الإرجاع

مثال [`Mesh`](../../../aspose.threed.entities/mesh/) أو [`PointCloud`](../../../aspose.threed.entities/pointcloud/) يعتمد على محتوى الملف

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| IOException | يُرمى عندما يفشل القراءة من الملف |

## أمثلة

الكود التالي يوضح كيفية ترميز وفك ترميز Mesh إلى/من مصفوفة بايت:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//ترميز mesh إلى صيغة Draco
byte[] draco = FileFormat.Draco.Encode(mesh);
//فك ترميز mesh من صيغة Draco
Mesh decodedMesh = (Mesh)FileFormat.Draco.Decode(draco);
```

### انظر أيضًا

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)

---

## Decode(byte[]) {#decode}

فك تشفير سحابة النقاط أو mesh من بيانات الذاكرة

```csharp
public Geometry Decode(byte[] data)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| بيانات | Byte[] | البتات الخام من drc |

### قيمة الإرجاع

مثال [`Mesh`](../../../aspose.threed.entities/mesh/) أو [`PointCloud`](../../../aspose.threed.entities/pointcloud/) يعتمد على المحتوى

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [ImportException](../../../aspose.threed/importexception/) | يُرمى عندما تكون البيانات غير صالحة. |

## أمثلة

الكود التالي يوضح كيفية ترميز وفك ترميز Mesh إلى/من مصفوفة بايت:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//ترميز mesh إلى صيغة Draco
byte[] draco = FileFormat.Draco.Encode(mesh);
//فك ترميز mesh من صيغة Draco
Mesh decodedMesh = (Mesh)FileFormat.Draco.Decode(draco);
```

### انظر أيضًا

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)


