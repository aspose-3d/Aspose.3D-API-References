---
title: "シェイプ"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/shape/
---
## Shape class

シェイプは制御点の集合に対する変形を記述し、Maya のクラスターデフォーマーに似ています。例えば、作成したジオメトリにシェイプを追加できます。シェイプとジオメトリは同じトポロジ情報を持ちますが、制御点の位置が異なります。影響度の違いにより、ジオメトリは変形効果を実行します。


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor() | Shape クラスの新しいインスタンスを初期化します。 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名前 | 説明 |
| --- | --- |
| constructor_overload(name) | Shape クラスの新しいインスタンスを初期化します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| name | 文字列 | 名前 |

 **Result:**



---


### getIndices{#getIndices}

| 名前 | 説明 |
| --- | --- |
| getIndices() | インデックスを取得します。インデックス。 |

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


### getDeformers{#getDeformers}

| 名前 | 説明 |
| --- | --- |
| getDeformers() | このジオメトリに関連付けられたすべてのデフォーマーを取得します。デフォーマー。 |

 **Result:**



---


### getControlPoints{#getControlPoints}

| 名前 | 説明 |
| --- | --- |
| getControlPoints() | すべての制御点を取得します |

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


### getVertexElements{#getVertexElements}

| 名前 | 説明 |
| --- | --- |
| getVertexElements() | すべての頂点要素を取得します |

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


### fromControlPoints{#fromControlPoints}

| 名前 | 説明 |
| --- | --- |
| fromControlPoints(controlPoints) | 指定された制御点とデフォルトのインデックスでシェイプを作成します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| controlPoint | Vector3[] | null |

 **Result:**
シェイプ


---


### getElement{#getElement}

| 名前 | 説明 |
| --- | --- |
| getElement(type) | 指定されたタイプの頂点要素を取得します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| type | VertexElementType | VertexElementType |

 **Result:**
VertexElement


---


### getVertexElementOfUV{#getVertexElementOfUV}

| 名前 | 説明 |
| --- | --- |
| getVertexElementOfUV(textureMapping) | 指定されたテクスチャマッピングタイプの VertexElementUV インスタンスを取得します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| textureMapping | TextureMapping | TextureMapping |

 **Result:**
VertexElementUV


---


### createElement{#createElement}

| 名前 | 説明 |
| --- | --- |
| createElement(type) | 指定されたタイプの頂点要素を作成し、ジオメトリに追加します。type が VertexElementType.UV の場合、テクスチャマッピングタイプが TextureMapping.DIFFUSE の VertexElementUV が作成されます。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| type | VertexElementType | VertexElementType |

 **Result:**
VertexElement


---


### addElement{#addElement}

| 名前 | 説明 |
| --- | --- |
| addElement(element) | 既存の頂点要素を現在のジオメトリに追加します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| element | VertexElement | 追加する頂点要素 |

 **Result:**
VertexElement


---


### createElement{#createElement}

| 名前 | 説明 |
| --- | --- |
| createElement(type, mappingMode, referenceMode) | 指定されたタイプの頂点要素を作成し、ジオメトリに追加します。type が VertexElementType.UV の場合、テクスチャマッピングタイプが TextureMapping.DIFFUSE の VertexElementUV が作成されます。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| type | VertexElementType | VertexElementType |
| mappingMode | MappingMode | MappingMode |
| referenceMode | ReferenceMode | ReferenceMode |

 **Result:**
VertexElement


---


### createElementUV{#createElementUV}

| 名前 | 説明 |
| --- | --- |
| createElementUV(uvMapping) | 指定されたテクスチャマッピングタイプで VertexElementUV を作成します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| uvMapping | TextureMapping | TextureMapping |

 **Result:**
VertexElementUV


---


### createElementUV{#createElementUV}

| 名前 | 説明 |
| --- | --- |
| createElementUV(uvMapping, mappingMode, referenceMode) | 指定されたテクスチャマッピングタイプで VertexElementUV を作成します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| uvMapping | TextureMapping | TextureMapping |
| mappingMode | MappingMode | MappingMode |
| referenceMode | ReferenceMode | ReferenceMode |

 **Result:**
VertexElementUV


---


### getBoundingBox{#getBoundingBox}

| 名前 | 説明 |
| --- | --- |
| getBoundingBox() | 現在のエンティティのオブジェクト空間座標系におけるバウンディングボックスを取得します。 |

 **Result:**
VertexElementUV


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



