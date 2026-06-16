---
title: "LinearExtrusion"
second_title: "Aspose.3D for Java API 参考"
description: "线性拉伸以二维形状为输入，并在第三维度上扩展该形状。"
type: docs
weight: 96
url: /zh/java/com.aspose.threed/linearextrusion/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity)

**All Implemented Interfaces:**
[com.aspose.threed.IMeshConvertible](../../com.aspose.threed/imeshconvertible)
```
public class LinearExtrusion extends Entity implements IMeshConvertible
```

线性挤压接受一个二维形状作为输入，并在第三维度上扩展该形状。 **Example:** 以下代码展示了如何使用 LinearExtrusion 将形状挤压成实体模型。

```
//Create a new 3D scene
 		Scene scene = new Scene();
 
 		// Initialize the base profile to be extruded
 		var profile = new RectangleShape();
 		profile.setRoundingRadius(0.3);
 
 		// Create left node
 		var left = scene.getRootNode().createChildNode();
 		left.createChildNode(new Box(0.01, 3, 3));
 
 		// Create right node
 		var right = scene.getRootNode().createChildNode();
 		right.createChildNode(new Box(0.01, 3, 3));
 		right.getTransform().setTranslation(new Vector3(5, 0, 0));
 
 		//Perform linear extrusion on left node using center and slices property
 		var l = new LinearExtrusion(profile, 10);
 		l.setCenter(false);
 		l.setSlices(3);
 		l.setTwist(20);
 		left.createChildNode(l);
 
 		// Perform linear extrusion on left node using center and slices property
 		var r = new LinearExtrusion(profile, 10);
 		r.setCenter(true);
 		r.setSlices(3);
 		r.setTwist(90);
 		right.createChildNode(r);
```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [LinearExtrusion()](#LinearExtrusion--) | 实例 [LinearExtrusion](../../com.aspose.threed/linearextrusion) 的构造函数。 |
| [LinearExtrusion(Profile shape, double height)](#LinearExtrusion-com.aspose.threed.Profile-double-) | 实例 [LinearExtrusion](../../com.aspose.threed/linearextrusion) 的构造函数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 查找属性。 |
| [getBoundingBox()](#getBoundingBox--) | 获取当前实体在其对象空间坐标系中的边界框。 |
| [getCenter()](#getCenter--) | 如果此值为 false，则线性挤压的 Z 范围为 0 到 height；否则范围为 -height/2 到 height/2。 |
| [getClass()](#getClass--) |  |
| [getDirection()](#getDirection--) | 挤压方向，默认值为 (0, 0, 1) |
| [getEntityRendererKey()](#getEntityRendererKey--) | 获取在渲染器中注册的实体渲染器的键 |
| [getExcluded()](#getExcluded--) | 获取在导出期间是否排除此实体。 |
| [getHeight()](#getHeight--) | 挤压几何体的高度，默认值为 1.0 |
| [getName()](#getName--) | 获取名称。 |
| [getParentNode()](#getParentNode--) | 获取第一个父节点，如果设置第一个父节点，则此实体将从其他父节点分离。 |
| [getParentNodes()](#getParentNodes--) | 获取所有父节点，实体可以附加到多个父节点以进行几何实例化 |
| [getProperties()](#getProperties--) | 获取所有属性的集合。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 获取指定属性的值 |
| [getScene()](#getScene--) | 获取此对象所属的场景 |
| [getShape()](#getShape--) | 要挤压的基础形状。 |
| [getSlices()](#getSlices--) | 扭曲挤压几何体的切片数，默认值为 1。 |
| [getTwist()](#getTwist--) | 形状被挤压的角度（度数）。 |
| [getTwistOffset()](#getTwistOffset--) | 扭曲时使用的偏移量，默认值为 (0, 0, 0)。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 移除动态属性。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 移除通过名称标识的指定属性 |
| [setCenter(boolean value)](#setCenter-boolean-) | 如果此值为 false，则线性挤压的 Z 范围为 0 到 height；否则范围为 -height/2 到 height/2。 |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | 挤压方向，默认值为 (0, 0, 1) |
| [setExcluded(boolean value)](#setExcluded-boolean-) | 设置在导出期间是否排除此实体。 |
| [setHeight(double value)](#setHeight-double-) | 挤压几何体的高度，默认值为 1.0 |
| [setName(String value)](#setName-java.lang.String-) | 设置名称。 |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | 设置第一个父节点，如果设置第一个父节点，则此实体将从其他父节点分离。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 设置指定属性的值 |
| [setShape(Profile value)](#setShape-com.aspose.threed.Profile-) | 要挤压的基础形状。 |
| [setSlices(int value)](#setSlices-int-) | 扭曲挤压几何体的切片数，默认值为 1。 |
| [setTwist(double value)](#setTwist-double-) | 形状被挤压的角度（度数）。 |
| [setTwistOffset(Vector3 value)](#setTwistOffset-com.aspose.threed.Vector3-) | 扭曲时使用的偏移量，默认值为 (0, 0, 0)。 |
| [toMesh()](#toMesh--) | 将挤压转换为网格。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LinearExtrusion() {#LinearExtrusion--}
```
public LinearExtrusion()
```


实例 [LinearExtrusion](../../com.aspose.threed/linearextrusion) 的构造函数。

### LinearExtrusion(Profile shape, double height) {#LinearExtrusion-com.aspose.threed.Profile-double-}
```
public LinearExtrusion(Profile shape, double height)
```


实例 [LinearExtrusion](../../com.aspose.threed/linearextrusion) 的构造函数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shape | [Profile](../../com.aspose.threed/profile) |  |
| 高度 | double |  |

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
### getCenter() {#getCenter--}
```
public boolean getCenter()
```


如果此值为 false，则线性挤压的 Z 范围为 0 到 height；否则范围为 -height/2 到 height/2。

**Returns:**
boolean - 如果此值为 false，则线性挤压的 Z 范围为 0 到 height；否则范围为 -height/2 到 height/2。
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


挤压方向，默认值为 (0, 0, 1)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The direction of extrusion, default value is (0, 0, 1)
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


挤压几何体的高度，默认值为 1.0

**Returns:**
double - 挤压几何体的高度，默认值为 1.0
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
### getScene() {#getScene--}
```
public Scene getScene()
```


获取此对象所属的场景

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getShape() {#getShape--}
```
public Profile getShape()
```


要挤压的基础形状。

**Returns:**
[Profile](../../com.aspose.threed/profile) - The base shape to be extruded.
### getSlices() {#getSlices--}
```
public int getSlices()
```


扭曲挤压几何体的切片数，默认值为 1。

**Returns:**
int - 扭曲挤压几何体的切片数，默认值为 1。
### getTwist() {#getTwist--}
```
public double getTwist()
```


形状被挤压的角度（度数）。

**Returns:**
double - 形状被挤压的角度（度数）。
### getTwistOffset() {#getTwistOffset--}
```
public Vector3 getTwistOffset()
```


扭曲时使用的偏移量，默认值为 (0, 0, 0)。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The offset that used in twisting, default value is (0, 0, 0).
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
### setCenter(boolean value) {#setCenter-boolean-}
```
public void setCenter(boolean value)
```


如果此值为 false，则线性挤压的 Z 范围为 0 到 height；否则范围为 -height/2 到 height/2。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

### setDirection(Vector3 value) {#setDirection-com.aspose.threed.Vector3-}
```
public void setDirection(Vector3 value)
```


挤压方向，默认值为 (0, 0, 1)

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

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


挤压几何体的高度，默认值为 1.0

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

### setShape(Profile value) {#setShape-com.aspose.threed.Profile-}
```
public void setShape(Profile value)
```


要挤压的基础形状。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Profile](../../com.aspose.threed/profile) | 新值 |

### setSlices(int value) {#setSlices-int-}
```
public void setSlices(int value)
```


扭曲挤压几何体的切片数，默认值为 1。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 新值 |

### setTwist(double value) {#setTwist-double-}
```
public void setTwist(double value)
```


形状被挤压的角度（度数）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setTwistOffset(Vector3 value) {#setTwistOffset-com.aspose.threed.Vector3-}
```
public void setTwistOffset(Vector3 value)
```


扭曲时使用的偏移量，默认值为 (0, 0, 0)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新值 |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


将挤压转换为网格。

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

