---
title: "IOConfig.LookupPaths"
second_title: "Справочник API Aspose.3D для .NET"
description: "Свойство IOConfig. Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D находить внешние файлы для загрузки"
type: docs
weight: 50
url: /ru/net/aspose.threed.formats/ioconfig/lookuppaths/
---
## IOConfig.LookupPaths property

Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D находить внешние файлы для загрузки.

```csharp
public List<string> LookupPaths { get; set; }
```

## Примеры

Следующий код показывает, как вручную задать пути поиска текстур, чтобы импортёр мог их найти

```csharp
var opt = new ObjLoadOptions();
//Укажите пути поиска, чтобы текстуры могли быть найдены.
opt.LookupPaths.Add("textures");
var scene = Scene.FromFile("input.obj", opt);
scene.Save("output.glb");
```

### См. также

* class [IOConfig](../)
* namespace [Aspose.ThreeD.Formats](../../ioconfig/)
* assembly [Aspose.3D](../../../)


