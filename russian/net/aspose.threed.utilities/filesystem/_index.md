---
title: "Класс FileSystem"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Utilities.FileSystem. Инкапсуляция файловой системы. Aspose.3D будет использовать его для чтения/записи зависимостей"
type: docs
weight: 2750
url: /ru/net/aspose.threed.utilities/filesystem/
---
## FileSystem class

Инкапсуляция файловой системы. Aspose.3D будет использовать это для чтения/записи зависимостей.

```csharp
public abstract class FileSystem : IDisposable
```

## Методы

| Имя | Описание |
| --- | --- |
| static [CreateDummyFileSystem](../../aspose.threed.utilities/filesystem/createdummyfilesystem/)() | Создайте фиктивную файловую систему, операции чтения/записи являются фиктивными. |
| static [CreateLocalFileSystem](../../aspose.threed.utilities/filesystem/createlocalfilesystem/)(string) | Инициализируйте новую `FileSystem`, которая работает только с локальным каталогом. Все операции чтения/записи файлов в этом экземпляре FileSystem будут отображаться в указанный каталог. |
| static [CreateMemoryFileSystem](../../aspose.threed.utilities/filesystem/creatememoryfilesystem/)(Dictionary&lt;string, MemoryStream&gt;) |  |
| static [CreateZipFileSystem](../../aspose.threed.utilities/filesystem/createzipfilesystem/#createzipfilesystem_1)(string) | Файловая система, предоставляющая доступ только для чтения к указанному zip‑файлу или zip‑потоку. Файловая система будет освобождена после операции открытия/сохранения. |
| static [CreateZipFileSystem](../../aspose.threed.utilities/filesystem/createzipfilesystem/#createzipfilesystem)(Stream, string) | Создайте файловую систему для предоставления доступа только для чтения к указанному zip‑файлу или zip‑потоку. Файловая система будет освобождена после операции открытия/сохранения. |
| virtual [Dispose](../../aspose.threed.utilities/filesystem/dispose/)() | Освободите файловую систему и освободите её ресурсы. |
| abstract [ReadFile](../../aspose.threed.utilities/filesystem/readfile/)(string, IOConfig) | Создайте поток для чтения зависимостей. |
| abstract [WriteFile](../../aspose.threed.utilities/filesystem/writefile/)(string, IOConfig) | Создайте поток для записи зависимостей. |

## Примеры

Следующий код показывает, как импортировать файл и предоставить зависимые файлы в заданном каталоге

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//создайте экземпляр параметров загрузки и укажите файловую систему zip
var opt = format.CreateLoadOptions();
opt.FileSystem = new LocalFileSystem("textures/");
//загрузите файл
var scene = Scene.FromFile(inputFile, opt);
```

### См. также

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


