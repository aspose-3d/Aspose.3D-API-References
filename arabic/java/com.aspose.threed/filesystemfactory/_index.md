---
title: "FileSystemFactory"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "و سيقوم بإنشاء com.aspose.threed.LocalFileSystem كإعداد افتراضي."
type: docs
weight: 238
url: /ar/java/com.aspose.threed/filesystemfactory/
---
```
public interface FileSystemFactory
```

[SaveOptions](../../com.aspose.threed/saveoptions) and [LoadOptions](../../com.aspose.threed/loadoptions) will create a com.aspose.threed.LocalFileSystem for default. This can be a security issue in server environment. Use your own [FileSystemFactory](../../com.aspose.threed/filesystemfactory) to [IOConfig.getFileSystemFactory](../../com.aspose.threed/ioconfig\#getFileSystemFactory) to improve server side security.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [call()](#call--) | [SaveOptions](../../com.aspose.threed/saveoptions) و [LoadOptions](../../com.aspose.threed/loadoptions) سيقومان بإنشاء com.aspose.threed.LocalFileSystem كإعداد افتراضي. |
### call() {#call--}
```
public abstract FileSystem call()
```


[SaveOptions](../../com.aspose.threed/saveoptions) and [LoadOptions](../../com.aspose.threed/loadoptions) will create a com.aspose.threed.LocalFileSystem for default. This can be a security issue in server environment. Use your own [FileSystemFactory](../../com.aspose.threed/filesystemfactory) to [IOConfig.getFileSystemFactory](../../com.aspose.threed/ioconfig\#getFileSystemFactory) to improve server side security.

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem)
