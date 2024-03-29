---
title: Matrix4
second_title: Aspose.3D for.NETAPIリファレンス
description: 4x4 マトリックスの実装
type: docs
weight: 2560
url: /ja/net/aspose.threed.utilities/matrix4/
---
## Matrix4 structure

4x4 マトリックスの実装。

```csharp
public struct Matrix4
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Matrix4](matrix4/#constructor_3)(double[]) | の新しいインスタンスを初期化します`Matrix4`構造体. |
| [Matrix4](matrix4/#constructor)(FMatrix4) | コンストラクト`Matrix4`から[`FMatrix4`](../fmatrix4/) instance |
| [Matrix4](matrix4/#constructor_1)(Vector4, Vector4, Vector4, Vector4) | 4 つの行から行列を構築します。 |
| [Matrix4](matrix4/#constructor_2)(double, double, double, double, double, double, double, double, double, double, double, double, double, double, double, double) | の新しいインスタンスを初期化します`Matrix4`構造体. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [Identity](../../aspose.threed.utilities/matrix4/identity/) { get; } | 恒等行列を取得します。 |
| [Determinant](../../aspose.threed.utilities/matrix4/determinant/) { get; } | 行列の行列式を取得します. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [Rotate](../../aspose.threed.utilities/matrix4/rotate/#rotate)(Quaternion) | クォータニオンから回転行列を作成します |
| static [Rotate](../../aspose.threed.utilities/matrix4/rotate/#rotate_1)(double, Vector3) | 回転角と軸で回転行列を作成 |
| static [RotateFromEuler](../../aspose.threed.utilities/matrix4/rotatefromeuler/#rotatefromeuler)(Vector3) | オイラー角から回転行列を作成 |
| static [RotateFromEuler](../../aspose.threed.utilities/matrix4/rotatefromeuler/#rotatefromeuler_1)(double, double, double) | オイラー角から回転行列を作成 |
| static [Scale](../../aspose.threed.utilities/matrix4/scale/#scale_1)(double) | x 軸、y 軸、z 軸に沿ってスケーリングするマトリックスを作成します。 |
| static [Scale](../../aspose.threed.utilities/matrix4/scale/#scale)(Vector3) | x 軸、y 軸、z 軸に沿ってスケーリングするマトリックスを作成します。 |
| static [Scale](../../aspose.threed.utilities/matrix4/scale/#scale_2)(double, double, double) | x 軸、y 軸、z 軸に沿ってスケーリングするマトリックスを作成します。 |
| static [Translate](../../aspose.threed.utilities/matrix4/translate/#translate)(Vector3) | x 軸、y 軸、z 軸に沿って平行移動するマトリックスを作成します |
| static [Translate](../../aspose.threed.utilities/matrix4/translate/#translate_1)(double, double, double) | x 軸、y 軸、z 軸に沿って平行移動するマトリックスを作成します |
| [Concatenate](../../aspose.threed.utilities/matrix4/concatenate/)(Matrix4) | 2 つの行列を連結します |
| [Decompose](../../aspose.threed.utilities/matrix4/decompose/)(out Vector3, out Vector3, out Quaternion) |  |
| [Inverse](../../aspose.threed.utilities/matrix4/inverse/)() | このインスタンスを反転します。 |
| [Normalize](../../aspose.threed.utilities/matrix4/normalize/)() | このインスタンスを正規化します。 |
| [SetTRS](../../aspose.threed.utilities/matrix4/settrs/)(Vector3, Vector3, Vector3) | 平行移動/回転/スケールでマトリックスを初期化 |
| [ToArray](../../aspose.threed.utilities/matrix4/toarray/)() | 行列を配列に変換します。 |
| override [ToString](../../aspose.threed.utilities/matrix4/tostring/)() | を返しますString現在を表すもの`Matrix4`. |
| [Transpose](../../aspose.threed.utilities/matrix4/transpose/)() | このインスタンスを転置します。 |
| [operator *](../../aspose.threed.utilities/matrix4/op_multiply/#op_multiply) | 2 つの行列を掛けます (4 operators) |

## 田畑

| 名前 | 説明 |
| --- | --- |
| [m00](../../aspose.threed.utilities/matrix4/m00/) | m00. |
| [m01](../../aspose.threed.utilities/matrix4/m01/) | m01. |
| [m02](../../aspose.threed.utilities/matrix4/m02/) | m02. |
| [m03](../../aspose.threed.utilities/matrix4/m03/) | m03. |
| [m10](../../aspose.threed.utilities/matrix4/m10/) | m10. |
| [m11](../../aspose.threed.utilities/matrix4/m11/) | m11. |
| [m12](../../aspose.threed.utilities/matrix4/m12/) | m12. |
| [m13](../../aspose.threed.utilities/matrix4/m13/) | m13. |
| [m20](../../aspose.threed.utilities/matrix4/m20/) | m20. |
| [m21](../../aspose.threed.utilities/matrix4/m21/) | m21. |
| [m22](../../aspose.threed.utilities/matrix4/m22/) | m22. |
| [m23](../../aspose.threed.utilities/matrix4/m23/) | m23. |
| [m30](../../aspose.threed.utilities/matrix4/m30/) | m30. |
| [m31](../../aspose.threed.utilities/matrix4/m31/) | m31. |
| [m32](../../aspose.threed.utilities/matrix4/m32/) | m32. |
| [m33](../../aspose.threed.utilities/matrix4/m33/) | m33. |

### 関連項目

* 名前空間 [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* 組み立て [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
