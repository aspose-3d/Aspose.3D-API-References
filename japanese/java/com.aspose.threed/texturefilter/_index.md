---
title: TextureFilter
second_title: Aspose.3D for Java API リファレンス
description: テクスチャサンプリング中のフィルタオプション。
type: docs
weight: 305
url: /ja/java/com.aspose.threed/texturefilter/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TextureFilter extends Enum<TextureFilter>
```

テクスチャサンプリング中のフィルタオプション。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [ANISOTROPIC](#ANISOTROPIC) | サンプリングに異方性補間を使用します。これは縮小フィルタでのみ使用されます。 |
| [LINEAR](#LINEAR) | サンプリングに線形補間を使用します |
| [NONE](#NONE) | 縮小なし、これは縮小フィルタでのみ使用されます。 |
| [POINT](#POINT) | ポイントサンプリングを使用します |
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
### ANISOTROPIC {#ANISOTROPIC}
```
public static final TextureFilter ANISOTROPIC
```


サンプリングに異方性補間を使用します。これは縮小フィルタでのみ使用されます。

### LINEAR {#LINEAR}
```
public static final TextureFilter LINEAR
```


サンプリングに線形補間を使用します

### NONE {#NONE}
```
public static final TextureFilter NONE
```


縮小なし、これは縮小フィルタでのみ使用されます。

### POINT {#POINT}
```
public static final TextureFilter POINT
```


ポイントサンプリングを使用します

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
public static TextureFilter valueOf(String name)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter)
### values() {#values--}
```
public static TextureFilter[] values()
```




**Returns:**
com.aspose.threed.TextureFilter[]
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

