---
title: "IOConfig.FileSystem"
second_title: "مرجع Aspose.3D for .NET API"
description: "خاصية IOConfig. تسمح للمستخدم بالتعامل مع كيفية إدارة الاعتمادات الخارجية أثناء التحميل/الحفظ."
type: docs
weight: 40
url: /ar/net/aspose.threed.formats/ioconfig/filesystem/
---
## IOConfig.FileSystem property

السماح للمستخدم بالتعامل مع كيفية إدارة التبعيات الخارجية أثناء التحميل/الحفظ.

```csharp
public FileSystem FileSystem { get; set; }
```

## أمثلة

نظام الملفات الافتراضي هو LocalFileSystem، وهو غير آمن في بيئات مثل جانب الخادم، لكن يمكنك تجاوز وصول نظام الملفات بتحديد تنفيذ مختلف. توفر Aspose.3D تطبيقات نظام ملفات مختلفة مثل: Memory-based file systemDirectory-based file systemDummy file systemZip file system ويمكنك أيضاً استخدام تنفيذك الخاص.

```csharp
Scene scene = new Scene();
var material = new PhongMaterial();
var boxNode = scene.RootNode.CreateChildNode(new Box());
boxNode.Material = material;

var opt = new ObjSaveOptions();
var memFs = new Dictionary<string, MemoryStream>();
opt.FileSystem = FileSystem.CreateMemoryFileSystem(memFs);
using var output = new MemoryStream();
opt.FileName = "output.obj";
scene.Save(output, opt);
//سيتم كتابة المادة إلى المتغيّر memFs المسمى output.mtl.
var materialInBytes = memFs["output.mtl"].ToArray();
```

### انظر أيضًا

* class [FileSystem](../../../aspose.threed.utilities/filesystem/)
* class [IOConfig](../)
* namespace [Aspose.ThreeD.Formats](../../ioconfig/)
* assembly [Aspose.3D](../../../)


