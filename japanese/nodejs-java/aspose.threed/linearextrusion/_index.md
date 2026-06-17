---
title: "LinearExtrusion"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/linearextrusion/
---
## LinearExtrusion class

線形押し出しは 2D 形状を入力として受け取り、形状を第3次元に拡張します。


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor() | LinearExtrusion インスタンスのコンストラクタ。 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名前 | 説明 |
| --- | --- |
| constructor_overload(shape, height) | LinearExtrusion インスタンスのコンストラクタ。 |

 **Result:**



---


### getShape{#getShape}

| 名前 | 説明 |
| --- | --- |
| getShape() | 押し出される基本形状。 |

 **Result:**



---


### setShape{#setShape}

| 名前 | 説明 |
| --- | --- |
| setShape(value) | 押し出される基本形状。 |

 **Result:**



---


### getDirection{#getDirection}

| 名前 | 説明 |
| --- | --- |
| getDirection() | 押し出し方向、デフォルト値は (0, 0, 1) です。 |

 **Result:**



---


### setDirection{#setDirection}

| 名前 | 説明 |
| --- | --- |
| setDirection(value) | 押し出し方向、デフォルト値は (0, 0, 1) です。 |

 **Result:**



---


### getHeight{#getHeight}

| 名前 | 説明 |
| --- | --- |
| getHeight() | 押し出されたジオメトリの高さ、デフォルト値は 1.0 です。 |

 **Result:**



---


### setHeight{#setHeight}

| 名前 | 説明 |
| --- | --- |
| setHeight(value) | 押し出されたジオメトリの高さ、デフォルト値は 1.0 です。 |

 **Result:**



---


### getSlices{#getSlices}

| 名前 | 説明 |
| --- | --- |
| getSlices() | ねじれた押し出しジオメトリのスライス数、デフォルト値は 1 です。 |

 **Result:**



---


### setSlices{#setSlices}

| 名前 | 説明 |
| --- | --- |
| setSlices(value) | ねじれた押し出しジオメトリのスライス数、デフォルト値は 1 です。 |

 **Result:**



---


### getCenter{#getCenter}

| 名前 | 説明 |
| --- | --- |
| getCenter() | この値が false の場合、線形押し出しの Z 範囲は 0 から高さまでになります。false でない場合、範囲は -height/2 から height/2 になります。 |

 **Result:**



---


### setCenter{#setCenter}

| 名前 | 説明 |
| --- | --- |
| setCenter(value) | この値が false の場合、線形押し出しの Z 範囲は 0 から高さまでになります。false でない場合、範囲は -height/2 から height/2 になります。 |

 **Result:**



---


### getTwistOffset{#getTwistOffset}

| 名前 | 説明 |
| --- | --- |
| getTwistOffset() | ねじりに使用されるオフセット、デフォルト値は (0, 0, 0) です。 |

 **Result:**



---


### setTwistOffset{#setTwistOffset}

| 名前 | 説明 |
| --- | --- |
| setTwistOffset(value) | ねじりに使用されるオフセット、デフォルト値は (0, 0, 0) です。 |

 **Result:**



---


### getTwist{#getTwist}

| 名前 | 説明 |
| --- | --- |
| getTwist() | 形状が押し出される角度（度）です。 |

 **Result:**



---


### setTwist{#setTwist}

| 名前 | 説明 |
| --- | --- |
| setTwist(value) | 形状が押し出される角度（度）です。 |

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
| toMesh() | 押し出しをメッシュに変換します。 |

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



