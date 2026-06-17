---
title: "CShape"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/cshape/
---
## CShape class

IFC 互換の C 形状プロファイルはパラメータで定義されます。 プロファイルの中心位置はバウンディングボックスの中心にあります。


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor() | CShape のコンストラクタ |

 **Result:**



---


### getDepth{#getDepth}

| 名前 | 説明 |
| --- | --- |
| getDepth() | プロファイルの深さを取得または設定します。 |

 **Result:**



---


### setDepth{#setDepth}

| 名前 | 説明 |
| --- | --- |
| setDepth(value) | プロファイルの深さを取得または設定します。 |

 **Result:**



---


### getWidth{#getWidth}

| 名前 | 説明 |
| --- | --- |
| getWidth() | プロファイルの幅を取得または設定します。 |

 **Result:**



---


### setWidth{#setWidth}

| 名前 | 説明 |
| --- | --- |
| setWidth(value) | プロファイルの幅を取得または設定します。 |

 **Result:**



---


### getGirth{#getGirth}

| 名前 | 説明 |
| --- | --- |
| getGirth() | 周囲の長さを取得または設定します。 |

 **Result:**



---


### setGirth{#setGirth}

| 名前 | 説明 |
| --- | --- |
| setGirth(value) | 周囲の長さを取得または設定します。 |

 **Result:**



---


### getWallThickness{#getWallThickness}

| 名前 | 説明 |
| --- | --- |
| getWallThickness() | 壁の厚さを取得または設定します。 |

 **Result:**



---


### setWallThickness{#setWallThickness}

| 名前 | 説明 |
| --- | --- |
| setWallThickness(value) | 壁の厚さを取得または設定します。 |

 **Result:**



---


### getInternalFilletRadius{#getInternalFilletRadius}

| 名前 | 説明 |
| --- | --- |
| getInternalFilletRadius() | 内部フィレット半径を取得または設定します。 |

 **Result:**



---


### setInternalFilletRadius{#setInternalFilletRadius}

| 名前 | 説明 |
| --- | --- |
| setInternalFilletRadius(value) | 内部フィレット半径を取得または設定します。 |

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


### getExtent{#getExtent}

| 名前 | 説明 |
| --- | --- |
| getExtent() | x と y の次元での範囲を取得します |

 **Result:**
Vector2


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



