---
title: "Класс DracoSaveOptions"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Formats.DracoSaveOptions. Параметры сохранения для файлов Google Draco"
type: docs
weight: 1160
url: /ru/net/aspose.threed.formats/dracosaveoptions/
---
## DracoSaveOptions class

Параметры сохранения для файлов Google draco

```csharp
public class DracoSaveOptions : SaveOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [DracoSaveOptions](dracosaveoptions/)() | Создать конфигурацию по умолчанию для сохранения файлов Draco. |

## Свойства

| Имя | Описание |
| --- | --- |
| [ApplyUnitScale](../../aspose.threed.formats/dracosaveoptions/applyunitscale/) { get; set; } | Применить [`UnitScaleFactor`](../../aspose.threed/assetinfo/unitscalefactor/) к сетке. Значение по умолчанию — false. |
| [ColorBits](../../aspose.threed.formats/dracosaveoptions/colorbits/) { get; set; } | Биты квантизации для цвета вершины, значение по умолчанию — 10 |
| [CompressionLevel](../../aspose.threed.formats/dracosaveoptions/compressionlevel/) { get; set; } | Уровень сжатия, значение по умолчанию — Standard |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Получает или задает кодировку по умолчанию для текстовых файлов. Значение по умолчанию — null, что означает, что импортёр/экспортер определит, какую кодировку использовать. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Пробовать копировать текстуры, используемые в сцене, в выходной каталог. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Получает формат файла, указанный в текущих параметрах сохранения/загрузки. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Имя файла экспортируемой/импортируемой сцены. Это необязательно, но полезно при сериализации внешних ресурсов, таких как материал OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D находить внешние файлы для загрузки. |
| [NormalBits](../../aspose.threed.formats/dracosaveoptions/normalbits/) { get; set; } | Биты квантизации для нормальных векторов, значение по умолчанию — 10 |
| [PointCloud](../../aspose.threed.formats/dracosaveoptions/pointcloud/) { get; set; } | Экспортировать сцену как облако точек, значение по умолчанию — false. |
| [PositionBits](../../aspose.threed.formats/dracosaveoptions/positionbits/) { get; set; } | Биты квантизации для позиции, значение по умолчанию — 14 |
| [TextureCoordinateBits](../../aspose.threed.formats/dracosaveoptions/texturecoordinatebits/) { get; set; } | Биты квантизации для координат текстуры, значение по умолчанию — 12 |

### См. также

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


