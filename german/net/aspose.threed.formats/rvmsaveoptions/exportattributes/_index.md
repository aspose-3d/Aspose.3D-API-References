---
title: "RvmSaveOptions.ExportAttributes"
second_title: "Aspose.3D für .NET API-Referenz"
description: "RvmSaveOptions-Eigenschaft. Gibt an, ob die Attributliste in eine externe .att-Datei exportiert wird. Standardwert ist false"
type: docs
weight: 60
url: /de/net/aspose.threed.formats/rvmsaveoptions/exportattributes/
---
## RvmSaveOptions.ExportAttributes property

Liest oder setzt, ob die Attributliste in eine externe .att-Datei exportiert werden soll, Standardwert ist false.

```csharp
public bool ExportAttributes { get; set; }
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


