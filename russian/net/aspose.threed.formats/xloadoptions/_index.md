---
title: "Класс XLoadOptions"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Formats.XLoadOptions. Параметры загрузки для файлов DirectX X"
type: docs
weight: 1550
url: /ru/net/aspose.threed.formats/xloadoptions/
---
## XLoadOptions class

Параметры загрузки для файлов DirectX X.

```csharp
public class XLoadOptions : LoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [XLoadOptions](xloadoptions/)(FileContentType) | Конструктор `XLoadOptions` |

## Свойства

| Имя | Описание |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Получает или задает кодировку по умолчанию для текстовых файлов. Значение по умолчанию — null, что означает, что импортёр/экспортер определит, какую кодировку использовать. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Получает формат файла, указанный в текущих параметрах сохранения/загрузки. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Имя файла экспортируемой/импортируемой сцены. Это необязательно, но полезно при сериализации внешних ресурсов, таких как материал OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения. |
| [FlipCoordinateSystem](../../aspose.threed.formats/xloadoptions/flipcoordinatesystem/) { get; set; } | Инвертировать систему координат, по умолчанию true |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D находить внешние файлы для загрузки. |

### См. также

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


