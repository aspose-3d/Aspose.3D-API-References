---
title: "MappingMode"
second_title: "Aspose.3D for Java API 参考"
description: "确定元素如何映射到表面。"
type: docs
weight: 285
url: /zh/java/com.aspose.threed/mappingmode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MappingMode extends Enum<MappingMode>
```

确定元素如何映射到表面。该 [MappingMode](../../com.aspose.threed/mappingmode) 定义了 [VertexElement](../../com.aspose.threed/vertexelement) 如何映射到几何体的表面。
## 字段

| 字段 | 描述 |
| --- | --- |
| [ALL_SAME](#ALL-SAME) | 一个数据映射到整个表面。 |
| [CONTROL_POINT](#CONTROL-POINT) | 每个数据映射到几何体的控制点。 |
| [EDGE](#EDGE) | 数据映射到边缘。 |
| [POLYGON](#POLYGON) | 数据映射到多边形。 |
| [POLYGON_VERTEX](#POLYGON-VERTEX) | 数据映射到多边形的顶点。当一个控制点被多个多边形共享，并且数据映射为 [POLYGON\_VERTEX](../../com.aspose.threed/mappingmode\#POLYGON-VERTEX) 时，作为不同多边形顶点的控制点将拥有各自的数据。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ALL_SAME {#ALL-SAME}
```
public static final MappingMode ALL_SAME
```


一个数据映射到整个表面。无论数据被解释为控制点/多边形顶点/边缘端点，数据始终与由 [ALL\_SAME](../../com.aspose.threed/mappingmode\#ALL-SAME) 定义的相同。

### CONTROL_POINT {#CONTROL-POINT}
```
public static final MappingMode CONTROL_POINT
```


每个数据映射到几何体的控制点。

### EDGE {#EDGE}
```
public static final MappingMode EDGE
```


数据映射到边缘。当映射为 [EDGE](../../com.aspose.threed/mappingmode\#EDGE) 时，每个边缘端点共享相同的数据。

### POLYGON {#POLYGON}
```
public static final MappingMode POLYGON
```


数据映射到多边形。当映射模式为 [POLYGON](../../com.aspose.threed/mappingmode\#POLYGON) 时，每个多边形顶点共享相同的数据。

### POLYGON_VERTEX {#POLYGON-VERTEX}
```
public static final MappingMode POLYGON_VERTEX
```


数据映射到多边形的顶点。当一个控制点被多个多边形共享，并且数据映射为 [POLYGON\_VERTEX](../../com.aspose.threed/mappingmode\#POLYGON-VERTEX) 时，作为不同多边形顶点的控制点将拥有各自的数据。

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static MappingMode valueOf(String name)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |

**Returns:**
[MappingMode](../../com.aspose.threed/mappingmode)
### values() {#values--}
```
public static MappingMode[] values()
```




**Returns:**
com.aspose.threed.MappingMode[]
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

