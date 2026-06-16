---
title: "PlyFormat.Encode"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة PlyFormat. تشفير الكيان وحفظ النتيجة في الدفق"
type: docs
weight: 20
url: /ar/net/aspose.threed.formats/plyformat/encode/
---
## Encode(Entity, Stream) {#encode}

تشفير الكيان وحفظ النتيجة في الدفق.

```csharp
public void Encode(Entity entity, Stream stream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| كيان | كيان | الكيان المراد تشفيره |
| stream | Stream | الدفق للكتابة إليه، هذه الطريقة لن تغلق هذا الدفق |

## أمثلة

الكود التالي يوضح كيفية تشفير شبكة إلى ملف PLY:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//تشفير شبكة إلى صيغة PLY
FileFormat.PLY.Encode(mesh, "sphere.ply");
```

### انظر أيضًا

* class [Entity](../../../aspose.threed/entity/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Encode(Entity, Stream, PlySaveOptions) {#encode_1}

تشفير الكيان وحفظ النتيجة في الدفق.

```csharp
public void Encode(Entity entity, Stream stream, PlySaveOptions opt)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| كيان | كيان | الكيان المراد تشفيره |
| stream | Stream | الدفق للكتابة إليه، هذه الطريقة لن تغلق هذا الدفق |
| opt | PlySaveOptions | خيارات الحفظ |

## أمثلة

الكود التالي يوضح كيفية تشفير شبكة إلى ملف PLY:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//تشفير شبكة إلى صيغة PLY
FileFormat.PLY.Encode(mesh, "sphere.ply");
```

### انظر أيضًا

* class [Entity](../../../aspose.threed/entity/)
* class [PlySaveOptions](../../plysaveoptions/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Encode(Entity, string) {#encode_2}

تشفير الكيان وحفظ النتيجة في ملف خارجي.

```csharp
public void Encode(Entity entity, string fileName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| كيان | كيان | الكيان المراد تشفيره |
| fileName | سلسلة | الملف المراد الكتابة إليه |

## أمثلة

الكود التالي يوضح كيفية تشفير شبكة إلى ملف PLY:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//تشفير شبكة إلى صيغة PLY
FileFormat.PLY.Encode(mesh, "sphere.ply");
```

### انظر أيضًا

* class [Entity](../../../aspose.threed/entity/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Encode(Entity, string, PlySaveOptions) {#encode_3}

تشفير الكيان وحفظ النتيجة في ملف خارجي.

```csharp
public void Encode(Entity entity, string fileName, PlySaveOptions opt)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| كيان | كيان | الكيان المراد تشفيره |
| fileName | سلسلة | الملف المراد الكتابة إليه |
| opt | PlySaveOptions | خيارات الحفظ |

## أمثلة

الكود التالي يوضح كيفية تشفير شبكة إلى ملف PLY:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//تشفير شبكة إلى صيغة PLY
FileFormat.PLY.Encode(mesh, "sphere.ply");
```

### انظر أيضًا

* class [Entity](../../../aspose.threed/entity/)
* class [PlySaveOptions](../../plysaveoptions/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)


