---
title: "Класс U3dSaveOptions"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Formats.U3dSaveOptions. Параметры сохранения для universal 3d"
type: docs
weight: 1530
url: /ru/net/aspose.threed.formats/u3dsaveoptions/
---
## U3dSaveOptions class

Параметры сохранения для universal 3d

```csharp
public class U3dSaveOptions : SaveOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [U3dSaveOptions](u3dsaveoptions/)() | Конструктор `U3dSaveOptions` |

## Свойства

| Имя | Описание |
| --- | --- |
| [EmbedTextures](../../aspose.threed.formats/u3dsaveoptions/embedtextures/) { get; set; } | Встраивает внешние текстуры в файл U3D, значение по умолчанию — false. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Получает или задает кодировку по умолчанию для текстовых файлов. Значение по умолчанию — null, что означает, что импортёр/экспортер определит, какую кодировку использовать. |
| [ExportNormals](../../aspose.threed.formats/u3dsaveoptions/exportnormals/) { get; set; } | Получает или задает, экспортировать ли нормальные данные. |
| [ExportTextureCoordinates](../../aspose.threed.formats/u3dsaveoptions/exporttexturecoordinates/) { get; set; } | Получает или задает, экспортировать ли координаты текстур. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Пробовать копировать текстуры, используемые в сцене, в выходной каталог. |
| [ExportVertexDiffuse](../../aspose.threed.formats/u3dsaveoptions/exportvertexdiffuse/) { get; set; } | Получает или задает, экспортировать ли диффузный цвет вершины. |
| [ExportVertexSpecular](../../aspose.threed.formats/u3dsaveoptions/exportvertexspecular/) { get; set; } | Получает или задает, экспортировать ли зеркальный цвет вершины. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Получает формат файла, указанный в текущих параметрах сохранения/загрузки. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Имя файла экспортируемой/импортируемой сцены. Это необязательно, но полезно при сериализации внешних ресурсов, таких как материал OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения. |
| [FlipCoordinateSystem](../../aspose.threed.formats/u3dsaveoptions/flipcoordinatesystem/) { get; set; } | Получает или задает, следует ли инвертировать систему координат контрольных точек/нормалей при импорте/экспорте. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D находить внешние файлы для загрузки. |
| [MeshCompression](../../aspose.threed.formats/u3dsaveoptions/meshcompression/) { get; set; } | Получает или задает, включать ли сжатие данных сетки. |

### См. также

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


