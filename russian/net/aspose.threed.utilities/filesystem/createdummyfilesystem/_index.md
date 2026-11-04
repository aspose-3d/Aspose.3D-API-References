---
title: "FileSystem.CreateDummyFileSystem"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод FileSystem. Создайте фиктивную файловую систему; операции чтения/записи являются фиктивными."
type: docs
weight: 10
url: /ru/net/aspose.threed.utilities/filesystem/createdummyfilesystem/
---
## FileSystem.CreateDummyFileSystem method

Создайте фиктивную файловую систему, операции чтения/записи являются фиктивными.

```csharp
public static FileSystem CreateDummyFileSystem()
```

### Возвращаемое значение

Фиктивная файловая система

## Примеры

Следующий код показывает, как экспортировать файл в память и игнорировать генерацию всех зависимых файлов.

```csharp
//создать сцену с материалом
Scene scene = new Scene();
scene.RootNode.CreateChildNode(new Box()).Material = new LambertMaterial();
//создать параметр сохранения и указать файловую систему, чтобы зависимый файл был записан в память
var opt = FileFormat.WavefrontOBJ.CreateSaveOptions();
var dfs = FileSystem.CreateDummyFileSystem();
opt.FileSystem = dfs;
//имя файла материала obj связано с именем файла obj, поэтому нам нужно явное имя.
opt.FileName = "test.obj";
using (var ms = new MemoryStream())
{
    scene.Save(ms, opt);
}
```

### См. также

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


