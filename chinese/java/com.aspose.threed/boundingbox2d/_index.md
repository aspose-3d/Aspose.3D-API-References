---
title: "BoundingBox2D"
second_title: "Aspose.3D for Java API 参考"
description: "轴对齐的边界框用于"
type: docs
weight: 25
url: /zh/java/com.aspose.threed/boundingbox2d/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class BoundingBox2D implements Struct<BoundingBox2D>, Serializable
```

针对 [Vector2](../../com.aspose.threed/vector2) 的轴对齐包围盒
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [BoundingBox2D(Vector2 minimum, Vector2 maximum)](#BoundingBox2D-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | 使用给定的最小角和最大角初始化有限的包围盒 |
| [BoundingBox2D()](#BoundingBox2D--) |  |
## 字段

| 字段 | 描述 |
| --- | --- |
| [INFINITE](#INFINITE) | 无限包围盒 |
| [NULL](#NULL) | 空包围盒 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [clone()](#clone--) |  |
| [copyFrom(BoundingBox2D src)](#copyFrom-com.aspose.threed.BoundingBox2D-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtent()](#getExtent--) | 获取包围盒的范围。 |
| [getMaximum()](#getMaximum--) | 包围盒的最大角 |
| [getMinimum()](#getMinimum--) | 包围盒的最小角 |
| [hashCode()](#hashCode--) |  |
| [merge(BoundingBox2D bb)](#merge-com.aspose.threed.BoundingBox2D-) | 将新盒合并到当前包围盒中。 |
| [merge(Vector2 pt)](#merge-com.aspose.threed.Vector2-) | 将新盒合并到当前包围盒中。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | 获取包围盒的字符串表示形式。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BoundingBox2D(Vector2 minimum, Vector2 maximum) {#BoundingBox2D-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public BoundingBox2D(Vector2 minimum, Vector2 maximum)
```


使用给定的最小角和最大角初始化有限的包围盒

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| minimum | [Vector2](../../com.aspose.threed/vector2) | 最小角 |
| maximum | [Vector2](../../com.aspose.threed/vector2) | 最大角 |

### BoundingBox2D() {#BoundingBox2D--}
```
public BoundingBox2D()
```


### INFINITE {#INFINITE}
```
public static final BoundingBox2D INFINITE
```


无限包围盒

### NULL {#NULL}
```
public static final BoundingBox2D NULL
```


空包围盒

### clone() {#clone--}
```
public BoundingBox2D clone()
```


克隆当前实例

**Returns:**
[BoundingBox2D](../../com.aspose.threed/boundingbox2d)
### copyFrom(BoundingBox2D src) {#copyFrom-com.aspose.threed.BoundingBox2D-}
```
public void copyFrom(BoundingBox2D src)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| src | [BoundingBox2D](../../com.aspose.threed/boundingbox2d) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
布尔
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getExtent() {#getExtent--}
```
public BoundingBoxExtent getExtent()
```


获取包围盒的范围。

**Returns:**
[BoundingBoxExtent](../../com.aspose.threed/boundingboxextent) - the extent of the bounding box.
### getMaximum() {#getMaximum--}
```
public Vector2 getMaximum()
```


包围盒的最大角

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The maximum corner of the bounding box
### getMinimum() {#getMinimum--}
```
public Vector2 getMinimum()
```


包围盒的最小角

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The minimum corner of the bounding box
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### merge(BoundingBox2D bb) {#merge-com.aspose.threed.BoundingBox2D-}
```
public void merge(BoundingBox2D bb)
```


将新盒合并到当前包围盒中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bb | [BoundingBox2D](../../com.aspose.threed/boundingbox2d) | 要合并的包围盒 |

### merge(Vector2 pt) {#merge-com.aspose.threed.Vector2-}
```
public void merge(Vector2 pt)
```


将新盒合并到当前包围盒中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pt | [Vector2](../../com.aspose.threed/vector2) | 要合并的点 |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


获取包围盒的字符串表示形式。

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

