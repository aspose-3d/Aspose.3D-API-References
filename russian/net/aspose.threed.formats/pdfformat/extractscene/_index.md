---
title: "PdfFormat.ExtractScene"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод PdfFormat. Извлекает 3D‑сцены из PDF‑файла"
type: docs
weight: 20
url: /ru/net/aspose.threed.formats/pdfformat/extractscene/
---
## ExtractScene(string) {#extractscene_1}

Извлечь 3D‑сцены из PDF‑файла.

```csharp
public List<Scene> ExtractScene(string fileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | String | Имя входного PDF‑файла. |

### Возвращаемое значение

Список декодированных 3D‑сцен, поддерживаемых Aspose.3D

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

* class [Scene](../../../aspose.threed/scene/)
* class [PdfFormat](../)
* namespace [Aspose.ThreeD.Formats](../../pdfformat/)
* assembly [Aspose.3D](../../../)

---

## ExtractScene(string, byte[]) {#extractscene_2}

Извлечь 3D‑сцены из PDF‑файла.

```csharp
public List<Scene> ExtractScene(string fileName, byte[] password)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | String | Имя входного PDF‑файла. |
| пароль | Byte[] | Пароль PDF‑файла. |

### Возвращаемое значение

Список декодированных 3D‑сцен, поддерживаемых Aspose.3D

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

* class [Scene](../../../aspose.threed/scene/)
* class [PdfFormat](../)
* namespace [Aspose.ThreeD.Formats](../../pdfformat/)
* assembly [Aspose.3D](../../../)

---

## ExtractScene(Stream, byte[]) {#extractscene}

Извлечь необработанное 3D‑содержание из PDF‑потока.

```csharp
public List<Scene> ExtractScene(Stream stream, byte[] password = null)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток входного PDF‑файла |
| пароль | Byte[] | Пароль PDF‑файла. |

### Возвращаемое значение

Список декодированных 3D‑сцен, поддерживаемых Aspose.3D

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

* class [Scene](../../../aspose.threed/scene/)
* class [PdfFormat](../)
* namespace [Aspose.ThreeD.Formats](../../pdfformat/)
* assembly [Aspose.3D](../../../)


