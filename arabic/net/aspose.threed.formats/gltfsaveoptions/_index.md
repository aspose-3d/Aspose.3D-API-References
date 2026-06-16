---
title: "الفئة GltfSaveOptions"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Formats.GltfSaveOptions. خيارات الحفظ لتنسيق glTF"
type: docs
weight: 1280
url: /ar/net/aspose.threed.formats/gltfsaveoptions/
---
## GltfSaveOptions class

خيارات الحفظ لتنسيق glTF.

```csharp
public class GltfSaveOptions : SaveOptions
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [GltfSaveOptions](gltfsaveoptions/#constructor)(FileContentType) | منشئ `GltfSaveOptions` |
| [GltfSaveOptions](gltfsaveoptions/#constructor_1)(FileFormat) | منشئ `GltfSaveOptions` |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ApplyUnitScale](../../aspose.threed.formats/gltfsaveoptions/applyunitscale/) { get; set; } | تطبيق [`UnitScaleFactor`](../../aspose.threed/assetinfo/unitscalefactor/) على الشبكة. القيمة الافتراضية هي false. |
| [BufferFile](../../aspose.threed.formats/gltfsaveoptions/bufferfile/) { get; set; } | اسم ملف المخزن المؤقت الخارجي المستخدم لتخزين البيانات الثنائية. إذا لم يتم تحديد هذا الملف، سيقوم Aspose.3D بإنشاء اسم لك. يتم تجاهل ذلك عند تصدير glTF في الوضع الثنائي. |
| [DracoCompression](../../aspose.threed.formats/gltfsaveoptions/dracocompression/) { get; set; } | يحصل أو يعيّن ما إذا كان سيتم تمكين ضغط draco |
| [EmbedAssets](../../aspose.threed.formats/gltfsaveoptions/embedassets/) { get; set; } | تضمين جميع الأصول الخارجية كـ base64 في ملف واحد بوضع ASCII، القيمة الافتراضية هي false. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | يحصل أو يضبط الترميز الافتراضي للملفات النصية. القيمة الافتراضية هي null مما يعني أن المستورد/المصدر سيقرر أي ترميز يستخدم. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | محاولة نسخ القوام المستخدمة في المشهد إلى دليل الإخراج. |
| [ExternalDracoEncoder](../../aspose.threed.formats/gltfsaveoptions/externaldracoencoder/) { get; set; } | استخدام مُشفّر draco الخارجي لتسريع سرعة ضغط draco. |
| [FallbackNormal](../../aspose.threed.formats/gltfsaveoptions/fallbacknormal/) { get; set; } | عند اكتشاف مُصدّر GLTF2 لِعادي غير صالح، سيتم استخدام هذا بدلاً من قيمته الأصلية لتجاوز التحقق. القيمة الافتراضية هي (0, 1, 0) |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | يحصل على تنسيق الملف المحدد في خيار الحفظ/التحميل الحالي. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | اسم ملف المشهد المُصدّر/المستورد. هذا اختياري، لكنه مفيد عند تسلسل الأصول الخارجية مثل مادة OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | السماح للمستخدم بالتعامل مع كيفية إدارة التبعيات الخارجية أثناء التحميل/الحفظ. |
| [FlipTexCoordV](../../aspose.threed.formats/gltfsaveoptions/fliptexcoordv/) { get; set; } | قلب مكوّن إحداثي النسيج v(t)، القيمة الافتراضية هي true. |
| [ImageFormat](../../aspose.threed.formats/gltfsaveoptions/imageformat/) { get; set; } | يدعم glTF القياسي فقط PNG/JPG كصيغة نسيج، هذا الخيار سيوجه كيفية تحويل Aspose.3D للصور غير القياسية إلى صيغة مدعومة أثناء التصدير. القيمة الافتراضية هي Png |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | بعض الملفات مثل OBJ تعتمد على ملف خارجي، مسارات البحث ستسمح لـ Aspose.3D بالبحث عن الملف الخارجي للتحميل. |
| [MaterialConverter](../../aspose.threed.formats/gltfsaveoptions/materialconverter/) { get; set; } | محول مخصص لتحويل مادة الهندسة إلى مادة PBR. إذا لم يتم تعيينه، سيقوم مُصدّر glTF 2.0 تلقائيًا بتحويل المادة القياسية إلى مادة PBR. القيمة الافتراضية هي null. تُستخدم هذه الخاصية عند تصدير مشهد إلى ملف glTF 2.0. |
| [PrettyPrint](../../aspose.threed.formats/gltfsaveoptions/prettyprint/) { get; set; } | محتوى JSON لملف GLTF مُنظم لتسهيل القراءة البشرية، القيمة الافتراضية هي false |
| [SaveExtras](../../aspose.threed.formats/gltfsaveoptions/saveextras/) { get; set; } | حفظ الخصائص الديناميكية لكائن المشهد في حقول 'extra' في ملف glTF المُولَّد. هذا مفيد لتوفير بيانات خاصة بالتطبيق. القيمة الافتراضية هي false. |
| [UseCommonMaterials](../../aspose.threed.formats/gltfsaveoptions/usecommonmaterials/) { get; set; } | تسلسل المواد باستخدام امتدادات مادة KHR الشائعة، القيمة الافتراضية هي false. ضبط هذا على false سيتسبب في تصدير Aspose.3D لمجموعة من شادر القمة/القطعة إذا كان ExportShaders مفعلاً. |

### انظر أيضًا

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


