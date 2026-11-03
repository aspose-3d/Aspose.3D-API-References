---
title: "RvmSaveOptions.FileNote"
second_title: "Aspose.3D für .NET API-Referenz"
description: "RvmSaveOptions-Eigenschaft. Dateinotiz im Dateikopf"
type: docs
weight: 70
url: /de/net/aspose.threed.formats/rvmsaveoptions/filenote/
---
## RvmSaveOptions.FileNote property

Dateikommentar im Dateikopf.

```csharp
public string FileNote { get; set; }
```

## Beispiele

Der folgende Code zeigt, wie man Attribute in RVM exportiert.

```csharp
Scene scene = new Scene();
var box = new Box().ToMesh();
//Der Name des Knotens ist erforderlich, um Attribute zu exportieren
var boxNode = scene.RootNode.CreateChildNode("box", box);
boxNode.SetProperty("rvm:Price", 12.0);
boxNode.SetProperty("rvm:Weight", 30.0);
var opt = new RvmSaveOptions();
//Eigenschaften mit dem Präfix rvm: werden exportiert.
opt.ExportAttributes = true;
opt.AttributePrefix = "rvm:";
opt.Author = "Aspose.3D";
opt.FileNote = "Test attribute export";
scene.Save("output.rvm", opt);
```

### Siehe auch

* class [RvmSaveOptions](../)
* namespace [Aspose.ThreeD.Formats](../../rvmsaveoptions/)
* assembly [Aspose.3D](../../../)


