---
title: VertexDeclaration
second_title: Aspose.3D for Java API Reference
description: The declaration of a custom defined vertexs structure
type: docs
weight: 206
url: /el/java/com.aspose.threed/vertexdeclaration/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable, java.lang.Comparable
```
public final class VertexDeclaration implements Iterable<VertexField>, Comparable<VertexDeclaration>
```

Η δήλωση της δομής μιας προσαρμοσμένης κορυφής
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [VertexDeclaration()](#VertexDeclaration--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addField(int dataType, VertexFieldSemantic semantic)](#addField-int-com.aspose.threed.VertexFieldSemantic-) | Προσθέτει ένα νέο πεδίο κορυφής |
| [addField(int dataType, VertexFieldSemantic semantic, int index)](#addField-int-com.aspose.threed.VertexFieldSemantic-int-) | Προσθέτει ένα νέο πεδίο κορυφής |
| [addField(int dataType, VertexFieldSemantic semantic, int index, String alias)](#addField-int-com.aspose.threed.VertexFieldSemantic-int-java.lang.String-) | Προσθέτει ένα νέο πεδίο κορυφής |
| [clear()](#clear--) | Καθαρίζει όλα τα πεδία. |
| [compareTo(VertexDeclaration other)](#compareTo-com.aspose.threed.VertexDeclaration-) | Συγκρίνει αυτή την παρουσία με ένα καθορισμένο αντικείμενο και επιστρέφει ένδειξη των σχετικών τιμών τους. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether this instance and a specified object, which must also be a [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) object, have the same value. |
| [fromGeometry(Geometry geometry, boolean useFloat)](#fromGeometry-com.aspose.threed.Geometry-boolean-) | Create a [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) based on a [Geometry](../../com.aspose.threed/geometry)'s layout. |
| [get(int index)](#get-int-) | Gets the [VertexField](../../com.aspose.threed/vertexfield) by index |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Gets the count of all fields defined in this [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |
| [getSealed()](#getSealed--) | A [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) will be sealed when its been used by [TriMesh](../../com.aspose.threed/trimesh), no more modifications is allowed. |
| [getSize()](#getSize--) | Το μέγεθος σε byte της δομής κορυφής. |
| [hashCode()](#hashCode--) | Returns the hash code for this string. |
| [iterator()](#iterator--) | Gets an enumerator to walk through all vertex fields in this instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | String representation of [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VertexDeclaration() {#VertexDeclaration--}
```
public VertexDeclaration()
```


### addField(int dataType, VertexFieldSemantic semantic) {#addField-int-com.aspose.threed.VertexFieldSemantic-}
```
public VertexField addField(int dataType, VertexFieldSemantic semantic)
```


Προσθέτει ένα νέο πεδίο κορυφής

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dataType | int | The data type of the vertex field |
| semantic | [VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) | Πώς θα χρησιμοποιηθεί αυτό το πεδίο |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield)
### addField(int dataType, VertexFieldSemantic semantic, int index) {#addField-int-com.aspose.threed.VertexFieldSemantic-int-}
```
public VertexField addField(int dataType, VertexFieldSemantic semantic, int index)
```


Προσθέτει ένα νέο πεδίο κορυφής

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dataType | int | The data type of the vertex field |
| semantic | [VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) | Πώς θα χρησιμοποιηθεί αυτό το πεδίο |
| δείκτης | int | Ο δείκτης για την ίδια σημασιολογία πεδίου, -1 για αυτόματη δημιουργία |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield)
### addField(int dataType, VertexFieldSemantic semantic, int index, String alias) {#addField-int-com.aspose.threed.VertexFieldSemantic-int-java.lang.String-}
```
public VertexField addField(int dataType, VertexFieldSemantic semantic, int index, String alias)
```


Προσθέτει ένα νέο πεδίο κορυφής

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dataType | int | The data type of the vertex field |
| semantic | [VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) | Πώς θα χρησιμοποιηθεί αυτό το πεδίο |
| δείκτης | int | Ο δείκτης για την ίδια σημασιολογία πεδίου, -1 για αυτόματη δημιουργία |
| ψευδώνυμο | java.lang.String | Το όνομα ψευδώνυμου του πεδίου |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield)
### clear() {#clear--}
```
public void clear()
```


Καθαρίζει όλα τα πεδία.

### compareTo(VertexDeclaration other) {#compareTo-com.aspose.threed.VertexDeclaration-}
```
public int compareTo(VertexDeclaration other)
```


Συγκρίνει αυτή την παρουσία με ένα καθορισμένο αντικείμενο και επιστρέφει ένδειξη των σχετικών τιμών τους.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| other | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |  |

**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether this instance and a specified object, which must also be a [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) object, have the same value.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromGeometry(Geometry geometry, boolean useFloat) {#fromGeometry-com.aspose.threed.Geometry-boolean-}
```
public static VertexDeclaration fromGeometry(Geometry geometry, boolean useFloat)
```


Create a [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) based on a [Geometry](../../com.aspose.threed/geometry)'s layout.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| geometry | [Geometry](../../com.aspose.threed/geometry) |  |
| useFloat | boolean | Χρησιμοποιήστε float αντί για τύπο double |

**Returns:**
[VertexDeclaration](../../com.aspose.threed/vertexdeclaration)
### get(int index) {#get-int-}
```
public VertexField get(int index)
```


Gets the [VertexField](../../com.aspose.threed/vertexfield) by index

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δείκτης | int |  |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield) - the [VertexField](../../com.aspose.threed/vertexfield) by index
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public int getCount()
```


Gets the count of all fields defined in this [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)

**Returns:**
int - ο αριθμός όλων των πεδίων που ορίζονται σε αυτή τη [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)
### getSealed() {#getSealed--}
```
public boolean getSealed()
```


A [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) will be sealed when its been used by [TriMesh](../../com.aspose.threed/trimesh), no more modifications is allowed.

**Returns:**
boolean - Ένα [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) θα σφραγιστεί όταν χρησιμοποιηθεί από το [TriMesh](../../com.aspose.threed/trimesh), δεν επιτρέπονται περαιτέρω τροποποιήσεις.
### getSize() {#getSize--}
```
public int getSize()
```


Το μέγεθος σε byte της δομής κορυφής.

**Returns:**
int - Το μέγεθος σε byte της δομής κορυφής.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns the hash code for this string.

**Returns:**
int - A 32-bit signed integer hash code.
### iterator() {#iterator--}
```
public Iterator<VertexField> iterator()
```


Gets an enumerator to walk through all vertex fields in this instance.

**Returns:**
java.util.Iterator<com.aspose.threed.VertexField> - Απαριθμητής
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


String representation of [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)

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

