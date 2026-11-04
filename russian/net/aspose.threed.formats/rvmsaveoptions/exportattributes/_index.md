---
title: "RvmSaveOptions.ExportAttributes"
second_title: "Справочник API Aspose.3D для .NET"
description: "Свойство RvmSaveOptions. Получает или задает, следует ли экспортировать список атрибутов во внешний файл .att, значение по умолчанию — false"
type: docs
weight: 60
url: /ru/net/aspose.threed.formats/rvmsaveoptions/exportattributes/
---
## RvmSaveOptions.ExportAttributes property

Получает или задает, следует ли экспортировать список атрибутов во внешний файл .att; значение по умолчанию — false.

```csharp
public bool ExportAttributes { get; set; }
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


