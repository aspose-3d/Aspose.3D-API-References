---
title: IOConfig.FileSystemFactory
second_title: Aspose.3D for .NET API Reference
description: IOConfig property. Gets or sets the factory class for FileSystem. The default factory will create LocalFileSystem which is not suitable for server environment
type: docs
weight: 60
url: /net/aspose.threed.formats/ioconfig/filesystemfactory/
---
## IOConfig.FileSystemFactory property

Gets or sets the factory class for FileSystem. The default factory will create LocalFileSystem which is not suitable for server environment.

```csharp
public static FileSystemFactory FileSystemFactory { get; set; }
```

## Examples

The default FileSystem in SaveOptions/LoadOptions is directory-based file system, You can override the default implementation by specify it through IOConfig.FileSystemFactory:

```csharp
IOConfig.FileSystemFactory = () => {
    return FileSystem.CreateDummyFileSystem();
};

Scene scene = new Scene();
var material = new PhongMaterial();
var boxNode = scene.RootNode.CreateChildNode(new Box());
boxNode.Material = material;

//opt.FileSystem would be dummy file system now
var opt = new ObjSaveOptions();
using var output = new MemoryStream();
opt.FileName = "output.obj";
scene.Save(output, opt);
//the material file output.mtl will not be written to any places because we've configured a dummy file system as default implementation.
```

### See Also

* delegate [FileSystemFactory](../../filesystemfactory/)
* class [IOConfig](../)
* namespace [Aspose.ThreeD.Formats](../../ioconfig/)
* assembly [Aspose.3D](../../../)


