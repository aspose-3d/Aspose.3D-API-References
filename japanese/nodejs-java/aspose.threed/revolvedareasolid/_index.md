---
title: "RevolvedAreaSolid"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/revolvedareasolid/
---
## RevolvedAreaSolid class

このクラスは、プロファイルで提供された断面を軸の周りに回転させることで、ソリッドモデルを表現します。


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getAngleStart{#getAngleStart}

| 名前 | 説明 |
| --- | --- |
| getAngleStart() | 回転手順の開始角度を取得または設定します（ラジアンで測定）、デフォルト値は 0 です。 |

 **Result:**



---


### setAngleStart{#setAngleStart}

| 名前 | 説明 |
| --- | --- |
| setAngleStart(value) | 回転手順の開始角度を取得または設定します（ラジアンで測定）、デフォルト値は 0 です。 |

 **Result:**



---


### getAngleEnd{#getAngleEnd}

| 名前 | 説明 |
| --- | --- |
| getAngleEnd() | 回転手順の終了角度を取得または設定します（ラジアンで測定）、デフォルト値は π です。 |

 **Result:**



---


### setAngleEnd{#setAngleEnd}

| 名前 | 説明 |
| --- | --- |
| setAngleEnd(value) | 回転手順の終了角度を取得または設定します（ラジアンで測定）、デフォルト値は π です。 |

 **Result:**



---


### getAxis{#getAxis}

| 名前 | 説明 |
| --- | --- |
| getAxis() | 軸方向を取得または設定します、デフォルト値は (0, 1, 0) です。 |

 **Result:**



---


### setAxis{#setAxis}

| 名前 | 説明 |
| --- | --- |
| setAxis(value) | 軸方向を取得または設定します、デフォルト値は (0, 1, 0) です。 |

 **Result:**



---


### getOrigin{#getOrigin}

| 名前 | 説明 |
| --- | --- |
| getOrigin() | 回転の原点を取得または設定します、デフォルト値は (0, 0, 0) です。 |

 **Result:**



---


### setOrigin{#setOrigin}

| 名前 | 説明 |
| --- | --- |
| setOrigin(value) | 回転の原点を取得または設定します、デフォルト値は (0, 0, 0) です。 |

 **Result:**



---


### getShape{#getShape}

| 名前 | 説明 |
| --- | --- |
| getShape() | 回転に使用されるベースプロファイルを取得または設定します。 |

 **Result:**



---


### setShape{#setShape}

| 名前 | 説明 |
| --- | --- |
| setShape(value) | 回転に使用されるベースプロファイルを取得または設定します。 |

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
| toMesh() | RevolvedAreaSolid をメッシュに変換します。 |

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



