---
title: UsdSaveOptions
second_title: Справочник по Aspose.3D для .NET API
description: Параметры сохранения для форматов USD/USDZ.
type: docs
weight: 1390
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
| [UsdSaveOptions](usdsaveoptions#constructor)() | Инициализировать новый[`UsdSaveOptions`](../usdsaveoptions)с[`USD`](../../aspose.threed/fileformat/usd)формат |
| [UsdSaveOptions](usdsaveoptions#constructor_1)(FileFormat) | Инициализировать новый[`UsdSaveOptions`](../usdsaveoptions)с указанным форматом USD/USDZ. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding) { get; set; } | Получает или задает кодировку по умолчанию для текстовых файлов. Значение по умолчанию равно null, что означает, что импортер/экспортер решит, какую кодировку использовать. |
| [ExportMetaData](../../aspose.threed.formats/usdsaveoptions/exportmetadata) { get; set; } | Экспорт свойств узла через поле customData USD. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat) { get; } | Получает формат файла, указанный в текущей опции сохранения/загрузки. |
| [FileName](../../aspose.threed.formats/ioconfig/filename) { get; set; } | Имя файла сцены экспорта/импорта. Это необязательно, но полезно при сериализации внешних ресурсов, таких как материал OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem) { get; set; } | Разрешить пользователю управлять внешними зависимостями во время загрузки/сохранения. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths) { get; set; } | Некоторые файлы, такие как OBJ, зависят от внешнего файла, пути поиска позволяют Aspose.3D искать внешний файл для загрузки. |
| [PrimitiveToMesh](../../aspose.threed.formats/usdsaveoptions/primitivetomesh) { get; set; } | Преобразование объектов-примитивов в меш во время экспорта. Или напрямую закодировать примитивы в выходной файл (используется определение расширения Aspose для неофициальных примитивов, таких как Dish, Torus) Значение по умолчанию - true. |

### Смотрите также

* class [SaveOptions](../saveoptions)
* пространство имен [Aspose.ThreeD.Formats](../../aspose.threed.formats)
* сборка [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->