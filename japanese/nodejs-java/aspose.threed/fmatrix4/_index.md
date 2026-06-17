---
title: "FMatrix4"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/fmatrix4/
---
## FMatrix4 class

すべての要素が float 型の 4x4 行列


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
| IDENTITY | 単位行列です。 |

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
| constructor_overload(m00, m01, m02, m03, m10, m11, m12, m13, m20, m21, m22, m23, m30, m31, m32, m33) | FMatrix4 のインスタンスを初期化する |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| m0 | 数 | null |
| m0 | 数 | null |
| m0 | 数 | null |
| m0 | 数 | null |
| m1 | 数 | null |
| m1 | 数 | null |
| m1 | 数 | null |
| m1 | 数 | null |
| m2 | 数 | null |
| m2 | 数 | null |
| m2 | 数 | null |
| m2 | 数 | null |
| m3 | 数 | null |
| m3 | 数 | null |
| m3 | 数 | null |
| m3 | 数 | null |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| 名前 | 説明 |
| --- | --- |
| constructor_overload2(mat) | Matrix4 インスタンスから FMatrix4 のインスタンスを初期化します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| ma | Matrix4 | null |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| 名前 | 説明 |
| --- | --- |
| constructor_overload3(r0, r1, r2, r3) | 4 行から行列を構築します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| r0 | FVector4 | R0. |
| r1 | FVector4 | R1. |
| r2 | FVector4 | R2. |
| r3 | FVector4 | R3. |

 **Result:**



---


### concatenate{#concatenate}

| 名前 | 説明 |
| --- | --- |
| concatenate(m2) | 2 つの行列を連結します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| m2 | FMatrix4 | M2. |

 **Result:**
FMatrix4


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
FMatrix4


---


### transpose{#transpose}

| 名前 | 説明 |
| --- | --- |
| transpose() | このインスタンスを転置します。 |

 **Result:**
FMatrix4


---


### inverse{#inverse}

| 名前 | 説明 |
| --- | --- |
| inverse() | 現在のインスタンスの逆行列を計算します。 |

 **Result:**
FMatrix4


---



