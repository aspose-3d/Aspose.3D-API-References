---
title: "الفئة Discreet3dsLoadOptions"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Formats.Discreet3dsLoadOptions. خيارات التحميل لملف 3DS."
type: docs
weight: 1120
url: /ar/net/aspose.threed.formats/discreet3dsloadoptions/
---
## Discreet3dsLoadOptions class

خيارات التحميل لملف 3DS.

```csharp
public class Discreet3dsLoadOptions : LoadOptions
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [Discreet3dsLoadOptions](discreet3dsloadoptions/)() | منشئ `Discreet3dsLoadOptions` |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ApplyAnimationTransform](../../aspose.threed.formats/discreet3dsloadoptions/applyanimationtransform/) { get; set; } | يحصل أو يعيّن ما إذا كان سيتم استخدام التحويل المحدد في الإطار الأول لمسار الرسوم المتحركة. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | يحصل أو يضبط الترميز الافتراضي للملفات النصية. القيمة الافتراضية هي null مما يعني أن المستورد/المصدر سيقرر أي ترميز يستخدم. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | يحصل على تنسيق الملف المحدد في خيار الحفظ/التحميل الحالي. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | اسم ملف المشهد المُصدّر/المستورد. هذا اختياري، لكنه مفيد عند تسلسل الأصول الخارجية مثل مادة OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | السماح للمستخدم بالتعامل مع كيفية إدارة التبعيات الخارجية أثناء التحميل/الحفظ. |
| [FlipCoordinateSystem](../../aspose.threed.formats/discreet3dsloadoptions/flipcoordinatesystem/) { get; set; } | يحصل أو يضبط عكس نظام الإحداثيات لنقاط التحكم/السطوح أثناء الاستيراد/التصدير. |
| [GammaCorrectedColor](../../aspose.threed.formats/discreet3dsloadoptions/gammacorrectedcolor/) { get; set; } | قد يحتوي ملف 3ds على اللون الأصلي واللون المصحح للجاما لنفس الخاصية، ضبط هذا إلى true سيستخدم اللون المصحح للجاما إذا كان ممكنًا، وإلا سيحاول Aspose.3D استخدام اللون الأصلي. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | بعض الملفات مثل OBJ تعتمد على ملف خارجي، مسارات البحث ستسمح لـ Aspose.3D بالبحث عن الملف الخارجي للتحميل. |

### انظر أيضًا

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


