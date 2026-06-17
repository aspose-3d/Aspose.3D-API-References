---
title: "TriMesh"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/trimesh/
---
## TriMesh class

TriMeshはGPUが直接使用できる生データを含みます。このクラスは頂点ごとのデータのみを含むメッシュの構築を支援するユーティリティです。


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor(name, declaration) | TriMesh のインスタンスを初期化する |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| name | 文字列 | この TriMesh の名前 |
| declaration | VertexDeclaration | 頂点の宣言 |

 **Result:**



---


### getVertexDeclaration{#getVertexDeclaration}

| 名前 | 説明 |
| --- | --- |
| getVertexDeclaration() | TriMesh の頂点レイアウト。 |

 **Result:**



---


### getVerticesCount{#getVerticesCount}

| 名前 | 説明 |
| --- | --- |
| getVerticesCount() | この TriMesh の頂点数 |

 **Result:**



---


### getIndicesCount{#getIndicesCount}

| 名前 | 説明 |
| --- | --- |
| getIndicesCount() | この TriMesh のインデックス数 |

 **Result:**



---


### getUnmergedVerticesCount{#getUnmergedVerticesCount}

| 名前 | 説明 |
| --- | --- |
| getUnmergedVerticesCount() | beginVertex() と endVertex() によって渡された未マージ頂点の数 |

 **Result:**



---


### getCapacity{#getCapacity}

| 名前 | 説明 |
| --- | --- |
| getCapacity() | 事前割り当てされた頂点の容量 |

 **Result:**



---


### getVerticesSizeInBytes{#getVerticesSizeInBytes}

| 名前 | 説明 |
| --- | --- |
| getVerticesSizeInBytes() | すべての頂点の合計サイズ（バイト） |

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


### fromMesh{#fromMesh}

| 名前 | 説明 |
| --- | --- |
| fromMesh(declaration, mesh) | 指定された頂点レイアウトを持つメッシュオブジェクトから TriMesh を作成します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| 宣言 | VertexDeclaration | null |
| メッシュ | Mesh | null |

 **Result:**
TriMesh


---


### copyFrom{#copyFrom}

| 名前 | 説明 |
| --- | --- |
| copyFrom(input, vd) | 新しい頂点レイアウトで入力から TriMesh をコピーします |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| 入力 | TriMesh | コピー用の入力 TriMesh |
| vd | VertexDeclaration | 出力 TriMesh の新しい頂点宣言 |

 **Result:**
TriMesh


---


### fromMesh{#fromMesh}

| 名前 | 説明 |
| --- | --- |
| fromMesh(mesh, useFloat) | 入力メッシュの構造に基づく頂点宣言で、指定されたメッシュオブジェクトから TriMesh を作成します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| メッシュ | Mesh | null |
| useFloat | boolean | 各頂点要素コンポーネントに double 型の代わりに float 型を使用します。 |

 **Result:**
TriMesh


---


### beginVertex{#beginVertex}

| 名前 | 説明 |
| --- | --- |
| beginVertex() | 頂点の追加を開始します |

 **Result:**
頂点


---


### endVertex{#endVertex}

| 名前 | 説明 |
| --- | --- |
| endVertex() | 頂点の追加を終了する |

 **Result:**
頂点


---


### verticesToArray{#verticesToArray}

| 名前 | 説明 |
| --- | --- |
| verticesToArray() | 頂点データをバイト配列に変換する |

 **Result:**
byte[]


---


### toString{#toString}

| 名前 | 説明 |
| --- | --- |
| toString() |  |

 **Result:**
文字列


---


### fromRawData{#fromRawData}

| 名前 | 説明 |
| --- | --- |
| fromRawData(vd, vertices, indices, generateVertexMapping) | 生データから TriMesh を作成します。返される TriMesh はパフォーマンスのために入力バイト配列をコピーせず、配列への外部変更はこのインスタンスに反映されます。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| vd | VertexDeclaration | 頂点宣言は、少なくとも1つのフィールドを含む必要があります。 |
| vertices | byte[] | 入力頂点データです。頂点の最小長さは、頂点宣言のサイズ以上である必要があります。 |
| indices | Number[] | 三角形インデックス |
| generateVertexMapping | boolean | 生成 |

 **Result:**
TriMesh


---


### loadVerticesFromBytes{#loadVerticesFromBytes}

| 名前 | 説明 |
| --- | --- |
| loadVerticesFromBytes(verticesInBytes) | バイトから頂点をロードします。バイト長は頂点サイズの整数倍である必要があります。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| verticesInByte | byte[] | null |

 **Result:**
TriMesh


---


### readVector4{#readVector4}

| 名前 | 説明 |
| --- | --- |
| readVector4(idx, field) | vector4 フィールドを読み取ります |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| idx | 数 | 読み取る頂点のインデックス |
| フィールド | VertexField | Vector4/FVector4 データ型を持つフィールド |

 **Result:**
Vector4


---


### readFVector4{#readFVector4}

| 名前 | 説明 |
| --- | --- |
| readFVector4(idx, field) | vector4 フィールドを読み取ります |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| idx | 数 | 読み取る頂点のインデックス |
| フィールド | VertexField | Vector4/FVector4 データ型を持つフィールド |

 **Result:**
FVector4


---


### readVector3{#readVector3}

| 名前 | 説明 |
| --- | --- |
| readVector3(idx, field) | vector3 フィールドを読み取ります |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| idx | 数 | 読み取る頂点のインデックス |
| フィールド | VertexField | Vector3/FVector3 データ型のフィールド |

 **Result:**
Vector3


---


### readFVector3{#readFVector3}

| 名前 | 説明 |
| --- | --- |
| readFVector3(idx, field) | vector3 フィールドを読み取ります |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| idx | 数 | 読み取る頂点のインデックス |
| フィールド | VertexField | Vector3/FVector3 データ型のフィールド |

 **Result:**
FVector3


---


### readVector2{#readVector2}

| 名前 | 説明 |
| --- | --- |
| readVector2(idx, field) | vector2 フィールドを読み取ります |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| idx | 数 | 読み取る頂点のインデックス |
| フィールド | VertexField | Vector2/FVector2 データ型のフィールド |

 **Result:**
Vector2


---


### readFVector2{#readFVector2}

| 名前 | 説明 |
| --- | --- |
| readFVector2(idx, field) | vector2 フィールドを読み取ります |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| idx | 数 | 読み取る頂点のインデックス |
| フィールド | VertexField | Vector2/FVector2 データ型のフィールド |

 **Result:**
FVector2


---


### readDouble{#readDouble}

| 名前 | 説明 |
| --- | --- |
| readDouble(idx, field) | double フィールドを読み取ります |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| idx | 数 | 読み取る頂点のインデックス |
| フィールド | VertexField | float/double 互換データ型のフィールド |

 **Result:**
数


---


### readFloat{#readFloat}

| 名前 | 説明 |
| --- | --- |
| readFloat(idx, field) | float フィールドを読み取ります |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| idx | 数 | 読み取る頂点のインデックス |
| フィールド | VertexField | float/double 互換データ型のフィールド |

 **Result:**
数


---


### getBoundingBox{#getBoundingBox}

| 名前 | 説明 |
| --- | --- |
| getBoundingBox() | 現在のエンティティのオブジェクト空間座標系におけるバウンディングボックスを取得します。 |

 **Result:**
数


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


### iterator{#iterator}

| 名前 | 説明 |
| --- | --- |
| iterator() | 内部使用のために予約されています。 |

 **Result:**
Property


---



