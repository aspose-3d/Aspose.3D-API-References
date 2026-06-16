---
title: "AnimationClip"
second_title: "Aspose.3D for Java API 参考"
description: "动画剪辑是动画的集合。"
type: docs
weight: 14
url: /zh/java/com.aspose.threed/animationclip/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject)
```
public class AnimationClip extends SceneObject
```

动画剪辑是动画的集合。场景可以包含一个或多个动画剪辑。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [AnimationClip()](#AnimationClip--) | 初始化 [AnimationClip](../../com.aspose.threed/animationclip) 类的新实例。 |
| [AnimationClip(String name)](#AnimationClip-java.lang.String-) | 初始化 [AnimationClip](../../com.aspose.threed/animationclip) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [createAnimationNode(String nodeName)](#createAnimationNode-java.lang.String-) | 在当前剪辑上创建并注册动画节点的简写函数。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 查找属性。 |
| [getAnimations()](#getAnimations--) | 获取剪辑中包含的动画。 |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | 获取此动画剪辑的描述 |
| [getName()](#getName--) | 获取名称。 |
| [getProperties()](#getProperties--) | 获取所有属性的集合。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 获取指定属性的值 |
| [getScene()](#getScene--) | 获取此对象所属的场景 |
| [getStart()](#getStart--) | 获取剪辑开始的时间（秒）。 |
| [getStop()](#getStop--) | 获取剪辑结束的时间（秒）。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 移除动态属性。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 移除通过名称标识的指定属性 |
| [setDescription(String value)](#setDescription-java.lang.String-) | 设置此动画剪辑的描述 |
| [setName(String value)](#setName-java.lang.String-) | 设置名称。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 设置指定属性的值 |
| [setStart(double value)](#setStart-double-) | 设置剪辑开始时间（秒）。 |
| [setStop(double value)](#setStop-double-) | 设置剪辑结束时间（秒）。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AnimationClip() {#AnimationClip--}
```
public AnimationClip()
```


初始化 [AnimationClip](../../com.aspose.threed/animationclip) 类的新实例。

### AnimationClip(String name) {#AnimationClip-java.lang.String-}
```
public AnimationClip(String name)
```


初始化 [AnimationClip](../../com.aspose.threed/animationclip) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 名称 |

### createAnimationNode(String nodeName) {#createAnimationNode-java.lang.String-}
```
public AnimationNode createAnimationNode(String nodeName)
```


在当前剪辑上创建并注册动画节点的简写函数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| nodeName | java.lang.String | 新动画节点的名称 |

**Returns:**
[AnimationNode](../../com.aspose.threed/animationnode) - A new instance of [AnimationNode](../../com.aspose.threed/animationnode) with given name.
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
### getAnimations() {#getAnimations--}
```
public List<AnimationNode> getAnimations()
```


获取剪辑中包含的动画。

**Returns:**
java.util.List<com.aspose.threed.AnimationNode> - 包含在剪辑中的动画。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDescription() {#getDescription--}
```
public String getDescription()
```


获取此动画剪辑的描述

**Returns:**
java.lang.String - 此动画剪辑的描述
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
### getScene() {#getScene--}
```
public Scene getScene()
```


获取此对象所属的场景

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getStart() {#getStart--}
```
public double getStart()
```


获取剪辑开始的时间（秒）。

**Returns:**
double - 剪辑开始时间（秒）。
### getStop() {#getStop--}
```
public double getStop()
```


获取剪辑结束的时间（秒）。

**Returns:**
double - 剪辑结束时间（秒）。
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
### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


设置此动画剪辑的描述

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

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

### setStart(double value) {#setStart-double-}
```
public void setStart(double value)
```


设置剪辑开始时间（秒）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setStop(double value) {#setStop-double-}
```
public void setStop(double value)
```


设置剪辑结束时间（秒）。

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

