---
title: "Dish"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/dish/
---
## Dish class

パラメータ化されたディッシュです。


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor() | デフォルトの半径(10)とデフォルトの高さ(5)で新しい Dish インスタンスを作成します |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名前 | 説明 |
| --- | --- |
| constructor_overload(radius, height) | 指定された半径と高さで新しい Dish インスタンスを作成します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| 半径 | 数 | Dish の半径 |
| height | 数 | Dish の高さ |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| 名前 | 説明 |
| --- | --- |
| constructor_overload2(name, radius, height, widthSegments, heightSegments) | 指定された半径と高さで新しい Dish インスタンスを作成します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| name | 文字列 | Dish の名前 |
| 半径 | 数 | Dish の半径 |
| height | 数 | Dish の高さ |
| widthSegments | 数 | Dish の幅セグメント |
| heightSegments | 数 | 皿の高さセグメント |

 **Result:**



---


### getHeight{#getHeight}

| 名前 | 説明 |
| --- | --- |
| getHeight() | 皿の高さ |

 **Result:**



---


### setHeight{#setHeight}

| 名前 | 説明 |
| --- | --- |
| setHeight(value) | 皿の高さ |

 **Result:**



---


### getRadius{#getRadius}

| 名前 | 説明 |
| --- | --- |
| getRadius() | 皿の半径 |

 **Result:**



---


### setRadius{#setRadius}

| 名前 | 説明 |
| --- | --- |
| setRadius(value) | 皿の半径 |

 **Result:**



---


### getWidthSegments{#getWidthSegments}

| 名前 | 説明 |
| --- | --- |
| getWidthSegments() | 幅セグメントを取得または設定します。 |

 **Result:**



---


### setWidthSegments{#setWidthSegments}

| 名前 | 説明 |
| --- | --- |
| setWidthSegments(value) | 幅セグメントを取得または設定します。 |

 **Result:**



---


### getHeightSegments{#getHeightSegments}

| 名前 | 説明 |
| --- | --- |
| getHeightSegments() | 高さセグメントを取得または設定します |

 **Result:**



---


### setHeightSegments{#setHeightSegments}

| 名前 | 説明 |
| --- | --- |
| setHeightSegments(value) | 高さセグメントを取得または設定します |

 **Result:**



---


### getCastShadows{#getCastShadows}

| 名前 | 説明 |
| --- | --- |
| getCastShadows() | このジオメトリが影を落とすかどうかを取得または設定します |

 **Result:**



---


### setCastShadows{#setCastShadows}

| 名前 | 説明 |
| --- | --- |
| setCastShadows(value) | このジオメトリが影を落とすかどうかを取得または設定します |

 **Result:**



---


### getReceiveShadows{#getReceiveShadows}

| 名前 | 説明 |
| --- | --- |
| getReceiveShadows() | このジオメトリが影を受け取るかどうかを取得または設定します。 |

 **Result:**



---


### setReceiveShadows{#setReceiveShadows}

| 名前 | 説明 |
| --- | --- |
| setReceiveShadows(value) | このジオメトリが影を受け取るかどうかを取得または設定します。 |

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


### toMesh{#toMesh}

| 名前 | 説明 |
| --- | --- |
| toMesh() | 現在のオブジェクトをメッシュに変換します |

 **Result:**
Mesh


---


### getBoundingBox{#getBoundingBox}

| 名前 | 説明 |
| --- | --- |
| getBoundingBox() | 現在のエンティティのオブジェクト空間座標系におけるバウンディングボックスを取得します。 |

 **Result:**
Mesh


---


### getEntityRendererKey{#getEntityRendererKey}

| 名前 | 説明 |
| --- | --- |
| getEntityRendererKey() | レンダラーに登録されたエンティティレンダラーのキーを取得します。 |

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



