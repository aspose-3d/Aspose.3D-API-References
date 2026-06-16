---
title: "IOConfig.FileSystem"
second_title: "Aspose.3D for .NET API 参考"
description: "IOConfig 属性。允许用户处理加载/保存期间外部依赖的管理方式"
type: docs
weight: 40
url: /zh/net/aspose.threed.formats/ioconfig/filesystem/
---
## IOConfig.FileSystem property

允许用户处理在加载/保存期间如何管理外部依赖项。

```csharp
public FileSystem FileSystem { get; set; }
```

## 示例

默认的 FileSystem 是 LocalFileSystem，在服务器端等环境中并不安全，但您可以通过指定不同的实现来覆盖文件系统访问。Aspose.3D 提供了多种 FileSystem 实现，例如：Memory-based file system、Directory-based file system、Dummy file system、Zip file system，您也可以使用自己的实现。

```csharp
Scene scene = new Scene();
var material = new PhongMaterial();
var boxNode = scene.RootNode.CreateChildNode(new Box());
boxNode.Material = material;

var opt = new ObjSaveOptions();
var memFs = new Dictionary<string, MemoryStream>();
opt.FileSystem = FileSystem.CreateMemoryFileSystem(memFs);
using var output = new MemoryStream();
opt.FileName = "output.obj";
scene.Save(output, opt);
//材质将写入名为 output.mtl 的变量 memFs 中
var materialInBytes = memFs["output.mtl"].ToArray();
```

### 另请参见

* class [FileSystem](../../../aspose.threed.utilities/filesystem/)
* class [IOConfig](../)
* namespace [Aspose.ThreeD.Formats](../../ioconfig/)
* assembly [Aspose.3D](../../../)


