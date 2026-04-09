---
title: FileSystem.CreateDummyFileSystem
second_title: مرجع API Aspose.3D لـ .NET
description: طريقة FileSystem. إنشاء نظام ملفات تجريبي؛ عمليات القراءة/الكتابة هي عمليات تجريبية
type: docs
weight: 10
url: /ar/net/aspose.threed.utilities/filesystem/createdummyfilesystem/
---
## FileSystem.CreateDummyFileSystem method

إنشاء نظام ملفات تجريبي، عمليات القراءة/الكتابة هي عمليات تجريبية.

```csharp
public static FileSystem CreateDummyFileSystem()
```

### قيمة الإرجاع

نظام ملفات تجريبي

## Examples

يعرض الشيفرة التالية كيفية تصدير الملف إلى الذاكرة، وتجاهل جميع توليد الملفات التابعة.

```csharp
//إنشاء مشهد مع مادة
Scene scene = new Scene();
scene.RootNode.CreateChildNode(new Box()).Material = new LambertMaterial();
//إنشاء خيار حفظ وتحديد نظام الملفات، بحيث يُكتب الملف التابع إلى الذاكرة
var opt = FileFormat.WavefrontOBJ.CreateSaveOptions();
var dfs = FileSystem.CreateDummyFileSystem();
opt.FileSystem = dfs;
//اسم ملف مادة الـ obj مرتبط باسم ملف الـ obj، لذا نحتاج إلى اسم صريح.
opt.FileName = "test.obj";
using (var ms = new MemoryStream())
{
    scene.Save(ms, opt);
}
```

### انظر أيضًا

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


