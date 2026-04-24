---
title: PatchDirectionType
second_title: Aspose.3D for Java API 레퍼런스
description: 패치 방향 유형들.
type: docs
weight: 287
url: /ko/java/com.aspose.threed/patchdirectiontype/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PatchDirectionType extends Enum<PatchDirectionType>
```

패치 방향 유형.
## 필드

| 필드 | 설명 |
| --- | --- |
|  | [BASIS_SPLINE](#BASIS-SPLINE) | [패치 방향은 베이시스 스플라인입니다.][] |


[The patch direction is a basis spline.]: https://en.wikipedia.org/wiki/B-spline |
|  | [BEZIER](#BEZIER) | [패치 방향은 베지어 곡선입니다.][] |


[The patch direction is a Bezier curve.]: https://en.wikipedia.org/wiki/B%C3%A9zier_curve |
| [CARDINAL_SPLINE](#CARDINAL-SPLINE) | 카디널 패치. |
|  | [LINEAR](#LINEAR) | [패치 방향은 선형 곡선입니다.][] |


[The patch direction is a linear curve.]: https://en.wikipedia.org/wiki/B%C3%A9zier_curve#Linear_curves |
| [QUADRATIC_BEZIER](#QUADRATIC-BEZIER) | 이차 베지어 패치. |
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
### BASIS_SPLINE {#BASIS-SPLINE}
```
public static final PatchDirectionType BASIS_SPLINE
```


[The patch direction is a basis spline.][]


[The patch direction is a basis spline.]: https://en.wikipedia.org/wiki/B-spline

### BEZIER {#BEZIER}
```
public static final PatchDirectionType BEZIER
```


[The patch direction is a Bezier curve.][]


[The patch direction is a Bezier curve.]: https://en.wikipedia.org/wiki/B%C3%A9zier_curve

### CARDINAL_SPLINE {#CARDINAL-SPLINE}
```
public static final PatchDirectionType CARDINAL_SPLINE
```


카디널 패치. [패치 방향은 카디널 스플라인입니다.][]


[The patch direction is a cardinal spline.]: https://en.wikipedia.org/wiki/Cubic_Hermite_spline#Cardinal_spline

### LINEAR {#LINEAR}
```
public static final PatchDirectionType LINEAR
```


[The patch direction is a linear curve.][]


[The patch direction is a linear curve.]: https://en.wikipedia.org/wiki/B%C3%A9zier_curve#Linear_curves

### QUADRATIC_BEZIER {#QUADRATIC-BEZIER}
```
public static final PatchDirectionType QUADRATIC_BEZIER
```


이차 베지어 패치. [패치 방향은 이차 곡선입니다.][]


[The patch direction is a quadratic curve.]: https://en.wikipedia.org/wiki/B%C3%A9zier_curve#Quadratic_curves

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
public static PatchDirectionType valueOf(String name)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

**Returns:**
[PatchDirectionType](../../com.aspose.threed/patchdirectiontype)
### values() {#values--}
```
public static PatchDirectionType[] values()
```




**Returns:**
com.aspose.threed.PatchDirectionType[]
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

