---
title: "FileFormat.Detect"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "طريقة FileFormat. اكتشف تنسيق الملف من تدفق البيانات اسم الملف اختياري لتخمين الأنواع التي لا تحتوي على رأس سحري"
type: docs
weight: 460
url: /ar/net/aspose.threed/fileformat/detect/
---
## Detect(Stream, string) {#detect}

اكتشف تنسيق الملف من تدفق البيانات، اسم الملف اختياري لتخمين الأنواع التي لا تحتوي على رأس سحري.

```csharp
public static FileFormat Detect(Stream stream, string fileName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| تدفق | تدفق | تدفق يحتوي على البيانات للكشف |
| fileName | String | اسم الملف الأصلي للبيانات، يُستخدم كإشارة. |

### قيمة الإرجاع

ال [`FileFormat`](../) المثيل للنّوع المكتشف أو null إذا فشل.

### الاستثناءات

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

اكتشف تنسيق الملف من اسم الملف، يجب أن يكون الملف قابلاً للقراءة حتى يتمكن Aspose.3D من اكتشاف تنسيق الملف عبر رأس الملف.

```csharp
public static FileFormat Detect(string fileName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fileName | String | المسار إلى الملف لاكتشاف تنسيق الملف. |

### قيمة الإرجاع

ال [`FileFormat`](../) المثيل للنّوع المكتشف أو null إذا فشل.

### الاستثناءات

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


