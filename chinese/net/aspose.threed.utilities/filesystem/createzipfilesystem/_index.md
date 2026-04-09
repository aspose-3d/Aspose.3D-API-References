---
title: FileSystem.CreateZipFileSystem
second_title: Aspose.3D for .NET API 参考手册
description: FileSystem 方法。创建一个文件系统，以提供对指定 zip 文件或 zip 流的只读访问。文件系统将在打开/保存操作后被释放。
type: docs
weight: 40
url: /zh/net/aspose.threed.utilities/filesystem/createzipfilesystem/
---
## CreateZipFileSystem(Stream, string) {#createzipfilesystem}

创建一个文件系统，以提供对指定 zip 文件或 zip 流的只读访问。文件系统将在打开/保存操作后被释放。

```csharp
public static FileSystem CreateZipFileSystem(Stream stream, string baseDir = "/")
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | Stream | 用于访问 zip 文件的流 |
| baseDir | 字符串 | zip 文件内部的基目录。 |

### 返回值

zip 文件系统

### 异常

| 异常 | 条件 |
| --- | --- |
| IOException | 当从流读取失败时抛出。 |

## 备注

这是只读文件系统，因此不支持写入操作。

## 示例

以下代码展示了如何导入文件，并在 zip 存档文件中提供依赖文件。

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//创建一个加载选项实例并指定 zip 文件系统
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateZipFileSystem("textures.zip");
//加载文件
var scene = Scene.FromFile(inputFile, opt);
```

### 另请参见

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)

---

## CreateZipFileSystem(string) {#createzipfilesystem_1}

文件系统，以提供对指定 zip 文件或 zip 流的只读访问。文件系统将在打开/保存操作后被释放。

```csharp
public static FileSystem CreateZipFileSystem(string fileName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | 字符串 | zip 文件的文件名。 |

### 返回值

zip 文件系统

### 异常

| 异常 | 条件 |
| --- | --- |
| IOException | 当从流读取失败时抛出。 |

## 示例

以下代码展示了如何导入文件，并在 zip 存档文件中提供依赖文件。

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//创建一个加载选项实例并指定 zip 文件系统
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateZipFileSystem("textures.zip");
//加载文件
var scene = Scene.FromFile(inputFile, opt);
```

### 另请参见

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


