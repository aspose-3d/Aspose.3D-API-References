---
title: "StructuralMetadata"
second_title: "Aspose.3D for Java API Reference"
description: "Αυτή η κλάση παρέχει υποστήριξη για EXT_structural_metadata που χρησιμοποιείται μόνο στο glTF."
type: docs
weight: 180
url: /el/java/com.aspose.threed/structuralmetadata/
---

**Inheritance:**
java.lang.Object
```
public class StructuralMetadata
```

Αυτή η κλάση παρέχει υποστήριξη για EXT\_structural\_metadata, που χρησιμοποιείται μόνο στο glTF.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [StructuralMetadata()](#StructuralMetadata--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [attach(Scene scene)](#attach-com.aspose.threed.Scene-) | Συνδέστε τα τρέχοντα μετα-δεδομένα στη συγκεκριμένη σκηνή |
| [createClass(String name)](#createClass-java.lang.String-) | Δημιουργήστε έναν τύπο μετα-κλάσης |
| [createEnum(String name)](#createEnum-java.lang.String-) | Δημιουργήστε έναν τύπο enum |
| [createPropertyTable(String name, StructuralMetadata.ClassType clazz)](#createPropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-) | Δημιουργήστε έναν νέο πίνακα ιδιοτήτων με τον δεδομένο τύπο μετα-κλάσης |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [from(Scene scene)](#from-com.aspose.threed.Scene-) | Λάβετε το [StructuralMetadata](../../com.aspose.threed/structuralmetadata) που συσχετίζεται με τη συγκεκριμένη σκηνή. |
| [getClass()](#getClass--) |  |
| [getClasses()](#getClasses--) | Οι ορισμοί της κλάσης . |
| [getEnums()](#getEnums--) | Οι ορισμοί του τύπου enum |
| [getPropertyTables()](#getPropertyTables--) | Οι πίνακες ιδιοτήτων σε αυτά τα μεταδεδομένα. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StructuralMetadata() {#StructuralMetadata--}
```
public StructuralMetadata()
```


### attach(Scene scene) {#attach-com.aspose.threed.Scene-}
```
public void attach(Scene scene)
```


Συνδέστε τα τρέχοντα μετα-δεδομένα στη συγκεκριμένη σκηνή

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) |  |

### createClass(String name) {#createClass-java.lang.String-}
```
public StructuralMetadata.ClassType createClass(String name)
```


Δημιουργήστε έναν τύπο μετα-κλάσης

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Το όνομα της κλάσης |

**Returns:**
[ClassType](../../com.aspose.threed/classtype) - Instance of the meta class
### createEnum(String name) {#createEnum-java.lang.String-}
```
public StructuralMetadata.EnumType createEnum(String name)
```


Δημιουργήστε έναν τύπο enum

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Το όνομα του τύπου enum |

**Returns:**
[EnumType](../../com.aspose.threed/enumtype) - Instance of the enum type
### createPropertyTable(String name, StructuralMetadata.ClassType clazz) {#createPropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-}
```
public StructuralMetadata.PropertyTable createPropertyTable(String name, StructuralMetadata.ClassType clazz)
```


Δημιουργήστε έναν νέο πίνακα ιδιοτήτων με τον δεδομένο τύπο μετα-κλάσης

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Το όνομα του πίνακα ιδιοτήτων |
| clazz | [ClassType](../../com.aspose.threed/classtype) | Ο τύπος κλάσης του νέου πίνακα ιδιοτήτων |

**Returns:**
[PropertyTable](../../com.aspose.threed/propertytable) - The new instance of property table
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
### from(Scene scene) {#from-com.aspose.threed.Scene-}
```
public static StructuralMetadata from(Scene scene)
```


Λάβετε το [StructuralMetadata](../../com.aspose.threed/structuralmetadata) που συσχετίζεται με τη συγκεκριμένη σκηνή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | Ποια σκηνή να αναζητηθεί για τα δομικά μεταδεδομένα |

**Returns:**
[StructuralMetadata](../../com.aspose.threed/structuralmetadata) - A valid instance of [StructuralMetadata](../../com.aspose.threed/structuralmetadata) if its found in the scene, otherwise null returned
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClasses() {#getClasses--}
```
public HashMap<String,StructuralMetadata.ClassType> getClasses()
```


Οι ορισμοί της κλάσης .

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.threed.StructuralMetadata.ClassType> - Οι ορισμοί της κλάσης .
### getEnums() {#getEnums--}
```
public HashMap<String,StructuralMetadata.EnumType> getEnums()
```


Οι ορισμοί του τύπου enum

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.threed.StructuralMetadata.EnumType> - Οι ορισμοί του τύπου enum
### getPropertyTables() {#getPropertyTables--}
```
public ArrayList<StructuralMetadata.PropertyTable> getPropertyTables()
```


Οι πίνακες ιδιοτήτων σε αυτά τα μεταδεδομένα.

**Returns:**
java.util.ArrayList<com.aspose.threed.StructuralMetadata.PropertyTable> - Οι πίνακες ιδιοτήτων σε αυτά τα μεταδεδομένα.
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

