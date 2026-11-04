---
title: "LocalFileSystem"
second_title: "Справочник API Aspose.3D для .NET"
description: 
type: docs
weight: 2650
url: /ru/net/aspose.threed.utilities/localfilesystem/
---
## LocalFileSystem class

[`LocalFileSystem`](../localfilesystem) будет сопоставлять операции чтения/записи с локальной директорией.

```csharp
public class LocalFileSystem : FileSystem
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [LocalFileSystem](localfilesystem)(string) | Инициализируйте новый [`LocalFileSystem`](../localfilesystem) с указанным базовым каталогом. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [Dispose](../../aspose.threed.utilities/filesystem/dispose)() | Освободите файловую систему и освободите её ресурсы. |
| override [ReadFile](../../aspose.threed.utilities/localfilesystem/readfile)(string, IOConfig) | Создайте поток для чтения зависимостей. |
| override [WriteFile](../../aspose.threed.utilities/localfilesystem/writefile)(string, IOConfig) | Создайте поток для записи зависимостей. |

### Примеры

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

* class [FileSystem](../filesystem)
* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities)
* assembly [Aspose.3D](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для Aspose.3D.dll -->
