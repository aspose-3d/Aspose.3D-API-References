---
title: "CompareFunction"
second_title: "Référence d'API Aspose.3D pour Java"
description: "La fonction de comparaison utilisée dans les tests de profondeur/stencil."
type: docs
weight: 271
url: /fr/java/com.aspose.threed/comparefunction/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum CompareFunction extends Enum<CompareFunction>
```

La fonction de comparaison utilisée dans les tests de profondeur/stencil.
## Champs

| Champ | Description |
| --- | --- |
| [ALWAYS](#ALWAYS) | Toujours passe |
| [EQUAL](#EQUAL) | Valide si la valeur entrante est égale à la valeur stockée. |
| [GREATER](#GREATER) | Valide si la valeur entrante est supérieure à la valeur stockée. |
| [G_EQUAL](#G-EQUAL) | Valide si la valeur entrante est supérieure ou égale à la valeur stockée. |
| [LESS](#LESS) | Valide si la valeur entrante est inférieure à la valeur stockée. |
| [L_EQUAL](#L-EQUAL) | Valide si la valeur entrante est inférieure ou égale à la valeur stockée. |
| [NEVER](#NEVER) | Ne passe jamais |
| [NOT_EQUAL](#NOT-EQUAL) | Valide si la valeur entrante n'est pas égale à la valeur stockée. |
## Méthodes

| Méthode | Description |
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


Toujours passe

### EQUAL {#EQUAL}
```
public static final CompareFunction EQUAL
```


Valide si la valeur entrante est égale à la valeur stockée.

### GREATER {#GREATER}
```
public static final CompareFunction GREATER
```


Valide si la valeur entrante est supérieure à la valeur stockée.

### G_EQUAL {#G-EQUAL}
```
public static final CompareFunction G_EQUAL
```


Valide si la valeur entrante est supérieure ou égale à la valeur stockée.

### LESS {#LESS}
```
public static final CompareFunction LESS
```


Valide si la valeur entrante est inférieure à la valeur stockée.

### L_EQUAL {#L-EQUAL}
```
public static final CompareFunction L_EQUAL
```


Valide si la valeur entrante est inférieure ou égale à la valeur stockée.

### NEVER {#NEVER}
```
public static final CompareFunction NEVER
```


Ne passe jamais

### NOT_EQUAL {#NOT-EQUAL}
```
public static final CompareFunction NOT_EQUAL
```


Valide si la valeur entrante n'est pas égale à la valeur stockée.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

