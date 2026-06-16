---
title: "الفئة UsdSaveOptions"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Formats.UsdSaveOptions. خيارات الحفظ لتنسيقات USD/USDZ"
type: docs
weight: 1540
url: /ar/net/aspose.threed.formats/usdsaveoptions/
---
## UsdSaveOptions class

خيارات الحفظ لتنسيقات USD/USDZ.

```csharp
public class UsdSaveOptions : SaveOptions
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [UsdSaveOptions](usdsaveoptions/#constructor)() | إنشاء `UsdSaveOptions` جديد مع تنسيق [`USD`](../../aspose.threed/fileformat/usd/) |
| [UsdSaveOptions](usdsaveoptions/#constructor_1)(FileFormat) | إنشاء `UsdSaveOptions` جديد مع تنسيق USD/USDZ المحدد. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | يحصل أو يضبط الترميز الافتراضي للملفات النصية. القيمة الافتراضية هي null مما يعني أن المستورد/المصدر سيقرر أي ترميز يستخدم. |
| [ExportMetaData](../../aspose.threed.formats/usdsaveoptions/exportmetadata/) { get; set; } | تصدير خصائص العقدة عبر حقل customData الخاص بـ USD. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | محاولة نسخ القوام المستخدمة في المشهد إلى دليل الإخراج. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | يحصل على تنسيق الملف المحدد في خيار الحفظ/التحميل الحالي. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | اسم ملف المشهد المُصدّر/المستورد. هذا اختياري، لكنه مفيد عند تسلسل الأصول الخارجية مثل مادة OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | السماح للمستخدم بالتعامل مع كيفية إدارة التبعيات الخارجية أثناء التحميل/الحفظ. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | بعض الملفات مثل OBJ تعتمد على ملف خارجي، مسارات البحث ستسمح لـ Aspose.3D بالبحث عن الملف الخارجي للتحميل. |
| [MaterialConverter](../../aspose.threed.formats/usdsaveoptions/materialconverter/) { get; set; } | محول مخصص لتحويل مادة الشكل الهندسي إلى مادة PBR. إذا لم يتم تعيينه، سيقوم مُصدّر USD تلقائيًا بتحويل المادة القياسية إلى مادة PBR. القيمة الافتراضية هي null |
| [PrimitiveToMesh](../../aspose.threed.formats/usdsaveoptions/primitivetomesh/) { get; set; } | تحويل الكيانات الأولية إلى شبكة أثناء التصدير. أو ترميز الكيانات الأولية مباشرة إلى ملف الإخراج (سيتم استخدام تعريف امتداد Aspose للكيانات غير الرسمية مثل Dish و Torus). القيمة الافتراضية هي true. |

### انظر أيضًا

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


