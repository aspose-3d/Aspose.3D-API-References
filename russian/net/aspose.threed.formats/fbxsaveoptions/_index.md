---
title: "Класс FbxSaveOptions"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Formats.FbxSaveOptions. Параметры сохранения для файла Fbx"
type: docs
weight: 1180
url: /ru/net/aspose.threed.formats/fbxsaveoptions/
---
## FbxSaveOptions class

Параметры сохранения для файла Fbx.

```csharp
public class FbxSaveOptions : SaveOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [FbxSaveOptions](fbxsaveoptions/#constructor)(FileContentType) | Инициализировать `FbxSaveOptions`, используя последнюю поддерживаемую версию. |
| [FbxSaveOptions](fbxsaveoptions/#constructor_1)(FileFormat) | Инициализирует `FbxSaveOptions` |

## Свойства

| Имя | Описание |
| --- | --- |
| [EmbedTextures](../../aspose.threed.formats/fbxsaveoptions/embedtextures/) { get; set; } | Получает или задает, встраивать ли текстуру в конечный выходной файл. Экспортер FBX попытается найти необработанные данные текстуры из [`FileSystem`](../ioconfig/filesystem/), и встроит файл в конечный FBX файл. Значение по умолчанию false. |
| [EnableCompression](../../aspose.threed.formats/fbxsaveoptions/enablecompression/) { get; set; } | Сжатие больших бинарных данных в файле FBX (например, данные анимации, контрольные точки, данные элементов вершин, индексы), значение по умолчанию true. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Получает или задает кодировку по умолчанию для текстовых файлов. Значение по умолчанию — null, что означает, что импортёр/экспортер определит, какую кодировку использовать. |
| [ExportLegacyMaterialProperties](../../aspose.threed.formats/fbxsaveoptions/exportlegacymaterialproperties/) { get; set; } | Получает или задает, следует ли экспортировать устаревшие свойства материалов, используемые для обратной совместимости. Эта опция включена по умолчанию. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Пробовать копировать текстуры, используемые в сцене, в выходной каталог. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Получает формат файла, указанный в текущих параметрах сохранения/загрузки. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Имя файла экспортируемой/импортируемой сцены. Это необязательно, но полезно при сериализации внешних ресурсов, таких как материал OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения. |
| [FoldRepeatedCurveData](../../aspose.threed.formats/fbxsaveoptions/foldrepeatedcurvedata/) { get; set; } | Получает или задает, следует ли повторно использовать повторяющиеся данные кривой, увеличивая счетчик ссылок последних данных. |
| [GenerateVertexElementMaterial](../../aspose.threed.formats/fbxsaveoptions/generatevertexelementmaterial/) { get; set; } | Получает или задает, следует ли всегда генерировать [`VertexElementMaterial`](../../aspose.threed.entities/vertexelementmaterial/) для геометрий, если присоединенный узел содержит материалы. По умолчанию эта опция отключена. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D находить внешние файлы для загрузки. |
| [ReusePrimitiveMesh](../../aspose.threed.formats/fbxsaveoptions/reuseprimitivemesh/) { get; set; } | Повторно использовать сетку для примитивов с одинаковыми параметрами, это значительно уменьшит размер вывода FBX, если сцена была построена большим набором примитивных форм (например, импортированных из файлов CAD). Значение по умолчанию — false. |
| [VideoForTexture](../../aspose.threed.formats/fbxsaveoptions/videofortexture/) { get; set; } | Получает или задает, следует ли генерировать объект Video для [`Texture`](../../aspose.threed.shading/texture/) при экспорте в FBX. |

### См. также

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


