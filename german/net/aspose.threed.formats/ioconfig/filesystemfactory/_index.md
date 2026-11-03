---
title: "IOConfig.FileSystemFactory"
second_title: "Aspose.3D für .NET API-Referenz"
description: "IOConfig Eigenschaft. Gibt die Fabrikklasse für das Dateisystem zurück oder legt sie fest. Die Standard‑Fabrik erstellt LocalFileSystem, das für Serverumgebungen nicht geeignet ist."
type: docs
weight: 60
url: /de/net/aspose.threed.formats/ioconfig/filesystemfactory/
---
## IOConfig.FileSystemFactory property

Liest oder setzt die Fabrikklasse für das Dateisystem. Die Standardfabrik erstellt LocalFileSystem, das für Serverumgebungen nicht geeignet ist.

```csharp
public static FileSystemFactory FileSystemFactory { get; set; }
```

## Beispiele

Das Standard‑Dateisystem in SaveOptions/LoadOptions ist ein verzeichnisbasiertes Dateisystem. Sie können die Standardimplementierung überschreiben, indem Sie sie über IOConfig.FileSystemFactory angeben:

```csharp
IOConfig.FileSystemFactory = () => {
    return FileSystem.CreateDummyFileSystem();
};

Scene scene = new Scene();
var material = new PhongMaterial();
var boxNode = scene.RootNode.CreateChildNode(new Box());
boxNode.Material = material;

//opt.FileSystem wäre jetzt ein Dummy‑Dateisystem.
var opt = new ObjSaveOptions();
using var output = new MemoryStream();
opt.FileName = "output.obj";
scene.Save(output, opt);
//Die Materialdatei output.mtl wird nicht geschrieben, weil wir ein Dummy‑Dateisystem als Standardimplementierung konfiguriert haben.
```

### Siehe auch

* delegate [FileSystemFactory](../../filesystemfactory/)
* class [IOConfig](../)
* namespace [Aspose.ThreeD.Formats](../../ioconfig/)
* assembly [Aspose.3D](../../../)


