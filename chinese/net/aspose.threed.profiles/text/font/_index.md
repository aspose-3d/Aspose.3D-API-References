---
title: Text.Font
second_title: Aspose.3D for .NET API 参考手册
description: Text 属性。文本的字体
type: docs
weight: 30
url: /zh/net/aspose.threed.profiles/text/font/
---
## Text.Font property

文本的字体。

```csharp
public FontFile Font { get; set; }
```

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

* class [FontFile](../../fontfile/)
* class [Text](../)
* namespace [Aspose.ThreeD.Profiles](../../text/)
* assembly [Aspose.3D](../../../)


