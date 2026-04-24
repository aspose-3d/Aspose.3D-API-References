---
title: FileSystemFactory
second_title: Aspose.3D for Java API 레퍼런스
description: 그리고 기본값으로 com.aspose.threed.LocalFileSystem을 생성합니다.
type: docs
weight: 238
url: /ko/java/com.aspose.threed/filesystemfactory/
---
```
public interface FileSystemFactory
```

[SaveOptions](../../com.aspose.threed/saveoptions) and [LoadOptions](../../com.aspose.threed/loadoptions) will create a com.aspose.threed.LocalFileSystem for default. This can be a security issue in server environment. Use your own [FileSystemFactory](../../com.aspose.threed/filesystemfactory) to [IOConfig.getFileSystemFactory](../../com.aspose.threed/ioconfig\#getFileSystemFactory) to improve server side security.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [call()](#call--) | [SaveOptions](../../com.aspose.threed/saveoptions) 및 [LoadOptions](../../com.aspose.threed/loadoptions) 은 기본값으로 com.aspose.threed.LocalFileSystem을 생성합니다. |
### call() {#call--}
```
public abstract FileSystem call()
```


[SaveOptions](../../com.aspose.threed/saveoptions) and [LoadOptions](../../com.aspose.threed/loadoptions) will create a com.aspose.threed.LocalFileSystem for default. This can be a security issue in server environment. Use your own [FileSystemFactory](../../com.aspose.threed/filesystemfactory) to [IOConfig.getFileSystemFactory](../../com.aspose.threed/ioconfig\#getFileSystemFactory) to improve server side security.

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem)
