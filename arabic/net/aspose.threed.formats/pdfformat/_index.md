---
title: "الفئة PdfFormat"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Formats.PdfFormat. تنسيق المستند القابل للنقل من Adobe"
type: docs
weight: 1380
url: /ar/net/aspose.threed.formats/pdfformat/
---
## PdfFormat class

تنسيق المستند القابل للنقل من Adobe

```csharp
public class PdfFormat : FileFormat
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CanExport](../../aspose.threed/fileformat/canexport/) { get; } | يحصل ما إذا كان Aspose.3D يدعم تصدير المشهد إلى تنسيق الملف الحالي. |
| [CanImport](../../aspose.threed/fileformat/canimport/) { get; } | يحصل على ما إذا كان Aspose.3D يدعم استيراد المشهد من تنسيق الملف الحالي. |
| [ContentType](../../aspose.threed/fileformat/contenttype/) { get; } | يحصل على نوع محتوى تنسيق الملف |
| [Extension](../../aspose.threed/fileformat/extension/) { get; } | يحصل على اسم الامتداد لهذا النوع. |
| [Extensions](../../aspose.threed/fileformat/extensions/) { get; } | يحصل على أسماء الامتداد لهذا النوع. |
| [FileFormatType](../../aspose.threed/fileformat/fileformattype/) { get; } | يحصل على نوع تنسيق الملف |
| [Version](../../aspose.threed/fileformat/version/) { get; } | يحصل على إصدار تنسيق الملف |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [CreateLoadOptions](../../aspose.threed/fileformat/createloadoptions/)() | إنشاء خيارات تحميل افتراضية لهذا التنسيق |
| [CreateSaveOptions](../../aspose.threed/fileformat/createsaveoptions/)() | إنشاء خيارات حفظ افتراضية لهذا التنسيق |
| [Extract](../../aspose.threed.formats/pdfformat/extract/#extract)(Stream, byte[]) | استخراج المحتوى ثلاثي الأبعاد الخام من تدفق PDF. |
| [Extract](../../aspose.threed.formats/pdfformat/extract/#extract_1)(string, byte[]) | استخراج المحتوى ثلاثي الأبعاد الخام من ملف PDF. |
| [ExtractScene](../../aspose.threed.formats/pdfformat/extractscene/#extractscene_1)(string) | استخراج المشاهد ثلاثية الأبعاد من ملف PDF. |
| [ExtractScene](../../aspose.threed.formats/pdfformat/extractscene/#extractscene)(Stream, byte[]) | استخراج المحتوى ثلاثي الأبعاد الخام من تدفق PDF. |
| [ExtractScene](../../aspose.threed.formats/pdfformat/extractscene/#extractscene_2)(string, byte[]) | استخراج المشاهد ثلاثية الأبعاد من ملف PDF. |
| override [ToString](../../aspose.threed/fileformat/tostring/)() | تحويل الصيغ إلى سلسلة |

## أمثلة

الكود التالي يوضح كيفية استخراج جميع المشاهد ثلاثية الأبعاد المدعومة من ملف PDF ثلاثي الأبعاد، وكتابتها إلى تنسيق obj.

```csharp
var scenes = FileFormat.PDF.ExtractScene("input.pdf");
for(int i = 0; i < scenes.Count; i++) 
{
    scenes[i].Save($"output-{i}.obj");
}
```

### انظر أيضًا

* class [FileFormat](../../aspose.threed/fileformat/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


