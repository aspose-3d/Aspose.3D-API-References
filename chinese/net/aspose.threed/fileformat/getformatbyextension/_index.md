---
title: "FileFormat.GetFormatByExtension"
second_title: "Aspose.3D for .NET API 参考"
description: "FileFormat 方法。根据文件扩展名获取首选文件格式。扩展名应以点开头"
type: docs
weight: 470
url: /zh/net/aspose.threed/fileformat/getformatbyextension/
---
## FileFormat.GetFormatByExtension method

从文件扩展名获取首选文件格式。扩展名应以点（'.'）开头。

```csharp
public static FileFormat GetFormatByExtension(string extensionName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| extensionName | 字符串 | 扩展名以 '.' 开头以进行查询。 |

### 返回值

`[`FileFormat`](../)` 的实例，否则返回 null。

## 示例

以下代码展示了如何使用指定格式将场景保存到内存中

```csharp
Scene scene = new Scene(new Box());
var outputFormat = ".glb";
var format = FileFormat.GetFormatByExtension(outputFormat);
using(var ms = new MemoryStream())
{
    scene.Save(ms, format);
}
```

### 另请参见

* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)


