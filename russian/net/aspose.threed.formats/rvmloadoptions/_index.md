---
title: "Класс RvmLoadOptions"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Formats.RvmLoadOptions. Параметры загрузки файлов RVM системы AVEVA Plant Design Management Systems"
type: docs
weight: 1470
url: /ru/net/aspose.threed.formats/rvmloadoptions/
---
## RvmLoadOptions class

Параметры загрузки для RVM-файла системы AVEVA Plant Design Management System.

```csharp
public class RvmLoadOptions : LoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [RvmLoadOptions](rvmloadoptions/#constructor)() | Создать экземпляр `RvmLoadOptions` |
| [RvmLoadOptions](rvmloadoptions/#constructor_1)(FileContentType) | Создать экземпляр `RvmLoadOptions` |

## Свойства

| Имя | Описание |
| --- | --- |
| [AttributePrefix](../../aspose.threed.formats/rvmloadoptions/attributeprefix/) { get; set; } | Получает или задает префикс атрибутов, определённых во внешних файлах атрибутов. Префикс используется для избежания конфликтов имён, значение по умолчанию — "rvm:". |
| [CenterScene](../../aspose.threed.formats/rvmloadoptions/centerscene/) { get; set; } | Центрировать сцену после её загрузки. |
| [CylinderRadialSegments](../../aspose.threed.formats/rvmloadoptions/cylinderradialsegments/) { get; set; } | Получает или задает количество радиальных сегментов цилиндра, значение по умолчанию — 16. |
| [DishLatitudeSegments](../../aspose.threed.formats/rvmloadoptions/dishlatitudesegments/) { get; set; } | Получает или задает количество широтных сегментов тарелки, значение по умолчанию — 8. |
| [DishLongitudeSegments](../../aspose.threed.formats/rvmloadoptions/dishlongitudesegments/) { get; set; } | Получает или задает количество долготных сегментов тарелки, значение по умолчанию — 12. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Получает или задает кодировку по умолчанию для текстовых файлов. Значение по умолчанию — null, что означает, что импортёр/экспортер определит, какую кодировку использовать. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Получает формат файла, указанный в текущих параметрах сохранения/загрузки. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Имя файла экспортируемой/импортируемой сцены. Это необязательно, но полезно при сериализации внешних ресурсов, таких как материал OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения. |
| [GenerateMaterials](../../aspose.threed.formats/rvmloadoptions/generatematerials/) { get; set; } | Генерировать материалы со случайными цветами для каждого объекта в сцене, если таблица цветов не экспортирована в файле RVM. Значение по умолчанию — true. |
| [LookupAttributes](../../aspose.threed.formats/rvmloadoptions/lookupattributes/) { get; set; } | Получает или задает, следует ли загружать атрибуты из внешнего файла списка атрибутов (.att/.attrib/.txt), значение по умолчанию — true. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D находить внешние файлы для загрузки. |
| [RectangularTorusSegments](../../aspose.threed.formats/rvmloadoptions/rectangulartorussegments/) { get; set; } | Получает или задает количество радиальных сегментов прямоугольного тора, значение по умолчанию — 20. |
| [TorusTubularSegments](../../aspose.threed.formats/rvmloadoptions/torustubularsegments/) { get; set; } | Получает или задает количество трубчатых сегментов тора, значение по умолчанию — 20 |

## Примеры

Следующий код показывает, как настроить параметры тесселяции для примитивных геометрий, импортированных из файла RVM с использованием RvmLoadOptions.

```csharp
RvmLoadOptions opt = new RvmLoadOptions();
opt.RectangularTorusSegments = 30;
opt.CylinderRadialSegments = 20;
opt.DishLatitudeSegments = 20;
opt.DishLongitudeSegments = 20;
opt.CenterScene = true;
var scene = Scene.FromFile("input.rvm", opt);
scene.Save("output.obj");
```

### См. также

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


