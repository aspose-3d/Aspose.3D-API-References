---
title: "Класс ObjSaveOptions"
second_title: "Справочник API Aspose.3D для .NET"
description: "класс Aspose.ThreeD.Formats.ObjSaveOptions. Параметры сохранения для файла wavefront obj"
type: docs
weight: 1370
url: /ru/net/aspose.threed.formats/objsaveoptions/
---
## ObjSaveOptions class

Параметры сохранения для файла wavefront obj

```csharp
public class ObjSaveOptions : SaveOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ObjSaveOptions](objsaveoptions/)() | Конструктор `ObjSaveOptions` |

## Свойства

| Имя | Описание |
| --- | --- |
| [ApplyUnitScale](../../aspose.threed.formats/objsaveoptions/applyunitscale/) { get; set; } | Применить [`UnitScaleFactor`](../../aspose.threed/assetinfo/unitscalefactor/) к сетке. Значение по умолчанию — false. |
| [AxisSystem](../../aspose.threed.formats/objsaveoptions/axissystem/) { get; set; } | Получает или задает систему координат в экспортируемом файле. |
| [EnableMaterials](../../aspose.threed.formats/objsaveoptions/enablematerials/) { get; set; } | Получает или задает, импортировать/экспортировать материалы для каждого объекта |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Получает или задает кодировку по умолчанию для текстовых файлов. Значение по умолчанию — null, что означает, что импортёр/экспортер определит, какую кодировку использовать. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Пробовать копировать текстуры, используемые в сцене, в выходной каталог. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Получает формат файла, указанный в текущих параметрах сохранения/загрузки. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Имя файла экспортируемой/импортируемой сцены. Это необязательно, но полезно при сериализации внешних ресурсов, таких как материал OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения. |
| [FlipCoordinateSystem](../../aspose.threed.formats/objsaveoptions/flipcoordinatesystem/) { get; set; } | Получает или задает, следует ли инвертировать систему координат контрольных точек/нормалей при импорте/экспорте. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D находить внешние файлы для загрузки. |
| [PointCloud](../../aspose.threed.formats/objsaveoptions/pointcloud/) { get; set; } | Получает или задает флаг, следует ли экспортировать сцену как облако точек (без топологической структуры), значение по умолчанию — false |
| [SerializeW](../../aspose.threed.formats/objsaveoptions/serializew/) { get; set; } | Получает или задает, сериализовать ли компонент W в позиции вершины модели. |
| [Verbose](../../aspose.threed.formats/objsaveoptions/verbose/) { get; set; } | Получает или задает, генерировать ли комментарии для каждого раздела. |

### См. также

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


