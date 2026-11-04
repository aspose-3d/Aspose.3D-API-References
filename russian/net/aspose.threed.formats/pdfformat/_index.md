---
title: "Класс PdfFormat"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Formats.PdfFormat. Формат Adobe Portable Document Format"
type: docs
weight: 1380
url: /ru/net/aspose.threed.formats/pdfformat/
---
## PdfFormat class

Портативный формат документов Adobe

```csharp
public class PdfFormat : FileFormat
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
| [Extract](../../aspose.threed.formats/pdfformat/extract/#extract)(Stream, byte[]) | Извлечь необработанное 3D‑содержание из PDF‑потока. |
| [Extract](../../aspose.threed.formats/pdfformat/extract/#extract_1)(string, byte[]) | Извлечь необработанное 3D‑содержание из PDF‑файла. |
| [ExtractScene](../../aspose.threed.formats/pdfformat/extractscene/#extractscene_1)(string) | Извлечь 3D‑сцены из PDF‑файла. |
| [ExtractScene](../../aspose.threed.formats/pdfformat/extractscene/#extractscene)(Stream, byte[]) | Извлечь необработанное 3D‑содержание из PDF‑потока. |
| [ExtractScene](../../aspose.threed.formats/pdfformat/extractscene/#extractscene_2)(string, byte[]) | Извлечь 3D‑сцены из PDF‑файла. |
| override [ToString](../../aspose.threed/fileformat/tostring/)() | Преобразует форматы в строку |

## Примеры

Следующий код показывает, как извлечь все поддерживаемые 3D‑сцены из 3D‑PDF‑файла и записать их в формат obj.

```csharp
var scenes = FileFormat.PDF.ExtractScene("input.pdf");
for(int i = 0; i < scenes.Count; i++) 
{
    scenes[i].Save($"output-{i}.obj");
}
```

### См. также

* class [FileFormat](../../aspose.threed/fileformat/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


