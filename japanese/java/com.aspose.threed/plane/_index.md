---
title: Plane
second_title: Aspose.3D for Java API リファレンス
description: パラメトリック平面。
type: docs
weight: 128
url: /ja/java/com.aspose.threed/plane/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Primitive](../../com.aspose.threed/primitive)
```
public class Plane extends Primitive
```

パラメトリック平面。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [Plane()](#Plane--) | デフォルトサイズ 1x1 の [Plane](../../com.aspose.threed/plane) の新しいインスタンスを初期化します。 |
| [Plane(double length, double width)](#Plane-double-double-) | [Plane](../../com.aspose.threed/plane) の新しいインスタンスを初期化します。 |
| [Plane(String name, double length, double width, int lengthSegments, int widthSegments)](#Plane-java.lang.String-double-double-int-int-) | [Plane](../../com.aspose.threed/plane) の新しいインスタンスを初期化します。 |
## Methods

| Method | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | プロパティを検索します。 |
| [getBoundingBox()](#getBoundingBox--) | 現在のエンティティのオブジェクト空間座標系におけるバウンディングボックスを取得します。 |
| [getCastShadows()](#getCastShadows--) | このジオメトリが影を落とすかどうかを取得します |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | レンダラーに登録されたエンティティレンダラーのキーを取得します |
| [getExcluded()](#getExcluded--) | エクスポート時にこのエンティティを除外するかどうかを取得します。 |
| [getLength()](#getLength--) | 平面の長さを取得します。 |
| [getLengthSegments()](#getLengthSegments--) | 長さのセグメントを取得します。 |
| [getName()](#getName--) | 名前を取得します。 |
| [getParentNode()](#getParentNode--) | 最初の親ノードを取得します。最初の親ノードを設定すると、このエンティティは他の親ノードから切り離されます。 |
| [getParentNodes()](#getParentNodes--) | すべての親ノードを取得します。エンティティはジオメトリインスタンシングのために複数の親ノードにアタッチできます。 |
| [getProperties()](#getProperties--) | すべてのプロパティのコレクションを取得します。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 指定されたプロパティの値を取得します |
| [getReceiveShadows()](#getReceiveShadows--) | このジオメトリが影を受け取るかどうかを取得します。 |
| [getScene()](#getScene--) | このオブジェクトが属するシーンを取得します |
| [getUp()](#getUp--) | 平面の上方向ベクトルを取得します。デフォルト値は (0, 1, 0) で、平面の生成に影響します。 |
| [getWidth()](#getWidth--) | 平面の幅を取得します。 |
| [getWidthSegments()](#getWidthSegments--) | 幅のセグメントを取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 動的プロパティを削除します。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 名前で識別される指定されたプロパティを削除します |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | このジオメトリが影を落とすかどうかを設定します |
| [setExcluded(boolean value)](#setExcluded-boolean-) | エクスポート時にこのエンティティを除外するかどうかを設定します。 |
| [setLength(double value)](#setLength-double-) | 平面の長さを設定します。 |
| [setLengthSegments(int value)](#setLengthSegments-int-) | 長さのセグメントを設定します。 |
| [setName(String value)](#setName-java.lang.String-) | 名前を設定します。 |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | 最初の親ノードを設定します。最初の親ノードを設定すると、このエンティティは他の親ノードから切り離されます。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 指定されたプロパティの値を設定します |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | このジオメトリが影を受け取るかどうかを設定します。 |
| [setUp(Vector3 value)](#setUp-com.aspose.threed.Vector3-) | 平面の上方向ベクトルを設定します。デフォルト値は (0, 1, 0) で、平面の生成に影響します。 |
| [setWidth(double value)](#setWidth-double-) | 平面の幅を設定します。 |
| [setWidthSegments(int value)](#setWidthSegments-int-) | 幅のセグメントを設定します。 |
| [toMesh()](#toMesh--) | 現在のオブジェクトをメッシュに変換します |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Plane() {#Plane--}
```
public Plane()
```


デフォルトサイズ 1x1 の [Plane](../../com.aspose.threed/plane) の新しいインスタンスを初期化します。

### Plane(double length, double width) {#Plane-double-double-}
```
public Plane(double length, double width)
```


[Plane](../../com.aspose.threed/plane) の新しいインスタンスを初期化します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 長さ | double | 平面の長さ。 |
| 幅 | double | 平面の幅。 |

### Plane(String name, double length, double width, int lengthSegments, int widthSegments) {#Plane-java.lang.String-double-double-int-int-}
```
public Plane(String name, double length, double width, int lengthSegments, int widthSegments)
```


[Plane](../../com.aspose.threed/plane) の新しいインスタンスを初期化します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String | 名前。 |
| 長さ | double | 平面の長さ。 |
| 幅 | double | 平面の幅。 |
| lengthSegments | int | 長さのセグメント。 |
| widthSegments | int | 幅のセグメント。 |

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
### getLength() {#getLength--}
```
public double getLength()
```


平面の長さを取得します。

**Returns:**
double - 平面の長さ。
### getLengthSegments() {#getLengthSegments--}
```
public int getLengthSegments()
```


長さのセグメントを取得します。

**Returns:**
int - 長さのセグメント。
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
### getUp() {#getUp--}
```
public Vector3 getUp()
```


平面の上方向ベクトルを取得します。デフォルト値は (0, 1, 0) で、平面の生成に影響します。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the up vector of the plane, default value is (0, 1, 0), this affects the generation of the plane
### getWidth() {#getWidth--}
```
public double getWidth()
```


平面の幅を取得します。

**Returns:**
double - 平面の幅。
### getWidthSegments() {#getWidthSegments--}
```
public int getWidthSegments()
```


幅のセグメントを取得します。

**Returns:**
int - 幅のセグメント。
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

### setLength(double value) {#setLength-double-}
```
public void setLength(double value)
```


平面の長さを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

### setLengthSegments(int value) {#setLengthSegments-int-}
```
public void setLengthSegments(int value)
```


長さのセグメントを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | int | 新しい値 |

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

### setUp(Vector3 value) {#setUp-com.aspose.threed.Vector3-}
```
public void setUp(Vector3 value)
```


平面の上方向ベクトルを設定します。デフォルト値は (0, 1, 0) で、平面の生成に影響します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新しい値 |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


平面の幅を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

### setWidthSegments(int value) {#setWidthSegments-int-}
```
public void setWidthSegments(int value)
```


幅のセグメントを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | int | 新しい値 |

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

