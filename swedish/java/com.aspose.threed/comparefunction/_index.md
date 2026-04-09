---
title: CompareFunction
second_title: Aspose.3D for Java API-referens
description: Jämförelsefunktionen som används i djup-/stenciltestning.
type: docs
weight: 271
url: /sv/java/com.aspose.threed/comparefunction/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum CompareFunction extends Enum<CompareFunction>
```

Jämförelsefunktionen som används i djup-/stenciltestning.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [ALWAYS](#ALWAYS) | Alltid godkänns |
| [EQUAL](#EQUAL) | Godkänn om det inkommande värdet är lika med det lagrade värdet. |
| [GREATER](#GREATER) | Godkänn om det inkommande värdet är större än det lagrade värdet. |
| [G_EQUAL](#G-EQUAL) | Godkänn om det inkommande värdet är större än eller lika med det lagrade värdet. |
| [LESS](#LESS) | Godkänn om det inkommande värdet är mindre än det lagrade värdet. |
| [L_EQUAL](#L-EQUAL) | Godkänn om det inkommande värdet är mindre än eller lika med det lagrade värdet. |
| [NEVER](#NEVER) | Aldrig godkänd |
| [NOT_EQUAL](#NOT-EQUAL) | Godkänn om det inkommande värdet inte är lika med det lagrade värdet. |
## Metoder

| Metod | Beskrivning |
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


Alltid godkänns

### EQUAL {#EQUAL}
```
public static final CompareFunction EQUAL
```


Godkänn om det inkommande värdet är lika med det lagrade värdet.

### GREATER {#GREATER}
```
public static final CompareFunction GREATER
```


Godkänn om det inkommande värdet är större än det lagrade värdet.

### G_EQUAL {#G-EQUAL}
```
public static final CompareFunction G_EQUAL
```


Godkänn om det inkommande värdet är större än eller lika med det lagrade värdet.

### LESS {#LESS}
```
public static final CompareFunction LESS
```


Godkänn om det inkommande värdet är mindre än det lagrade värdet.

### L_EQUAL {#L-EQUAL}
```
public static final CompareFunction L_EQUAL
```


Godkänn om det inkommande värdet är mindre än eller lika med det lagrade värdet.

### NEVER {#NEVER}
```
public static final CompareFunction NEVER
```


Aldrig godkänd

### NOT_EQUAL {#NOT-EQUAL}
```
public static final CompareFunction NOT_EQUAL
```


Godkänn om det inkommande värdet inte är lika med det lagrade värdet.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

