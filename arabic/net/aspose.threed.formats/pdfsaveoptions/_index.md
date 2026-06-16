---
title: "الفئة PdfSaveOptions"
second_title: "مرجع Aspose.3D for .NET API"
description: "Aspose.ThreeD.Formats.PdfSaveOptions class. خيارات الحفظ في تصدير PDF"
type: docs
weight: 1420
url: /ar/net/aspose.threed.formats/pdfsaveoptions/
---
## PdfSaveOptions class

خيارات الحفظ في تصدير PDF.

```csharp
public class PdfSaveOptions : SaveOptions
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | منشئ `PdfSaveOptions` |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AuxiliaryColor](../../aspose.threed.formats/pdfsaveoptions/auxiliarycolor/) { get; set; } | يحصل أو يضبط اللون المساعد الذي سيُستخدم عند عرض المحتوى ثلاثي الأبعاد. تفسير هذا اللون يعتمد على [`RenderMode`](./rendermode/) |
| [BackgroundColor](../../aspose.threed.formats/pdfsaveoptions/backgroundcolor/) { get; set; } | لون الخلفية للعرض ثلاثي الأبعاد في ملف PDF. |
| [EmbedTextures](../../aspose.threed.formats/pdfsaveoptions/embedtextures/) { get; set; } | دمج القوام الخارجية في ملف PDF، القيمة الافتراضية هي false. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | يحصل أو يضبط الترميز الافتراضي للملفات النصية. القيمة الافتراضية هي null مما يعني أن المستورد/المصدر سيقرر أي ترميز يستخدم. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | محاولة نسخ القوام المستخدمة في المشهد إلى دليل الإخراج. |
| [FaceColor](../../aspose.threed.formats/pdfsaveoptions/facecolor/) { get; set; } | يحصل أو يضبط لون الوجه الذي سيُستخدم عند عرض المحتوى ثلاثي الأبعاد. هذا ذو صلة فقط عندما يكون لدى [`RenderMode`](./rendermode/) قيمة Illustration. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | يحصل على تنسيق الملف المحدد في خيار الحفظ/التحميل الحالي. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | اسم ملف المشهد المُصدّر/المستورد. هذا اختياري، لكنه مفيد عند تسلسل الأصول الخارجية مثل مادة OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | السماح للمستخدم بالتعامل مع كيفية إدارة التبعيات الخارجية أثناء التحميل/الحفظ. |
| [FlipCoordinateSystem](../../aspose.threed.formats/pdfsaveoptions/flipcoordinatesystem/) { get; set; } | يحصل أو يضبط لعكس نظام إحداثيات المشهد أثناء التصدير. |
| [LightingScheme](../../aspose.threed.formats/pdfsaveoptions/lightingscheme/) { get; set; } | LightingScheme يحدد الإضاءة التي تُطبق على الأعمال ثلاثية الأبعاد. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | بعض الملفات مثل OBJ تعتمد على ملف خارجي، مسارات البحث ستسمح لـ Aspose.3D بالبحث عن الملف الخارجي للتحميل. |
| [RenderMode](../../aspose.threed.formats/pdfsaveoptions/rendermode/) { get; set; } | وضعية العرض تحدد النمط الذي يُعرض به العمل ثلاثي الأبعاد. |

### انظر أيضًا

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


