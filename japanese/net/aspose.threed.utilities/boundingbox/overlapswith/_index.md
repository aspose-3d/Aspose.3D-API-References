---
title: "BoundingBox.OverlapsWith"
second_title: "Aspose.3D for .NET API リファレンス"
description: "BoundingBox メソッド。現在のバウンディングボックスが指定されたバウンディングボックスと重なるかどうかを確認します"
type: docs
weight: 140
url: /ja/net/aspose.threed.utilities/boundingbox/overlapswith/
---
## BoundingBox.OverlapsWith method

現在のバウンディングボックスが指定されたバウンディングボックスと重なるかどうかを確認します。

```csharp
public bool OverlapsWith(BoundingBox box)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ボックス | BoundingBox | テストするもう一つのバウンディングボックス |

### 戻り値

現在のバウンディングボックスが与えられたものと重なる場合は true。

## 例

以下のコードは、2つのバウンディングボックスが互いに重なるかどうかを確認する方法を示しています。

```csharp
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
var bbox2 = new BoundingBox(1, 1, 1, 11, 11, 11);
Console.WriteLine("Bounding box overlaps = " + boundingBox.OverlapsWith(bbox2));
```

### 関連項目

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


