---
title: "PdfFormat.ExtractScene"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "طريقة PdfFormat. استخراج المشاهد ثلاثية الأبعاد من ملف PDF"
type: docs
weight: 20
url: /ar/net/aspose.threed.formats/pdfformat/extractscene/
---
## ExtractScene(string) {#extractscene_1}

استخراج المشاهد ثلاثية الأبعاد من ملف PDF.

```csharp
public List<Scene> ExtractScene(string fileName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fileName | String | اسم ملف PDF الإدخال |

### قيمة الإرجاع

قائمة المشاهد ثلاثية الأبعاد المفكوكة المدعومة من قبل Aspose.3D

## أمثلة

الكود التالي يوضح كيفية استخراج جميع المشاهد ثلاثية الأبعاد المدعومة من ملف PDF ثلاثي الأبعاد، وكتابتها إلى صيغة obj.

```csharp
var scenes = FileFormat.PDF.ExtractScene("input.pdf");
for(int i = 0; i < scenes.Count; i++) 
{
    scenes[i].Save($"output-{i}.obj");
}
```

### انظر أيضًا

* class [Scene](../../../aspose.threed/scene/)
* class [PdfFormat](../)
* namespace [Aspose.ThreeD.Formats](../../pdfformat/)
* assembly [Aspose.3D](../../../)

---

## ExtractScene(string, byte[]) {#extractscene_2}

استخراج المشاهد ثلاثية الأبعاد من ملف PDF.

```csharp
public List<Scene> ExtractScene(string fileName, byte[] password)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fileName | String | اسم ملف PDF الإدخال |
| كلمة مرور | Byte[] | كلمة مرور ملف PDF |

### قيمة الإرجاع

قائمة المشاهد ثلاثية الأبعاد المفكوكة المدعومة من قبل Aspose.3D

## أمثلة

الكود التالي يوضح كيفية استخراج جميع المشاهد ثلاثية الأبعاد المدعومة من ملف PDF ثلاثي الأبعاد، وكتابتها إلى صيغة obj.

```csharp
var scenes = FileFormat.PDF.ExtractScene("input.pdf");
for(int i = 0; i < scenes.Count; i++) 
{
    scenes[i].Save($"output-{i}.obj");
}
```

### انظر أيضًا

* class [Scene](../../../aspose.threed/scene/)
* class [PdfFormat](../)
* namespace [Aspose.ThreeD.Formats](../../pdfformat/)
* assembly [Aspose.3D](../../../)

---

## ExtractScene(Stream, byte[]) {#extractscene}

استخراج المحتوى ثلاثي الأبعاد الخام من تدفق PDF.

```csharp
public List<Scene> ExtractScene(Stream stream, byte[] password = null)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| تدفق | تدفق | تدفق ملف PDF الإدخال |
| كلمة مرور | Byte[] | كلمة مرور ملف PDF |

### قيمة الإرجاع

قائمة المشاهد ثلاثية الأبعاد المفكوكة المدعومة من قبل Aspose.3D

## أمثلة

الكود التالي يوضح كيفية استخراج جميع المشاهد ثلاثية الأبعاد المدعومة من ملف PDF ثلاثي الأبعاد، وكتابتها إلى صيغة obj.

```csharp
var scenes = FileFormat.PDF.ExtractScene("input.pdf");
for(int i = 0; i < scenes.Count; i++) 
{
    scenes[i].Save($"output-{i}.obj");
}
```

### انظر أيضًا

* class [Scene](../../../aspose.threed/scene/)
* class [PdfFormat](../)
* namespace [Aspose.ThreeD.Formats](../../pdfformat/)
* assembly [Aspose.3D](../../../)


