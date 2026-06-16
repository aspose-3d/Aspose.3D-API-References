---
title: "RvmSaveOptions.ExportAttributes"
second_title: "مرجع Aspose.3D for .NET API"
description: "خاصية RvmSaveOptions. الحصول أو تعيين ما إذا كان سيتم تصدير قائمة السمات إلى ملف .att خارجي القيمة الافتراضية هي false"
type: docs
weight: 60
url: /ar/net/aspose.threed.formats/rvmsaveoptions/exportattributes/
---
## RvmSaveOptions.ExportAttributes property

يحصل أو يعيّن ما إذا كان سيتم تصدير قائمة السمات إلى ملف .att خارجي، القيمة الافتراضية هي false.

```csharp
public bool ExportAttributes { get; set; }
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


