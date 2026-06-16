---
title: "RvmSaveOptions.Author"
second_title: "مرجع Aspose.3D for .NET API"
description: "خاصية RvmSaveOptions. القيمة الافتراضية لمعلومات المؤلف هي 3daspose"
type: docs
weight: 40
url: /ar/net/aspose.threed.formats/rvmsaveoptions/author/
---
## RvmSaveOptions.Author property

معلومات المؤلف، القيمة الافتراضية هي '3d@aspose'

```csharp
public string Author { get; set; }
```

## أمثلة

الكود التالي يوضح كيفية تصدير السمة في RVM.

```csharp
Scene scene = new Scene();
var box = new Box().ToMesh();
//اسم العقدة مطلوب لتصدير السمات
var boxNode = scene.RootNode.CreateChildNode("box", box);
boxNode.SetProperty("rvm:Price", 12.0);
boxNode.SetProperty("rvm:Weight", 30.0);
var opt = new RvmSaveOptions();
//الخصائص ذات البادئة rvm: سيتم تصديرها.
opt.ExportAttributes = true;
opt.AttributePrefix = "rvm:";
opt.Author = "Aspose.3D";
opt.FileNote = "Test attribute export";
scene.Save("output.rvm", opt);
```

### انظر أيضًا

* class [RvmSaveOptions](../)
* namespace [Aspose.ThreeD.Formats](../../rvmsaveoptions/)
* assembly [Aspose.3D](../../../)


