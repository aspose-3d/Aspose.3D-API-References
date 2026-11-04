---
title: "PdfFormat.Extract"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод PdfFormat. Извлекать необработанное 3D‑содержимое из PDF‑файла."
type: docs
weight: 10
url: /ru/net/aspose.threed.formats/pdfformat/extract/
---
## Extract(string, byte[]) {#extract_1}

Извлечь необработанное 3D‑содержание из PDF‑файла.

```csharp
public List<byte[]> Extract(string fileName, byte[] password = null)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | String | Имя входного PDF‑файла. |
| пароль | Byte[] | Пароль PDF‑файла. |

### Возвращаемое значение

Список всех 3D‑содержимых в виде байтов, включая форматы, которые не поддерживает Aspose.3D.

## Примеры

Следующий код показывает, как извлечь все необработанные 3D‑содержимое из 3D PDF‑файла и записать его в файлы.

```csharp
var raw3DContents = FileFormat.PDF.Extract("input.pdf");
for (int i = 0; i < raw3DContents.Count; i++)
{
    File.WriteAllBytes("raw-3d-" + i, raw3DContents[i]);
}
```

### См. также

* class [PdfFormat](../)
* namespace [Aspose.ThreeD.Formats](../../pdfformat/)
* assembly [Aspose.3D](../../../)

---

## Extract(Stream, byte[]) {#extract}

Извлечь необработанное 3D‑содержание из PDF‑потока.

```csharp
public List<byte[]> Extract(Stream stream, byte[] password = null)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток входного PDF‑файла |
| пароль | Byte[] | Пароль PDF‑файла. |

### Возвращаемое значение

Список всех 3D‑содержимых в виде байтов, включая форматы, которые не поддерживает Aspose.3D.

## Примеры

Следующий код показывает, как извлечь все необработанные 3D‑содержимое из 3D PDF‑файла и записать его в файлы.

```csharp
var raw3DContents = FileFormat.PDF.Extract("input.pdf");
for (int i = 0; i < raw3DContents.Count; i++)
{
    File.WriteAllBytes("raw-3d-" + i, raw3DContents[i]);
}
```

### См. также

* class [PdfFormat](../)
* namespace [Aspose.ThreeD.Formats](../../pdfformat/)
* assembly [Aspose.3D](../../../)


