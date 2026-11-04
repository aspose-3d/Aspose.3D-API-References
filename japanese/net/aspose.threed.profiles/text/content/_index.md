---
title: "Text.Content"
second_title: "Aspose.3D for .NET API リファレンス"
description: "Text プロパティ。テキストの内容"
type: docs
weight: 20
url: /ja/net/aspose.threed.profiles/text/content/
---
## Text.Content property

テキストの内容

```csharp
public string Content { get; set; }
```

## 例

以下のコードは、指定されたフォントファイルを使用してテキストから 3D メッシュを作成する方法を示しています。

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

### 関連項目

* class [Text](../)
* namespace [Aspose.ThreeD.Profiles](../../text/)
* assembly [Aspose.3D](../../../)


