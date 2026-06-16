---
title: "MemoryFileSystem"
second_title: "مرجع Aspose.3D for .NET API"
description: 
type: docs
weight: 2680
url: /ar/net/aspose.threed.utilities/memoryfilesystem/
---
## MemoryFileSystem class

سيقوم الـ [`MemoryFileSystem`](../memoryfilesystem) بربط عمليات القراءة/الكتابة بالذاكرة.

```csharp
public class MemoryFileSystem : FileSystem
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [MemoryFileSystem](memoryfilesystem)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [FileNames](../../aspose.threed.utilities/memoryfilesystem/filenames) { get; } | أسماء الملفات الموجودة في نظام الملفات الذاكرة هذا. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [Dispose](../../aspose.threed.utilities/filesystem/dispose)() | تخلص من نظام الملفات وأطلق موارده. |
| [GetFileContent](../../aspose.threed.utilities/memoryfilesystem/getfilecontent)(string) | يرجع المحتوى الخام للملف المحدد. يطرح استثناء FileNotFoundException إذا كان الملف المحدد غير موجود. |
| override [ReadFile](../../aspose.threed.utilities/memoryfilesystem/readfile)(string, IOConfig) | أنشئ تدفقاً لقراءة الاعتمادات. |
| override [WriteFile](../../aspose.threed.utilities/memoryfilesystem/writefile)(string, IOConfig) | أنشئ تدفقاً لكتابة الاعتمادات. |

### أمثلة

يظهر الكود التالي كيفية تصدير الملف إلى الذاكرة، ويتضمن الملف التابع باستخدام MemoryFileSystem.

```csharp
//أنشئ مشهداً بمواد
Scene scene = new Scene();
scene.RootNode.CreateChildNode(new Box()).Material = new LambertMaterial();
//أنشئ خيار حفظ وحدد نظام الملفات، بحيث يُكتب الملف التابع إلى الذاكرة
var opt = FileFormat.WavefrontOBJ.CreateSaveOptions();
var mfs = new MemoryFileSystem();
opt.FileSystem = mfs;
//اسم ملف مادة الـ obj مرتبط باسم ملف الـ obj، لذا نحتاج إلى اسم صريح.
opt.FileName = "test.obj";
using (var ms = new MemoryStream())
{
    scene.Save(ms, opt);
}
//تم كتابة test.obj إلى المتغيّر ms، ويمكننا أيضاً الحصول على محتوى ملف test.mtl عبر
var materialFile = mfs.GetFileContent("test.mtl");
```

### انظر أيضًا

* class [FileSystem](../filesystem)
* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities)
* assembly [Aspose.3D](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ Aspose.3D.dll -->
