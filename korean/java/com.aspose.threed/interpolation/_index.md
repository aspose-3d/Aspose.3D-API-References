---
title: 보간
second_title: Aspose.3D for Java API 레퍼런스
description: 키 프레임 보간 유형입니다.
type: docs
weight: 283
url: /ko/java/com.aspose.threed/interpolation/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Interpolation extends Enum<Interpolation>
```

키 프레임의 보간 유형.
## 필드

| 필드 | 설명 |
| --- | --- |
| [BEZIER](#BEZIER) | 베지어 또는 헤르미트 스플라인. |
| [B_SPLINE](#B-SPLINE) | 베이시스 스플라인은 일련의 제어점으로 정의되며, 곡선은 첫 번째와 마지막 점을 통과하도록 보장됩니다. |
| [CARDINAL_SPLINE](#CARDINAL-SPLINE) | 카디널 스플라인은 끝점과 장력 매개변수에 의해 접선이 정의되는 3차 Hermite 스플라인입니다. |
| [CONSTANT](#CONSTANT) | 값은 다음 구간이 시작될 때까지 첫 번째 점의 값에 계속 고정됩니다. |
| [LINEAR](#LINEAR) | 선형 보간은 두 점 사이의 직선입니다. |
| [TCB_SPLINE](#TCB-SPLINE) | Kochanek-Bartels 스플라인이라고도 하며, 접선의 동작은 장력/바이어스/연속성에 의해 정의됩니다. |
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
### BEZIER {#BEZIER}
```
public static final Interpolation BEZIER
```


베지어 또는 헤르미트 스플라인.

### B_SPLINE {#B-SPLINE}
```
public static final Interpolation B_SPLINE
```


베이시스 스플라인은 일련의 제어점으로 정의되며, 곡선은 첫 번째와 마지막 점을 통과하도록 보장됩니다.

### CARDINAL_SPLINE {#CARDINAL-SPLINE}
```
public static final Interpolation CARDINAL_SPLINE
```


카디널 스플라인은 끝점과 장력 매개변수에 의해 접선이 정의되는 3차 Hermite 스플라인입니다.

### CONSTANT {#CONSTANT}
```
public static final Interpolation CONSTANT
```


값은 다음 구간이 시작될 때까지 첫 번째 점의 값에 계속 고정됩니다.

### LINEAR {#LINEAR}
```
public static final Interpolation LINEAR
```


선형 보간은 두 점 사이의 직선입니다.

### TCB_SPLINE {#TCB-SPLINE}
```
public static final Interpolation TCB_SPLINE
```


Kochanek-Bartels 스플라인이라고도 하며, 접선의 동작은 장력/바이어스/연속성에 의해 정의됩니다.

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
public static Interpolation valueOf(String name)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

**Returns:**
[Interpolation](../../com.aspose.threed/interpolation)
### values() {#values--}
```
public static Interpolation[] values()
```




**Returns:**
com.aspose.threed.Interpolation[]
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

