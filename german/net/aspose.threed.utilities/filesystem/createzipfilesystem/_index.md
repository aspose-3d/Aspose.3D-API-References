---
title: "FileSystem.CreateZipFileSystem"
second_title: "Aspose.3D für .NET API-Referenz"
description: "FileSystem-Methode. Erstelle ein Dateisystem, das nur Lesezugriff auf die angegebene ZIP‑Datei oder den ZIP‑Stream bietet. Das Dateisystem wird nach dem Öffnen-/Speichern‑Vorgang freigegeben."
type: docs
weight: 40
url: /de/net/aspose.threed.utilities/filesystem/createzipfilesystem/
---
## CreateZipFileSystem(Stream, string) {#createzipfilesystem}

Erstelle ein Dateisystem, das nur Lesezugriff auf die angegebene ZIP-Datei oder den ZIP-Stream bietet. Das Dateisystem wird nach dem Öffnen/Speichern freigegeben.

```csharp
public static FileSystem CreateZipFileSystem(Stream stream, string baseDir = "/")
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | Stream | Der Stream zum Zugriff auf die ZIP‑Datei |
| baseDir | String | Das Basisverzeichnis innerhalb der ZIP‑Datei. |

### Rückgabewert

Ein ZIP‑Dateisystem

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| IOException | Wird ausgelöst, wenn das Lesen aus dem Stream fehlschlägt. |

## Hinweise

Dies ist ein schreibgeschütztes Dateisystem, daher werden keine Schreibvorgänge unterstützt.

## Beispiele

Der folgende Code zeigt, wie man eine Datei importiert und abhängige Dateien in einer ZIP-Archivdatei bereitstellt.

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//Erstelle eine Instanz von Ladeoptionen und gib ein ZIP-Dateisystem an
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateZipFileSystem("textures.zip");
//Lade die Datei
var scene = Scene.FromFile(inputFile, opt);
```

### Siehe auch

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)

---

## CreateZipFileSystem(string) {#createzipfilesystem_1}

Dateisystem, das schreibgeschützten Zugriff auf eine angegebene ZIP-Datei oder einen ZIP-Stream ermöglicht. Das Dateisystem wird nach dem Öffnen/Speichern freigegeben.

```csharp
public static FileSystem CreateZipFileSystem(string fileName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Dateiname der ZIP-Datei. |

### Rückgabewert

Ein ZIP‑Dateisystem

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| IOException | Wird ausgelöst, wenn das Lesen aus dem Stream fehlschlägt. |

## Beispiele

Der folgende Code zeigt, wie man eine Datei importiert und abhängige Dateien in einer ZIP-Archivdatei bereitstellt.

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//Erstelle eine Instanz von Ladeoptionen und gib ein ZIP-Dateisystem an
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateZipFileSystem("textures.zip");
//Lade die Datei
var scene = Scene.FromFile(inputFile, opt);
```

### Siehe auch

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


