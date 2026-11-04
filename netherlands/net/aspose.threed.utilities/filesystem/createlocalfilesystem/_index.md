---
title: "FileSystem.CreateLocalFileSystem"
second_title: "Aspose.3D voor .NET API-referentie"
description: "FileSystem-methode. Initialiseert een nieuw FileSystem dat alleen toegang heeft tot de lokale map. Alle bestandslees- en -schrijfbewerkingen op deze FileSystem-instantie worden naar de opgegeven map gemapt"
type: docs
weight: 20
url: /nl/net/aspose.threed.utilities/filesystem/createlocalfilesystem/
---
## FileSystem.CreateLocalFileSystem method

Initialiseer een nieuw [`FileSystem`](../) dat alleen toegang heeft tot de lokale map. Alle bestandslees- en -schrijfbewerkingen op deze FileSystem-instantie worden naar de opgegeven map gemapt.

```csharp
public static FileSystem CreateLocalFileSystem(string directory)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| map | String | De map in uw fysieke bestandssysteem als de virtuele hoofdmap. |

### Retourwaarde

Een nieuwe instantie van het bestandssysteem om lokale bestands toegang te bieden

### Exceptions

| exceptie | conditie |
| --- | --- |
| FileNotFoundException | Wordt gegooid wanneer de map niet gevonden kan worden. |

## Voorbeelden

De volgende code laat zien hoe een bestand te importeren en afhankelijke bestanden te leveren in een opgegeven map.

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//maak een instantie van load options en specificeer een lokaal bestandssysteem
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateLocalFileSystem("textures/");
//laad het bestand
var scene = Scene.FromFile(inputFile, opt);
```

### Zie ook

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


