---
title: BoneLinkMode
second_title: Aspose.3D for Java API 레퍼런스
description: BoneLinkMode는 뼈가 계층 구조 내에서 부모 뼈와 연결되거나 연결되는 방식을 나타냅니다.
type: docs
weight: 267
url: /ko/java/com.aspose.threed/bonelinkmode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum BoneLinkMode extends Enum<BoneLinkMode>
```

뼈대의 연결 모드는 계층 구조 내에서 뼈가 부모 뼈와 연결되거나 링크되는 방식을 나타냅니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [ADDITIVE](#ADDITIVE) | Additive 모드는 자식 뼈의 변환을 해당 로컬 변환을 부모 뼈의 변환에 추가하여 계산합니다. |
| [NORMALIZE](#NORMALIZE) | 이 모드에서는 자식 뼈의 변환이 부모 뼈의 변환에 대해 정규화됩니다. |
| [TOTAL_ONE](#TOTAL-ONE) | Total One은 부모와 자식 뼈의 결합된 변환이 전체 길이가 1 단위가 되도록 스케일되는 결합 변환을 보장합니다. |
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
### ADDITIVE {#ADDITIVE}
```
public static final BoneLinkMode ADDITIVE
```


Additive 모드는 자식 뼈의 변환을 해당 로컬 변환을 부모 뼈의 변환에 추가하여 계산합니다.

### NORMALIZE {#NORMALIZE}
```
public static final BoneLinkMode NORMALIZE
```


이 모드에서는 자식 뼈의 변환이 부모 뼈의 변환에 대해 정규화됩니다.

### TOTAL_ONE {#TOTAL-ONE}
```
public static final BoneLinkMode TOTAL_ONE
```


Total One은 부모와 자식 뼈의 결합된 변환이 전체 길이가 1 단위가 되도록 스케일되는 결합 변환을 보장합니다.

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
public static BoneLinkMode valueOf(String name)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

**Returns:**
[BoneLinkMode](../../com.aspose.threed/bonelinkmode)
### values() {#values--}
```
public static BoneLinkMode[] values()
```




**Returns:**
com.aspose.threed.BoneLinkMode[]
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

