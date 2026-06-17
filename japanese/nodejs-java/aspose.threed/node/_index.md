---
title: "ノード"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/node/
---
## Node class

シーングラフ内の要素を表します。シーングラフは Node オブジェクトのツリーです。ツリー管理サービスはこのクラスに自己完結しています。Aspose.3D SDK は構築されたシーングラフの有効性を検証しないことに注意してください。呼び出し側の責任で、ノード階層に循環グラフが生成されないようにする必要があります。ツリー管理に加えて、このクラスはシーン内のオブジェクトの位置を記述するために必要なすべてのプロパティを定義します。この情報には基本的な Translation、Rotation、Scaling プロパティと、ピボット、リミット、IK ジョイント属性（剛性や減衰など）の高度なオプションが含まれます。最初に作成されたとき、Node オブジェクトは "empty"（つまり、位置情報のみを保持し、グラフィカルな表現を持たないオブジェクト）です。この状態では、ノードツリー構造の親を表すために使用できますが、それ以上の用途はほとんどありません。この種のオブジェクトの通常の使用方法は、ノードを専門化するエンティティ（"Entity"参照）を追加することです。エンティティはそれ自体がオブジェクトであり、Node に接続されます。これは、同じエンティティを複数のノードで共有できることも意味します。Camera、Light、Mesh などはすべてエンティティであり、すべて基底クラス Entity から派生しています。


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor() | Node クラスの新しいインスタンスを初期化します。 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名前 | 説明 |
| --- | --- |
| constructor_overload(name, entity) | Node クラスの新しいインスタンスを初期化します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| name | 文字列 | 名前。 |
| エンティティ | エンティティ | デフォルトエンティティ。 |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| 名前 | 説明 |
| --- | --- |
| constructor_overload2(name) | Node クラスの新しいインスタンスを初期化します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| name | 文字列 | 名前。 |

 **Result:**



---


### getAssetInfo{#getAssetInfo}

| 名前 | 説明 |
| --- | --- |
| getAssetInfo() | ノードごとのアセット情報 |

 **Result:**



---


### setAssetInfo{#setAssetInfo}

| 名前 | 説明 |
| --- | --- |
| setAssetInfo(value) | ノードごとのアセット情報 |

 **Result:**



---


### getVisible{#getVisible}

| 名前 | 説明 |
| --- | --- |
| getVisible() | ノードの表示を取得または設定します |

 **Result:**



---


### setVisible{#setVisible}

| 名前 | 説明 |
| --- | --- |
| setVisible(value) | ノードの表示を取得または設定します |

 **Result:**



---


### getChildNodes{#getChildNodes}

| 名前 | 説明 |
| --- | --- |
| getChildNodes() | 子ノードを取得します。ノード。 |

 **Result:**



---


### getEntity{#getEntity}

| 名前 | 説明 |
| --- | --- |
| getEntity() | このノードに添付された最初のエンティティを取得または設定します。設定した場合、他のエンティティはクリアされます。ノードエンティティ。 |

 **Result:**



---


### setEntity{#setEntity}

| 名前 | 説明 |
| --- | --- |
| setEntity(value) | このノードに添付された最初のエンティティを取得または設定します。設定した場合、他のエンティティはクリアされます。ノードエンティティ。 |

 **Result:**



---


### getExcluded{#getExcluded}

| 名前 | 説明 |
| --- | --- |
| getExcluded() | エクスポート時にこのノードとすべての子ノード/エンティティを除外するかどうかを取得または設定します。 |

 **Result:**



---


### setExcluded{#setExcluded}

| 名前 | 説明 |
| --- | --- |
| setExcluded(value) | エクスポート時にこのノードとすべての子ノード/エンティティを除外するかどうかを取得または設定します。 |

 **Result:**



---


### getEntities{#getEntities}

| 名前 | 説明 |
| --- | --- |
| getEntities() | すべてのノードエンティティを取得します。ノードエンティティ。 |

 **Result:**



---


### getMetaDatas{#getMetaDatas}

| 名前 | 説明 |
| --- | --- |
| getMetaDatas() | このノードで定義されたメタデータを取得します。メタデータ。 |

 **Result:**



---


### getMaterials{#getMaterials}

| 名前 | 説明 |
| --- | --- |
| getMaterials() | このノードに関連付けられたマテリアルを取得します。マテリアル。 |

 **Result:**



---


### getMaterial{#getMaterial}

| 名前 | 説明 |
| --- | --- |
| getMaterial() | このノードに関連付けられた最初のマテリアルを取得または設定します。設定した場合、他のマテリアルはクリアされます。マテリアル。 |

 **Result:**



---


### setMaterial{#setMaterial}

| 名前 | 説明 |
| --- | --- |
| setMaterial(value) | このノードに関連付けられた最初のマテリアルを取得または設定します。設定した場合、他のマテリアルはクリアされます。マテリアル。 |

 **Result:**



---


### getParentNode{#getParentNode}

| 名前 | 説明 |
| --- | --- |
| getParentNode() | 親ノードを取得または設定します。親ノード。 |

 **Result:**



