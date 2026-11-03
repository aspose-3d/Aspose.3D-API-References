---
title: "IOConfig.FileSystem"
second_title: "Aspose.3D für .NET API-Referenz"
description: "IOConfig Eigenschaft. Ermöglicht dem Benutzer, zu steuern, wie externe Abhängigkeiten beim Laden/Speichern verwaltet werden."
type: docs
weight: 40
url: /de/net/aspose.threed.formats/ioconfig/filesystem/
---
## IOConfig.FileSystem property

Ermöglicht dem Benutzer zu steuern, wie externe Abhängigkeiten während Laden/Speichern verwaltet werden.

```csharp
public FileSystem FileSystem { get; set; }
```

## Beispiele

Das Standard‑Dateisystem ist LocalFileSystem, es ist in Umgebungen wie Server‑Seiten nicht sicher. Sie können jedoch den Dateisystemzugriff überschreiben, indem Sie eine andere Implementierung angeben. Aspose.3D bietet verschiedene Dateisystem‑Implementierungen an, wie: Memory-based file system, Directory-based file system, Dummy file system, Zip file system. Und Sie können auch Ihre eigene Implementierung verwenden.

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
//Das Material wird in die Variable memFs mit dem Namen output.mtl geschrieben.
var materialInBytes = memFs["output.mtl"].ToArray();
```

### Siehe auch

* class [FileSystem](../../../aspose.threed.utilities/filesystem/)
* class [IOConfig](../)
* namespace [Aspose.ThreeD.Formats](../../ioconfig/)
* assembly [Aspose.3D](../../../)


