---
title: "الفئة FbxSaveOptions"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Formats.FbxSaveOptions. خيارات الحفظ لملف Fbx"
type: docs
weight: 1180
url: /ar/net/aspose.threed.formats/fbxsaveoptions/
---
## FbxSaveOptions class

خيارات الحفظ لملف Fbx.

```csharp
public class FbxSaveOptions : SaveOptions
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [FbxSaveOptions](fbxsaveoptions/#constructor)(FileContentType) | تهيئة `FbxSaveOptions` باستخدام أحدث نسخة مدعومة. |
| [FbxSaveOptions](fbxsaveoptions/#constructor_1)(FileFormat) | يُهيئ `FbxSaveOptions` |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [EmbedTextures](../../aspose.threed.formats/fbxsaveoptions/embedtextures/) { get; set; } | يحصل أو يعيّن ما إذا كان سيتم تضمين الملمس في ملف الإخراج النهائي. سيحاول مُصدّر FBX العثور على البيانات الخام للملمس من [`FileSystem`](../ioconfig/filesystem/)، وتضمين الملف في ملف FBX النهائي. القيمة الافتراضية هي false. |
| [EnableCompression](../../aspose.threed.formats/fbxsaveoptions/enablecompression/) { get; set; } | ضغط البيانات الثنائية الكبيرة في ملف FBX (مثل بيانات الرسوم المتحركة، نقاط التحكم، بيانات عناصر الرؤوس، الفهارس)، القيمة الافتراضية هي true. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | يحصل أو يضبط الترميز الافتراضي للملفات النصية. القيمة الافتراضية هي null مما يعني أن المستورد/المصدر سيقرر أي ترميز يستخدم. |
| [ExportLegacyMaterialProperties](../../aspose.threed.formats/fbxsaveoptions/exportlegacymaterialproperties/) { get; set; } | يحصل أو يعيّن ما إذا كان سيتم تصدير خصائص المواد القديمة، المستخدمة للتوافق العكسي. يتم تشغيل هذا الخيار بشكل افتراضي. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | محاولة نسخ القوام المستخدمة في المشهد إلى دليل الإخراج. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | يحصل على تنسيق الملف المحدد في خيار الحفظ/التحميل الحالي. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | اسم ملف المشهد المُصدّر/المستورد. هذا اختياري، لكنه مفيد عند تسلسل الأصول الخارجية مثل مادة OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | السماح للمستخدم بالتعامل مع كيفية إدارة التبعيات الخارجية أثناء التحميل/الحفظ. |
| [FoldRepeatedCurveData](../../aspose.threed.formats/fbxsaveoptions/foldrepeatedcurvedata/) { get; set; } | يحصل أو يعيّن ما إذا كان سيتم إعادة استخدام بيانات المنحنى المتكررة بزيادة عدد المراجع للبيانات الأخيرة. |
| [GenerateVertexElementMaterial](../../aspose.threed.formats/fbxsaveoptions/generatevertexelementmaterial/) { get; set; } | يحصل أو يعيّن ما إذا كان سيتم دائمًا إنشاء [`VertexElementMaterial`](../../aspose.threed.entities/vertexelementmaterial/) للهياكل إذا كان العقدة المرفقة تحتوي على مواد. يتم إيقاف هذا الخيار بشكل افتراضي. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | بعض الملفات مثل OBJ تعتمد على ملف خارجي، مسارات البحث ستسمح لـ Aspose.3D بالبحث عن الملف الخارجي للتحميل. |
| [ReusePrimitiveMesh](../../aspose.threed.formats/fbxsaveoptions/reuseprimitivemesh/) { get; set; } | إعادة استخدام الشبكة للأشكال الأولية ذات المعلمات نفسها، سيؤدي ذلك إلى تقليل حجم مخرجات FBX بشكل كبير عندما يتم بناء المشهد بمجموعة كبيرة من الأشكال الأولية (مثل المستوردة من ملفات CAD). القيمة الافتراضية هي false |
| [VideoForTexture](../../aspose.threed.formats/fbxsaveoptions/videofortexture/) { get; set; } | يحصل أو يعيّن ما إذا كان سيتم إنشاء مثيل فيديو لـ [`Texture`](../../aspose.threed.shading/texture/) عند التصدير كـ FBX. |

### انظر أيضًا

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


