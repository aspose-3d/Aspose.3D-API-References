---
title: "RvmSaveOptions.FileNote"
second_title: "Справочник API Aspose.3D для .NET"
description: "Свойство RvmSaveOptions. Примечание к файлу в заголовке"
type: docs
weight: 70
url: /ru/net/aspose.threed.formats/rvmsaveoptions/filenote/
---
## RvmSaveOptions.FileNote property

Примечание к файлу в заголовке.

```csharp
public string FileNote { get; set; }
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


