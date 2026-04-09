---
title: StructuralMetadata.PropertyTable
second_title: Aspose.3D for Java API Reference
description: Πίνακας ιδιοτήτων.
type: docs
weight: 14
url: /el/java/com.aspose.threed/structuralmetadata.propertytable/
---

**Inheritance:**
java.lang.Object
```
public static class StructuralMetadata.PropertyTable
```

Πίνακας ιδιοτήτων.
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [PropertyTable(String name, StructuralMetadata.ClassType mclass)](#PropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-) | Κατασκευαστής του πίνακα ιδιοτήτων. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addValue(StructuralMetadata.Property prop, Object value)](#addValue-com.aspose.threed.StructuralMetadata.Property-java.lang.Object-) | Προσθέστε μια νέα ιδιότητα στον πίνακα ιδιοτήτων. |
| [addValue(String propName, Object value)](#addValue-java.lang.String-java.lang.Object-) | Προσθέστε μια νέα ιδιότητα στον πίνακα ιδιοτήτων. |
| [attach(VertexElementUserData userData)](#attach-com.aspose.threed.VertexElementUserData-) | Συνδέστε τον τρέχοντα πίνακα ιδιοτήτων με τα καθορισμένα δεδομένα χρήστη |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [from(VertexElementUserData userData)](#from-com.aspose.threed.VertexElementUserData-) | Εξάγετε τον συνδεδεμένο πίνακα ιδιοτήτων από τα καθορισμένα δεδομένα χρήστη |
| [getClass()](#getClass--) |  |
| [getMetaClass()](#getMetaClass--) | Η meta κλάση αυτού του πίνακα ιδιοτήτων. |
| [getName()](#getName--) | Όνομα του πίνακα ιδιοτήτων. |
| [getValue(String name)](#getValue-java.lang.String-) | Λαμβάνει την τιμή του καθορισμένου ονόματος ιδιότητας |
| [getValues()](#getValues--) | Τιμές του πίνακα ιδιοτήτων. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PropertyTable(String name, StructuralMetadata.ClassType mclass) {#PropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-}
```
public PropertyTable(String name, StructuralMetadata.ClassType mclass)
```


Κατασκευαστής του πίνακα ιδιοτήτων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Το όνομα αυτής της παρουσίας του πίνακα. |
| mclass | [ClassType](../../com.aspose.threed/classtype) | Ο ορισμός της meta κλάσης αυτού του πίνακα ιδιοτήτων |

### addValue(StructuralMetadata.Property prop, Object value) {#addValue-com.aspose.threed.StructuralMetadata.Property-java.lang.Object-}
```
public void addValue(StructuralMetadata.Property prop, Object value)
```


Προσθέστε μια νέα ιδιότητα στον πίνακα ιδιοτήτων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| prop | [Property](../../com.aspose.threed/property) | Ποια ιδιότητα να προστεθεί με τιμή |
| τιμή | java.lang.Object | Πίνακας τιμών |

### addValue(String propName, Object value) {#addValue-java.lang.String-java.lang.Object-}
```
public void addValue(String propName, Object value)
```


Προσθέστε μια νέα ιδιότητα στον πίνακα ιδιοτήτων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| propName | java.lang.String | Ποια ιδιότητα να προστεθεί με τιμή |
| τιμή | java.lang.Object | Πίνακας τιμών |

### attach(VertexElementUserData userData) {#attach-com.aspose.threed.VertexElementUserData-}
```
public void attach(VertexElementUserData userData)
```


Συνδέστε τον τρέχοντα πίνακα ιδιοτήτων με τα καθορισμένα δεδομένα χρήστη

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| userData | [VertexElementUserData](../../com.aspose.threed/vertexelementuserdata) |  |

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
### from(VertexElementUserData userData) {#from-com.aspose.threed.VertexElementUserData-}
```
public static StructuralMetadata.PropertyTable from(VertexElementUserData userData)
```


Εξάγετε τον συνδεδεμένο πίνακα ιδιοτήτων από τα καθορισμένα δεδομένα χρήστη

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| userData | [VertexElementUserData](../../com.aspose.threed/vertexelementuserdata) | Τα δεδομένα χρήστη που σχετίζονται με έναν πίνακα ιδιοτήτων |

**Returns:**
[PropertyTable](../../com.aspose.threed/propertytable) - The associated property table instance
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMetaClass() {#getMetaClass--}
```
public StructuralMetadata.ClassType getMetaClass()
```


Η meta κλάση αυτού του πίνακα ιδιοτήτων.

**Returns:**
[ClassType](../../com.aspose.threed/classtype) - The meta class of this property table.
### getName() {#getName--}
```
public String getName()
```


Όνομα του πίνακα ιδιοτήτων.

**Returns:**
java.lang.String - Όνομα του πίνακα ιδιοτήτων.
### getValue(String name) {#getValue-java.lang.String-}
```
public Object getValue(String name)
```


Λαμβάνει την τιμή του καθορισμένου ονόματος ιδιότητας

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα ιδιότητας |

**Returns:**
java.lang.Object - Τιμή ιδιότητας ή null αν δεν βρεθεί
### getValues() {#getValues--}
```
public HashMap<String,Object> getValues()
```


Τιμές του πίνακα ιδιοτήτων.

**Returns:**
java.util.HashMap<java.lang.String,java.lang.Object> - Τιμές του πίνακα ιδιοτήτων.
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




### toString() {#toString--}
```
public String toString()
```




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

