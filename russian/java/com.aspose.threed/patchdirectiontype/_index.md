---
title: PatchDirectionType
second_title: Справочник API Aspose.3D для Java
description: Типы направлений патча.
type: docs
weight: 287
url: /ru/java/com.aspose.threed/patchdirectiontype/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PatchDirectionType extends Enum<PatchDirectionType>
```

Типы направлений патча.
## Поля

| Поле | Описание |
| --- | --- |
|  | [BASIS_SPLINE](#BASIS-SPLINE) | [Направление патча — базисный сплайн.][] |


[The patch direction is a basis spline.]: https://en.wikipedia.org/wiki/B-spline |
|  | [BEZIER](#BEZIER) | [Направление патча — кривая Безье.][] |


[The patch direction is a Bezier curve.]: https://en.wikipedia.org/wiki/B%C3%A9zier_curve |
| [CARDINAL_SPLINE](#CARDINAL-SPLINE) | кардинальный патч. |
|  | [LINEAR](#LINEAR) | [Направление патча — линейная кривая.][] |


[The patch direction is a linear curve.]: https://en.wikipedia.org/wiki/B%C3%A9zier_curve#Linear_curves |
| [QUADRATIC_BEZIER](#QUADRATIC-BEZIER) | Квадратический патч Безье. |
## Методы

| Метод | Описание |
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


кардинальный патч. [Направление патча — кардинальный сплайн.][]


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


Квадратический патч Безье. [Направление патча — квадратичная кривая.][]


[The patch direction is a quadratic curve.]: https://en.wikipedia.org/wiki/B%C3%A9zier_curve#Quadratic_curves

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
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
| Параметр | Тип | Описание |
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
| Параметр | Тип | Описание |
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
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String |  |

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

