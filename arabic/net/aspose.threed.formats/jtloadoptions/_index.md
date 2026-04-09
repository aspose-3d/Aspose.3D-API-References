---
title: الفئة JtLoadOptions
second_title: مرجع API Aspose.3D لـ .NET
description: الفئة Aspose.ThreeD.Formats.JtLoadOptions. خيارات التحميل لـ Siemens JT
type: docs
weight: 1310
url: /ar/net/aspose.threed.formats/jtloadoptions/
---
## JtLoadOptions class

خيارات التحميل لـ Siemens JT

```csharp
public class JtLoadOptions : LoadOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [JtLoadOptions](jtloadoptions/)() | المُنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | يحصل أو يضبط الترميز الافتراضي للملفات النصية. القيمة الافتراضية هي null مما يعني أن المستورد/المصدر سيقرر أي ترميز يستخدم. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | يحصل على تنسيق الملف المحدد في خيار الحفظ/التحميل الحالي. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | اسم الملف للمشهد المُصدّر/المستورد. هذا اختياري، لكنه مفيد عند تسلسل الأصول الخارجية مثل مادة OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | السماح للمستخدم بالتعامل مع كيفية إدارة الاعتمادات الخارجية أثناء التحميل/الحفظ. |
| [LoadPMI](../../aspose.threed.formats/jtloadoptions/loadpmi/) { get; set; } | تحميل معلومات PMI من ملف JT إذا كان ذلك ممكنًا، سيتم حفظ البيانات كخاصية \"PMI\" في [`AssetInfo`](../../aspose.threed/scene/assetinfo/). القيمة الافتراضية هي false. |
| [LoadProperties](../../aspose.threed.formats/jtloadoptions/loadproperties/) { get; set; } | تحميل الخصائص من جدول خصائص JT كخصائص Aspose.3D. القيمة الافتراضية هي false. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | بعض الملفات مثل OBJ تعتمد على ملفات خارجية، سيسمح مسارات البحث لـ Aspose.3D بالعثور على الملف الخارجي للتحميل. |

### انظر أيضًا

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


