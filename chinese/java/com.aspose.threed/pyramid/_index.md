---
title: "金字塔"
second_title: "Aspose.3D for Java API 参考"
description: "参数化金字塔。"
type: docs
weight: 142
url: /zh/java/com.aspose.threed/pyramid/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Primitive](../../com.aspose.threed/primitive)
```
public class Pyramid extends Primitive
```

参数化金字塔。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Pyramid()](#Pyramid--) | 使用默认底部面积(10, 10)和默认高度(5)构造一个新的金字塔实例 |
| [Pyramid(double xbottom, double ybottom, double height)](#Pyramid-double-double-double-) | 使用指定的底部面积构造一个新的金字塔实例 |
| [Pyramid(double xbottom, double ybottom, double xtop, double ytop, double height)](#Pyramid-double-double-double-double-double-) | 使用指定的底部面积、顶部面积和高度构造一个新的金字塔实例。 |
| [Pyramid(String name, double xbottom, double ybottom, double xtop, double ytop, double height)](#Pyramid-java.lang.String-double-double-double-double-double-) | 使用指定的底部面积、顶部面积和高度构造一个新的金字塔实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 查找属性。 |
| [getBottomArea()](#getBottomArea--) | 底部盖子的面积 |
| [getBottomOffset()](#getBottomOffset--) | 底部顶点的偏移量 |
| [getBoundingBox()](#getBoundingBox--) | 获取当前实体在其对象空间坐标系中的边界框。 |
| [getCastShadows()](#getCastShadows--) | 获取此几何体是否可以投射阴影 |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | 获取在渲染器中注册的实体渲染器的键 |
| [getExcluded()](#getExcluded--) | 获取在导出期间是否排除此实体。 |
| [getHeight()](#getHeight--) | 金字塔的高度 |
| [getName()](#getName--) | 获取名称。 |
| [getParentNode()](#getParentNode--) | 获取第一个父节点，如果设置第一个父节点，则此实体将从其他父节点分离。 |
| [getParentNodes()](#getParentNodes--) | 获取所有父节点，实体可以附加到多个父节点以进行几何实例化 |
| [getProperties()](#getProperties--) | 获取所有属性的集合。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 获取指定属性的值 |
| [getReceiveShadows()](#getReceiveShadows--) | 获取此几何体是否可以接收阴影。 |
| [getScene()](#getScene--) | 获取此对象所属的场景 |
| [getTopArea()](#getTopArea--) | 顶部盖子的面积 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 移除动态属性。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 移除通过名称标识的指定属性 |
| [setBottomArea(Vector2 value)](#setBottomArea-com.aspose.threed.Vector2-) | 底部盖子的面积 |
| [setBottomOffset(Vector3 value)](#setBottomOffset-com.aspose.threed.Vector3-) | 底部顶点的偏移量 |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | 设置此几何体是否可以投射阴影 |
| [setExcluded(boolean value)](#setExcluded-boolean-) | 设置在导出期间是否排除此实体。 |
| [setHeight(double value)](#setHeight-double-) | 金字塔的高度 |
| [setName(String value)](#setName-java.lang.String-) | 设置名称。 |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | 设置第一个父节点，如果设置第一个父节点，则此实体将从其他父节点分离。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 设置指定属性的值 |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | 设置此几何体是否可以接收阴影。 |
| [setTopArea(Vector2 value)](#setTopArea-com.aspose.threed.Vector2-) | 顶部盖子的面积 |
| [toMesh()](#toMesh--) | 将当前对象转换为网格 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Pyramid() {#Pyramid--}
```
public Pyramid()
```


使用默认底部面积(10, 10)和默认高度(5)构造一个新的金字塔实例

### Pyramid(double xbottom, double ybottom, double height) {#Pyramid-double-double-double-}
```
public Pyramid(double xbottom, double ybottom, double height)
```


使用指定的底部面积构造一个新的金字塔实例

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xbottom | double | 底部的 x 方向长度 |
| ybottom | double | 底部的 y 方向长度 |
| 高度 | double | 金字塔的高度 |

### Pyramid(double xbottom, double ybottom, double xtop, double ytop, double height) {#Pyramid-double-double-double-double-double-}
```
public Pyramid(double xbottom, double ybottom, double xtop, double ytop, double height)
```


使用指定的底部面积、顶部面积和高度构造一个新的金字塔实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xbottom | double | 底部面积的 x 方向长度 |
| ybottom | double | 底部面积的 y 方向长度 |
| xtop | double | 顶部面积的 x 方向长度 |
| ytop | double | 顶部面积的 y 方向长度 |
| 高度 | double | 金字塔的高度 |

### Pyramid(String name, double xbottom, double ybottom, double xtop, double ytop, double height) {#Pyramid-java.lang.String-double-double-double-double-double-}
```
public Pyramid(String name, double xbottom, double ybottom, double xtop, double ytop, double height)
```


使用指定的底部面积、顶部面积和高度构造一个新的金字塔实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 金字塔的名称 |
| xbottom | double | 底部面积的 x 方向长度 |
| ybottom | double | 底部面积的 y 方向长度 |
| xtop | double | 顶部面积的 x 方向长度 |
| ytop | double | 顶部面积的 y 方向长度 |
| 高度 | double | 金字塔的高度 |

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
### getBottomArea() {#getBottomArea--}
```
public Vector2 getBottomArea()
```


底部盖子的面积

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - Area of the bottom cap
### getBottomOffset() {#getBottomOffset--}
```
public Vector3 getBottomOffset()
```


底部顶点的偏移量

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Offset for bottom vertices
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
### getHeight() {#getHeight--}
```
public double getHeight()
```


金字塔的高度

**Returns:**
double - 金字塔的高度
### getName() {#getName--}
```
public String getName()
```


获取名称。

**Returns:**
java.lang.String - 名称。
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
### getTopArea() {#getTopArea--}
```
public Vector2 getTopArea()
```


顶部盖子的面积

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
### setBottomArea(Vector2 value) {#setBottomArea-com.aspose.threed.Vector2-}
```
public void setBottomArea(Vector2 value)
```


底部盖子的面积

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | 新值 |

### setBottomOffset(Vector3 value) {#setBottomOffset-com.aspose.threed.Vector3-}
```
public void setBottomOffset(Vector3 value)
```


底部顶点的偏移量

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新值 |

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

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


金字塔的高度

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


设置名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

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

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


设置此几何体是否可以接收阴影。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

### setTopArea(Vector2 value) {#setTopArea-com.aspose.threed.Vector2-}
```
public void setTopArea(Vector2 value)
```


顶部盖子的面积

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | 新值 |

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

