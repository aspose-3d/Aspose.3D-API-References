---
title: "FileSystem.CreateLocalFileSystem"
second_title: "Aspose.3D för .NET API‑referens"
description: "FileSystem metod. Initiera ett nytt FileSystem som endast får åtkomst till den lokala katalogen. All fil‑läsa/skriva på detta FileSystem‑instans kommer att mappas till den angivna katalogen."
type: docs
weight: 20
url: /sv/net/aspose.threed.utilities/filesystem/createlocalfilesystem/
---
## FileSystem.CreateLocalFileSystem method

Initiera ett nytt [`FileSystem`](../) som endast får åtkomst till den lokala katalogen. All fil‑läsa/skriva på detta FileSystem‑instans kommer att mappas till den angivna katalogen.

```csharp
public static FileSystem CreateLocalFileSystem(string directory)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| katalog | String | Katalogen i ditt fysiska filsystem som den virtuella rotkatalogen. |

### Returvärde

En ny instans av filsystemet för att tillhandahålla lokal filåtkomst

### Undantag

| undantag | villkor |
| --- | --- |
| FileNotFoundException | Kastas när katalogen inte kan hittas. |

## Exempel

Följande kod visar hur man importerar en fil och tillhandahåller beroende filer i en given katalog

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//skapa en instans av laddningsalternativ och ange ett lokalt filsystem
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateLocalFileSystem("textures/");
//läs in filen
var scene = Scene.FromFile(inputFile, opt);
```

### Se även

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


