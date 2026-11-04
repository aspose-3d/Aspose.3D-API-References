---
title: "Класс U3dLoadOptions"
second_title: "Справочник API Aspose.3D для .NET"
description: "Aspose.ThreeD.Formats.U3dLoadOptions class. Параметры загрузки для универсального 3D"
type: docs
weight: 1520
url: /ru/net/aspose.threed.formats/u3dloadoptions/
---
## U3dLoadOptions class

Параметры загрузки для universal 3d

```csharp
public class U3dLoadOptions : LoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [U3dLoadOptions](u3dloadoptions/)() | Конструктор `U3dLoadOptions` |

## Свойства

| Имя | Описание |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Получает или задает кодировку по умолчанию для текстовых файлов. Значение по умолчанию — null, что означает, что импортёр/экспортер определит, какую кодировку использовать. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Получает формат файла, указанный в текущих параметрах сохранения/загрузки. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Имя файла экспортируемой/импортируемой сцены. Это необязательно, но полезно при сериализации внешних ресурсов, таких как материал OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения. |
| [FlipCoordinateSystem](../../aspose.threed.formats/u3dloadoptions/flipcoordinatesystem/) { get; set; } | Получает или задает, следует ли инвертировать систему координат контрольных точек/нормалей при импорте/экспорте. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D находить внешние файлы для загрузки. |

### См. также

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


