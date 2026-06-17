---
title: "Pyramid"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/pyramid/
---
## Pyramid class

パラメトリックピラミッド。


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor() | デフォルトの底面領域(10, 10)とデフォルトの高さ(5)で新しい Pyramid インスタンスを構築します |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名前 | 説明 |
| --- | --- |
| constructor_overload(xbottom, ybottom, height) | 指定された底面領域で新しい Pyramid インスタンスを構築します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| xbottom | 数 | 底面の x 方向の長さ |
| ybottom | 数 | 底面の y 方向の長さ |
| height | 数 | Pyramid の高さ |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| 名前 | 説明 |
| --- | --- |
| constructor_overload2(xbottom, ybottom, xtop, ytop, height) | 指定された底面領域、上面領域、および高さで新しい Pyramid インスタンスを構築します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| xbottom | 数 | 底面領域の x 方向の長さ |
| ybottom | 数 | 底面領域の y 方向の長さ |
| xtop | 数 | 上面領域の x 方向の長さ |
| ytop | 数 | 上面領域の y 方向の長さ |
| height | 数 | Pyramid の高さ |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| 名前 | 説明 |
| --- | --- |
| constructor_overload3(name, xbottom, ybottom, xtop, ytop, height) | 指定された底面領域、上面領域、および高さで新しい Pyramid インスタンスを構築します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| name | 文字列 | ピラミッドの名前 |
| xbottom | 数 | 底面領域の x 方向の長さ |
| ybottom | 数 | 底面領域の y 方向の長さ |
| xtop | 数 | 上面領域の x 方向の長さ |
| ytop | 数 | 上面領域の y 方向の長さ |
| height | 数 | Pyramid の高さ |

 **Result:**



---


### getBottomArea{#getBottomArea}

| 名前 | 説明 |
| --- | --- |
| getBottomArea() | 底部キャップの面積 |

 **Result:**



---


### setBottomArea{#setBottomArea}

| 名前 | 説明 |
| --- | --- |
| setBottomArea(value) | 底部キャップの面積 |

 **Result:**



---


### getTopArea{#getTopArea}

| 名前 | 説明 |
| --- | --- |
| getTopArea() | 上部キャップの面積 |

 **Result:**



---


### setTopArea{#setTopArea}

| 名前 | 説明 |
| --- | --- |
| setTopArea(value) | 上部キャップの面積 |

 **Result:**



---


### getBottomOffset{#getBottomOffset}

| 名前 | 説明 |
| --- | --- |
| getBottomOffset() | 底部頂点のオフセット |

 **Result:**



---


### setBottomOffset{#setBottomOffset}

| 名前 | 説明 |
| --- | --- |
| setBottomOffset(value) | 底部頂点のオフセット |

 **Result:**



---


### getHeight{#getHeight}

| 名前 | 説明 |
| --- | --- |
| getHeight() | ピラミッドの高さ |

 **Result:**



---


### setHeight{#setHeight}

| 名前 | 説明 |
| --- | --- |
| setHeight(value) | ピラミッドの高さ |

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



