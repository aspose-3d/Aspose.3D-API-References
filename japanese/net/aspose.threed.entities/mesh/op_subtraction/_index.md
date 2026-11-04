---
title: "Mesh.op_Subtraction"
second_title: "Aspose.3D for .NET API リファレンス"
description: "Mesh method. 2つのメッシュの差分を計算します"
type: docs
weight: 150
url: /ja/net/aspose.threed.entities/mesh/op_subtraction/
---
## Mesh Subtraction operator

2つのメッシュの差分を計算します

```csharp
public static Mesh operator -(Mesh a, Mesh b)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| a | Mesh | 最初のメッシュ |
| b | Mesh | 2 番目のメッシュ |

### 戻り値

結果のメッシュ

## 例

以下のコードは、2つのメッシュの差分を計算する方法を示しています:

```csharp
var box1 = new Box(10, 10, 1).ToMesh();
var box2 = new Box(1, 1, 10).ToMesh();
Mesh merged = box1 - box2;
```

### 関連項目

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


