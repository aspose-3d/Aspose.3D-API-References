---
title: "الفئة PlyFormat"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Formats.PlyFormat. صيغة PLY"
type: docs
weight: 1430
url: /ar/net/aspose.threed.formats/plyformat/
---
## PlyFormat class

تنسيق PLY.

```csharp
public class PlyFormat : FileFormat
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
| [Decode](../../aspose.threed.formats/plyformat/decode/#decode)(Stream) | فك تشفير سحابة نقطية أو شبكة من الدفق المحدد. |
| [Decode](../../aspose.threed.formats/plyformat/decode/#decode_2)(string) | فك تشفير سحابة نقطية أو شبكة من الدفق المحدد. |
| [Decode](../../aspose.threed.formats/plyformat/decode/#decode_1)(Stream, PlyLoadOptions) | فك تشفير سحابة نقطية أو شبكة من الدفق المحدد. |
| [Decode](../../aspose.threed.formats/plyformat/decode/#decode_3)(string, PlyLoadOptions) | فك تشفير سحابة نقطية أو شبكة من الدفق المحدد. |
| [Encode](../../aspose.threed.formats/plyformat/encode/#encode)(Entity, Stream) | تشفير الكيان وحفظ النتيجة في الدفق. |
| [Encode](../../aspose.threed.formats/plyformat/encode/#encode_2)(Entity, string) | تشفير الكيان وحفظ النتيجة في ملف خارجي. |
| [Encode](../../aspose.threed.formats/plyformat/encode/#encode_1)(Entity, Stream, PlySaveOptions) | تشفير الكيان وحفظ النتيجة في الدفق. |
| [Encode](../../aspose.threed.formats/plyformat/encode/#encode_3)(Entity, string, PlySaveOptions) | تشفير الكيان وحفظ النتيجة في ملف خارجي. |
| override [ToString](../../aspose.threed/fileformat/tostring/)() | تحويل الصيغ إلى سلسلة |

## أمثلة

الكود التالي يوضح كيفية تشفير شبكة إلى ملف PLY:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//تشفير شبكة إلى صيغة PLY
FileFormat.PLY.Encode(mesh, "sphere.ply");
```

الكود التالي يوضح كيفية فك تشفير شبكة من ملف PLY:

```csharp
//إنشاء ملف اختبار للفك
FileFormat.PLY.Encode(new Sphere(), "sphere.ply");
//فك تشفير الملف
var mesh = (Mesh)FileFormat.PLY.Decode("sphere.ply")
```

### انظر أيضًا

* class [FileFormat](../../aspose.threed/fileformat/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


