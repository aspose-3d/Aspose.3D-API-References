---
title: "فئة PlySaveOptions"
second_title: "مرجع Aspose.3D for .NET API"
description: "Aspose.ThreeD.Formats.PlySaveOptions فئة. خيارات الحفظ لتصدير المشهد كملف PLY"
type: docs
weight: 1450
url: /ar/net/aspose.threed.formats/plysaveoptions/
---
## PlySaveOptions class

خيارات الحفظ لتصدير المشهد كملف PLY.

```csharp
public class PlySaveOptions : SaveOptions
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [PlySaveOptions](plysaveoptions/#constructor)() | منشئ `PlySaveOptions` |
| [PlySaveOptions](plysaveoptions/#constructor_1)(FileContentType) | منشئ `PlySaveOptions` |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AxisSystem](../../aspose.threed.formats/plysaveoptions/axissystem/) { get; set; } | يحصل أو يضبط نظام المحاور في ملف STL المُصدَّر. |
| [ColorComponents](../../aspose.threed.formats/plysaveoptions/colorcomponents/) { get; set; } | أسماء المكوّنات للون القمة، القيمة الافتراضية هي ("red", "green", "blue") |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | يحصل أو يضبط الترميز الافتراضي للملفات النصية. القيمة الافتراضية هي null مما يعني أن المستورد/المصدر سيقرر أي ترميز يستخدم. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | محاولة نسخ القوام المستخدمة في المشهد إلى دليل الإخراج. |
| [FaceElement](../../aspose.threed.formats/plysaveoptions/faceelement/) { get; set; } | اسم العنصر لبيانات الوجه، القيمة الافتراضية هي "face" |
| [FaceProperty](../../aspose.threed.formats/plysaveoptions/faceproperty/) { get; set; } | اسم الخاصية لبيانات الوجه، القيمة الافتراضية هي "vertex_index" |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | يحصل على تنسيق الملف المحدد في خيار الحفظ/التحميل الحالي. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | اسم ملف المشهد المُصدّر/المستورد. هذا اختياري، لكنه مفيد عند تسلسل الأصول الخارجية مثل مادة OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | السماح للمستخدم بالتعامل مع كيفية إدارة التبعيات الخارجية أثناء التحميل/الحفظ. |
| [FlipCoordinate](../../aspose.threed.formats/plysaveoptions/flipcoordinate/) { get; set; } | قلب الإحداثيات أثناء حفظ المشهد، القيمة الافتراضية هي true |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | بعض الملفات مثل OBJ تعتمد على ملف خارجي، مسارات البحث ستسمح لـ Aspose.3D بالبحث عن الملف الخارجي للتحميل. |
| [NormalComponents](../../aspose.threed.formats/plysaveoptions/normalcomponents/) { get; set; } | أسماء المكوّنات للبيانات العادية، القيمة الافتراضية هي ("nx", "ny", "nz") |
| [PointCloud](../../aspose.threed.formats/plysaveoptions/pointcloud/) { get; set; } | تصدير المشهد كسحابة نقاط، القيمة الافتراضية هي false. |
| [PositionComponents](../../aspose.threed.formats/plysaveoptions/positioncomponents/) { get; set; } | أسماء المكوّنات لبيانات الموقع، القيمة الافتراضية هي ("x", "y", "z") |
| [TextureCoordinateComponents](../../aspose.threed.formats/plysaveoptions/texturecoordinatecomponents/) { get; set; } | أسماء المكوّنات لبيانات إحداثيات النسيج، القيمة الافتراضية هي ("u", "v") |
| [VertexElement](../../aspose.threed.formats/plysaveoptions/vertexelement/) { get; set; } | اسم العنصر لبيانات القمة، القيمة الافتراضية هي "vertex" |

### انظر أيضًا

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


