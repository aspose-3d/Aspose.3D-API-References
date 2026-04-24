---
title: FileSystem.CreateLocalFileSystem
second_title: مرجع API Aspose.3D لـ .NET
description: طريقة FileSystem. تهيئة FileSystem جديد يمكنه الوصول فقط إلى الدليل المحلي. جميع عمليات قراءة/كتابة الملفات على هذه المثيلة من FileSystem سيتم ربطها بالدليل المحدد
type: docs
weight: 20
url: /ar/net/aspose.threed.utilities/filesystem/createlocalfilesystem/
---
## FileSystem.CreateLocalFileSystem method

تهيئة [`FileSystem`](../) جديد يمكنه الوصول فقط إلى الدليل المحلي. جميع عمليات قراءة/كتابة الملفات على هذه المثيلة من FileSystem سيتم ربطها بالدليل المحدد.

```csharp
public static FileSystem CreateLocalFileSystem(string directory)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| دليل | سلسلة | الدليل في نظام الملفات الفعلي الخاص بك كدليل الجذر الافتراضي. |

### قيمة الإرجاع

مثيلة جديدة من نظام الملفات لتوفير الوصول إلى الملفات المحلية

### استثناءات

| استثناء | شرط |
| --- | --- |
| FileNotFoundException | يُرمى عندما لا يمكن العثور على الدليل. |

## Examples

يعرض الشيفرة التالية كيفية استيراد ملف وتوفير الملفات التابعة في دليل معين

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//إنشاء مثيلة خيارات التحميل وتحديد نظام ملفات محلي
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateLocalFileSystem("textures/");
//تحميل الملف
var scene = Scene.FromFile(inputFile, opt);
```

### انظر أيضًا

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


