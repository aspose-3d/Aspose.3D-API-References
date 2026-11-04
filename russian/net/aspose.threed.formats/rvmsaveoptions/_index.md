---
title: "Класс RvmSaveOptions"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Formats.RvmSaveOptions. Параметры сохранения для файла Aveva PDMS RVM"
type: docs
weight: 1480
url: /ru/net/aspose.threed.formats/rvmsaveoptions/
---
## RvmSaveOptions class

Параметры сохранения для RVM-файла Aveva PDMS.

```csharp
public class RvmSaveOptions : SaveOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [RvmSaveOptions](rvmsaveoptions/#constructor)() | Конструктор `RvmSaveOptions` |
| [RvmSaveOptions](rvmsaveoptions/#constructor_1)(FileContentType) | Конструктор `RvmSaveOptions` |

## Свойства

| Имя | Описание |
| --- | --- |
| [AttributeListFile](../../aspose.threed.formats/rvmsaveoptions/attributelistfile/) { get; set; } | Получает или задает имя файла списка атрибутов, экспортёр сгенерирует имя на основе имени файла .rvm, если это свойство не определено; значение по умолчанию — null. |
| [AttributePrefix](../../aspose.threed.formats/rvmsaveoptions/attributeprefix/) { get; set; } | Получает или задает префикс атрибутов, которые будут экспортированы; экспортируемое свойство будет без префикса, пользовательские свойства с другим префиксом экспортированы не будут; значение по умолчанию — 'rvm:'. Например, если свойство rvm:Refno=345, экспортируемый атрибут будет Refno = 345, префикс будет удалён. |
| [Author](../../aspose.threed.formats/rvmsaveoptions/author/) { get; set; } | Информация об авторе, значение по умолчанию — '3d@aspose' |
| [CreationTime](../../aspose.threed.formats/rvmsaveoptions/creationtime/) { get; set; } | Метка времени, когда был экспортирован этот файл, значение по умолчанию — текущее время |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Получает или задает кодировку по умолчанию для текстовых файлов. Значение по умолчанию — null, что означает, что импортёр/экспортер определит, какую кодировку использовать. |
| [ExportAttributes](../../aspose.threed.formats/rvmsaveoptions/exportattributes/) { get; set; } | Получает или задает, следует ли экспортировать список атрибутов во внешний файл .att; значение по умолчанию — false. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Пробовать копировать текстуры, используемые в сцене, в выходной каталог. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Получает формат файла, указанный в текущих параметрах сохранения/загрузки. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Имя файла экспортируемой/импортируемой сцены. Это необязательно, но полезно при сериализации внешних ресурсов, таких как материал OBJ. |
| [FileNote](../../aspose.threed.formats/rvmsaveoptions/filenote/) { get; set; } | Примечание к файлу в заголовке. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D находить внешние файлы для загрузки. |

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

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


