---
title: "骨架"
second_title: "Aspose.3D for Java API 参考"
description: "该 主要被 CAD 软件用于帮助设计师操作骨骼结构的变换，通常在 CAD 软件之外毫无用处。"
type: docs
weight: 172
url: /zh/java/com.aspose.threed/skeleton/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity)
```
public class Skeleton extends Entity
```

该 [Skeleton](../../com.aspose.threed/skeleton) 主要被 CAD 软件用于帮助设计师操作骨骼结构的变换，通常在 CAD 软件之外毫无用处。为了使骨架层次在 CAD 软件中表现为一个对象，需要通过将顶层 [Skeleton](../../com.aspose.threed/skeleton) 节点的 [getType](../../com.aspose.threed/skeleton\#getType) 设置为 [SkeletonType.SKELETON](../../com.aspose.threed/skeletontype\#SKELETON) 来标记为根节点，并将所有子节点设置为 [SkeletonType.BONE](../../com.aspose.threed/skeletontype\#BONE)。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Skeleton()](#Skeleton--) | 初始化 [Skeleton](../../com.aspose.threed/skeleton) 类的新实例。 |
| [Skeleton(String name)](#Skeleton-java.lang.String-) | 初始化 [Skeleton](../../com.aspose.threed/skeleton) 类的新实例。 |
| [Skeleton(String name, SkeletonType type)](#Skeleton-java.lang.String-com.aspose.threed.SkeletonType-) | 初始化 [Skeleton](../../com.aspose.threed/skeleton) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 查找属性。 |
| [getBoundingBox()](#getBoundingBox--) | 获取当前实体在其对象空间坐标系中的边界框。 |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | 获取在渲染器中注册的实体渲染器的键 |
| [getExcluded()](#getExcluded--) | 获取在导出期间是否排除此实体。 |
| [getName()](#getName--) | 获取名称。 |
| [getParentNode()](#getParentNode--) | 获取第一个父节点，如果设置第一个父节点，则此实体将从其他父节点分离。 |
| [getParentNodes()](#getParentNodes--) | 获取所有父节点，实体可以附加到多个父节点以进行几何实例化 |
| [getProperties()](#getProperties--) | 获取所有属性的集合。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 获取指定属性的值 |
| [getScene()](#getScene--) | 获取此对象所属的场景 |
| [getSize()](#getSize--) | 获取在 CAD 软件中用于表示骨骼大小的肢体节点尺寸。 |
| [getType()](#getType--) | 获取骨架的类型。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 移除动态属性。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 移除通过名称标识的指定属性 |
| [setExcluded(boolean value)](#setExcluded-boolean-) | 设置在导出期间是否排除此实体。 |
| [setName(String value)](#setName-java.lang.String-) | 设置名称。 |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | 设置第一个父节点，如果设置第一个父节点，则此实体将从其他父节点分离。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 设置指定属性的值 |
| [setSize(double value)](#setSize-double-) | 设置在 CAD 软件中用于表示骨骼大小的肢体节点尺寸。 |
| [setType(SkeletonType value)](#setType-com.aspose.threed.SkeletonType-) | 设置骨架的类型。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Skeleton() {#Skeleton--}
```
public Skeleton()
```


初始化 [Skeleton](../../com.aspose.threed/skeleton) 类的新实例。

### Skeleton(String name) {#Skeleton-java.lang.String-}
```
public Skeleton(String name)
```


初始化 [Skeleton](../../com.aspose.threed/skeleton) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 名称。 |

### Skeleton(String name, SkeletonType type) {#Skeleton-java.lang.String-com.aspose.threed.SkeletonType-}
```
public Skeleton(String name, SkeletonType type)
```


初始化 [Skeleton](../../com.aspose.threed/skeleton) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 实体名称。 |
| type | [SkeletonType](../../com.aspose.threed/skeletontype) | 骨架类型 |

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
### getSize() {#getSize--}
```
public double getSize()
```


获取在 CAD 软件中用于表示骨骼大小的肢体节点尺寸。

**Returns:**
double - 在 CAD 软件中用于表示骨骼大小的肢体节点尺寸。
### getType() {#getType--}
```
public SkeletonType getType()
```


获取骨架的类型。

**Returns:**
[SkeletonType](../../com.aspose.threed/skeletontype) - the type of the skeleton.
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

### setSize(double value) {#setSize-double-}
```
public void setSize(double value)
```


设置在 CAD 软件中用于表示骨骼大小的肢体节点尺寸。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setType(SkeletonType value) {#setType-com.aspose.threed.SkeletonType-}
```
public void setType(SkeletonType value)
```


设置骨架的类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [SkeletonType](../../com.aspose.threed/skeletontype) | 新值 |

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

