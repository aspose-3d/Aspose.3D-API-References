---
title: "Camera"
second_title: "Aspose.3D for Java API 参考"
description: "相机描述了观看场景的观察者的视点。"
type: docs
weight: 28
url: /zh/java/com.aspose.threed/camera/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Frustum](../../com.aspose.threed/frustum)

**All Implemented Interfaces:**
[com.aspose.threed.IOrientable](../../com.aspose.threed/iorientable)
```
public class Camera extends Frustum implements IOrientable
```

相机描述了观看场景的观察者的视点。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Camera()](#Camera--) | 初始化 [Camera](../../com.aspose.threed/camera) 类的新实例。 |
| [Camera(ProjectionType projectionType)](#Camera-com.aspose.threed.ProjectionType-) | 初始化 [Camera](../../com.aspose.threed/camera) 类的新实例。 |
| [Camera(String name)](#Camera-java.lang.String-) | 初始化 [Camera](../../com.aspose.threed/camera) 类的新实例。 |
| [Camera(String name, ProjectionType projectionType)](#Camera-java.lang.String-com.aspose.threed.ProjectionType-) | 初始化 [Camera](../../com.aspose.threed/camera) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 查找属性。 |
| [getApertureMode()](#getApertureMode--) | 获取相机的光圈模式 |
| [getAspect()](#getAspect--) | 获取视锥体的宽高比。 |
| [getAspectRatio()](#getAspectRatio--) | 获取视图平面的宽高比。 |
| [getBoundingBox()](#getBoundingBox--) | 获取当前实体在其对象空间坐标系中的边界框。 |
| [getClass()](#getClass--) |  |
| [getDirection()](#getDirection--) | 获取相机所看的方向。 |
| [getEntityRendererKey()](#getEntityRendererKey--) | 获取在渲染器中注册的实体渲染器的键 |
| [getExcluded()](#getExcluded--) | 获取在导出期间是否排除此实体。 |
| [getFarPlane()](#getFarPlane--) | 获取视锥体的远平面距离。 |
| [getFieldOfView()](#getFieldOfView--) | 获取相机的视场角（以度为单位），此属性仅在 ApertureMode 为 [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) 或 [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL) 时使用 |
| [getFieldOfViewX()](#getFieldOfViewX--) | 获取相机的水平视场角（以度为单位），此属性仅在 ApertureMode 为 [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) 时使用 |
| [getFieldOfViewY()](#getFieldOfViewY--) | 获取相机的垂直视场角（以度为单位），此属性仅在 ApertureMode 为 [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) 时使用 |
| [getHeight()](#getHeight--) | 获取视图平面的高度（以英寸为单位） |
| [getLookAt()](#getLookAt--) | 获取相机所关注的位置。 |
| [getMagnification()](#getMagnification--) | 获取正交相机使用的放大倍率 |
| [getName()](#getName--) | 获取名称。 |
| [getNearPlane()](#getNearPlane--) | 获取视锥体的近裁剪面距离。 |
| [getOrthoHeight()](#getOrthoHeight--) | 获取视锥体在正交投影时的高度。 |
| [getParentNode()](#getParentNode--) | 获取第一个父节点，如果设置第一个父节点，则此实体将从其他父节点分离。 |
| [getParentNodes()](#getParentNodes--) | 获取所有父节点，实体可以附加到多个父节点以进行几何实例化 |
| [getProjectionType()](#getProjectionType--) | 获取相机的投影类型。 |
| [getProperties()](#getProperties--) | 获取所有属性的集合。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 获取指定属性的值 |
| [getRotationMode()](#getRotationMode--) | 获取视锥体的方向模式。此属性仅在 [getTarget](../../com.aspose.threed/frustum\#getTarget) 为 null 时有效。 |
| [getScene()](#getScene--) | 获取此对象所属的场景 |
| [getTarget()](#getTarget--) | 获取相机所看的目标。 |
| [getUp()](#getUp--) | 获取相机的上方向 |
| [getWidth()](#getWidth--) | 获取视图平面的宽度（以英寸为单位） |
| [hashCode()](#hashCode--) |  |
| [moveForward(double distance)](#moveForward-double-) | 向前移动相机，使其朝向方向或目标。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 移除动态属性。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 移除通过名称标识的指定属性 |
| [setApertureMode(ApertureMode value)](#setApertureMode-com.aspose.threed.ApertureMode-) | 设置相机的光圈模式 |
| [setAspect(double value)](#setAspect-double-) | 设置视锥体的宽高比 |
| [setAspectRatio(double value)](#setAspectRatio-double-) | 设置视图平面的宽高比。 |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | 设置相机所看的方向。 |
| [setExcluded(boolean value)](#setExcluded-boolean-) | 设置在导出期间是否排除此实体。 |
| [setFarPlane(double value)](#setFarPlane-double-) | 设置视锥体的远裁剪面距离。 |
| [setFieldOfView(double value)](#setFieldOfView-double-) | 设置相机的视场角（以度为单位），此属性仅在 ApertureMode 为 [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) 或 [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL) 时使用 |
| [setFieldOfViewX(double value)](#setFieldOfViewX-double-) | 设置相机的水平视场角（以度为单位），此属性仅在 ApertureMode 为 [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) 时使用 |
| [setFieldOfViewY(double value)](#setFieldOfViewY-double-) | 设置相机的垂直视场角（以度为单位），此属性仅在 ApertureMode 为 [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) 时使用 |
| [setHeight(double value)](#setHeight-double-) | 设置视图平面的高度（以英寸为单位） |
| [setLookAt(Vector3 value)](#setLookAt-com.aspose.threed.Vector3-) | 设置相机所关注的位置。 |
| [setMagnification(Vector2 value)](#setMagnification-com.aspose.threed.Vector2-) | 设置正交相机使用的放大倍率 |
| [setName(String value)](#setName-java.lang.String-) | 设置名称。 |
| [setNearPlane(double value)](#setNearPlane-double-) | 设置视锥体的近裁剪面距离。 |
| [setOrthoHeight(double value)](#setOrthoHeight-double-) | 设置视锥体在正交投影时的高度。 |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | 设置第一个父节点，如果设置第一个父节点，则此实体将从其他父节点分离。 |
| [setProjectionType(ProjectionType value)](#setProjectionType-com.aspose.threed.ProjectionType-) | 设置相机的投影类型。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 设置指定属性的值 |
| [setRotationMode(RotationMode value)](#setRotationMode-com.aspose.threed.RotationMode-) | 设置视锥体的方向模式。此属性仅在 [getTarget](../../com.aspose.threed/frustum\#getTarget) 为 null 时有效。 |
| [setTarget(Node value)](#setTarget-com.aspose.threed.Node-) | 设置相机所看的目标。 |
| [setUp(Vector3 value)](#setUp-com.aspose.threed.Vector3-) | 设置相机的上方向 |
| [setWidth(double value)](#setWidth-double-) | 设置视图平面的宽度（以英寸为单位） |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Camera() {#Camera--}
```
public Camera()
```


初始化 [Camera](../../com.aspose.threed/camera) 类的新实例。

### Camera(ProjectionType projectionType) {#Camera-com.aspose.threed.ProjectionType-}
```
public Camera(ProjectionType projectionType)
```


初始化 [Camera](../../com.aspose.threed/camera) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| projectionType | [ProjectionType](../../com.aspose.threed/projectiontype) | 投影类型。 |

### Camera(String name) {#Camera-java.lang.String-}
```
public Camera(String name)
```


初始化 [Camera](../../com.aspose.threed/camera) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 名称。 |

### Camera(String name, ProjectionType projectionType) {#Camera-java.lang.String-com.aspose.threed.ProjectionType-}
```
public Camera(String name, ProjectionType projectionType)
```


初始化 [Camera](../../com.aspose.threed/camera) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 名称。 |
| projectionType | [ProjectionType](../../com.aspose.threed/projectiontype) | 投影类型。 |

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
### getApertureMode() {#getApertureMode--}
```
public ApertureMode getApertureMode()
```


获取相机的光圈模式

**Returns:**
[ApertureMode](../../com.aspose.threed/aperturemode) - the camera's aperture mode
### getAspect() {#getAspect--}
```
public double getAspect()
```


获取视锥体的宽高比。

**Returns:**
double - 视锥体的宽高比
### getAspectRatio() {#getAspectRatio--}
```
public double getAspectRatio()
```


获取视图平面的宽高比。

**Returns:**
double - 视图平面的宽高比。
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
### getFarPlane() {#getFarPlane--}
```
public double getFarPlane()
```


获取视锥体的远平面距离。

**Returns:**
double - 视锥体的远裁剪面距离。
### getFieldOfView() {#getFieldOfView--}
```
public double getFieldOfView()
```


获取相机的视场角（以度为单位），此属性仅在 ApertureMode 为 [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) 或 [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL) 时使用

**Returns:**
double - 相机的视场角（以度为单位），此属性仅在 ApertureMode 为 [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) 或 [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL) 时使用
### getFieldOfViewX() {#getFieldOfViewX--}
```
public double getFieldOfViewX()
```


获取相机的水平视场角（以度为单位），此属性仅在 ApertureMode 为 [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) 时使用

**Returns:**
double - 相机的水平视场角（以度为单位），此属性仅在 ApertureMode 为 [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) 时使用
### getFieldOfViewY() {#getFieldOfViewY--}
```
public double getFieldOfViewY()
```


获取相机的垂直视场角（以度为单位），此属性仅在 ApertureMode 为 [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) 时使用

**Returns:**
double - 相机的垂直视场角（以度为单位），此属性仅在 ApertureMode 为 [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) 时使用
### getHeight() {#getHeight--}
```
public double getHeight()
```


获取视图平面的高度（以英寸为单位）

**Returns:**
double - 视图平面的高度（以英寸为单位）
### getLookAt() {#getLookAt--}
```
public Vector3 getLookAt()
```


获取相机所关注的位置。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the the interested position that the camera is looking at.
### getMagnification() {#getMagnification--}
```
public Vector2 getMagnification()
```


获取正交相机使用的放大倍率

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the magnification used in orthographic camera
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
### getProjectionType() {#getProjectionType--}
```
public ProjectionType getProjectionType()
```


获取相机的投影类型。默认使用透视投影。

**Returns:**
[ProjectionType](../../com.aspose.threed/projectiontype) - the camera's projection type. By default the perspective projection is used.
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
### getWidth() {#getWidth--}
```
public double getWidth()
```


获取视图平面的宽度（以英寸为单位）

**Returns:**
double - 以英寸为单位测量的视平面宽度
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### moveForward(double distance) {#moveForward-double-}
```
public void moveForward(double distance)
```


向前移动相机，使其朝向方向或目标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 距离 | double | 向前移动的时长 |

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
### setApertureMode(ApertureMode value) {#setApertureMode-com.aspose.threed.ApertureMode-}
```
public void setApertureMode(ApertureMode value)
```


设置相机的光圈模式

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ApertureMode](../../com.aspose.threed/aperturemode) | 新值 |

### setAspect(double value) {#setAspect-double-}
```
public void setAspect(double value)
```


设置视锥体的宽高比

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setAspectRatio(double value) {#setAspectRatio-double-}
```
public void setAspectRatio(double value)
```


设置视图平面的宽高比。

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

### setFarPlane(double value) {#setFarPlane-double-}
```
public void setFarPlane(double value)
```


设置视锥体的远裁剪面距离。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setFieldOfView(double value) {#setFieldOfView-double-}
```
public void setFieldOfView(double value)
```


设置相机的视场角（以度为单位），此属性仅在 ApertureMode 为 [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) 或 [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL) 时使用

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setFieldOfViewX(double value) {#setFieldOfViewX-double-}
```
public void setFieldOfViewX(double value)
```


设置相机的水平视场角（以度为单位），此属性仅在 ApertureMode 为 [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) 时使用

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setFieldOfViewY(double value) {#setFieldOfViewY-double-}
```
public void setFieldOfViewY(double value)
```


设置相机的垂直视场角（以度为单位），此属性仅在 ApertureMode 为 [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) 时使用

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


设置视图平面的高度（以英寸为单位）

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

### setMagnification(Vector2 value) {#setMagnification-com.aspose.threed.Vector2-}
```
public void setMagnification(Vector2 value)
```


设置正交相机使用的放大倍率

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | 新值 |

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

### setProjectionType(ProjectionType value) {#setProjectionType-com.aspose.threed.ProjectionType-}
```
public void setProjectionType(ProjectionType value)
```


设置相机的投影类型。默认使用透视投影。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ProjectionType](../../com.aspose.threed/projectiontype) | 新值 |

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

### setRotationMode(RotationMode value) {#setRotationMode-com.aspose.threed.RotationMode-}
```
public void setRotationMode(RotationMode value)
```


设置视锥体的方向模式。此属性仅在 [getTarget](../../com.aspose.threed/frustum\#getTarget) 为 null 时有效。如果值为 [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET)，方向始终由属性 [getLookAt](../../com.aspose.threed/frustum\#getLookAt) 计算；否则 [getLookAt](../../com.aspose.threed/frustum\#getLookAt) 始终由 [getDirection](../../com.aspose.threed/frustum\#getDirection) 计算。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [RotationMode](../../com.aspose.threed/rotationmode) | 新值 |

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

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


设置视图平面的宽度（以英寸为单位）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

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

