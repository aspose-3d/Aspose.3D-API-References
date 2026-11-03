---
title: "FileSystem.CreateLocalFileSystem"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "طريقة FileSystem. تهيئة FileSystem جديد يمكنه الوصول فقط إلى الدليل المحلي. جميع عمليات قراءة/كتابة الملفات على هذا المثال من FileSystem سيتم ربطها بالدليل المحدد"
type: docs
weight: 20
url: /ar/net/aspose.threed.utilities/filesystem/createlocalfilesystem/
---
## FileSystem.CreateLocalFileSystem method

تهيئة [`FileSystem`](../) جديد يمكنه الوصول فقط إلى الدليل المحلي. جميع عمليات قراءة/كتابة الملفات على هذا المثال من FileSystem سيتم ربطها بالدليل المحدد.

```csharp
public static FileSystem CreateLocalFileSystem(string directory)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| دليل | String | الدليل في نظام الملفات الفعلي الخاص بك كدليل الجذر الافتراضي. |

### قيمة الإرجاع

مثال جديد لنظام الملفات لتوفير الوصول إلى الملفات المحلية

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| FileNotFoundException | يُرمى عندما لا يمكن العثور على الدليل. |

## أمثلة

يعرض الكود التالي كيفية استيراد الملف وتوفير الملفات التابعة في دليل معين.

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//إنشاء مثال خيارات التحميل وتحديد نظام ملفات محلي
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateLocalFileSystem("textures/");
//تحميل الملف.
var scene = Scene.FromFile(inputFile, opt);
```

### انظر أيضًا

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


