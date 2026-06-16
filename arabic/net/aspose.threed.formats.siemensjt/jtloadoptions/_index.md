---
title: "الفئة JtLoadOptions"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Formats.SiemensJT.JtLoadOptions. خيارات التحميل لـ Siemens JT"
type: docs
weight: 1380
url: /ar/net/aspose.threed.formats.siemensjt/jtloadoptions/
---
## JtLoadOptions class

خيارات التحميل لـ Siemens JT

```csharp
public class JtLoadOptions : LoadOptions
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [JtLoadOptions](jtloadoptions/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | يحصل أو يعيّن الترميز الافتراضي للملفات النصية. القيمة الافتراضية هي null مما يعني أن المستورد/المصدر سيقرر أي ترميز يُستخدم. (موروث من [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | يحصل على تنسيق الملف المحدد في خيار الحفظ/التحميل الحالي. (موروث من [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | اسم الملف للمشهد المُصدّر/المستورد. هذا اختياري، لكنه مفيد عند تسلسل الأصول الخارجية مثل مادة OBJ. (موروث من [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | السماح للمستخدم بالتعامل مع كيفية إدارة التبعيات الخارجية أثناء التحميل/الحفظ. (موروث من [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |
| [LoadPMI](../../aspose.threed.formats.siemensjt/jtloadoptions/loadpmi/) { get; set; } | تحميل معلومات PMI من ملف JT إذا كان ذلك ممكنًا، سيتم حفظ البيانات كخاصية "PMI" لـ [`AssetInfo`](../../aspose.threed/scene/assetinfo/). القيمة الافتراضية هي false. |
| [LoadProperties](../../aspose.threed.formats.siemensjt/jtloadoptions/loadproperties/) { get; set; } | تحميل الخصائص من جدول خصائص JT كخصائص Aspose.3D. القيمة الافتراضية هي false. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | بعض الملفات مثل OBJ تعتمد على ملفات خارجية، سيسمح مسارات البحث لـ Aspose.3D بالبحث عن الملف الخارجي للتحميل. (موروث من [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |

### انظر أيضًا

* class [LoadOptions](../../aspose.threed.formats/loadoptions/)
* namespace [Aspose.ThreeD.Formats.SiemensJT](../../aspose.threed.formats.siemensjt/)
* assembly [Aspose.3D](../../)


