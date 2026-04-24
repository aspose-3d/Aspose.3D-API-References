---
title: Vector2
second_title: Aspose.3D for Java API Reference
description: Διανύσμα με δύο συνιστώσες.
type: docs
weight: 201
url: /el/java/com.aspose.threed/vector2/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.threed.Struct, java.io.Serializable
```
public final class Vector2 implements Comparable<Vector2>, Struct<Vector2>, Serializable
```

Διανύσμα με δύο συνιστώσες.
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [Vector2(double s)](#Vector2-double-) | Αρχικοποιεί μια νέα παρουσία της δομής [Vector2](../../com.aspose.threed/vector2) struct. |
| [Vector2(Vector3 s)](#Vector2-com.aspose.threed.Vector3-) | Αρχικοποιεί μια νέα παρουσία της δομής [Vector2](../../com.aspose.threed/vector2) struct. |
| [Vector2(FVector2 vec)](#Vector2-com.aspose.threed.FVector2-) | Αρχικοποιεί μια νέα παρουσία της δομής [Vector2](../../com.aspose.threed/vector2) struct. |
| [Vector2(double x, double y)](#Vector2-double-double-) | Αρχικοποιεί μια νέα παρουσία της δομής [Vector2](../../com.aspose.threed/vector2) struct. |
| [Vector2()](#Vector2--) |  |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [x](#x) | Το στοιχείο x. |
| [y](#y) | Το στοιχείο y. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [add(Vector2 lhs, Vector2 rhs)](#add-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Τελεστής πρόσθεσης για το Vector2 |
| [clone()](#clone--) |  |
| [compareTo(Vector2 other)](#compareTo-com.aspose.threed.Vector2-) | Συγκρίνει το τρέχον διάνυσμα με μια άλλη παρουσία. |
| [copyFrom(Vector2 src)](#copyFrom-com.aspose.threed.Vector2-) |  |
| [create(Vector2 v)](#create-com.aspose.threed.Vector2-) | Τελεστής ρητής μετατροπής για τη μετατροπή του Vector2 σε FVector2 |
| [cross(Vector2 v)](#cross-com.aspose.threed.Vector2-) | Γινόμενο διανυσματικό δύο διανυσμάτων. |
| [div(Vector2 lhs, double rhs)](#div-com.aspose.threed.Vector2-double-) | Τελεστής διαίρεσης για το Vector2 |
| [dot(Vector2 rhs)](#dot-com.aspose.threed.Vector2-) | Επιστρέφει το εσωτερικό γινόμενο δύο διανυσμάτων. |
| [equals(Vector2 rhs)](#equals-com.aspose.threed.Vector2-) | Ελέγξτε αν δύο vector2 είναι ίσα |
| [equals(Object obj)](#equals-java.lang.Object-) | Ελέγξτε αν δύο vector2 είναι ίσα |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Λαμβάνει το μήκος. |
| [getU()](#getU--) | Λαμβάνει το συστατικό U εάν το [Vector2](../../com.aspose.threed/vector2) χρησιμοποιείται ως συντεταγμένη χαρτογράφησης. |
| [getV()](#getV--) | Λαμβάνει το συστατικό V εάν το [Vector2](../../com.aspose.threed/vector2) χρησιμοποιείται ως συντεταγμένη χαρτογράφησης. |
| [hashCode()](#hashCode--) | Λαμβάνει τον κωδικό κατακερματισμού του Vector2 |
| [mul(Vector2 lhs, double rhs)](#mul-com.aspose.threed.Vector2-double-) | Τελεστής πολλαπλασιασμού για το Vector2 |
| [mul(double lhs, Vector2 rhs)](#mul-double-com.aspose.threed.Vector2-) | Τελεστής πολλαπλασιασμού για το Vector2 |
| [normalize()](#normalize--) | Κανονικοποιεί αυτήν την instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(Vector2 lhs, Vector2 rhs)](#op-eq-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Τελεστής ισότητας για Vector2 |
| [op_ne(Vector2 lhs, Vector2 rhs)](#op-ne-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Τελεστής ανισότητας για Vector2 |
| [setU(double value)](#setU-double-) | Ορίζει το συστατικό U εάν το [Vector2](../../com.aspose.threed/vector2) χρησιμοποιείται ως συντεταγμένη χαρτογράφησης. |
| [setV(double value)](#setV-double-) | Ορίζει το συστατικό V εάν το [Vector2](../../com.aspose.threed/vector2) χρησιμοποιείται ως συντεταγμένη χαρτογράφησης. |
| [sub(Vector2 lhs, Vector2 rhs)](#sub-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Τελεστής αφαίρεσης για Vector2 |
| [toString()](#toString--) | Επιστρέφει ένα java.lang.String που αντιπροσωπεύει το τρέχον [Vector2](../../com.aspose.threed/vector2). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Vector2(double s) {#Vector2-double-}
```
public Vector2(double s)
```


Αρχικοποιεί μια νέα παρουσία της δομής [Vector2](../../com.aspose.threed/vector2) struct.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | double | S. |

### Vector2(Vector3 s) {#Vector2-com.aspose.threed.Vector3-}
```
public Vector2(Vector3 s)
```


Αρχικοποιεί μια νέα παρουσία της δομής [Vector2](../../com.aspose.threed/vector2) struct.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | [Vector3](../../com.aspose.threed/vector3) | S. |

### Vector2(FVector2 vec) {#Vector2-com.aspose.threed.FVector2-}
```
public Vector2(FVector2 vec)
```


Αρχικοποιεί μια νέα παρουσία της δομής [Vector2](../../com.aspose.threed/vector2) struct.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| vec | [FVector2](../../com.aspose.threed/fvector2) | Διάνυσμα σε float. |

### Vector2(double x, double y) {#Vector2-double-double-}
```
public Vector2(double x, double y)
```


Αρχικοποιεί μια νέα παρουσία της δομής [Vector2](../../com.aspose.threed/vector2) struct.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | double | The x coordinate. |
| y | double | The y coordinate. |

### Vector2() {#Vector2--}
```
public Vector2()
```


### x {#x}
```
public double x
```


Το στοιχείο x.

### y {#y}
```
public double y
```


Το στοιχείο y.

### add(Vector2 lhs, Vector2 rhs) {#add-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static Vector2 add(Vector2 lhs, Vector2 rhs)
```


Τελεστής πρόσθεσης για το Vector2

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Left hand side value. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Τιμή δεξιάς πλευράς. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of addition.
### clone() {#clone--}
```
public Vector2 clone()
```


Clone current instance

**Returns:**
[Vector2](../../com.aspose.threed/vector2)
### compareTo(Vector2 other) {#compareTo-com.aspose.threed.Vector2-}
```
public int compareTo(Vector2 other)
```


Συγκρίνει το τρέχον διάνυσμα με μια άλλη παρουσία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| other | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
int
### copyFrom(Vector2 src) {#copyFrom-com.aspose.threed.Vector2-}
```
public void copyFrom(Vector2 src)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| src | [Vector2](../../com.aspose.threed/vector2) |  |

### create(Vector2 v) {#create-com.aspose.threed.Vector2-}
```
public static FVector2 create(Vector2 v)
```


Τελεστής ρητής μετατροπής για τη μετατροπή του Vector2 σε FVector2

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| v | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2)
### cross(Vector2 v) {#cross-com.aspose.threed.Vector2-}
```
public double cross(Vector2 v)
```


Γινόμενο διανυσματικό δύο διανυσμάτων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| v | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
double
### div(Vector2 lhs, double rhs) {#div-com.aspose.threed.Vector2-double-}
```
public static Vector2 div(Vector2 lhs, double rhs)
```


Τελεστής διαίρεσης για το Vector2

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Left hand side value. |
| rhs | double | Τιμή δεξιάς πλευράς. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of division.
### dot(Vector2 rhs) {#dot-com.aspose.threed.Vector2-}
```
public double dot(Vector2 rhs)
```


Επιστρέφει το εσωτερικό γινόμενο δύο διανυσμάτων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Τιμή δεξιάς πλευράς. |

**Returns:**
double - The dot product of the two vectors.
### equals(Vector2 rhs) {#equals-com.aspose.threed.Vector2-}
```
public boolean equals(Vector2 rhs)
```


Ελέγξτε αν δύο vector2 είναι ίσα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Η τιμή της δεξιάς πλευράς. |

**Returns:**
boolean - True if all components are identically equal.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Ελέγξτε αν δύο vector2 είναι ίσα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το αντικείμενο προς σύγκριση. |

**Returns:**
boolean - True if all components are identically equal.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLength() {#getLength--}
```
public double getLength()
```


Λαμβάνει το μήκος.

**Returns:**
double - το μήκος.
### getU() {#getU--}
```
public double getU()
```


Αποκτά το συστατικό U εάν το [Vector2](../../com.aspose.threed/vector2) χρησιμοποιείται ως συντεταγμένη χαρτογράφησης. Είναι ψευδώνυμο του συστατικού x.

**Returns:**
double - το συστατικό U εάν το [Vector2](../../com.aspose.threed/vector2) χρησιμοποιείται ως συντεταγμένη χαρτογράφησης. Είναι ψευδώνυμο του συστατικού x.
### getV() {#getV--}
```
public double getV()
```


Αποκτά το συστατικό V εάν το [Vector2](../../com.aspose.threed/vector2) χρησιμοποιείται ως συντεταγμένη χαρτογράφησης. Είναι ψευδώνυμο του συστατικού y.

**Returns:**
double - το συστατικό V εάν το [Vector2](../../com.aspose.threed/vector2) χρησιμοποιείται ως συντεταγμένη χαρτογράφησης. Είναι ψευδώνυμο του συστατικού y.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Λαμβάνει τον κωδικό κατακερματισμού του Vector2

**Returns:**
int - Ο κωδικός κατακερματισμού του [Vector2](../../com.aspose.threed/vector2)
### mul(Vector2 lhs, double rhs) {#mul-com.aspose.threed.Vector2-double-}
```
public static Vector2 mul(Vector2 lhs, double rhs)
```


Τελεστής πολλαπλασιασμού για το Vector2

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Left hand side value. |
| rhs | double | Τιμή δεξιάς πλευράς. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of multiply.
### mul(double lhs, Vector2 rhs) {#mul-double-com.aspose.threed.Vector2-}
```
public static Vector2 mul(double lhs, Vector2 rhs)
```


Τελεστής πολλαπλασιασμού για το Vector2

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs | double | Left hand side value. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Τιμή δεξιάς πλευράς. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of multiply.
### normalize() {#normalize--}
```
public Vector2 normalize()
```


Κανονικοποιεί αυτήν την instance.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - Normalized vector.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_eq(Vector2 lhs, Vector2 rhs) {#op-eq-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static boolean op_eq(Vector2 lhs, Vector2 rhs)
```


Τελεστής ισότητας για Vector2

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Left hand side value. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Τιμή δεξιάς πλευράς. |

**Returns:**
boolean - True if all components are identically equal.
### op_ne(Vector2 lhs, Vector2 rhs) {#op-ne-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static boolean op_ne(Vector2 lhs, Vector2 rhs)
```


Τελεστής ανισότητας για Vector2

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Left hand side value. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Τιμή δεξιάς πλευράς. |

**Returns:**
boolean - True if two vectors are not equal.
### setU(double value) {#setU-double-}
```
public void setU(double value)
```


Ορίζει το συστατικό U εάν το [Vector2](../../com.aspose.threed/vector2) χρησιμοποιείται ως συντεταγμένη χαρτογράφησης. Είναι ψευδώνυμο του συστατικού x.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Νέα τιμή |

### setV(double value) {#setV-double-}
```
public void setV(double value)
```


Ορίζει το συστατικό V εάν το [Vector2](../../com.aspose.threed/vector2) χρησιμοποιείται ως συντεταγμένη χαρτογράφησης. Είναι ψευδώνυμο του συστατικού y.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Νέα τιμή |

### sub(Vector2 lhs, Vector2 rhs) {#sub-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static Vector2 sub(Vector2 lhs, Vector2 rhs)
```


Τελεστής αφαίρεσης για Vector2

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Left hand side value. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Τιμή δεξιάς πλευράς. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of substraction.
### toString() {#toString--}
```
public String toString()
```


Επιστρέφει ένα java.lang.String που αντιπροσωπεύει το τρέχον [Vector2](../../com.aspose.threed/vector2).

**Returns:**
java.lang.String - Ένα java.lang.String που αντιπροσωπεύει το τρέχον [Vector2](../../com.aspose.threed/vector2).
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

