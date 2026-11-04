---
title: "Mesh.Optimize"
second_title: "Aspose.3D for .NET API リファレンス"
description: "Mesh メソッド。重複した制御点を除去してメッシュのメモリ使用量を最適化します"
type: docs
weight: 100
url: /ja/net/aspose.threed.entities/mesh/optimize/
---
## Optimize(bool) {#optimize}

重複した制御点を除去してメッシュのメモリ使用量を最適化する

```csharp
public Mesh Optimize(bool vertexElements)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| vertexElements | Boolean | 重複した頂点要素データを最適化する |

### 戻り値

コンパクトなメモリ使用量の新しいメッシュインスタンス

## 例

以下のコードは、最適化されていないメッシュから重複した制御点を除去する方法を示しています:

```csharp
//Sphere.ToMesh は 117 個の制御点を生成します
var mesh = (new Sphere()).ToMesh();
//最適化後、制御点は 86 個だけになり、ポリゴンインデックスも再マッピングされます。
var optimized = mesh.Optimize(true);
```

### 関連項目

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## Optimize(bool, float, float, float) {#optimize_1}

重複した制御点を除去してメッシュのメモリ使用量を最適化する

```csharp
public Mesh Optimize(bool vertexElements, float toleranceControlPoint = 1E-09, 
    float toleranceNormal = 1E-09, float toleranceUV = 1E-09)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| vertexElements | Boolean | 重複した頂点要素データを最適化する |
| toleranceControlPoint | 単一 | 制御点の許容誤差、デフォルト値は 1e-9 です |
| toleranceNormal | 単一 | 法線/接線/バイノーマルの許容誤差、デフォルト値は 1e-9 です |
| toleranceUV | 単一 | UV の許容誤差、デフォルト値は 1e-9 です |

### 戻り値

コンパクトなメモリ使用量の新しいメッシュインスタンス

### 関連項目

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


