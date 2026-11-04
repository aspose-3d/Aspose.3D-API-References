---
title: "FileSystem.CreateLocalFileSystem"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод FileSystem. Инициализировать новый FileSystem, который работает только с локальным каталогом. Все операции чтения/записи файлов в этом экземпляре FileSystem будут отображаться в указанный каталог"
type: docs
weight: 20
url: /ru/net/aspose.threed.utilities/filesystem/createlocalfilesystem/
---
## FileSystem.CreateLocalFileSystem method

Инициализировать новый [`FileSystem`](../), который работает только с локальным каталогом. Все операции чтения/записи файлов в этом экземпляре FileSystem будут отображаться в указанный каталог.

```csharp
public static FileSystem CreateLocalFileSystem(string directory)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| каталог | String | Каталог в вашей физической файловой системе, выступающий в качестве виртуального корневого каталога. |

### Возвращаемое значение

Новый экземпляр файловой системы для обеспечения локального доступа к файлам

### Исключения

| исключение | условие |
| --- | --- |
| FileNotFoundException | Выбрасывается, когда каталог не может быть найден. |

## Примеры

Следующий код показывает, как импортировать файл и предоставить зависимые файлы в заданном каталоге

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//создайте экземпляр параметров загрузки и укажите локальную файловую систему
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateLocalFileSystem("textures/");
//загрузите файл
var scene = Scene.FromFile(inputFile, opt);
```

### См. также

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


