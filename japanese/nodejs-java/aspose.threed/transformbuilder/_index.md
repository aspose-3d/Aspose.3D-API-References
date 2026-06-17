---
title: "TransformBuilder"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/transformbuilder/
---
## TransformBuilder class

TransformBuilderは変換のチェーンによって変換行列を構築するために使用されます。


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor(initial, order) | 初期変換行列と指定された合成順序で TransformBuilder を構築します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| initia | Matrix4 | null |
| 順序 | ComposeOrder | ComposeOrder |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名前 | 説明 |
| --- | --- |
| constructor_overload(order) | 初期の単位変換行列と指定された合成順序で TransformBuilder を構築します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| 順序 | ComposeOrder | ComposeOrder |

 **Result:**



---


### getMatrix{#getMatrix}

| 名前 | 説明 |
| --- | --- |
| getMatrix() | 現在の行列値を取得または設定します |

 **Result:**



---


### setMatrix{#setMatrix}

| 名前 | 説明 |
| --- | --- |
| setMatrix(value) | 現在の行列値を取得または設定します |

 **Result:**



---


### getComposeOrder{#getComposeOrder}

| 名前 | 説明 |
| --- | --- |
| getComposeOrder() | チェーンの合成順序を取得または設定します。プロパティの値は ComposeOrder の整数定数です。 |

 **Result:**



---


### setComposeOrder{#setComposeOrder}

| 名前 | 説明 |
| --- | --- |
| setComposeOrder(value) | チェーンの合成順序を取得または設定します。プロパティの値は ComposeOrder の整数定数です。 |

 **Result:**



---


### compose{#compose}

| 名前 | 説明 |
| --- | --- |
| compose(m) | 引数を内部行列に追加または前置します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### append{#append}

| 名前 | 説明 |
| --- | --- |
| append(m) | 新しい変換行列を変換チェーンに追加します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### prepend{#prepend}

| 名前 | 説明 |
| --- | --- |
| prepend(m) | 新しい変換行列を変換チェーンの先頭に追加します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### rearrange{#rearrange}

| 名前 | 説明 |
| --- | --- |
| rearrange(newX, newY, newZ) | 軸のレイアウトを再配置します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| newX | 軸 | 軸 |
| newY | 軸 | 軸 |
| newZ | 軸 | 軸 |

 **Result:**



---


### scale{#scale}

| 名前 | 説明 |
| --- | --- |
| scale(s) | コンポーネントが s でスケールされた拡大変換行列をチェーンします。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
|  | 数 | null |

 **Result:**



---


### scale{#scale}

| 名前 | 説明 |
| --- | --- |
| scale(x, y, z) | スケーリング変換行列をチェーンします。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
|  | 数 | null |
|  | 数 | null |
|  | 数 | null |

 **Result:**



---


### scale{#scale}

| 名前 | 説明 |
| --- | --- |
| scale(s) | スケール変換をチェーンします。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### rotateDegree{#rotateDegree}

| 名前 | 説明 |
| --- | --- |
| rotateDegree(angle, axis) | 度単位の回転変換をチェーンします。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| angle | 数 | 回転角度（度） |
| axis | Vector3 | 回転軸 |

 **Result:**



---


### rotateRadian{#rotateRadian}

| 名前 | 説明 |
| --- | --- |
| rotateRadian(angle, axis) | ラジアン単位の回転変換をチェーンします。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| angle | 数 | 回転角度（ラジアン） |
| axis | Vector3 | 回転軸 |

 **Result:**



---


### rotate{#rotate}

| 名前 | 説明 |
| --- | --- |
| rotate(q) | クォータニオンによる回転をチェーンします。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
|  | クォータニオン | null |

 **Result:**



---


### rotateEulerDegree{#rotateEulerDegree}

| 名前 | 説明 |
| --- | --- |
| rotateEulerDegree(degX, degY, degZ) | 度単位のオイラー角による回転をチェーンします。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| 度 | 数 | null |
| 度 | 数 | null |
| 度 | 数 | null |

 **Result:**



---


### rotateEulerRadian{#rotateEulerRadian}

| 名前 | 説明 |
| --- | --- |
| rotateEulerRadian(x, y, z) | ラジアン単位のオイラー角による回転をチェーンします。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
|  | 数 | null |
|  | 数 | null |
|  | 数 | null |

 **Result:**



---


### rotateEulerRadian{#rotateEulerRadian}

| 名前 | 説明 |
| --- | --- |
| rotateEulerRadian(r) | ラジアン単位のオイラー角による回転をチェーンします。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### translate{#translate}

| 名前 | 説明 |
| --- | --- |
| translate(tx, ty, tz) | 平行移動変換をチェーンします。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| t | 数 | null |
| t | 数 | null |
| t | 数 | null |

 **Result:**



---


### translate{#translate}

| 名前 | 説明 |
| --- | --- |
| translate(v) | 平行移動変換をチェーンします。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### reset{#reset}

| 名前 | 説明 |
| --- | --- |
| reset() | 変換を単位行列にリセットします。 |

 **Result:**



---


### rotateDegree{#rotateDegree}

| 名前 | 説明 |
| --- | --- |
| rotateDegree(rot, order) | 指定された順序で回転を追加する |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| rot | Vector3 | 回転角度（度） |
| 順序 | RotationOrder | RotationOrder |

 **Result:**



---


### rotateRadian{#rotateRadian}

| 名前 | 説明 |
| --- | --- |
| rotateRadian(rot, order) | 指定された順序で回転を追加する |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| rot | Vector3 | ラジアンでの回転 |
| 順序 | RotationOrder | RotationOrder |

 **Result:**



---



