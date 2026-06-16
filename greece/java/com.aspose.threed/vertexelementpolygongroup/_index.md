---
title: "VertexElementPolygonGroup"
second_title: "Aspose.3D for Java API Reference"
description: "Ορίζει την ομάδα πολυγώνων για τα καθορισμένα στοιχεία ώστε να ομαδοποιεί συναφή πολύγωνα μαζί."
type: docs
weight: 215
url: /el/java/com.aspose.threed/vertexelementpolygongroup/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.VertexElement](../../com.aspose.threed/vertexelement), [com.aspose.threed.VertexElementIntsTemplate](../../com.aspose.threed/vertexelementintstemplate)
```
public class VertexElementPolygonGroup extends VertexElementIntsTemplate
```

Ορίζει την ομάδα πολυγώνων για τα καθορισμένα στοιχεία ώστε να ομαδοποιεί συναφή πολύγωνα μαζί.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [VertexElementPolygonGroup()](#VertexElementPolygonGroup--) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [VertexElementPolygonGroup](../../com.aspose.threed/vertexelementpolygongroup). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [clear()](#clear--) | Αφαιρεί όλα τα στοιχεία από τους άμεσους και τους δείκτες πίνακες. |
| [clone(boolean withData)](#clone-boolean-) | Βαθιά κλωνοποίηση του στοιχείου κορυφής |
| [clone(boolean withDirect, boolean withIndice)](#clone-boolean-boolean-) |  |
| [copyTo(VertexElementIntsTemplate target)](#copyTo-com.aspose.threed.VertexElementIntsTemplate-) | Αντιγράφει δεδομένα στο καθορισμένο στοιχείο |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | Αποκτά τα δεδομένα κορυφής |
| [getIndices()](#getIndices--) | Λαμβάνει τα δεδομένα δεικτών |
| [getMappingMode()](#getMappingMode--) | Λαμβάνει πώς χαρτογραφείται το στοιχείο. |
| [getName()](#getName--) | Λαμβάνει το όνομα. |
| [getReferenceMode()](#getReferenceMode--) | Λαμβάνει πώς αναφέρεται το στοιχείο. |
| [getVertexElementType()](#getVertexElementType--) | Λαμβάνει τον τύπο του [VertexElement](../../com.aspose.threed/vertexelement) |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setData(int[] data)](#setData-int---) | Φόρτωση δεδομένων |
| [setIndices(int[] data)](#setIndices-int---) | Φόρτωση δεικτών |
| [setMappingMode(MappingMode value)](#setMappingMode-com.aspose.threed.MappingMode-) | Ορίζει πώς χαρτογραφείται το στοιχείο. |
| [setName(String value)](#setName-java.lang.String-) | Ορίζει το όνομα. |
| [setReferenceMode(ReferenceMode value)](#setReferenceMode-com.aspose.threed.ReferenceMode-) | Ορίζει πώς αναφέρεται το στοιχείο. |
| [toString()](#toString--) | Αναπαράσταση συμβολοσειράς του στοιχείου κορυφής. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VertexElementPolygonGroup() {#VertexElementPolygonGroup--}
```
public VertexElementPolygonGroup()
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [VertexElementPolygonGroup](../../com.aspose.threed/vertexelementpolygongroup).

### clear() {#clear--}
```
public void clear()
```


Αφαιρεί όλα τα στοιχεία από τους άμεσους και τους δείκτες πίνακες.

### clone(boolean withData) {#clone-boolean-}
```
public VertexElement clone(boolean withData)
```


Βαθιά κλωνοποίηση του στοιχείου κορυφής

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| withData | boolean | Κλωνοποιήστε την κορυφή με άμεσο και πίνακα δεικτών |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement)
### clone(boolean withDirect, boolean withIndice) {#clone-boolean-boolean-}
```
public VertexElement clone(boolean withDirect, boolean withIndice)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| withDirect | boolean |  |
| withIndice | boolean |  |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement)
### copyTo(VertexElementIntsTemplate target) {#copyTo-com.aspose.threed.VertexElementIntsTemplate-}
```
public void copyTo(VertexElementIntsTemplate target)
```


Αντιγράφει δεδομένα στο καθορισμένο στοιχείο

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| target | [VertexElementIntsTemplate](../../com.aspose.threed/vertexelementintstemplate) | Στόχος. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
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
### getData() {#getData--}
```
public List<Integer> getData()
```


Αποκτά τα δεδομένα κορυφής

**Returns:**
java.util.List<java.lang.Integer> - τα δεδομένα κορυφής
### getIndices() {#getIndices--}
```
public List<Integer> getIndices()
```


Λαμβάνει τα δεδομένα δεικτών

**Returns:**
java.util.List<java.lang.Integer> - τα δεδομένα δεικτών
### getMappingMode() {#getMappingMode--}
```
public MappingMode getMappingMode()
```


Λαμβάνει πώς χαρτογραφείται το στοιχείο.

**Returns:**
[MappingMode](../../com.aspose.threed/mappingmode) - how the element is mapped.
### getName() {#getName--}
```
public String getName()
```


Λαμβάνει το όνομα.

**Returns:**
java.lang.String - το όνομα.
### getReferenceMode() {#getReferenceMode--}
```
public ReferenceMode getReferenceMode()
```


Λαμβάνει πώς αναφέρεται το στοιχείο.

**Returns:**
[ReferenceMode](../../com.aspose.threed/referencemode) - how the element is referenced.
### getVertexElementType() {#getVertexElementType--}
```
public VertexElementType getVertexElementType()
```


Λαμβάνει τον τύπο του [VertexElement](../../com.aspose.threed/vertexelement)

**Returns:**
[VertexElementType](../../com.aspose.threed/vertexelementtype) - the type of the [VertexElement](../../com.aspose.threed/vertexelement)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setData(int[] data) {#setData-int---}
```
public void setData(int[] data)
```


Φόρτωση δεδομένων

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δεδομένα | int[] |  |

### setIndices(int[] data) {#setIndices-int---}
```
public void setIndices(int[] data)
```


Φόρτωση δεικτών

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δεδομένα | int[] |  |

### setMappingMode(MappingMode value) {#setMappingMode-com.aspose.threed.MappingMode-}
```
public void setMappingMode(MappingMode value)
```


Ορίζει πώς χαρτογραφείται το στοιχείο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [MappingMode](../../com.aspose.threed/mappingmode) | Νέα τιμή |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Ορίζει το όνομα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setReferenceMode(ReferenceMode value) {#setReferenceMode-com.aspose.threed.ReferenceMode-}
```
public void setReferenceMode(ReferenceMode value)
```


Ορίζει πώς αναφέρεται το στοιχείο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ReferenceMode](../../com.aspose.threed/referencemode) | Νέα τιμή |

### toString() {#toString--}
```
public String toString()
```


Αναπαράσταση συμβολοσειράς του στοιχείου κορυφής.

**Returns:**
java.lang.String
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

