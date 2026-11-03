---
title: "FileSystem.CreateDummyFileSystem"
second_title: "Aspose.3D für .NET API-Referenz"
description: "FileSystem-Methode. Erstelle ein Dummy-Dateisystem, Lese-/Schreibvorgänge sind Dummy-Operationen."
type: docs
weight: 10
url: /de/net/aspose.threed.utilities/filesystem/createdummyfilesystem/
---
## FileSystem.CreateDummyFileSystem method

Erstelle ein Dummy-Dateisystem, Lese-/Schreibvorgänge sind Dummy-Operationen.

```csharp
public static FileSystem CreateDummyFileSystem()
```

### Rückgabewert

Ein Dummy-Dateisystem

## Beispiele

Der folgende Code zeigt, wie man eine Datei in den Speicher exportiert und alle abhängigen Dateigenerierungen ignoriert.

```csharp
//Erstelle eine Szene mit Material.
Scene scene = new Scene();
scene.RootNode.CreateChildNode(new Box()).Material = new LambertMaterial();
//Erstelle eine Speicheroption und gib das Dateisystem an, sodass die abhängige Datei in den Speicher geschrieben wird.
var opt = FileFormat.WavefrontOBJ.CreateSaveOptions();
var dfs = FileSystem.CreateDummyFileSystem();
opt.FileSystem = dfs;
//Der Materialdateiname des obj ist mit dem Dateinamen des obj verknüpft, daher benötigen wir einen expliziten Namen.
opt.FileName = "test.obj";
using (var ms = new MemoryStream())
{
    scene.Save(ms, opt);
}
```

### Siehe auch

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


