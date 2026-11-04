---
title: "Mesh.op_BitwiseOr"
second_title: "Aspose.3D for .NET API リファレンス"
description: "Mesh メソッド。2 つのメッシュの合体を計算します"
type: docs
weight: 140
url: /ja/net/aspose.threed.entities/mesh/op_bitwiseor/
---
## Mesh BitwiseOr operator

2 つのメッシュの合体を計算する

```csharp
public static Mesh operator |(Mesh a, Mesh b)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| a | Mesh | 最初のメッシュ |
| b | Mesh | 2 番目のメッシュ |

### 戻り値

結果のメッシュ

## 例

以下のコードは、2 つのメッシュを 1 つのメッシュに結合する方法を示しています:

```csharp
var box1 = new Box(10, 10, 1).ToMesh();
var box2 = new Box(1, 1, 10).ToMesh();
var merged = box1 | box2;
```

### 関連項目

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


