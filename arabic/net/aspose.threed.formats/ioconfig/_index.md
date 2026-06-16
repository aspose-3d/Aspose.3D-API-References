---
title: "الفئة IOConfig"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Formats.IOConfig. إعدادات الإدخال/الإخراج للتسلسل/إلغاء التسلسل. يمكن للمستخدم تحديد تكوينات مفصلة مثل مسار البحث عن الاعتمادات أو إعدادات متعلقة بالتنسيق هنا."
type: docs
weight: 1300
url: /ar/net/aspose.threed.formats/ioconfig/
---
## IOConfig class

إعدادات الإدخال والإخراج للتسلسل/إلغاء التسلسل. يمكن للمستخدم تحديد تكوينات مفصلة مثل مسار البحث عن الاعتمادات أو إعدادات متعلقة بالتنسيق هنا

```csharp
public class IOConfig
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | يحصل أو يضبط الترميز الافتراضي للملفات النصية. القيمة الافتراضية هي null مما يعني أن المستورد/المصدر سيقرر أي ترميز يستخدم. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | يحصل على تنسيق الملف المحدد في خيار الحفظ/التحميل الحالي. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | اسم ملف المشهد المُصدّر/المستورد. هذا اختياري، لكنه مفيد عند تسلسل الأصول الخارجية مثل مادة OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | السماح للمستخدم بالتعامل مع كيفية إدارة التبعيات الخارجية أثناء التحميل/الحفظ. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | بعض الملفات مثل OBJ تعتمد على ملف خارجي، مسارات البحث ستسمح لـ Aspose.3D بالبحث عن الملف الخارجي للتحميل. |
| static [FileSystemFactory](../../aspose.threed.formats/ioconfig/filesystemfactory/) { get; set; } | يحصل أو يعيّن فئة المصنع لنظام الملفات. المصنع الافتراضي سيُنشئ LocalFileSystem الذي لا يناسب بيئة الخادم. |

### انظر أيضًا

* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


