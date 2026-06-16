---
title: "委托 FileSystemFactory"
second_title: "Aspose.3D for .NET API 参考"
description: "SaveOptions 和 LoadOptions 默认会创建一个 LocalFileSystem。这在服务器环境中可能导致安全问题。使用您自己的 FileSystemFactory 来改进服务器端安全性。"
type: docs
weight: 1190
url: /zh/net/aspose.threed.formats/filesystemfactory/
---
## FileSystemFactory delegate

[`SaveOptions`](../saveoptions/) and [`LoadOptions`](../loadoptions/) will create a LocalFileSystem for default. This can be a security issue in server environment. Use your own `FileSystemFactory` to [`FileSystemFactory`](../ioconfig/filesystemfactory/) to improve server side security.

```csharp
public delegate FileSystem FileSystemFactory();
```

### 另请参见

* class [FileSystem](../../aspose.threed.utilities/filesystem/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


