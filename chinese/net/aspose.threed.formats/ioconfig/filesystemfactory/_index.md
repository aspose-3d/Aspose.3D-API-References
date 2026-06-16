---
title: "IOConfig.FileSystemFactory"
second_title: "Aspose.3D for .NET API 参考"
description: "IOConfig 属性。获取或设置 FileSystem 的工厂类。默认工厂将创建 LocalFileSystem，但它不适合服务器环境"
type: docs
weight: 60
url: /zh/net/aspose.threed.formats/ioconfig/filesystemfactory/
---
## IOConfig.FileSystemFactory property

获取或设置 FileSystem 的工厂类。默认工厂将创建 LocalFileSystem，但它不适用于服务器环境。

```csharp
public static FileSystemFactory FileSystemFactory { get; set; }
```

## 示例

SaveOptions/LoadOptions 中的默认 FileSystem 是基于目录的文件系统，您可以通过 IOConfig.FileSystemFactory 指定来覆盖默认实现：

```csharp
IOConfig.FileSystemFactory = () => {
    return FileSystem.CreateDummyFileSystem();
};

Scene scene = new Scene();
var material = new PhongMaterial();
var boxNode = scene.RootNode.CreateChildNode(new Box());
boxNode.Material = material;

//opt.FileSystem 现在将是虚拟文件系统
var opt = new ObjSaveOptions();
using var output = new MemoryStream();
opt.FileName = "output.obj";
scene.Save(output, opt);
//材质文件 output.mtl 将不会写入任何位置，因为我们已将虚拟文件系统配置为默认实现。
```

### 另请参见

* delegate [FileSystemFactory](../../filesystemfactory/)
* class [IOConfig](../)
* namespace [Aspose.ThreeD.Formats](../../ioconfig/)
* assembly [Aspose.3D](../../../)


