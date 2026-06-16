---
title: "NurbsDirection"
second_title: "Aspose.3D for Java API 参考"
description: "一个 3D 有两个方向，分别是  和  ，并且  为每个方向定义数据。"
type: docs
weight: 113
url: /zh/java/com.aspose.threed/nurbsdirection/
---

**Inheritance:**
java.lang.Object
```
public class NurbsDirection
```

一个 3D [NurbsSurface](../../com.aspose.threed/nurbssurface) 有两个方向，分别是 [NurbsSurface.getU](../../com.aspose.threed/nurbssurface\#getU) 和 [NurbsSurface.getV](../../com.aspose.threed/nurbssurface\#getV)，[NurbsDirection](../../com.aspose.threed/nurbsdirection) 为每个方向定义数据。方向实际上是一条 NURBS 曲线，这意味着它也由其 [getOrder](../../com.aspose.threed/nurbsdirection\#getOrder)、[getKnotVectors](../../com.aspose.threed/nurbsdirection\#getKnotVectors) 以及一组加权控制点（在 [NurbsSurface](../../com.aspose.threed/nurbssurface) 中定义）决定。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [NurbsDirection()](#NurbsDirection--) | 构造一个新的 [NurbsDirection](../../com.aspose.threed/nurbsdirection) 实例 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | 获取当前方向上控制点的计数。 |
| [getDegree()](#getDegree--) | 获取 NURBS 曲线的次数，次数定义为 Order - 1 |
| [getDivisions()](#getDivisions--) | 获取当前方向相邻控制点之间的细分数。 |
| [getKnotVectors()](#getKnotVectors--) | 获取节点向量，它是一系列参数值，决定控制点在何处以及如何影响 NURBS 曲线。 |
| [getMultiplicity()](#getMultiplicity--) | 获取多重性。 |
| [getOrder()](#getOrder--) | 获取 NURBS 曲线的阶数，它定义了影响曲线上任意点的相邻控制点的数量。 |
| [getType()](#getType--) | 获取当前方向的类型。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCount(int value)](#setCount-int-) | 设置当前方向上控制点的计数。 |
| [setDegree(int value)](#setDegree-int-) | 设置 NURBS 曲线的次数，次数定义为 Order - 1 |
| [setDivisions(int value)](#setDivisions-int-) | 设置当前方向相邻控制点之间的细分数。 |
| [setOrder(int value)](#setOrder-int-) | 设置 NURBS 曲线的阶数，它定义了影响曲线上任意点的相邻控制点的数量。 |
| [setType(NurbsType value)](#setType-com.aspose.threed.NurbsType-) | 设置当前方向的类型。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NurbsDirection() {#NurbsDirection--}
```
public NurbsDirection()
```


构造一个新的 [NurbsDirection](../../com.aspose.threed/nurbsdirection) 实例

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public int getCount()
```


获取当前方向上控制点的计数。

**Returns:**
int - 当前方向上控制点的计数。
### getDegree() {#getDegree--}
```
public int getDegree()
```


获取 NURBS 曲线的次数，次数定义为 Order - 1

**Returns:**
int - NURBS 曲线的次数，次数定义为 Order - 1
### getDivisions() {#getDivisions--}
```
public int getDivisions()
```


获取当前方向相邻控制点之间的细分数。

**Returns:**
int - 当前方向相邻控制点之间的细分数。
### getKnotVectors() {#getKnotVectors--}
```
public List<Double> getKnotVectors()
```


获取节点向量，它是一系列参数值，决定控制点在何处以及如何影响 NURBS 曲线。

**Returns:**
java.util.List<java.lang.Double> - 节点向量，它是一系列参数值，决定控制点在何处以及如何影响 NURBS 曲线。
### getMultiplicity() {#getMultiplicity--}
```
public List<Integer> getMultiplicity()
```


获取多重性。

**Returns:**
java.util.List<java.lang.Integer> - 多重性。
### getOrder() {#getOrder--}
```
public int getOrder()
```


获取 NURBS 曲线的阶数，它定义了影响曲线上任意点的相邻控制点的数量。

**Returns:**
int - NURBS 曲线的阶数，它定义了影响曲线上任意点的邻近控制点的数量。
### getType() {#getType--}
```
public NurbsType getType()
```


获取当前方向的类型。

**Returns:**
[NurbsType](../../com.aspose.threed/nurbstype) - the type of the current direction.
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




### setCount(int value) {#setCount-int-}
```
public void setCount(int value)
```


设置当前方向上控制点的计数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 新值 |

### setDegree(int value) {#setDegree-int-}
```
public void setDegree(int value)
```


设置 NURBS 曲线的次数，次数定义为 Order - 1

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 新值 |

### setDivisions(int value) {#setDivisions-int-}
```
public void setDivisions(int value)
```


设置当前方向相邻控制点之间的细分数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 新值 |

### setOrder(int value) {#setOrder-int-}
```
public void setOrder(int value)
```


设置 NURBS 曲线的阶数，它定义了影响曲线上任意点的相邻控制点的数量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 新值 |

### setType(NurbsType value) {#setType-com.aspose.threed.NurbsType-}
```
public void setType(NurbsType value)
```


设置当前方向的类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [NurbsType](../../com.aspose.threed/nurbstype) | 新值 |

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

