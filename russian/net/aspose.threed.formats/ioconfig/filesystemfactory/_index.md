---
title: "IOConfig.FileSystemFactory"
second_title: "Справочник API Aspose.3D для .NET"
description: "Свойство IOConfig. Получает или задает класс фабрики для FileSystem. Фабрика по умолчанию создаёт LocalFileSystem, который не подходит для серверной среды"
type: docs
weight: 60
url: /ru/net/aspose.threed.formats/ioconfig/filesystemfactory/
---
## IOConfig.FileSystemFactory property

Получает или задает класс фабрики для FileSystem. Фабрика по умолчанию создаст LocalFileSystem, который не подходит для серверной среды.

```csharp
public static FileSystemFactory FileSystemFactory { get; set; }
```

## Примеры

Файловая система по умолчанию в SaveOptions/LoadOptions — файловая система, основанная на каталогах. Вы можете переопределить реализацию по умолчанию, указав её через IOConfig.FileSystemFactory:

```csharp
IOConfig.FileSystemFactory = () => {
    return FileSystem.CreateDummyFileSystem();
};

Scene scene = new Scene();
var material = new PhongMaterial();
var boxNode = scene.RootNode.CreateChildNode(new Box());
boxNode.Material = material;

//opt.FileSystem теперь будет фиктивной файловой системой
var opt = new ObjSaveOptions();
using var output = new MemoryStream();
opt.FileName = "output.obj";
scene.Save(output, opt);
//файл материала output.mtl не будет записан никуда, потому что мы настроили фиктивную файловую систему как реализацию по умолчанию.
```

### См. также

* delegate [FileSystemFactory](../../filesystemfactory/)
* class [IOConfig](../)
* namespace [Aspose.ThreeD.Formats](../../ioconfig/)
* assembly [Aspose.3D](../../../)


