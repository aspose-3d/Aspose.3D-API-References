---
title: Node
second_title: Aspose.3D for Java API リファレンス
description: シーングラフ内の要素を表します。
type: docs
weight: 110
url: /ja/java/com.aspose.threed/node/
---

**Inheritance:**
java.lang.Object、[com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)、[com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject)
```
public class Node extends SceneObject
```

シーン グラフ内の要素を表します。シーン グラフは Node オブジェクトのツリーです。ツリー管理サービスはこのクラスに自己完結しています。Aspose.3D SDK は構築されたシーン グラフの有効性をテストしないことに注意してください。呼び出し元の責任で、ノード階層に循環グラフが生成されないようにする必要があります。ツリー管理に加えて、このクラスはシーン内のオブジェクトの位置を記述するために必要なすべてのプロパティを定義します。この情報には基本的な平行移動、回転、スケーリングのプロパティと、ピボット、リミット、IK ジョイント属性（剛性や減衰など）の高度なオプションが含まれます。最初に作成されたとき、Node オブジェクトは "empty"（つまり、位置情報のみを含むグラフィカルな表現を持たないオブジェクト）です。この状態では、ノードツリー構造の親を表すために使用できますが、それ以上のことはできません。この種のオブジェクトの通常の使用方法は、ノードを専門化するエンティティを追加することです（"Entity" を参照）。エンティティはそれ自体がオブジェクトであり、Node に接続されています。これは同じエンティティを複数のノード間で共有できることも意味します。Camera、Light、Mesh などはすべてエンティティであり、すべて基底クラス Entity から派生しています。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [Node()](#Node--) | [Node](../../com.aspose.threed/node) クラスの新しいインスタンスを初期化します。 |
| [Node(String name, Entity entity)](#Node-java.lang.String-com.aspose.threed.Entity-) | [Node](../../com.aspose.threed/node) クラスの新しいインスタンスを初期化します。 |
| [Node(String name)](#Node-java.lang.String-) | [Node](../../com.aspose.threed/node) クラスの新しいインスタンスを初期化します。 |
## Methods

| Method | 説明 |
| --- | --- |
| [accept(NodeVisitor visitor)](#accept-com.aspose.threed.NodeVisitor-) | すべての子孫ノード（現在のノードを含む）を走査し、ノードを引数としてビジターを呼び出します。 |
| [addChildNode(Node node)](#addChildNode-com.aspose.threed.Node-) | このノードに子ノードを追加します。 |
| [addEntity(Entity entity)](#addEntity-com.aspose.threed.Entity-) | ノードにエンティティを追加します。 |
| [createChildNode()](#createChildNode--) | 子ノードを作成します |
| [createChildNode(Entity entity)](#createChildNode-com.aspose.threed.Entity-) | 指定されたエンティティが添付された新しい子ノードを作成します |
| [createChildNode(String nodeName)](#createChildNode-java.lang.String-) | 指定されたノード名で新しい子ノードを作成します |
| [createChildNode(String nodeName, Entity entity)](#createChildNode-java.lang.String-com.aspose.threed.Entity-) | 指定されたノード名で新しい子ノードを作成します |
| [createChildNode(String nodeName, Entity entity, Material material)](#createChildNode-java.lang.String-com.aspose.threed.Entity-com.aspose.threed.Material-) | 指定されたノード名で新しい子ノードを作成し、指定されたエンティティとマテリアルを添付します |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [evaluateGlobalTransform(boolean withGeometricTransform)](#evaluateGlobalTransform-boolean-) | グローバル変換を評価し、幾何変換を含めるかどうかを指定します。 |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | プロパティを検索します。 |
| [getAssetInfo()](#getAssetInfo--) | ノードごとのアセット情報 |
| [getBoundingBox()](#getBoundingBox--) | ノードのバウンディングボックスを計算します |
| [getChild(int index)](#getChild-int-) | 指定されたインデックスの子ノードを取得します。 |
| [getChild(String nodeName)](#getChild-java.lang.String-) | 指定された名前の子ノードを取得します |
| [getChildNodes()](#getChildNodes--) | 子ノードを取得します。 |
| [getClass()](#getClass--) |  |
| [getEntities()](#getEntities--) | すべてのノードエンティティを取得します。 |
| [getEntity()](#getEntity--) | このノードに添付された最初のエンティティを取得します。設定すると、他のエンティティはクリアされます。 |
| [getExcluded()](#getExcluded--) | エクスポート時にこのノードとすべての子ノード/エンティティを除外するかどうかを取得します。 |
| [getGlobalTransform()](#getGlobalTransform--) | グローバル変換を取得します。 |
| [getMaterial()](#getMaterial--) | このノードに関連付けられた最初のマテリアルを取得します。設定すると、他のマテリアルはクリアされます |
| [getMaterials()](#getMaterials--) | このノードに関連付けられたマテリアルを取得します。 |
| [getMetaDatas()](#getMetaDatas--) | このノードで定義されたメタデータを取得します。 |
| [getName()](#getName--) | 名前を取得します。 |
| [getParentNode()](#getParentNode--) | 親ノードを取得します。 |
| [getProperties()](#getProperties--) | すべてのプロパティのコレクションを取得します。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 指定されたプロパティの値を取得します |
| [getScene()](#getScene--) | このオブジェクトが属するシーンを取得します |
| [getTransform()](#getTransform--) | ローカル変換を取得します。 |
| [getVisible()](#getVisible--) | ノードの表示状態を取得します。 |
| [hashCode()](#hashCode--) |  |
| [merge(Node node)](#merge-com.aspose.threed.Node-) | ノード以下のすべてをデタッチし、現在のノードに添付します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 動的プロパティを削除します。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 名前で識別される指定されたプロパティを削除します |
| [selectObjects(String path)](#selectObjects-java.lang.String-) | XPath ライクなクエリ構文を使用して、現在のノード以下の複数オブジェクトを選択します。 |
| [selectSingleObject(String path)](#selectSingleObject-java.lang.String-) | XPath ライクなクエリ構文を使用して、現在のノード以下の単一オブジェクトを選択します。 |
| [setAssetInfo(AssetInfo value)](#setAssetInfo-com.aspose.threed.AssetInfo-) | ノードごとのアセット情報 |
| [setEntity(Entity value)](#setEntity-com.aspose.threed.Entity-) | このノードに添付された最初のエンティティを設定します。設定すると、他のエンティティはクリアされます。 |
| [setExcluded(boolean value)](#setExcluded-boolean-) | エクスポート時にこのノードとすべての子ノード/エンティティを除外するかどうかを設定します。 |
| [setMaterial(Material value)](#setMaterial-com.aspose.threed.Material-) | このノードに関連付けられた最初のマテリアルを設定します。設定すると、他のマテリアルはクリアされます。 |
| [setName(String value)](#setName-java.lang.String-) | 名前を設定します。 |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | 親ノードを設定します。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 指定されたプロパティの値を設定します |
| [setVisible(boolean value)](#setVisible-boolean-) | ノードを表示するように設定します。 |
| [toString()](#toString--) | このノードの文字列表現を取得します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Node() {#Node--}
```
public Node()
```


[Node](../../com.aspose.threed/node) クラスの新しいインスタンスを初期化します。

### Node(String name, Entity entity) {#Node-java.lang.String-com.aspose.threed.Entity-}
```
public Node(String name, Entity entity)
```


[Node](../../com.aspose.threed/node) クラスの新しいインスタンスを初期化します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String | 名前。 |
| entity | [Entity](../../com.aspose.threed/entity) | デフォルトエンティティ。 |

### Node(String name) {#Node-java.lang.String-}
```
public Node(String name)
```


[Node](../../com.aspose.threed/node) クラスの新しいインスタンスを初期化します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String | 名前。 |

### accept(NodeVisitor visitor) {#accept-com.aspose.threed.NodeVisitor-}
```
public boolean accept(NodeVisitor visitor)
```


現在のノードを含むすべての子孫ノードを走査し、ノードを引数としてビジターを呼び出します。ビジターは false を返すことで走査を中断できます。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| visitor | [NodeVisitor](../../com.aspose.threed/nodevisitor) | ノードを訪問するためのビジターコールバック |

**Returns:**
boolean - true はビジターが走査を中断したことを意味します。 **Example:** 以下のコードはシーンからすべてのメッシュを取得する方法を示しています。

```
Scene scene = Scene.fromFile("input.fbx");
     List<Mesh> meshes = new ArrayList<Mesh>();
     scene.getRootNode().accept(new NodeVisitor() {
         @Override
         public boolean call(Node node) {
             if(node.Entity instanceof Mesh)
                 meshes.add(((Mesh)node).getEntity());
             //continue searching
             return true;
         }
     });
```
### addChildNode(Node node) {#addChildNode-com.aspose.threed.Node-}
```
public void addChildNode(Node node)
```


このノードに子ノードを追加します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
|  | node | [Node](../../com.aspose.threed/node) | 添付される子ノード **Example:** 以下のコードはシーンからすべてのメッシュを取得する方法を示しています。 |

```
Scene scene = Scene.fromFile("input.fbx");
     var newNode = new Node();
     //add a new node manually
     scene.getRootNode().addChildNode(newNode);
``` |

### addEntity(Entity entity) {#addEntity-com.aspose.threed.Entity-}
```
public void addEntity(Entity entity)
```


ノードにエンティティを追加します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | ノードに添付されるエンティティ |

### createChildNode() {#createChildNode--}
```
public Node createChildNode()
```


子ノードを作成します

**Returns:**
[Node](../../com.aspose.threed/node) - The new child node. **Example:** The following code shows how to create a new child node under root node

```
Scene scene = new Scene();
     Node node = scene.getRootNode().createChildNode();
     node.setEntity(new Box());
     scene.save("output.fbx");
```
### createChildNode(Entity entity) {#createChildNode-com.aspose.threed.Entity-}
```
public Node createChildNode(Entity entity)
```


指定されたエンティティが添付された新しい子ノードを作成します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | ノードに添付されたデフォルトエンティティ |

**Returns:**
[Node](../../com.aspose.threed/node) - The new child node. **Example:** The following code shows how to create a new child node under root node

```
Scene scene = new Scene();
     Node node = scene.getRootNode().createChildNode(new Box());
     scene.save("output.fbx");
```
### createChildNode(String nodeName) {#createChildNode-java.lang.String-}
```
public Node createChildNode(String nodeName)
```


指定されたノード名で新しい子ノードを作成します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| nodeName | java.lang.String | 新しい子ノードの名前 |

**Returns:**
[Node](../../com.aspose.threed/node) - The new child node. **Example:** The following code shows how to create a new child node under root node

```
Scene scene = new Scene();
     Node node = scene.getRootNode().createChildNode("new node");
     node.setEntity(new Box());
     scene.save("output.fbx");
```
### createChildNode(String nodeName, Entity entity) {#createChildNode-java.lang.String-com.aspose.threed.Entity-}
```
public Node createChildNode(String nodeName, Entity entity)
```


指定されたノード名で新しい子ノードを作成します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| nodeName | java.lang.String | 新しい子ノードの名前 |
| entity | [Entity](../../com.aspose.threed/entity) | ノードに添付されたデフォルトエンティティ |

**Returns:**
[Node](../../com.aspose.threed/node) - The new child node.
### createChildNode(String nodeName, Entity entity, Material material) {#createChildNode-java.lang.String-com.aspose.threed.Entity-com.aspose.threed.Material-}
```
public Node createChildNode(String nodeName, Entity entity, Material material)
```


指定されたノード名で新しい子ノードを作成し、指定されたエンティティとマテリアルを添付します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| nodeName | java.lang.String | 新しい子ノードの名前 |
| entity | [Entity](../../com.aspose.threed/entity) | ノードに添付されたデフォルトエンティティ |
| material | [Material](../../com.aspose.threed/material) | ノードに添付されたマテリアル |

**Returns:**
[Node](../../com.aspose.threed/node) - The new child node.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### evaluateGlobalTransform(boolean withGeometricTransform) {#evaluateGlobalTransform-boolean-}
```
public Matrix4 evaluateGlobalTransform(boolean withGeometricTransform)
```


グローバル変換を評価し、幾何変換を含めるかどうかを指定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| withGeometricTransform | boolean | 幾何変換が必要かどうか。 |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - The global transform matrix. **Example:** The following code shows how to read the node's global transform matrix.

```
Scene scene = new Scene();
     var boxNode = scene.getRootNode().createChildNode(new Box());
     //place the box at (10, 0, 0)
     boxNode.getTransform().setTranslation(new Vector3(10, 0, 0));
     Matrix4 mat = boxNode.evaluateGlobalTransform(true);
     System.out.printf("The box's global transform matrix is %s", mat);
```
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


プロパティを検索します。動的プロパティ（CreateDynamicProperty/SetProperty により作成）またはネイティブプロパティ（名前で識別）になる可能性があります。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| propertyName | java.lang.String | プロパティ名。 |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getAssetInfo() {#getAssetInfo--}
```
public AssetInfo getAssetInfo()
```


ノードごとのアセット情報

**Returns:**
[AssetInfo](../../com.aspose.threed/assetinfo) - Per-node asset info
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


ノードのバウンディングボックスを計算します

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The bounding box of current node
### getChild(int index) {#getChild-int-}
```
public Node getChild(int index)
```


指定されたインデックスの子ノードを取得します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| インデックス | int | インデックスです。 |

**Returns:**
[Node](../../com.aspose.threed/node) - The child. **Example:** The following code shows how to get a child node at specified index.

```
Scene scene = Scene.fromFile("input.fbx");
     var node = scene.getRootNode().getChild(0);
     System.out.printf("The first node of the file is %s", node.getName());
```
### getChild(String nodeName) {#getChild-java.lang.String-}
```
public Node getChild(String nodeName)
```


指定された名前の子ノードを取得します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| nodeName | java.lang.String | 検索する子の名前。 |

**Returns:**
[Node](../../com.aspose.threed/node) - The child. **Example:** The following code shows how to get a child node with specified name

```
Scene scene = Scene.fromFile("input.fbx");
     var node = scene.getRootNode().getChild("box");
     System.out.printf("The box node's translation is %s", node.getTransform().getTranslation());
```
### getChildNodes() {#getChildNodes--}
```
public List<Node> getChildNodes()
```


子ノードを取得します。

**Returns:**
java.util.List<com.aspose.threed.Node> - 子ノードのリストです。 **Example:** 以下のコードはルートノードの子ノードを列挙する方法を示しています。

```
Scene scene = Scene.fromFile("test.fbx");
     for(var child : scene.getRootNode().getChildNodes())
     {
         //do your business
     }
```
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEntities() {#getEntities--}
```
public List<Entity> getEntities()
```


すべてのノードエンティティを取得します。

**Returns:**
java.util.List<com.aspose.threed.Entity> - すべてのノードエンティティ。
### getEntity() {#getEntity--}
```
public Entity getEntity()
```


このノードに添付された最初のエンティティを取得します。設定すると、他のエンティティはクリアされます。

**Returns:**
[Entity](../../com.aspose.threed/entity) - the first entity attached to this node, if sets, will clear other entities. **Example:** The following code shows how to create a new child node under root node

```
Scene scene = new Scene();
     Node node = scene.getRootNode().createChildNode("new node");
     node.setEntity(new Box());
     scene.save("output.fbx");
```
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


エクスポート時にこのノードとすべての子ノード/エンティティを除外するかどうかを取得します。

**Returns:**
boolean - エクスポート時にこのノードとすべての子ノード/エンティティを除外するかどうか。 **Example:** 以下のコードは指定したノードをエクスポートから除外する方法を示しています。

```
Scene scene = new Scene();
     scene.getRootNode().createChildNode("excluded", new Box()).setExcluded(true);
     scene.getRootNode().createChildNode("not excluded", new Box());
     scene.save("output.usdz");
```
### getGlobalTransform() {#getGlobalTransform--}
```
public GlobalTransform getGlobalTransform()
```


グローバル変換を取得します。

**Returns:**
[GlobalTransform](../../com.aspose.threed/globaltransform) - the global transform. **Example:** The following code shows how to read node's global transform

```
Scene scene = new Scene();
     var boxNode = scene.getRootNode().createChildNode(new Box());
     //place the box at (10, 0, 0)
     boxNode.getTransform().setTranslation(new Vector3(10, 0, 0));
     var global = boxNode.getGlobalTransform();
     System.out.printf("The box's position in world coordinate is %s", global.getTranslation());
```
### getMaterial() {#getMaterial--}
```
public Material getMaterial()
```


このノードに関連付けられた最初のマテリアルを取得します。設定すると、他のマテリアルはクリアされます

**Returns:**
[Material](../../com.aspose.threed/material) - the first material associated with this node, if sets, will clear other materials **Example:**

```
Scene scene = new Scene();
     var node = scene.getRootNode().createChildNode(new Box());
     node.setMaterial(new LambertMaterial());
```
### getMaterials() {#getMaterials--}
```
public List<Material> getMaterials()
```


このノードに関連付けられたマテリアルを取得します。

**Returns:**
java.util.List<com.aspose.threed.Material> - このノードに関連付けられたマテリアル。
### getMetaDatas() {#getMetaDatas--}
```
public List<CustomObject> getMetaDatas()
```


このノードで定義されたメタデータを取得します。

**Returns:**
java.util.List<com.aspose.threed.CustomObject> - このノードで定義されたメタデータ。
### getName() {#getName--}
```
public String getName()
```


名前を取得します。

**Returns:**
java.lang.String - 名前です。
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


親ノードを取得します。

**Returns:**
[Node](../../com.aspose.threed/node) - the parent node.
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


すべてのプロパティのコレクションを取得します。

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


指定されたプロパティの値を取得します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| プロパティ | java.lang.String | プロパティ名 |

**Returns:**
java.lang.Object - 見つかったプロパティの値
### getScene() {#getScene--}
```
public Scene getScene()
```


このオブジェクトが属するシーンを取得します

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getTransform() {#getTransform--}
```
public Transform getTransform()
```


ローカル変換を取得します。

**Returns:**
[Transform](../../com.aspose.threed/transform) - the local transform. **Example:** The following code shows how to change the transform of the node:

```
Scene scene = new Scene();
     var boxNode = scene.getRootNode().createChildNode(new Box());
     //place the box at (10, 0, 0)
     boxNode.getTransform().setTranslation(new Vector3(10, 0, 0));
```
### getVisible() {#getVisible--}
```
public boolean getVisible()
```


ノードの表示状態を取得します。

**Returns:**
boolean - ノードを表示するかどうか。 **Example:** 以下のコードは不可視ノードを作成する方法を示しています。

```
Scene scene = new Scene();
     Node node = scene.getRootNode().createChildNode("test-node", new Box());
     node.setVisible(false);
     scene.save("output.fbx");
```
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### merge(Node node) {#merge-com.aspose.threed.Node-}
```
public void merge(Node node)
```


ノード以下のすべてを切り離し、現在のノードに添付します。 **Example:** 以下のコードは2つの3Dファイルを1つのファイルにマージする方法を示しています。

```
Scene scene1 = Scene.fromFile("scene1.fbx");
     Scene scene2 = Scene.fromFile("scene2.fbx");
     scene1.getRootNode().merge(scene2.getRootNode());
     scene1.save("merged.fbx");
```

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) |  |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeProperty(Property property) {#removeProperty-com.aspose.threed.Property-}
```
public boolean removeProperty(Property property)
```


動的プロパティを削除します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | 削除するプロパティ |

**Returns:**
boolean - プロパティが正常に削除された場合は true
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


名前で識別される指定されたプロパティを削除します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| プロパティ | java.lang.String | 削除するプロパティ |

**Returns:**
boolean - プロパティが正常に削除された場合は true
### selectObjects(String path) {#selectObjects-java.lang.String-}
```
public ArrayList<Object> selectObjects(String path)
```


XPath ライクなクエリ構文を使用して、現在のノード以下の複数オブジェクトを選択します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| path | java.lang.String | XPath 風のクエリ |

**Returns:**
java.util.ArrayList<java.lang.Object> - XPath のようなクエリに一致する複数のオブジェクトです。
### selectSingleObject(String path) {#selectSingleObject-java.lang.String-}
```
public Object selectSingleObject(String path)
```


XPath ライクなクエリ構文を使用して、現在のノード以下の単一オブジェクトを選択します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| path | java.lang.String | XPath 風のクエリ |

**Returns:**
java.lang.Object - XPath のようなクエリで見つかったオブジェクトです。
### setAssetInfo(AssetInfo value) {#setAssetInfo-com.aspose.threed.AssetInfo-}
```
public void setAssetInfo(AssetInfo value)
```


ノードごとのアセット情報

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [AssetInfo](../../com.aspose.threed/assetinfo) | 新しい値 |

### setEntity(Entity value) {#setEntity-com.aspose.threed.Entity-}
```
public void setEntity(Entity value)
```


このノードに添付された最初のエンティティを設定します。設定すると、他のエンティティはクリアされます。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
|  | value | [Entity](../../com.aspose.threed/entity) | 新しい値 **Example:** 以下のコードは、ルートノードの下に新しい子ノードを作成する方法を示しています。 |

```
Scene scene = new Scene();
     Node node = scene.getRootNode().createChildNode("new node");
     node.setEntity(new Box());
     scene.save("output.fbx");
``` |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


エクスポート時にこのノードとすべての子ノード/エンティティを除外するかどうかを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
|  | 値 | boolean | 新しい値 **Example:** 以下のコードは、指定されたノードをエクスポートから除外する方法を示しています。 |

```
Scene scene = new Scene();
     scene.getRootNode().createChildNode("excluded", new Box()).setExcluded(true);
     scene.getRootNode().createChildNode("not excluded", new Box());
     scene.save("output.usdz");
``` |

### setMaterial(Material value) {#setMaterial-com.aspose.threed.Material-}
```
public void setMaterial(Material value)
```


このノードに関連付けられた最初のマテリアルを設定します。設定すると、他のマテリアルはクリアされます。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
|  | value | [Material](../../com.aspose.threed/material) | 新しい値 **Example:** |

```
Scene scene = new Scene();
     var node = scene.getRootNode().createChildNode(new Box());
     node.setMaterial(new LambertMaterial());
``` |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


名前を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


親ノードを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | 新しい値 |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


指定されたプロパティの値を設定します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| プロパティ | java.lang.String | プロパティ名 |
| 値 | java.lang.Object | プロパティの値 |

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


ノードを表示するように設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
|  | 値 | boolean | 新しい値 **Example:** 以下のコードは、不可視ノードを作成する方法を示しています。 |

```
Scene scene = new Scene();
     Node node = scene.getRootNode().createChildNode("test-node", new Box());
     node.setVisible(false);
     scene.save("output.fbx");
``` |

### toString() {#toString--}
```
public String toString()
```


このノードの文字列表現を取得します。

**Returns:**
java.lang.String - デバッグ用のこのノードの文字列表現です。
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

