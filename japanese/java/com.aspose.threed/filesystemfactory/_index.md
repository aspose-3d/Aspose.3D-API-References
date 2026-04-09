---
title: FileSystemFactory
second_title: Aspose.3D for Java API リファレンス
description: そして、デフォルトで com.aspose.threed.LocalFileSystem を作成します。
type: docs
weight: 238
url: /ja/java/com.aspose.threed/filesystemfactory/
---
```
public interface FileSystemFactory
```

[SaveOptions](../../com.aspose.threed/saveoptions) and [LoadOptions](../../com.aspose.threed/loadoptions) will create a com.aspose.threed.LocalFileSystem for default. This can be a security issue in server environment. Use your own [FileSystemFactory](../../com.aspose.threed/filesystemfactory) to [IOConfig.getFileSystemFactory](../../com.aspose.threed/ioconfig\#getFileSystemFactory) to improve server side security.
## Methods

| Method | 説明 |
| --- | --- |
| [call()](#call--) | [SaveOptions](../../com.aspose.threed/saveoptions) と [LoadOptions](../../com.aspose.threed/loadoptions) は、デフォルトで com.aspose.threed.LocalFileSystem を作成します。 |
### call() {#call--}
```
public abstract FileSystem call()
```


[SaveOptions](../../com.aspose.threed/saveoptions) and [LoadOptions](../../com.aspose.threed/loadoptions) will create a com.aspose.threed.LocalFileSystem for default. This can be a security issue in server environment. Use your own [FileSystemFactory](../../com.aspose.threed/filesystemfactory) to [IOConfig.getFileSystemFactory](../../com.aspose.threed/ioconfig\#getFileSystemFactory) to improve server side security.

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem)
