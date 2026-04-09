---
title: CompareFunction
second_title: Aspose.3D for Java API 레퍼런스
description: 깊이/스텐실 테스트에 사용되는 비교 함수.
type: docs
weight: 271
url: /ko/java/com.aspose.threed/comparefunction/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum CompareFunction extends Enum<CompareFunction>
```

깊이/스텐실 테스트에 사용되는 비교 함수.
## 필드

| 필드 | 설명 |
| --- | --- |
| [ALWAYS](#ALWAYS) | 항상 통과합니다 |
| [EQUAL](#EQUAL) | 입력 값이 저장된 값과 같으면 통과합니다. |
| [GREATER](#GREATER) | 입력 값이 저장된 값보다 크면 통과합니다. |
| [G_EQUAL](#G-EQUAL) | 입력 값이 저장된 값보다 크거나 같으면 통과합니다. |
| [LESS](#LESS) | 입력 값이 저장된 값보다 작으면 통과합니다. |
| [L_EQUAL](#L-EQUAL) | 입력 값이 저장된 값보다 작거나 같으면 통과합니다. |
| [NEVER](#NEVER) | 절대 통과하지 않습니다 |
| [NOT_EQUAL](#NOT-EQUAL) | 입력 값이 저장된 값과 다르면 통과합니다. |
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
### ALWAYS {#ALWAYS}
```
public static final CompareFunction ALWAYS
```


항상 통과합니다

### EQUAL {#EQUAL}
```
public static final CompareFunction EQUAL
```


입력 값이 저장된 값과 같으면 통과합니다.

### GREATER {#GREATER}
```
public static final CompareFunction GREATER
```


입력 값이 저장된 값보다 크면 통과합니다.

### G_EQUAL {#G-EQUAL}
```
public static final CompareFunction G_EQUAL
```


입력 값이 저장된 값보다 크거나 같으면 통과합니다.

### LESS {#LESS}
```
public static final CompareFunction LESS
```


입력 값이 저장된 값보다 작으면 통과합니다.

### L_EQUAL {#L-EQUAL}
```
public static final CompareFunction L_EQUAL
```


입력 값이 저장된 값보다 작거나 같으면 통과합니다.

### NEVER {#NEVER}
```
public static final CompareFunction NEVER
```


절대 통과하지 않습니다

### NOT_EQUAL {#NOT-EQUAL}
```
public static final CompareFunction NOT_EQUAL
```


입력 값이 저장된 값과 다르면 통과합니다.

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
public static CompareFunction valueOf(String name)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

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

