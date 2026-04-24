---
title: FontFile.FromFile
second_title: Aspose.3D for .NET API 参考手册
description: FontFile 方法。 从文件名加载 FontFile
type: docs
weight: 10
url: /zh/net/aspose.threed.profiles/fontfile/fromfile/
---
## FontFile.FromFile method

从文件名加载 FontFile

```csharp
public static FontFile FromFile(string fileName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | 字符串 | 字体文件的路径 |

### 返回值

FontFile 实例

### 异常

| 异常 | 条件 |
| --- | --- |
| IOException | 当读取文件失败时抛出。 |

## 示例

以下代码展示了如何使用指定的字体文件从文本创建 3D 网格。

```csharp
var font = FontFile.FromFile(@"CascadiaCode-Regular.otf");
var text = new Text();
text.Font = font;
text.Content = "ABC";
text.FontSize = 10;
var linear = new LinearExtrusion(text, 10).ToMesh();
var scene = new Scene(linear);
scene.Save(@"test.stl");
```

### 另请参见

* class [FontFile](../)
* namespace [Aspose.ThreeD.Profiles](../../fontfile/)
* assembly [Aspose.3D](../../../)


