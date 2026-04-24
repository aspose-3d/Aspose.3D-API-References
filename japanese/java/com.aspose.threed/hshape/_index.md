---
title: HShape
second_title: Aspose.3D for Java API リファレンス
description: H または I 形状の定義パラメータを提供します。
type: docs
weight: 76
url: /ja/java/com.aspose.threed/hshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Profile](../../com.aspose.threed/profile), [com.aspose.threed.ParameterizedProfile](../../com.aspose.threed/parameterizedprofile)
```
public class HShape extends ParameterizedProfile
```

The [HShape](../../com.aspose.threed/hshape) は 'H' または 'I' 形状の定義パラメータを提供します。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [HShape()](#HShape--) | [HShape](../../com.aspose.threed/hshape) のコンストラクタ |
## Methods

| Method | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | プロパティを検索します。 |
| [getBottomFlangeEdgeRadius()](#getBottomFlangeEdgeRadius--) | 底部フランジの上部エッジの半径を取得します。 |
| [getBottomFlangeFilletRadius()](#getBottomFlangeFilletRadius--) | ウェブと下フランジの間のフィレット半径を取得します。 |
| [getBottomFlangeThickness()](#getBottomFlangeThickness--) | H形状のフランジ厚さを取得します。 |
| [getBottomFlangeWidth()](#getBottomFlangeWidth--) | 幅の範囲を取得します。 |
| [getBoundingBox()](#getBoundingBox--) | 現在のエンティティのオブジェクト空間座標系におけるバウンディングボックスを取得します。 |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | レンダラーに登録されたエンティティレンダラーのキーを取得します |
| [getExcluded()](#getExcluded--) | エクスポート時にこのエンティティを除外するかどうかを取得します。 |
| [getExtent()](#getExtent--) | x と y の次元の範囲を取得します。 |
| [getName()](#getName--) | 名前を取得します。 |
| [getOverallDepth()](#getOverallDepth--) | 深さの範囲を取得します。 |
| [getParentNode()](#getParentNode--) | 最初の親ノードを取得します。最初の親ノードを設定すると、このエンティティは他の親ノードから切り離されます。 |
| [getParentNodes()](#getParentNodes--) | すべての親ノードを取得します。エンティティはジオメトリインスタンシングのために複数の親ノードにアタッチできます。 |
| [getProperties()](#getProperties--) | すべてのプロパティのコレクションを取得します。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 指定されたプロパティの値を取得します |
| [getScene()](#getScene--) | このオブジェクトが属するシーンを取得します |
| [getTopFlangeEdgeRadius()](#getTopFlangeEdgeRadius--) | 上フランジの下端の半径を取得します。 |
| [getTopFlangeFilletRadius()](#getTopFlangeFilletRadius--) | ウェブと上フランジの間のフィレット半径を取得します。 |
| [getTopFlangeThickness()](#getTopFlangeThickness--) | 上フランジの厚さを取得します。 |
| [getTopFlangeWidth()](#getTopFlangeWidth--) | 上フランジの幅を取得します。 |
| [getWebThickness()](#getWebThickness--) | H形状のウェブの厚さを取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 動的プロパティを削除します。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 名前で識別される指定されたプロパティを削除します |
| [setBottomFlangeEdgeRadius(double value)](#setBottomFlangeEdgeRadius-double-) | 下フランジの上端の半径を設定します。 |
| [setBottomFlangeFilletRadius(double value)](#setBottomFlangeFilletRadius-double-) | ウェブと下フランジの間のフィレット半径を設定します。 |
| [setBottomFlangeThickness(double value)](#setBottomFlangeThickness-double-) | H形状のフランジ厚さを設定します。 |
| [setBottomFlangeWidth(double value)](#setBottomFlangeWidth-double-) | 幅の範囲を設定します。 |
| [setExcluded(boolean value)](#setExcluded-boolean-) | エクスポート時にこのエンティティを除外するかどうかを設定します。 |
| [setName(String value)](#setName-java.lang.String-) | 名前を設定します。 |
| [setOverallDepth(double value)](#setOverallDepth-double-) | 深さの範囲を設定します。 |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | 最初の親ノードを設定します。最初の親ノードを設定すると、このエンティティは他の親ノードから切り離されます。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 指定されたプロパティの値を設定します |
| [setTopFlangeEdgeRadius(double value)](#setTopFlangeEdgeRadius-double-) | 上フランジの下端の半径を設定します。 |
| [setTopFlangeFilletRadius(double value)](#setTopFlangeFilletRadius-double-) | ウェブと上フランジの間のフィレット半径を設定します。 |
| [setTopFlangeThickness(double value)](#setTopFlangeThickness-double-) | 上フランジの厚さを設定します。 |
| [setTopFlangeWidth(double value)](#setTopFlangeWidth-double-) | 上フランジの幅を設定します。 |
| [setWebThickness(double value)](#setWebThickness-double-) | H形状のウェブの厚さを設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HShape() {#HShape--}
```
public HShape()
```


[HShape](../../com.aspose.threed/hshape) のコンストラクタ

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
### getBottomFlangeEdgeRadius() {#getBottomFlangeEdgeRadius--}
```
public double getBottomFlangeEdgeRadius()
```


底部フランジの上部エッジの半径を取得します。

**Returns:**
double - 下フランジの上端の半径。
### getBottomFlangeFilletRadius() {#getBottomFlangeFilletRadius--}
```
public double getBottomFlangeFilletRadius()
```


ウェブと下フランジの間のフィレット半径を取得します。

**Returns:**
double - ウェブと下フランジの間のフィレット半径。
### getBottomFlangeThickness() {#getBottomFlangeThickness--}
```
public double getBottomFlangeThickness()
```


H形状のフランジ厚さを取得します。

**Returns:**
double - H形状のフランジ厚さ。
### getBottomFlangeWidth() {#getBottomFlangeWidth--}
```
public double getBottomFlangeWidth()
```


幅の範囲を取得します。

**Returns:**
double - 幅の範囲。
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
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


レンダラーに登録されたエンティティレンダラーのキーを取得します

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey)
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


エクスポート時にこのエンティティを除外するかどうかを取得します。

**Returns:**
boolean - エクスポート時にこのエンティティを除外するかどうか。
### getExtent() {#getExtent--}
```
public Vector2 getExtent()
```


x と y の次元の範囲を取得します。

**Returns:**
[Vector2](../../com.aspose.threed/vector2)
### getName() {#getName--}
```
public String getName()
```


名前を取得します。

**Returns:**
java.lang.String - 名前です。
### getOverallDepth() {#getOverallDepth--}
```
public double getOverallDepth()
```


深さの範囲を取得します。

**Returns:**
double - 深さの範囲。
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
### getTopFlangeEdgeRadius() {#getTopFlangeEdgeRadius--}
```
public double getTopFlangeEdgeRadius()
```


上フランジの下端の半径を取得します。

**Returns:**
double - 上フランジの下端の半径。
### getTopFlangeFilletRadius() {#getTopFlangeFilletRadius--}
```
public double getTopFlangeFilletRadius()
```


ウェブと上フランジの間のフィレット半径を取得します。

**Returns:**
double - ウェブと上フランジ間のフィレット半径。
### getTopFlangeThickness() {#getTopFlangeThickness--}
```
public double getTopFlangeThickness()
```


上フランジの厚さを取得します。

**Returns:**
double - 上フランジの厚さ。
### getTopFlangeWidth() {#getTopFlangeWidth--}
```
public double getTopFlangeWidth()
```


上フランジの幅を取得します。

**Returns:**
double - 上フランジの幅。
### getWebThickness() {#getWebThickness--}
```
public double getWebThickness()
```


H形状のウェブの厚さを取得します。

**Returns:**
double - H形状のウェブの厚さ。
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
### setBottomFlangeEdgeRadius(double value) {#setBottomFlangeEdgeRadius-double-}
```
public void setBottomFlangeEdgeRadius(double value)
```


下フランジの上端の半径を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

### setBottomFlangeFilletRadius(double value) {#setBottomFlangeFilletRadius-double-}
```
public void setBottomFlangeFilletRadius(double value)
```


ウェブと下フランジの間のフィレット半径を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

### setBottomFlangeThickness(double value) {#setBottomFlangeThickness-double-}
```
public void setBottomFlangeThickness(double value)
```


H形状のフランジ厚さを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

### setBottomFlangeWidth(double value) {#setBottomFlangeWidth-double-}
```
public void setBottomFlangeWidth(double value)
```


幅の範囲を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

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

### setOverallDepth(double value) {#setOverallDepth-double-}
```
public void setOverallDepth(double value)
```


深さの範囲を設定します。

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

### setTopFlangeEdgeRadius(double value) {#setTopFlangeEdgeRadius-double-}
```
public void setTopFlangeEdgeRadius(double value)
```


上フランジの下端の半径を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

### setTopFlangeFilletRadius(double value) {#setTopFlangeFilletRadius-double-}
```
public void setTopFlangeFilletRadius(double value)
```


ウェブと上フランジの間のフィレット半径を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

### setTopFlangeThickness(double value) {#setTopFlangeThickness-double-}
```
public void setTopFlangeThickness(double value)
```


上フランジの厚さを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

### setTopFlangeWidth(double value) {#setTopFlangeWidth-double-}
```
public void setTopFlangeWidth(double value)
```


上フランジの幅を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

### setWebThickness(double value) {#setWebThickness-double-}
```
public void setWebThickness(double value)
```


H形状のウェブの厚さを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

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

