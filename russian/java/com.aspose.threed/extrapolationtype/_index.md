---
title: ExtrapolationType
second_title: Справочник API Aspose.3D для Java
description: Тип экстраполяции.
type: docs
weight: 278
url: /ru/java/com.aspose.threed/extrapolationtype/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ExtrapolationType extends Enum<ExtrapolationType>
```

Тип экстраполяции.
## Поля

| Поле | Описание |
| --- | --- |
| [CONSTANT](#CONSTANT) | Значение будет сохранять то же значение, что и последнее значение |
| [CYCLE](#CYCLE) | Повторение. |
| [CYCLE_RELATIVE](#CYCLE-RELATIVE) | Повторить предыдущий шаблон, основываясь на последнем значении |
| [GRADIENT](#GRADIENT) | Значение будет сохранять тот же наклон со временем |
| [OSCILLATE](#OSCILLATE) | Зеркальное повторение. |
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
### CONSTANT {#CONSTANT}
```
public static final ExtrapolationType CONSTANT
```


Значение будет сохранять то же значение, что и последнее значение

### CYCLE {#CYCLE}
```
public static final ExtrapolationType CYCLE
```


Повторение.

### CYCLE_RELATIVE {#CYCLE-RELATIVE}
```
public static final ExtrapolationType CYCLE_RELATIVE
```


Повторить предыдущий шаблон, основываясь на последнем значении

### GRADIENT {#GRADIENT}
```
public static final ExtrapolationType GRADIENT
```


Значение будет сохранять тот же наклон со временем

### OSCILLATE {#OSCILLATE}
```
public static final ExtrapolationType OSCILLATE
```


Зеркальное повторение.

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
public static ExtrapolationType valueOf(String name)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String |  |

**Returns:**
[ExtrapolationType](../../com.aspose.threed/extrapolationtype)
### values() {#values--}
```
public static ExtrapolationType[] values()
```




**Returns:**
com.aspose.threed.ExtrapolationType[]
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

