---
title: "Класс Microsoft3MFSaveOptions"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Formats.Microsoft3MFSaveOptions. Параметры сохранения для файла Microsoft 3MF"
type: docs
weight: 1350
url: /ru/net/aspose.threed.formats/microsoft3mfsaveoptions/
---
## Microsoft3MFSaveOptions class

Параметры сохранения для файла Microsoft 3MF.

```csharp
public class Microsoft3MFSaveOptions : SaveOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Microsoft3MFSaveOptions](microsoft3mfsaveoptions/)() | Создать `Microsoft3MFSaveOptions` |

## Свойства

| Имя | Описание |
| --- | --- |
| [BuildAll](../../aspose.threed.formats/microsoft3mfsaveoptions/buildall/) { get; set; } | Отметьте все геометрии в сцене как печатаемые. Или вы можете вручную отметить узел как печатаемый с помощью [`SetBuildable`](../microsoft3mfformat/setbuildable/) Значение по умолчанию — true |
| [EnableCompression](../../aspose.threed.formats/microsoft3mfsaveoptions/enablecompression/) { get; set; } | Включить сжатие в выходном файле 3mf. Значение по умолчанию — true |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Получает или задает кодировку по умолчанию для текстовых файлов. Значение по умолчанию — null, что означает, что импортёр/экспортер определит, какую кодировку использовать. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Пробовать копировать текстуры, используемые в сцене, в выходной каталог. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Получает формат файла, указанный в текущих параметрах сохранения/загрузки. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Имя файла экспортируемой/импортируемой сцены. Это необязательно, но полезно при сериализации внешних ресурсов, таких как материал OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D находить внешние файлы для загрузки. |

### См. также

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


