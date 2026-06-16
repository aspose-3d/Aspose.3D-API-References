---
title: "SweptAreaSolid"
second_title: "Aspose.3D for Java API 参考"
description: "A 通过沿导线扫掠轮廓来构建几何体。"
type: docs
weight: 181
url: /zh/java/com.aspose.threed/sweptareasolid/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity)

**All Implemented Interfaces:**
[com.aspose.threed.IMeshConvertible](../../com.aspose.threed/imeshconvertible)
```
public class SweptAreaSolid extends Entity implements IMeshConvertible
```

A [SweptAreaSolid](../../com.aspose.threed/sweptareasolid) 通过沿导线扫掠轮廓来构建几何体。 **示例:** 以下代码展示了如何通过在圆上扫掠 C 形来建模实体。

```
var directrix = new Circle(20);
         var shape = new CShape();
 
         var swept = new SweptAreaSolid();
         swept.setShape(shape);
         swept.setDirectrix(directrix);
         swept.setStartPoint(EndPoint.fromDegree(0));
         swept.setEndPoint(EndPoint.fromDegree(130));
 
         var scene = new Scene();
         scene.getRootNode().createChildNode(swept);
         scene.save("swept.obj");
```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SweptAreaSolid()](#SweptAreaSolid--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 查找属性。 |
| [getBoundingBox()](#getBoundingBox--) | 获取当前实体在其对象空间坐标系中的边界框。 |
| [getClass()](#getClass--) |  |
| [getDirectrix()](#getDirectrix--) | 扫掠区域所沿随的导线。 |
| [getEndPoint()](#getEndPoint--) | 导线的终点。 |
| [getEntityRendererKey()](#getEntityRendererKey--) | 获取在渲染器中注册的实体渲染器的键 |
| [getExcluded()](#getExcluded--) | 获取在导出期间是否排除此实体。 |
| [getName()](#getName--) | 获取名称。 |
| [getParentNode()](#getParentNode--) | 获取第一个父节点，如果设置第一个父节点，则此实体将从其他父节点分离。 |
| [getParentNodes()](#getParentNodes--) | 获取所有父节点，实体可以附加到多个父节点以进行几何实例化 |
| [getProperties()](#getProperties--) | 获取所有属性的集合。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 获取指定属性的值 |
| [getScene()](#getScene--) | 获取此对象所属的场景 |
| [getShape()](#getShape--) | 用于构建几何体的基础轮廓。 |
| [getStartPoint()](#getStartPoint--) | 导线的起点。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 移除动态属性。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 移除通过名称标识的指定属性 |
| [setDirectrix(Curve value)](#setDirectrix-com.aspose.threed.Curve-) | 扫掠区域所沿随的导线。 |
| [setEndPoint(EndPoint value)](#setEndPoint-com.aspose.threed.EndPoint-) | 导线的终点。 |
| [setExcluded(boolean value)](#setExcluded-boolean-) | 设置在导出期间是否排除此实体。 |
| [setName(String value)](#setName-java.lang.String-) | 设置名称。 |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | 设置第一个父节点，如果设置第一个父节点，则此实体将从其他父节点分离。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 设置指定属性的值 |
| [setShape(Profile value)](#setShape-com.aspose.threed.Profile-) | 用于构建几何体的基础轮廓。 |
| [setStartPoint(EndPoint value)](#setStartPoint-com.aspose.threed.EndPoint-) | 导线的起点。 |
| [toMesh()](#toMesh--) | 将当前对象转换为网格 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SweptAreaSolid() {#SweptAreaSolid--}
```
public SweptAreaSolid()
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
### getDirectrix() {#getDirectrix--}
```
public Curve getDirectrix()
```


扫掠区域所沿随的导线。

**Returns:**
[Curve](../../com.aspose.threed/curve) - The directrix that the swept area sweeping along with.
### getEndPoint() {#getEndPoint--}
```
public EndPoint getEndPoint()
```


导线的终点。

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint) - The end point of the directrix.
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


用于构建几何体的基础轮廓。

**Returns:**
[Profile](../../com.aspose.threed/profile) - The base profile to construct the geometry.
### getStartPoint() {#getStartPoint--}
```
public EndPoint getStartPoint()
```


导线的起点。

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint) - The start point of the directrix.
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
### setDirectrix(Curve value) {#setDirectrix-com.aspose.threed.Curve-}
```
public void setDirectrix(Curve value)
```


扫掠区域所沿随的导线。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Curve](../../com.aspose.threed/curve) | 新值 |

### setEndPoint(EndPoint value) {#setEndPoint-com.aspose.threed.EndPoint-}
```
public void setEndPoint(EndPoint value)
```


导线的终点。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EndPoint](../../com.aspose.threed/endpoint) | 新值 |

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


用于构建几何体的基础轮廓。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Profile](../../com.aspose.threed/profile) | 新值 |

### setStartPoint(EndPoint value) {#setStartPoint-com.aspose.threed.EndPoint-}
```
public void setStartPoint(EndPoint value)
```


导线的起点。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EndPoint](../../com.aspose.threed/endpoint) | 新值 |

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

