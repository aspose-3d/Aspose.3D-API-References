---
title: "Light"
second_title: "Aspose.3D for Java API 参考"
description: "光照亮场景。"
type: docs
weight: 94
url: /zh/java/com.aspose.threed/light/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Frustum](../../com.aspose.threed/frustum)
```
public class Light extends Frustum
```

光照亮场景。

计算光的总衰减的公式为： A = ConstantAttenuation + (Dist \* LinearAttenuation) + ((Dist^2) \* QuadraticAttenuation)
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Light()](#Light--) | 初始化 [Light](../../com.aspose.threed/light) 类的新实例。 |
| [Light(String name)](#Light-java.lang.String-) | 初始化 [Light](../../com.aspose.threed/light) 类的新实例。 |
| [Light(String name, LightType type)](#Light-java.lang.String-com.aspose.threed.LightType-) | 初始化 [Light](../../com.aspose.threed/light) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 查找属性。 |
| [getAspect()](#getAspect--) | 获取视锥体的宽高比。 |
| [getBoundingBox()](#getBoundingBox--) | 获取当前实体在其对象空间坐标系中的边界框。 |
| [getCastLight()](#getCastLight--) | 获取当前光实例是否可以照亮其他对象。 |
| [getCastShadows()](#getCastShadows--) | 获取光是否可以在其他对象上投射阴影。 |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | 获取光的颜色。 |
| [getConstantAttenuation()](#getConstantAttenuation--) | 获取用于计算光的总衰减的常数衰减。 |
| [getDirection()](#getDirection--) | 获取相机所看的方向。 |
| [getEntityRendererKey()](#getEntityRendererKey--) | 获取在渲染器中注册的实体渲染器的键 |
| [getExcluded()](#getExcluded--) | 获取在导出期间是否排除此实体。 |
| [getFalloff()](#getFalloff--) | 获取衰减锥角（单位：度）。 |
| [getFarPlane()](#getFarPlane--) | 获取视锥体的远平面距离。 |
| [getHotSpot()](#getHotSpot--) | 获取热点锥角（单位为度）。 |
| [getIntensity()](#getIntensity--) | 获取光的强度，默认值为 100 |
| [getLightType()](#getLightType--) | 获取光的类型 |
| [getLinearAttenuation()](#getLinearAttenuation--) | 获取线性衰减，以计算光的总衰减 |
| [getLookAt()](#getLookAt--) | 获取相机所关注的位置。 |
| [getName()](#getName--) | 获取名称。 |
| [getNearPlane()](#getNearPlane--) | 获取视锥体的近裁剪面距离。 |
| [getOrthoHeight()](#getOrthoHeight--) | 获取视锥体在正交投影时的高度。 |
| [getParentNode()](#getParentNode--) | 获取第一个父节点，如果设置第一个父节点，则此实体将从其他父节点分离。 |
| [getParentNodes()](#getParentNodes--) | 获取所有父节点，实体可以附加到多个父节点以进行几何实例化 |
| [getProperties()](#getProperties--) | 获取所有属性的集合。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 获取指定属性的值 |
| [getQuadraticAttenuation()](#getQuadraticAttenuation--) | 获取二次衰减，以计算光的总衰减 |
| [getRotationMode()](#getRotationMode--) | 获取视锥体的方向模式。此属性仅在 [getTarget](../../com.aspose.threed/frustum\#getTarget) 为 null 时有效。 |
| [getScene()](#getScene--) | 获取此对象所属的场景 |
| [getShadowColor()](#getShadowColor--) | 获取阴影的颜色。 |
| [getTarget()](#getTarget--) | 获取相机所看的目标。 |
| [getUp()](#getUp--) | 获取相机的上方向 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 移除动态属性。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 移除通过名称标识的指定属性 |
| [setAspect(double value)](#setAspect-double-) | 设置视锥体的宽高比 |
| [setCastLight(boolean value)](#setCastLight-boolean-) | 设置当前光实例是否可以照亮其他对象。 |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | 设置光是否可以在其他对象上投射阴影。 |
| [setColor(Vector3 value)](#setColor-com.aspose.threed.Vector3-) | 设置光的颜色 |
| [setConstantAttenuation(double value)](#setConstantAttenuation-double-) | 设置常数衰减，以计算光的总衰减。 |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | 设置相机所看的方向。 |
| [setExcluded(boolean value)](#setExcluded-boolean-) | 设置在导出期间是否排除此实体。 |
| [setFalloff(double value)](#setFalloff-double-) | 设置衰减锥角（单位为度）。 |
| [setFarPlane(double value)](#setFarPlane-double-) | 设置视锥体的远裁剪面距离。 |
| [setHotSpot(double value)](#setHotSpot-double-) | 设置热点锥角（单位为度）。 |
| [setIntensity(double value)](#setIntensity-double-) | 设置光的强度，默认值为 100 |
| [setLightType(LightType value)](#setLightType-com.aspose.threed.LightType-) | 设置光的类型 |
| [setLinearAttenuation(double value)](#setLinearAttenuation-double-) | 设置线性衰减，以计算光的总衰减 |
| [setLookAt(Vector3 value)](#setLookAt-com.aspose.threed.Vector3-) | 设置相机所关注的位置。 |
| [setName(String value)](#setName-java.lang.String-) | 设置名称。 |
| [setNearPlane(double value)](#setNearPlane-double-) | 设置视锥体的近裁剪面距离。 |
| [setOrthoHeight(double value)](#setOrthoHeight-double-) | 设置视锥体在正交投影时的高度。 |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | 设置第一个父节点，如果设置第一个父节点，则此实体将从其他父节点分离。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 设置指定属性的值 |
| [setQuadraticAttenuation(double value)](#setQuadraticAttenuation-double-) | 设置二次衰减以计算光的总衰减 |
| [setRotationMode(RotationMode value)](#setRotationMode-com.aspose.threed.RotationMode-) | 设置视锥体的方向模式。此属性仅在 [getTarget](../../com.aspose.threed/frustum\#getTarget) 为 null 时有效。 |
| [setShadowColor(Vector3 value)](#setShadowColor-com.aspose.threed.Vector3-) | 设置阴影的颜色。 |
| [setTarget(Node value)](#setTarget-com.aspose.threed.Node-) | 设置相机所看的目标。 |
| [setUp(Vector3 value)](#setUp-com.aspose.threed.Vector3-) | 设置相机的上方向 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Light() {#Light--}
```
public Light()
```


初始化 [Light](../../com.aspose.threed/light) 类的新实例。

### Light(String name) {#Light-java.lang.String-}
```
public Light(String name)
```


初始化 [Light](../../com.aspose.threed/light) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 名称 |

### Light(String name, LightType type) {#Light-java.lang.String-com.aspose.threed.LightType-}
```
public Light(String name, LightType type)
```


初始化 [Light](../../com.aspose.threed/light) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 名称 |
| type | [LightType](../../com.aspose.threed/lighttype) | 新光源的类型 |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本机属性（通过其名称标识）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| propertyName | java.lang.String | 属性名称。 |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getAspect() {#getAspect--}
```
public double getAspect()
```


获取视锥体的宽高比。

**Returns:**
double - 视锥体的宽高比
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


获取当前实体在其对象空间坐标系中的边界框。

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


获取当前光实例是否可以照亮其他对象。

**Returns:**
boolean - 当前光实例是否可以照亮其他对象。
### getCastShadows() {#getCastShadows--}
```
public boolean getCastShadows()
```


获取光是否可以在其他对象上投射阴影。

**Returns:**
boolean - 光是否可以在其他对象上投射阴影。
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


获取光的颜色。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the light's color
### getConstantAttenuation() {#getConstantAttenuation--}
```
public double getConstantAttenuation()
```


获取用于计算光的总衰减的常数衰减。

**Returns:**
double - 用于计算光总衰减的常数衰减
### getDirection() {#getDirection--}
```
public Vector3 getDirection()
```


获取相机所看的方向。对此属性的更改也会影响 [getLookAt](../../com.aspose.threed/frustum\#getLookAt) 和 [getTarget](../../com.aspose.threed/frustum\#getTarget)。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the direction that the camera is looking at. Changes on this property will also affects the [getLookAt](../../com.aspose.threed/frustum\#getLookAt) and [getTarget](../../com.aspose.threed/frustum\#getTarget).
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


获取在渲染器中注册的实体渲染器的键

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey) - the key of the entity renderer registered in the renderer
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


获取在导出期间是否排除此实体。

**Returns:**
boolean - 是否在导出期间排除此实体。
### getFalloff() {#getFalloff--}
```
public double getFalloff()
```


获取衰减锥角（单位：度）。

**Returns:**
double - 衰减锥角（以度为单位）。
### getFarPlane() {#getFarPlane--}
```
public double getFarPlane()
```


获取视锥体的远平面距离。

**Returns:**
double - 视锥体的远裁剪面距离。
### getHotSpot() {#getHotSpot--}
```
public double getHotSpot()
```


获取热点锥角（单位为度）。

**Returns:**
double - 热点锥角（以度为单位）。
### getIntensity() {#getIntensity--}
```
public double getIntensity()
```


获取光的强度，默认值为 100

**Returns:**
double - 光的强度，默认值为 100
### getLightType() {#getLightType--}
```
public LightType getLightType()
```


获取光的类型

**Returns:**
[LightType](../../com.aspose.threed/lighttype) - the light's type
### getLinearAttenuation() {#getLinearAttenuation--}
```
public double getLinearAttenuation()
```


获取线性衰减，以计算光的总衰减

**Returns:**
double - 用于计算光总衰减的线性衰减
### getLookAt() {#getLookAt--}
```
public Vector3 getLookAt()
```


获取相机所关注的位置。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the the interested position that the camera is looking at.
### getName() {#getName--}
```
public String getName()
```


获取名称。

**Returns:**
java.lang.String - 名称。
### getNearPlane() {#getNearPlane--}
```
public double getNearPlane()
```


获取视锥体的近裁剪面距离。

**Returns:**
double - 视锥体的近裁剪面距离。
### getOrthoHeight() {#getOrthoHeight--}
```
public double getOrthoHeight()
```


获取视锥体在正交投影时的高度。

**Returns:**
double - 视锥体在正交投影时的高度。
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


获取第一个父节点，如果设置第一个父节点，则此实体将从其他父节点分离。

**Returns:**
[Node](../../com.aspose.threed/node) - the first parent node, if set the first parent node, this entity will be detached from other parent nodes.
### getParentNodes() {#getParentNodes--}
```
public ArrayList<Node> getParentNodes()
```


获取所有父节点，实体可以附加到多个父节点以进行几何实例化

**Returns:**
java.util.ArrayList<com.aspose.threed.Node> - 所有父节点，实体可以附加到多个父节点以实现几何实例化
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


获取所有属性的集合。

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


获取指定属性的值

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 属性 | java.lang.String | 属性名称 |

**Returns:**
java.lang.Object - 找到的属性的值
### getQuadraticAttenuation() {#getQuadraticAttenuation--}
```
public double getQuadraticAttenuation()
```


获取二次衰减，以计算光的总衰减

**Returns:**
double - 用于计算光总衰减的二次衰减
### getRotationMode() {#getRotationMode--}
```
public RotationMode getRotationMode()
```


获取视锥体的方向模式。此属性仅在 [getTarget](../../com.aspose.threed/frustum\#getTarget) 为 null 时有效。如果值为 [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET)，方向始终由属性 [getLookAt](../../com.aspose.threed/frustum\#getLookAt) 计算；否则 [getLookAt](../../com.aspose.threed/frustum\#getLookAt) 始终由 [getDirection](../../com.aspose.threed/frustum\#getDirection) 计算。

**Returns:**
[RotationMode](../../com.aspose.threed/rotationmode) - the frustum's orientation mode This property only works when the [getTarget](../../com.aspose.threed/frustum\#getTarget) is null. If the value is [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET), the direction is always calculated by the property [getLookAt](../../com.aspose.threed/frustum\#getLookAt) Otherwise the [getLookAt](../../com.aspose.threed/frustum\#getLookAt) is always calculated by the [getDirection](../../com.aspose.threed/frustum\#getDirection)
### getScene() {#getScene--}
```
public Scene getScene()
```


获取此对象所属的场景

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getShadowColor() {#getShadowColor--}
```
public Vector3 getShadowColor()
```


获取阴影的颜色。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the shadow's color.
### getTarget() {#getTarget--}
```
public Node getTarget()
```


获取相机所看的目标。如果用户支持此属性，它应在 [getLookAt](../../com.aspose.threed/frustum\#getLookAt) 属性之前。

**Returns:**
[Node](../../com.aspose.threed/node) - the target that the camera is looking at. If the user supports this property, it should be prior to [getLookAt](../../com.aspose.threed/frustum\#getLookAt) property.
### getUp() {#getUp--}
```
public Vector3 getUp()
```


获取相机的上方向

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


移除动态属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | 要删除哪个属性 |

**Returns:**
boolean - 如果属性成功删除则为 true
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


移除通过名称标识的指定属性

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 属性 | java.lang.String | 要删除哪个属性 |

**Returns:**
boolean - 如果属性成功删除则为 true
### setAspect(double value) {#setAspect-double-}
```
public void setAspect(double value)
```


设置视锥体的宽高比

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setCastLight(boolean value) {#setCastLight-boolean-}
```
public void setCastLight(boolean value)
```


设置当前光实例是否可以照亮其他对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

### setCastShadows(boolean value) {#setCastShadows-boolean-}
```
public void setCastShadows(boolean value)
```


设置光是否可以在其他对象上投射阴影。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

### setColor(Vector3 value) {#setColor-com.aspose.threed.Vector3-}
```
public void setColor(Vector3 value)
```


设置光的颜色

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新值 |

### setConstantAttenuation(double value) {#setConstantAttenuation-double-}
```
public void setConstantAttenuation(double value)
```


设置常数衰减，以计算光的总衰减。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setDirection(Vector3 value) {#setDirection-com.aspose.threed.Vector3-}
```
public void setDirection(Vector3 value)
```


设置相机所看的方向。对此属性的更改也会影响 [getLookAt](../../com.aspose.threed/frustum\#getLookAt) 和 [getTarget](../../com.aspose.threed/frustum\#getTarget)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新值 |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


设置在导出期间是否排除此实体。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

### setFalloff(double value) {#setFalloff-double-}
```
public void setFalloff(double value)
```


设置衰减锥角（单位为度）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setFarPlane(double value) {#setFarPlane-double-}
```
public void setFarPlane(double value)
```


设置视锥体的远裁剪面距离。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setHotSpot(double value) {#setHotSpot-double-}
```
public void setHotSpot(double value)
```


设置热点锥角（单位为度）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setIntensity(double value) {#setIntensity-double-}
```
public void setIntensity(double value)
```


设置光的强度，默认值为 100

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setLightType(LightType value) {#setLightType-com.aspose.threed.LightType-}
```
public void setLightType(LightType value)
```


设置光的类型

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [LightType](../../com.aspose.threed/lighttype) | 新值 |

### setLinearAttenuation(double value) {#setLinearAttenuation-double-}
```
public void setLinearAttenuation(double value)
```


设置线性衰减，以计算光的总衰减

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setLookAt(Vector3 value) {#setLookAt-com.aspose.threed.Vector3-}
```
public void setLookAt(Vector3 value)
```


设置相机所关注的位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新值 |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


设置名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

### setNearPlane(double value) {#setNearPlane-double-}
```
public void setNearPlane(double value)
```


设置视锥体的近裁剪面距离。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setOrthoHeight(double value) {#setOrthoHeight-double-}
```
public void setOrthoHeight(double value)
```


设置视锥体在正交投影时的高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


设置第一个父节点，如果设置第一个父节点，则此实体将从其他父节点分离。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | 新值 |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


设置指定属性的值

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 属性 | java.lang.String | 属性名称 |
| 值 | java.lang.Object | 属性的值 |

### setQuadraticAttenuation(double value) {#setQuadraticAttenuation-double-}
```
public void setQuadraticAttenuation(double value)
```


设置二次衰减以计算光的总衰减

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setRotationMode(RotationMode value) {#setRotationMode-com.aspose.threed.RotationMode-}
```
public void setRotationMode(RotationMode value)
```


设置视锥体的方向模式。此属性仅在 [getTarget](../../com.aspose.threed/frustum\#getTarget) 为 null 时有效。如果值为 [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET)，方向始终由属性 [getLookAt](../../com.aspose.threed/frustum\#getLookAt) 计算；否则 [getLookAt](../../com.aspose.threed/frustum\#getLookAt) 始终由 [getDirection](../../com.aspose.threed/frustum\#getDirection) 计算。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [RotationMode](../../com.aspose.threed/rotationmode) | 新值 |

### setShadowColor(Vector3 value) {#setShadowColor-com.aspose.threed.Vector3-}
```
public void setShadowColor(Vector3 value)
```


设置阴影的颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新值 |

### setTarget(Node value) {#setTarget-com.aspose.threed.Node-}
```
public void setTarget(Node value)
```


设置相机所看的目标。如果用户支持此属性，则应在 [getLookAt](../../com.aspose.threed/frustum\#getLookAt) 属性之前设置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | 新值 |

### setUp(Vector3 value) {#setUp-com.aspose.threed.Vector3-}
```
public void setUp(Vector3 value)
```


设置相机的上方向

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新值 |

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

