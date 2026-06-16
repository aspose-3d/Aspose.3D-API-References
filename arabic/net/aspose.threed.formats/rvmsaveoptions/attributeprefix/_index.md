---
title: "RvmSaveOptions.AttributePrefix"
second_title: "مرجع Aspose.3D for .NET API"
description: "خاصية RvmSaveOptions. الحصول أو تعيين بادئة السمات التي سيتم تصديرها؛ الخاصية المصدرة لن تحتوي على بادئة؛ الخصائص المخصصة ذات البادئة المختلفة لن يتم تصديرها؛ القيمة الافتراضية هي rvm. على سبيل المثال إذا كانت الخاصية rvmRefno345 فإن السمة المصدرة ستكون Refno 345؛ تم إزالة البادئة."
type: docs
weight: 30
url: /ar/net/aspose.threed.formats/rvmsaveoptions/attributeprefix/
---
## RvmSaveOptions.AttributePrefix property

يحصل أو يعيّن البادئة للسمات التي سيتم تصديرها، الخاصية المصدّرة لن تحتوي على بادئة، السمات المخصصة ذات البادئة المختلفة لن تُصدّر، القيمة الافتراضية هي 'rvm:'. على سبيل المثال إذا كانت الخاصية rvm:Refno=345، فإن السمة المصدّرة ستكون Refno = 345، تُزال البادئة.

```csharp
public string AttributePrefix { get; set; }
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


