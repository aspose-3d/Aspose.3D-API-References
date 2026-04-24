---
title: NurbsCurve
second_title: Aspose.3D for Java API リファレンス
description: NURBS curve は NURBSNon-uniform rational basis spline によって表現される曲線です。 NURBS curve は一連の重み付けされた制御点と ... によって定義されます。 制御点の w 成分は制御点の重みとして使用されます。
type: docs
weight: 112
url: /ja/java/com.aspose.threed/nurbscurve/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Curve](../../com.aspose.threed/curve)
```
public class NurbsCurve extends Curve
```

[NURBS curve][] is a curve represented by NURBS(Non-uniform rational basis spline), A NURBS curve is defined by its [getOrder](../../com.aspose.threed/nurbscurve\#getOrder), a set of weighted [Geometry.getControlPoints](../../com.aspose.threed/geometry\#getControlPoints) and a [getKnotVectors](../../com.aspose.threed/nurbscurve\#getKnotVectors) The w component in control point is used as control point's weight, whatever it is a [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL) or [CurveDimension.THREE\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#THREE-DIMENSIONAL)


[NURBS curve]: https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline
## Constructors

| Constructor | 説明 |
| --- | --- |
| [NurbsCurve()](#NurbsCurve--) | 新しい [NurbsCurve](../../com.aspose.threed/nurbscurve) クラスのインスタンスを初期化します。 |
| [NurbsCurve(String name)](#NurbsCurve-java.lang.String-) | 新しい [NurbsCurve](../../com.aspose.threed/nurbscurve) クラスのインスタンスを初期化します。 |
## Methods

| Method | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [evaluate()](#evaluate--) | NURBS 曲線を評価する |
| [evaluate(int steps)](#evaluate-int-) | NURBS 曲線を評価する |
| [evaluateAt(double u)](#evaluateAt-double-) | 指定された位置で曲線の点を評価する |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | プロパティを検索します。 |
| [getBoundingBox()](#getBoundingBox--) | 現在のエンティティのオブジェクト空間座標系におけるバウンディングボックスを取得します。 |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | 線の色を取得します。デフォルト値は白 (1, 1, 1) です |
| [getControlPoints()](#getControlPoints--) | すべての制御点を取得します。 |
| [getCurveType()](#getCurveType--) | 曲線のタイプを取得します。 |
| [getDegree()](#getDegree--) | NURBS 曲線の次数を取得します。次数は Order - 1 と定義されます |
| [getDimension()](#getDimension--) | 曲線の次元を取得します。 |
| [getEntityRendererKey()](#getEntityRendererKey--) | レンダラーに登録されたエンティティレンダラーのキーを取得します |
| [getExcluded()](#getExcluded--) | エクスポート時にこのエンティティを除外するかどうかを取得します。 |
| [getKnotVectors()](#getKnotVectors--) | ノットベクトルを取得します。これはパラメータ値のシーケンスで、制御点が NURBS 曲線にどのように影響するかを決定します |
| [getMultiplicity()](#getMultiplicity--) | 多重度を取得します。 |
| [getName()](#getName--) | 名前を取得します。 |
| [getOrder()](#getOrder--) | NURBS 曲線のオーダーを取得します。これは曲線上の任意の点に影響を与える近傍の制御点の数を定義します |
| [getParentNode()](#getParentNode--) | 最初の親ノードを取得します。最初の親ノードを設定すると、このエンティティは他の親ノードから切り離されます。 |
| [getParentNodes()](#getParentNodes--) | すべての親ノードを取得します。エンティティはジオメトリインスタンシングのために複数の親ノードにアタッチできます。 |
| [getProperties()](#getProperties--) | すべてのプロパティのコレクションを取得します。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 指定されたプロパティの値を取得します |
| [getRational()](#getRational--) | 有理かどうかを取得します。この値はこの [NurbsCurve](../../com.aspose.threed/nurbscurve) が有理スプラインか非有理スプラインかを示します。 |
| [getScene()](#getScene--) | このオブジェクトが属するシーンを取得します |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 動的プロパティを削除します。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 名前で識別される指定されたプロパティを削除します |
| [setColor(Vector3 value)](#setColor-com.aspose.threed.Vector3-) | 線の色を設定します。デフォルト値は白 (1, 1, 1) です |
| [setCurveType(NurbsType value)](#setCurveType-com.aspose.threed.NurbsType-) | 曲線のタイプを設定します。 |
| [setDegree(int value)](#setDegree-int-) | NURBS 曲線の次数を設定します。次数は Order - 1 と定義されます |
| [setDimension(CurveDimension value)](#setDimension-com.aspose.threed.CurveDimension-) | 曲線の次元を設定します。 |
| [setExcluded(boolean value)](#setExcluded-boolean-) | エクスポート時にこのエンティティを除外するかどうかを設定します。 |
| [setName(String value)](#setName-java.lang.String-) | 名前を設定します。 |
| [setOrder(int value)](#setOrder-int-) | NURBS 曲線のオーダーを設定します。これは曲線上の任意の点に影響を与える近傍の制御点の数を定義します |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | 最初の親ノードを設定します。最初の親ノードを設定すると、このエンティティは他の親ノードから切り離されます。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 指定されたプロパティの値を設定します |
| [setRational(boolean value)](#setRational-boolean-) | 有理かどうかを設定します。この値はこの [NurbsCurve](../../com.aspose.threed/nurbscurve) が有理スプラインか非有理スプラインかを示します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NurbsCurve() {#NurbsCurve--}
```
public NurbsCurve()
```


新しい [NurbsCurve](../../com.aspose.threed/nurbscurve) クラスのインスタンスを初期化します。

### NurbsCurve(String name) {#NurbsCurve-java.lang.String-}
```
public NurbsCurve(String name)
```


新しい [NurbsCurve](../../com.aspose.threed/nurbscurve) クラスのインスタンスを初期化します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String | 名前 |

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
### evaluate() {#evaluate--}
```
public Vector4[] evaluate()
```


NURBS 曲線を評価する

**Returns:**
com.aspose.threed.Vector4[] - 曲線内のポイント
### evaluate(int steps) {#evaluate-int-}
```
public Vector4[] evaluate(int steps)
```


NURBS 曲線を評価する

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| ステップ | int | 隣接する2つのノット間の評価頻度です。デフォルト値は20です |

**Returns:**
com.aspose.threed.Vector4[] - 曲線内のポイント
### evaluateAt(double u) {#evaluateAt-double-}
```
public Vector4 evaluateAt(double u)
```


指定された位置で曲線の点を評価する

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| u | double | 曲線上の位置で、0から1の間です |

**Returns:**
[Vector4](../../com.aspose.threed/vector4)
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
### getColor() {#getColor--}
```
public Vector3 getColor()
```


線の色を取得します。デフォルト値は白 (1, 1, 1) です

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the color of the line, default value is white(1, 1, 1)
### getControlPoints() {#getControlPoints--}
```
public List<Vector4> getControlPoints()
```


すべての制御点を取得します。

**Returns:**
java.util.List<com.aspose.threed.Vector4> - すべての制御点
### getCurveType() {#getCurveType--}
```
public NurbsType getCurveType()
```


曲線のタイプを取得します。

**Returns:**
[NurbsType](../../com.aspose.threed/nurbstype) - the type of the curve.
### getDegree() {#getDegree--}
```
public int getDegree()
```


NURBS 曲線の次数を取得します。次数は Order - 1 と定義されます

**Returns:**
int - NURBS 曲線の次数、次数は Order - 1 と定義されます
### getDimension() {#getDimension--}
```
public CurveDimension getDimension()
```


曲線の次元を取得します。

**Returns:**
[CurveDimension](../../com.aspose.threed/curvedimension) - the curve's dimension. **Remarks:** For a [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL) curve, the z component in control point is unused.
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
### getKnotVectors() {#getKnotVectors--}
```
public List<Double> getKnotVectors()
```


ノットベクトルを取得します。これはパラメータ値のシーケンスで、制御点が NURBS 曲線にどのように影響するかを決定します

**Returns:**
java.util.List<java.lang.Double> - ノットベクトルです。これはパラメータ値のシーケンスで、制御点が NURBS 曲線にどのように影響するかを決定します
### getMultiplicity() {#getMultiplicity--}
```
public List<Integer> getMultiplicity()
```


多重度を取得します。

**Returns:**
java.util.List<java.lang.Integer> - 多重度。
### getName() {#getName--}
```
public String getName()
```


名前を取得します。

**Returns:**
java.lang.String - 名前です。
### getOrder() {#getOrder--}
```
public int getOrder()
```


NURBS 曲線のオーダーを取得します。これは曲線上の任意の点に影響を与える近傍の制御点の数を定義します

**Returns:**
int - NURBS 曲線の次数で、曲線上の任意の点に影響を与える近傍の制御点の数を定義します。
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
### getRational() {#getRational--}
```
public boolean getRational()
```


有理かどうかを取得します。この値は、この [NurbsCurve](../../com.aspose.threed/nurbscurve) が有理スプラインか非有理スプラインかを示します。非有理 B スプラインは有理 B スプラインの特別なケースです。

**Returns:**
boolean - 有理かどうか。この値は、この [NurbsCurve](../../com.aspose.threed/nurbscurve) が有理スプラインか非有理スプラインかを示します。非有理 B スプラインは有理 B スプラインの特別なケースです。
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
### setColor(Vector3 value) {#setColor-com.aspose.threed.Vector3-}
```
public void setColor(Vector3 value)
```


線の色を設定します。デフォルト値は白 (1, 1, 1) です

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新しい値 |

### setCurveType(NurbsType value) {#setCurveType-com.aspose.threed.NurbsType-}
```
public void setCurveType(NurbsType value)
```


曲線のタイプを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [NurbsType](../../com.aspose.threed/nurbstype) | 新しい値 |

### setDegree(int value) {#setDegree-int-}
```
public void setDegree(int value)
```


NURBS 曲線の次数を設定します。次数は Order - 1 と定義されます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | int | 新しい値 |

### setDimension(CurveDimension value) {#setDimension-com.aspose.threed.CurveDimension-}
```
public void setDimension(CurveDimension value)
```


曲線の次元を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [CurveDimension](../../com.aspose.threed/curvedimension) | 新しい値 **Remarks:** [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL) 曲線の場合、制御点の z 成分は使用されません。 |

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

### setOrder(int value) {#setOrder-int-}
```
public void setOrder(int value)
```


NURBS 曲線のオーダーを設定します。これは曲線上の任意の点に影響を与える近傍の制御点の数を定義します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | int | 新しい値 |

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

### setRational(boolean value) {#setRational-boolean-}
```
public void setRational(boolean value)
```


有理かどうかを設定します。この値は、この [NurbsCurve](../../com.aspose.threed/nurbscurve) が有理スプラインか非有理スプラインかを示します。非有理 B スプラインは有理 B スプラインの特別なケースです。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

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

