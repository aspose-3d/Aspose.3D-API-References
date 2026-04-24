---
title: RectangularTorus
second_title: Aspose.3D for Java API リファレンス
description: パラメータ化された矩形トーラスです。
type: docs
weight: 146
url: /ja/java/com.aspose.threed/rectangulartorus/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Primitive](../../com.aspose.threed/primitive)
```
public class RectangularTorus extends Primitive
```

パラメータ化された矩形トーラスです。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [RectangularTorus()](#RectangularTorus--) | [RectangularTorus](../../com.aspose.threed/rectangulartorus) のコンストラクタ |
| [RectangularTorus(String name)](#RectangularTorus-java.lang.String-) | [RectangularTorus](../../com.aspose.threed/rectangulartorus) のコンストラクタ |
## Methods

| Method | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | プロパティを検索します。 |
| [getAngleStart()](#getAngleStart--) | 弧の開始角度（ラジアンで測定）。 |
| [getArc()](#getArc--) | 弧の総角度（ラジアンで測定）。 |
| [getBoundingBox()](#getBoundingBox--) | 現在のエンティティのオブジェクト空間座標系におけるバウンディングボックスを取得します。 |
| [getCastShadows()](#getCastShadows--) | このジオメトリが影を落とすかどうかを取得します |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | レンダラーに登録されたエンティティレンダラーのキーを取得します |
| [getExcluded()](#getExcluded--) | エクスポート時にこのエンティティを除外するかどうかを取得します。 |
| [getHeight()](#getHeight--) | 矩形トーラスの高さ。 |
| [getInnerRadius()](#getInnerRadius--) | 矩形トーラスの内側半径（デフォルト値は 17）。 |
| [getName()](#getName--) | 名前を取得します。 |
| [getOuterRadius()](#getOuterRadius--) | 矩形トーラスの外側半径（デフォルト値は 20）。 |
| [getParentNode()](#getParentNode--) | 最初の親ノードを取得します。最初の親ノードを設定すると、このエンティティは他の親ノードから切り離されます。 |
| [getParentNodes()](#getParentNodes--) | すべての親ノードを取得します。エンティティはジオメトリインスタンシングのために複数の親ノードにアタッチできます。 |
| [getProperties()](#getProperties--) | すべてのプロパティのコレクションを取得します。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 指定されたプロパティの値を取得します |
| [getRadialSegments()](#getRadialSegments--) | 放射状セグメント（デフォルト値は 10）。 |
| [getReceiveShadows()](#getReceiveShadows--) | このジオメトリが影を受け取るかどうかを取得します。 |
| [getScene()](#getScene--) | このオブジェクトが属するシーンを取得します |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 動的プロパティを削除します。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 名前で識別される指定されたプロパティを削除します |
| [setAngleStart(double value)](#setAngleStart-double-) | 弧の開始角度（ラジアンで測定）。 |
| [setArc(double value)](#setArc-double-) | 弧の総角度（ラジアンで測定）。 |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | このジオメトリが影を落とすかどうかを設定します |
| [setExcluded(boolean value)](#setExcluded-boolean-) | エクスポート時にこのエンティティを除外するかどうかを設定します。 |
| [setHeight(double value)](#setHeight-double-) | 矩形トーラスの高さ。 |
| [setInnerRadius(double value)](#setInnerRadius-double-) | 矩形トーラスの内側半径（デフォルト値は 17）。 |
| [setName(String value)](#setName-java.lang.String-) | 名前を設定します。 |
| [setOuterRadius(double value)](#setOuterRadius-double-) | 矩形トーラスの外側半径（デフォルト値は 20）。 |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | 最初の親ノードを設定します。最初の親ノードを設定すると、このエンティティは他の親ノードから切り離されます。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 指定されたプロパティの値を設定します |
| [setRadialSegments(int value)](#setRadialSegments-int-) | 放射状セグメント（デフォルト値は 10）。 |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | このジオメトリが影を受け取るかどうかを設定します。 |
| [toMesh()](#toMesh--) | このプリミティブを [Mesh](../../com.aspose.threed/mesh) に変換します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RectangularTorus() {#RectangularTorus--}
```
public RectangularTorus()
```


[RectangularTorus](../../com.aspose.threed/rectangulartorus) のコンストラクタ

### RectangularTorus(String name) {#RectangularTorus-java.lang.String-}
```
public RectangularTorus(String name)
```


[RectangularTorus](../../com.aspose.threed/rectangulartorus) のコンストラクタ

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String |  |

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
### getAngleStart() {#getAngleStart--}
```
public double getAngleStart()
```


弧の開始角度（ラジアンで測定）。デフォルト値は 0。

**Returns:**
double - 弧の開始角度（ラジアンで測定）。デフォルト値は 0 です。
### getArc() {#getArc--}
```
public double getArc()
```


弧の総角度（ラジアンで測定）。デフォルト値は PI です。

**Returns:**
double - 弧の総角度（ラジアンで測定）。デフォルト値は PI です。
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


矩形トーラスの高さ。デフォルト値は 20 です。

**Returns:**
double - 矩形トーラスの高さ。デフォルト値は 20 です。
### getInnerRadius() {#getInnerRadius--}
```
public double getInnerRadius()
```


矩形トーラスの内側半径（デフォルト値は 17）。

**Returns:**
double - 矩形トーラスの内半径。デフォルト値は 17 です。
### getName() {#getName--}
```
public String getName()
```


名前を取得します。

**Returns:**
java.lang.String - 名前です。
### getOuterRadius() {#getOuterRadius--}
```
public double getOuterRadius()
```


矩形トーラスの外側半径（デフォルト値は 20）。

**Returns:**
double - 矩形トーラスの外半径。デフォルト値は 20 です。
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
### getRadialSegments() {#getRadialSegments--}
```
public int getRadialSegments()
```


放射状セグメント（デフォルト値は 10）。

**Returns:**
int - 放射状セグメント数。デフォルト値は 10 です。
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
### setAngleStart(double value) {#setAngleStart-double-}
```
public void setAngleStart(double value)
```


弧の開始角度（ラジアンで測定）。デフォルト値は 0。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

### setArc(double value) {#setArc-double-}
```
public void setArc(double value)
```


弧の総角度（ラジアンで測定）。デフォルト値は PI です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

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


矩形トーラスの高さ。デフォルト値は 20 です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

### setInnerRadius(double value) {#setInnerRadius-double-}
```
public void setInnerRadius(double value)
```


矩形トーラスの内側半径（デフォルト値は 17）。

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

### setOuterRadius(double value) {#setOuterRadius-double-}
```
public void setOuterRadius(double value)
```


矩形トーラスの外側半径（デフォルト値は 20）。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

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

### setRadialSegments(int value) {#setRadialSegments-int-}
```
public void setRadialSegments(int value)
```


放射状セグメント（デフォルト値は 10）。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | int | 新しい値 |

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


このジオメトリが影を受け取るかどうかを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


このプリミティブを [Mesh](../../com.aspose.threed/mesh) に変換します。

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

