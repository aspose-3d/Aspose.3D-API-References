---
title: "Класс IOConfig"
second_title: "Справочник API Aspose.3D для .NET"
description: "класс Aspose.ThreeD.Formats.IOConfig. Конфигурация ввода/вывода для сериализации/десериализации. Пользователь может указать детальные конфигурации, такие как путь поиска зависимостей или конфигурации, связанные с форматом, здесь."
type: docs
weight: 1300
url: /ru/net/aspose.threed.formats/ioconfig/
---
## IOConfig class

Конфигурация ввода-вывода для сериализации/десериализации. Пользователь может указать подробные настройки, такие как путь поиска зависимостей или конфигурации, связанные с форматом, здесь.

```csharp
public class IOConfig
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Получает или задает кодировку по умолчанию для текстовых файлов. Значение по умолчанию — null, что означает, что импортёр/экспортер определит, какую кодировку использовать. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Получает формат файла, указанный в текущих параметрах сохранения/загрузки. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Имя файла экспортируемой/импортируемой сцены. Это необязательно, но полезно при сериализации внешних ресурсов, таких как материал OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D находить внешние файлы для загрузки. |
| static [FileSystemFactory](../../aspose.threed.formats/ioconfig/filesystemfactory/) { get; set; } | Получает или задает класс фабрики для FileSystem. Фабрика по умолчанию создаст LocalFileSystem, который не подходит для серверной среды. |

### См. также

* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


