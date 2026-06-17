---
title: "Line"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/line/
---
## Line class

ポリラインは Geometry.ControlPoints で定義された点の集合で構成され、Segments によって接続されたパスです。つまり、接続された線分の集合とも言えます。ラインは通常線形オブジェクトであり、曲線を表すことはできません。曲線を表現するには NurbsCurve を使用します。


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor() | Line クラスの新しいインスタンスを初期化します。 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名前 | 説明 |
| --- | --- |
| constructor_overload(name) | Line クラスの新しいインスタンスを初期化します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| name | 文字列 | 名前。 |

 **Result:**



---


### getControlPoints{#getControlPoints}

| 名前 | 説明 |
| --- | --- |
| getControlPoints() | すべての制御点を取得します |

 **Result:**



---


### getVisible{#getVisible}

| 名前 | 説明 |
| --- | --- |
| getVisible() | ジオメトリが表示されているかどうかを取得または設定します |

 **Result:**



---


### setVisible{#setVisible}

| 名前 | 説明 |
| --- | --- |
| setVisible(value) | ジオメトリが表示されているかどうかを取得または設定します |

 **Result:**



---


### getSegments{#getSegments}

| 名前 | 説明 |
| --- | --- |
| getSegments() | ラインのセグメントを取得します |

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


### fromPoints{#fromPoints}

| 名前 | 説明 |
| --- | --- |
| fromPoints(points) | ポイントの集合から Line インスタンスを構築します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| ポイント | Vector3[] | null |

 **Result:**
Line


---


### makeDefaultIndices{#makeDefaultIndices}

| 名前 | 説明 |
| --- | --- |
| makeDefaultIndices() | 0,1,2,3....Geometry.ControlPoints.Length-1 のシーケンスを Segments に生成し、ControlPoints を単一のラインとして使用できるようにします |

 **Result:**
Line


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



