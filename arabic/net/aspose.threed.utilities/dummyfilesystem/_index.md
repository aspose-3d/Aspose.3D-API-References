---
title: "DummyFileSystem"
second_title: "مرجع Aspose.3D for .NET API"
description: 
type: docs
weight: 2570
url: /ar/net/aspose.threed.utilities/dummyfilesystem/
---
## DummyFileSystem class

عمليات القراءة/الكتابة هي عمليات تجريبية.

```csharp
public class DummyFileSystem : FileSystem
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [DummyFileSystem](dummyfilesystem)() | المنشئ الافتراضي. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [Dispose](../../aspose.threed.utilities/filesystem/dispose)() | تخلص من نظام الملفات وأطلق موارده. |
| override [ReadFile](../../aspose.threed.utilities/dummyfilesystem/readfile)(string, IOConfig) | أنشئ تدفقاً لقراءة الاعتمادات. |
| override [WriteFile](../../aspose.threed.utilities/dummyfilesystem/writefile)(string, IOConfig) | أنشئ تدفقاً لكتابة الاعتمادات. |

### أمثلة

الكود التالي يوضح كيفية تصدير الملف إلى الذاكرة، وتجاهل جميع توليد الملفات التابعة.

```csharp
//أنشئ مشهداً بمواد
Scene scene = new Scene();
scene.RootNode.CreateChildNode(new Box()).Material = new LambertMaterial();
//أنشئ خيار حفظ وحدد نظام الملفات، بحيث يُكتب الملف التابع إلى الذاكرة
var opt = FileFormat.WavefrontOBJ.CreateSaveOptions();
var dfs = new DummyFileSystem();
opt.FileSystem = dfs;
//اسم ملف مادة الـ obj مرتبط باسم ملف الـ obj، لذا نحتاج إلى اسم صريح.
opt.FileName = "test.obj";
using (var ms = new MemoryStream())
{
    scene.Save(ms, opt);
}
```

### انظر أيضًا

* class [FileSystem](../filesystem)
* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities)
* assembly [Aspose.3D](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ Aspose.3D.dll -->
