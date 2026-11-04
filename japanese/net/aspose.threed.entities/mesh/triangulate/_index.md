---
title: "Mesh.Triangulate"
second_title: "Aspose.3D for .NET API リファレンス"
description: "Mesh メソッド。三角形化されたメッシュを返します"
type: docs
weight: 120
url: /ja/net/aspose.threed.entities/mesh/triangulate/
---
## Mesh.Triangulate method

三角形化されたメッシュを返す

```csharp
public Mesh Triangulate()
```

### 戻り値

現在のメッシュがすでに三角形化されている場合はそれを返し、そうでなければ新しい三角形化メッシュを計算して返します

## 例

以下のコードはメッシュを三角形化する方法を示しています：

```csharp
//平面メッシュは 4 つの制御点を持つポリゴンが 1 つだけです
var mesh = (new Plane()).ToMesh();
//三角形化された後、新しいメッシュの矩形は 2 つの三角形になります。
var triangulated = mesh.Triangulate();
```

### 関連項目

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


