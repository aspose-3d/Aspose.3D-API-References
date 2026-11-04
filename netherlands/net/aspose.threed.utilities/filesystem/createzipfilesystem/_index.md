---
title: "FileSystem.CreateZipFileSystem"
second_title: "Aspose.3D voor .NET API-referentie"
description: "FileSystem-methode. Maak een bestandssysteem om alleen-lezen toegang te bieden tot een gespecificeerd zip-bestand of zip-stream. Het bestandssysteem wordt verwijderd na de open-/opslaan-bewerking."
type: docs
weight: 40
url: /nl/net/aspose.threed.utilities/filesystem/createzipfilesystem/
---
## CreateZipFileSystem(Stream, string) {#createzipfilesystem}

Maak een bestandssysteem om alleen-lezen toegang te bieden tot een gespecificeerd zip-bestand of zip-stream. Het bestandssysteem wordt verwijderd na de open-/opslaan-bewerking.

```csharp
public static FileSystem CreateZipFileSystem(Stream stream, string baseDir = "/")
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | Stream | De stream om toegang te krijgen tot het zip-bestand |
| baseDir | String | De basismap binnen het zip-bestand. |

### Retourwaarde

Een zip-bestandssysteem

### Exceptions

| exceptie | conditie |
| --- | --- |
| IOException | Wordt gegooid wanneer het lezen van de stream mislukt. |

## Opmerkingen

Dit is een alleen-lezen bestandssysteem, dus schrijfoperaties worden niet ondersteund.

## Voorbeelden

De volgende code laat zien hoe een bestand te importeren en afhankelijke bestanden te leveren in een zip-archiefbestand.

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//maak een instantie van load options en specificeer een zip-bestandssysteem
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateZipFileSystem("textures.zip");
//laad het bestand
var scene = Scene.FromFile(inputFile, opt);
```

### Zie ook

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)

---

## CreateZipFileSystem(string) {#createzipfilesystem_1}

Bestandssysteem om alleen-lezen toegang te bieden tot een gespecificeerd zip-bestand of zip-stream. Het bestandssysteem wordt verwijderd na de open-/opslaan-bewerking.

```csharp
public static FileSystem CreateZipFileSystem(string fileName)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | String | Bestandsnaam voor het zip‑bestand. |

### Retourwaarde

Een zip-bestandssysteem

### Exceptions

| exceptie | conditie |
| --- | --- |
| IOException | Wordt gegooid wanneer het lezen van de stream mislukt. |

## Voorbeelden

De volgende code laat zien hoe een bestand te importeren en afhankelijke bestanden te leveren in een zip-archiefbestand.

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//maak een instantie van load options en specificeer een zip-bestandssysteem
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateZipFileSystem("textures.zip");
//laad het bestand
var scene = Scene.FromFile(inputFile, opt);
```

### Zie ook

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


