---
title: "Класс ColladaSaveOptions"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Formats.ColladaSaveOptions. Параметры сохранения для Collada"
type: docs
weight: 1100
url: /ru/net/aspose.threed.formats/colladasaveoptions/
---
## ColladaSaveOptions class

Параметры сохранения для collada

```csharp
public class ColladaSaveOptions : SaveOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ColladaSaveOptions](colladasaveoptions/)() | Конструктор `ColladaSaveOptions` |

## Свойства

| Имя | Описание |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Получает или задает кодировку по умолчанию для текстовых файлов. Значение по умолчанию — null, что означает, что импортёр/экспортер определит, какую кодировку использовать. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Пробовать копировать текстуры, используемые в сцене, в выходной каталог. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Получает формат файла, указанный в текущих параметрах сохранения/загрузки. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Имя файла экспортируемой/импортируемой сцены. Это необязательно, но полезно при сериализации внешних ресурсов, таких как материал OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения. |
| [Indented](../../aspose.threed.formats/colladasaveoptions/indented/) { get; set; } | Получает или задает, будет ли экспортированный XML‑документ отформатирован с отступами. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D находить внешние файлы для загрузки. |
| [TransformStyle](../../aspose.threed.formats/colladasaveoptions/transformstyle/) { get; set; } | Получает или задает стиль трансформации узла |

### См. также

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


