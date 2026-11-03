---
title: "Klasse ZipArchiveFileSystem"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Utilities.ZipArchiveFileSystem Klasse. Dateisystem, das nur Lesezugriff auf eine angegebene ZIP-Datei oder ZIP-Stream bietet. Das Dateisystem wird nach dem Öffnen/Speichern freigegeben."
type: docs
weight: 2830
url: /de/net/aspose.threed.utilities/ziparchivefilesystem/
---
## ZipArchiveFileSystem class

Dateisystem, das schreibgeschützten Zugriff auf eine angegebene ZIP-Datei oder einen ZIP-Stream ermöglicht. Das Dateisystem wird nach dem Öffnen/Speichern freigegeben.

```csharp
public class ZipArchiveFileSystem : FileSystem
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Dispose](../../aspose.threed.utilities/ziparchivefilesystem/dispose/)() | Entfernt das ZipArchiveFileSystem und gibt seine internen Ressourcen frei. |
| override [ReadFile](../../aspose.threed.utilities/ziparchivefilesystem/readfile/)(string, IOConfig) | Datei zum Lesen öffnen |
| override [WriteFile](../../aspose.threed.utilities/ziparchivefilesystem/writefile/)(string, IOConfig) | Datei zum Schreiben öffnen, in dieser Klasse nicht implementiert. |

### Beispiele

Der folgende Code zeigt, wie man eine Datei importiert und abhängige Dateien in einer ZIP-Archivdatei bereitstellt.

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//Erstelle eine Instanz von Ladeoptionen und gib ein ZIP-Dateisystem an
var opt = format.CreateLoadOptions();
opt.FileSystem = new ZipArchiveFileSystem("textures.zip");
//Lade die Datei
var scene = Scene.FromFile(inputFile, opt);
```

### Siehe auch

* class [FileSystem](../filesystem/)
* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


