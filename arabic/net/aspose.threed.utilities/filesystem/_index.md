---
title: "الفئة FileSystem"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Utilities.FileSystem. تغليف نظام الملفات. ستستخدم Aspose.3D هذا لقراءة/كتابة الاعتمادات."
type: docs
weight: 2750
url: /ar/net/aspose.threed.utilities/filesystem/
---
## FileSystem class

تغليف نظام الملفات. سيستخدم Aspose.3D هذا لقراءة/كتابة الاعتمادات.

```csharp
public abstract class FileSystem : IDisposable
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [CreateDummyFileSystem](../../aspose.threed.utilities/filesystem/createdummyfilesystem/)() | إنشاء نظام ملفات تجريبي، عمليات القراءة/الكتابة هي عمليات تجريبية. |
| static [CreateLocalFileSystem](../../aspose.threed.utilities/filesystem/createlocalfilesystem/)(string) | تهيئة `FileSystem` جديد يقتصر على الوصول إلى الدليل المحلي. جميع عمليات القراءة/الكتابة على هذه المثيلة من FileSystem سيتم توجيهها إلى الدليل المحدد. |
| static [CreateMemoryFileSystem](../../aspose.threed.utilities/filesystem/creatememoryfilesystem/)(Dictionary&lt;string, MemoryStream&gt;) |  |
| static [CreateZipFileSystem](../../aspose.threed.utilities/filesystem/createzipfilesystem/#createzipfilesystem_1)(string) | نظام الملفات لتوفير الوصول للقراءة فقط إلى ملف zip المحدد أو تدفق zip. سيتم التخلص من نظام الملفات بعد عملية الفتح/الحفظ. |
| static [CreateZipFileSystem](../../aspose.threed.utilities/filesystem/createzipfilesystem/#createzipfilesystem)(Stream, string) | إنشاء نظام ملفات لتوفير وصول للقراءة فقط إلى ملف zip المحدد أو تدفق zip. سيتم التخلص من نظام الملفات بعد عملية الفتح/الحفظ. |
| virtual [Dispose](../../aspose.threed.utilities/filesystem/dispose/)() | تخلص من نظام الملفات وأطلق موارده. |
| abstract [ReadFile](../../aspose.threed.utilities/filesystem/readfile/)(string, IOConfig) | أنشئ تدفقاً لقراءة الاعتمادات. |
| abstract [WriteFile](../../aspose.threed.utilities/filesystem/writefile/)(string, IOConfig) | أنشئ تدفقاً لكتابة الاعتمادات. |

## أمثلة

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

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


