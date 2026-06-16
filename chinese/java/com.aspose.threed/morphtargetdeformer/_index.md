---
title: "MorphTargetDeformer"
second_title: "Aspose.3D for Java API 参考"
description: "MorphTargetDeformer 提供每个顶点的动画。"
type: docs
weight: 108
url: /zh/java/com.aspose.threed/morphtargetdeformer/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Deformer](../../com.aspose.threed/deformer)
```
public class MorphTargetDeformer extends Deformer
```

MorphTargetDeformer 提供每顶点动画。MorphTargetDeformer 通过 [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel) 组织所有目标，每个通道可以组织多个目标。Morph target deformer 的常见用法是为角色应用面部表情。更多细节请参阅 https://en.wikipedia.org/wiki/Morph\_target\_animation
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MorphTargetDeformer(String name)](#MorphTargetDeformer-java.lang.String-) | 初始化 [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer) 类的新实例。 |
| [MorphTargetDeformer()](#MorphTargetDeformer--) | 初始化 [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 查找属性。 |
| [get(Shape target)](#get-com.aspose.threed.Shape-) | 获取给定几何体的权重，这是一种无需访问通道即可修改目标权重的简写方式。 |
| [getChannels()](#getChannels--) | 获取此变形器中包含的所有通道 |
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | 获取名称。 |
| [getOwner()](#getOwner--) | 获取拥有此变形器的几何体 |
| [getProperties()](#getProperties--) | 获取所有属性的集合。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 获取指定属性的值 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 移除动态属性。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 移除通过名称标识的指定属性 |
| [set(Shape target, double value)](#set-com.aspose.threed.Shape-double-) | 设置给定几何体的权重，这是一种无需访问通道即可修改目标权重的简写方式。 |
| [setName(String value)](#setName-java.lang.String-) | 设置名称。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 设置指定属性的值 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MorphTargetDeformer(String name) {#MorphTargetDeformer-java.lang.String-}
```
public MorphTargetDeformer(String name)
```


初始化 [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 名称。 |

### MorphTargetDeformer() {#MorphTargetDeformer--}
```
public MorphTargetDeformer()
```


初始化 [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer) 类的新实例。

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
### get(Shape target) {#get-com.aspose.threed.Shape-}
```
public double get(Shape target)
```


获取给定几何体的权重，这是一种无需访问通道即可修改目标权重的简写方式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | 目标几何 |

**Returns:**
double - 权重
### getChannels() {#getChannels--}
```
public List<MorphTargetChannel> getChannels()
```


获取此变形器中包含的所有通道

**Returns:**
java.util.List<com.aspose.threed.MorphTargetChannel> - 此变形器中包含的所有通道
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getName() {#getName--}
```
public String getName()
```


获取名称。

**Returns:**
java.lang.String - 名称。
### getOwner() {#getOwner--}
```
public Geometry getOwner()
```


获取拥有此变形器的几何体

**Returns:**
[Geometry](../../com.aspose.threed/geometry) - the geometry which owns this deformer
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
### set(Shape target, double value) {#set-com.aspose.threed.Shape-double-}
```
public void set(Shape target, double value)
```


设置给定几何体的权重，这是一种无需访问通道即可修改目标权重的简写方式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | 目标几何 |
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

