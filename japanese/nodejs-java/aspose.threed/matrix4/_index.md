---
title: "Matrix4"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/matrix4/
---
## Matrix4 class

4x4 行列の実装です。


## プロパティ

| 名前 | 説明 |
| --- | --- |
| m00 | m00です。 |
| m01 | m01です。 |
| m02 | m02です。 |
| m03 | m03です。 |
| m10 | m10です。 |
| m11 | m11です。 |
| m12 | m12です。 |
| m13 | m13です。 |
| m20 | m20です。 |
| m21 | m21です。 |
| m22 | m22です。 |
| m23 | m23です。 |
| m30 | m30です。 |
| m31 | m31です。 |
| m32 | m32です。 |
| m33 | m33です。 |

## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor() |  |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名前 | 説明 |
| --- | --- |
| constructor_overload(r0, r1, r2, r3) | 4 行から行列を構築します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| r0 | Vector4 | R0. |
| r1 | Vector4 | R1. |
| r2 | Vector4 | R2. |
| r3 | Vector4 | R3. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| 名前 | 説明 |
| --- | --- |
| constructor_overload2(m00, m01, m02, m03, m10, m11, m12, m13, m20, m21, m22, m23, m30, m31, m32, m33) | Matrix4 構造体の新しいインスタンスを初期化します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| m00 | 数 | M00. |
| m01 | 数 | M01. |
| m02 | 数 | M02. |
| m03 | 数 | M03. |
| m10 | 数 | M10. |
| m11 | 数 | M11. |
| m12 | 数 | M12. |
| m13 | 数 | M13. |
| m20 | 数 | M20. |
| m21 | 数 | M21. |
| m22 | 数 | M22. |
| m23 | 数 | M23. |
| m30 | 数 | M30. |
| m31 | 数 | M31. |
| m32 | 数 | M32. |
| m33 | 数 | M33. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| 名前 | 説明 |
| --- | --- |
| constructor_overload3(m) | FMatrix4 インスタンスから Matrix4 を構築します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
|  | FMatrix4 | null |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| 名前 | 説明 |
| --- | --- |
| constructor_overload4(m) | Matrix4 構造体の新しいインスタンスを初期化します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| m | Number[] | M. |

 **Result:**



---


### getIdentity{#getIdentity}

| 名前 | 説明 |
| --- | --- |
| getIdentity() | 単位行列を取得します。単位行列です。 |

 **Result:**



---


### getDeterminant{#getDeterminant}

| 名前 | 説明 |
| --- | --- |
| getDeterminant() | 行列の行列式を取得します。行列式です。 |

 **Result:**



---


### concatenate{#concatenate}

| 名前 | 説明 |
| --- | --- |
| concatenate(m2) | 2 つの行列を連結します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| m2 | Matrix4 | M2. |

 **Result:**
Matrix4


---


### transpose{#transpose}

| 名前 | 説明 |
| --- | --- |
| transpose() | このインスタンスを転置します。 |

 **Result:**
Matrix4


---


### normalize{#normalize}

| 名前 | 説明 |
| --- | --- |
| normalize() | このインスタンスを正規化します。 |

 **Result:**
Matrix4


---


### inverse{#inverse}

| 名前 | 説明 |
| --- | --- |
| inverse() | このインスタンスを逆行列にします。 |

 **Result:**
Matrix4


---


### setTRS{#setTRS}

| 名前 | 説明 |
| --- | --- |
| setTRS(translation, rotation, scale) | 平行移動/回転/スケールで行列を初期化します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| 平行移動 | Vector3 | 平行移動。 |
| 回転 | Vector3 | 回転のオイラー角、フィールドは度単位です。 |
| スケール | Vector3 | スケール。 |

 **Result:**
Matrix4


---


### toArray{#toArray}

| 名前 | 説明 |
| --- | --- |
| toArray() | 行列を配列に変換します。 |

 **Result:**
Number[]


---


### toString{#toString}

| 名前 | 説明 |
| --- | --- |
| toString() | 現在の Matrix4 を表す java.lang.String を返します。 |

 **Result:**
文字列


---


### translate{#translate}

| 名前 | 説明 |
| --- | --- |
| translate(t) | x 軸、y 軸、z 軸に沿って平行移動する行列を作成します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| t | Vector3 | 平行移動オフセット |

 **Result:**
Matrix4


---


### translate{#translate}

| 名前 | 説明 |
| --- | --- |
| translate(tx, ty, tz) | x 軸、y 軸、z 軸に沿って平行移動する行列を作成します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| tx | 数 | X 座標オフセット |
| ty | 数 | Y座標オフセット |
| tz | 数 | Z座標オフセット |

 **Result:**
Matrix4


---


### scale{#scale}

| 名前 | 説明 |
| --- | --- |
| scale(s) | x軸、y軸、z軸に沿って拡大する行列を作成します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| s | Vector3 | スケーリングファクトリはx軸、y軸、z軸に適用されます |

 **Result:**
Matrix4


---


### scale{#scale}

| 名前 | 説明 |
| --- | --- |
| scale(s) | x軸、y軸、z軸に沿って拡大する行列を作成します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| s | 数 | スケーリングファクトリはすべての軸に適用されます |

 **Result:**
Matrix4


---


### scale{#scale}

| 名前 | 説明 |
| --- | --- |
| scale(sx, sy, sz) | x軸、y軸、z軸に沿って拡大する行列を作成します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| sx | 数 | スケーリングファクトリはx軸に適用されます |
| sy | 数 | スケーリングファクトリはy軸に適用されます |
| sz | 数 | スケーリングファクトリはz軸に適用されます |

 **Result:**
Matrix4


---


### rotateFromEuler{#rotateFromEuler}

| 名前 | 説明 |
| --- | --- |
| rotateFromEuler(eul) | Euler角から回転行列を作成します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| eul | Vector3 | ラジアンでの回転 |

 **Result:**
Matrix4


---


### rotateFromEuler{#rotateFromEuler}

| 名前 | 説明 |
| --- | --- |
| rotateFromEuler(rx, ry, rz) | Euler角から回転行列を作成します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| rx | 数 | x軸のラジアンでの回転 |
| ry | 数 | y軸のラジアンでの回転 |
| rz | 数 | z 軸の回転（ラジアン） |

 **Result:**
Matrix4


---


### rotate{#rotate}

| 名前 | 説明 |
| --- | --- |
| rotate(angle, axis) | 回転角と軸で回転行列を作成する |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| angle | 数 | ラジアン単位の回転角 |
| axis | Vector3 | 回転軸 |

 **Result:**
Matrix4


---


### rotate{#rotate}

| 名前 | 説明 |
| --- | --- |
| rotate(q) | クォータニオンから回転行列を作成する |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| q | クォータニオン | 回転クォータニオン |

 **Result:**
Matrix4


---



