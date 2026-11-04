---
title: "Класс A3dwSaveOptions"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Formats.A3dwSaveOptions. Параметры сохранения для формата A3DW"
type: docs
weight: 1080
url: /ru/net/aspose.threed.formats/a3dwsaveoptions/
---
## A3dwSaveOptions class

Параметры сохранения для формата A3DW.

```csharp
public class A3dwSaveOptions : SaveOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [A3dwSaveOptions](a3dwsaveoptions/)() | Конструктор `A3dwSaveOptions` |

## Свойства

| Имя | Описание |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Получает или задает кодировку по умолчанию для текстовых файлов. Значение по умолчанию — null, что означает, что импортёр/экспортер определит, какую кодировку использовать. |
| [ExportMetaData](../../aspose.threed.formats/a3dwsaveoptions/exportmetadata/) { get; set; } | Экспортировать метаданные, связанные со сценой/узлом, клиенту. Значение по умолчанию — true |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Пробовать копировать текстуры, используемые в сцене, в выходной каталог. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Получает формат файла, указанный в текущих параметрах сохранения/загрузки. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Имя файла экспортируемой/импортируемой сцены. Это необязательно, но полезно при сериализации внешних ресурсов, таких как материал OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D находить внешние файлы для загрузки. |
| [MetaDataPrefix](../../aspose.threed.formats/a3dwsaveoptions/metadataprefix/) { get; set; } | Если это свойство не равно null, будут экспортированы только свойства Scene/Node, начинающиеся с данного префикса, и префикс будет удалён. |

### См. также

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


