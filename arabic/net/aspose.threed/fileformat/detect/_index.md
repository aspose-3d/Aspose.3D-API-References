---
title: "FileFormat.Detect"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة FileFormat. اكتشاف تنسيق الملف من تدفق البيانات؛ اسم الملف اختياري لتخمين الأنواع التي لا تحتوي على رأس سحري"
type: docs
weight: 460
url: /ar/net/aspose.threed/fileformat/detect/
---
## Detect(Stream, string) {#detect}

اكتشاف تنسيق الملف من تدفق البيانات، اسم الملف اختياري لتخمين الأنواع التي لا تحتوي على رأس سحري.

```csharp
public static FileFormat Detect(Stream stream, string fileName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| stream | Stream | دفق يحتوي على البيانات للكشف |
| fileName | سلسلة | اسم الملف الأصلي للبيانات، يُستخدم كدليل. |

### قيمة الإرجاع

مثيل [`FileFormat`](../) للنمط المكتشف أو null إذا فشل.

### استثناءات

| استثناء | شرط |
| --- | --- |
| IOException | استثناء يُرمى عند فشل قراءة البيانات. |

## أمثلة

```csharp
byte[] bytes = new byte[100];//take the bytes from your source
var fmt = FileFormat.Detect(new MemoryStream(bytes), "input-file");
Console.WriteLine($"Input data format: {fmt}");
```

### انظر أيضًا

* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)

---

## Detect(string) {#detect_1}

اكتشاف تنسيق الملف من اسم الملف، يجب أن يكون الملف قابلاً للقراءة حتى يتمكن Aspose.3D من اكتشاف تنسيق الملف عبر رأس الملف.

```csharp
public static FileFormat Detect(string fileName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fileName | سلسلة | المسار إلى الملف لاكتشاف تنسيق الملف. |

### قيمة الإرجاع

مثيل [`FileFormat`](../) للنمط المكتشف أو null إذا فشل.

### استثناءات

| استثناء | شرط |
| --- | --- |
| IOException | استثناء يُرمى عند فشل قراءة البيانات. |

## أمثلة

```csharp
var fmt = FileFormat.Detect("input.fbx");
Console.WriteLine($"Input file format: {fmt}");
```

### انظر أيضًا

* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)


