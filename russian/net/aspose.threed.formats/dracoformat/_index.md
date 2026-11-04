---
title: "Класс DracoFormat"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Formats.DracoFormat. Формат Google Draco"
type: docs
weight: 1150
url: /ru/net/aspose.threed.formats/dracoformat/
---
## DracoFormat class

Формат Google Draco

```csharp
public class DracoFormat : FileFormat
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
| [Decode](../../aspose.threed.formats/dracoformat/decode/#decode)(byte[]) | Декодировать облако точек или сетку из данных в памяти |
| [Decode](../../aspose.threed.formats/dracoformat/decode/#decode_1)(string) | Декодировать облако точек или сетку из указанного имени файла |
| [Encode](../../aspose.threed.formats/dracoformat/encode/#encode)(Entity, DracoSaveOptions) | Кодировать объект в необработанные данные Draco |
| [Encode](../../aspose.threed.formats/dracoformat/encode/#encode_1)(Entity, Stream, DracoSaveOptions) | Кодировать объект в указанный поток |
| [Encode](../../aspose.threed.formats/dracoformat/encode/#encode_2)(Entity, string, DracoSaveOptions) | Кодировать объект в указанный файл |
| override [ToString](../../aspose.threed/fileformat/tostring/)() | Преобразует форматы в строку |

## Примеры

Следующий код показывает, как кодировать и декодировать Mesh в/из массива байтов:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//кодировать сетку в формат Draco
byte[] draco = FileFormat.Draco.Encode(mesh);
//декодировать сетку из формата Draco
Mesh decodedMesh = (Mesh)FileFormat.Draco.Decode(draco);
```

### См. также

* class [FileFormat](../../aspose.threed/fileformat/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


