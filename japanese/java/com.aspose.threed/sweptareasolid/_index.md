---
title: SweptAreaSolid
second_title: Aspose.3D for Java API リファレンス
description: A はプロファイルを導軌に沿ってスイープすることでジオメトリを構築します。
type: docs
weight: 181
url: /ja/java/com.aspose.threed/sweptareasolid/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity)

**All Implemented Interfaces:**
[com.aspose.threed.IMeshConvertible](../../com.aspose.threed/imeshconvertible)
```
public class SweptAreaSolid extends Entity implements IMeshConvertible
```

A [SweptAreaSolid](../../com.aspose.threed/sweptareasolid) はプロファイルを導軌に沿ってスイープすることでジオメトリを構築します。 **Example:** 以下のコードは、円上で C 形状をスイープしてソリッドエンティティをモデリングする方法を示しています。

```
var directrix = new Circle(20);
         var shape = new CShape();
 
         var swept = new SweptAreaSolid();
         swept.setShape(shape);
         swept.setDirectrix(directrix);
         swept.setStartPoint(EndPoint.fromDegree(0));
         swept.setEndPoint(EndPoint.fromDegree(130));
 
         var scene = new Scene();
         scene.getRootNode().createChildNode(swept);
         scene.save("swept.obj");
```
## Constructors

| Constructor | 説明 |
| --- | --- |
| [SweptAreaSolid()](#SweptAreaSolid--) |  |
## Methods

| Method | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | プロパティを検索します。 |
| [getBoundingBox()](#getBoundingBox--) | 現在のエンティティのオブジェクト空間座標系におけるバウンディングボックスを取得します。 |
| [getClass()](#getClass--) |  |
| [getDirectrix()](#getDirectrix--) | スイープ領域が沿ってスイープされる導軌です。 |
| [getEndPoint()](#getEndPoint--) | 導軌の終点です。 |
| [getEntityRendererKey()](#getEntityRendererKey--) | レンダラーに登録されたエンティティレンダラーのキーを取得します |
| [getExcluded()](#getExcluded--) | エクスポート時にこのエンティティを除外するかどうかを取得します。 |
| [getName()](#getName--) | 名前を取得します。 |
| [getParentNode()](#getParentNode--) | 最初の親ノードを取得します。最初の親ノードを設定すると、このエンティティは他の親ノードから切り離されます。 |
| [getParentNodes()](#getParentNodes--) | すべての親ノードを取得します。エンティティはジオメトリインスタンシングのために複数の親ノードにアタッチできます。 |
| [getProperties()](#getProperties--) | すべてのプロパティのコレクションを取得します。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 指定されたプロパティの値を取得します |
| [getScene()](#getScene--) | このオブジェクトが属するシーンを取得します |
| [getShape()](#getShape--) | ジオメトリを構築するためのベースプロファイルです。 |
| [getStartPoint()](#getStartPoint--) | 導軌の始点です。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 動的プロパティを削除します。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 名前で識別される指定されたプロパティを削除します |
| [setDirectrix(Curve value)](#setDirectrix-com.aspose.threed.Curve-) | スイープ領域が沿ってスイープされる導軌です。 |
| [setEndPoint(EndPoint value)](#setEndPoint-com.aspose.threed.EndPoint-) | 導軌の終点です。 |
| [setExcluded(boolean value)](#setExcluded-boolean-) | エクスポート時にこのエンティティを除外するかどうかを設定します。 |
| [setName(String value)](#setName-java.lang.String-) | 名前を設定します。 |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | 最初の親ノードを設定します。最初の親ノードを設定すると、このエンティティは他の親ノードから切り離されます。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 指定されたプロパティの値を設定します |
| [setShape(Profile value)](#setShape-com.aspose.threed.Profile-) | ジオメトリを構築するためのベースプロファイルです。 |
| [setStartPoint(EndPoint value)](#setStartPoint-com.aspose.threed.EndPoint-) | 導軌の始点です。 |
| [toMesh()](#toMesh--) | 現在のオブジェクトをメッシュに変換します |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SweptAreaSolid() {#SweptAreaSolid--}
```
public SweptAreaSolid()
```


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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDirectrix() {#getDirectrix--}
```
public Curve getDirectrix()
```


スイープ領域が沿ってスイープされる導軌です。

**Returns:**
[Curve](../../com.aspose.threed/curve) - The directrix that the swept area sweeping along with.
### getEndPoint() {#getEndPoint--}
```
public EndPoint getEndPoint()
```


導軌の終点です。

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint) - The end point of the directrix.
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


ジオメトリを構築するためのベースプロファイルです。

**Returns:**
[Profile](../../com.aspose.threed/profile) - The base profile to construct the geometry.
### getStartPoint() {#getStartPoint--}
```
public EndPoint getStartPoint()
```


導軌の始点です。

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint) - The start point of the directrix.
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
### setDirectrix(Curve value) {#setDirectrix-com.aspose.threed.Curve-}
```
public void setDirectrix(Curve value)
```


スイープ領域が沿ってスイープされる導軌です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Curve](../../com.aspose.threed/curve) | 新しい値 |

### setEndPoint(EndPoint value) {#setEndPoint-com.aspose.threed.EndPoint-}
```
public void setEndPoint(EndPoint value)
```


導軌の終点です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [EndPoint](../../com.aspose.threed/endpoint) | 新しい値 |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


エクスポート時にこのエンティティを除外するかどうかを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

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


ジオメトリを構築するためのベースプロファイルです。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Profile](../../com.aspose.threed/profile) | 新しい値 |

### setStartPoint(EndPoint value) {#setStartPoint-com.aspose.threed.EndPoint-}
```
public void setStartPoint(EndPoint value)
```


導軌の始点です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [EndPoint](../../com.aspose.threed/endpoint) | 新しい値 |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


現在のオブジェクトをメッシュに変換します

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - The mesh.
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

