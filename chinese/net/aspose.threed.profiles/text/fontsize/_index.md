---
title: Text.FontSize
second_title: Aspose.3D for .NET API 参考手册
description: Text 属性。字体大小比例
type: docs
weight: 40
url: /zh/net/aspose.threed.profiles/text/fontsize/
---
## Text.FontSize property

字体大小比例。

```csharp
public float FontSize { get; set; }
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

* class [Text](../)
* namespace [Aspose.ThreeD.Profiles](../../text/)
* assembly [Aspose.3D](../../../)


