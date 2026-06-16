---
title: "الفئة DracoFormat"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Formats.DracoFormat. تنسيق Google Draco"
type: docs
weight: 1150
url: /ar/net/aspose.threed.formats/dracoformat/
---
## DracoFormat class

تنسيق Google Draco

```csharp
public class DracoFormat : FileFormat
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
| [Decode](../../aspose.threed.formats/dracoformat/decode/#decode)(byte[]) | فك تشفير سحابة النقاط أو الشبكة من بيانات الذاكرة |
| [Decode](../../aspose.threed.formats/dracoformat/decode/#decode_1)(string) | فك تشفير سحابة النقاط أو الشبكة من اسم الملف المحدد |
| [Encode](../../aspose.threed.formats/dracoformat/encode/#encode)(Entity, DracoSaveOptions) | ترميز الكيان إلى بيانات Draco الخام |
| [Encode](../../aspose.threed.formats/dracoformat/encode/#encode_1)(Entity, Stream, DracoSaveOptions) | ترميز الكيان إلى التدفق المحدد |
| [Encode](../../aspose.threed.formats/dracoformat/encode/#encode_2)(Entity, string, DracoSaveOptions) | ترميز الكيان إلى الملف المحدد |
| override [ToString](../../aspose.threed/fileformat/tostring/)() | تحويل الصيغ إلى سلسلة |

## أمثلة

الكود التالي يوضح كيفية ترميز وفك ترميز Mesh إلى/من مصفوفة بايت:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//ترميز الشبكة إلى تنسيق Draco
byte[] draco = FileFormat.Draco.Encode(mesh);
//فك ترميز الشبكة من تنسيق Draco
Mesh decodedMesh = (Mesh)FileFormat.Draco.Decode(draco);
```

### انظر أيضًا

* class [FileFormat](../../aspose.threed/fileformat/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


