---
title: Интерполяция
second_title: Справочник API Aspose.3D для Java
description: Тип интерполяции ключевых кадров.
type: docs
weight: 283
url: /ru/java/com.aspose.threed/interpolation/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Interpolation extends Enum<Interpolation>
```

Тип интерполяции ключевого кадра.
## Поля

| Поле | Описание |
| --- | --- |
| [BEZIER](#BEZIER) | Кривая Безье или сплайн Эрмита. |
| [B_SPLINE](#B-SPLINE) | Базисные сплайны определяются набором контрольных точек, при этом кривая гарантированно проходит только через первую и последнюю точку. |
| [CARDINAL_SPLINE](#CARDINAL-SPLINE) | Кардинальный сплайн — это кубический сплайн Гермица, тангенты которого определяются конечными точками и параметром натяжения. |
| [CONSTANT](#CONSTANT) | Значение будет оставаться постоянным, равным значению первой точки, до следующего сегмента. |
| [LINEAR](#LINEAR) | Линейная интерполяция — это прямая линия между двумя точками. |
| [TCB_SPLINE](#TCB-SPLINE) | Также называется сплайн Коханека-Бартелса, поведение тангента определяется параметрами натяжения/смещения/непрерывности |
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
### BEZIER {#BEZIER}
```
public static final Interpolation BEZIER
```


Кривая Безье или сплайн Эрмита.

### B_SPLINE {#B-SPLINE}
```
public static final Interpolation B_SPLINE
```


Базисные сплайны определяются набором контрольных точек, при этом кривая гарантированно проходит только через первую и последнюю точку.

### CARDINAL_SPLINE {#CARDINAL-SPLINE}
```
public static final Interpolation CARDINAL_SPLINE
```


Кардинальный сплайн — это кубический сплайн Гермица, тангенты которого определяются конечными точками и параметром натяжения.

### CONSTANT {#CONSTANT}
```
public static final Interpolation CONSTANT
```


Значение будет оставаться постоянным, равным значению первой точки, до следующего сегмента.

### LINEAR {#LINEAR}
```
public static final Interpolation LINEAR
```


Линейная интерполяция — это прямая линия между двумя точками.

### TCB_SPLINE {#TCB-SPLINE}
```
public static final Interpolation TCB_SPLINE
```


Также называется сплайн Коханека-Бартелса, поведение тангента определяется параметрами натяжения/смещения/непрерывности

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
public static Interpolation valueOf(String name)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String |  |

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

