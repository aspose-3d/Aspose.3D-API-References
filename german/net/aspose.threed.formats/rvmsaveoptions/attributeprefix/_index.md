---
title: "RvmSaveOptions.AttributePrefix"
second_title: "Aspose.3D für .NET API-Referenz"
description: "RvmSaveOptions-Eigenschaft. Gibt das Präfix der zu exportierenden Attribute an bzw. legt es fest. Die exportierte Eigenschaft enthält kein Präfix; benutzerdefinierte Eigenschaften mit anderem Präfix werden nicht exportiert. Standardwert ist rvm. Zum Beispiel, wenn eine Eigenschaft rvmRefno345 heißt, wird das exportierte Attribut Refno 345 sein, das Präfix wird entfernt."
type: docs
weight: 30
url: /de/net/aspose.threed.formats/rvmsaveoptions/attributeprefix/
---
## RvmSaveOptions.AttributePrefix property

Liest oder setzt das Präfix der Attribute, die exportiert werden sollen; die exportierten Eigenschaften enthalten kein Präfix, benutzerdefinierte Eigenschaften mit anderem Präfix werden nicht exportiert, Standardwert ist 'rvm:'. Zum Beispiel, wenn eine Eigenschaft rvm:Refno=345 ist, wird das exportierte Attribut Refno = 345 sein, das Präfix wird entfernt.

```csharp
public string AttributePrefix { get; set; }
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


