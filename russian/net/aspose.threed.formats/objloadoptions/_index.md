---
title: "Класс ObjLoadOptions"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Formats.ObjLoadOptions. Параметры загрузки для Wavefront OBJ"
type: docs
weight: 1360
url: /ru/net/aspose.threed.formats/objloadoptions/
---
## ObjLoadOptions class

Параметры загрузки для wavefront obj

```csharp
public class ObjLoadOptions : LoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ObjLoadOptions](objloadoptions/)() | Конструктор `ObjLoadOptions` |

## Свойства

| Имя | Описание |
| --- | --- |
| [EnableMaterials](../../aspose.threed.formats/objloadoptions/enablematerials/) { get; set; } | Получает или задает, импортировать ли материалы для каждого объекта |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Получает или задает кодировку по умолчанию для текстовых файлов. Значение по умолчанию — null, что означает, что импортёр/экспортер определит, какую кодировку использовать. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Получает формат файла, указанный в текущих параметрах сохранения/загрузки. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Имя файла экспортируемой/импортируемой сцены. Это необязательно, но полезно при сериализации внешних ресурсов, таких как материал OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения. |
| [FlipCoordinateSystem](../../aspose.threed.formats/objloadoptions/flipcoordinatesystem/) { get; set; } | Получает или задает, следует ли инвертировать систему координат контрольных точек/нормали при импорте |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D находить внешние файлы для загрузки. |
| [NormalizeNormal](../../aspose.threed.formats/objloadoptions/normalizenormal/) { get; set; } | Получает или задает, следует ли нормализовать вектор нормали при загрузке. Значение по умолчанию — true. |
| [Scale](../../aspose.threed.formats/objloadoptions/scale/) { get; set; } | Масштаб по осям x/y/z, значение по умолчанию — 1.0 |

### См. также

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


