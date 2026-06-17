---
title: "NurbsCurve"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/nurbscurve/
---
## NurbsCurve class

NURBS 曲線は NURBS（Non-uniform rational basis spline）で表現される曲線です。NURBS 曲線はその Order、重み付き Geometry.ControlPoints の集合、そして KnotVectors によって定義されます。制御点の w 成分は制御点の重みとして使用され、CurveDimension.TWO_DIMENSIONAL であろうと CurveDimension.THREE_DIMENSIONAL であろうと同様です。


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor() | NurbsCurve クラスの新しいインスタンスを初期化します。 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名前 | 説明 |
| --- | --- |
| constructor_overload(name) | NurbsCurve クラスの新しいインスタンスを初期化します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| name | 文字列 | 名前 |

 **Result:**



---


### getControlPoints{#getControlPoints}

| 名前 | 説明 |
| --- | --- |
| getControlPoints() | すべての制御点を取得します |

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
| getOrder() | NURBS 曲線の次数を取得または設定します。次数は、曲線上の任意の点に影響を与える近傍の制御点の数を定義します。次数。 |

 **Result:**



---


### setOrder{#setOrder}

| 名前 | 説明 |
| --- | --- |
| setOrder(value) | NURBS 曲線の次数を取得または設定します。次数は、曲線上の任意の点に影響を与える近傍の制御点の数を定義します。次数。 |

 **Result:**



---


### getDimension{#getDimension}

| 名前 | 説明 |
| --- | --- |
| getDimension() | 曲線の次元を取得または設定します。プロパティの値は CurveDimension 整数定数です。CurveDimension.TWO_DIMENSIONAL 曲線の場合、制御点の z 成分は使用されません。 |

 **Result:**



---


### setDimension{#setDimension}

| 名前 | 説明 |
| --- | --- |
| setDimension(value) | 曲線の次元を取得または設定します。プロパティの値は CurveDimension 整数定数です。CurveDimension.TWO_DIMENSIONAL 曲線の場合、制御点の z 成分は使用されません。 |

 **Result:**



---


### getCurveType{#getCurveType}

| 名前 | 説明 |
| --- | --- |
| getCurveType() | 曲線のタイプを取得または設定します。プロパティの値は NurbsType 整数定数です。曲線のタイプ。 |

 **Result:**



---


### setCurveType{#setCurveType}

| 名前 | 説明 |
| --- | --- |
| setCurveType(value) | 曲線のタイプを取得または設定します。プロパティの値は NurbsType 整数定数です。曲線のタイプ。 |

 **Result:**



---


### getKnotVectors{#getKnotVectors}

| 名前 | 説明 |
| --- | --- |
| getKnotVectors() | ノットベクトルを取得します。これはパラメータ値のシーケンスで、制御点が NURBS 曲線にどのように影響するかを決定します。 |

 **Result:**



---


### getRational{#getRational}

| 名前 | 説明 |
| --- | --- |
| getRational() | 有理かどうかを取得または設定します。この値は、この NurbsCurve が有理スプラインか非有理スプラインかを示します。非有理 B スプラインは有理 B スプラインの特別なケースです。有理スプラインの場合は true、そうでない場合は非有理スプラインとして false です。 |

 **Result:**



---


### setRational{#setRational}

| 名前 | 説明 |
| --- | --- |
| setRational(value) | 有理かどうかを取得または設定します。この値は、この NurbsCurve が有理スプラインか非有理スプラインかを示します。非有理 B スプラインは有理 B スプラインの特別なケースです。有理スプラインの場合は true、そうでない場合は非有理スプラインとして false です。 |

 **Result:**



---


### getColor{#getColor}

| 名前 | 説明 |
| --- | --- |
| getColor() | 線の色を取得または設定します。デフォルト値は白 (1, 1, 1) です。 |

 **Result:**



---


### setColor{#setColor}

| 名前 | 説明 |
| --- | --- |
| setColor(value) | 線の色を取得または設定します。デフォルト値は白 (1, 1, 1) です。 |

 **Result:**



---


### getParentNodes{#getParentNodes}

