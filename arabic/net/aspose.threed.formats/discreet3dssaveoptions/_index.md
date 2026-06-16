---
title: "فئة Discreet3dsSaveOptions"
second_title: "مرجع Aspose.3D for .NET API"
description: "فئة Aspose.ThreeD.Formats.Discreet3dsSaveOptions. خيارات الحفظ لملف 3DS"
type: docs
weight: 1130
url: /ar/net/aspose.threed.formats/discreet3dssaveoptions/
---
## Discreet3dsSaveOptions class

خيارات الحفظ لملف 3DS.

```csharp
public class Discreet3dsSaveOptions : SaveOptions
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [Discreet3dsSaveOptions](discreet3dssaveoptions/)() | منشئ `Discreet3dsSaveOptions` |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [DuplicatedNameCounterBase](../../aspose.threed.formats/discreet3dssaveoptions/duplicatednamecounterbase/) { get; set; } | العداد المستخدم لإنشاء اسم جديد للأسماء المكررة، القيمة الافتراضية هي 2. |
| [DuplicatedNameCounterFormat](../../aspose.threed.formats/discreet3dssaveoptions/duplicatednamecounterformat/) { get; set; } | تنسيق العداد المكرر، القيمة الافتراضية هي سلسلة فارغة. |
| [DuplicatedNameSeparator](../../aspose.threed.formats/discreet3dssaveoptions/duplicatednameseparator/) { get; set; } | الفاصل بين اسم الكائن والعداد المكرر، القيمة الافتراضية هي "_". عندما يحتوي المشهد على كائنات تستخدم نفس الاسم، سيولد مصدر Aspose.3D 3DS اسمًا مختلفًا للكائن. على سبيل المثال هناك عقدتين باسم "Box"، العقدة الأولى ستحمل الاسم "Box"، والعقدة الثانية ستحصل على اسم جديد "Box_2" باستخدام الإعداد الافتراضي. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | يحصل أو يضبط الترميز الافتراضي للملفات النصية. القيمة الافتراضية هي null مما يعني أن المستورد/المصدر سيقرر أي ترميز يستخدم. |
| [ExportCamera](../../aspose.threed.formats/discreet3dssaveoptions/exportcamera/) { get; set; } | يحصل أو يضبط ما إذا كان يتم تصدير جميع الكاميرات في المشهد. |
| [ExportLight](../../aspose.threed.formats/discreet3dssaveoptions/exportlight/) { get; set; } | يحصل أو يضبط ما إذا كان يتم تصدير جميع الأضواء في المشهد. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | محاولة نسخ القوام المستخدمة في المشهد إلى دليل الإخراج. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | يحصل على تنسيق الملف المحدد في خيار الحفظ/التحميل الحالي. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | اسم ملف المشهد المُصدّر/المستورد. هذا اختياري، لكنه مفيد عند تسلسل الأصول الخارجية مثل مادة OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | السماح للمستخدم بالتعامل مع كيفية إدارة التبعيات الخارجية أثناء التحميل/الحفظ. |
| [FlipCoordinateSystem](../../aspose.threed.formats/discreet3dssaveoptions/flipcoordinatesystem/) { get; set; } | يحصل أو يضبط عكس نظام الإحداثيات لنقاط التحكم/السطوح أثناء الاستيراد/التصدير. |
| [GammaCorrectedColor](../../aspose.threed.formats/discreet3dssaveoptions/gammacorrectedcolor/) { get; set; } | قد يحتوي ملف 3ds على اللون الأصلي واللون المصحح للجاما لنفس الخاصية، ضبط هذا إلى true سيستخدم اللون المصحح للجاما إذا كان ممكنًا، وإلا سيحاول Aspose.3D استخدام اللون الأصلي. |
| [HighPreciseColor](../../aspose.threed.formats/discreet3dssaveoptions/highprecisecolor/) { get; set; } | إذا كان هذا true، سيستخدم ملف 3ds المُولد لونًا عالي الدقة، مما يعني أن كل قناة من الأحمر/الأخضر/الأزرق تكون في صيغة 32‑bit عائمة. وإلا سيستخدم الملف المُولد لونًا 24‑bit، حيث كل قناة تستخدم بايت 8‑bit. القيمة الافتراضية هي false، لأن ليس كل التطبيقات تدعم اللون عالي الدقة. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | بعض الملفات مثل OBJ تعتمد على ملف خارجي، مسارات البحث ستسمح لـ Aspose.3D بالبحث عن الملف الخارجي للتحميل. |
| [MasterScale](../../aspose.threed.formats/discreet3dssaveoptions/masterscale/) { get; set; } | يحصل أو يضبط مقياس القاعدة المستخدم في التصدير. |

### انظر أيضًا

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


