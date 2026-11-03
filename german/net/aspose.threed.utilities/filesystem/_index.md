---
title: "Klasse FileSystem"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Utilities.FileSystem Klasse. Dateisystemkapselung. Aspose.3D wird dies zum Lesen/Schreiben von Abhängigkeiten verwenden"
type: docs
weight: 2750
url: /de/net/aspose.threed.utilities/filesystem/
---
## FileSystem class

Dateisystemkapselung. Aspose.3D wird dies zum Lesen/Schreiben von Abhängigkeiten verwenden.

```csharp
public abstract class FileSystem : IDisposable
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [CreateDummyFileSystem](../../aspose.threed.utilities/filesystem/createdummyfilesystem/)() | Erstelle ein Dummy-Dateisystem, Lese-/Schreibvorgänge sind Dummy-Operationen. |
| static [CreateLocalFileSystem](../../aspose.threed.utilities/filesystem/createlocalfilesystem/)(string) | Initialisiere ein neues `FileSystem`, das nur auf das lokale Verzeichnis zugreift. Alle Datei-Lese-/Schreibvorgänge auf dieser FileSystem-Instanz werden auf das angegebene Verzeichnis abgebildet. |
| static [CreateMemoryFileSystem](../../aspose.threed.utilities/filesystem/creatememoryfilesystem/)(Dictionary&lt;string, MemoryStream&gt;) |  |
| static [CreateZipFileSystem](../../aspose.threed.utilities/filesystem/createzipfilesystem/#createzipfilesystem_1)(string) | Dateisystem, das schreibgeschützten Zugriff auf eine angegebene ZIP-Datei oder einen ZIP-Stream ermöglicht. Das Dateisystem wird nach dem Öffnen/Speichern freigegeben. |
| static [CreateZipFileSystem](../../aspose.threed.utilities/filesystem/createzipfilesystem/#createzipfilesystem)(Stream, string) | Erstelle ein Dateisystem, das nur Lesezugriff auf die angegebene ZIP-Datei oder den ZIP-Stream bietet. Das Dateisystem wird nach dem Öffnen/Speichern freigegeben. |
| virtual [Dispose](../../aspose.threed.utilities/filesystem/dispose/)() | Entfernen Sie das Dateisystem und geben Sie dessen Ressourcen frei. |
| abstract [ReadFile](../../aspose.threed.utilities/filesystem/readfile/)(string, IOConfig) | Erstellt einen Stream zum Lesen von Abhängigkeiten. |
| abstract [WriteFile](../../aspose.threed.utilities/filesystem/writefile/)(string, IOConfig) | Erstellt einen Stream zum Schreiben von Abhängigkeiten. |

## Beispiele

Der folgende Code zeigt, wie man eine Datei importiert und abhängige Dateien in einem angegebenen Verzeichnis bereitstellt.

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//Erstelle eine Instanz von Ladeoptionen und gib ein ZIP-Dateisystem an
var opt = format.CreateLoadOptions();
opt.FileSystem = new LocalFileSystem("textures/");
//Lade die Datei
var scene = Scene.FromFile(inputFile, opt);
```

### Siehe auch

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


