---
title: "EndPoint"
second_title: "Aspose.3D for Java API 参考"
description: "用于修剪曲线的端点可以是参数值或笛卡尔点。"
type: docs
weight: 51
url: /zh/java/com.aspose.threed/endpoint/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class EndPoint implements Struct<EndPoint>, Serializable
```

用于修剪曲线的端点，可以是参数值或笛卡尔点。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EndPoint(Vector3 point)](#EndPoint-com.aspose.threed.Vector3-) | 从笛卡尔点构造一个 [EndPoint](../../com.aspose.threed/endpoint)。 |
| [EndPoint(double v)](#EndPoint-double-) | 从实数参数构造一个 [EndPoint](../../com.aspose.threed/endpoint)。 |
| [EndPoint()](#EndPoint--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [clone()](#clone--) |  |
| [copyFrom(EndPoint src)](#copyFrom-com.aspose.threed.EndPoint-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromDegree(double degree)](#fromDegree-double-) | 创建以度数衡量的端点。 |
| [fromRadian(double degree)](#fromRadian-double-) | 创建以弧度衡量的端点。 |
| [getAsPoint()](#getAsPoint--) | 获取端点的笛卡尔点，或抛出异常。 |
| [getAsValue()](#getAsValue--) | 获取端点的实数参数，或抛出异常。 |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [isCartesianPoint()](#isCartesianPoint--) | 端点是笛卡尔点吗？ |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | 返回当前端点的字符串表示。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EndPoint(Vector3 point) {#EndPoint-com.aspose.threed.Vector3-}
```
public EndPoint(Vector3 point)
```


从笛卡尔点构造一个 [EndPoint](../../com.aspose.threed/endpoint)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | [Vector3](../../com.aspose.threed/vector3) | 用于构造的点 |

### EndPoint(double v) {#EndPoint-double-}
```
public EndPoint(double v)
```


从实数参数构造一个 [EndPoint](../../com.aspose.threed/endpoint)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| v | double | 用于构造端点的实数参数 |

### EndPoint() {#EndPoint--}
```
public EndPoint()
```


### clone() {#clone--}
```
public EndPoint clone()
```


克隆当前实例

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint)
### copyFrom(EndPoint src) {#copyFrom-com.aspose.threed.EndPoint-}
```
public void copyFrom(EndPoint src)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| src | [EndPoint](../../com.aspose.threed/endpoint) |  |

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
### fromDegree(double degree) {#fromDegree-double-}
```
public static EndPoint fromDegree(double degree)
```


创建以度数衡量的端点。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 度 | double | 度数值 |

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint) - An end point constructed from degree
### fromRadian(double degree) {#fromRadian-double-}
```
public static EndPoint fromRadian(double degree)
```


创建以弧度衡量的端点。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 度 | double | 弧度值 |

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint) - An end point constructed from radian
### getAsPoint() {#getAsPoint--}
```
public Vector3 getAsPoint()
```


获取端点的笛卡尔点，或抛出异常。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the end point as Cartesian point, or thrown an exception.
### getAsValue() {#getAsValue--}
```
public double getAsValue()
```


获取端点的实数参数，或抛出异常。

**Returns:**
double - 端点的实数参数，或抛出异常。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### isCartesianPoint() {#isCartesianPoint--}
```
public boolean isCartesianPoint()
```


端点是笛卡尔点吗？

**Returns:**
boolean - 端点是笛卡尔点吗？
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


返回当前端点的字符串表示。

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

