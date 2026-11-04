---
title: "Класс JtLoadOptions"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Formats.SiemensJT.JtLoadOptions. Параметры загрузки для Siemens JT"
type: docs
weight: 1380
url: /ru/net/aspose.threed.formats.siemensjt/jtloadoptions/
---
## JtLoadOptions class

Параметры загрузки для Siemens JT

```csharp
public class JtLoadOptions : LoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [JtLoadOptions](jtloadoptions/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Получает или задает кодировку по умолчанию для текстовых файлов. Значение по умолчанию — null, что означает, что импортёр/экспортёр определит, какую кодировку использовать. (Наследовано от [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Получает формат файла, указанный в текущих параметрах сохранения/загрузки. (Наследовано от [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Имя файла экспортируемой/импортируемой сцены. Это необязательно, но полезно при сериализации внешних ресурсов, например материалов OBJ. (Наследовано от [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения. (Наследовано от [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |
| [LoadPMI](../../aspose.threed.formats.siemensjt/jtloadoptions/loadpmi/) { get; set; } | Загружать информацию PMI из файла JT, если возможно; данные будут сохранены как свойство "PMI" объекта [`AssetInfo`](../../aspose.threed/scene/assetinfo/). Значение по умолчанию — false. |
| [LoadProperties](../../aspose.threed.formats.siemensjt/jtloadoptions/loadproperties/) { get; set; } | Загружать свойства из таблицы свойств JT как свойства Aspose.3D. Значение по умолчанию — false. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D находить внешние файлы для загрузки. (Наследовано от [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |

### См. также

* class [LoadOptions](../../aspose.threed.formats/loadoptions/)
* namespace [Aspose.ThreeD.Formats.SiemensJT](../../aspose.threed.formats.siemensjt/)
* assembly [Aspose.3D](../../)


