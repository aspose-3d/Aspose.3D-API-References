---
title: ピラミッド
second_title: Aspose.3D for Java API リファレンス
description: パラメータ化されたピラミッドです。
type: docs
weight: 142
url: /ja/java/com.aspose.threed/pyramid/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Primitive](../../com.aspose.threed/primitive)
```
public class Pyramid extends Primitive
```

パラメータ化されたピラミッドです。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [Pyramid()](#Pyramid--) | デフォルトの底面積(10, 10)とデフォルトの高さ(5)で新しいピラミッドインスタンスを構築する |
| [Pyramid(double xbottom, double ybottom, double height)](#Pyramid-double-double-double-) | 指定された底面積で新しいピラミッドインスタンスを構築する |
| [Pyramid(double xbottom, double ybottom, double xtop, double ytop, double height)](#Pyramid-double-double-double-double-double-) | 指定された底面積と上面積と高さで新しいピラミッドインスタンスを構築する。 |
| [Pyramid(String name, double xbottom, double ybottom, double xtop, double ytop, double height)](#Pyramid-java.lang.String-double-double-double-double-double-) | 指定された底面積と上面積と高さで新しいピラミッドインスタンスを構築する。 |
## Methods

| Method | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | プロパティを検索します。 |
| [getBottomArea()](#getBottomArea--) | 底面キャップの面積 |
| [getBottomOffset()](#getBottomOffset--) | 底部頂点のオフセット |
| [getBoundingBox()](#getBoundingBox--) | 現在のエンティティのオブジェクト空間座標系におけるバウンディングボックスを取得します。 |
| [getCastShadows()](#getCastShadows--) | このジオメトリが影を落とすかどうかを取得します |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | レンダラーに登録されたエンティティレンダラーのキーを取得します |
| [getExcluded()](#getExcluded--) | エクスポート時にこのエンティティを除外するかどうかを取得します。 |
| [getHeight()](#getHeight--) | ピラミッドの高さ |
| [getName()](#getName--) | 名前を取得します。 |
| [getParentNode()](#getParentNode--) | 最初の親ノードを取得します。最初の親ノードを設定すると、このエンティティは他の親ノードから切り離されます。 |
| [getParentNodes()](#getParentNodes--) | すべての親ノードを取得します。エンティティはジオメトリインスタンシングのために複数の親ノードにアタッチできます。 |
| [getProperties()](#getProperties--) | すべてのプロパティのコレクションを取得します。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 指定されたプロパティの値を取得します |
| [getReceiveShadows()](#getReceiveShadows--) | このジオメトリが影を受け取るかどうかを取得します。 |
| [getScene()](#getScene--) | このオブジェクトが属するシーンを取得します |
| [getTopArea()](#getTopArea--) | 上面キャップの面積 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 動的プロパティを削除します。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 名前で識別される指定されたプロパティを削除します |
| [setBottomArea(Vector2 value)](#setBottomArea-com.aspose.threed.Vector2-) | 底面キャップの面積 |
| [setBottomOffset(Vector3 value)](#setBottomOffset-com.aspose.threed.Vector3-) | 底部頂点のオフセット |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | このジオメトリが影を落とすかどうかを設定します |
| [setExcluded(boolean value)](#setExcluded-boolean-) | エクスポート時にこのエンティティを除外するかどうかを設定します。 |
| [setHeight(double value)](#setHeight-double-) | ピラミッドの高さ |
| [setName(String value)](#setName-java.lang.String-) | 名前を設定します。 |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | 最初の親ノードを設定します。最初の親ノードを設定すると、このエンティティは他の親ノードから切り離されます。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 指定されたプロパティの値を設定します |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | このジオメトリが影を受け取るかどうかを設定します。 |
| [setTopArea(Vector2 value)](#setTopArea-com.aspose.threed.Vector2-) | 上面キャップの面積 |
| [toMesh()](#toMesh--) | 現在のオブジェクトをメッシュに変換します |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Pyramid() {#Pyramid--}
```
public Pyramid()
```


デフォルトの底面積(10, 10)とデフォルトの高さ(5)で新しいピラミッドインスタンスを構築する

### Pyramid(double xbottom, double ybottom, double height) {#Pyramid-double-double-double-}
```
public Pyramid(double xbottom, double ybottom, double height)
```


指定された底面積で新しいピラミッドインスタンスを構築する

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| xbottom | double | 底部のX方向の長さ |
| ybottom | double | 底部のY方向の長さ |
| 高さ | double | ピラミッドの高さ |

### Pyramid(double xbottom, double ybottom, double xtop, double ytop, double height) {#Pyramid-double-double-double-double-double-}
```
public Pyramid(double xbottom, double ybottom, double xtop, double ytop, double height)
```


指定された底面積と上面積と高さで新しいピラミッドインスタンスを構築する。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| xbottom | double | 底面積のX方向の長さ |
| ybottom | double | 底面積のY方向の長さ |
| xtop | double | 上面積のX方向の長さ |
| ytop | double | 上面積のY方向の長さ |
| 高さ | double | ピラミッドの高さ |

### Pyramid(String name, double xbottom, double ybottom, double xtop, double ytop, double height) {#Pyramid-java.lang.String-double-double-double-double-double-}
```
public Pyramid(String name, double xbottom, double ybottom, double xtop, double ytop, double height)
```


指定された底面積と上面積と高さで新しいピラミッドインスタンスを構築する。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String | ピラミッドの名前 |
| xbottom | double | 底面積のX方向の長さ |
| ybottom | double | 底面積のY方向の長さ |
| xtop | double | 上面積のX方向の長さ |
| ytop | double | 上面積のY方向の長さ |
| 高さ | double | ピラミッドの高さ |

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
### getBottomArea() {#getBottomArea--}
```
public Vector2 getBottomArea()
```


底面キャップの面積

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - Area of the bottom cap
### getBottomOffset() {#getBottomOffset--}
```
public Vector3 getBottomOffset()
```


底部頂点のオフセット

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Offset for bottom vertices
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
### getCastShadows() {#getCastShadows--}
```
public boolean getCastShadows()
```


このジオメトリが影を落とすかどうかを取得します

**Returns:**
boolean - このジオメトリが影を落とすかどうか
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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


ピラミッドの高さ

**Returns:**
double - ピラミッドの高さ
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
### getReceiveShadows() {#getReceiveShadows--}
```
public boolean getReceiveShadows()
```


このジオメトリが影を受け取るかどうかを取得します。

**Returns:**
boolean - このジオメトリが影を受け取れるかどうか。
### getScene() {#getScene--}
```
public Scene getScene()
```


このオブジェクトが属するシーンを取得します

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getTopArea() {#getTopArea--}
```
public Vector2 getTopArea()
```


上面キャップの面積

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - Area of the top cap
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
### setBottomArea(Vector2 value) {#setBottomArea-com.aspose.threed.Vector2-}
```
public void setBottomArea(Vector2 value)
```


底面キャップの面積

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | 新しい値 |

### setBottomOffset(Vector3 value) {#setBottomOffset-com.aspose.threed.Vector3-}
```
public void setBottomOffset(Vector3 value)
```


底部頂点のオフセット

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新しい値 |

### setCastShadows(boolean value) {#setCastShadows-boolean-}
```
public void setCastShadows(boolean value)
```


このジオメトリが影を落とすかどうかを設定します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

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


ピラミッドの高さ

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

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


このジオメトリが影を受け取るかどうかを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setTopArea(Vector2 value) {#setTopArea-com.aspose.threed.Vector2-}
```
public void setTopArea(Vector2 value)
```


上面キャップの面積

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | 新しい値 |

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

