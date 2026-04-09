---
title: ExtrapolationType
second_title: Aspose.3D for Java API リファレンス
description: 外挿タイプ。
type: docs
weight: 278
url: /ja/java/com.aspose.threed/extrapolationtype/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ExtrapolationType extends Enum<ExtrapolationType>
```

外挿タイプ。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [CONSTANT](#CONSTANT) | 値は前回の値と同じまま保持されます |
| [CYCLE](#CYCLE) | 繰り返し。 |
| [CYCLE_RELATIVE](#CYCLE-RELATIVE) | 前のパターンを前回の値に基づいて繰り返します |
| [GRADIENT](#GRADIENT) | 値は時間に対して同じ傾きを保ちます |
| [OSCILLATE](#OSCILLATE) | 鏡像の繰り返し。 |
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
### CONSTANT {#CONSTANT}
```
public static final ExtrapolationType CONSTANT
```


値は前回の値と同じまま保持されます

### CYCLE {#CYCLE}
```
public static final ExtrapolationType CYCLE
```


繰り返し。

### CYCLE_RELATIVE {#CYCLE-RELATIVE}
```
public static final ExtrapolationType CYCLE_RELATIVE
```


前のパターンを前回の値に基づいて繰り返します

### GRADIENT {#GRADIENT}
```
public static final ExtrapolationType GRADIENT
```


値は時間に対して同じ傾きを保ちます

### OSCILLATE {#OSCILLATE}
```
public static final ExtrapolationType OSCILLATE
```


鏡像の繰り返し。

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
public static ExtrapolationType valueOf(String name)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[ExtrapolationType](../../com.aspose.threed/extrapolationtype)
### values() {#values--}
```
public static ExtrapolationType[] values()
```




**Returns:**
com.aspose.threed.ExtrapolationType[]
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

