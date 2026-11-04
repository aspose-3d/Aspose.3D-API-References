---
title: "DummyFileSystem"
second_title: "Справочник API Aspose.3D для .NET"
description: 
type: docs
weight: 2570
url: /ru/net/aspose.threed.utilities/dummyfilesystem/
---
## DummyFileSystem class

Операции чтения/записи являются фиктивными.

```csharp
public class DummyFileSystem : FileSystem
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [DummyFileSystem](dummyfilesystem)() | Конструктор по умолчанию. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [Dispose](../../aspose.threed.utilities/filesystem/dispose)() | Освободите файловую систему и освободите её ресурсы. |
| override [ReadFile](../../aspose.threed.utilities/dummyfilesystem/readfile)(string, IOConfig) | Создайте поток для чтения зависимостей. |
| override [WriteFile](../../aspose.threed.utilities/dummyfilesystem/writefile)(string, IOConfig) | Создайте поток для записи зависимостей. |

### Примеры

Следующий код показывает, как экспортировать файл в память и игнорировать генерацию всех зависимых файлов.

```csharp
//создать сцену с материалом
Scene scene = new Scene();
scene.RootNode.CreateChildNode(new Box()).Material = new LambertMaterial();
//создать параметр сохранения и указать файловую систему, чтобы зависимый файл был записан в память
var opt = FileFormat.WavefrontOBJ.CreateSaveOptions();
var dfs = new DummyFileSystem();
opt.FileSystem = dfs;
//имя файла материала obj связано с именем файла obj, поэтому нам нужно явное имя.
opt.FileName = "test.obj";
using (var ms = new MemoryStream())
{
    scene.Save(ms, opt);
}
```

### См. также

* class [FileSystem](../filesystem)
* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities)
* assembly [Aspose.3D](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для Aspose.3D.dll -->
