---
title: CompareFunction
second_title: Aspose.3D for Java API リファレンス
description: 深度/ステンシルテストで使用される比較関数。
type: docs
weight: 271
url: /ja/java/com.aspose.threed/comparefunction/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum CompareFunction extends Enum<CompareFunction>
```

深度/ステンシルテストで使用される比較関数。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [ALWAYS](#ALWAYS) | 常に合格 |
| [EQUAL](#EQUAL) | 受信した値が保存された値と等しい場合に合格します。 |
| [GREATER](#GREATER) | 受信した値が保存された値より大きい場合に合格します。 |
| [G_EQUAL](#G-EQUAL) | 受信した値が保存された値以上の場合に合格します。 |
| [LESS](#LESS) | 受信した値が保存された値より小さい場合に合格します。 |
| [L_EQUAL](#L-EQUAL) | 受信した値が保存された値以下の場合に合格します。 |
| [NEVER](#NEVER) | 合格しません |
| [NOT_EQUAL](#NOT-EQUAL) | 受信した値が保存された値と等しくない場合に合格します。 |
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
### ALWAYS {#ALWAYS}
```
public static final CompareFunction ALWAYS
```


常に合格

### EQUAL {#EQUAL}
```
public static final CompareFunction EQUAL
```


受信した値が保存された値と等しい場合に合格します。

### GREATER {#GREATER}
```
public static final CompareFunction GREATER
```


受信した値が保存された値より大きい場合に合格します。

### G_EQUAL {#G-EQUAL}
```
public static final CompareFunction G_EQUAL
```


受信した値が保存された値以上の場合に合格します。

### LESS {#LESS}
```
public static final CompareFunction LESS
```


受信した値が保存された値より小さい場合に合格します。

### L_EQUAL {#L-EQUAL}
```
public static final CompareFunction L_EQUAL
```


受信した値が保存された値以下の場合に合格します。

### NEVER {#NEVER}
```
public static final CompareFunction NEVER
```


合格しません

### NOT_EQUAL {#NOT-EQUAL}
```
public static final CompareFunction NOT_EQUAL
```


受信した値が保存された値と等しくない場合に合格します。

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
public static CompareFunction valueOf(String name)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[CompareFunction](../../com.aspose.threed/comparefunction)
### values() {#values--}
```
public static CompareFunction[] values()
```




**Returns:**
com.aspose.threed.CompareFunction[]
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

