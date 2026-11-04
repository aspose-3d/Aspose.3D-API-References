---
title: "Класс UsdSaveOptions"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Formats.UsdSaveOptions. Параметры сохранения для форматов USD/USDZ"
type: docs
weight: 1540
url: /ru/net/aspose.threed.formats/usdsaveoptions/
---
## UsdSaveOptions class

Параметры сохранения для форматов USD/USDZ.

```csharp
public class UsdSaveOptions : SaveOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [UsdSaveOptions](usdsaveoptions/#constructor)() | Инициализировать новый `UsdSaveOptions` с форматом [`USD`](../../aspose.threed/fileformat/usd/) |
| [UsdSaveOptions](usdsaveoptions/#constructor_1)(FileFormat) | Инициализировать новый `UsdSaveOptions` с указанным форматом USD/USDZ. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Получает или задает кодировку по умолчанию для текстовых файлов. Значение по умолчанию — null, что означает, что импортёр/экспортер определит, какую кодировку использовать. |
| [ExportMetaData](../../aspose.threed.formats/usdsaveoptions/exportmetadata/) { get; set; } | Экспортировать свойства узла через поле customData формата USD. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Пробовать копировать текстуры, используемые в сцене, в выходной каталог. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Получает формат файла, указанный в текущих параметрах сохранения/загрузки. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Имя файла экспортируемой/импортируемой сцены. Это необязательно, но полезно при сериализации внешних ресурсов, таких как материал OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D находить внешние файлы для загрузки. |
| [MaterialConverter](../../aspose.threed.formats/usdsaveoptions/materialconverter/) { get; set; } | Пользовательский конвертер для преобразования материала геометрии в материал PBR. Если он не назначен, экспортёр USD автоматически преобразует стандартный материал в материал PBR. Значение по умолчанию — null. |
| [PrimitiveToMesh](../../aspose.threed.formats/usdsaveoptions/primitivetomesh/) { get; set; } | Преобразовывать примитивные сущности в сетку во время экспорта. Либо напрямую кодировать примитивы в выходной файл (будет использовать определение расширения Aspose для неофициальных примитивов, таких как Dish, Torus). Значение по умолчанию — true. |

### См. также

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


