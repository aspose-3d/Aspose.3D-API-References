---
title: "FileSystem.CreateLocalFileSystem"
second_title: "Aspose.3D für .NET API-Referenz"
description: "FileSystem-Methode. Initialisiere ein neues FileSystem, das nur auf das lokale Verzeichnis zugreift. Alle Datei‑Lese‑/Schreibvorgänge auf dieser FileSystem‑Instanz werden auf das angegebene Verzeichnis abgebildet"
type: docs
weight: 20
url: /de/net/aspose.threed.utilities/filesystem/createlocalfilesystem/
---
## FileSystem.CreateLocalFileSystem method

Initialisiere ein neues [`FileSystem`](../), das nur auf das lokale Verzeichnis zugreift. Alle Datei‑Lese‑/Schreibvorgänge auf dieser FileSystem‑Instanz werden auf das angegebene Verzeichnis abgebildet.

```csharp
public static FileSystem CreateLocalFileSystem(string directory)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Verzeichnis | String | Das Verzeichnis in Ihrem physischen Dateisystem als virtuelles Stammverzeichnis. |

### Rückgabewert

Eine neue Instanz des Dateisystems, um lokalen Dateizugriff zu ermöglichen

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| FileNotFoundException | Wird ausgelöst, wenn das Verzeichnis nicht gefunden werden kann. |

## Beispiele

Der folgende Code zeigt, wie man eine Datei importiert und abhängige Dateien in einem angegebenen Verzeichnis bereitstellt.

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//Erstelle eine Instanz von Ladeoptionen und gib ein lokales Dateisystem an
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateLocalFileSystem("textures/");
//Lade die Datei
var scene = Scene.FromFile(inputFile, opt);
```

### Siehe auch

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


