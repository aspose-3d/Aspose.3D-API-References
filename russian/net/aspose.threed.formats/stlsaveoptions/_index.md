---
title: "Класс StlSaveOptions"
second_title: "Справочник API Aspose.3D для .NET"
description: "Aspose.ThreeD.Formats.StlSaveOptions class. Параметры сохранения для STL"
type: docs
weight: 1510
url: /ru/net/aspose.threed.formats/stlsaveoptions/
---
## StlSaveOptions class

Параметры сохранения для STL

```csharp
public class StlSaveOptions : SaveOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [StlSaveOptions](stlsaveoptions/#constructor)() | Инициализирует новый экземпляр `StlSaveOptions`. |
| [StlSaveOptions](stlsaveoptions/#constructor_1)(FileContentType) | Инициализирует новый экземпляр `StlSaveOptions`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AxisSystem](../../aspose.threed.formats/stlsaveoptions/axissystem/) { get; set; } | Получает или задает систему координат в экспортируемом файле STL. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Получает или задает кодировку по умолчанию для текстовых файлов. Значение по умолчанию — null, что означает, что импортёр/экспортер определит, какую кодировку использовать. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Пробовать копировать текстуры, используемые в сцене, в выходной каталог. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Получает формат файла, указанный в текущих параметрах сохранения/загрузки. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Имя файла экспортируемой/импортируемой сцены. Это необязательно, но полезно при сериализации внешних ресурсов, таких как материал OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения. |
| [FlipCoordinateSystem](../../aspose.threed.formats/stlsaveoptions/flipcoordinatesystem/) { get; set; } | Получает или задает, следует ли инвертировать систему координат контрольных точек/нормалей при экспорте. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D находить внешние файлы для загрузки. |

### См. также

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


