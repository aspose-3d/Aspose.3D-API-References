---
title: WrapMode
second_title: Aspose.3D for Java API Reference
description: Λειτουργία περιτύλιξης υφών.
type: docs
weight: 310
url: /el/java/com.aspose.threed/wrapmode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum WrapMode extends Enum<WrapMode>
```

Λειτουργία περιτύλιξης υφής.
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [BORDER](#BORDER) | Οι συντεταγμένες που βρίσκονται εκτός του εύρους [0.0, 1.0] ορίζονται σε ένα καθορισμένο χρώμα περιγράμματος. |
| [CLAMP](#CLAMP) | Κρατά την υφή στο τελευταίο pixel στο περίγραμμα. |
| [MIRROR](#MIRROR) | Η υφή θα επαναληφθεί, αλλά θα αντικατοπτριστεί όταν το ακέραιο μέρος της συντεταγμένης είναι περιττό. |
| [MIRROR_ONCE](#MIRROR-ONCE) | Η υφή θα αντικατοπτριστεί μία φορά και στη συνέχεια θα περιοριστεί στην μέγιστη τιμή. |
| [WRAP](#WRAP) | Τοποθετεί την υφή σε πλακίδια στην επιφάνεια του μοντέλου, δημιουργώντας ένα επαναλαμβανόμενο μοτίβο. |
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
### BORDER {#BORDER}
```
public static final WrapMode BORDER
```


Οι συντεταγμένες που βρίσκονται εκτός του εύρους [0.0, 1.0] ορίζονται σε ένα καθορισμένο χρώμα περιγράμματος.

### CLAMP {#CLAMP}
```
public static final WrapMode CLAMP
```


Κρατά την υφή στο τελευταίο pixel στο περίγραμμα.

### MIRROR {#MIRROR}
```
public static final WrapMode MIRROR
```


Η υφή θα επαναληφθεί, αλλά θα αντικατοπτριστεί όταν το ακέραιο μέρος της συντεταγμένης είναι περιττό.

### MIRROR_ONCE {#MIRROR-ONCE}
```
public static final WrapMode MIRROR_ONCE
```


Η υφή θα αντικατοπτριστεί μία φορά και στη συνέχεια θα περιοριστεί στην μέγιστη τιμή.

### WRAP {#WRAP}
```
public static final WrapMode WRAP
```


Τοποθετεί την υφή σε πλακίδια στην επιφάνεια του μοντέλου, δημιουργώντας ένα επαναλαμβανόμενο μοτίβο.

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
public static WrapMode valueOf(String name)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode)
### values() {#values--}
```
public static WrapMode[] values()
```




**Returns:**
com.aspose.threed.WrapMode[]
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

