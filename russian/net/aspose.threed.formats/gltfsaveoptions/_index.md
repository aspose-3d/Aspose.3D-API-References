---
title: "Класс GltfSaveOptions"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Formats.GltfSaveOptions. Параметры сохранения для формата glTF"
type: docs
weight: 1280
url: /ru/net/aspose.threed.formats/gltfsaveoptions/
---
## GltfSaveOptions class

Параметры сохранения для формата glTF.

```csharp
public class GltfSaveOptions : SaveOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [GltfSaveOptions](gltfsaveoptions/#constructor)(FileContentType) | Конструктор `GltfSaveOptions` |
| [GltfSaveOptions](gltfsaveoptions/#constructor_1)(FileFormat) | Конструктор `GltfSaveOptions` |

## Свойства

| Имя | Описание |
| --- | --- |
| [ApplyUnitScale](../../aspose.threed.formats/gltfsaveoptions/applyunitscale/) { get; set; } | Применить [`UnitScaleFactor`](../../aspose.threed/assetinfo/unitscalefactor/) к сетке. Значение по умолчанию — false. |
| [BufferFile](../../aspose.threed.formats/gltfsaveoptions/bufferfile/) { get; set; } | Имя файла внешнего буферного файла, используемого для хранения бинарных данных. Если этот файл не указан, Aspose.3D сгенерирует имя автоматически. Это игнорируется при экспорте glTF в бинарном режиме. |
| [DracoCompression](../../aspose.threed.formats/gltfsaveoptions/dracocompression/) { get; set; } | Получает или задает, включено ли сжатие draco |
| [EmbedAssets](../../aspose.threed.formats/gltfsaveoptions/embedassets/) { get; set; } | Встраивает все внешние ресурсы в виде base64 в один файл в режиме ASCII, значение по умолчанию — false. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Получает или задает кодировку по умолчанию для текстовых файлов. Значение по умолчанию — null, что означает, что импортёр/экспортер определит, какую кодировку использовать. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Пробовать копировать текстуры, используемые в сцене, в выходной каталог. |
| [ExternalDracoEncoder](../../aspose.threed.formats/gltfsaveoptions/externaldracoencoder/) { get; set; } | Использовать внешний кодировщик draco для ускорения скорости сжатия draco. |
| [FallbackNormal](../../aspose.threed.formats/gltfsaveoptions/fallbacknormal/) { get; set; } | Когда экспортёр GLTF2 обнаруживает недопустимую нормаль, вместо её оригинального значения будет использовано это значение, чтобы обойти проверку. Значение по умолчанию — (0, 1, 0). |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Получает формат файла, указанный в текущих параметрах сохранения/загрузки. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Имя файла экспортируемой/импортируемой сцены. Это необязательно, но полезно при сериализации внешних ресурсов, таких как материал OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения. |
| [FlipTexCoordV](../../aspose.threed.formats/gltfsaveoptions/fliptexcoordv/) { get; set; } | Инвертировать компонент v(t) текстурных координат, значение по умолчанию — true. |
| [ImageFormat](../../aspose.threed.formats/gltfsaveoptions/imageformat/) { get; set; } | Стандартный glTF поддерживает только PNG/JPG в качестве формата текстур, эта опция определяет, как Aspose.3D будет конвертировать нестандартные изображения в поддерживаемый формат во время экспорта. Значение по умолчанию — Png. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D находить внешние файлы для загрузки. |
| [MaterialConverter](../../aspose.threed.formats/gltfsaveoptions/materialconverter/) { get; set; } | Пользовательский конвертер для преобразования материала геометрии в материал PBR. Если он не задан, экспортёр glTF 2.0 автоматически преобразует стандартный материал в материал PBR. Значение по умолчанию — null. Это свойство используется при экспорте сцены в файл glTF 2.0. |
| [PrettyPrint](../../aspose.threed.formats/gltfsaveoptions/prettyprint/) { get; set; } | JSON‑содержимое файла GLTF форматируется с отступами для удобства чтения человеком, значение по умолчанию — false. |
| [SaveExtras](../../aspose.threed.formats/gltfsaveoptions/saveextras/) { get; set; } | Сохранять динамические свойства объектов сцены в поля 'extra' в сгенерированном файле glTF. Это полезно для предоставления данных, специфичных для приложения. Значение по умолчанию — false. |
| [UseCommonMaterials](../../aspose.threed.formats/gltfsaveoptions/usecommonmaterials/) { get; set; } | Сериализовать материалы с использованием общих расширений материалов KHR, значение по умолчанию — false. Установка этого параметра в false приведёт к тому, что Aspose.3D экспортирует набор вершинных/фрагментных шейдеров, если включён ExportShaders. |

### См. также

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


