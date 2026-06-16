---
title: "MorphTargetChannel"
second_title: "Aspose.3D for Java API 参考"
description: "MorphTargetChannel 用于组织目标几何体。"
type: docs
weight: 107
url: /zh/java/com.aspose.threed/morphtargetchannel/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class MorphTargetChannel extends A3DObject
```

MorphTargetChannel 用于 [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer) 组织目标几何体。某些文件格式如 FBX 支持并行的多个通道。**Remarks:** 权重介于 0 到 1.0 之间，默认目标权重为 0.0；
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MorphTargetChannel(String name)](#MorphTargetChannel-java.lang.String-) | 初始化 [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel) 类的新实例。 |
| [MorphTargetChannel()](#MorphTargetChannel--) | 初始化 [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel) 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [DEFAULT_WEIGHT](#DEFAULT-WEIGHT) | 形变目标的默认权重。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 查找属性。 |
| [get(Shape target)](#get-com.aspose.threed.Shape-) | 获取指定几何体的权重 |
| [getChannelWeight()](#getChannelWeight--) | 获取此通道的变形器权重。 |
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | 获取名称。 |
| [getProperties()](#getProperties--) | 获取所有属性的集合。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 获取指定属性的值 |
| [getTargets()](#getTargets--) | 获取与该通道关联的所有目标。 |
| [getWeight(Shape target)](#getWeight-com.aspose.threed.Shape-) | 获取指定目标的权重，如果该目标不属于此通道，则返回默认值 0。 |
| [getWeights()](#getWeights--) | 获取目标几何体的完整权重值。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 移除动态属性。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 移除通过名称标识的指定属性 |
| [set(Shape target, double value)](#set-com.aspose.threed.Shape-double-) | 设置指定几何体的权重 |
| [setChannelWeight(double value)](#setChannelWeight-double-) | 设置此通道的变形器权重。 |
| [setName(String value)](#setName-java.lang.String-) | 设置名称。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 设置指定属性的值 |
| [setWeight(Shape target)](#setWeight-com.aspose.threed.Shape-) | 设置指定目标的权重，默认值为 1，范围应在 0~1 之间。 |
| [setWeight(Shape target, double weight)](#setWeight-com.aspose.threed.Shape-double-) | 设置指定目标的权重，默认值为 1，范围应在 0~1 之间。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MorphTargetChannel(String name) {#MorphTargetChannel-java.lang.String-}
```
public MorphTargetChannel(String name)
```


初始化 [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 名称。 |

### MorphTargetChannel() {#MorphTargetChannel--}
```
public MorphTargetChannel()
```


初始化 [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel) 类的新实例。

### DEFAULT_WEIGHT {#DEFAULT-WEIGHT}
```
public static final double DEFAULT_WEIGHT
```


形变目标的默认权重。

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


获取指定几何体的权重

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | 目标几何体。 |

**Returns:**
double - 权重
### getChannelWeight() {#getChannelWeight--}
```
public double getChannelWeight()
```


获取此通道的变形器权重。权重在 0.0 到 1.0 之间。

**Returns:**
double - 此通道的变形器权重。权重在 0.0 到 1.0 之间。
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
### getTargets() {#getTargets--}
```
public List<Shape> getTargets()
```


获取与该通道关联的所有目标。

**Returns:**
java.util.List<com.aspose.threed.Shape> - 与该通道关联的所有目标。
### getWeight(Shape target) {#getWeight-com.aspose.threed.Shape-}
```
public double getWeight(Shape target)
```


获取指定目标的权重，如果该目标不属于此通道，则返回默认值 0。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) |  |

**Returns:**
double
### getWeights() {#getWeights--}
```
public List<Double> getWeights()
```


获取目标几何体的完整权重值。

**Returns:**
java.util.List<java.lang.Double> - 目标几何体的完整权重值。
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


设置指定几何体的权重

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | 目标几何体。 |
| 值 | double | 新值 |

### setChannelWeight(double value) {#setChannelWeight-double-}
```
public void setChannelWeight(double value)
```


设置此通道的变形器权重。权重在 0.0 到 1.0 之间。

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

### setWeight(Shape target) {#setWeight-com.aspose.threed.Shape-}
```
public void setWeight(Shape target)
```


设置指定目标的权重，默认值为 1，范围应在 0~1 之间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) |  |

### setWeight(Shape target, double weight) {#setWeight-com.aspose.threed.Shape-double-}
```
public void setWeight(Shape target, double weight)
```


设置指定目标的权重，默认值为 1，范围应在 0~1 之间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) |  |
| 权重 | double |  |

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

