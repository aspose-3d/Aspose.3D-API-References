---
title: "BoundingBox.Contains"
second_title: "Aspose.3D for .NET API リファレンス"
description: "BoundingBox メソッド。点 p がバウンディングボックス内にあるかどうかを確認します"
type: docs
weight: 100
url: /ja/net/aspose.threed.utilities/boundingbox/contains/
---
## Contains(Vector3) {#contains_1}

点 p がバウンディングボックス内にあるかどうかを確認します

```csharp
public bool Contains(Vector3 p)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| p | Vector3 | テストする点 |

### 戻り値

点がバウンディングボックスの内部にある場合は True

## 例

以下のコードは、点がバウンディングボックスの内部にあるかどうかを確認する方法を示しています。

```csharp
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
var pt = new Vector3(4, 4, 4);
Console.WriteLine("Bounding box overlaps = " + boundingBox.Contains(pt));
```

### 関連項目

* struct [Vector3](../../vector3/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Contains(BoundingBox) {#contains}

現在のバウンディングボックスの内部にあるかどうかを確認するバウンディングボックス。

```csharp
public bool Contains(BoundingBox bbox)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| bbox | BoundingBox |  |

### 関連項目

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


