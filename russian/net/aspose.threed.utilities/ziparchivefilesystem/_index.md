---
title: "Класс ZipArchiveFileSystem"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Utilities.ZipArchiveFileSystem. Файловая система, предоставляющая доступ только для чтения к указанному zip‑файлу или zip‑потоку. Файловая система будет освобождена после операции открытия/сохранения"
type: docs
weight: 2830
url: /ru/net/aspose.threed.utilities/ziparchivefilesystem/
---
## ZipArchiveFileSystem class

Файловая система, предоставляющая доступ только для чтения к указанному zip‑файлу или zip‑потоку. Файловая система будет освобождена после операции открытия/сохранения.

```csharp
public class ZipArchiveFileSystem : FileSystem
```

## Методы

| Имя | Описание |
| --- | --- |
| override [Dispose](../../aspose.threed.utilities/ziparchivefilesystem/dispose/)() | Освободите ZipArchiveFileSystem и его внутренние ресурсы. |
| override [ReadFile](../../aspose.threed.utilities/ziparchivefilesystem/readfile/)(string, IOConfig) | Открыть файл для чтения |
| override [WriteFile](../../aspose.threed.utilities/ziparchivefilesystem/writefile/)(string, IOConfig) | Открыть файл для записи, не реализовано в этом классе. |

### Примеры

Следующий код показывает, как импортировать файл и предоставить зависимые файлы в zip‑архиве.

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//создайте экземпляр параметров загрузки и укажите файловую систему zip
var opt = format.CreateLoadOptions();
opt.FileSystem = new ZipArchiveFileSystem("textures.zip");
//загрузите файл
var scene = Scene.FromFile(inputFile, opt);
```

### См. также

* class [FileSystem](../filesystem/)
* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


