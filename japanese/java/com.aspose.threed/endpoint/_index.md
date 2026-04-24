---
title: EndPoint
second_title: Aspose.3D for Java API リファレンス
description: 曲線をトリムするエンドポイントは、パラメータ値またはデカルト座標点のいずれかにできます。
type: docs
weight: 51
url: /ja/java/com.aspose.threed/endpoint/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class EndPoint implements Struct<EndPoint>, Serializable
```

曲線をトリムする終点で、パラメータ値またはデカルト座標点のいずれかにできます。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [EndPoint(Vector3 point)](#EndPoint-com.aspose.threed.Vector3-) | デカルト座標点から [EndPoint](../../com.aspose.threed/endpoint) を構築します。 |
| [EndPoint(double v)](#EndPoint-double-) | 実数パラメータから [EndPoint](../../com.aspose.threed/endpoint) を構築します。 |
| [EndPoint()](#EndPoint--) |  |
## Methods

| Method | 説明 |
| --- | --- |
| [clone()](#clone--) |  |
| [copyFrom(EndPoint src)](#copyFrom-com.aspose.threed.EndPoint-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromDegree(double degree)](#fromDegree-double-) | 度単位で測定されたエンドポイントを作成します。 |
| [fromRadian(double degree)](#fromRadian-double-) | ラジアン単位で測定されたエンドポイントを作成します。 |
| [getAsPoint()](#getAsPoint--) | エンドポイントをデカルト座標点として取得します。例外がスローされることがあります。 |
| [getAsValue()](#getAsValue--) | エンドポイントを実数パラメータとして取得します。例外がスローされます。 |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [isCartesianPoint()](#isCartesianPoint--) | エンドポイントはデカルト座標点ですか？ |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | 現在のエンドポイントの文字列表現を返します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EndPoint(Vector3 point) {#EndPoint-com.aspose.threed.Vector3-}
```
public EndPoint(Vector3 point)
```


デカルト座標点から [EndPoint](../../com.aspose.threed/endpoint) を構築します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| point | [Vector3](../../com.aspose.threed/vector3) | 構築するポイント |

### EndPoint(double v) {#EndPoint-double-}
```
public EndPoint(double v)
```


実数パラメータから [EndPoint](../../com.aspose.threed/endpoint) を構築します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| v | double | エンドポイントを構築するための実数パラメータ |

### EndPoint() {#EndPoint--}
```
public EndPoint()
```


### clone() {#clone--}
```
public EndPoint clone()
```


現在のインスタンスをクローンする

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint)
### copyFrom(EndPoint src) {#copyFrom-com.aspose.threed.EndPoint-}
```
public void copyFrom(EndPoint src)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| src | [EndPoint](../../com.aspose.threed/endpoint) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromDegree(double degree) {#fromDegree-double-}
```
public static EndPoint fromDegree(double degree)
```


度単位で測定されたエンドポイントを作成します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 度 | double | 度単位の値 |

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint) - An end point constructed from degree
### fromRadian(double degree) {#fromRadian-double-}
```
public static EndPoint fromRadian(double degree)
```


ラジアン単位で測定されたエンドポイントを作成します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 度 | double | ラジアン単位の値 |

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint) - An end point constructed from radian
### getAsPoint() {#getAsPoint--}
```
public Vector3 getAsPoint()
```


エンドポイントをデカルト座標点として取得します。例外がスローされることがあります。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the end point as Cartesian point, or thrown an exception.
### getAsValue() {#getAsValue--}
```
public double getAsValue()
```


エンドポイントを実数パラメータとして取得します。例外がスローされます。

**Returns:**
double - エンドポイントを実数パラメータとして取得、または例外をスローします。
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


エンドポイントはデカルト座標点ですか？

**Returns:**
boolean - エンドポイントはデカルト座標点ですか？
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


現在のエンドポイントの文字列表現を返します。

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

