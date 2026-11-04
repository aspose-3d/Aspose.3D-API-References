---
title: "Класс PlyFormat"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Formats.PlyFormat. Формат PLY."
type: docs
weight: 1430
url: /ru/net/aspose.threed.formats/plyformat/
---
## PlyFormat class

Формат PLY.

```csharp
public class PlyFormat : FileFormat
```

## Свойства

| Имя | Описание |
| --- | --- |
| [CanExport](../../aspose.threed/fileformat/canexport/) { get; } | Получает, поддерживает ли Aspose.3D экспорт сцены в текущий формат файла. |
| [CanImport](../../aspose.threed/fileformat/canimport/) { get; } | Получает, поддерживает ли Aspose.3D импорт сцены из текущего формата файла. |
| [ContentType](../../aspose.threed/fileformat/contenttype/) { get; } | Получает тип содержимого формата файла |
| [Extension](../../aspose.threed/fileformat/extension/) { get; } | Получает имя расширения этого типа. |
| [Extensions](../../aspose.threed/fileformat/extensions/) { get; } | Получает имена расширений этого типа. |
| [FileFormatType](../../aspose.threed/fileformat/fileformattype/) { get; } | Получает тип формата файла |
| [Version](../../aspose.threed/fileformat/version/) { get; } | Получает версию формата файла |

## Методы

| Имя | Описание |
| --- | --- |
| [CreateLoadOptions](../../aspose.threed/fileformat/createloadoptions/)() | Создаёт параметры загрузки по умолчанию для этого формата файла |
| [CreateSaveOptions](../../aspose.threed/fileformat/createsaveoptions/)() | Создаёт параметры сохранения по умолчанию для этого формата файла |
| [Decode](../../aspose.threed.formats/plyformat/decode/#decode)(Stream) | Декодировать облако точек или сетку из указанного потока. |
| [Decode](../../aspose.threed.formats/plyformat/decode/#decode_2)(string) | Декодировать облако точек или сетку из указанного потока. |
| [Decode](../../aspose.threed.formats/plyformat/decode/#decode_1)(Stream, PlyLoadOptions) | Декодировать облако точек или сетку из указанного потока. |
| [Decode](../../aspose.threed.formats/plyformat/decode/#decode_3)(string, PlyLoadOptions) | Декодировать облако точек или сетку из указанного потока. |
| [Encode](../../aspose.threed.formats/plyformat/encode/#encode)(Entity, Stream) | Кодировать объект и сохранить результат в поток. |
| [Encode](../../aspose.threed.formats/plyformat/encode/#encode_2)(Entity, string) | Кодировать объект и сохранить результат во внешний файл. |
| [Encode](../../aspose.threed.formats/plyformat/encode/#encode_1)(Entity, Stream, PlySaveOptions) | Кодировать объект и сохранить результат в поток. |
| [Encode](../../aspose.threed.formats/plyformat/encode/#encode_3)(Entity, string, PlySaveOptions) | Кодировать объект и сохранить результат во внешний файл. |
| override [ToString](../../aspose.threed/fileformat/tostring/)() | Преобразует форматы в строку |

## Примеры

Следующий код показывает, как закодировать сетку в файл PLY:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//закодировать сетку в формат PLY
FileFormat.PLY.Encode(mesh, "sphere.ply");
```

Следующий код показывает, как декодировать сетку из файла PLY:

```csharp
//Создать тестовый файл для декодирования
FileFormat.PLY.Encode(new Sphere(), "sphere.ply");
//Декодировать файл
var mesh = (Mesh)FileFormat.PLY.Decode("sphere.ply")
```

### См. также

* class [FileFormat](../../aspose.threed/fileformat/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


