---
title: "LocalFileSystem"
second_title: "مرجع Aspose.3D for .NET API"
description: 
type: docs
weight: 2650
url: /ar/net/aspose.threed.utilities/localfilesystem/
---
## LocalFileSystem class

ستقوم [`LocalFileSystem`](../localfilesystem) بربط عمليات القراءة/الكتابة بالدليل المحلي.

```csharp
public class LocalFileSystem : FileSystem
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [LocalFileSystem](localfilesystem)(string) | تهيئة [`LocalFileSystem`](../localfilesystem) جديد باستخدام الدليل الأساسي المحدد. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [Dispose](../../aspose.threed.utilities/filesystem/dispose)() | تخلص من نظام الملفات وأطلق موارده. |
| override [ReadFile](../../aspose.threed.utilities/localfilesystem/readfile)(string, IOConfig) | أنشئ تدفقاً لقراءة الاعتمادات. |
| override [WriteFile](../../aspose.threed.utilities/localfilesystem/writefile)(string, IOConfig) | أنشئ تدفقاً لكتابة الاعتمادات. |

### أمثلة

الكود التالي يوضح كيفية استيراد الملف وتوفير الملفات التابعة في دليل معين

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//إنشاء كائن خيارات التحميل وتحديد نظام ملفات zip
var opt = format.CreateLoadOptions();
opt.FileSystem = new LocalFileSystem("textures/");
//تحميل الملف
var scene = Scene.FromFile(inputFile, opt);
```

### انظر أيضًا

* class [FileSystem](../filesystem)
* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities)
* assembly [Aspose.3D](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ Aspose.3D.dll -->
