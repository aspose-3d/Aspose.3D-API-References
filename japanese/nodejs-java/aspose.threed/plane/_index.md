---
title: "Plane"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/plane/
---
## Plane class

パラメトリック平面。


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor() | Plane の新しいインスタンスを初期化します（デフォルトサイズ 1x1）。 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名前 | 説明 |
| --- | --- |
| constructor_overload(length, width) | Plane の新しいインスタンスを初期化します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| length | 数 | 平面の長さ。 |
| 幅 | 数 | 平面の幅。 |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| 名前 | 説明 |
| --- | --- |
| constructor_overload2(name, length, width, lengthSegments, widthSegments) | Plane の新しいインスタンスを初期化します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| name | 文字列 | 名前。 |
| length | 数 | 平面の長さ。 |
| 幅 | 数 | 平面の幅。 |
| lengthSegments | 数 | 長さのセグメント。 |
| widthSegments | 数 | 幅のセグメント。 |

 **Result:**



---


### getUp{#getUp}

| 名前 | 説明 |
| --- | --- |
| getUp() | 平面の上方向ベクトルを取得または設定します。デフォルト値は (0, 1, 0) で、平面の生成に影響します。 |

 **Result:**



---


### setUp{#setUp}

| 名前 | 説明 |
| --- | --- |
| setUp(value) | 平面の上方向ベクトルを取得または設定します。デフォルト値は (0, 1, 0) で、平面の生成に影響します。 |

 **Result:**



---


### getLength{#getLength}

| 名前 | 説明 |
| --- | --- |
| getLength() | 平面の長さを取得または設定します。長さ。 |

 **Result:**



---


### setLength{#setLength}

| 名前 | 説明 |
| --- | --- |
| setLength(value) | 平面の長さを取得または設定します。長さ。 |

 **Result:**



---


### getWidth{#getWidth}

| 名前 | 説明 |
| --- | --- |
| getWidth() | 平面の幅を取得または設定します。幅。 |

 **Result:**



---


### setWidth{#setWidth}

| 名前 | 説明 |
| --- | --- |
| setWidth(value) | 平面の幅を取得または設定します。幅。 |

 **Result:**



---


### getLengthSegments{#getLengthSegments}

| 名前 | 説明 |
| --- | --- |
| getLengthSegments() | 長さのセグメントを取得または設定します。長さのセグメント。 |

 **Result:**



---


### setLengthSegments{#setLengthSegments}

| 名前 | 説明 |
| --- | --- |
| setLengthSegments(value) | 長さのセグメントを取得または設定します。長さのセグメント。 |

 **Result:**



---


### getWidthSegments{#getWidthSegments}

| 名前 | 説明 |
| --- | --- |
| getWidthSegments() | 幅のセグメントを取得または設定します。幅のセグメント。 |

 **Result:**



---


### setWidthSegments{#setWidthSegments}

| 名前 | 説明 |
| --- | --- |
| setWidthSegments(value) | 幅のセグメントを取得または設定します。幅のセグメント。 |

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



