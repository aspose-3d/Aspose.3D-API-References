---
title: "クォータニオン"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/quaternion/
---
## Quaternion class

Quaternionはコンピュータグラフィックスで回転を実行するために通常使用されます。


## プロパティ

| 名前 | 説明 |
| --- | --- |
| w | w コンポーネントです。 |
| x | x 成分。 |
| y | y 成分。 |
| z | z 成分。 |
| IDENTITY | 単位四元数。 |

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
| constructor_overload(w, x, y, z) | Quaternion クラスの新しいインスタンスを初期化します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| w | 数 | 四元数の w 成分 |
| x | 数 | 四元数の x 成分 |
| y | 数 | 四元数の y 成分 |
| z | 数 | 四元数の z 成分 |

 **Result:**



---


### getLength{#getLength}

| 名前 | 説明 |
| --- | --- |
| getLength() | 四元数の長さを取得します |

 **Result:**



---


### equals{#equals}

| 名前 | 説明 |
| --- | --- |
| equals(obj) | 二つの四元数が等しいかチェックします |

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
| hashCode() | Quaternion のハッシュコードを取得します |

 **Result:**
数


---


### conjugate{#conjugate}

| 名前 | 説明 |
| --- | --- |
| conjugate() | 現在の四元数の共役四元数を返します |

 **Result:**
クォータニオン


---


### inverse{#inverse}

| 名前 | 説明 |
| --- | --- |
| inverse() | 現在の四元数の逆四元数を返します |

 **Result:**
クォータニオン


---


### dot{#dot}

| 名前 | 説明 |
| --- | --- |
| dot(q) | Dots の積 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| q | クォータニオン | クォータニオン |

 **Result:**
数


---


### eulerAngles{#eulerAngles}

| 名前 | 説明 |
| --- | --- |
| eulerAngles() | クォータニオンをオイラー角で表される回転に変換します。すべての成分はラジアンです。 |

 **Result:**
Vector3


---


### normalize{#normalize}

| 名前 | 説明 |
| --- | --- |
| normalize() | クォータニオンを正規化する |

 **Result:**
クォータニオン


---


### concat{#concat}

| 名前 | 説明 |
| --- | --- |
| concat(rhs) | 2つのクォータニオンを連結する |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| rh | クォータニオン | null |

 **Result:**
クォータニオン


---


### fromAngleAxis{#fromAngleAxis}

| 名前 | 説明 |
| --- | --- |
| fromAngleAxis(a, axis) | 指定された軸の周りにクォータニオンを作成し、時計回りに回転させます |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| a | 数 | 時計回りの回転（ラジアン） |
| axis | Vector3 | 軸 |

 **Result:**
クォータニオン


---


### fromRotation{#fromRotation}

| 名前 | 説明 |
| --- | --- |
| fromRotation(orig, dest) | 元の方向から目的地の方向へ回転するクォータニオンを作成します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| orig | Vector3 | 元の方向 |
| dest | Vector3 | 目的地の方向 |

 **Result:**
クォータニオン


---


### fromEulerAngle{#fromEulerAngle}

| 名前 | 説明 |
| --- | --- |
| fromEulerAngle(pitch, yaw, roll) | 指定されたオイラー角からクォータニオンを作成します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| pitch | 数 | ピッチ（ラジアン） |
| yaw | 数 | ヨー（ラジアン） |
| ロール | 数 | ラジアンでの回転 |

 **Result:**
クォータニオン


---


### fromEulerAngle{#fromEulerAngle}

| 名前 | 説明 |
| --- | --- |
| fromEulerAngle(eulerAngle) | 指定されたオイラー角からクォータニオンを作成します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| eulerAngle | Vector3 | ラジアン単位のオイラー角 |

 **Result:**
クォータニオン


---


### toMatrix{#toMatrix}

| 名前 | 説明 |
| --- | --- |
| toMatrix() | クォータニオンで表現された回転を変換行列に変換します。 |

 **Result:**
Matrix4


---


### toString{#toString}

| 名前 | 説明 |
| --- | --- |
| toString() | クォータニオンの文字列表現を取得します。 |

 **Result:**
文字列


---


### interpolate{#interpolate}

| 名前 | 説明 |
| --- | --- |
| interpolate(t, from, to) | このクォータニオンに、from と to の間の t の値に対する、与えられたクォータニオン引数間の補間値を設定します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| t | 数 | 補間に使用する係数です。 |
| from | クォータニオン | ソースクォータニオン。 |
| to | クォータニオン | ターゲットクォータニオン。 |

 **Result:**
クォータニオン


---



