---
title: "FileFormat.ContentType"
second_title: "Aspose.3D for .NET API 参考"
description: "FileFormat 属性。获取文件格式内容类型"
type: docs
weight: 500
url: /zh/net/aspose.threed/fileformat/contenttype/
---
## FileFormat.ContentType property

获取文件格式的内容类型

```csharp
public FileContentType ContentType { get; }
```

## 示例

```csharp
var format = FileFormat.MayaBinary;
if (format.ContentType == FileContentType.Binary)
    Console.WriteLine($"{format} is binary format");
else
    Console.WriteLine($"{format} is text-based format");
```

### 另请参见

* enum [FileContentType](../../filecontenttype/)
* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)


