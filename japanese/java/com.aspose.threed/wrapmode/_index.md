---
title: WrapMode
second_title: Aspose.3D for Java API リファレンス
description: テクスチャのラップモード。
type: docs
weight: 310
url: /ja/java/com.aspose.threed/wrapmode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum WrapMode extends Enum<WrapMode>
```

テクスチャのラップモード。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [BORDER](#BORDER) | 範囲 [0.0, 1.0] の外にある座標は、指定された境界色に設定されます。 |
| [CLAMP](#CLAMP) | テクスチャを境界の最後のピクセルにクランプします。 |
| [MIRROR](#MIRROR) | テクスチャは繰り返されますが、座標の整数部分が奇数の場合は鏡像になります。 |
| [MIRROR_ONCE](#MIRROR-ONCE) | テクスチャは一度鏡像になり、その後最大値にクランプされます。 |
| [WRAP](#WRAP) | テクスチャをモデルの表面にタイル状に配置し、繰り返しパターンを作成します。 |
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
### BORDER {#BORDER}
```
public static final WrapMode BORDER
```


範囲 [0.0, 1.0] の外にある座標は、指定された境界色に設定されます。

### CLAMP {#CLAMP}
```
public static final WrapMode CLAMP
```


テクスチャを境界の最後のピクセルにクランプします。

### MIRROR {#MIRROR}
```
public static final WrapMode MIRROR
```


テクスチャは繰り返されますが、座標の整数部分が奇数の場合は鏡像になります。

### MIRROR_ONCE {#MIRROR-ONCE}
```
public static final WrapMode MIRROR_ONCE
```


テクスチャは一度鏡像になり、その後最大値にクランプされます。

### WRAP {#WRAP}
```
public static final WrapMode WRAP
```


テクスチャをモデルの表面にタイル状に配置し、繰り返しパターンを作成します。

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
public static WrapMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode)
### values() {#values--}
```
public static WrapMode[] values()
```




**Returns:**
com.aspose.threed.WrapMode[]
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

