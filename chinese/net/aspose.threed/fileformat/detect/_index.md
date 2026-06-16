---
title: "FileFormat.Detect"
second_title: "Aspose.3D for .NET API 参考"
description: "FileFormat 方法。从数据流检测文件格式，文件名是可选的，用于猜测没有魔术头的类型"
type: docs
weight: 460
url: /zh/net/aspose.threed/fileformat/detect/
---
## Detect(Stream, string) {#detect}

从数据流检测文件格式，文件名是可选的，用于猜测没有魔术头的类型。

```csharp
public static FileFormat Detect(Stream stream, string fileName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 用于检测的数据流 |
| fileName | 字符串 | 数据的原始文件名，用作提示。 |

### 返回值

检测到的类型的 [`FileFormat`](../) 实例，如果失败则为 null。

### 异常

| 异常 | 条件 |
| --- | --- |
| IOException | 读取数据失败时抛出的异常。 |

## 示例

```csharp
byte[] bytes = new byte[100];//take the bytes from your source
var fmt = FileFormat.Detect(new MemoryStream(bytes), "input-file");
Console.WriteLine($"Input data format: {fmt}");
```

### 另请参见

* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)

---

## Detect(string) {#detect_1}

从文件名检测文件格式，文件必须可读取，以便 Aspose.3D 能通过文件头检测文件格式。

```csharp
public static FileFormat Detect(string fileName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | 字符串 | 用于检测文件格式的文件路径。 |

### 返回值

检测到的类型的 [`FileFormat`](../) 实例，如果失败则为 null。

### 异常

| 异常 | 条件 |
| --- | --- |
| IOException | 读取数据失败时抛出的异常。 |

## 示例

```csharp
var fmt = FileFormat.Detect("input.fbx");
Console.WriteLine($"Input file format: {fmt}");
```

### 另请参见

* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)


