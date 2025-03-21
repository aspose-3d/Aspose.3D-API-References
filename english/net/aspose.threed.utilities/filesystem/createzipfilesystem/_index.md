---
title: FileSystem.CreateZipFileSystem
second_title: Aspose.3D for .NET API Reference
description: FileSystem method. Create a file system to provide to the readonly access to speicified zip file or zip stream. File system will be disposed after the open/save operation
type: docs
weight: 40
url: /net/aspose.threed.utilities/filesystem/createzipfilesystem/
---
## CreateZipFileSystem(Stream, string) {#createzipfilesystem}

Create a file system to provide to the read-only access to speicified zip file or zip stream. File system will be disposed after the open/save operation.

```csharp
public static FileSystem CreateZipFileSystem(Stream stream, string baseDir = "/")
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to access the zip file |
| baseDir | String | The base directory inside the zip file. |

### Return Value

A zip file system

### Exceptions

| exception | condition |
| --- | --- |
| IOException | Thrown when failed to read from stream. |

## Remarks

This is a read-only file system, so no write operations are supported.

## Examples

The following code shows how to import file, and provide dependent files in a zip archive file.

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//create a load options instance and specify a zip file system
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateZipFileSystem("textures.zip");
//load the file
var scene = Scene.FromFile(inputFile, opt);
```

### See Also

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)

---

## CreateZipFileSystem(string) {#createzipfilesystem_1}

File system to provide to the read-only access to speicified zip file or zip stream. File system will be disposed after the open/save operation.

```csharp
public static FileSystem CreateZipFileSystem(string fileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | File name to the zip file. |

### Return Value

A zip file system

### Exceptions

| exception | condition |
| --- | --- |
| IOException | Thrown when failed to read from stream. |

## Examples

The following code shows how to import file, and provide dependent files in a zip archive file.

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//create a load options instance and specify a zip file system
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateZipFileSystem("textures.zip");
//load the file
var scene = Scene.FromFile(inputFile, opt);
```

### See Also

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


