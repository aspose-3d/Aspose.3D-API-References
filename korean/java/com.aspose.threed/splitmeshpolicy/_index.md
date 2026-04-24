---
title: SplitMeshPolicy
second_title: Aspose.3D for Java API 레퍼런스
description: 서브 메쉬 간에 정점/제어점 데이터를 공유하거나 각 서브 메쉬가 자체 압축 데이터를 가집니다.
type: docs
weight: 302
url: /ko/java/com.aspose.threed/splitmeshpolicy/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum SplitMeshPolicy extends Enum<SplitMeshPolicy>
```

서브 메쉬 간에 정점/제어점 데이터를 공유하거나 각 서브 메쉬가 자체 압축 데이터를 가집니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [CLONE_DATA](#CLONE-DATA) | 제어점 및 정점 요소 데이터가 복제됩니다. |
| [COMPACT_DATA](#COMPACT-DATA) | 사용된 제어점 및 정점 요소 데이터만 서브 메시에 복사됩니다. |
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
### CLONE_DATA {#CLONE-DATA}
```
public static final SplitMeshPolicy CLONE_DATA
```


제어점 및 정점 요소 데이터가 복제됩니다.

### COMPACT_DATA {#COMPACT-DATA}
```
public static final SplitMeshPolicy COMPACT_DATA
```


사용된 제어점 및 정점 요소 데이터만 서브 메시에 복사됩니다.

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
public static SplitMeshPolicy valueOf(String name)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

**Returns:**
[SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy)
### values() {#values--}
```
public static SplitMeshPolicy[] values()
```




**Returns:**
com.aspose.threed.SplitMeshPolicy[]
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

