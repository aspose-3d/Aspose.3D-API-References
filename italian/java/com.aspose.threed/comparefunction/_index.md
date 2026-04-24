---
title: CompareFunction
second_title: Aspose.3D for Java API Reference
description: La funzione di confronto utilizzata nei test di depth/stencil.
type: docs
weight: 271
url: /it/java/com.aspose.threed/comparefunction/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum CompareFunction extends Enum<CompareFunction>
```

La funzione di confronto utilizzata nei test di depth/stencil.
## Campi

| Campo | Descrizione |
| --- | --- |
| [ALWAYS](#ALWAYS) | Passa sempre |
| [EQUAL](#EQUAL) | Passa se il valore in ingresso è uguale al valore memorizzato. |
| [GREATER](#GREATER) | Passa se il valore in ingresso è maggiore del valore memorizzato. |
| [G_EQUAL](#G-EQUAL) | Passa se il valore in ingresso è maggiore o uguale al valore memorizzato. |
| [LESS](#LESS) | Passa se il valore in ingresso è minore del valore memorizzato. |
| [L_EQUAL](#L-EQUAL) | Passa se il valore in ingresso è minore o uguale al valore memorizzato. |
| [NEVER](#NEVER) | Non passa mai |
| [NOT_EQUAL](#NOT-EQUAL) | Passa se il valore in ingresso non è uguale al valore memorizzato. |
## Metodi

| Metodo | Descrizione |
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


Passa sempre

### EQUAL {#EQUAL}
```
public static final CompareFunction EQUAL
```


Passa se il valore in ingresso è uguale al valore memorizzato.

### GREATER {#GREATER}
```
public static final CompareFunction GREATER
```


Passa se il valore in ingresso è maggiore del valore memorizzato.

### G_EQUAL {#G-EQUAL}
```
public static final CompareFunction G_EQUAL
```


Passa se il valore in ingresso è maggiore o uguale al valore memorizzato.

### LESS {#LESS}
```
public static final CompareFunction LESS
```


Passa se il valore in ingresso è minore del valore memorizzato.

### L_EQUAL {#L-EQUAL}
```
public static final CompareFunction L_EQUAL
```


Passa se il valore in ingresso è minore o uguale al valore memorizzato.

### NEVER {#NEVER}
```
public static final CompareFunction NEVER
```


Non passa mai

### NOT_EQUAL {#NOT-EQUAL}
```
public static final CompareFunction NOT_EQUAL
```


Passa se il valore in ingresso non è uguale al valore memorizzato.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

