---
title: 補間
second_title: Aspose.3D for Java API リファレンス
description: キーフレームの補間タイプです。
type: docs
weight: 283
url: /ja/java/com.aspose.threed/interpolation/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Interpolation extends Enum<Interpolation>
```

キーフレームの補間タイプ。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [BEZIER](#BEZIER) | ベジエまたはエルミートスプラインです。 |
| [B_SPLINE](#B-SPLINE) | 基底スプラインは一連の制御点で定義され、曲線は最初と最後の点のみを必ず通過することが保証されています。 |
| [CARDINAL_SPLINE](#CARDINAL-SPLINE) | カーディナルスプラインは、エンドポイントと張力パラメータによって接線が定義される立方体エルミートスプラインです。 |
| [CONSTANT](#CONSTANT) | 次のセグメントまで、値は最初の点の値に対して一定のままになります。 |
| [LINEAR](#LINEAR) | 線形補間は、二つの点間の直線です。 |
| [TCB_SPLINE](#TCB-SPLINE) | コーハネック‑バーテルススプラインとも呼ばれ、接線の挙動は張力/バイアス/連続性によって定義されます。 |
## Methods

| Method | 説明 |
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
### BEZIER {#BEZIER}
```
public static final Interpolation BEZIER
```


ベジエまたはエルミートスプラインです。

### B_SPLINE {#B-SPLINE}
```
public static final Interpolation B_SPLINE
```


基底スプラインは一連の制御点で定義され、曲線は最初と最後の点のみを必ず通過することが保証されています。

### CARDINAL_SPLINE {#CARDINAL-SPLINE}
```
public static final Interpolation CARDINAL_SPLINE
```


カーディナルスプラインは、エンドポイントと張力パラメータによって接線が定義される立方体エルミートスプラインです。

### CONSTANT {#CONSTANT}
```
public static final Interpolation CONSTANT
```


次のセグメントまで、値は最初の点の値に対して一定のままになります。

### LINEAR {#LINEAR}
```
public static final Interpolation LINEAR
```


線形補間は、二つの点間の直線です。

### TCB_SPLINE {#TCB-SPLINE}
```
public static final Interpolation TCB_SPLINE
```


コーハネック‑バーテルススプラインとも呼ばれ、接線の挙動は張力/バイアス/連続性によって定義されます。

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | 説明 |
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
| Parameter | Type | 説明 |
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
public static Interpolation valueOf(String name)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[Interpolation](../../com.aspose.threed/interpolation)
### values() {#values--}
```
public static Interpolation[] values()
```




**Returns:**
com.aspose.threed.Interpolation[]
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

