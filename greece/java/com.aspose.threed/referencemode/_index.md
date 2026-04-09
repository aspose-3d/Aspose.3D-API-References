---
title: ReferenceMode
second_title: Aspose.3D for Java API Reference
description: ορίζει πώς αποθηκεύονται και αναφέρονται οι πληροφορίες αντιστοίχισης από.
type: docs
weight: 296
url: /el/java/com.aspose.threed/referencemode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ReferenceMode extends Enum<ReferenceMode>
```

[ReferenceMode](../../com.aspose.threed/referencemode) defines how mapping information is stored and referenced by.
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [DIRECT](#DIRECT) | Τα δεδομένα αναφέρονται άμεσα |
| [INDEX](#INDEX) | Τα δεδομένα αναφέρονται με δείκτη |
| [INDEX_TO_DIRECT](#INDEX-TO-DIRECT) | Τα δεδομένα αναφέρονται με δείκτη, έπειτα προσπελάζονται με δείκτη στη λίστα δεδομένων του [VertexElement](../../com.aspose.threed/vertexelement). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
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
### DIRECT {#DIRECT}
```
public static final ReferenceMode DIRECT
```


Τα δεδομένα αναφέρονται άμεσα

### INDEX {#INDEX}
```
public static final ReferenceMode INDEX
```


Τα δεδομένα αναφέρονται με δείκτη

### INDEX_TO_DIRECT {#INDEX-TO-DIRECT}
```
public static final ReferenceMode INDEX_TO_DIRECT
```


Τα δεδομένα αναφέρονται με δείκτη, έπειτα προσπελάζονται με δείκτη στη λίστα δεδομένων του [VertexElement](../../com.aspose.threed/vertexelement).

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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
| Παράμετρος | Τύπος | Περιγραφή |
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
| Παράμετρος | Τύπος | Περιγραφή |
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
public static ReferenceMode valueOf(String name)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[ReferenceMode](../../com.aspose.threed/referencemode)
### values() {#values--}
```
public static ReferenceMode[] values()
```




**Returns:**
com.aspose.threed.ReferenceMode[]
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

