---
title: "MemoryFileSystem"
second_title: "Справочник API Aspose.3D для .NET"
description: 
type: docs
weight: 2680
url: /ru/net/aspose.threed.utilities/memoryfilesystem/
---
## MemoryFileSystem class

Эта [`MemoryFileSystem`](../memoryfilesystem) будет отображать операции чтения/записи в память.

```csharp
public class MemoryFileSystem : FileSystem
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MemoryFileSystem](memoryfilesystem)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [FileNames](../../aspose.threed.utilities/memoryfilesystem/filenames) { get; } | Имена файлов, находящиеся в этой файловой системе памяти. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [Dispose](../../aspose.threed.utilities/filesystem/dispose)() | Освободите файловую систему и освободите её ресурсы. |
| [GetFileContent](../../aspose.threed.utilities/memoryfilesystem/getfilecontent)(string) | Возвращает необработанное содержимое указанного файла. Выбрасывает FileNotFoundException, если указанный файл не существует. |
| override [ReadFile](../../aspose.threed.utilities/memoryfilesystem/readfile)(string, IOConfig) | Создайте поток для чтения зависимостей. |
| override [WriteFile](../../aspose.threed.utilities/memoryfilesystem/writefile)(string, IOConfig) | Создайте поток для записи зависимостей. |

### Примеры

Следующий код показывает, как экспортировать файл в память, включая зависимый файл с помощью MemoryFileSystem.

```csharp
//создать сцену с материалом
Scene scene = new Scene();
scene.RootNode.CreateChildNode(new Box()).Material = new LambertMaterial();
//создать параметр сохранения и указать файловую систему, чтобы зависимый файл был записан в память
var opt = FileFormat.WavefrontOBJ.CreateSaveOptions();
var mfs = new MemoryFileSystem();
opt.FileSystem = mfs;
//имя файла материала obj связано с именем файла obj, поэтому нам нужно явное имя.
opt.FileName = "test.obj";
using (var ms = new MemoryStream())
{
    scene.Save(ms, opt);
}
//файл test.obj был записан в переменную ms, и мы также можем получить содержимое файла test.mtl с помощью
var materialFile = mfs.GetFileContent("test.mtl");
```

### См. также

* class [FileSystem](../filesystem)
* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities)
* assembly [Aspose.3D](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для Aspose.3D.dll -->
