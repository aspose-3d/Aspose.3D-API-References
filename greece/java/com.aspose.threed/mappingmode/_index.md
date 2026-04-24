---
title: MappingMode
second_title: Aspose.3D for Java API Reference
description: Καθορίζει πώς το στοιχείο αντιστοιχίζεται σε μια επιφάνεια.
type: docs
weight: 285
url: /el/java/com.aspose.threed/mappingmode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MappingMode extends Enum<MappingMode>
```

Determines how the element is mapped to a surface. The [MappingMode](../../com.aspose.threed/mappingmode) defined how [VertexElement](../../com.aspose.threed/vertexelement) is mapped to the surface of geometry.
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [ALL_SAME](#ALL-SAME) | One data mapped to the whole surface. |
| [CONTROL_POINT](#CONTROL-POINT) | Κάθε δεδομένο αντιστοιχίζεται στο σημείο ελέγχου της γεωμετρίας. |
| [EDGE](#EDGE) | Τα δεδομένα αντιστοιχίζονται στην άκρη. |
| [POLYGON](#POLYGON) | Τα δεδομένα αντιστοιχίζονται στο πολύγωνο. |
| [POLYGON_VERTEX](#POLYGON-VERTEX) | Τα δεδομένα αντιστοιχίζονται στο vertex του πολύγωνου. Όταν ένα σημείο ελέγχου μοιράζεται από πολλαπλά πολύγωνα και τα δεδομένα αντιστοιχίζονται ως [POLYGON\_VERTEX](../../com.aspose.threed/mappingmode\#POLYGON-VERTEX), το σημείο ελέγχου ως διαφορετικό vertex του πολύγωνου θα έχει τα δικά του δεδομένα |
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
### ALL_SAME {#ALL-SAME}
```
public static final MappingMode ALL_SAME
```


Ένα δεδομένο αντιστοιχίζεται σε ολόκληρη την επιφάνεια. Όποιο δεδομένο ερμηνευτεί ως σημείο ελέγχου/vertex πολύγωνου/άκρα ακμής, τα δεδομένα είναι πάντα τα ίδια όπως ορίζονται από [ALL\_SAME](../../com.aspose.threed/mappingmode\#ALL-SAME).

### CONTROL_POINT {#CONTROL-POINT}
```
public static final MappingMode CONTROL_POINT
```


Κάθε δεδομένο αντιστοιχίζεται στο σημείο ελέγχου της γεωμετρίας.

### EDGE {#EDGE}
```
public static final MappingMode EDGE
```


Τα δεδομένα αντιστοιχίζονται στην άκρη. Κάθε άκρο της ακμής μοιράζεται τα ίδια δεδομένα όταν η αντιστοίχηση είναι [EDGE](../../com.aspose.threed/mappingmode\#EDGE).

### POLYGON {#POLYGON}
```
public static final MappingMode POLYGON
```


Τα δεδομένα αντιστοιχίζονται στο πολύγωνο. Κάθε vertex του πολύγωνου μοιράζεται τα ίδια δεδομένα όταν η λειτουργία αντιστοίχισης είναι [POLYGON](../../com.aspose.threed/mappingmode\#POLYGON).

### POLYGON_VERTEX {#POLYGON-VERTEX}
```
public static final MappingMode POLYGON_VERTEX
```


Τα δεδομένα αντιστοιχίζονται στο vertex του πολύγωνου. Όταν ένα σημείο ελέγχου μοιράζεται από πολλαπλά πολύγωνα και τα δεδομένα αντιστοιχίζονται ως [POLYGON\_VERTEX](../../com.aspose.threed/mappingmode\#POLYGON-VERTEX), το σημείο ελέγχου ως διαφορετικό vertex του πολύγωνου θα έχει τα δικά του δεδομένα

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
public static MappingMode valueOf(String name)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[MappingMode](../../com.aspose.threed/mappingmode)
### values() {#values--}
```
public static MappingMode[] values()
```




**Returns:**
com.aspose.threed.MappingMode[]
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