---


### setParentNode{#setParentNode}

| 名前 | 説明 |
| --- | --- |
| setParentNode(value) | 親ノードを取得または設定します。親ノード。 |

 **Result:**



---


### getTransform{#getTransform}

| 名前 | 説明 |
| --- | --- |
| getTransform() | ローカル変換を取得します。変換。 |

 **Result:**



---


### getGlobalTransform{#getGlobalTransform}

| 名前 | 説明 |
| --- | --- |
| getGlobalTransform() | グローバル変換を取得します。グローバル変換。 |

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


### createChildNode{#createChildNode}

| 名前 | 説明 |
| --- | --- |
| createChildNode() | 子ノードを作成します |

 **Result:**
ノード


---


### merge{#merge}

| 名前 | 説明 |
| --- | --- |
| merge(node) | ノード以下のすべてを切り離し、現在のノードに添付します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| nod | ノード | null |

 **Result:**
ノード


---


### createChildNode{#createChildNode}

| 名前 | 説明 |
| --- | --- |
| createChildNode(nodeName) | 指定されたノード名で新しい子ノードを作成します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| nodeName | 文字列 | 新しい子ノードの名前 |

 **Result:**
ノード


---


### createChildNode{#createChildNode}

| 名前 | 説明 |
| --- | --- |
| createChildNode(entity) | 指定されたエンティティが添付された新しい子ノードを作成します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| エンティティ | エンティティ | ノードに添付されたデフォルトエンティティ |

 **Result:**
ノード


---


### createChildNode{#createChildNode}

| 名前 | 説明 |
| --- | --- |
| createChildNode(nodeName, entity) | 指定されたノード名で新しい子ノードを作成します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| nodeName | 文字列 | 新しい子ノードの名前 |
| エンティティ | エンティティ | ノードに添付されたデフォルトエンティティ |

 **Result:**
ノード


---


### createChildNode{#createChildNode}

| 名前 | 説明 |
| --- | --- |
| createChildNode(nodeName, entity, material) | 指定されたノード名で新しい子ノードを作成し、指定されたエンティティとマテリアルを添付します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| nodeName | 文字列 | 新しい子ノードの名前 |
| エンティティ | エンティティ | ノードに添付されたデフォルトエンティティ |
| material | マテリアル | ノードに添付されたマテリアル |

 **Result:**
ノード


---


### evaluateGlobalTransform{#evaluateGlobalTransform}

| 名前 | 説明 |
| --- | --- |
| evaluateGlobalTransform(withGeometricTransform) | グローバル変換を評価します。幾何変換を含めるかどうか。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| withGeometricTransform | boolean | 幾何変換が必要かどうか。 |

 **Result:**
Matrix4


---


### getChild{#getChild}

| 名前 | 説明 |
| --- | --- |
| getChild(index) | 指定されたインデックスの子ノードを取得します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| index | 数 | インデックス。 |

 **Result:**
ノード


---


### getChild{#getChild}

| 名前 | 説明 |
| --- | --- |
| getChild(nodeName) | 指定された名前の子ノードを取得します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| nodeName | 文字列 | 検索する子ノードの名前。 |

 **Result:**
ノード


---


### accept{#accept}

| 名前 | 説明 |
| --- | --- |
| accept(visitor) | 現在のノードを含むすべての子孫ノードを走査し、ノードを visitor に渡して呼び出します。visitor は false を返すことで走査を中止できます。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| visitor | NodeVisitor | ノードを訪問するための Visitor コールバック |

 **Result:**
boolean


---


### toString{#toString}

| 名前 | 説明 |
| --- | --- |
| toString() | このノードの文字列表現を取得します。 |

 **Result:**
文字列


---


### getBoundingBox{#getBoundingBox}

| 名前 | 説明 |
| --- | --- |
| getBoundingBox() | ノードのバウンディングボックスを計算します。 |

 **Result:**
BoundingBox


---


### addEntity{#addEntity}

| 名前 | 説明 |
| --- | --- |
| addEntity(entity) | エンティティをノードに追加します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| エンティティ | エンティティ | ノードに添付するエンティティ |

 **Result:**
BoundingBox


---


### addChildNode{#addChildNode}

| 名前 | 説明 |
| --- | --- |
| addChildNode(node) | このノードに子ノードを追加します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| ノード | ノード | 添付する子ノード |

 **Result:**
BoundingBox


---


### selectSingleObject{#selectSingleObject}

| 名前 | 説明 |
| --- | --- |
| selectSingleObject(path) | XPath ライクなクエリ構文を使用して、現在のノード以下の単一オブジェクトを選択します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| pat | 文字列 | null |

 **Result:**
オブジェクト


---


### selectObjects{#selectObjects}

| 名前 | 説明 |
| --- | --- |
| selectObjects(path) | XPath ライクなクエリ構文を使用して、現在のノード以下の複数オブジェクトを選択します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| pat | 文字列 | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=b77a5c561934e089]]


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



