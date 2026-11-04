---
title: "RvmSaveOptions.AttributePrefix"
second_title: "Справочник API Aspose.3D для .NET"
description: "Свойство RvmSaveOptions. Получает или задает префикс атрибутов, которые будут экспортированы; экспортируемое свойство будет без префикса, пользовательские свойства с другим префиксом экспортированы не будут; значение по умолчанию — rvm. Например, если свойство rvmRefno345, экспортируемый атрибут будет Refno345, префикс удалён"
type: docs
weight: 30
url: /ru/net/aspose.threed.formats/rvmsaveoptions/attributeprefix/
---
## RvmSaveOptions.AttributePrefix property

Получает или задает префикс атрибутов, которые будут экспортированы; экспортируемое свойство будет без префикса, пользовательские свойства с другим префиксом экспортированы не будут; значение по умолчанию — 'rvm:'. Например, если свойство rvm:Refno=345, экспортируемый атрибут будет Refno = 345, префикс будет удалён.

```csharp
public string AttributePrefix { get; set; }
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


