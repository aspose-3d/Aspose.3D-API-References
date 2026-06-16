---
title: "DracoFormat.Encode"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة DracoFormat. تشفير الكيان إلى الدفق المحدد"
type: docs
weight: 20
url: /ar/net/aspose.threed.formats/dracoformat/encode/
---
## Encode(Entity, Stream, DracoSaveOptions) {#encode_1}

ترميز الكيان إلى التدفق المحدد

```csharp
public void Encode(Entity entity, Stream stream, DracoSaveOptions options = null)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| كيان | كيان | الكيان المراد ترميزه |
| stream | Stream | الدفق الذي سيُكتب إليه البيانات المشفرة |
| خيارات | DracoSaveOptions | خيارات إضافية لترميز سحابة النقاط |

### استثناءات

| استثناء | شرط |
| --- | --- |
| IOException | يُرمى عند الفشل في القراءة من الدفق |

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

* class [Entity](../../../aspose.threed/entity/)
* class [DracoSaveOptions](../../dracosaveoptions/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)

---

## Encode(Entity, string, DracoSaveOptions) {#encode_2}

ترميز الكيان إلى الملف المحدد

```csharp
public void Encode(Entity entity, string fileName, DracoSaveOptions options = null)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| كيان | كيان | الكيان المراد ترميزه |
| fileName | سلسلة | اسم الملف الذي سيُكتب |
| خيارات | DracoSaveOptions | خيارات إضافية لترميز سحابة النقاط |

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

* class [Entity](../../../aspose.threed/entity/)
* class [DracoSaveOptions](../../dracosaveoptions/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)

---

## Encode(Entity, DracoSaveOptions) {#encode}

ترميز الكيان إلى بيانات Draco الخام

```csharp
public byte[] Encode(Entity entity, DracoSaveOptions options = null)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| كيان | كيان | الكيان المراد ترميزه |
| خيارات | DracoSaveOptions | خيارات إضافية لترميز سحابة النقاط |

### قيمة الإرجاع

بيانات الدراكو المشفرة ممثلة بالبايتات

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

* class [Entity](../../../aspose.threed/entity/)
* class [DracoSaveOptions](../../dracosaveoptions/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)


