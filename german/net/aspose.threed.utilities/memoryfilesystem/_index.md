---
title: "MemoryFileSystem"
second_title: "Aspose.3D für .NET API-Referenz"
description: 
type: docs
weight: 2680
url: /de/net/aspose.threed.utilities/memoryfilesystem/
---
## MemoryFileSystem class

Der [`MemoryFileSystem`](../memoryfilesystem) mappt die Lese-/Schreibvorgänge in den Speicher.

```csharp
public class MemoryFileSystem : FileSystem
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [MemoryFileSystem](memoryfilesystem)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [FileNames](../../aspose.threed.utilities/memoryfilesystem/filenames) { get; } | Dateinamen, die in diesem MemoryFileSystem liegen. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [Dispose](../../aspose.threed.utilities/filesystem/dispose)() | Entfernen Sie das Dateisystem und geben Sie dessen Ressourcen frei. |
| [GetFileContent](../../aspose.threed.utilities/memoryfilesystem/getfilecontent)(string) | Gibt den Rohinhalt der angegebenen Datei zurück. Wirft FileNotFoundException, wenn die angegebene Datei nicht existiert. |
| override [ReadFile](../../aspose.threed.utilities/memoryfilesystem/readfile)(string, IOConfig) | Erstellt einen Stream zum Lesen von Abhängigkeiten. |
| override [WriteFile](../../aspose.threed.utilities/memoryfilesystem/writefile)(string, IOConfig) | Erstellt einen Stream zum Schreiben von Abhängigkeiten. |

### Beispiele

Der folgende Code zeigt, wie man eine Datei in den Speicher exportiert und die abhängige Datei mit MemoryFileSystem einbezieht.

```csharp
//Erstelle eine Szene mit Material.
Scene scene = new Scene();
scene.RootNode.CreateChildNode(new Box()).Material = new LambertMaterial();
//Erstelle eine Speicheroption und gib das Dateisystem an, sodass die abhängige Datei in den Speicher geschrieben wird.
var opt = FileFormat.WavefrontOBJ.CreateSaveOptions();
var mfs = new MemoryFileSystem();
opt.FileSystem = mfs;
//Der Materialdateiname des obj ist mit dem Dateinamen des obj verknüpft, daher benötigen wir einen expliziten Namen.
opt.FileName = "test.obj";
using (var ms = new MemoryStream())
{
    scene.Save(ms, opt);
}
//Die test.obj wurde in die Variable ms geschrieben, und wir können den Inhalt der test.mtl-Datei auch erhalten, indem wir
var materialFile = mfs.GetFileContent("test.mtl");
```

### Siehe auch

* class [FileSystem](../filesystem)
* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities)
* assembly [Aspose.3D](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für Aspose.3D.dll -->
