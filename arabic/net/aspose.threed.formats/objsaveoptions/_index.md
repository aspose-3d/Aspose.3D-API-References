---
title: "الفئة ObjSaveOptions"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Formats.ObjSaveOptions. خيارات الحفظ لملف wavefront obj."
type: docs
weight: 1370
url: /ar/net/aspose.threed.formats/objsaveoptions/
---
## ObjSaveOptions class

خيارات الحفظ لملف wavefront obj.

```csharp
public class ObjSaveOptions : SaveOptions
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [ObjSaveOptions](objsaveoptions/)() | منشئ `ObjSaveOptions` |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ApplyUnitScale](../../aspose.threed.formats/objsaveoptions/applyunitscale/) { get; set; } | تطبيق [`UnitScaleFactor`](../../aspose.threed/assetinfo/unitscalefactor/) على الشبكة. القيمة الافتراضية هي false. |
| [AxisSystem](../../aspose.threed.formats/objsaveoptions/axissystem/) { get; set; } | يحصل أو يعيّن نظام المحاور في الملف المُصدَّر. |
| [EnableMaterials](../../aspose.threed.formats/objsaveoptions/enablematerials/) { get; set; } | يحصل أو يعيّن ما إذا كان سيتم استيراد/تصدير المواد لكل كائن. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | يحصل أو يضبط الترميز الافتراضي للملفات النصية. القيمة الافتراضية هي null مما يعني أن المستورد/المصدر سيقرر أي ترميز يستخدم. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | محاولة نسخ القوام المستخدمة في المشهد إلى دليل الإخراج. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | يحصل على تنسيق الملف المحدد في خيار الحفظ/التحميل الحالي. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | اسم ملف المشهد المُصدّر/المستورد. هذا اختياري، لكنه مفيد عند تسلسل الأصول الخارجية مثل مادة OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | السماح للمستخدم بالتعامل مع كيفية إدارة التبعيات الخارجية أثناء التحميل/الحفظ. |
| [FlipCoordinateSystem](../../aspose.threed.formats/objsaveoptions/flipcoordinatesystem/) { get; set; } | يحصل أو يضبط ما إذا كان يتم عكس نظام الإحداثيات لنقاط التحكم/العمود أثناء الاستيراد/التصدير. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | بعض الملفات مثل OBJ تعتمد على ملف خارجي، مسارات البحث ستسمح لـ Aspose.3D بالبحث عن الملف الخارجي للتحميل. |
| [PointCloud](../../aspose.threed.formats/objsaveoptions/pointcloud/) { get; set; } | يحصل أو يعيّن العلامة التي تحدد ما إذا كان المُصدِّر يجب أن يصدر المشهد كسحابة نقطية (بدون بنية طوبولوجية)، القيمة الافتراضية هي false. |
| [SerializeW](../../aspose.threed.formats/objsaveoptions/serializew/) { get; set; } | يحصل أو يعيّن ما إذا كان سيتم تسلسل المكوّن W في موضع رأس النموذج. |
| [Verbose](../../aspose.threed.formats/objsaveoptions/verbose/) { get; set; } | يحصل أو يعيّن ما إذا كان سيتم إنشاء تعليقات لكل قسم. |

### انظر أيضًا

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


