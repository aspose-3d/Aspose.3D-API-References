---
title: "IOConfig.FileSystemFactory"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "خاصية IOConfig. تحصل أو تعيّن فئة المصنع لنظام الملفات. المصنع الافتراضي سيُنشئ LocalFileSystem وهو غير مناسب لبيئة الخادم"
type: docs
weight: 60
url: /ar/net/aspose.threed.formats/ioconfig/filesystemfactory/
---
## IOConfig.FileSystemFactory property

تحصل أو تعيّن فئة المصنع لنظام الملفات. المصنع الافتراضي سيُنشئ LocalFileSystem وهو غير مناسب لبيئة الخادم.

```csharp
public static FileSystemFactory FileSystemFactory { get; set; }
```

## أمثلة

نظام الملفات الافتراضي في SaveOptions/LoadOptions هو نظام ملفات قائم على الدليل، يمكنك تجاوز التنفيذ الافتراضي عن طريق تحديده عبر IOConfig.FileSystemFactory:

```csharp
IOConfig.FileSystemFactory = () => {
    return FileSystem.CreateDummyFileSystem();
};

Scene scene = new Scene();
var material = new PhongMaterial();
var boxNode = scene.RootNode.CreateChildNode(new Box());
boxNode.Material = material;

//سيصبح opt.FileSystem نظام ملفات تجريبي الآن
var opt = new ObjSaveOptions();
using var output = new MemoryStream();
opt.FileName = "output.obj";
scene.Save(output, opt);
//لن يتم كتابة ملف المادة output.mtl إلى أي مكان لأننا قمنا بتكوين نظام ملفات تجريبي كتنفيذ افتراضي.
```

### انظر أيضًا

* delegate [FileSystemFactory](../../filesystemfactory/)
* class [IOConfig](../)
* namespace [Aspose.ThreeD.Formats](../../ioconfig/)
* assembly [Aspose.3D](../../../)


