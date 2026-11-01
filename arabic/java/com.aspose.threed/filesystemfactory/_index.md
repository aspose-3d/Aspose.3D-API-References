---
title: "FileSystemFactory"
second_title: "مرجع Aspose.3D لـ Java API"
description: "و  سيُنشئ com.aspose.threed.LocalFileSystem كافتراضي."
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
| [call()](#call--) | [SaveOptions](../../com.aspose.threed/saveoptions) و [LoadOptions](../../com.aspose.threed/loadoptions) سيُنشئان com.aspose.threed.LocalFileSystem كافتراضي. |
### call() {#call--}
```
public abstract FileSystem call()
```


[SaveOptions](../../com.aspose.threed/saveoptions) and [LoadOptions](../../com.aspose.threed/loadoptions) will create a com.aspose.threed.LocalFileSystem for default. This can be a security issue in server environment. Use your own [FileSystemFactory](../../com.aspose.threed/filesystemfactory) to [IOConfig.getFileSystemFactory](../../com.aspose.threed/ioconfig\#getFileSystemFactory) to improve server side security.

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem)
