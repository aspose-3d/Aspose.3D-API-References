---
title: "FileSystem.CreateZipFileSystem"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод FileSystem. Создайте файловую систему, предоставляющую только чтение к указанному zip‑файлу или zip‑потоку. Файловая система будет освобождена после операции открытия/сохранения."
type: docs
weight: 40
url: /ru/net/aspose.threed.utilities/filesystem/createzipfilesystem/
---
## CreateZipFileSystem(Stream, string) {#createzipfilesystem}

Создайте файловую систему для предоставления доступа только для чтения к указанному zip‑файлу или zip‑потоку. Файловая система будет освобождена после операции открытия/сохранения.

```csharp
public static FileSystem CreateZipFileSystem(Stream stream, string baseDir = "/")
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток для доступа к zip‑файлу |
| baseDir | String | Базовый каталог внутри zip‑файла. |

### Возвращаемое значение

Zip‑файловая система

### Исключения

| исключение | условие |
| --- | --- |
| IOException | Выбрасывается, когда не удалось прочитать из потока. |

## Примечания

Это файловая система только для чтения, поэтому операции записи не поддерживаются.

## Примеры

Следующий код показывает, как импортировать файл и предоставить зависимые файлы в zip‑архиве.

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//создайте экземпляр параметров загрузки и укажите файловую систему zip
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateZipFileSystem("textures.zip");
//загрузите файл
var scene = Scene.FromFile(inputFile, opt);
```

### См. также

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)

---

## CreateZipFileSystem(string) {#createzipfilesystem_1}

Файловая система, предоставляющая доступ только для чтения к указанному zip‑файлу или zip‑потоку. Файловая система будет освобождена после операции открытия/сохранения.

```csharp
public static FileSystem CreateZipFileSystem(string fileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | String | Имя файла zip‑файла. |

### Возвращаемое значение

Zip‑файловая система

### Исключения

| исключение | условие |
| --- | --- |
| IOException | Выбрасывается, когда не удалось прочитать из потока. |

## Примеры

Следующий код показывает, как импортировать файл и предоставить зависимые файлы в zip‑архиве.

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//создайте экземпляр параметров загрузки и укажите файловую систему zip
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateZipFileSystem("textures.zip");
//загрузите файл
var scene = Scene.FromFile(inputFile, opt);
```

### См. также

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


