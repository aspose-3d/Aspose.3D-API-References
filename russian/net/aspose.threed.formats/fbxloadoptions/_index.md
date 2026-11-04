---
title: "Класс FbxLoadOptions"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Formats.FbxLoadOptions. Параметры загрузки для формата Fbx"
type: docs
weight: 1170
url: /ru/net/aspose.threed.formats/fbxloadoptions/
---
## FbxLoadOptions class

Параметры загрузки для формата Fbx.

```csharp
public class FbxLoadOptions : LoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [FbxLoadOptions](fbxloadoptions/#constructor)() | Конструктор `FbxLoadOptions` |
| [FbxLoadOptions](fbxloadoptions/#constructor_1)(FileFormat) | Конструктор `FbxLoadOptions` |

## Свойства

| Имя | Описание |
| --- | --- |
| [CompatibleMode](../../aspose.threed.formats/fbxloadoptions/compatiblemode/) { get; set; } | Получает или задает, включить ли совместимый режим. Совместимый режим будет пытаться поддерживать нестандартные определения FBX, такие как PBR-материалы, экспортированные из Blender. Значение по умолчанию — false. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Получает или задает кодировку по умолчанию для текстовых файлов. Значение по умолчанию — null, что означает, что импортёр/экспортер определит, какую кодировку использовать. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Получает формат файла, указанный в текущих параметрах сохранения/загрузки. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Имя файла экспортируемой/импортируемой сцены. Это необязательно, но полезно при сериализации внешних ресурсов, таких как материал OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения. |
| [KeepBuiltinGlobalSettings](../../aspose.threed.formats/fbxloadoptions/keepbuiltinglobalsettings/) { get; set; } | Получает или задает, сохранять ли встроенные свойства в GlobalSettings, которые имеют замену нативного свойства в [`AssetInfo`](../../aspose.threed/assetinfo/). Установите значение true, если хотите полные свойства в GlobalSettings. Значение по умолчанию — false. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D находить внешние файлы для загрузки. |

### См. также

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


