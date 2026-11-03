---
title: "DracoFormat.Encode"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "طريقة DracoFormat. ترميز الكيان إلى الدفق المحدد"
type: docs
weight: 20
url: /ar/net/aspose.threed.formats/dracoformat/encode/
---
## Encode(Entity, Stream, DracoSaveOptions) {#encode_1}

ترميز الكيان إلى الدفق المحدد

```csharp
public void Encode(Entity entity, Stream stream, DracoSaveOptions options = null)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| الكيان | الكيان | الكيان المراد ترميزه |
| تدفق | تدفق | الدفق الذي ستُكتب إليه البيانات المشفرة |
| الخيارات | DracoSaveOptions | خيارات إضافية لترميز سحابة النقاط |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| IOException | يُرمى عندما يفشل القراءة من الدفق |

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
| الكيان | الكيان | الكيان المراد ترميزه |
| fileName | String | اسم الملف المراد كتابته |
| الخيارات | DracoSaveOptions | خيارات إضافية لترميز سحابة النقاط |

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

* class [Entity](../../../aspose.threed/entity/)
* class [DracoSaveOptions](../../dracosaveoptions/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)

---

## Encode(Entity, DracoSaveOptions) {#encode}

ترميز الكيان إلى بيانات دراكو الخام

```csharp
public byte[] Encode(Entity entity, DracoSaveOptions options = null)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| الكيان | الكيان | الكيان المراد ترميزه |
| الخيارات | DracoSaveOptions | خيارات إضافية لترميز سحابة النقاط |

### قيمة الإرجاع

بيانات دراكو المشفرة ممثلة بالبايتات

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

* class [Entity](../../../aspose.threed/entity/)
* class [DracoSaveOptions](../../dracosaveoptions/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)


