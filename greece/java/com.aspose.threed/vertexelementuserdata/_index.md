---
title: VertexElementUserData
second_title: Aspose.3D for Java API Reference
description: Ορίζει προσαρμοσμένα δεδομένα χρήστη για τα καθορισμένα στοιχεία.
type: docs
weight: 221
url: /el/java/com.aspose.threed/vertexelementuserdata/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.VertexElement](../../com.aspose.threed/vertexelement)
```
public class VertexElementUserData extends VertexElement
```

Ορίζει προσαρμοσμένα δεδομένα χρήστη για συγκεκριμένα στοιχεία. Συνήθως είναι δεδομένα ειδικά για την εφαρμογή για ειδικό σκοπό.
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [VertexElementUserData()](#VertexElementUserData--) | Αρχικοποιεί μια νέα παρουσία της κλάσης [VertexElementUserData](../../com.aspose.threed/vertexelementuserdata). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [clear()](#clear--) | Καθαρίζει όλα τα δεδομένα από αυτό το στοιχείο κορυφής. |
| [clone(boolean withData)](#clone-boolean-) | Deep clone the vertex element |
| [clone(boolean withDirect, boolean withIndice)](#clone-boolean-boolean-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | Τα δεδομένα χρήστη που επισυνάπτονται σε αυτό το στοιχείο |
| [getIndices()](#getIndices--) | Gets the indices data |
| [getMappingMode()](#getMappingMode--) | Gets how the element is mapped. |
| [getName()](#getName--) | Λαμβάνει το όνομα. |
| [getReferenceMode()](#getReferenceMode--) | Gets how the element is referenced. |
| [getVertexElementType()](#getVertexElementType--) | Gets the type of the [VertexElement](../../com.aspose.threed/vertexelement) |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setData(Object value)](#setData-java.lang.Object-) | Τα δεδομένα χρήστη που επισυνάπτονται σε αυτό το στοιχείο |
| [setIndices(int[] data)](#setIndices-int---) | Load indices |
| [setMappingMode(MappingMode value)](#setMappingMode-com.aspose.threed.MappingMode-) | Sets how the element is mapped. |
| [setName(String value)](#setName-java.lang.String-) | Ορίζει το όνομα. |
| [setReferenceMode(ReferenceMode value)](#setReferenceMode-com.aspose.threed.ReferenceMode-) | Sets how the element is referenced. |
| [toString()](#toString--) | String representation of vertex element. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VertexElementUserData() {#VertexElementUserData--}
```
public VertexElementUserData()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [VertexElementUserData](../../com.aspose.threed/vertexelementuserdata).

### clear() {#clear--}
```
public void clear()
```


Καθαρίζει όλα τα δεδομένα από αυτό το στοιχείο κορυφής.

### clone(boolean withData) {#clone-boolean-}
```
public VertexElement clone(boolean withData)
```


Deep clone the vertex element

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| withData | boolean | Clone the vertex with direct and index array |

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
public Object getData()
```


Τα δεδομένα χρήστη που επισυνάπτονται σε αυτό το στοιχείο

**Returns:**
java.lang.Object - Τα δεδομένα χρήστη που επισυνάπτονται σε αυτό το στοιχείο
### getIndices() {#getIndices--}
```
public List<Integer> getIndices()
```


Gets the indices data

**Returns:**
java.util.List<java.lang.Integer> - the indices data
### getMappingMode() {#getMappingMode--}
```
public MappingMode getMappingMode()
```


Gets how the element is mapped.

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


Gets how the element is referenced.

**Returns:**
[ReferenceMode](../../com.aspose.threed/referencemode) - how the element is referenced.
### getVertexElementType() {#getVertexElementType--}
```
public VertexElementType getVertexElementType()
```


Gets the type of the [VertexElement](../../com.aspose.threed/vertexelement)

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




### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```


Τα δεδομένα χρήστη που επισυνάπτονται σε αυτό το στοιχείο

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.Object | Νέα τιμή |

### setIndices(int[] data) {#setIndices-int---}
```
public void setIndices(int[] data)
```


Load indices

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δεδομένα | int[] |  |

### setMappingMode(MappingMode value) {#setMappingMode-com.aspose.threed.MappingMode-}
```
public void setMappingMode(MappingMode value)
```


Sets how the element is mapped.

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


Sets how the element is referenced.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ReferenceMode](../../com.aspose.threed/referencemode) | Νέα τιμή |

### toString() {#toString--}
```
public String toString()
```


String representation of vertex element.

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

