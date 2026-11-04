---
title: "FileFormat.Detect"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод FileFormat. Определяет формат файла из потока данных; имя файла является необязательным для угадывания типов, у которых нет магического заголовка"
type: docs
weight: 460
url: /ru/net/aspose.threed/fileformat/detect/
---
## Detect(Stream, string) {#detect}

Определить формат файла из потока данных, имя файла необязательно для определения типов, у которых нет магического заголовка.

```csharp
public static FileFormat Detect(Stream stream, string fileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток, содержащий данные для определения |
| fileName | String | Исходное имя файла данных, используется как подсказка. |

### Возвращаемое значение

Экземпляр [`FileFormat`](../) обнаруженного типа или null, если не удалось.

### Исключения

| исключение | условие |
| --- | --- |
| IOException | Исключение, выбрасываемое при ошибке чтения данных. |

## Примеры

```csharp
byte[] bytes = new byte[100];//take the bytes from your source
var fmt = FileFormat.Detect(new MemoryStream(bytes), "input-file");
Console.WriteLine($"Input data format: {fmt}");
```

### См. также

* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)

---

## Detect(string) {#detect_1}

Определить формат файла по имени файла, файл должен быть читаемым, чтобы Aspose.3D мог определить формат файла по заголовку.

```csharp
public static FileFormat Detect(string fileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | String | Путь к файлу для определения формата файла. |

### Возвращаемое значение

Экземпляр [`FileFormat`](../) обнаруженного типа или null, если не удалось.

### Исключения

| исключение | условие |
| --- | --- |
| IOException | Исключение, выбрасываемое при ошибке чтения данных. |

## Примеры

```csharp
var fmt = FileFormat.Detect("input.fbx");
Console.WriteLine($"Input file format: {fmt}");
```

### См. также

* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)


