---
title: "PdfFormat.Extract"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة PdfFormat. استخراج المحتوى ثلاثي الأبعاد الخام من ملف PDF"
type: docs
weight: 10
url: /ar/net/aspose.threed.formats/pdfformat/extract/
---
## Extract(string, byte[]) {#extract_1}

استخراج المحتوى ثلاثي الأبعاد الخام من ملف PDF.

```csharp
public List<byte[]> Extract(string fileName, byte[] password = null)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fileName | سلسلة | اسم ملف PDF الإدخال |
| password | Byte[] | كلمة مرور ملف PDF |

### قيمة الإرجاع

قائمة بجميع المحتويات ثلاثية الأبعاد بالبايتات، بما في ذلك الصيغ التي لا يدعمها Aspose.3D.

## أمثلة

الكود التالي يوضح كيفية استخراج جميع المحتويات ثلاثية الأبعاد الخام من ملف PDF ثلاثي الأبعاد، وكتابتها إلى ملفات.

```csharp
var raw3DContents = FileFormat.PDF.Extract("input.pdf");
for (int i = 0; i < raw3DContents.Count; i++)
{
    File.WriteAllBytes("raw-3d-" + i, raw3DContents[i]);
}
```

### انظر أيضًا

* class [PdfFormat](../)
* namespace [Aspose.ThreeD.Formats](../../pdfformat/)
* assembly [Aspose.3D](../../../)

---

## Extract(Stream, byte[]) {#extract}

استخراج المحتوى ثلاثي الأبعاد الخام من تدفق PDF.

```csharp
public List<byte[]> Extract(Stream stream, byte[] password = null)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| stream | Stream | دفق ملف PDF الإدخال |
| password | Byte[] | كلمة مرور ملف PDF |

### قيمة الإرجاع

قائمة بجميع المحتويات ثلاثية الأبعاد بالبايتات، بما في ذلك الصيغ التي لا يدعمها Aspose.3D.

## أمثلة

الكود التالي يوضح كيفية استخراج جميع المحتويات ثلاثية الأبعاد الخام من ملف PDF ثلاثي الأبعاد، وكتابتها إلى ملفات.

```csharp
var raw3DContents = FileFormat.PDF.Extract("input.pdf");
for (int i = 0; i < raw3DContents.Count; i++)
{
    File.WriteAllBytes("raw-3d-" + i, raw3DContents[i]);
}
```

### انظر أيضًا

* class [PdfFormat](../)
* namespace [Aspose.ThreeD.Formats](../../pdfformat/)
* assembly [Aspose.3D](../../../)


