---
title: "HShape"
second_title: "Aspose.3D for Java API 参考"
description: "提供 H 或 I 形状的定义参数。"
type: docs
weight: 76
url: /zh/java/com.aspose.threed/hshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Profile](../../com.aspose.threed/profile), [com.aspose.threed.ParameterizedProfile](../../com.aspose.threed/parameterizedprofile)
```
public class HShape extends ParameterizedProfile
```

该 [HShape](../../com.aspose.threed/hshape) 提供 'H' 或 'I' 形状的定义参数。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [HShape()](#HShape--) | [HShape](../../com.aspose.threed/hshape) 的构造函数 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 查找属性。 |
| [getBottomFlangeEdgeRadius()](#getBottomFlangeEdgeRadius--) | 获取底法兰上缘的半径。 |
| [getBottomFlangeFilletRadius()](#getBottomFlangeFilletRadius--) | 获取腹板与底缘之间的圆角半径。 |
| [getBottomFlangeThickness()](#getBottomFlangeThickness--) | 获取 H 形截面的法兰厚度。 |
| [getBottomFlangeWidth()](#getBottomFlangeWidth--) | 获取宽度的范围。 |
| [getBoundingBox()](#getBoundingBox--) | 获取当前实体在其对象空间坐标系中的边界框。 |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | 获取在渲染器中注册的实体渲染器的键 |
| [getExcluded()](#getExcluded--) | 获取在导出期间是否排除此实体。 |
| [getExtent()](#getExtent--) | 获取 x 和 y 维度的范围。 |
| [getName()](#getName--) | 获取名称。 |
| [getOverallDepth()](#getOverallDepth--) | 获取深度的范围。 |
| [getParentNode()](#getParentNode--) | 获取第一个父节点，如果设置第一个父节点，则此实体将从其他父节点分离。 |
| [getParentNodes()](#getParentNodes--) | 获取所有父节点，实体可以附加到多个父节点以进行几何实例化 |
| [getProperties()](#getProperties--) | 获取所有属性的集合。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 获取指定属性的值 |
| [getScene()](#getScene--) | 获取此对象所属的场景 |
| [getTopFlangeEdgeRadius()](#getTopFlangeEdgeRadius--) | 获取上法兰下缘的半径。 |
| [getTopFlangeFilletRadius()](#getTopFlangeFilletRadius--) | 获取腹板与上法兰之间的圆角半径。 |
| [getTopFlangeThickness()](#getTopFlangeThickness--) | 获取上法兰的厚度。 |
| [getTopFlangeWidth()](#getTopFlangeWidth--) | 获取上法兰的宽度。 |
| [getWebThickness()](#getWebThickness--) | 获取 H 形腹板的厚度。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 移除动态属性。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 移除通过名称标识的指定属性 |
| [setBottomFlangeEdgeRadius(double value)](#setBottomFlangeEdgeRadius-double-) | 设置底法兰上缘的半径。 |
| [setBottomFlangeFilletRadius(double value)](#setBottomFlangeFilletRadius-double-) | 设置腹板与底法兰之间的圆角半径。 |
| [setBottomFlangeThickness(double value)](#setBottomFlangeThickness-double-) | 设置 H 形的法兰厚度。 |
| [setBottomFlangeWidth(double value)](#setBottomFlangeWidth-double-) | 设置宽度的范围。 |
| [setExcluded(boolean value)](#setExcluded-boolean-) | 设置在导出期间是否排除此实体。 |
| [setName(String value)](#setName-java.lang.String-) | 设置名称。 |
| [setOverallDepth(double value)](#setOverallDepth-double-) | 设置深度的范围。 |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | 设置第一个父节点，如果设置第一个父节点，则此实体将从其他父节点分离。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 设置指定属性的值 |
| [setTopFlangeEdgeRadius(double value)](#setTopFlangeEdgeRadius-double-) | 设置上法兰下缘的半径。 |
| [setTopFlangeFilletRadius(double value)](#setTopFlangeFilletRadius-double-) | 设置腹板与上法兰之间的圆角半径。 |
| [setTopFlangeThickness(double value)](#setTopFlangeThickness-double-) | 设置上法兰的厚度。 |
| [setTopFlangeWidth(double value)](#setTopFlangeWidth-double-) | 设置上法兰的宽度。 |
| [setWebThickness(double value)](#setWebThickness-double-) | 设置 H 形腹板的厚度。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HShape() {#HShape--}
```
public HShape()
```


[HShape](../../com.aspose.threed/hshape) 的构造函数

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
### getBottomFlangeEdgeRadius() {#getBottomFlangeEdgeRadius--}
```
public double getBottomFlangeEdgeRadius()
```


获取底法兰上缘的半径。

**Returns:**
double - 底法兰上缘的半径。
### getBottomFlangeFilletRadius() {#getBottomFlangeFilletRadius--}
```
public double getBottomFlangeFilletRadius()
```


获取腹板与底缘之间的圆角半径。

**Returns:**
double - 腹板与底法兰之间的圆角半径。
### getBottomFlangeThickness() {#getBottomFlangeThickness--}
```
public double getBottomFlangeThickness()
```


获取 H 形截面的法兰厚度。

**Returns:**
double - H 形的法兰厚度。
### getBottomFlangeWidth() {#getBottomFlangeWidth--}
```
public double getBottomFlangeWidth()
```


获取宽度的范围。

**Returns:**
double - 宽度的范围。
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
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


获取在渲染器中注册的实体渲染器的键

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey)
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


获取在导出期间是否排除此实体。

**Returns:**
boolean - 是否在导出期间排除此实体。
### getExtent() {#getExtent--}
```
public Vector2 getExtent()
```


获取 x 和 y 维度的范围。

**Returns:**
[Vector2](../../com.aspose.threed/vector2)
### getName() {#getName--}
```
public String getName()
```


获取名称。

**Returns:**
java.lang.String - 名称。
### getOverallDepth() {#getOverallDepth--}
```
public double getOverallDepth()
```


获取深度的范围。

**Returns:**
double - 深度的范围。
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
### getScene() {#getScene--}
```
public Scene getScene()
```


获取此对象所属的场景

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getTopFlangeEdgeRadius() {#getTopFlangeEdgeRadius--}
```
public double getTopFlangeEdgeRadius()
```


获取上法兰下缘的半径。

**Returns:**
double - 上法兰下缘的半径。
### getTopFlangeFilletRadius() {#getTopFlangeFilletRadius--}
```
public double getTopFlangeFilletRadius()
```


获取腹板与上法兰之间的圆角半径。

**Returns:**
double - 网板与上法兰之间的圆角半径。
### getTopFlangeThickness() {#getTopFlangeThickness--}
```
public double getTopFlangeThickness()
```


获取上法兰的厚度。

**Returns:**
double - 上法兰的厚度。
### getTopFlangeWidth() {#getTopFlangeWidth--}
```
public double getTopFlangeWidth()
```


获取上法兰的宽度。

**Returns:**
double - 上法兰的宽度。
### getWebThickness() {#getWebThickness--}
```
public double getWebThickness()
```


获取 H 形腹板的厚度。

**Returns:**
double - H形截面网板的厚度。
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
### setBottomFlangeEdgeRadius(double value) {#setBottomFlangeEdgeRadius-double-}
```
public void setBottomFlangeEdgeRadius(double value)
```


设置底法兰上缘的半径。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setBottomFlangeFilletRadius(double value) {#setBottomFlangeFilletRadius-double-}
```
public void setBottomFlangeFilletRadius(double value)
```


设置腹板与底法兰之间的圆角半径。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setBottomFlangeThickness(double value) {#setBottomFlangeThickness-double-}
```
public void setBottomFlangeThickness(double value)
```


设置 H 形的法兰厚度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setBottomFlangeWidth(double value) {#setBottomFlangeWidth-double-}
```
public void setBottomFlangeWidth(double value)
```


设置宽度的范围。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


设置在导出期间是否排除此实体。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


设置名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

### setOverallDepth(double value) {#setOverallDepth-double-}
```
public void setOverallDepth(double value)
```


设置深度的范围。

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

### setTopFlangeEdgeRadius(double value) {#setTopFlangeEdgeRadius-double-}
```
public void setTopFlangeEdgeRadius(double value)
```


设置上法兰下缘的半径。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setTopFlangeFilletRadius(double value) {#setTopFlangeFilletRadius-double-}
```
public void setTopFlangeFilletRadius(double value)
```


设置腹板与上法兰之间的圆角半径。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setTopFlangeThickness(double value) {#setTopFlangeThickness-double-}
```
public void setTopFlangeThickness(double value)
```


设置上法兰的厚度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setTopFlangeWidth(double value) {#setTopFlangeWidth-double-}
```
public void setTopFlangeWidth(double value)
```


设置上法兰的宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setWebThickness(double value) {#setWebThickness-double-}
```
public void setWebThickness(double value)
```


设置 H 形腹板的厚度。

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

