---
title: "BoundingBox2D"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/boundingbox2d/
---
## BoundingBox2D class

Vector2 の軸整列バウンディングボックス


## プロパティ

| 名前 | 説明 |
| --- | --- |
| NULL | null バウンディングボックス |
| INFINITE | 無限のバウンディングボックス |

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
| constructor_overload(minimum, maximum) | 指定された minimum と maximum のコーナーで有限バウンディングボックスを初期化します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| minimum | Vector2 | minimum コーナー |
| maximum | Vector2 | maximum コーナー |

 **Result:**



---


### getExtent{#getExtent}

| 名前 | 説明 |
| --- | --- |
| getExtent() | バウンディングボックスの範囲を取得します。プロパティの値は BoundingBoxExtent 整数定数です。 |

 **Result:**



---


### getMinimum{#getMinimum}

| 名前 | 説明 |
| --- | --- |
| getMinimum() | バウンディングボックスの minimum コーナー |

 **Result:**



---


### getMaximum{#getMaximum}

| 名前 | 説明 |
| --- | --- |
| getMaximum() | バウンディングボックスの maximum コーナー |

 **Result:**



---


### merge{#merge}

| 名前 | 説明 |
| --- | --- |
| merge(pt) | 新しいボックスを現在のバウンディングボックスにマージします。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| p | Vector2 | null |

 **Result:**



---


### merge{#merge}

| 名前 | 説明 |
| --- | --- |
| merge(bb) | 新しいボックスを現在のバウンディングボックスにマージします。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| b | BoundingBox2D | null |

 **Result:**



---


### toString{#toString}

| 名前 | 説明 |
| --- | --- |
| toString() | バウンディングボックスの文字列表現を取得します。 |

 **Result:**
文字列


---



