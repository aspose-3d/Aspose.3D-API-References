---
title: LinearExtrusion
second_title: Aspose.3D for Java API リファレンス
description: 線形押し出しは 2D 形状を入力として受け取り、形状を第3次元に拡張します。
type: docs
weight: 96
url: /ja/java/com.aspose.threed/linearextrusion/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity)

**All Implemented Interfaces:**
[com.aspose.threed.IMeshConvertible](../../com.aspose.threed/imeshconvertible)
```
public class LinearExtrusion extends Entity implements IMeshConvertible
```

Linear extrusion は 2D 形状を入力として受け取り、形状を第3次元に伸長します。 **Example:** 以下のコードは LinearExtrusion を使用して形状をソリッドモデルに押し出す方法を示しています。

```
//Create a new 3D scene
 		Scene scene = new Scene();
 
 		// Initialize the base profile to be extruded
 		var profile = new RectangleShape();
 		profile.setRoundingRadius(0.3);
 
 		// Create left node
 		var left = scene.getRootNode().createChildNode();
 		left.createChildNode(new Box(0.01, 3, 3));
 
 		// Create right node
 		var right = scene.getRootNode().createChildNode();
 		right.createChildNode(new Box(0.01, 3, 3));
 		right.getTransform().setTranslation(new Vector3(5, 0, 0));
 
 		//Perform linear extrusion on left node using center and slices property
 		var l = new LinearExtrusion(profile, 10);
 		l.setCenter(false);
 		l.setSlices(3);
 		l.setTwist(20);
 		left.createChildNode(l);
 
 		// Perform linear extrusion on left node using center and slices property
 		var r = new LinearExtrusion(profile, 10);
 		r.setCenter(true);
 		r.setSlices(3);
 		r.setTwist(90);
 		right.createChildNode(r);
```
## Constructors

