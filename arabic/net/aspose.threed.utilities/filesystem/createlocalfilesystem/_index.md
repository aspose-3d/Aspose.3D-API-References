---
title: "FileSystem.CreateLocalFileSystem"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة FileSystem. تهيئة FileSystem جديد يقتصر على الوصول إلى الدليل المحلي. جميع عمليات قراءة/كتابة الملفات على هذه النسخة من FileSystem سيتم توجيهها إلى الدليل المحدد"
type: docs
weight: 20
url: /ar/net/aspose.threed.utilities/filesystem/createlocalfilesystem/
---
## FileSystem.CreateLocalFileSystem method

تهيئة نظام ملفات جديد [`FileSystem`](../) يقتصر على الوصول إلى الدليل المحلي. جميع عمليات قراءة/كتابة الملفات على مثيل FileSystem هذا سيتم توجيهها إلى الدليل المحدد.

```csharp
public static FileSystem CreateLocalFileSystem(string directory)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| دليل | سلسلة | الدليل في نظام الملفات الفعلي الخاص بك كدليل جذري افتراضي. |

### قيمة الإرجاع

مثال جديد لنظام الملفات لتوفير الوصول إلى الملفات المحلية

### استثناءات

| استثناء | شرط |
| --- | --- |
| FileNotFoundException | يتم إلقاؤه عندما لا يمكن العثور على الدليل. |

## أمثلة

الكود التالي يوضح كيفية استيراد الملف وتوفير الملفات التابعة في دليل معين

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//إنشاء مثيل خيارات التحميل وتحديد نظام ملفات محلي
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateLocalFileSystem("textures/");
//تحميل الملف
var scene = Scene.FromFile(inputFile, opt);
```

### انظر أيضًا

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


