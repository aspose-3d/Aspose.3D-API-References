---
title: "骨骼"
second_title: "Aspose.3D for Java API 参考"
description: "骨骼定义了几何体控制点的子集，并为每个控制点定义了混合权重。"
type: docs
weight: 20
url: /zh/java/com.aspose.threed/bone/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class Bone extends A3DObject
```

骨骼定义了几何体控制点的子集，并为每个控制点定义了混合权重。 [Bone](../../com.aspose.threed/bone) 对象不能直接使用，需要使用 [SkinDeformer](../../com.aspose.threed/skindeformer) 实例来变形几何体，且 [SkinDeformer](../../com.aspose.threed/skindeformer) 附带一组骨骼，每个骨骼链接到一个节点。注意：几何体的一个控制点可以绑定到多个骨骼。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Bone(String name)](#Bone-java.lang.String-) | 初始化一个新的 [Bone](../../com.aspose.threed/bone) 类实例。 |
| [Bone()](#Bone--) | 初始化一个新的 [Bone](../../com.aspose.threed/bone) 类实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 查找属性。 |
| [get(int index)](#get-int-) | 获取指定控制点的混合权重 |
| [getBoneTransform()](#getBoneTransform--) | 获取骨骼的变换矩阵。 |
| [getClass()](#getClass--) |  |
| [getLinkMode()](#getLinkMode--) | 骨骼的链接模式指骨骼在层次结构中与其父骨骼连接或链接的方式。 |
| [getName()](#getName--) | 获取名称。 |
| [getNode()](#getNode--) | 获取节点。 |
| [getProperties()](#getProperties--) | 获取所有属性的集合。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 获取指定属性的值 |
| [getTransform()](#getTransform--) | 获取包含骨骼的节点的变换矩阵。 |
| [getWeight(int index)](#getWeight-int-) | 获取指定索引的控制点的权重 |
| [getWeightCount()](#getWeightCount--) | 获取权重的计数，若使用 [setWeight](../../com.aspose.threed/bone\#setWeight) 将自动扩展。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 移除动态属性。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 移除通过名称标识的指定属性 |
| [set(int index, double value)](#set-int-double-) | 设置指定控制点的混合权重 |
| [setBoneTransform(Matrix4 value)](#setBoneTransform-com.aspose.threed.Matrix4-) | 设置骨骼的变换矩阵。 |
| [setLinkMode(BoneLinkMode value)](#setLinkMode-com.aspose.threed.BoneLinkMode-) | 骨骼的链接模式指骨骼在层次结构中与其父骨骼连接或链接的方式。 |
| [setName(String value)](#setName-java.lang.String-) | 设置名称。 |
| [setNode(Node value)](#setNode-com.aspose.threed.Node-) | 设置节点。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 设置指定属性的值 |
| [setTransform(Matrix4 value)](#setTransform-com.aspose.threed.Matrix4-) | 设置包含骨骼的节点的变换矩阵。 |
| [setWeight(int index, double weight)](#setWeight-int-double-) | 设置指定索引的控制点的权重 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Bone(String name) {#Bone-java.lang.String-}
```
public Bone(String name)
```


初始化一个新的 [Bone](../../com.aspose.threed/bone) 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 名称。 |

### Bone() {#Bone--}
```
public Bone()
```


初始化一个新的 [Bone](../../com.aspose.threed/bone) 类实例。

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
### get(int index) {#get-int-}
```
public double get(int index)
```


获取指定控制点的混合权重

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int | 权重的索引 |

**Returns:**
double - 权重
### getBoneTransform() {#getBoneTransform--}
```
public Matrix4 getBoneTransform()
```


获取骨骼的变换矩阵。

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the transform matrix of the bone.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLinkMode() {#getLinkMode--}
```
public BoneLinkMode getLinkMode()
```


骨骼的链接模式指骨骼在层次结构中与其父骨骼连接或链接的方式。

**Returns:**
[BoneLinkMode](../../com.aspose.threed/bonelinkmode) - A bone's link mode refers to the way in which a bone is connected or linked to its parent bone within a hierarchical structure.
### getName() {#getName--}
```
public String getName()
```


获取名称。

**Returns:**
java.lang.String - 名称。
### getNode() {#getNode--}
```
public Node getNode()
```


获取节点。骨骼节点是皮肤附着的骨骼，[SkinDeformer](../../com.aspose.threed/skindeformer) 将使用骨骼节点影响控制点的位移。骨骼节点通常附带一个 [Skeleton](../../com.aspose.threed/skeleton)，但这不是必需的。附加的 [Skeleton](../../com.aspose.threed/skeleton) 通常由 DCC 软件用于向用户显示骨架。

**Returns:**
[Node](../../com.aspose.threed/node) - the node. The bone node is the bone which skin attached to, the [SkinDeformer](../../com.aspose.threed/skindeformer) will use bone node to influence the displacement of the control points. Bone node usually has a [Skeleton](../../com.aspose.threed/skeleton) attached, but it's not required. Attached [Skeleton](../../com.aspose.threed/skeleton) is usually used by DCC software to show skeleton to user.
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
### getTransform() {#getTransform--}
```
public Matrix4 getTransform()
```


获取包含骨骼的节点的变换矩阵。

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the transform matrix of the node containing the bone.
### getWeight(int index) {#getWeight-int-}
```
public double getWeight(int index)
```


获取指定索引的控制点的权重

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int | 控制点的索引 |

**Returns:**
double - 指定索引处的权重，如果索引无效则为 0
### getWeightCount() {#getWeightCount--}
```
public int getWeightCount()
```


获取权重的计数，若使用 [setWeight](../../com.aspose.threed/bone\#setWeight) 将自动扩展。

**Returns:**
int - 权重的计数，若使用 [setWeight](../../com.aspose.threed/bone\#setWeight) 将自动扩展
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
### set(int index, double value) {#set-int-double-}
```
public void set(int index, double value)
```


设置指定控制点的混合权重

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int | 权重的索引 |
| 值 | double | 新值 |

### setBoneTransform(Matrix4 value) {#setBoneTransform-com.aspose.threed.Matrix4-}
```
public void setBoneTransform(Matrix4 value)
```


设置骨骼的变换矩阵。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | 新值 |

### setLinkMode(BoneLinkMode value) {#setLinkMode-com.aspose.threed.BoneLinkMode-}
```
public void setLinkMode(BoneLinkMode value)
```


骨骼的链接模式指骨骼在层次结构中与其父骨骼连接或链接的方式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [BoneLinkMode](../../com.aspose.threed/bonelinkmode) | 新值 |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


设置名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

### setNode(Node value) {#setNode-com.aspose.threed.Node-}
```
public void setNode(Node value)
```


设置节点。骨骼节点是皮肤附着的骨骼，[SkinDeformer](../../com.aspose.threed/skindeformer) 将使用骨骼节点影响控制点的位移。骨骼节点通常附带一个 [Skeleton](../../com.aspose.threed/skeleton)，但这不是必需的。附加的 [Skeleton](../../com.aspose.threed/skeleton) 通常由 DCC 软件用于向用户显示骨架。

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

### setTransform(Matrix4 value) {#setTransform-com.aspose.threed.Matrix4-}
```
public void setTransform(Matrix4 value)
```


设置包含骨骼的节点的变换矩阵。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | 新值 |

### setWeight(int index, double weight) {#setWeight-int-double-}
```
public void setWeight(int index, double weight)
```


设置指定索引的控制点的权重

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int | 控制点的索引 |
| 权重 | double | 新权重 |

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

