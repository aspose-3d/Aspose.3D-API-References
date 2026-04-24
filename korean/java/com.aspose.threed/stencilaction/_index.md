---
title: StencilAction
second_title: Aspose.3D for Java API 레퍼런스
description: 스텐실 테스트 동작
type: docs
weight: 303
url: /ko/java/com.aspose.threed/stencilaction/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum StencilAction extends Enum<StencilAction>
```

스텐실 테스트 동작
## 필드

| 필드 | 설명 |
| --- | --- |
| [DECREMENT](#DECREMENT) | 현재 스텐실 버퍼 값을 증가시키고, 0으로 제한합니다. |
| [DECREMENT_WRAP](#DECREMENT-WRAP) | 현재 스텐실 버퍼 값을 감소시키며, 0에 도달하면 최대값으로 래핑합니다. |
| [INCREMENT](#INCREMENT) | 현재 스텐실 버퍼 값을 증가시키고, 최대값으로 제한합니다. |
| [INCREMENT_WRAP](#INCREMENT-WRAP) | 현재 스텐실 버퍼 값을 증가시키며, 최대값에 도달하면 0으로 래핑합니다. |
| [INVERT](#INVERT) | 현재 스텐실 버퍼 값을 비트 단위로 반전시킵니다. |
| [KEEP](#KEEP) | 현재 값을 유지합니다. |
| [REPLACE](#REPLACE) | 스텐실 버퍼를 [RenderState.getStencilReference](../../com.aspose.threed/renderstate\\#getStencilReference)에서 정의된 ref 값으로 설정합니다. |
| [ZERO](#ZERO) | 스텐실 버퍼 값을 0으로 설정합니다. |
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
### DECREMENT {#DECREMENT}
```
public static final StencilAction DECREMENT
```


현재 스텐실 버퍼 값을 증가시키고, 0으로 제한합니다.

### DECREMENT_WRAP {#DECREMENT-WRAP}
```
public static final StencilAction DECREMENT_WRAP
```


현재 스텐실 버퍼 값을 감소시키며, 0에 도달하면 최대값으로 래핑합니다.

### INCREMENT {#INCREMENT}
```
public static final StencilAction INCREMENT
```


현재 스텐실 버퍼 값을 증가시키고, 최대값으로 제한합니다.

### INCREMENT_WRAP {#INCREMENT-WRAP}
```
public static final StencilAction INCREMENT_WRAP
```


현재 스텐실 버퍼 값을 증가시키며, 최대값에 도달하면 0으로 래핑합니다.

### INVERT {#INVERT}
```
public static final StencilAction INVERT
```


현재 스텐실 버퍼 값을 비트 단위로 반전시킵니다.

### KEEP {#KEEP}
```
public static final StencilAction KEEP
```


현재 값을 유지합니다.

### REPLACE {#REPLACE}
```
public static final StencilAction REPLACE
```


스텐실 버퍼를 [RenderState.getStencilReference](../../com.aspose.threed/renderstate\\#getStencilReference)에서 정의된 ref 값으로 설정합니다.

### ZERO {#ZERO}
```
public static final StencilAction ZERO
```


스텐실 버퍼 값을 0으로 설정합니다.

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
public static StencilAction valueOf(String name)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction)
### values() {#values--}
```
public static StencilAction[] values()
```




**Returns:**
com.aspose.threed.StencilAction[]
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

