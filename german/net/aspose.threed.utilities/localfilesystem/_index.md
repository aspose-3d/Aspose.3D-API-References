---
title: "LocalFileSystem"
second_title: "Aspose.3D für .NET API-Referenz"
description: 
type: docs
weight: 2650
url: /de/net/aspose.threed.utilities/localfilesystem/
---
## LocalFileSystem class

Das [`LocalFileSystem`](../localfilesystem) mappt die Lese-/Schreibvorgänge auf das lokale Verzeichnis.

```csharp
public class LocalFileSystem : FileSystem
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [LocalFileSystem](localfilesystem)(string) | Initialisieren Sie ein neues [`LocalFileSystem`](../localfilesystem) mit dem angegebenen Basisverzeichnis. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [Dispose](../../aspose.threed.utilities/filesystem/dispose)() | Entfernen Sie das Dateisystem und geben Sie dessen Ressourcen frei. |
| override [ReadFile](../../aspose.threed.utilities/localfilesystem/readfile)(string, IOConfig) | Erstellt einen Stream zum Lesen von Abhängigkeiten. |
| override [WriteFile](../../aspose.threed.utilities/localfilesystem/writefile)(string, IOConfig) | Erstellt einen Stream zum Schreiben von Abhängigkeiten. |

### Beispiele

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

* class [FileSystem](../filesystem)
* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities)
* assembly [Aspose.3D](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für Aspose.3D.dll -->