| Constructor | 説明 |
| --- | --- |
| [LinearExtrusion()](#LinearExtrusion--) | インスタンス [LinearExtrusion](../../com.aspose.threed/linearextrusion) のコンストラクタ。 |
| [LinearExtrusion(Profile shape, double height)](#LinearExtrusion-com.aspose.threed.Profile-double-) | インスタンス [LinearExtrusion](../../com.aspose.threed/linearextrusion) のコンストラクタ。 |
## Methods

| Method | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | プロパティを検索します。 |
| [getBoundingBox()](#getBoundingBox--) | 現在のエンティティのオブジェクト空間座標系におけるバウンディングボックスを取得します。 |
| [getCenter()](#getCenter--) | この値が false の場合、線形押し出しの Z 範囲は 0 から高さまでになり、そうでない場合は範囲が -height/2 から height/2 になります。 |
| [getClass()](#getClass--) |  |
| [getDirection()](#getDirection--) | 押し出しの方向、デフォルト値は (0, 0, 1) |
| [getEntityRendererKey()](#getEntityRendererKey--) | レンダラーに登録されたエンティティレンダラーのキーを取得します |
| [getExcluded()](#getExcluded--) | エクスポート時にこのエンティティを除外するかどうかを取得します。 |
| [getHeight()](#getHeight--) | 押し出されたジオメトリの高さ、デフォルト値は 1.0 |
| [getName()](#getName--) | 名前を取得します。 |
| [getParentNode()](#getParentNode--) | 最初の親ノードを取得します。最初の親ノードを設定すると、このエンティティは他の親ノードから切り離されます。 |
| [getParentNodes()](#getParentNodes--) | すべての親ノードを取得します。エンティティはジオメトリインスタンシングのために複数の親ノードにアタッチできます。 |
| [getProperties()](#getProperties--) | すべてのプロパティのコレクションを取得します。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 指定されたプロパティの値を取得します |
| [getScene()](#getScene--) | このオブジェクトが属するシーンを取得します |
| [getShape()](#getShape--) | 押し出すベース形状。 |
| [getSlices()](#getSlices--) | ねじれた押し出しジオメトリのスライス数、デフォルト値は 1。 |
| [getTwist()](#getTwist--) | 形状が押し出される角度（度数）。 |
| [getTwistOffset()](#getTwistOffset--) | ねじりに使用されるオフセット、デフォルト値は (0, 0, 0)。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 動的プロパティを削除します。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 名前で識別される指定されたプロパティを削除します |
| [setCenter(boolean value)](#setCenter-boolean-) | この値が false の場合、線形押し出しの Z 範囲は 0 から高さまでになり、そうでない場合は範囲が -height/2 から height/2 になります。 |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | 押し出しの方向、デフォルト値は (0, 0, 1) |
| [setExcluded(boolean value)](#setExcluded-boolean-) | エクスポート時にこのエンティティを除外するかどうかを設定します。 |
| [setHeight(double value)](#setHeight-double-) | 押し出されたジオメトリの高さ、デフォルト値は 1.0 |
| [setName(String value)](#setName-java.lang.String-) | 名前を設定します。 |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | 最初の親ノードを設定します。最初の親ノードを設定すると、このエンティティは他の親ノードから切り離されます。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 指定されたプロパティの値を設定します |
| [setShape(Profile value)](#setShape-com.aspose.threed.Profile-) | 押し出すベース形状。 |
| [setSlices(int value)](#setSlices-int-) | ねじれた押し出しジオメトリのスライス数、デフォルト値は 1。 |
| [setTwist(double value)](#setTwist-double-) | 形状が押し出される角度（度数）。 |
| [setTwistOffset(Vector3 value)](#setTwistOffset-com.aspose.threed.Vector3-) | ねじりに使用されるオフセット、デフォルト値は (0, 0, 0)。 |
| [toMesh()](#toMesh--) | 押し出しをメッシュに変換します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LinearExtrusion() {#LinearExtrusion--}
```
public LinearExtrusion()
```


インスタンス [LinearExtrusion](../../com.aspose.threed/linearextrusion) のコンストラクタ。

### LinearExtrusion(Profile shape, double height) {#LinearExtrusion-com.aspose.threed.Profile-double-}
```
public LinearExtrusion(Profile shape, double height)
```


インスタンス [LinearExtrusion](../../com.aspose.threed/linearextrusion) のコンストラクタ。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| shape | [Profile](../../com.aspose.threed/profile) |  |
| 高さ | double |  |

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
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


現在のエンティティのオブジェクト空間座標系におけるバウンディングボックスを取得します。

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - the bounding box of current entity in its object space coordinate system. **Example:** The following code shows how to calculate the bounding box of a shape

```
Entity entity = new Sphere();
     entity.setRadius(10);
     var bbox = entity.getBoundingBox();
     System.out.printf("The bounding box of the entity is %s ~ %s", bbox.getMinimum(), bbox.getMaximum());
```
### getCenter() {#getCenter--}
```
public boolean getCenter()
```


この値が false の場合、線形押し出しの Z 範囲は 0 から高さまでになり、そうでない場合は範囲が -height/2 から height/2 になります。

**Returns:**
boolean - この値が false の場合、線形押し出しの Z 範囲は 0 から高さまでになり、そうでない場合は範囲が -height/2 から height/2 になります。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDirection() {#getDirection--}
```
public Vector3 getDirection()
```


押し出しの方向、デフォルト値は (0, 0, 1)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The direction of extrusion, default value is (0, 0, 1)
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


レンダラーに登録されたエンティティレンダラーのキーを取得します

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey) - the key of the entity renderer registered in the renderer
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


エクスポート時にこのエンティティを除外するかどうかを取得します。

**Returns:**
boolean - エクスポート時にこのエンティティを除外するかどうか。
### getHeight() {#getHeight--}
```
public double getHeight()
```


押し出されたジオメトリの高さ、デフォルト値は 1.0

**Returns:**
double - 押し出されたジオメトリの高さ、デフォルト値は 1.0
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


最初の親ノードを取得します。最初の親ノードを設定すると、このエンティティは他の親ノードから切り離されます。

**Returns:**
[Node](../../com.aspose.threed/node) - the first parent node, if set the first parent node, this entity will be detached from other parent nodes.
### getParentNodes() {#getParentNodes--}
```
public ArrayList<Node> getParentNodes()
```


すべての親ノードを取得します。エンティティはジオメトリインスタンシングのために複数の親ノードにアタッチできます。

**Returns:**
java.util.ArrayList<com.aspose.threed.Node> - すべての親ノード、エンティティはジオメトリ インスタンシングのために複数の親ノードにアタッチできます
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
### getShape() {#getShape--}
```
public Profile getShape()
```


押し出すベース形状。

**Returns:**
[Profile](../../com.aspose.threed/profile) - The base shape to be extruded.
### getSlices() {#getSlices--}
```
public int getSlices()
```


ねじれた押し出しジオメトリのスライス数、デフォルト値は 1。

**Returns:**
int - ねじれた押し出しジオメトリのスライス数、デフォルト値は 1。
### getTwist() {#getTwist--}
```
public double getTwist()
```


形状が押し出される角度（度数）。

**Returns:**
double - 形状が押し出される角度（度数）。
### getTwistOffset() {#getTwistOffset--}
```
public Vector3 getTwistOffset()
```


ねじりに使用されるオフセット、デフォルト値は (0, 0, 0)。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The offset that used in twisting, default value is (0, 0, 0).
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
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
### setCenter(boolean value) {#setCenter-boolean-}
```
public void setCenter(boolean value)
```


この値が false の場合、線形押し出しの Z 範囲は 0 から高さまでになり、そうでない場合は範囲が -height/2 から height/2 になります。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setDirection(Vector3 value) {#setDirection-com.aspose.threed.Vector3-}
```
public void setDirection(Vector3 value)
```


押し出しの方向、デフォルト値は (0, 0, 1)

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新しい値 |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


エクスポート時にこのエンティティを除外するかどうかを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


押し出されたジオメトリの高さ、デフォルト値は 1.0

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

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


最初の親ノードを設定します。最初の親ノードを設定すると、このエンティティは他の親ノードから切り離されます。

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

### setShape(Profile value) {#setShape-com.aspose.threed.Profile-}
```
public void setShape(Profile value)
```


押し出すベース形状。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Profile](../../com.aspose.threed/profile) | 新しい値 |

### setSlices(int value) {#setSlices-int-}
```
public void setSlices(int value)
```


ねじれた押し出しジオメトリのスライス数、デフォルト値は 1。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | int | 新しい値 |

### setTwist(double value) {#setTwist-double-}
```
public void setTwist(double value)
```


形状が押し出される角度（度数）。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

### setTwistOffset(Vector3 value) {#setTwistOffset-com.aspose.threed.Vector3-}
```
public void setTwistOffset(Vector3 value)
```


ねじりに使用されるオフセット、デフォルト値は (0, 0, 0)。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新しい値 |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


押し出しをメッシュに変換します。

**Returns:**
[Mesh](../../com.aspose.threed/mesh)
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

