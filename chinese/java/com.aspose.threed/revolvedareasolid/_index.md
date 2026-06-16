---
title: "RevolvedAreaSolid"
second_title: "Aspose.3D for Java API 参考"
description: "此类通过围绕轴旋转由轮廓提供的横截面来表示实体模型。"
type: docs
weight: 155
url: /zh/java/com.aspose.threed/revolvedareasolid/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity)

**All Implemented Interfaces:**
[com.aspose.threed.IMeshConvertible](../../com.aspose.threed/imeshconvertible)
```
public class RevolvedAreaSolid extends Entity implements IMeshConvertible
```

此类通过围绕轴旋转由轮廓提供的横截面来表示实体模型。**Example:** 以下代码展示了如何使用 RevolvedAreaSolid 将形状旋转为实体模型。

```
//Create a new 3D scene
         Scene scene = new Scene();
 
         // Initialize the base profile to be extruded
         var profile = new RectangleShape();
         profile.setRoundingRadius(0.3);
 
         var revolved = new RevolvedAreaSolid();
         revolved.setShape(profile);
         revolved.setOrigin(new Vector3(1, 0, 0));
         revolved.setAngleStart(0);
         revolved.setAngleEnd(Math.PI);
         scene.getRootNode().createChildNode(revolved);
 
         scene.save("revolved.obj");
```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [RevolvedAreaSolid()](#RevolvedAreaSolid--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 查找属性。 |
| [getAngleEnd()](#getAngleEnd--) | 获取旋转过程的结束角度，单位为弧度，默认值为 pi。 |
| [getAngleStart()](#getAngleStart--) | 获取旋转过程的起始角度，以弧度为单位，默认值为 0。 |
| [getAxis()](#getAxis--) | 获取轴向方向，默认值为 (0, 1, 0)。 |
| [getBoundingBox()](#getBoundingBox--) | 获取当前实体在其对象空间坐标系中的边界框。 |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | 获取在渲染器中注册的实体渲染器的键 |
| [getExcluded()](#getExcluded--) | 获取在导出期间是否排除此实体。 |
| [getName()](#getName--) | 获取名称。 |
| [getOrigin()](#getOrigin--) | 获取旋转的原点，默认值为 (0, 0, 0)。 |
| [getParentNode()](#getParentNode--) | 获取第一个父节点，如果设置第一个父节点，则此实体将从其他父节点分离。 |
| [getParentNodes()](#getParentNodes--) | 获取所有父节点，实体可以附加到多个父节点以进行几何实例化 |
| [getProperties()](#getProperties--) | 获取所有属性的集合。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 获取指定属性的值 |
| [getScene()](#getScene--) | 获取此对象所属的场景 |
| [getShape()](#getShape--) | 获取用于旋转的基准轮廓。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 移除动态属性。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 移除通过名称标识的指定属性 |
| [setAngleEnd(double value)](#setAngleEnd-double-) | 设置旋转过程的结束角度，以弧度为单位，默认值为 pi。 |
| [setAngleStart(double value)](#setAngleStart-double-) | 设置旋转过程的起始角度，以弧度为单位，默认值为 0。 |
| [setAxis(Vector3 value)](#setAxis-com.aspose.threed.Vector3-) | 设置轴向方向，默认值为 (0, 1, 0)。 |
| [setExcluded(boolean value)](#setExcluded-boolean-) | 设置在导出期间是否排除此实体。 |
| [setName(String value)](#setName-java.lang.String-) | 设置名称。 |
| [setOrigin(Vector3 value)](#setOrigin-com.aspose.threed.Vector3-) | 设置旋转的原点，默认值为 (0, 0, 0)。 |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | 设置第一个父节点，如果设置第一个父节点，则此实体将从其他父节点分离。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 设置指定属性的值 |
| [setShape(Profile value)](#setShape-com.aspose.threed.Profile-) | 设置用于旋转的基准轮廓。 |
| [toMesh()](#toMesh--) | 将 [RevolvedAreaSolid](../../com.aspose.threed/revolvedareasolid) 转换为网格。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RevolvedAreaSolid() {#RevolvedAreaSolid--}
```
public RevolvedAreaSolid()
```


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
### getAngleEnd() {#getAngleEnd--}
```
public double getAngleEnd()
```


获取旋转过程的结束角度，单位为弧度，默认值为 pi。

**Returns:**
double - 旋转过程的结束角度，以弧度为单位，默认值为 pi。
### getAngleStart() {#getAngleStart--}
```
public double getAngleStart()
```


获取旋转过程的起始角度，以弧度为单位，默认值为 0。

**Returns:**
double - 旋转过程的起始角度，以弧度为单位，默认值为 0。
### getAxis() {#getAxis--}
```
public Vector3 getAxis()
```


获取轴向方向，默认值为 (0, 1, 0)。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the axis direction, default value is (0, 1, 0).
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
[EntityRendererKey](../../com.aspose.threed/entityrendererkey) - the key of the entity renderer registered in the renderer
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


获取在导出期间是否排除此实体。

**Returns:**
boolean - 是否在导出期间排除此实体。
### getName() {#getName--}
```
public String getName()
```


获取名称。

**Returns:**
java.lang.String - 名称。
### getOrigin() {#getOrigin--}
```
public Vector3 getOrigin()
```


获取旋转的原点，默认值为 (0, 0, 0)。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the origin point of the revolving, default value is (0, 0, 0).
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


获取用于旋转的基准轮廓。

**Returns:**
[Profile](../../com.aspose.threed/profile) - the base profile used to revolve.
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
### setAngleEnd(double value) {#setAngleEnd-double-}
```
public void setAngleEnd(double value)
```


设置旋转过程的结束角度，以弧度为单位，默认值为 pi。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setAngleStart(double value) {#setAngleStart-double-}
```
public void setAngleStart(double value)
```


设置旋转过程的起始角度，以弧度为单位，默认值为 0。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setAxis(Vector3 value) {#setAxis-com.aspose.threed.Vector3-}
```
public void setAxis(Vector3 value)
```


设置轴向方向，默认值为 (0, 1, 0)。

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

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


设置名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

### setOrigin(Vector3 value) {#setOrigin-com.aspose.threed.Vector3-}
```
public void setOrigin(Vector3 value)
```


设置旋转的原点，默认值为 (0, 0, 0)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新值 |

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


设置用于旋转的基准轮廓。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Profile](../../com.aspose.threed/profile) | 新值 |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


将 [RevolvedAreaSolid](../../com.aspose.threed/revolvedareasolid) 转换为网格。

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

