---
title: TextureFilter
second_title: Aspose.3D for Java API 레퍼런스
description: 텍스처 샘플링 중 필터 옵션.
type: docs
weight: 305
url: /ko/java/com.aspose.threed/texturefilter/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TextureFilter extends Enum<TextureFilter>
```

텍스처 샘플링 중 필터 옵션.
## 필드

| 필드 | 설명 |
| --- | --- |
| [ANISOTROPIC](#ANISOTROPIC) | 샘플링에 비등방성 보간을 사용합니다, 이는 최소화 필터에서만 사용됩니다. |
| [LINEAR](#LINEAR) | 샘플링에 선형 보간을 사용합니다 |
| [NONE](#NONE) | 최소화가 없습니다, 이는 최소화 필터에서만 사용됩니다. |
| [POINT](#POINT) | 포인트 샘플링을 사용합니다 |
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
### ANISOTROPIC {#ANISOTROPIC}
```
public static final TextureFilter ANISOTROPIC
```


샘플링에 비등방성 보간을 사용합니다, 이는 최소화 필터에서만 사용됩니다.

### LINEAR {#LINEAR}
```
public static final TextureFilter LINEAR
```


샘플링에 선형 보간을 사용합니다

### NONE {#NONE}
```
public static final TextureFilter NONE
```


최소화가 없습니다, 이는 최소화 필터에서만 사용됩니다.

### POINT {#POINT}
```
public static final TextureFilter POINT
```


포인트 샘플링을 사용합니다

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
public static TextureFilter valueOf(String name)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

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

