---
title: "FileSystemFactory"
second_title: "Aspose.3D for Java API 参考"
description: "并将创建一个默认的 com.aspose.threed.LocalFileSystem。"
type: docs
weight: 238
url: /zh/java/com.aspose.threed/filesystemfactory/
---
```
public interface FileSystemFactory
```

[SaveOptions](../../com.aspose.threed/saveoptions) and [LoadOptions](../../com.aspose.threed/loadoptions) will create a com.aspose.threed.LocalFileSystem for default. This can be a security issue in server environment. Use your own [FileSystemFactory](../../com.aspose.threed/filesystemfactory) to [IOConfig.getFileSystemFactory](../../com.aspose.threed/ioconfig\#getFileSystemFactory) to improve server side security.
## 方法

| 方法 | 描述 |
| --- | --- |
| [call()](#call--) | [SaveOptions](../../com.aspose.threed/saveoptions) 和 [LoadOptions](../../com.aspose.threed/loadoptions) 将创建一个默认的 com.aspose.threed.LocalFileSystem。 |
### call() {#call--}
```
public abstract FileSystem call()
```


[SaveOptions](../../com.aspose.threed/saveoptions) and [LoadOptions](../../com.aspose.threed/loadoptions) will create a com.aspose.threed.LocalFileSystem for default. This can be a security issue in server environment. Use your own [FileSystemFactory](../../com.aspose.threed/filesystemfactory) to [IOConfig.getFileSystemFactory](../../com.aspose.threed/ioconfig\#getFileSystemFactory) to improve server side security.

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem)
