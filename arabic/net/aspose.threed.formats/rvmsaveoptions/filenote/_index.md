---
title: "RvmSaveOptions.FileNote"
second_title: "مرجع Aspose.3D for .NET API"
description: "خاصية RvmSaveOptions. ملاحظة الملف في رأس الملف"
type: docs
weight: 70
url: /ar/net/aspose.threed.formats/rvmsaveoptions/filenote/
---
## RvmSaveOptions.FileNote property

ملاحظة الملف في رأس الملف.

```csharp
public string FileNote { get; set; }
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


