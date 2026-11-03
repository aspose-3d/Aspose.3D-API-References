---
title: "DummyFileSystem"
second_title: "Aspose.3D für .NET API-Referenz"
description: 
type: docs
weight: 2570
url: /de/net/aspose.threed.utilities/dummyfilesystem/
---
## DummyFileSystem class

Lese-/Schreibvorgänge sind Dummy-Operationen.

```csharp
public class DummyFileSystem : FileSystem
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [DummyFileSystem](dummyfilesystem)() | Der Standardkonstruktor. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [Dispose](../../aspose.threed.utilities/filesystem/dispose)() | Entfernen Sie das Dateisystem und geben Sie dessen Ressourcen frei. |
| override [ReadFile](../../aspose.threed.utilities/dummyfilesystem/readfile)(string, IOConfig) | Erstellt einen Stream zum Lesen von Abhängigkeiten. |
| override [WriteFile](../../aspose.threed.utilities/dummyfilesystem/writefile)(string, IOConfig) | Erstellt einen Stream zum Schreiben von Abhängigkeiten. |

### Beispiele

Der folgende Code zeigt, wie man eine Datei in den Speicher exportiert und alle abhängigen Dateigenerierungen ignoriert.

```csharp
//Erstelle eine Szene mit Material.
Scene scene = new Scene();
scene.RootNode.CreateChildNode(new Box()).Material = new LambertMaterial();
//Erstelle eine Speicheroption und gib das Dateisystem an, sodass die abhängige Datei in den Speicher geschrieben wird.
var opt = FileFormat.WavefrontOBJ.CreateSaveOptions();
var dfs = new DummyFileSystem();
opt.FileSystem = dfs;
//Der Materialdateiname des obj ist mit dem Dateinamen des obj verknüpft, daher benötigen wir einen expliziten Namen.
opt.FileName = "test.obj";
using (var ms = new MemoryStream())
{
    scene.Save(ms, opt);
}
```

### Siehe auch

* class [FileSystem](../filesystem)
* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities)
* assembly [Aspose.3D](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für Aspose.3D.dll -->
