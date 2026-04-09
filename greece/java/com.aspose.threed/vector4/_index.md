---
title: Vector4
second_title: Aspose.3D for Java API Reference
description: Διανύσμα με τέσσερις συνιστώσες.
type: docs
weight: 203
url: /el/java/com.aspose.threed/vector4/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.threed.Struct, java.io.Serializable
```
public final class Vector4 implements Comparable<Vector4>, Struct<Vector4>, Serializable
```

Διανύσμα με τέσσερις συνιστώσες.
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [Vector4(Vector3 vec, double w)](#Vector4-com.aspose.threed.Vector3-double-) | Αρχικοποιεί ένα νέο στιγμιότυπο της δομής [Vector4](../../com.aspose.threed/vector4). |
| [Vector4(Vector3 vec)](#Vector4-com.aspose.threed.Vector3-) | Αρχικοποιεί ένα νέο στιγμιότυπο της δομής [Vector4](../../com.aspose.threed/vector4). |
| [Vector4(FVector4 vec)](#Vector4-com.aspose.threed.FVector4-) | Αρχικοποιεί ένα νέο στιγμιότυπο της δομής [Vector4](../../com.aspose.threed/vector4). |
| [Vector4(double x, double y, double z)](#Vector4-double-double-double-) | Αρχικοποιεί ένα νέο στιγμιότυπο της δομής [Vector4](../../com.aspose.threed/vector4). |
| [Vector4(double x, double y, double z, double w)](#Vector4-double-double-double-double-) | Αρχικοποιεί ένα νέο στιγμιότυπο της δομής [Vector4](../../com.aspose.threed/vector4). |
| [Vector4()](#Vector4--) |  |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [w](#w) | Το w συστατικό. |
| [x](#x) | Το στοιχείο x. |
| [y](#y) | Το στοιχείο y. |
| [z](#z) | Το στοιχείο z. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [add(Vector4 lhs, Vector4 rhs)](#add-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | Υπερφόρτωση τελεστή για + |
| [clone()](#clone--) |  |
| [compareTo(Vector4 other)](#compareTo-com.aspose.threed.Vector4-) | Συγκρίνει το τρέχον διάνυσμα με μια άλλη παρουσία. |
| [copyFrom(Vector4 src)](#copyFrom-com.aspose.threed.Vector4-) |  |
| [create(Vector4 v)](#create-com.aspose.threed.Vector4-) | Συγκεκριμένος τελεστής μετατροπής για μετατροπή του Vector4 σε FVector4 |
| [equals(Object obj)](#equals-java.lang.Object-) | Check if two vectors are equal |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | Λαμβάνει τον κωδικό κατακερματισμού αυτού του διανύσματος |
| [mul(Vector4 lhs, Vector4 rhs)](#mul-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | Υπερφόρτωση τελεστή για \* |
| [mul(Vector4 lhs, double rhs)](#mul-com.aspose.threed.Vector4-double-) | Υπερφόρτωση τελεστή για \* |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [set(double newX, double newY, double newZ)](#set-double-double-double-) | Ορίζει τα xyz συστατικά του διανύσματος ταυτόχρονα, το w θα οριστεί σε 1 |
| [set(double newX, double newY, double newZ, double newW)](#set-double-double-double-double-) | Ορίζει όλα τα συστατικά του διανύσματος ταυτόχρονα |
| [sub(Vector4 lhs, Vector4 rhs)](#sub-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | Operator overloading for - (minus) |
| [toString()](#toString--) | Επιστρέφει ένα java.lang.String που αντιπροσωπεύει το τρέχον [Vector4](../../com.aspose.threed/vector4). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Vector4(Vector3 vec, double w) {#Vector4-com.aspose.threed.Vector3-double-}
```
public Vector4(Vector3 vec, double w)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της δομής [Vector4](../../com.aspose.threed/vector4).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) | Vec. |
| w | double | Το πλάτος. |

### Vector4(Vector3 vec) {#Vector4-com.aspose.threed.Vector3-}
```
public Vector4(Vector3 vec)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της δομής [Vector4](../../com.aspose.threed/vector4).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) | Vec. |

### Vector4(FVector4 vec) {#Vector4-com.aspose.threed.FVector4-}
```
public Vector4(FVector4 vec)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της δομής [Vector4](../../com.aspose.threed/vector4).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| vec | [FVector4](../../com.aspose.threed/fvector4) | Vec. |

### Vector4(double x, double y, double z) {#Vector4-double-double-double-}
```
public Vector4(double x, double y, double z)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της δομής [Vector4](../../com.aspose.threed/vector4).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | double | The x coordinate. |
| y | double | The y coordinate. |
| z | double | The z coordinate. |

### Vector4(double x, double y, double z, double w) {#Vector4-double-double-double-double-}
```
public Vector4(double x, double y, double z, double w)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της δομής [Vector4](../../com.aspose.threed/vector4).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | double | The x coordinate. |
| y | double | The y coordinate. |
| z | double | The z coordinate. |
| w | double | Το πλάτος. |

### Vector4() {#Vector4--}
```
public Vector4()
```


### w {#w}
```
public double w
```


Το w συστατικό.

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

### z {#z}
```
public double z
```


Το στοιχείο z.

### add(Vector4 lhs, Vector4 rhs) {#add-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public static Vector4 add(Vector4 lhs, Vector4 rhs)
```


Υπερφόρτωση τελεστή για +

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | The left vector |
| rhs | [Vector4](../../com.aspose.threed/vector4) | The right vector |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### clone() {#clone--}
```
public Vector4 clone()
```


Clone current instance

**Returns:**
[Vector4](../../com.aspose.threed/vector4)
### compareTo(Vector4 other) {#compareTo-com.aspose.threed.Vector4-}
```
public int compareTo(Vector4 other)
```


Συγκρίνει το τρέχον διάνυσμα με μια άλλη παρουσία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| other | [Vector4](../../com.aspose.threed/vector4) |  |

**Returns:**
int
### copyFrom(Vector4 src) {#copyFrom-com.aspose.threed.Vector4-}
```
public void copyFrom(Vector4 src)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| src | [Vector4](../../com.aspose.threed/vector4) |  |

### create(Vector4 v) {#create-com.aspose.threed.Vector4-}
```
public static FVector4 create(Vector4 v)
```


Συγκεκριμένος τελεστής μετατροπής για μετατροπή του Vector4 σε FVector4

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| v | [Vector4](../../com.aspose.threed/vector4) |  |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Check if two vectors are equal

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public int hashCode()
```


Λαμβάνει τον κωδικό κατακερματισμού αυτού του διανύσματος

**Returns:**
int
### mul(Vector4 lhs, Vector4 rhs) {#mul-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public static Vector4 mul(Vector4 lhs, Vector4 rhs)
```


Υπερφόρτωση τελεστή για \*

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | The left vector |
| rhs | [Vector4](../../com.aspose.threed/vector4) | The right vector |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### mul(Vector4 lhs, double rhs) {#mul-com.aspose.threed.Vector4-double-}
```
public static Vector4 mul(Vector4 lhs, double rhs)
```


Υπερφόρτωση τελεστή για \*

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | The left vector |
| rhs | double | The right double value |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### set(double newX, double newY, double newZ) {#set-double-double-double-}
```
public void set(double newX, double newY, double newZ)
```


Ορίζει τα xyz συστατικά του διανύσματος ταυτόχρονα, το w θα οριστεί σε 1

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newX | double | Νέο συστατικό X. |
| newY | double | Νέο συστατικό Y. |
| newZ | double | Νέο συστατικό Z. |

### set(double newX, double newY, double newZ, double newW) {#set-double-double-double-double-}
```
public void set(double newX, double newY, double newZ, double newW)
```


Ορίζει όλα τα συστατικά του διανύσματος ταυτόχρονα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newX | double | Νέο συστατικό X. |
| newY | double | Νέο συστατικό Y. |
| newZ | double | Νέο συστατικό Z. |
| newW | double | Νέο στοιχείο W. |

### sub(Vector4 lhs, Vector4 rhs) {#sub-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public static Vector4 sub(Vector4 lhs, Vector4 rhs)
```


Operator overloading for - (minus)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | The left vector |
| rhs | [Vector4](../../com.aspose.threed/vector4) | The right vector |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### toString() {#toString--}
```
public String toString()
```


Επιστρέφει ένα java.lang.String που αντιπροσωπεύει το τρέχον [Vector4](../../com.aspose.threed/vector4).

**Returns:**
java.lang.String - Ένα java.lang.String που αντιπροσωπεύει το τρέχον [Vector4](../../com.aspose.threed/vector4).
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

