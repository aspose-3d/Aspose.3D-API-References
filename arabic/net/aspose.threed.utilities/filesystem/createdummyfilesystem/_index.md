---
title: "FileSystem.CreateDummyFileSystem"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "طريقة FileSystem. إنشاء نظام ملفات وهمي عمليات القراءة/الكتابة هي عمليات وهمية"
type: docs
weight: 10
url: /ar/net/aspose.threed.utilities/filesystem/createdummyfilesystem/
---
## FileSystem.CreateDummyFileSystem method

إنشاء نظام ملفات وهمي، عمليات القراءة/الكتابة هي عمليات وهمية.

```csharp
public static FileSystem CreateDummyFileSystem()
```

### قيمة الإرجاع

نظام ملفات وهمي

## أمثلة

يظهر الكود التالي كيفية تصدير الملف إلى الذاكرة، وتجاهل جميع توليد الملفات التابعة.

```csharp
//إنشاء مشهد بمواد
Scene scene = new Scene();
scene.RootNode.CreateChildNode(new Box()).Material = new LambertMaterial();
//إنشاء خيار حفظ وتحديد نظام الملفات، بحيث يُكتب الملف التابع إلى الذاكرة.
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


