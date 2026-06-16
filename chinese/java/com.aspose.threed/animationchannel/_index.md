---
title: "AnimationChannel"
second_title: "Aspose.3D for Java API 参考"
description: "通道将属性的组件字段映射到一组关键帧序列"
type: docs
weight: 13
url: /zh/java/com.aspose.threed/animationchannel/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.KeyframeSequence](../../com.aspose.threed/keyframesequence)
```
public class AnimationChannel extends KeyframeSequence
```

通道将属性的组件字段映射到一组关键帧序列
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(double time, float value)](#add-double-float-) | 使用指定的值创建新的关键帧 |
| [add(double time, float value, Interpolation interpolation)](#add-double-float-com.aspose.threed.Interpolation-) | 使用指定的值创建新的关键帧 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 查找属性。 |
| [getBindPoint()](#getBindPoint--) | 获取拥有此曲线的属性绑定点 |
| [getClass()](#getClass--) |  |
| [getComponentType()](#getComponentType--) | 获取组件字段的类型 |
| [getDefaultValue()](#getDefaultValue--) | 获取通道的默认值。 |
| [getKeyFrames()](#getKeyFrames--) | 获取此曲线的关键帧。 |
| [getKeyframeSequence()](#getKeyframeSequence--) | 获取此通道内关联的关键帧序列 |
| [getName()](#getName--) | 获取名称。 |
| [getPostBehavior()](#getPostBehavior--) | 获取后置行为，指示在最后一个关键帧之后采样值应为何。 |
| [getPreBehavior()](#getPreBehavior--) | 获取前置行为，指示在第一个关键帧之前采样值应为何。 |
| [getProperties()](#getProperties--) | 获取所有属性的集合。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 获取指定属性的值 |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | 获取枚举器以遍历所有关键帧。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 移除动态属性。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 移除通过名称标识的指定属性 |
| [reset()](#reset--) | 移除所有关键帧并重置后置/前置行为。 |
| [setDefaultValue(Object value)](#setDefaultValue-java.lang.Object-) | 设置通道的默认值。 |
| [setKeyframeSequence(KeyframeSequence value)](#setKeyframeSequence-com.aspose.threed.KeyframeSequence-) | 获取此通道内关联的关键帧序列 |
| [setName(String value)](#setName-java.lang.String-) | 设置名称。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 设置指定属性的值 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(double time, float value) {#add-double-float-}
```
public void add(double time, float value)
```


使用指定的值创建新的关键帧

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 时间 | double | 时间位置（以秒为单位） |
| 值 | float | 此时间位置的值 |

### add(double time, float value, Interpolation interpolation) {#add-double-float-com.aspose.threed.Interpolation-}
```
public void add(double time, float value, Interpolation interpolation)
```


使用指定的值创建新的关键帧

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 时间 | double | 时间位置（以秒为单位） |
| 值 | float | 此时间位置的值 |
| interpolation | [Interpolation](../../com.aspose.threed/interpolation) | 此关键帧的插值类型 |

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
### getBindPoint() {#getBindPoint--}
```
public BindPoint getBindPoint()
```


获取拥有此曲线的属性绑定点

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - the property bind point which owns this curve
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComponentType() {#getComponentType--}
```
public Class<?> getComponentType()
```


获取组件字段的类型

**Returns:**
java.lang.Class<?> - 组件字段的类型
### getDefaultValue() {#getDefaultValue--}
```
public Object getDefaultValue()
```


获取通道的默认值。如果通道没有连接任何关键帧序列，则在动画评估期间将使用默认值。实际场景：动画仅对节点的 x 坐标进行动画，而 y 和 z 未改变，则在完整平移评估期间将使用默认值。

**Returns:**
java.lang.Object - 通道的默认值。如果通道没有连接任何关键帧序列，则在动画评估期间将使用默认值。实际场景：动画仅对节点的 x 坐标进行动画，而 y 和 z 未改变，则在完整平移评估期间将使用默认值。
### getKeyFrames() {#getKeyFrames--}
```
public List<KeyFrame> getKeyFrames()
```


获取此曲线的关键帧。

**Returns:**
java.util.List<com.aspose.threed.KeyFrame> - 此曲线的关键帧。
### getKeyframeSequence() {#getKeyframeSequence--}
```
public KeyframeSequence getKeyframeSequence()
```


获取此通道内关联的关键帧序列

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - associated keyframe sequence inside this channel
### getName() {#getName--}
```
public String getName()
```


获取名称。

**Returns:**
java.lang.String - 名称。
### getPostBehavior() {#getPostBehavior--}
```
public Extrapolation getPostBehavior()
```


获取后置行为，指示在最后一个关键帧之后采样值应为何。

**Returns:**
[Extrapolation](../../com.aspose.threed/extrapolation) - the post behavior indicates what the sampled value should be after the last key frame.
### getPreBehavior() {#getPreBehavior--}
```
public Extrapolation getPreBehavior()
```


获取前置行为，指示在第一个关键帧之前采样值应为何。

**Returns:**
[Extrapolation](../../com.aspose.threed/extrapolation) - the pre behavior indicates what the sampled value should be before the first key.
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
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### iterator() {#iterator--}
```
public Iterator<KeyFrame> iterator()
```


获取枚举器以遍历所有关键帧。

**Returns:**
java.util.Iterator<com.aspose.threed.KeyFrame>
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
### reset() {#reset--}
```
public void reset()
```


移除所有关键帧并重置后置/前置行为。

### setDefaultValue(Object value) {#setDefaultValue-java.lang.Object-}
```
public void setDefaultValue(Object value)
```


设置通道的默认值。如果通道没有连接任何关键帧序列，则在动画评估期间将使用默认值。实际场景：动画仅对节点的 x 坐标进行动画，而 y 和 z 未改变，则在完整平移评估期间将使用默认值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.Object | 新值 |

### setKeyframeSequence(KeyframeSequence value) {#setKeyframeSequence-com.aspose.threed.KeyframeSequence-}
```
public void setKeyframeSequence(KeyframeSequence value)
```


获取此通道内关联的关键帧序列

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [KeyframeSequence](../../com.aspose.threed/keyframesequence) | 新值 |

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

