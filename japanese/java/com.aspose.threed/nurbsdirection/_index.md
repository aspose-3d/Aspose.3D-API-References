---
title: NurbsDirection
second_title: Aspose.3D for Java API リファレンス
description: 3D には 2 つの方向があり、 と がそれぞれの方向のデータを定義します。
type: docs
weight: 113
url: /ja/java/com.aspose.threed/nurbsdirection/
---

**Inheritance:**
java.lang.Object
```
public class NurbsDirection
```

3D [NurbsSurface](../../com.aspose.threed/nurbssurface) には 2 つの方向があり、[NurbsSurface.getU](../../com.aspose.threed/nurbssurface\#getU) と [NurbsSurface.getV](../../com.aspose.threed/nurbssurface\#getV) がそれぞれの方向を表します。[NurbsDirection](../../com.aspose.threed/nurbsdirection) は各方向のデータを定義します。方向は実際には NURBS 曲線であり、[getOrder](../../com.aspose.threed/nurbsdirection\#getOrder)、[getKnotVectors](../../com.aspose.threed/nurbsdirection\#getKnotVectors)、および [NurbsSurface](../../com.aspose.threed/nurbssurface) で定義される加重制御点の集合によっても定義されます。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [NurbsDirection()](#NurbsDirection--) | [NurbsDirection](../../com.aspose.threed/nurbsdirection) の新しいインスタンスを作成します |
## Methods

| Method | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | 現在の方向における制御点の数を取得します。 |
| [getDegree()](#getDegree--) | NURBS 曲線の次数を取得します。次数は Order - 1 と定義されます |
| [getDivisions()](#getDivisions--) | 現在の方向で隣接する制御点間の分割数を取得します。 |
| [getKnotVectors()](#getKnotVectors--) | ノットベクトルを取得します。これはパラメータ値のシーケンスで、制御点が NURBS 曲線にどのように影響するかを決定します |
| [getMultiplicity()](#getMultiplicity--) | 多重度を取得します。 |
| [getOrder()](#getOrder--) | NURBS 曲線のオーダーを取得します。これは曲線上の任意の点に影響を与える近傍の制御点の数を定義します |
| [getType()](#getType--) | 現在の方向のタイプを取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCount(int value)](#setCount-int-) | 現在の方向における制御点の数を設定します。 |
| [setDegree(int value)](#setDegree-int-) | NURBS 曲線の次数を設定します。次数は Order - 1 と定義されます |
| [setDivisions(int value)](#setDivisions-int-) | 現在の方向で隣接する制御点間の分割数を設定します。 |
| [setOrder(int value)](#setOrder-int-) | NURBS 曲線のオーダーを設定します。これは曲線上の任意の点に影響を与える近傍の制御点の数を定義します |
| [setType(NurbsType value)](#setType-com.aspose.threed.NurbsType-) | 現在の方向のタイプを設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NurbsDirection() {#NurbsDirection--}
```
public NurbsDirection()
```


[NurbsDirection](../../com.aspose.threed/nurbsdirection) の新しいインスタンスを作成します

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
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


現在の方向における制御点の数を取得します。

**Returns:**
int - 現在の方向における制御点の数。
### getDegree() {#getDegree--}
```
public int getDegree()
```


NURBS 曲線の次数を取得します。次数は Order - 1 と定義されます

**Returns:**
int - NURBS 曲線の次数、次数は Order - 1 と定義されます
### getDivisions() {#getDivisions--}
```
public int getDivisions()
```


現在の方向で隣接する制御点間の分割数を取得します。

**Returns:**
int - 現在の方向で隣接する制御点間の分割数です。
### getKnotVectors() {#getKnotVectors--}
```
public List<Double> getKnotVectors()
```


ノットベクトルを取得します。これはパラメータ値のシーケンスで、制御点が NURBS 曲線にどのように影響するかを決定します

**Returns:**
java.util.List<java.lang.Double> - ノットベクトルです。これはパラメータ値のシーケンスで、制御点が NURBS 曲線にどのように影響するかを決定します
### getMultiplicity() {#getMultiplicity--}
```
public List<Integer> getMultiplicity()
```


多重度を取得します。

**Returns:**
java.util.List<java.lang.Integer> - 多重度。
### getOrder() {#getOrder--}
```
public int getOrder()
```


NURBS 曲線のオーダーを取得します。これは曲線上の任意の点に影響を与える近傍の制御点の数を定義します

**Returns:**
int - NURBS 曲線の次数で、曲線上の任意の点に影響を与える近傍の制御点の数を定義します。
### getType() {#getType--}
```
public NurbsType getType()
```


現在の方向のタイプを取得します。

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


現在の方向における制御点の数を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | int | 新しい値 |

### setDegree(int value) {#setDegree-int-}
```
public void setDegree(int value)
```


NURBS 曲線の次数を設定します。次数は Order - 1 と定義されます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | int | 新しい値 |

### setDivisions(int value) {#setDivisions-int-}
```
public void setDivisions(int value)
```


現在の方向で隣接する制御点間の分割数を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | int | 新しい値 |

### setOrder(int value) {#setOrder-int-}
```
public void setOrder(int value)
```


NURBS 曲線のオーダーを設定します。これは曲線上の任意の点に影響を与える近傍の制御点の数を定義します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | int | 新しい値 |

### setType(NurbsType value) {#setType-com.aspose.threed.NurbsType-}
```
public void setType(NurbsType value)
```


現在の方向のタイプを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [NurbsType](../../com.aspose.threed/nurbstype) | 新しい値 |

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
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

