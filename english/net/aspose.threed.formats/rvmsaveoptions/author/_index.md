---
title: RvmSaveOptions.Author
second_title: Aspose.3D for .NET API Reference
description: RvmSaveOptions property. Author information default value is 3daspose
type: docs
weight: 40
url: /net/aspose.threed.formats/rvmsaveoptions/author/
---
## RvmSaveOptions.Author property

Author information, default value is '3d@aspose'

```csharp
public string Author { get; set; }
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


