---
title: AlphaSource
second_title: Aspose.3D for Java API 레퍼런스
description: 텍스처에 알파 채널이 포함되어 있는지 정의합니다.
type: docs
weight: 263
url: /ko/java/com.aspose.threed/alphasource/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum AlphaSource extends Enum<AlphaSource>
```

텍스처에 알파 채널이 포함되어 있는지 정의합니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [FIXED_VALUE](#FIXED-VALUE) | Alpha는 [TextureBase.getAlpha](../../com.aspose.threed/texturebase\#getAlpha)에 의해 정의되는 고정값입니다. |
| [NONE](#NONE) | 텍스처에 알파가 정의되어 있지 않습니다. |
| [PIXEL_ALPHA](#PIXEL-ALPHA) | 알파는 픽셀의 알파 채널에 의해 정의됩니다. |
## 메서드

| 메서드 | 설명 |
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
### FIXED_VALUE {#FIXED-VALUE}
```
public static final AlphaSource FIXED_VALUE
```


Alpha는 [TextureBase.getAlpha](../../com.aspose.threed/texturebase\#getAlpha)에 의해 정의되는 고정값입니다.

### NONE {#NONE}
```
public static final AlphaSource NONE
```


텍스처에 알파가 정의되어 있지 않습니다.

### PIXEL_ALPHA {#PIXEL-ALPHA}
```
public static final AlphaSource PIXEL_ALPHA
```


알파는 픽셀의 알파 채널에 의해 정의됩니다.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
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
| 매개변수 | 형식 | 설명 |
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
| 매개변수 | 형식 | 설명 |
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
public static AlphaSource valueOf(String name)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

**Returns:**
[AlphaSource](../../com.aspose.threed/alphasource)
### values() {#values--}
```
public static AlphaSource[] values()
```




**Returns:**
com.aspose.threed.AlphaSource[]
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

