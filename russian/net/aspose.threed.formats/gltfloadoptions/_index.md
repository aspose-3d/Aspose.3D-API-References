---
title: "Класс GltfLoadOptions"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Formats.GltfLoadOptions. Параметры загрузки для формата glTF"
type: docs
weight: 1270
url: /ru/net/aspose.threed.formats/gltfloadoptions/
---
## GltfLoadOptions class

Параметры загрузки для формата glTF

```csharp
public class GltfLoadOptions : LoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [GltfLoadOptions](gltfloadoptions/)() | Конструктор `GltfLoadOptions` |

## Свойства

| Имя | Описание |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Получает или задает кодировку по умолчанию для текстовых файлов. Значение по умолчанию — null, что означает, что импортёр/экспортер определит, какую кодировку использовать. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Получает формат файла, указанный в текущих параметрах сохранения/загрузки. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Имя файла экспортируемой/импортируемой сцены. Это необязательно, но полезно при сериализации внешних ресурсов, таких как материал OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения. |
| [FlipTexCoordV](../../aspose.threed.formats/gltfloadoptions/fliptexcoordv/) { get; set; } | Инвертировать координату v(t) в текстурных координатах сетки, значение по умолчанию — true. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D находить внешние файлы для загрузки. |

### См. также

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


