---
title: Δομή
second_title: Aspose.3D for Java API Reference
description: Δημιουργήθηκε από τον lexchou στις 13/11/2017.
type: docs
weight: 262
url: /el/java/com.aspose.threed/struct/
---

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable
```
public interface Struct<T> extends Cloneable, Serializable
```

Δημιουργήθηκε από τον lexchou στις 13/11/2017.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [<T>byVal(T value)](#-T-byVal-T-) | Προσπάθεια αντιγραφής της τιμής εισόδου αν είναι Struct |
| [clone()](#clone--) | Clone current instance |
| [copyFrom(T t)](#copyFrom-T-) | Αντιγραφή εσωτερικής κατάστασης από το όρισμα t |
### <T>byVal(T value) {#-T-byVal-T-}
```
public static T <T>byVal(T value)
```


Προσπάθεια αντιγραφής της τιμής εισόδου αν είναι Struct

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | T | τιμή εισόδου για κλωνοποίηση |

**Returns:**
T - null εάν η είσοδος είναι null ή το κλωνοποιημένο αντικείμενο
### clone() {#clone--}
```
public abstract T clone()
```


Clone current instance

**Returns:**
T - κλωνοποιημένο αντικείμενο
### copyFrom(T t) {#copyFrom-T-}
```
public abstract void copyFrom(T t)
```


Αντιγραφή εσωτερικής κατάστασης από το όρισμα t

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| t | T | αντικείμενο προέλευσης για αντιγραφή |

