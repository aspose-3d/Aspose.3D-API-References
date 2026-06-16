---
title: "IOConfig.FileSystemFactory"
second_title: "مرجع Aspose.3D for .NET API"
description: "خاصية IOConfig. تحصل أو تعين فئة المصنع لنظام الملفات. المصنع الافتراضي سيُنشئ LocalFileSystem الذي لا يناسب بيئة الخادم."
type: docs
weight: 60
url: /ar/net/aspose.threed.formats/ioconfig/filesystemfactory/
---
## IOConfig.FileSystemFactory property

يحصل أو يعيّن فئة المصنع لنظام الملفات. المصنع الافتراضي سيُنشئ LocalFileSystem الذي لا يناسب بيئة الخادم.

```csharp
public static FileSystemFactory FileSystemFactory { get; set; }
```

## أمثلة

نظام الملفات الافتراضي في SaveOptions/LoadOptions هو نظام ملفات قائم على الدليل، يمكنك تجاوز التنفيذ الافتراضي بتحديده عبر IOConfig.FileSystemFactory:

```csharp
IOConfig.FileSystemFactory = () => {
    return FileSystem.CreateDummyFileSystem();
};

Scene scene = new Scene();
var material = new PhongMaterial();
var boxNode = scene.RootNode.CreateChildNode(new Box());
boxNode.Material = material;

//سيصبح opt.FileSystem نظام ملفات تجريبي الآن.
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


