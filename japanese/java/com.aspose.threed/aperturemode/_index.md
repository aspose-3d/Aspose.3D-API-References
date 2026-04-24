---
title: ApertureMode
second_title: Aspose.3D for Java API リファレンス
description: カメラ絞りモード。
type: docs
weight: 264
url: /ja/java/com.aspose.threed/aperturemode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ApertureMode extends Enum<ApertureMode>
```

カメラの絞りモードです。絞りモードはどの値がカメラの絞りを制御するかを決定します。絞りモードが HorizAndVert、Horizontal、または Vertical の場合、視野角が使用されます。絞りモードが FocalLength の場合、焦点距離が使用されます。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [FOCAL_LENGTH](#FOCAL-LENGTH) | 焦点距離を直接使用します。 |
| [HORIZONTAL](#HORIZONTAL) | 水平角のみを設定します。 |
| [HORIZ_AND_VERT](#HORIZ-AND-VERT) | 水平と垂直の設定の両方の角度値を設定します。 |
| [VERTICAL](#VERTICAL) | 垂直角のみを設定します。 |
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
### FOCAL_LENGTH {#FOCAL-LENGTH}
```
public static final ApertureMode FOCAL_LENGTH
```


焦点距離を直接使用します。

### HORIZONTAL {#HORIZONTAL}
```
public static final ApertureMode HORIZONTAL
```


水平角のみを設定します。

### HORIZ_AND_VERT {#HORIZ-AND-VERT}
```
public static final ApertureMode HORIZ_AND_VERT
```


水平と垂直の設定の両方の角度値を設定します。

### VERTICAL {#VERTICAL}
```
public static final ApertureMode VERTICAL
```


垂直角のみを設定します。

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
public static ApertureMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[ApertureMode](../../com.aspose.threed/aperturemode)
### values() {#values--}
```
public static ApertureMode[] values()
```




**Returns:**
com.aspose.threed.ApertureMode[]
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

