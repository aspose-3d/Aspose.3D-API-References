---
title: "DracoCompressionLevel"
second_title: "Aspose.3D for Java API 参考"
description: "draco 文件的压缩级别"
type: docs
weight: 276
url: /zh/java/com.aspose.threed/dracocompressionlevel/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DracoCompressionLevel extends Enum<DracoCompressionLevel>
```

draco 文件的压缩级别
## 字段

| 字段 | 描述 |
| --- | --- |
| [FAST](#FAST) | 编码器将尽可能快速地进行压缩。 |
| [NO_COMPRESSION](#NO-COMPRESSION) | 不进行压缩，这将导致最短的编码时间。 |
| [OPTIMAL](#OPTIMAL) | 编码器将以最佳方式压缩场景，这可能需要更长的时间才能完成。 |
| [STANDARD](#STANDARD) | 标准模式，兼顾压缩率和速度。 |
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
### FAST {#FAST}
```
public static final DracoCompressionLevel FAST
```


编码器将尽可能快速地进行压缩。

### NO_COMPRESSION {#NO-COMPRESSION}
```
public static final DracoCompressionLevel NO_COMPRESSION
```


不进行压缩，这将导致最短的编码时间。

### OPTIMAL {#OPTIMAL}
```
public static final DracoCompressionLevel OPTIMAL
```


编码器将以最佳方式压缩场景，这可能需要更长的时间才能完成。

### STANDARD {#STANDARD}
```
public static final DracoCompressionLevel STANDARD
```


标准模式，兼顾压缩率和速度。

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
public static DracoCompressionLevel valueOf(String name)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |

**Returns:**
[DracoCompressionLevel](../../com.aspose.threed/dracocompressionlevel)
### values() {#values--}
```
public static DracoCompressionLevel[] values()
```




**Returns:**
com.aspose.threed.DracoCompressionLevel[]
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

