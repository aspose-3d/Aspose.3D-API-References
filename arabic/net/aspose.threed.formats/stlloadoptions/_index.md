---
title: "فئة StlLoadOptions"
second_title: "مرجع Aspose.3D for .NET API"
description: "فئة Aspose.ThreeD.Formats.StlLoadOptions. خيارات التحميل لملف STL"
type: docs
weight: 1500
url: /ar/net/aspose.threed.formats/stlloadoptions/
---
## StlLoadOptions class

خيارات التحميل لملف STL.

```csharp
public class StlLoadOptions : LoadOptions
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [StlLoadOptions](stlloadoptions/#constructor)() | تهيئة نسخة جديدة من `StlLoadOptions`. |
| [StlLoadOptions](stlloadoptions/#constructor_1)(FileContentType) | تهيئة نسخة جديدة من `StlLoadOptions`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | يحصل أو يضبط الترميز الافتراضي للملفات النصية. القيمة الافتراضية هي null مما يعني أن المستورد/المصدر سيقرر أي ترميز يستخدم. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | يحصل على تنسيق الملف المحدد في خيار الحفظ/التحميل الحالي. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | اسم ملف المشهد المُصدّر/المستورد. هذا اختياري، لكنه مفيد عند تسلسل الأصول الخارجية مثل مادة OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | السماح للمستخدم بالتعامل مع كيفية إدارة التبعيات الخارجية أثناء التحميل/الحفظ. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | بعض الملفات مثل OBJ تعتمد على ملف خارجي، مسارات البحث ستسمح لـ Aspose.3D بالبحث عن الملف الخارجي للتحميل. |
| [RecalculateNormal](../../aspose.threed.formats/stlloadoptions/recalculatenormal/) { get; set; } | تجاهل بيانات السطح المخزنة في ملف STL وإعادة حساب بيانات السطح بناءً على موضع الرؤوس. القيمة الافتراضية هي false. |

### انظر أيضًا

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


