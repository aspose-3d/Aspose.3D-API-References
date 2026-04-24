---
title: الفئة Microsoft3MFSaveOptions
second_title: مرجع API Aspose.3D لـ .NET
description: الفئة Aspose.ThreeD.Formats.Microsoft3MFSaveOptions. خيارات الحفظ لملف Microsoft 3MF
type: docs
weight: 1350
url: /ar/net/aspose.threed.formats/microsoft3mfsaveoptions/
---
## Microsoft3MFSaveOptions class

خيارات الحفظ لملف Microsoft 3MF.

```csharp
public class Microsoft3MFSaveOptions : SaveOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Microsoft3MFSaveOptions](microsoft3mfsaveoptions/)() | إنشاء `Microsoft3MFSaveOptions` |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BuildAll](../../aspose.threed.formats/microsoft3mfsaveoptions/buildall/) { get; set; } | وضع علامة على جميع الأشكال الهندسية في المشهد لتكون قابلة للطباعة. أو يمكنك يدويًا وضع علامة على العقدة لتكون قابلة للطباعة عبر [`SetBuildable`](../microsoft3mfformat/setbuildable/) القيمة الافتراضية هي true |
| [EnableCompression](../../aspose.threed.formats/microsoft3mfsaveoptions/enablecompression/) { get; set; } | فعّل الضغط على ملف 3mf الناتج. القيمة الافتراضية هي true |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | يحصل أو يضبط الترميز الافتراضي للملفات النصية. القيمة الافتراضية هي null مما يعني أن المستورد/المصدر سيقرر أي ترميز يستخدم. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | حاول نسخ القوام المستخدمة في المشهد إلى دليل الإخراج. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | يحصل على تنسيق الملف المحدد في خيار الحفظ/التحميل الحالي. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | اسم الملف للمشهد المُصدّر/المستورد. هذا اختياري، لكنه مفيد عند تسلسل الأصول الخارجية مثل مادة OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | السماح للمستخدم بالتعامل مع كيفية إدارة الاعتمادات الخارجية أثناء التحميل/الحفظ. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | بعض الملفات مثل OBJ تعتمد على ملفات خارجية، سيسمح مسارات البحث لـ Aspose.3D بالعثور على الملف الخارجي للتحميل. |

### انظر أيضًا

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


