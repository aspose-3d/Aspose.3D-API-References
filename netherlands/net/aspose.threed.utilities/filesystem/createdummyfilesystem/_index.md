---
title: "FileSystem.CreateDummyFileSystem"
second_title: "Aspose.3D voor .NET API-referentie"
description: "FileSystem-methode. Maak een dummy‑bestandssysteem lees-/schrijfbewerkingen zijn dummy‑bewerkingen"
type: docs
weight: 10
url: /nl/net/aspose.threed.utilities/filesystem/createdummyfilesystem/
---
## FileSystem.CreateDummyFileSystem method

Maak een dummy‑bestandssysteem, lees‑/schrijfbewerkingen zijn dummy‑bewerkingen.

```csharp
public static FileSystem CreateDummyFileSystem()
```

### Retourwaarde

Een dummy‑bestandssysteem

## Voorbeelden

De volgende code toont hoe een bestand naar het geheugen te exporteren en alle afhankelijke bestandsgeneratie te negeren.

```csharp
//maak een scène met materiaal
Scene scene = new Scene();
scene.RootNode.CreateChildNode(new Box()).Material = new LambertMaterial();
//maak een opslaan‑optie en specificeer het bestandssysteem, zodat het afhankelijke bestand naar het geheugen wordt geschreven
var opt = FileFormat.WavefrontOBJ.CreateSaveOptions();
var dfs = FileSystem.CreateDummyFileSystem();
opt.FileSystem = dfs;
//De bestandsnaam van het materiaal van het obj is gekoppeld aan de bestandsnaam van het obj, dus we hebben een expliciete naam nodig.
opt.FileName = "test.obj";
using (var ms = new MemoryStream())
{
    scene.Save(ms, opt);
}
```

### Zie ook

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


