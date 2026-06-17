---
title: "Vector3"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/vector3/
---
## Vector3 class

3 つの成分を持つベクトル。


## プロパティ

| 名前 | 説明 |
| --- | --- |
| x | x 成分。 |
| y | y 成分。 |
| z | z 成分。 |
| ORIGIN | 原点の位置を取得します。原点。 |
| UNIT_SCALE | 単位スケールベクトルを取得します。 |
| X_AXIS | X軸を取得します。X軸。 |
| Y_AXIS | Y軸を取得します。Y軸。 |
| Z_AXIS | Z軸を取得します。Z軸。 |

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
| constructor_overload(x, y, z) | Vector3構造体の新しいインスタンスを初期化します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| x | 数 | x座標。 |
| y | 数 | y座標。 |
| z | 数 | z座標。 |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| 名前 | 説明 |
| --- | --- |
| constructor_overload2(vec) | Vector3構造体の新しいインスタンスを初期化します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| vec | FVector3 | x座標。 |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| 名前 | 説明 |
| --- | --- |
| constructor_overload3(v) | Vector3構造体の新しいインスタンスを初期化します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| v | 数 | V. |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| 名前 | 説明 |
| --- | --- |
| constructor_overload4(vec4) | Vector3構造体の新しいインスタンスを初期化します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| vec4 | Vector4 | Vec4. |

 **Result:**



---


### getLength2{#getLength2}

| 名前 | 説明 |
| --- | --- |
| getLength2() | 長さの二乗を取得します。length2。 |

 **Result:**



---


### getLength{#getLength}

| 名前 | 説明 |
| --- | --- |
| getLength() | このベクトルの長さを取得します。長さ。 |

 **Result:**



---


### equals{#equals}

| 名前 | 説明 |
| --- | --- |
| equals(obj) | 2つの vector3 が等しいか確認します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| obj | オブジェクト | 等価性をチェックするオブジェクトです。 |

 **Result:**
boolean


---


### hashCode{#hashCode}

| 名前 | 説明 |
| --- | --- |
| hashCode() | Vector3 のハッシュコードを取得します |

 **Result:**
数


---


### dot{#dot}

| 名前 | 説明 |
| --- | --- |
| dot(rhs) | 2つのベクトルのドット積を取得します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| rhs | Vector3 | 右側の値です。 |

 **Result:**
数


---


### normalize{#normalize}

| 名前 | 説明 |
| --- | --- |
| normalize() | このインスタンスを正規化します。 |

 **Result:**
Vector3


---


### sin{#sin}

| 名前 | 説明 |
| --- | --- |
| sin() | 各コンポーネントの正弦を計算します |

 **Result:**
Vector3


---


### cos{#cos}

| 名前 | 説明 |
| --- | --- |
| cos() | 各コンポーネントの余弦を計算します |

 **Result:**
Vector3


---


### cross{#cross}

| 名前 | 説明 |
| --- | --- |
| cross(rhs) | 2つのベクトルの外積 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| rhs | Vector3 | 右側の値です。 |

 **Result:**
Vector3


---


### set{#set}

| 名前 | 説明 |
| --- | --- |
| set(newX, newY, newZ) | 1回の呼び出しで x/y/z コンポーネントを設定します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| newX | 数 | x 成分。 |
| newY | 数 | y 成分。 |
| newZ | 数 | z 成分。 |

 **Result:**
Vector3


---


### toString{#toString}

| 名前 | 説明 |
| --- | --- |
| toString() | 現在の Vector3 を表す java.lang.String を返します。 |

 **Result:**
文字列


---


### angleBetween{#angleBetween}

| 名前 | 説明 |
| --- | --- |
| angleBetween(dir, up) | 2つの方向間の内部角度を計算します。2つの方向は正規化されていないベクトルでも構いません。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| dir | Vector3 | 比較対象となる方向ベクトル |
| up | Vector3 | 2つの方向が共有する平面の上方向ベクトル |

 **Result:**
数


---


### angleBetween{#angleBetween}

| 名前 | 説明 |
| --- | --- |
| angleBetween(dir) | 2つの方向間の内部角度を計算します。2つの方向は正規化されていないベクトルでも構いません。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| dir | Vector3 | 比較対象となる方向ベクトル |

 **Result:**
数


---


### compareTo{#compareTo}

| 名前 | 説明 |
| --- | --- |
| compareTo(other) | 現在のベクトルを別のインスタンスと比較します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| othe | Vector3 | null |

 **Result:**
数


---



