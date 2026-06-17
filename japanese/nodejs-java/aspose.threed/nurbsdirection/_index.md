---
title: "NurbsDirection"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/nurbsdirection/
---
## NurbsDirection class

3D NurbsSurface には 2 つの方向、NurbsSurface.U と NurbsSurface.V があり、NurbsDirection は各方向のデータを定義します。方向は実際には NURBS 曲線であり、Order、KnotVectors、そして NurbsSurface で定義された重み付き制御点の集合によっても定義されます。


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getKnotVectors{#getKnotVectors}

| 名前 | 説明 |
| --- | --- |
| getKnotVectors() | ノットベクトルを取得します。これはパラメータ値のシーケンスで、制御点が NURBS 曲線にどのように影響するかを決定します。 |

 **Result:**



---


### getMultiplicity{#getMultiplicity}

| 名前 | 説明 |
| --- | --- |
| getMultiplicity() | 多重度を取得します。多重度。 |

 **Result:**



---


### getOrder{#getOrder}

| 名前 | 説明 |
| --- | --- |
| getOrder() | NURBS 曲線の次数を取得または設定します。これは、曲線上の任意の点に影響を与える近傍の制御点の数を定義します。 |

 **Result:**



---


### setOrder{#setOrder}

| 名前 | 説明 |
| --- | --- |
| setOrder(value) | NURBS 曲線の次数を取得または設定します。これは、曲線上の任意の点に影響を与える近傍の制御点の数を定義します。 |

 **Result:**



---


### getDivisions{#getDivisions}

| 名前 | 説明 |
| --- | --- |
| getDivisions() | 現在の方向における隣接する制御点間の分割数を取得または設定します。ステップです。 |

 **Result:**



---


### setDivisions{#setDivisions}

| 名前 | 説明 |
| --- | --- |
| setDivisions(value) | 現在の方向における隣接する制御点間の分割数を取得または設定します。ステップです。 |

 **Result:**



---


### getType{#getType}

| 名前 | 説明 |
| --- | --- |
| getType() | 現在の方向のタイプを取得または設定します。プロパティの値は NurbsType 整数定数です。 |

 **Result:**



---


### setType{#setType}

| 名前 | 説明 |
| --- | --- |
| setType(value) | 現在の方向のタイプを取得または設定します。プロパティの値は NurbsType 整数定数です。 |

 **Result:**



---


### getCount{#getCount}

| 名前 | 説明 |
| --- | --- |
| getCount() | 現在の方向における制御点の数を取得または設定します。カウント。 |

 **Result:**



---


### setCount{#setCount}

| 名前 | 説明 |
| --- | --- |
| setCount(value) | 現在の方向における制御点の数を取得または設定します。カウント。 |

 **Result:**



---



