---
title: "VertexDeclaration"
second_title: "Aspose.3D for Java API Reference"
description: "Η δήλωση μιας προσαρμοσμένης δομής κορυφών"
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
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
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
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν αυτή η παρουσία και ένα καθορισμένο αντικείμενο, το οποίο πρέπει επίσης να είναι ένα αντικείμενο [VertexDeclaration](../../com.aspose.threed/vertexdeclaration), έχουν την ίδια τιμή. |
| [fromGeometry(Geometry geometry, boolean useFloat)](#fromGeometry-com.aspose.threed.Geometry-boolean-) | Δημιουργήστε ένα [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) βασισμένο στη διάταξη ενός [Geometry](../../com.aspose.threed/geometry). |
| [get(int index)](#get-int-) | Λαμβάνει το [VertexField](../../com.aspose.threed/vertexfield) με δείκτη |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Λαμβάνει τον αριθμό όλων των πεδίων που ορίζονται σε αυτό το [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |
| [getSealed()](#getSealed--) | Ένα [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) θα σφραγιστεί όταν χρησιμοποιηθεί από [TriMesh](../../com.aspose.threed/trimesh), δεν επιτρέπονται περαιτέρω τροποποιήσεις. |
| [getSize()](#getSize--) | Το μέγεθος σε byte της δομής κορυφής. |
| [hashCode()](#hashCode--) | Επιστρέφει τον κωδικό κατακερματισμού για αυτή τη συμβολοσειρά. |
| [iterator()](#iterator--) | Λαμβάνει έναν enumerator για να διασχίσει όλα τα πεδία κορυφών σε αυτή την παρουσία. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Αναπαράσταση συμβολοσειράς του [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |
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
| dataType | int | Ο τύπος δεδομένων του πεδίου κορυφής |
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
| dataType | int | Ο τύπος δεδομένων του πεδίου κορυφής |
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
| dataType | int | Ο τύπος δεδομένων του πεδίου κορυφής |
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


Καθορίζει εάν αυτή η παρουσία και ένα καθορισμένο αντικείμενο, το οποίο πρέπει επίσης να είναι ένα αντικείμενο [VertexDeclaration](../../com.aspose.threed/vertexdeclaration), έχουν την ίδια τιμή.

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


Δημιουργήστε ένα [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) βασισμένο στη διάταξη ενός [Geometry](../../com.aspose.threed/geometry).

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


Λαμβάνει το [VertexField](../../com.aspose.threed/vertexfield) με δείκτη

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


Λαμβάνει τον αριθμό όλων των πεδίων που ορίζονται σε αυτό το [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)

**Returns:**
int - ο αριθμός όλων των πεδίων που ορίζονται σε αυτή τη [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)
### getSealed() {#getSealed--}
```
public boolean getSealed()
```


Ένα [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) θα σφραγιστεί όταν χρησιμοποιηθεί από [TriMesh](../../com.aspose.threed/trimesh), δεν επιτρέπονται περαιτέρω τροποποιήσεις.

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


Επιστρέφει τον κωδικό κατακερματισμού για αυτή τη συμβολοσειρά.

**Returns:**
int - Κωδικός κατακερματισμού 32-bit υπογεγραμμένου ακέραιου.
### iterator() {#iterator--}
```
public Iterator<VertexField> iterator()
```


Λαμβάνει έναν enumerator για να διασχίσει όλα τα πεδία κορυφών σε αυτή την παρουσία.

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


Αναπαράσταση συμβολοσειράς του [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)

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

