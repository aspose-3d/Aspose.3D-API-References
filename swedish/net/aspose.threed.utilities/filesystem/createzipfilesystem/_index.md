---
title: "FileSystem.CreateZipFileSystem"
second_title: "Aspose.3D för .NET API‑referens"
description: "FileSystem metod. Skapa ett filsystem för att ge skrivskyddad åtkomst till en specificerad zip‑fil eller zip‑ström. Filsystemet kommer att tas bort efter öppna/spara‑operationen."
type: docs
weight: 40
url: /sv/net/aspose.threed.utilities/filesystem/createzipfilesystem/
---
## CreateZipFileSystem(Stream, string) {#createzipfilesystem}

Skapa ett filsystem för att ge läs‑endast åtkomst till en specificerad zip‑fil eller zip‑ström. Filsystemet kommer att tas bort efter öppna/spara‑operationen.

```csharp
public static FileSystem CreateZipFileSystem(Stream stream, string baseDir = "/")
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | Strömmen för att komma åt zip‑filen |
| baseDir | String | Bas katalogen i zip-filen. |

### Returvärde

Ett zip-filsystem

### Undantag

| undantag | villkor |
| --- | --- |
| IOException | Kastas när läsning från ström misslyckas. |

## Anmärkningar

Detta är ett skrivskyddat filsystem, så inga skrivoperationer stöds.

## Exempel

Följande kod visar hur man importerar en fil och tillhandahåller beroende filer i ett zip-arkiv.

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//skapa en instans av load‑alternativ och ange ett zip‑filsystem
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateZipFileSystem("textures.zip");
//läs in filen
var scene = Scene.FromFile(inputFile, opt);
```

### Se även

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)

---

## CreateZipFileSystem(string) {#createzipfilesystem_1}

Filsystem för att ge skrivskyddad åtkomst till angiven zip‑fil eller zip‑ström. Filsystemet kommer att tas bort efter öppna/ spara‑operationen.

```csharp
public static FileSystem CreateZipFileSystem(string fileName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | String | Filnamn för zip‑filen. |

### Returvärde

Ett zip-filsystem

### Undantag

| undantag | villkor |
| --- | --- |
| IOException | Kastas när läsning från ström misslyckas. |

## Exempel

Följande kod visar hur man importerar en fil och tillhandahåller beroende filer i ett zip-arkiv.

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//skapa en instans av load‑alternativ och ange ett zip‑filsystem
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateZipFileSystem("textures.zip");
//läs in filen
var scene = Scene.FromFile(inputFile, opt);
```

### Se även

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


