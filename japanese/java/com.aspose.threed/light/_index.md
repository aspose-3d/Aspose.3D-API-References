---
title: Light
second_title: Aspose.3D for Java API リファレンス
description: 光がシーンを照らします。
type: docs
weight: 94
url: /ja/java/com.aspose.threed/light/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Frustum](../../com.aspose.threed/frustum)
```
public class Light extends Frustum
```

光がシーンを照らします。

光の総減衰を計算する式は次のとおりです:  A = ConstantAttenuation + (Dist \* LinearAttenuation) + ((Dist^2) \* QuadraticAttenuation)
## Constructors

| Constructor | 説明 |
| --- | --- |
| [Light()](#Light--) | 新しい [Light](../../com.aspose.threed/light) クラスのインスタンスを初期化します。 |
| [Light(String name)](#Light-java.lang.String-) | 新しい [Light](../../com.aspose.threed/light) クラスのインスタンスを初期化します。 |
| [Light(String name, LightType type)](#Light-java.lang.String-com.aspose.threed.LightType-) | 新しい [Light](../../com.aspose.threed/light) クラスのインスタンスを初期化します。 |
## Methods

| Method | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | プロパティを検索します。 |
| [getAspect()](#getAspect--) | フラスタムのアスペクト比を取得します |
| [getBoundingBox()](#getBoundingBox--) | 現在のエンティティのオブジェクト空間座標系におけるバウンディングボックスを取得します。 |
| [getCastLight()](#getCastLight--) | 現在の Light インスタンスが他のオブジェクトを照らすことができるかどうかを取得します。 |
| [getCastShadows()](#getCastShadows--) | 光が他のオブジェクトに影を落とすことができるかどうかを取得します。 |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | 光の色を取得します |
| [getConstantAttenuation()](#getConstantAttenuation--) | 光の総減衰を計算するための定数減衰を取得します |
| [getDirection()](#getDirection--) | カメラが向いている方向を取得します。 |
| [getEntityRendererKey()](#getEntityRendererKey--) | レンダラーに登録されたエンティティレンダラーのキーを取得します |
| [getExcluded()](#getExcluded--) | エクスポート時にこのエンティティを除外するかどうかを取得します。 |
| [getFalloff()](#getFalloff--) | 減衰コーン角度（度単位）を取得します。 |
| [getFarPlane()](#getFarPlane--) | フラスタムの遠平面距離を取得します。 |
| [getHotSpot()](#getHotSpot--) | ホットスポットコーン角度（度）を取得します。 |
| [getIntensity()](#getIntensity--) | 光の強度を取得します。デフォルト値は 100 です。 |
| [getLightType()](#getLightType--) | 光のタイプを取得します。 |
| [getLinearAttenuation()](#getLinearAttenuation--) | 光の総減衰を計算するための線形減衰を取得します。 |
| [getLookAt()](#getLookAt--) | カメラが注目している位置を取得します。 |
| [getName()](#getName--) | 名前を取得します。 |
| [getNearPlane()](#getNearPlane--) | 視錐台の近接平面距離を取得します。 |
| [getOrthoHeight()](#getOrthoHeight--) | 正射投影時の視錐台の高さを取得します。 |
| [getParentNode()](#getParentNode--) | 最初の親ノードを取得します。最初の親ノードを設定すると、このエンティティは他の親ノードから切り離されます。 |
| [getParentNodes()](#getParentNodes--) | すべての親ノードを取得します。エンティティはジオメトリインスタンシングのために複数の親ノードにアタッチできます。 |
| [getProperties()](#getProperties--) | すべてのプロパティのコレクションを取得します。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 指定されたプロパティの値を取得します |
| [getQuadraticAttenuation()](#getQuadraticAttenuation--) | 光の総減衰を計算するための二次減衰を取得します。 |
| [getRotationMode()](#getRotationMode--) | 視錐台の向きモードを取得します。このプロパティは [getTarget](../../com.aspose.threed/frustum\#getTarget) が null の場合にのみ機能します。 |
| [getScene()](#getScene--) | このオブジェクトが属するシーンを取得します |
| [getShadowColor()](#getShadowColor--) | 影の色を取得します。 |
| [getTarget()](#getTarget--) | カメラが見ている対象を取得します。 |
| [getUp()](#getUp--) | カメラの上方向を取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 動的プロパティを削除します。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 名前で識別される指定されたプロパティを削除します |
| [setAspect(double value)](#setAspect-double-) | 視錐台のアスペクト比を設定します。 |
| [setCastLight(boolean value)](#setCastLight-boolean-) | 現在の光インスタンスが他のオブジェクトを照らすかどうかを設定します。 |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | 光が他のオブジェクトに影を落とすかどうかを設定します。 |
| [setColor(Vector3 value)](#setColor-com.aspose.threed.Vector3-) | 光の色を設定します。 |
| [setConstantAttenuation(double value)](#setConstantAttenuation-double-) | 光の総減衰を計算するための一定減衰を設定します。 |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | カメラが向いている方向を設定します。 |
| [setExcluded(boolean value)](#setExcluded-boolean-) | エクスポート時にこのエンティティを除外するかどうかを設定します。 |
| [setFalloff(double value)](#setFalloff-double-) | 減衰コーン角度（度）を設定します。 |
| [setFarPlane(double value)](#setFarPlane-double-) | 視錐台の遠平面距離を設定します。 |
| [setHotSpot(double value)](#setHotSpot-double-) | ホットスポットコーン角度（度）を設定します。 |
| [setIntensity(double value)](#setIntensity-double-) | 光の強度を設定します。デフォルト値は 100 です。 |
| [setLightType(LightType value)](#setLightType-com.aspose.threed.LightType-) | 光のタイプを設定します。 |
| [setLinearAttenuation(double value)](#setLinearAttenuation-double-) | 光の総減衰を計算するための線形減衰を設定します。 |
| [setLookAt(Vector3 value)](#setLookAt-com.aspose.threed.Vector3-) | カメラが注目している位置を設定します。 |
| [setName(String value)](#setName-java.lang.String-) | 名前を設定します。 |
| [setNearPlane(double value)](#setNearPlane-double-) | フラスタムの近面距離を設定します。 |
| [setOrthoHeight(double value)](#setOrthoHeight-double-) | フラスタムが正射投影の場合の高さを設定します。 |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | 最初の親ノードを設定します。最初の親ノードを設定すると、このエンティティは他の親ノードから切り離されます。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 指定されたプロパティの値を設定します |
| [setQuadraticAttenuation(double value)](#setQuadraticAttenuation-double-) | 光の総減衰を計算するための二次減衰を設定します。 |
| [setRotationMode(RotationMode value)](#setRotationMode-com.aspose.threed.RotationMode-) | フラスタムの向きモードを設定します。このプロパティは [getTarget](../../com.aspose.threed/frustum\#getTarget) が null の場合にのみ機能します。 |
| [setShadowColor(Vector3 value)](#setShadowColor-com.aspose.threed.Vector3-) | 影の色を設定します。 |
| [setTarget(Node value)](#setTarget-com.aspose.threed.Node-) | カメラが注視するターゲットを設定します。 |
| [setUp(Vector3 value)](#setUp-com.aspose.threed.Vector3-) | カメラの上方向を設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Light() {#Light--}
```
public Light()
```


新しい [Light](../../com.aspose.threed/light) クラスのインスタンスを初期化します。

### Light(String name) {#Light-java.lang.String-}
```
public Light(String name)
```


新しい [Light](../../com.aspose.threed/light) クラスのインスタンスを初期化します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String | 名前 |

### Light(String name, LightType type) {#Light-java.lang.String-com.aspose.threed.LightType-}
```
public Light(String name, LightType type)
```


新しい [Light](../../com.aspose.threed/light) クラスのインスタンスを初期化します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String | 名前 |
| type | [LightType](../../com.aspose.threed/lighttype) | 新しい光のタイプ |

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
### getAspect() {#getAspect--}
```
public double getAspect()
```


フラスタムのアスペクト比を取得します

**Returns:**
double - フラスタムのアスペクト比
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
### getCastLight() {#getCastLight--}
```
public boolean getCastLight()
```


現在の Light インスタンスが他のオブジェクトを照らすことができるかどうかを取得します。

**Returns:**
boolean - 現在の光インスタンスが他のオブジェクトを照らすことができるかどうか。
### getCastShadows() {#getCastShadows--}
```
public boolean getCastShadows()
```


光が他のオブジェクトに影を落とすことができるかどうかを取得します。

**Returns:**
boolean - 光が他のオブジェクトに影を落とすことができるかどうか。
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


光の色を取得します

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the light's color
### getConstantAttenuation() {#getConstantAttenuation--}
```
public double getConstantAttenuation()
```


光の総減衰を計算するための定数減衰を取得します

**Returns:**
double - 光の総減衰を計算するための定数減衰
### getDirection() {#getDirection--}
```
public Vector3 getDirection()
```


カメラが注視する方向を取得します。このプロパティの変更は [getLookAt](../../com.aspose.threed/frustum\#getLookAt) と [getTarget](../../com.aspose.threed/frustum\#getTarget) にも影響します。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the direction that the camera is looking at. Changes on this property will also affects the [getLookAt](../../com.aspose.threed/frustum\#getLookAt) and [getTarget](../../com.aspose.threed/frustum\#getTarget).
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
### getFalloff() {#getFalloff--}
```
public double getFalloff()
```


減衰コーン角度（度単位）を取得します。

**Returns:**
double - 減衰コーン角度（度単位）。
### getFarPlane() {#getFarPlane--}
```
public double getFarPlane()
```


フラスタムの遠平面距離を取得します。

**Returns:**
double - フラスタムの遠面距離。
### getHotSpot() {#getHotSpot--}
```
public double getHotSpot()
```


ホットスポットコーン角度（度）を取得します。

**Returns:**
double - ホットスポットコーン角度（度単位）。
### getIntensity() {#getIntensity--}
```
public double getIntensity()
```


光の強度を取得します。デフォルト値は 100 です。

**Returns:**
double - 光の強度、デフォルト値は 100 です。
### getLightType() {#getLightType--}
```
public LightType getLightType()
```


光のタイプを取得します。

**Returns:**
[LightType](../../com.aspose.threed/lighttype) - the light's type
### getLinearAttenuation() {#getLinearAttenuation--}
```
public double getLinearAttenuation()
```


光の総減衰を計算するための線形減衰を取得します。

**Returns:**
double - 光の総減衰を計算するための線形減衰
### getLookAt() {#getLookAt--}
```
public Vector3 getLookAt()
```


カメラが注目している位置を取得します。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the the interested position that the camera is looking at.
### getName() {#getName--}
```
public String getName()
```


名前を取得します。

**Returns:**
java.lang.String - 名前です。
### getNearPlane() {#getNearPlane--}
```
public double getNearPlane()
```


視錐台の近接平面距離を取得します。

**Returns:**
double - フラスタムの近面距離。
### getOrthoHeight() {#getOrthoHeight--}
```
public double getOrthoHeight()
```


正射投影時の視錐台の高さを取得します。

**Returns:**
double - フラスタムが正射投影の場合の高さ。
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
### getQuadraticAttenuation() {#getQuadraticAttenuation--}
```
public double getQuadraticAttenuation()
```


光の総減衰を計算するための二次減衰を取得します。

**Returns:**
double - 光の総減衰を計算するための二次減衰
### getRotationMode() {#getRotationMode--}
```
public RotationMode getRotationMode()
```


フラスタムの向きモードを取得します。このプロパティは [getTarget](../../com.aspose.threed/frustum\#getTarget) が null の場合にのみ機能します。値が [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET) の場合、方向は常にプロパティ [getLookAt](../../com.aspose.threed/frustum\#getLookAt) によって計算されます。それ以外の場合、[getLookAt](../../com.aspose.threed/frustum\#getLookAt) は常に [getDirection](../../com.aspose.threed/frustum\#getDirection) によって計算されます。

**Returns:**
[RotationMode](../../com.aspose.threed/rotationmode) - the frustum's orientation mode This property only works when the [getTarget](../../com.aspose.threed/frustum\#getTarget) is null. If the value is [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET), the direction is always calculated by the property [getLookAt](../../com.aspose.threed/frustum\#getLookAt) Otherwise the [getLookAt](../../com.aspose.threed/frustum\#getLookAt) is always calculated by the [getDirection](../../com.aspose.threed/frustum\#getDirection)
### getScene() {#getScene--}
```
public Scene getScene()
```


このオブジェクトが属するシーンを取得します

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getShadowColor() {#getShadowColor--}
```
public Vector3 getShadowColor()
```


影の色を取得します。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the shadow's color.
### getTarget() {#getTarget--}
```
public Node getTarget()
```


カメラが注視するターゲットを取得します。ユーザーがこのプロパティをサポートしている場合、[getLookAt](../../com.aspose.threed/frustum\#getLookAt) プロパティよりも先に設定すべきです。

**Returns:**
[Node](../../com.aspose.threed/node) - the target that the camera is looking at. If the user supports this property, it should be prior to [getLookAt](../../com.aspose.threed/frustum\#getLookAt) property.
### getUp() {#getUp--}
```
public Vector3 getUp()
```


カメラの上方向を取得します。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the up direction of the camera
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
### setAspect(double value) {#setAspect-double-}
```
public void setAspect(double value)
```


視錐台のアスペクト比を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

### setCastLight(boolean value) {#setCastLight-boolean-}
```
public void setCastLight(boolean value)
```


現在の光インスタンスが他のオブジェクトを照らすかどうかを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setCastShadows(boolean value) {#setCastShadows-boolean-}
```
public void setCastShadows(boolean value)
```


光が他のオブジェクトに影を落とすかどうかを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setColor(Vector3 value) {#setColor-com.aspose.threed.Vector3-}
```
public void setColor(Vector3 value)
```


光の色を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新しい値 |

### setConstantAttenuation(double value) {#setConstantAttenuation-double-}
```
public void setConstantAttenuation(double value)
```


光の総減衰を計算するための一定減衰を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

### setDirection(Vector3 value) {#setDirection-com.aspose.threed.Vector3-}
```
public void setDirection(Vector3 value)
```


カメラが注視する方向を設定します。このプロパティの変更は [getLookAt](../../com.aspose.threed/frustum\#getLookAt) と [getTarget](../../com.aspose.threed/frustum\#getTarget) にも影響します。

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

### setFalloff(double value) {#setFalloff-double-}
```
public void setFalloff(double value)
```


減衰コーン角度（度）を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

### setFarPlane(double value) {#setFarPlane-double-}
```
public void setFarPlane(double value)
```


視錐台の遠平面距離を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

### setHotSpot(double value) {#setHotSpot-double-}
```
public void setHotSpot(double value)
```


ホットスポットコーン角度（度）を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

### setIntensity(double value) {#setIntensity-double-}
```
public void setIntensity(double value)
```


光の強度を設定します。デフォルト値は 100 です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

### setLightType(LightType value) {#setLightType-com.aspose.threed.LightType-}
```
public void setLightType(LightType value)
```


光のタイプを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [LightType](../../com.aspose.threed/lighttype) | 新しい値 |

### setLinearAttenuation(double value) {#setLinearAttenuation-double-}
```
public void setLinearAttenuation(double value)
```


光の総減衰を計算するための線形減衰を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

### setLookAt(Vector3 value) {#setLookAt-com.aspose.threed.Vector3-}
```
public void setLookAt(Vector3 value)
```


カメラが注目している位置を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新しい値 |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


名前を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

### setNearPlane(double value) {#setNearPlane-double-}
```
public void setNearPlane(double value)
```


フラスタムの近面距離を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

### setOrthoHeight(double value) {#setOrthoHeight-double-}
```
public void setOrthoHeight(double value)
```


フラスタムが正射投影の場合の高さを設定します。

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

### setQuadraticAttenuation(double value) {#setQuadraticAttenuation-double-}
```
public void setQuadraticAttenuation(double value)
```


光の総減衰を計算するための二次減衰を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

### setRotationMode(RotationMode value) {#setRotationMode-com.aspose.threed.RotationMode-}
```
public void setRotationMode(RotationMode value)
```


フラスタムの向きモードを設定します。このプロパティは [getTarget](../../com.aspose.threed/frustum\#getTarget) が null の場合にのみ機能します。値が [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET) の場合、方向は常にプロパティ [getLookAt](../../com.aspose.threed/frustum\#getLookAt) によって計算されます。それ以外の場合、[getLookAt](../../com.aspose.threed/frustum\#getLookAt) は常に [getDirection](../../com.aspose.threed/frustum\#getDirection) によって計算されます。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [RotationMode](../../com.aspose.threed/rotationmode) | 新しい値 |

### setShadowColor(Vector3 value) {#setShadowColor-com.aspose.threed.Vector3-}
```
public void setShadowColor(Vector3 value)
```


影の色を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新しい値 |

### setTarget(Node value) {#setTarget-com.aspose.threed.Node-}
```
public void setTarget(Node value)
```


カメラが注視している対象を設定します。ユーザーがこのプロパティをサポートしている場合、[getLookAt](../../com.aspose.threed/frustum\#getLookAt) プロパティより前に設定すべきです。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | 新しい値 |

### setUp(Vector3 value) {#setUp-com.aspose.threed.Vector3-}
```
public void setUp(Vector3 value)
```


カメラの上方向を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新しい値 |

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

