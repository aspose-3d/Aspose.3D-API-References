---
title: "BoundingBox"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/boundingbox/
---
## BoundingBox class

軸整列バウンディングボックス


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
| minimum | Vector3 | minimum コーナー |
| maximum | Vector3 | maximum コーナー |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| 名前 | 説明 |
| --- | --- |
| constructor_overload2(minX, minY, minZ, maxX, maxY, maxZ) | 指定された minimum と maximum のコーナーで有限バウンディングボックスを初期化します |

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


### getSize{#getSize}

| 名前 | 説明 |
| --- | --- |
| getSize() | バウンディングボックスのサイズ |

 **Result:**



---


### getCenter{#getCenter}

| 名前 | 説明 |
| --- | --- |
| getCenter() | バウンディングボックスの中心。 |

 **Result:**



---


### fromGeometry{#fromGeometry}

| 名前 | 説明 |
| --- | --- |
| fromGeometry(geometry) | 与えられたジオメトリからバウンディングボックスを構築します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| geometr | ジオメトリ | null |

 **Result:**
BoundingBox


---


### toString{#toString}

| 名前 | 説明 |
| --- | --- |
| toString() | バウンディングボックスの文字列表現を取得します。 |

 **Result:**
文字列


---


### hashCode{#hashCode}

| 名前 | 説明 |
| --- | --- |
| hashCode() | このインスタンスのハッシュコードを返します |

 **Result:**
数


---


### equals{#equals}

| 名前 | 説明 |
| --- | --- |
| equals(obj) | 2つのオブジェクトが等しいかどうかを判定します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| ob | オブジェクト | null |

 **Result:**
boolean


---



