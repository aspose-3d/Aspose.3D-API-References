---
title: "AnimationNode"
second_title: "Aspose.3D for Java API 参考"
description: "Aspose.3Ds 支持动画层次结构，每个动画可以由多个动画以及动画关键帧定义组成。"
type: docs
weight: 15
url: /zh/java/com.aspose.threed/animationnode/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class AnimationNode extends A3DObject
```

Aspose.3D 支持动画层次结构，每个动画可以由多个动画以及动画关键帧定义组成。 [AnimationNode](../../com.aspose.threed/animationnode) 定义属性值随时间的变换，例如，动画节点可用于控制节点的变换或其他 [A3DObject](../../com.aspose.threed/a3dobject) 对象的数值属性。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [AnimationNode(String name)](#AnimationNode-java.lang.String-) | 初始化 [AnimationNode](../../com.aspose.threed/animationnode) 类的新实例。 |
| [AnimationNode()](#AnimationNode--) | 初始化 [AnimationNode](../../com.aspose.threed/animationnode) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [createBindPoint(A3DObject obj, String propName)](#createBindPoint-com.aspose.threed.A3DObject-java.lang.String-) | 根据属性数据类型创建 BindPoint。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findBindPoint(A3DObject target, String name)](#findBindPoint-com.aspose.threed.A3DObject-java.lang.String-) | 通过目标和名称查找绑定点。 |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 查找属性。 |
| [getBindPoint(A3DObject target, String propName, boolean create)](#getBindPoint-com.aspose.threed.A3DObject-java.lang.String-boolean-) | 获取给定属性上的动画绑定点。 |
| [getBindPoints()](#getBindPoints--) | 获取当前属性的绑定点 |
| [getClass()](#getClass--) |  |
| [getKeyframeSequence(A3DObject target, String propName, boolean create)](#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-boolean-) | 获取给定属性的关键帧序列。 |
| [getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create)](#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-java.lang.String-boolean-) | 获取给定属性和通道上的关键帧序列。 |
| [getName()](#getName--) | 获取名称。 |
| [getProperties()](#getProperties--) | 获取所有属性的集合。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 获取指定属性的值 |
| [getSubAnimations()](#getSubAnimations--) | 获取当前动画下的子动画节点。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 移除动态属性。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 移除通过名称标识的指定属性 |
| [setName(String value)](#setName-java.lang.String-) | 设置名称。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 设置指定属性的值 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AnimationNode(String name) {#AnimationNode-java.lang.String-}
```
public AnimationNode(String name)
```


初始化 [AnimationNode](../../com.aspose.threed/animationnode) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 名称 |

### AnimationNode() {#AnimationNode--}
```
public AnimationNode()
```


初始化 [AnimationNode](../../com.aspose.threed/animationnode) 类的新实例。

### createBindPoint(A3DObject obj, String propName) {#createBindPoint-com.aspose.threed.A3DObject-java.lang.String-}
```
public BindPoint createBindPoint(A3DObject obj, String propName)
```


根据属性数据类型创建 BindPoint。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | [A3DObject](../../com.aspose.threed/a3dobject) | 对象。 |
| propName | java.lang.String | 属性名称。 |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point instance or null if the property is not defined.
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
### findBindPoint(A3DObject target, String name) {#findBindPoint-com.aspose.threed.A3DObject-java.lang.String-}
```
public BindPoint findBindPoint(A3DObject target, String name)
```


通过目标和名称查找绑定点。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | 要查找的绑定点目标。 |
| 名称 | java.lang.String | 要查找的绑定点名称。 |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point.
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
### getBindPoint(A3DObject target, String propName, boolean create) {#getBindPoint-com.aspose.threed.A3DObject-java.lang.String-boolean-}
```
public BindPoint getBindPoint(A3DObject target, String propName, boolean create)
```


获取给定属性上的动画绑定点。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | 在何对象上创建绑定点。 |
| propName | java.lang.String | 属性的名称。 |
| 创建 | 布尔 | 如果设置为  true  且绑定点不存在，则创建绑定点。 |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point.
### getBindPoints() {#getBindPoints--}
```
public List<BindPoint> getBindPoints()
```


获取当前属性的绑定点

**Returns:**
java.util.List<com.aspose.threed.BindPoint> - 当前属性的绑定点列表
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getKeyframeSequence(A3DObject target, String propName, boolean create) {#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-boolean-}
```
public KeyframeSequence getKeyframeSequence(A3DObject target, String propName, boolean create)
```


获取给定属性的关键帧序列。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | 在何实例上创建关键帧序列。 |
| propName | java.lang.String | 属性的名称。 |
| 创建 | 布尔 | 如果设置为  true , 且序列不存在，则创建序列。 |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
### getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create) {#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-java.lang.String-boolean-}
```
public KeyframeSequence getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create)
```


获取给定属性和通道上的关键帧序列。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | 在何实例上创建关键帧序列。 |
| propName | java.lang.String | 属性的名称。 |
| channelName | java.lang.String | 通道名称。 |
| 创建 | 布尔 | 如果设置为  true  且动画序列不存在，则创建动画序列。 |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
### getName() {#getName--}
```
public String getName()
```


获取名称。

**Returns:**
java.lang.String - 名称。
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
### getSubAnimations() {#getSubAnimations--}
```
public List<AnimationNode> getSubAnimations()
```


获取当前动画下的子动画节点。

**Returns:**
java.util.List<com.aspose.threed.AnimationNode> - 当前动画下的子动画节点列表
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
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


设置名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

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

