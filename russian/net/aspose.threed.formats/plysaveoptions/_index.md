---
title: "Класс PlySaveOptions"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Formats.PlySaveOptions. Параметры сохранения для экспорта сцены в файл PLY"
type: docs
weight: 1450
url: /ru/net/aspose.threed.formats/plysaveoptions/
---
## PlySaveOptions class

Параметры сохранения при экспорте сцены в файл PLY.

```csharp
public class PlySaveOptions : SaveOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PlySaveOptions](plysaveoptions/#constructor)() | Конструктор `PlySaveOptions` |
| [PlySaveOptions](plysaveoptions/#constructor_1)(FileContentType) | Конструктор `PlySaveOptions` |

## Свойства

| Имя | Описание |
| --- | --- |
| [AxisSystem](../../aspose.threed.formats/plysaveoptions/axissystem/) { get; set; } | Получает или задает систему координат в экспортируемом файле STL. |
| [ColorComponents](../../aspose.threed.formats/plysaveoptions/colorcomponents/) { get; set; } | Имена компонентов для цвета вершины, значение по умолчанию — ("red", "green", "blue") |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Получает или задает кодировку по умолчанию для текстовых файлов. Значение по умолчанию — null, что означает, что импортёр/экспортер определит, какую кодировку использовать. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Пробовать копировать текстуры, используемые в сцене, в выходной каталог. |
| [FaceElement](../../aspose.threed.formats/plysaveoptions/faceelement/) { get; set; } | Имя элемента для данных граней, значение по умолчанию — "face" |
| [FaceProperty](../../aspose.threed.formats/plysaveoptions/faceproperty/) { get; set; } | Имя свойства для данных граней, значение по умолчанию — "vertex_index" |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Получает формат файла, указанный в текущих параметрах сохранения/загрузки. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Имя файла экспортируемой/импортируемой сцены. Это необязательно, но полезно при сериализации внешних ресурсов, таких как материал OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения. |
| [FlipCoordinate](../../aspose.threed.formats/plysaveoptions/flipcoordinate/) { get; set; } | Инвертировать координаты при сохранении сцены, значение по умолчанию — true |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D находить внешние файлы для загрузки. |
| [NormalComponents](../../aspose.threed.formats/plysaveoptions/normalcomponents/) { get; set; } | Имена компонентов для данных нормалей, значение по умолчанию — ("nx", "ny", "nz") |
| [PointCloud](../../aspose.threed.formats/plysaveoptions/pointcloud/) { get; set; } | Экспортировать сцену как облако точек, значение по умолчанию — false. |
| [PositionComponents](../../aspose.threed.formats/plysaveoptions/positioncomponents/) { get; set; } | Имена компонентов для данных позиции, значение по умолчанию — ("x", "y", "z") |
| [TextureCoordinateComponents](../../aspose.threed.formats/plysaveoptions/texturecoordinatecomponents/) { get; set; } | Имена компонентов для данных текстурных координат, значение по умолчанию — ("u", "v") |
| [VertexElement](../../aspose.threed.formats/plysaveoptions/vertexelement/) { get; set; } | Имя элемента для данных вершины, значение по умолчанию — "vertex" |

### См. также

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


