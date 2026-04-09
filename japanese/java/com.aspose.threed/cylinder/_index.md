---
title: Cylinder
second_title: Aspose.3D for Java API リファレンス
description: パラメータ化されたシリンダー。
type: docs
weight: 40
url: /ja/java/com.aspose.threed/cylinder/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Primitive](../../com.aspose.threed/primitive)
```
public class Cylinder extends Primitive
```

パラメータ化されたシリンダー。radiusTop または radiusBottom のいずれかがゼロの場合、円錐を表すこともできます。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [Cylinder()](#Cylinder--) | 新しい [Cylinder](../../com.aspose.threed/cylinder) クラスのインスタンスを初期化します。 |
| [Cylinder(double radius, double height)](#Cylinder-double-double-) | 新しい [Cylinder](../../com.aspose.threed/cylinder) クラスのインスタンスを初期化します。 |
| [Cylinder(double radiusTop, double radiusBottom, double height)](#Cylinder-double-double-double-) | 新しい [Cylinder](../../com.aspose.threed/cylinder) クラスのインスタンスを初期化します。 |
| [Cylinder(double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded)](#Cylinder-double-double-double-int-int-boolean-) | 新しい [Cylinder](../../com.aspose.threed/cylinder) クラスのインスタンスを初期化します。 |
| [Cylinder(String name, double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded, double thetaStart, double thetaLength)](#Cylinder-java.lang.String-double-double-double-int-int-boolean-double-double-) | 新しい [Cylinder](../../com.aspose.threed/cylinder) クラスのインスタンスを初期化します。 |
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
| [getGenerateFanCylinder()](#getGenerateFanCylinder--) | ThetaLength が 2\*PI 未満のときにファンスタイルのシリンダーを生成するかどうかを取得します。そうでない場合、モデルはカットされません。 |
| [getHeight()](#getHeight--) | シリンダーの高さを取得します。 |
| [getHeightSegments()](#getHeightSegments--) | 高さセグメントを取得します。 |
| [getName()](#getName--) | 名前を取得します。 |
| [getOffsetBottom()](#getOffsetBottom--) | 底面側の頂点変換オフセットを取得します。 |
| [getOffsetTop()](#getOffsetTop--) | 上面側の頂点変換オフセットを取得します。 |
| [getOpenEnded()](#getOpenEnded--) | この [Cylinder](../../com.aspose.threed/cylinder) が開口しているかどうかを示す値を取得します。 |
| [getParentNode()](#getParentNode--) | 最初の親ノードを取得します。最初の親ノードを設定すると、このエンティティは他の親ノードから切り離されます。 |
| [getParentNodes()](#getParentNodes--) | すべての親ノードを取得します。エンティティはジオメトリインスタンシングのために複数の親ノードにアタッチできます。 |
| [getProperties()](#getProperties--) | すべてのプロパティのコレクションを取得します。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 指定されたプロパティの値を取得します |
| [getRadialSegments()](#getRadialSegments--) | 放射状セグメントを取得します。 |
| [getRadiusBottom()](#getRadiusBottom--) | シリンダーの底キャップの半径を取得します。 |
| [getRadiusTop()](#getRadiusTop--) | シリンダーの上部キャップの半径を取得します。 |
| [getReceiveShadows()](#getReceiveShadows--) | このジオメトリが影を受け取るかどうかを取得します。 |
| [getScene()](#getScene--) | このオブジェクトが属するシーンを取得します |
| [getShearBottom()](#getShearBottom--) | 底面のせん断変換を取得します。ベクトルはラジアンで測定された (x 軸, z 軸) のせん断値を格納し、デフォルト値は (0, 0) です。 |
| [getShearTop()](#getShearTop--) | 上部のせん断変換を取得します。ベクトルはラジアンで測定された (x 軸, z 軸) のせん断値を格納し、デフォルト値は (0, 0) です。 |
| [getThetaLength()](#getThetaLength--) | theta の長さを取得します。 |
| [getThetaStart()](#getThetaStart--) | theta の開始位置を取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 動的プロパティを削除します。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 名前で識別される指定されたプロパティを削除します |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | このジオメトリが影を落とすかどうかを設定します |
| [setExcluded(boolean value)](#setExcluded-boolean-) | エクスポート時にこのエンティティを除外するかどうかを設定します。 |
| [setGenerateFanCylinder(boolean value)](#setGenerateFanCylinder-boolean-) | ThetaLength が 2\*PI 未満の場合にファンスタイルのシリンダーを生成するかどうかを設定します。そうでない場合、モデルはカットされません。 |
| [setHeight(double value)](#setHeight-double-) | シリンダーの高さを設定します。 |
| [setHeightSegments(int value)](#setHeightSegments-int-) | 高さセグメントを設定します。 |
| [setName(String value)](#setName-java.lang.String-) | 名前を設定します。 |
| [setOffsetBottom(Vector3 value)](#setOffsetBottom-com.aspose.threed.Vector3-) | 底面の頂点変換オフセットを設定します。 |
| [setOffsetTop(Vector3 value)](#setOffsetTop-com.aspose.threed.Vector3-) | 上面の頂点変換オフセットを設定します。 |
| [setOpenEnded(boolean value)](#setOpenEnded-boolean-) | この [Cylinder](../../com.aspose.threed/cylinder) が開放端かどうかを示す値を設定します。 |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | 最初の親ノードを設定します。最初の親ノードを設定すると、このエンティティは他の親ノードから切り離されます。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 指定されたプロパティの値を設定します |
| [setRadialSegments(int value)](#setRadialSegments-int-) | 放射状セグメントを設定します。 |
| [setRadiusBottom(double value)](#setRadiusBottom-double-) | シリンダーの底部キャップの半径を設定します。 |
| [setRadiusTop(double value)](#setRadiusTop-double-) | シリンダーの上部キャップの半径を設定します。 |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | このジオメトリが影を受け取るかどうかを設定します。 |
| [setShearBottom(Vector2 value)](#setShearBottom-com.aspose.threed.Vector2-) | 底面のせん断変換を設定します。ベクトルはラジアンで測定された (x 軸, z 軸) のせん断値を格納し、デフォルト値は (0, 0) です。 |
| [setShearTop(Vector2 value)](#setShearTop-com.aspose.threed.Vector2-) | 上面のせん断変換を設定します。ベクトルはラジアンで測定された (x 軸, z 軸) のせん断値を格納し、デフォルト値は (0, 0) です。 |
| [setThetaLength(double value)](#setThetaLength-double-) | theta の長さを設定します。 |
| [setThetaStart(double value)](#setThetaStart-double-) | theta の開始位置を設定します。 |
| [toMesh()](#toMesh--) | 現在のオブジェクトをメッシュに変換します |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Cylinder() {#Cylinder--}
```
public Cylinder()
```


新しい [Cylinder](../../com.aspose.threed/cylinder) クラスのインスタンスを初期化します。

### Cylinder(double radius, double height) {#Cylinder-double-double-}
```
public Cylinder(double radius, double height)
```


新しい [Cylinder](../../com.aspose.threed/cylinder) クラスのインスタンスを初期化します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 半径 | double | 上部と下部キャップの半径。 |
| 高さ | double | 高さ。 |

### Cylinder(double radiusTop, double radiusBottom, double height) {#Cylinder-double-double-double-}
```
public Cylinder(double radiusTop, double radiusBottom, double height)
```


新しい [Cylinder](../../com.aspose.threed/cylinder) クラスのインスタンスを初期化します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| radiusTop | double | 上部の半径。 |
| radiusBottom | double | 下部の半径。 |
| 高さ | double | 高さ。 |

### Cylinder(double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded) {#Cylinder-double-double-double-int-int-boolean-}
```
public Cylinder(double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded)
```


新しい [Cylinder](../../com.aspose.threed/cylinder) クラスのインスタンスを初期化します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| radiusTop | double | シリンダーの上部キャップの半径。 |
| radiusBottom | double | シリンダーの底部キャップの半径。 |
| 高さ | double | シリンダーの高さ。 |
| radialSegments | int | 上部と下部の円の放射状セグメント.. |
| heightSegments | int | 高さセグメント。 |
| openEnded | boolean | true に設定すると、シリンダーに上下のキャップがなくなります。 |

### Cylinder(String name, double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded, double thetaStart, double thetaLength) {#Cylinder-java.lang.String-double-double-double-int-int-boolean-double-double-}
```
public Cylinder(String name, double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded, double thetaStart, double thetaLength)
```


新しい [Cylinder](../../com.aspose.threed/cylinder) クラスのインスタンスを初期化します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String | このオブジェクトの名前 |
| radiusTop | double | シリンダーの上部キャップの半径。 |
| radiusBottom | double | シリンダーの底部キャップの半径。 |
| 高さ | double | シリンダーの高さ。 |
| radialSegments | int | 上部と下部の円の放射状セグメント.. |
| heightSegments | int | 高さセグメント。 |
| openEnded | boolean | true に設定すると、シリンダーに上下のキャップがなくなります。 |
| thetaStart | double | Theta の開始位置。 |
| thetaLength | double | Theta の長さ。 |

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
### getGenerateFanCylinder() {#getGenerateFanCylinder--}
```
public boolean getGenerateFanCylinder()
```


ThetaLength が 2\*PI 未満のときにファンスタイルのシリンダーを生成するかどうかを取得します。そうでない場合、モデルはカットされません。

**Returns:**
boolean - ThetaLength が 2\*PI 未満のときにファンスタイルのシリンダーを生成するかどうか。そうでない場合、モデルはカットされません。
### getHeight() {#getHeight--}
```
public double getHeight()
```


シリンダーの高さを取得します。

**Returns:**
double - シリンダーの高さ。
### getHeightSegments() {#getHeightSegments--}
```
public int getHeightSegments()
```


高さセグメントを取得します。

**Returns:**
int - 高さセグメント。
### getName() {#getName--}
```
public String getName()
```


名前を取得します。

**Returns:**
java.lang.String - 名前です。
### getOffsetBottom() {#getOffsetBottom--}
```
public Vector3 getOffsetBottom()
```


底面側の頂点変換オフセットを取得します。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the vertices transformation offset of the bottom side.
### getOffsetTop() {#getOffsetTop--}
```
public Vector3 getOffsetTop()
```


上面側の頂点変換オフセットを取得します。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the vertices transformation offset of the top side.
### getOpenEnded() {#getOpenEnded--}
```
public boolean getOpenEnded()
```


この [Cylinder](../../com.aspose.threed/cylinder) が開口部かどうかを示す値を取得します。デフォルト値は false です。

**Returns:**
boolean - この [Cylinder](../../com.aspose.threed/cylinder) が開口部かどうかを示す値。デフォルト値は false です。
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


放射状セグメントを取得します。

**Returns:**
int - 放射状セグメント数。
### getRadiusBottom() {#getRadiusBottom--}
```
public double getRadiusBottom()
```


シリンダーの底キャップの半径を取得します。

**Returns:**
double - シリンダーの底キャップの半径。
### getRadiusTop() {#getRadiusTop--}
```
public double getRadiusTop()
```


シリンダーの上部キャップの半径を取得します。

**Returns:**
double - シリンダーの上部キャップの半径。
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
### getShearBottom() {#getShearBottom--}
```
public Vector2 getShearBottom()
```


底面のせん断変換を取得します。ベクトルはラジアンで測定された (x 軸, z 軸) のせん断値を格納し、デフォルト値は (0, 0) です。

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - of the shear transform of the bottom side, vector stores the (x-axis, z-axis) shear value that measured in radian, default value is (0, 0)
### getShearTop() {#getShearTop--}
```
public Vector2 getShearTop()
```


上部のせん断変換を取得します。ベクトルはラジアンで測定された (x 軸, z 軸) のせん断値を格納し、デフォルト値は (0, 0) です。

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - of the shear transform of the top side, vector stores the (x-axis, z-axis) shear value that measured in radian, default value is (0, 0)
### getThetaLength() {#getThetaLength--}
```
public double getThetaLength()
```


theta の長さを取得します。デフォルト値は 2\\u03c0 です。

**Returns:**
double - theta の長さ。デフォルト値は 2\\u03c0 です。
### getThetaStart() {#getThetaStart--}
```
public double getThetaStart()
```


theta の開始位置を取得します。デフォルト値は 0 です。

**Returns:**
double - theta の開始位置。デフォルト値は 0 です。
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

### setGenerateFanCylinder(boolean value) {#setGenerateFanCylinder-boolean-}
```
public void setGenerateFanCylinder(boolean value)
```


ThetaLength が 2\*PI 未満の場合にファンスタイルのシリンダーを生成するかどうかを設定します。そうでない場合、モデルはカットされません。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


シリンダーの高さを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

### setHeightSegments(int value) {#setHeightSegments-int-}
```
public void setHeightSegments(int value)
```


高さセグメントを設定します。

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

### setOffsetBottom(Vector3 value) {#setOffsetBottom-com.aspose.threed.Vector3-}
```
public void setOffsetBottom(Vector3 value)
```


底面の頂点変換オフセットを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新しい値 |

### setOffsetTop(Vector3 value) {#setOffsetTop-com.aspose.threed.Vector3-}
```
public void setOffsetTop(Vector3 value)
```


上面の頂点変換オフセットを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新しい値 |

### setOpenEnded(boolean value) {#setOpenEnded-boolean-}
```
public void setOpenEnded(boolean value)
```


この [Cylinder](../../com.aspose.threed/cylinder) が開口部かどうかを示す値を設定します。デフォルト値は false です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

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


放射状セグメントを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | int | 新しい値 |

### setRadiusBottom(double value) {#setRadiusBottom-double-}
```
public void setRadiusBottom(double value)
```


シリンダーの底部キャップの半径を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

### setRadiusTop(double value) {#setRadiusTop-double-}
```
public void setRadiusTop(double value)
```


シリンダーの上部キャップの半径を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


このジオメトリが影を受け取るかどうかを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setShearBottom(Vector2 value) {#setShearBottom-com.aspose.threed.Vector2-}
```
public void setShearBottom(Vector2 value)
```


底面のせん断変換を設定します。ベクトルはラジアンで測定された (x 軸, z 軸) のせん断値を格納し、デフォルト値は (0, 0) です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | 新しい値 |

### setShearTop(Vector2 value) {#setShearTop-com.aspose.threed.Vector2-}
```
public void setShearTop(Vector2 value)
```


上面のせん断変換を設定します。ベクトルはラジアンで測定された (x 軸, z 軸) のせん断値を格納し、デフォルト値は (0, 0) です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | 新しい値 |

### setThetaLength(double value) {#setThetaLength-double-}
```
public void setThetaLength(double value)
```


theta の長さを設定します。デフォルト値は 2\\u03c0 です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

### setThetaStart(double value) {#setThetaStart-double-}
```
public void setThetaStart(double value)
```


theta の開始位置を設定します。デフォルト値は 0 です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

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

