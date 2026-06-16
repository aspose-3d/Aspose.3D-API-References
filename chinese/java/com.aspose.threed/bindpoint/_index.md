---
title: "BindPoint"
second_title: "Aspose.3D for Java API 参考"
description: "通常在对象的属性上创建 BindPoint，某些属性类型包含多个组件字段（如 Vector3 字段），将为每个组件字段生成通道，并通过这些通道将字段连接到一个或多个关键帧序列实例。"
type: docs
weight: 19
url: /zh/java/com.aspose.threed/bindpoint/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class BindPoint extends A3DObject
```

通常在对象的属性上创建 [BindPoint](../../com.aspose.threed/bindpoint)，某些属性类型包含多个组件字段（如 Vector3 字段），[BindPoint](../../com.aspose.threed/bindpoint) 将为每个组件字段生成通道，并通过这些通道将字段连接到一个或多个关键帧序列实例。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [BindPoint(Scene scene, Property prop)](#BindPoint-com.aspose.threed.Scene-com.aspose.threed.Property-) | 初始化 [BindPoint](../../com.aspose.threed/bindpoint) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [addChannel(String name, Class<?> type, Object value)](#addChannel-java.lang.String-java.lang.Class----java.lang.Object-) | 添加指定的通道属性。 |
| [addChannel(String name, Object value)](#addChannel-java.lang.String-java.lang.Object-) | 添加指定的通道属性。 |
| [bindKeyframeSequence(String channelName, KeyframeSequence sequence)](#bindKeyframeSequence-java.lang.String-com.aspose.threed.KeyframeSequence-) | 将关键帧序列绑定到指定通道 |
| [createKeyframeSequence(String name)](#createKeyframeSequence-java.lang.String-) | 创建新曲线并将其连接到曲线映射的第一个通道 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 查找属性。 |
| [get(String channelName)](#get-java.lang.String-) | 根据给定名称获取通道 |
| [getChannel(String channelName)](#getChannel-java.lang.String-) | 根据给定名称获取通道 |
| [getChannelsCount()](#getChannelsCount--) | 获取此动画曲线映射中定义的属性通道总数。 |
| [getClass()](#getClass--) |  |
| [getKeyframeSequence(String channelName)](#getKeyframeSequence-java.lang.String-) | 获取指定通道中的第一个关键帧序列 |
| [getName()](#getName--) | 获取名称。 |
| [getProperties()](#getProperties--) | 获取所有属性的集合。 |
| [getProperty()](#getProperty--) | 获取与 CurveMapping 关联的属性 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 获取指定属性的值 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 移除动态属性。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 移除通过名称标识的指定属性 |
| [resetChannels()](#resetChannels--) | 清空此动画曲线映射的属性通道。 |
| [setName(String value)](#setName-java.lang.String-) | 设置名称。 |
| [setProperty(Property value)](#setProperty-com.aspose.threed.Property-) | 获取与 CurveMapping 关联的属性 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 设置指定属性的值 |
| [toString()](#toString--) | 将对象格式化为字符串 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BindPoint(Scene scene, Property prop) {#BindPoint-com.aspose.threed.Scene-com.aspose.threed.Property-}
```
public BindPoint(Scene scene, Property prop)
```


初始化 [BindPoint](../../com.aspose.threed/bindpoint) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | 包含动画的场景。 |
| prop | [Property](../../com.aspose.threed/property) | 属性。 |

### addChannel(String name, Class<?> type, Object value) {#addChannel-java.lang.String-java.lang.Class----java.lang.Object-}
```
public boolean addChannel(String name, Class<?> type, Object value)
```


添加指定的通道属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 名称。 |
| type | java.lang.Class<?> | 类型。 |
| 值 | java.lang.Object | 值。 |

**Returns:**
布尔型 - 如果通道已添加则为 true，否则为 false。
### addChannel(String name, Object value) {#addChannel-java.lang.String-java.lang.Object-}
```
public boolean addChannel(String name, Object value)
```


添加指定的通道属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 名称。 |
| 值 | java.lang.Object | 值。 |

**Returns:**
布尔型 - 如果通道已添加则为 true，否则为 false。
### bindKeyframeSequence(String channelName, KeyframeSequence sequence) {#bindKeyframeSequence-java.lang.String-com.aspose.threed.KeyframeSequence-}
```
public void bindKeyframeSequence(String channelName, KeyframeSequence sequence)
```


将关键帧序列绑定到指定通道

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| channelName | java.lang.String | 关键帧序列将绑定到的通道 |
| sequence | [KeyframeSequence](../../com.aspose.threed/keyframesequence) | 要绑定的关键帧序列 |

### createKeyframeSequence(String name) {#createKeyframeSequence-java.lang.String-}
```
public KeyframeSequence createKeyframeSequence(String name)
```


创建新曲线并将其连接到曲线映射的第一个通道

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 新序列的名称。 |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
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
### get(String channelName) {#get-java.lang.String-}
```
public AnimationChannel get(String channelName)
```


根据给定名称获取通道

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| channelName | java.lang.String | 通道名称 |

**Returns:**
[AnimationChannel](../../com.aspose.threed/animationchannel) - Animation channel
### getChannel(String channelName) {#getChannel-java.lang.String-}
```
public AnimationChannel getChannel(String channelName)
```


根据给定名称获取通道

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| channelName | java.lang.String | 要查找的通道名称 |

**Returns:**
[AnimationChannel](../../com.aspose.threed/animationchannel) - Channel with the name
### getChannelsCount() {#getChannelsCount--}
```
public int getChannelsCount()
```


获取此动画曲线映射中定义的属性通道总数。

**Returns:**
int - 通道计数。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getKeyframeSequence(String channelName) {#getKeyframeSequence-java.lang.String-}
```
public KeyframeSequence getKeyframeSequence(String channelName)
```


获取指定通道中的第一个关键帧序列

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| channelName | java.lang.String | 要查找的通道名称 |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - First keyframe sequence with the channel name
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
### getProperty() {#getProperty--}
```
public Property getProperty()
```


获取与 CurveMapping 关联的属性

**Returns:**
[Property](../../com.aspose.threed/property) - the property associated with the CurveMapping
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
### resetChannels() {#resetChannels--}
```
public void resetChannels()
```


清空此动画曲线映射的属性通道。

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


设置名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

### setProperty(Property value) {#setProperty-com.aspose.threed.Property-}
```
public void setProperty(Property value)
```


获取与 CurveMapping 关联的属性

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Property](../../com.aspose.threed/property) | 新值 |

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


将对象格式化为字符串

**Returns:**
java.lang.String - 对象字符串
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

