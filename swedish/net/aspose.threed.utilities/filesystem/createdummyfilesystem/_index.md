---
title: "FileSystem.CreateDummyFileSystem"
second_title: "Aspose.3D för .NET API‑referens"
description: "FileSystem‑metod. Skapa ett dummy‑filsystem, läs/skriv‑operationer är dummy‑operationer"
type: docs
weight: 10
url: /sv/net/aspose.threed.utilities/filesystem/createdummyfilesystem/
---
## FileSystem.CreateDummyFileSystem method

Skapa ett dummy‑filsystem, läs/skriv‑operationer är dummy‑operationer.

```csharp
public static FileSystem CreateDummyFileSystem()
```

### Returvärde

Ett dummy‑filsystem

## Exempel

Följande kod visar hur man exporterar en fil till minnet och ignorerar all generering av beroende filer.

```csharp
//skapa en scen med material
Scene scene = new Scene();
scene.RootNode.CreateChildNode(new Box()).Material = new LambertMaterial();
//skapa ett spara‑alternativ och ange filsystemet, så den beroende filen skrivs till minnet
var opt = FileFormat.WavefrontOBJ.CreateSaveOptions();
var dfs = FileSystem.CreateDummyFileSystem();
opt.FileSystem = dfs;
//obj:s materialfilnamn är associerat med obj:ns filnamn, så vi behöver ett explicit namn.
opt.FileName = "test.obj";
using (var ms = new MemoryStream())
{
    scene.Save(ms, opt);
}
```

### Se även

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


