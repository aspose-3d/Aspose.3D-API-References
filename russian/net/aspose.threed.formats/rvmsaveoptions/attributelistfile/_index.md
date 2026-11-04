---
title: "RvmSaveOptions.AttributeListFile"
second_title: "Справочник API Aspose.3D для .NET"
description: "Свойство RvmSaveOptions. Получает или задает имя файла списка атрибутов; экспортер сгенерирует имя на основе имени файла .rvm, когда это свойство не определено. Значение по умолчанию — null"
type: docs
weight: 20
url: /ru/net/aspose.threed.formats/rvmsaveoptions/attributelistfile/
---
## RvmSaveOptions.AttributeListFile property

Получает или задает имя файла списка атрибутов, экспортёр сгенерирует имя на основе имени файла .rvm, если это свойство не определено; значение по умолчанию — null.

```csharp
public string AttributeListFile { get; set; }
```

## Примеры

Следующий код показывает, как экспортировать атрибут в RVM.

```csharp
Scene scene = new Scene();
var box = new Box().ToMesh();
//Для экспорта атрибутов требуется имя узла
var boxNode = scene.RootNode.CreateChildNode("box", box);
boxNode.SetProperty("rvm:Price", 12.0);
boxNode.SetProperty("rvm:Weight", 30.0);
var opt = new RvmSaveOptions();
//Свойства с префиксом rvm: будут экспортированы.
opt.ExportAttributes = true;
opt.AttributePrefix = "rvm:";
opt.Author = "Aspose.3D";
opt.FileNote = "Test attribute export";
scene.Save("output.rvm", opt);
```

### См. также

* class [RvmSaveOptions](../)
* namespace [Aspose.ThreeD.Formats](../../rvmsaveoptions/)
* assembly [Aspose.3D](../../../)


