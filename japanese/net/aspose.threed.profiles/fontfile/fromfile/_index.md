---
title: "FontFile.FromFile"
second_title: "Aspose.3D for .NET API リファレンス"
description: "FontFile メソッド。ファイル名から FontFile をロードします"
type: docs
weight: 10
url: /ja/net/aspose.threed.profiles/fontfile/fromfile/
---
## FontFile.FromFile method

ファイル名から FontFile をロードする

```csharp
public static FontFile FromFile(string fileName)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileName | 文字列 | フォントファイルへのパス |

### 戻り値

FontFile インスタンス

### 例外

| 例外 | 条件 |
| --- | --- |
| IOException | ファイルの読み取りに失敗したときにスローされます。 |

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

* class [FontFile](../)
* namespace [Aspose.ThreeD.Profiles](../../fontfile/)
* assembly [Aspose.3D](../../../)


