---
title: RvmSaveOptions.ExportAttributes
second_title: Aspose.3D for .NET API Reference
description: RvmSaveOptions property. Gets or sets whether to export the attribute list to an external .att file default value is false
type: docs
weight: 60
url: /net/aspose.threed.formats/rvmsaveoptions/exportattributes/
---
## RvmSaveOptions.ExportAttributes property

Gets or sets whether to export the attribute list to an external .att file, default value is false.

```csharp
public bool ExportAttributes { get; set; }
```

## Examples

The following code shows how to export attribute in RVM.

```csharp
Scene scene = new Scene();
var box = new Box().ToMesh();
//node's name is required to export attributes
var boxNode = scene.RootNode.CreateChildNode("box", box);
boxNode.SetProperty("rvm:Price", 12.0);
boxNode.SetProperty("rvm:Weight", 30.0);
var opt = new RvmSaveOptions();
//Properties with rvm: prefix will be exported.
opt.ExportAttributes = true;
opt.AttributePrefix = "rvm:";
opt.Author = "Aspose.3D";
opt.FileNote = "Test attribute export";
scene.Save("output.rvm", opt);
```

### See Also

* class [RvmSaveOptions](../)
* namespace [Aspose.ThreeD.Formats](../../rvmsaveoptions/)
* assembly [Aspose.3D](../../../)