| 名前 | 説明 |
| --- | --- |
| getParentNodes() | すべての親ノードを取得します。エンティティはジオメトリインスタンシングのために複数の親ノードにアタッチできます。 |

 **Result:**



---


### getExcluded{#getExcluded}

| 名前 | 説明 |
| --- | --- |
| getExcluded() | エクスポート時にこのエンティティを除外するかどうかを取得または設定します。 |

 **Result:**



---


### setExcluded{#setExcluded}

| 名前 | 説明 |
| --- | --- |
| setExcluded(value) | エクスポート時にこのエンティティを除外するかどうかを取得または設定します。 |

 **Result:**



---


### getParentNode{#getParentNode}

| 名前 | 説明 |
| --- | --- |
| getParentNode() | 最初の親ノードを取得または設定します。最初の親ノードを設定すると、このエンティティは他の親ノードから切り離されます。親ノード。 |

 **Result:**



---


### setParentNode{#setParentNode}

| 名前 | 説明 |
| --- | --- |
| setParentNode(value) | 最初の親ノードを取得または設定します。最初の親ノードを設定すると、このエンティティは他の親ノードから切り離されます。親ノード。 |

 **Result:**



---


### getScene{#getScene}

| 名前 | 説明 |
| --- | --- |
| getScene() | このオブジェクトが属するシーンを取得します。 |

 **Result:**



---


### getName{#getName}

| 名前 | 説明 |
| --- | --- |
| getName() | 名前を取得または設定します。名前。 |

 **Result:**



---


### setName{#setName}

| 名前 | 説明 |
| --- | --- |
| setName(value) | 名前を取得または設定します。名前。 |

 **Result:**



---


### getProperties{#getProperties}

| 名前 | 説明 |
| --- | --- |
| getProperties() | すべてのプロパティのコレクションを取得します。 |

 **Result:**



---


### evaluate{#evaluate}

| 名前 | 説明 |
| --- | --- |
| evaluate(steps) | NURBS 曲線を評価します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| steps | 数 | 隣接する2つのノット間の評価頻度です。デフォルト値は 20 です。 |

 **Result:**
Vector4[]


---


### evaluateAt{#evaluateAt}

| 名前 | 説明 |
| --- | --- |
| evaluateAt(u) | 指定された位置で曲線の点を評価します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| u | 数 | 曲線上の位置で、0 から 1 の間です |

 **Result:**
Vector4


---


### getEntityRendererKey{#getEntityRendererKey}

| 名前 | 説明 |
| --- | --- |
| getEntityRendererKey() | レンダラーに登録されたエンティティレンダラーのキーを取得します。 |

 **Result:**
EntityRendererKey


---


### getBoundingBox{#getBoundingBox}

| 名前 | 説明 |
| --- | --- |
| getBoundingBox() | 現在のエンティティのオブジェクト空間座標系におけるバウンディングボックスを取得します。 |

 **Result:**
EntityRendererKey


---


### removeProperty{#removeProperty}

| 名前 | 説明 |
| --- | --- |
| removeProperty(property) | 動的プロパティを削除します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| property | Property | 削除するプロパティはどれですか |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| 名前 | 説明 |
| --- | --- |
| removeProperty(property) | 名前で識別された指定されたプロパティを削除します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| propert | 文字列 | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| 名前 | 説明 |
| --- | --- |
| getProperty(property) | 指定されたプロパティの値を取得します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| property | 文字列 | プロパティ名 |

 **Result:**
オブジェクト


---


### setProperty{#setProperty}

| 名前 | 説明 |
| --- | --- |
| setProperty(property, value) | 指定されたプロパティの値を設定します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| property | 文字列 | プロパティ名 |
| 値 | オブジェクト | プロパティの値 |

 **Result:**
オブジェクト


---


### findProperty{#findProperty}

| 名前 | 説明 |
| --- | --- |
| findProperty(propertyName) | プロパティを検索します。動的プロパティ（CreateDynamicProperty/SetProperty によって作成）またはネイティブプロパティ（名前で識別）になる可能性があります |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| propertyName | 文字列 | プロパティ名。 |

 **Result:**
Property


---



