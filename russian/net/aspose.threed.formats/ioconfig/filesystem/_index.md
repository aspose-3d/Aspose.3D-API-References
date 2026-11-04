---
title: "IOConfig.FileSystem"
second_title: "Справочник API Aspose.3D для .NET"
description: "Свойство IOConfig. Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения"
type: docs
weight: 40
url: /ru/net/aspose.threed.formats/ioconfig/filesystem/
---
## IOConfig.FileSystem property

Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения.

```csharp
public FileSystem FileSystem { get; set; }
```

## Примеры

Файловая система по умолчанию — LocalFileSystem, она не безопасна в среде типа серверной, но вы можете переопределить доступ к файловой системе, указав другую реализацию. Aspose.3D предоставляет различные реализации FileSystem, такие как: Memory-based file system, Directory-based file system, Dummy file system, Zip file system. И вы также можете использовать свою собственную реализацию.

```csharp
Scene scene = new Scene();
var material = new PhongMaterial();
var boxNode = scene.RootNode.CreateChildNode(new Box());
boxNode.Material = material;

var opt = new ObjSaveOptions();
var memFs = new Dictionary<string, MemoryStream>();
opt.FileSystem = FileSystem.CreateMemoryFileSystem(memFs);
using var output = new MemoryStream();
opt.FileName = "output.obj";
scene.Save(output, opt);
//Материал будет записан в переменную memFs с именем output.mtl
var materialInBytes = memFs["output.mtl"].ToArray();
```

### См. также

* class [FileSystem](../../../aspose.threed.utilities/filesystem/)
* class [IOConfig](../)
* namespace [Aspose.ThreeD.Formats](../../ioconfig/)
* assembly [Aspose.3D](../../../)


