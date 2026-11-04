---
title: "Делегат FileSystemFactory"
second_title: "Справочник API Aspose.3D для .NET"
description: "SaveOptions и LoadOptions по умолчанию создают LocalFileSystem. Это может стать проблемой безопасности в серверной среде. Используйте собственный FileSystemFactory, чтобы улучшить безопасность на стороне сервера."
type: docs
weight: 1190
url: /ru/net/aspose.threed.formats/filesystemfactory/
---
## FileSystemFactory delegate

[`SaveOptions`](../saveoptions/) and [`LoadOptions`](../loadoptions/) will create a LocalFileSystem for default. This can be a security issue in server environment. Use your own `FileSystemFactory` to [`FileSystemFactory`](../ioconfig/filesystemfactory/) to improve server side security.

```csharp
public delegate FileSystem FileSystemFactory();
```

### См. также

* class [FileSystem](../../aspose.threed.utilities/filesystem/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


