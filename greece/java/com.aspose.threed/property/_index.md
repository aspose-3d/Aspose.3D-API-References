---
title: StructuralMetadata.Property
second_title: Aspose.3D for Java API Reference
description: Ο ορισμός της ιδιότητας στις κλάσεις μεταδεδομένων.
type: docs
weight: 13
url: /el/java/com.aspose.threed/structuralmetadata.property/
---

**Inheritance:**
java.lang.Object
```
public static class StructuralMetadata.Property
```

Ο ορισμός ιδιότητας στις κλάσεις των μεταδεδομένων
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [Property(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count)](#Property-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----boolean-java.lang.Integer-) | Κατασκευαστής της ιδιότητας των μεταδεδομένων. |
| [Property(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count)](#Property-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-) | Κατασκευαστής της ιδιότητας των μεταδεδομένων. |
| [Property(String name, Class<?> type)](#Property-java.lang.String-java.lang.Class----) | Κατασκευαστής της ιδιότητας των μεταδεδομένων. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Αριθμός των δεδομένων για σταθερού μεγέθους πίνακα. |
| [getDescription()](#getDescription--) | Η περιγραφή της ιδιότητας. |
| [getDisplayName()](#getDisplayName--) | Το όνομα της ιδιότητας, που χρησιμοποιείται από το UI για την αναπαράσταση. |
| [getEnumType()](#getEnumType--) | Ο τύπος enum. |
| [getName()](#getName--) | Το μοναδικό όνομα της ιδιότητας. |
| [getNormalized()](#getNormalized--) | Είναι τα δεδομένα κανονικοποιημένα. |
| [getType()](#getType--) | Ο τύπος δεδομένων της ιδιότητας. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCount(Integer value)](#setCount-java.lang.Integer-) | Αριθμός των δεδομένων για σταθερού μεγέθους πίνακα. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Η περιγραφή της ιδιότητας. |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | Το όνομα της ιδιότητας, που χρησιμοποιείται από το UI για την αναπαράσταση. |
| [setEnumType(StructuralMetadata.EnumType value)](#setEnumType-com.aspose.threed.StructuralMetadata.EnumType-) | Ο τύπος enum. |
| [setNormalized(boolean value)](#setNormalized-boolean-) | Είναι τα δεδομένα κανονικοποιημένα. |
| [toString()](#toString--) | Λαμβάνει την αναπαράσταση συμβολοσειράς αυτού του αντικειμένου. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Property(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count) {#Property-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----boolean-java.lang.Integer-}
```
public Property(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count)
```


Κατασκευαστής της ιδιότητας των μεταδεδομένων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Το μοναδικό όνομα της ιδιότητας. |
| displayName | java.lang.String | Το όνομα της ιδιότητας, που χρησιμοποιείται από το UI για την αναπαράσταση. |
| description | java.lang.String | Η περιγραφή της ιδιότητας. |
| type | java.lang.Class<?> | Τύπος δεδομένων της ιδιότητας. |
| normalized | boolean | Είναι τα δεδομένα κανονικοποιημένα |
| πλήθος | java.lang.Integer | Πλήθος των δεδομένων για σταθερού μεγέθους πίνακα |

### Property(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count) {#Property-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-}
```
public Property(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count)
```


Κατασκευαστής της ιδιότητας των μεταδεδομένων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Το μοναδικό όνομα της ιδιότητας. |
| displayName | java.lang.String | Το όνομα της ιδιότητας, που χρησιμοποιείται από το UI για την αναπαράσταση. |
| description | java.lang.String | Η περιγραφή της ιδιότητας. |
| type | [EnumType](../../com.aspose.threed/enumtype) | Τύπος δεδομένων της ιδιότητας. |
| πίνακας | boolean | Είναι κάθε τιμή ιδιότητας πίνακας ή βαθμωτό |
| πλήθος | java.lang.Integer | Πλήθος των δεδομένων για σταθερού μεγέθους πίνακα |

### Property(String name, Class<?> type) {#Property-java.lang.String-java.lang.Class----}
```
public Property(String name, Class<?> type)
```


Κατασκευαστής της ιδιότητας των μεταδεδομένων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Το μοναδικό όνομα της ιδιότητας. |
| type | java.lang.Class<?> | Τύπος δεδομένων της ιδιότητας. |

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
### getCount() {#getCount--}
```
public Integer getCount()
```


Αριθμός των δεδομένων για σταθερού μεγέθους πίνακα.

**Returns:**
java.lang.Integer - Πλήθος των δεδομένων για σταθερού μεγέθους πίνακα.
### getDescription() {#getDescription--}
```
public String getDescription()
```


Η περιγραφή της ιδιότητας.

**Returns:**
java.lang.String - Η περιγραφή της ιδιότητας
### getDisplayName() {#getDisplayName--}
```
public String getDisplayName()
```


Το όνομα της ιδιότητας, που χρησιμοποιείται από το UI για την αναπαράσταση.

**Returns:**
java.lang.String - Το όνομα της ιδιότητας, που χρησιμοποιείται από το UI για την αναπαράσταση.
### getEnumType() {#getEnumType--}
```
public StructuralMetadata.EnumType getEnumType()
```


Ο τύπος enum.

**Returns:**
[EnumType](../../com.aspose.threed/enumtype) - The enum type
### getName() {#getName--}
```
public String getName()
```


Το μοναδικό όνομα της ιδιότητας.

**Returns:**
java.lang.String - Το μοναδικό όνομα της ιδιότητας
### getNormalized() {#getNormalized--}
```
public boolean getNormalized()
```


Είναι τα δεδομένα κανονικοποιημένα.

**Returns:**
boolean - Είναι τα δεδομένα κανονικοποιημένα.
### getType() {#getType--}
```
public Class<?> getType()
```


Ο τύπος δεδομένων της ιδιότητας.

**Returns:**
java.lang.Class<?> - Ο τύπος δεδομένων της ιδιότητας
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




### setCount(Integer value) {#setCount-java.lang.Integer-}
```
public void setCount(Integer value)
```


Αριθμός των δεδομένων για σταθερού μεγέθους πίνακα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.Integer | Νέα τιμή |

### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


Η περιγραφή της ιδιότητας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public void setDisplayName(String value)
```


Το όνομα της ιδιότητας, που χρησιμοποιείται από το UI για την αναπαράσταση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setEnumType(StructuralMetadata.EnumType value) {#setEnumType-com.aspose.threed.StructuralMetadata.EnumType-}
```
public void setEnumType(StructuralMetadata.EnumType value)
```


Ο τύπος enum.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [EnumType](../../com.aspose.threed/enumtype) | Νέα τιμή |

### setNormalized(boolean value) {#setNormalized-boolean-}
```
public void setNormalized(boolean value)
```


Είναι τα δεδομένα κανονικοποιημένα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### toString() {#toString--}
```
public String toString()
```


Λαμβάνει την αναπαράσταση συμβολοσειράς αυτού του αντικειμένου.

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

