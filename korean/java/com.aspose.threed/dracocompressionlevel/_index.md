---
title: DracoCompressionLevel
second_title: Aspose.3D for Java API 레퍼런스
description: 드라코 파일의 압축 수준
type: docs
weight: 276
url: /ko/java/com.aspose.threed/dracocompressionlevel/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DracoCompressionLevel extends Enum<DracoCompressionLevel>
```

드라코 파일의 압축 수준
## 필드

| 필드 | 설명 |
| --- | --- |
| [FAST](#FAST) | Encoder는 가능한 한 빠르게 압축을 수행합니다. |
| [NO_COMPRESSION](#NO-COMPRESSION) | 압축 없음, 이는 최소 인코딩 시간을 초래합니다. |
| [OPTIMAL](#OPTIMAL) | Encoder는 장면을 최적화하여 압축하며, 완료하는 데 더 오래 걸릴 수 있습니다. |
| [STANDARD](#STANDARD) | 표준 모드, 좋은 압축률과 속도를 제공합니다. |
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
### FAST {#FAST}
```
public static final DracoCompressionLevel FAST
```


Encoder는 가능한 한 빠르게 압축을 수행합니다.

### NO_COMPRESSION {#NO-COMPRESSION}
```
public static final DracoCompressionLevel NO_COMPRESSION
```


압축 없음, 이는 최소 인코딩 시간을 초래합니다.

### OPTIMAL {#OPTIMAL}
```
public static final DracoCompressionLevel OPTIMAL
```


Encoder는 장면을 최적화하여 압축하며, 완료하는 데 더 오래 걸릴 수 있습니다.

### STANDARD {#STANDARD}
```
public static final DracoCompressionLevel STANDARD
```


표준 모드, 좋은 압축률과 속도를 제공합니다.

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
public static DracoCompressionLevel valueOf(String name)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

**Returns:**
[DracoCompressionLevel](../../com.aspose.threed/dracocompressionlevel)
### values() {#values--}
```
public static DracoCompressionLevel[] values()
```




**Returns:**
com.aspose.threed.DracoCompressionLevel[]
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

