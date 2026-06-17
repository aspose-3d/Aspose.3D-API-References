---
title: "EndPoint"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/endpoint/
---
## EndPoint class

曲線をトリムする終点は、パラメータ値またはデカルト座標点のいずれかです。


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
| constructor_overload(point) | Cartesian 点から EndPoint を構築します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| poin | Vector3 | null |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| 名前 | 説明 |
| --- | --- |
| constructor_overload2(v) | 実数パラメータから EndPoint を構築します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
|  | 数 | null |

 **Result:**



---


### isCartesianPoint{#isCartesianPoint}

| 名前 | 説明 |
| --- | --- |
| isCartesianPoint() | 終点は Cartesian 点ですか？ |

 **Result:**



---


### getAsPoint{#getAsPoint}

| 名前 | 説明 |
| --- | --- |
| getAsPoint() | エンドポイントをデカルト座標として取得し、例外がスローされます。 |

 **Result:**



---


### getAsValue{#getAsValue}

| 名前 | 説明 |
| --- | --- |
| getAsValue() | エンドポイントを実数パラメータとして取得し、例外がスローされます。 |

 **Result:**



---


### fromDegree{#fromDegree}

| 名前 | 説明 |
| --- | --- |
| fromDegree(degree) | 度で測定されたエンドポイントを作成します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| degre | 数 | null |

 **Result:**
EndPoint


---


### fromRadian{#fromRadian}

| 名前 | 説明 |
| --- | --- |
| fromRadian(degree) | ラジアンで測定されたエンドポイントを作成します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| degre | 数 | null |

 **Result:**
EndPoint


---


### toString{#toString}

| 名前 | 説明 |
| --- | --- |
| toString() | 現在のエンドポイントの文字列表現を返します。 |

 **Result:**
文字列


---



