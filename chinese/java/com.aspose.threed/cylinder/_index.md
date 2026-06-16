---
title: "圆柱体"
second_title: "Aspose.3D for Java API 参考"
description: "参数化圆柱体。"
type: docs
weight: 40
url: /zh/java/com.aspose.threed/cylinder/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Primitive](../../com.aspose.threed/primitive)
```
public class Cylinder extends Primitive
```

参数化圆柱体。当 radiusTop/radiusBottom 中的一个为零时，它也可用于表示圆锥体。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Cylinder()](#Cylinder--) | 初始化 [Cylinder](../../com.aspose.threed/cylinder) 类的新实例。 |
| [Cylinder(double radius, double height)](#Cylinder-double-double-) | 初始化 [Cylinder](../../com.aspose.threed/cylinder) 类的新实例。 |
| [Cylinder(double radiusTop, double radiusBottom, double height)](#Cylinder-double-double-double-) | 初始化 [Cylinder](../../com.aspose.threed/cylinder) 类的新实例。 |
| [Cylinder(double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded)](#Cylinder-double-double-double-int-int-boolean-) | 初始化 [Cylinder](../../com.aspose.threed/cylinder) 类的新实例。 |
| [Cylinder(String name, double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded, double thetaStart, double thetaLength)](#Cylinder-java.lang.String-double-double-double-int-int-boolean-double-double-) | 初始化 [Cylinder](../../com.aspose.threed/cylinder) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 查找属性。 |
| [getBoundingBox()](#getBoundingBox--) | 获取当前实体在其对象空间坐标系中的边界框。 |
| [getCastShadows()](#getCastShadows--) | 获取此几何体是否可以投射阴影 |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | 获取在渲染器中注册的实体渲染器的键 |
| [getExcluded()](#getExcluded--) | 获取在导出期间是否排除此实体。 |
| [getGenerateFanCylinder()](#getGenerateFanCylinder--) | 获取当 ThetaLength 小于 2\*PI 时是否生成扇形圆柱体，否则模型将不会被裁剪。 |
| [getHeight()](#getHeight--) | 获取圆柱体的高度。 |
| [getHeightSegments()](#getHeightSegments--) | 获取高度段。 |
| [getName()](#getName--) | 获取名称。 |
| [getOffsetBottom()](#getOffsetBottom--) | 获取底部侧的顶点变换偏移。 |
| [getOffsetTop()](#getOffsetTop--) | 获取顶部侧的顶点变换偏移。 |
| [getOpenEnded()](#getOpenEnded--) | 获取一个值，指示此 [Cylinder](../../com.aspose.threed/cylinder) 是否为开放式。 |
| [getParentNode()](#getParentNode--) | 获取第一个父节点，如果设置第一个父节点，则此实体将从其他父节点分离。 |
| [getParentNodes()](#getParentNodes--) | 获取所有父节点，实体可以附加到多个父节点以进行几何实例化 |
| [getProperties()](#getProperties--) | 获取所有属性的集合。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 获取指定属性的值 |
| [getRadialSegments()](#getRadialSegments--) | 获取径向分段。 |
| [getRadiusBottom()](#getRadiusBottom--) | 获取圆柱体底部盖的半径。 |
| [getRadiusTop()](#getRadiusTop--) | 获取圆柱体顶部盖的半径。 |
| [getReceiveShadows()](#getReceiveShadows--) | 获取此几何体是否可以接收阴影。 |
| [getScene()](#getScene--) | 获取此对象所属的场景 |
| [getShearBottom()](#getShearBottom--) | 获取底部侧面的剪切变换，向量存储以弧度测量的 (x 轴, z 轴) 剪切值，默认值为 (0, 0)。 |
| [getShearTop()](#getShearTop--) | 获取顶部侧面的剪切变换，向量存储以弧度测量的 (x 轴, z 轴) 剪切值，默认值为 (0, 0)。 |
| [getThetaLength()](#getThetaLength--) | 获取 theta 的长度。 |
| [getThetaStart()](#getThetaStart--) | 获取 theta 起始值。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 移除动态属性。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 移除通过名称标识的指定属性 |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | 设置此几何体是否可以投射阴影 |
| [setExcluded(boolean value)](#setExcluded-boolean-) | 设置在导出期间是否排除此实体。 |
| [setGenerateFanCylinder(boolean value)](#setGenerateFanCylinder-boolean-) | 设置当 ThetaLength 小于 2\*PI 时是否生成扇形圆柱，否则模型将不会被裁剪。 |
| [setHeight(double value)](#setHeight-double-) | 设置圆柱体的高度。 |
| [setHeightSegments(int value)](#setHeightSegments-int-) | 设置高度段。 |
| [setName(String value)](#setName-java.lang.String-) | 设置名称。 |
| [setOffsetBottom(Vector3 value)](#setOffsetBottom-com.aspose.threed.Vector3-) | 设置底部侧面的顶点变换偏移。 |
| [setOffsetTop(Vector3 value)](#setOffsetTop-com.aspose.threed.Vector3-) | 设置顶部侧面的顶点变换偏移。 |
| [setOpenEnded(boolean value)](#setOpenEnded-boolean-) | 设置一个值，指示此 [Cylinder](../../com.aspose.threed/cylinder) 是否为开放式。 |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | 设置第一个父节点，如果设置第一个父节点，则此实体将从其他父节点分离。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 设置指定属性的值 |
| [setRadialSegments(int value)](#setRadialSegments-int-) | 设置径向段数。 |
| [setRadiusBottom(double value)](#setRadiusBottom-double-) | 设置圆柱体底部盖的半径。 |
| [setRadiusTop(double value)](#setRadiusTop-double-) | 设置圆柱体顶部盖的半径。 |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | 设置此几何体是否可以接收阴影。 |
| [setShearBottom(Vector2 value)](#setShearBottom-com.aspose.threed.Vector2-) | 设置底部侧面的剪切变换，向量存储以弧度测量的 (x 轴, z 轴) 剪切值，默认值为 (0, 0)。 |
| [setShearTop(Vector2 value)](#setShearTop-com.aspose.threed.Vector2-) | 设置顶部侧面的剪切变换，向量存储以弧度测量的 (x 轴, z 轴) 剪切值，默认值为 (0, 0)。 |
| [setThetaLength(double value)](#setThetaLength-double-) | 设置 theta 的长度。 |
| [setThetaStart(double value)](#setThetaStart-double-) | 设置 theta 起始。 |
| [toMesh()](#toMesh--) | 将当前对象转换为网格 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Cylinder() {#Cylinder--}
```
public Cylinder()
```


初始化 [Cylinder](../../com.aspose.threed/cylinder) 类的新实例。

### Cylinder(double radius, double height) {#Cylinder-double-double-}
```
public Cylinder(double radius, double height)
```


初始化 [Cylinder](../../com.aspose.threed/cylinder) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| radius | double | 顶部和底部盖的半径。 |
| 高度 | double | 高度。 |

### Cylinder(double radiusTop, double radiusBottom, double height) {#Cylinder-double-double-double-}
```
public Cylinder(double radiusTop, double radiusBottom, double height)
```


初始化 [Cylinder](../../com.aspose.threed/cylinder) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| radiusTop | double | 顶部半径。 |
| radiusBottom | double | 底部半径。 |
| 高度 | double | 高度。 |

### Cylinder(double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded) {#Cylinder-double-double-double-int-int-boolean-}
```
public Cylinder(double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded)
```


初始化 [Cylinder](../../com.aspose.threed/cylinder) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| radiusTop | double | 圆柱体顶部盖的半径。 |
| radiusBottom | double | 圆柱体底部盖的半径。 |
| 高度 | double | 圆柱体的高度。 |
| radialSegments | int | 顶部和底部圆的径向段数。 |
| heightSegments | int | 高度段。 |
| openEnded | 布尔 | 如果设置为 true，圆柱将没有底部/顶部盖子.. |

### Cylinder(String name, double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded, double thetaStart, double thetaLength) {#Cylinder-java.lang.String-double-double-double-int-int-boolean-double-double-}
```
public Cylinder(String name, double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded, double thetaStart, double thetaLength)
```


初始化 [Cylinder](../../com.aspose.threed/cylinder) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 此对象的名称 |
| radiusTop | double | 圆柱体顶部盖的半径。 |
| radiusBottom | double | 圆柱体底部盖的半径。 |
| 高度 | double | 圆柱体的高度。 |
| radialSegments | int | 顶部和底部圆的径向段数。 |
| heightSegments | int | 高度段。 |
| openEnded | 布尔 | 如果设置为 true，圆柱将没有底部/顶部盖子.. |
| thetaStart | double | Theta 起始。 |
| thetaLength | double | Theta 长度。 |

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
### getCastShadows() {#getCastShadows--}
```
public boolean getCastShadows()
```


获取此几何体是否可以投射阴影

**Returns:**
boolean - 此几何体是否可以投射阴影
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
### getGenerateFanCylinder() {#getGenerateFanCylinder--}
```
public boolean getGenerateFanCylinder()
```


获取当 ThetaLength 小于 2\*PI 时是否生成扇形圆柱体，否则模型将不会被裁剪。

**Returns:**
boolean - 当 ThetaLength 小于 2\*PI 时是否生成扇形圆柱，否则模型将不会被裁剪。
### getHeight() {#getHeight--}
```
public double getHeight()
```


获取圆柱体的高度。

**Returns:**
double - 圆柱的高度。
### getHeightSegments() {#getHeightSegments--}
```
public int getHeightSegments()
```


获取高度段。

**Returns:**
int - 高度段。
### getName() {#getName--}
```
public String getName()
```


获取名称。

**Returns:**
java.lang.String - 名称。
### getOffsetBottom() {#getOffsetBottom--}
```
public Vector3 getOffsetBottom()
```


获取底部侧的顶点变换偏移。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the vertices transformation offset of the bottom side.
### getOffsetTop() {#getOffsetTop--}
```
public Vector3 getOffsetTop()
```


获取顶部侧的顶点变换偏移。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the vertices transformation offset of the top side.
### getOpenEnded() {#getOpenEnded--}
```
public boolean getOpenEnded()
```


获取一个值，指示此 [Cylinder](../../com.aspose.threed/cylinder) 是否为开放式。默认值为 false。

**Returns:**
boolean - 一个值，指示此 [Cylinder](../../com.aspose.threed/cylinder) 是否为开放式。默认值为 false。
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
### getRadialSegments() {#getRadialSegments--}
```
public int getRadialSegments()
```


获取径向分段。

**Returns:**
int - 径向细分段数。
### getRadiusBottom() {#getRadiusBottom--}
```
public double getRadiusBottom()
```


获取圆柱体底部盖的半径。

**Returns:**
double - 圆柱底部盖的半径。
### getRadiusTop() {#getRadiusTop--}
```
public double getRadiusTop()
```


获取圆柱体顶部盖的半径。

**Returns:**
double - 圆柱顶部盖的半径。
### getReceiveShadows() {#getReceiveShadows--}
```
public boolean getReceiveShadows()
```


获取此几何体是否可以接收阴影。

**Returns:**
boolean - 此几何体是否可以接收阴影。
### getScene() {#getScene--}
```
public Scene getScene()
```


获取此对象所属的场景

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getShearBottom() {#getShearBottom--}
```
public Vector2 getShearBottom()
```


获取底部侧面的剪切变换，向量存储以弧度测量的 (x 轴, z 轴) 剪切值，默认值为 (0, 0)。

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - of the shear transform of the bottom side, vector stores the (x-axis, z-axis) shear value that measured in radian, default value is (0, 0)
### getShearTop() {#getShearTop--}
```
public Vector2 getShearTop()
```


获取顶部侧面的剪切变换，向量存储以弧度测量的 (x 轴, z 轴) 剪切值，默认值为 (0, 0)。

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - of the shear transform of the top side, vector stores the (x-axis, z-axis) shear value that measured in radian, default value is (0, 0)
### getThetaLength() {#getThetaLength--}
```
public double getThetaLength()
```


获取 theta 的长度。默认值为 2\\u03c0。

**Returns:**
double - theta 的长度。默认值为 2\\u03c0。
### getThetaStart() {#getThetaStart--}
```
public double getThetaStart()
```


获取 theta 的起始值。默认值为 0。

**Returns:**
double - theta 的起始值。默认值为 0。
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
### setCastShadows(boolean value) {#setCastShadows-boolean-}
```
public void setCastShadows(boolean value)
```


设置此几何体是否可以投射阴影

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


设置在导出期间是否排除此实体。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

### setGenerateFanCylinder(boolean value) {#setGenerateFanCylinder-boolean-}
```
public void setGenerateFanCylinder(boolean value)
```


设置当 ThetaLength 小于 2\*PI 时是否生成扇形圆柱，否则模型将不会被裁剪。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


设置圆柱体的高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setHeightSegments(int value) {#setHeightSegments-int-}
```
public void setHeightSegments(int value)
```


设置高度段。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 新值 |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


设置名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

### setOffsetBottom(Vector3 value) {#setOffsetBottom-com.aspose.threed.Vector3-}
```
public void setOffsetBottom(Vector3 value)
```


设置底部侧面的顶点变换偏移。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新值 |

### setOffsetTop(Vector3 value) {#setOffsetTop-com.aspose.threed.Vector3-}
```
public void setOffsetTop(Vector3 value)
```


设置顶部侧面的顶点变换偏移。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新值 |

### setOpenEnded(boolean value) {#setOpenEnded-boolean-}
```
public void setOpenEnded(boolean value)
```


设置一个值，指示此 [Cylinder](../../com.aspose.threed/cylinder) 是否为开放式。默认值为 false。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

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

### setRadialSegments(int value) {#setRadialSegments-int-}
```
public void setRadialSegments(int value)
```


设置径向段数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 新值 |

### setRadiusBottom(double value) {#setRadiusBottom-double-}
```
public void setRadiusBottom(double value)
```


设置圆柱体底部盖的半径。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setRadiusTop(double value) {#setRadiusTop-double-}
```
public void setRadiusTop(double value)
```


设置圆柱体顶部盖的半径。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


设置此几何体是否可以接收阴影。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

### setShearBottom(Vector2 value) {#setShearBottom-com.aspose.threed.Vector2-}
```
public void setShearBottom(Vector2 value)
```


设置底部侧面的剪切变换，向量存储以弧度测量的 (x 轴, z 轴) 剪切值，默认值为 (0, 0)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | 新值 |

### setShearTop(Vector2 value) {#setShearTop-com.aspose.threed.Vector2-}
```
public void setShearTop(Vector2 value)
```


设置顶部侧面的剪切变换，向量存储以弧度测量的 (x 轴, z 轴) 剪切值，默认值为 (0, 0)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | 新值 |

### setThetaLength(double value) {#setThetaLength-double-}
```
public void setThetaLength(double value)
```


设置 theta 的长度。默认值为 2\\u03c0。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setThetaStart(double value) {#setThetaStart-double-}
```
public void setThetaStart(double value)
```


设置 theta 的起始值。默认值为 0。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


将当前对象转换为网格

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

