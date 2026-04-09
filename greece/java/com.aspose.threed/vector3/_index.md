---
title: Vector3
second_title: Aspose.3D for Java API Reference
description: Διανύσμα με τρεις συνιστώσες.
type: docs
weight: 202
url: /el/java/com.aspose.threed/vector3/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.threed.Struct, java.io.Serializable
```
public final class Vector3 implements Comparable<Vector3>, Struct<Vector3>, Serializable
```

Διανύσμα με τρεις συνιστώσες.
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [Vector3(double x, double y, double z)](#Vector3-double-double-double-) | Αρχικοποιεί μια νέα παρουσία του δομικού τύπου [Vector3](../../com.aspose.threed/vector3). |
| [Vector3(FVector3 vec)](#Vector3-com.aspose.threed.FVector3-) | Αρχικοποιεί μια νέα παρουσία του δομικού τύπου [Vector3](../../com.aspose.threed/vector3). |
| [Vector3(double v)](#Vector3-double-) | Αρχικοποιεί μια νέα παρουσία του δομικού τύπου [Vector3](../../com.aspose.threed/vector3). |
| [Vector3(Vector4 vec4)](#Vector3-com.aspose.threed.Vector4-) | Αρχικοποιεί μια νέα παρουσία του δομικού τύπου [Vector3](../../com.aspose.threed/vector3). |
| [Vector3()](#Vector3--) |  |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [x](#x) | Το στοιχείο x. |
| [y](#y) | Το στοιχείο y. |
| [z](#z) | Το στοιχείο z. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [add(Vector3 lhs, Vector3 rhs)](#add-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Υπερφόρτωση τελεστή για + |
| [angleBetween(Vector3 dir)](#angleBetween-com.aspose.threed.Vector3-) | Υπολογίζει τη εσωτερική γωνία μεταξύ δύο διευθύνσεων. Οι δύο διευθύνσεις μπορούν να είναι μη κανονικοποιημένα διανύσματα. |
| [angleBetween(Vector3 dir, Vector3 up)](#angleBetween-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Υπολογίζει τη εσωτερική γωνία μεταξύ δύο διευθύνσεων. Οι δύο διευθύνσεις μπορούν να είναι μη κανονικοποιημένα διανύσματα. |
| [clone()](#clone--) |  |
| [compareTo(Vector3 other)](#compareTo-com.aspose.threed.Vector3-) | Συγκρίνει το τρέχον διάνυσμα με μια άλλη παρουσία. |
| [copyFrom(Vector3 src)](#copyFrom-com.aspose.threed.Vector3-) |  |
| [cos()](#cos--) | Υπολογίζει το συνημίτονο σε κάθε στοιχείο. |
| [create(Vector3 v)](#create-com.aspose.threed.Vector3-) | Συγκεκριμένος τελεστής μετατροπής για μετατροπή του Vector3 σε FVector3 |
| [cross(Vector3 rhs)](#cross-com.aspose.threed.Vector3-) | Γινόμενο διανυσματικό δύο διανυσμάτων. |
| [div(Vector3 lhs, Vector3 rhs)](#div-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Υπερφόρτωση τελεστή για / |
| [div(Vector3 lhs, double rhs)](#div-com.aspose.threed.Vector3-double-) | Υπερφόρτωση τελεστή για / |
| [dot(Vector3 rhs)](#dot-com.aspose.threed.Vector3-) | Επιστρέφει το εσωτερικό γινόμενο δύο διανυσμάτων. |
| [equals(Object obj)](#equals-java.lang.Object-) | Ελέγχει αν δύο vector3 είναι ίσα. |
| [get(int idx)](#get-int-) | Επιστρέφει το στοιχείο του διανύσματος με βάση το δείκτη. |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Επιστρέφει το μέγεθος αυτού του διανύσματος. |
| [getLength2()](#getLength2--) | Επιστρέφει το τετράγωνο του μήκους. |
| [getOne()](#getOne--) | Επιστρέφει το μοναδιαίο διάνυσμα (1, 1, 1). |
| [getUnitX()](#getUnitX--) | Επιστρέφει το μοναδιαίο διάνυσμα (1, 0, 0). |
| [getUnitY()](#getUnitY--) | Επιστρέφει το μοναδιαίο διάνυσμα (0, 1, 0). |
| [getUnitZ()](#getUnitZ--) | Επιστρέφει το μοναδιαίο διάνυσμα (0, 0, 1). |
| [getZero()](#getZero--) | Επιστρέφει το μοναδιαίο διάνυσμα (0, 0, 0). |
| [hashCode()](#hashCode--) | Επιστρέφει τον κωδικό κατακερματισμού του Vector3. |
| [mul(Vector3 lhs, Vector3 rhs)](#mul-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Υπερφόρτωση τελεστή για \* |
| [mul(Vector3 lhs, double rhs)](#mul-com.aspose.threed.Vector3-double-) | Υπερφόρτωση τελεστή για \* |
| [mul(double lhs, Vector3 rhs)](#mul-double-com.aspose.threed.Vector3-) | Υπερφόρτωση τελεστή για \* |
| [negative(Vector3 v)](#negative-com.aspose.threed.Vector3-) | Operator overloading for - |
| [normalize()](#normalize--) | Κανονικοποιεί αυτήν την instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(Vector3 lhs, Vector3 rhs)](#op-eq-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Equal operator for Vector3 |
| [op_ne(Vector3 lhs, Vector3 rhs)](#op-ne-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Not-equal operator for Vector3 |
| [set(double newX, double newY, double newZ)](#set-double-double-double-) | Ορίζει τα συστατικά x/y/z σε μία κλήση. |
| [set(int idx, double value)](#set-int-double-) | Sets vector's component by index. |
| [sin()](#sin--) | Υπολογίζει το ημίτονο σε κάθε συνιστώσα. |
| [sub(Vector3 lhs, Vector3 rhs)](#sub-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Operator overloading for - (minus) |
| [toString()](#toString--) | Returns a java.lang.String that represents the current [Vector3](../../com.aspose.threed/vector3). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Vector3(double x, double y, double z) {#Vector3-double-double-double-}
```
public Vector3(double x, double y, double z)
```


Αρχικοποιεί μια νέα παρουσία του δομικού τύπου [Vector3](../../com.aspose.threed/vector3).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | double | The x coordinate. |
| y | double | The y coordinate. |
| z | double | The z coordinate. |

### Vector3(FVector3 vec) {#Vector3-com.aspose.threed.FVector3-}
```
public Vector3(FVector3 vec)
```


Αρχικοποιεί μια νέα παρουσία του δομικού τύπου [Vector3](../../com.aspose.threed/vector3).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| vec | [FVector3](../../com.aspose.threed/fvector3) | The x coordinate. |

### Vector3(double v) {#Vector3-double-}
```
public Vector3(double v)
```


Αρχικοποιεί μια νέα παρουσία του δομικού τύπου [Vector3](../../com.aspose.threed/vector3).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| v | double | V. |

### Vector3(Vector4 vec4) {#Vector3-com.aspose.threed.Vector4-}
```
public Vector3(Vector4 vec4)
```


Αρχικοποιεί μια νέα παρουσία του δομικού τύπου [Vector3](../../com.aspose.threed/vector3).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| vec4 | [Vector4](../../com.aspose.threed/vector4) | Vec4. |

### Vector3() {#Vector3--}
```
public Vector3()
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

### z {#z}
```
public double z
```


Το στοιχείο z.

### add(Vector3 lhs, Vector3 rhs) {#add-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 add(Vector3 lhs, Vector3 rhs)
```


Υπερφόρτωση τελεστή για +

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | The left vector |
| rhs | [Vector3](../../com.aspose.threed/vector3) | The right vector |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### angleBetween(Vector3 dir) {#angleBetween-com.aspose.threed.Vector3-}
```
public double angleBetween(Vector3 dir)
```


Υπολογίζει τη εσωτερική γωνία μεταξύ δύο διευθύνσεων. Οι δύο διευθύνσεις μπορούν να είναι μη κανονικοποιημένα διανύσματα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dir | [Vector3](../../com.aspose.threed/vector3) | Το διάνυσμα κατεύθυνσης για σύγκριση. |

**Returns:**
double - inner angle in radian
### angleBetween(Vector3 dir, Vector3 up) {#angleBetween-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public double angleBetween(Vector3 dir, Vector3 up)
```


Υπολογίζει τη εσωτερική γωνία μεταξύ δύο διευθύνσεων. Οι δύο διευθύνσεις μπορούν να είναι μη κανονικοποιημένα διανύσματα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dir | [Vector3](../../com.aspose.threed/vector3) | Το διάνυσμα κατεύθυνσης για σύγκριση. |
| up | [Vector3](../../com.aspose.threed/vector3) | Το διάνυσμα up του κοινόχρηστου επιπέδου των δύο κατευθύνσεων. |

**Returns:**
double - inner angle in radian
### clone() {#clone--}
```
public Vector3 clone()
```


Clone current instance

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### compareTo(Vector3 other) {#compareTo-com.aspose.threed.Vector3-}
```
public int compareTo(Vector3 other)
```


Συγκρίνει το τρέχον διάνυσμα με μια άλλη παρουσία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| other | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
int
### copyFrom(Vector3 src) {#copyFrom-com.aspose.threed.Vector3-}
```
public void copyFrom(Vector3 src)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| src | [Vector3](../../com.aspose.threed/vector3) |  |

### cos() {#cos--}
```
public Vector3 cos()
```


Υπολογίζει το συνημίτονο σε κάθε στοιχείο.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Calculated [Vector3](../../com.aspose.threed/vector3).
### create(Vector3 v) {#create-com.aspose.threed.Vector3-}
```
public static FVector3 create(Vector3 v)
```


Συγκεκριμένος τελεστής μετατροπής για μετατροπή του Vector3 σε FVector3

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### cross(Vector3 rhs) {#cross-com.aspose.threed.Vector3-}
```
public Vector3 cross(Vector3 rhs)
```


Γινόμενο διανυσματικό δύο διανυσμάτων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Τιμή δεξιάς πλευράς. |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Cross product of two [Vector3](../../com.aspose.threed/vector3)s.
### div(Vector3 lhs, Vector3 rhs) {#div-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 div(Vector3 lhs, Vector3 rhs)
```


Υπερφόρτωση τελεστή για /

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | The left vector |
| rhs | [Vector3](../../com.aspose.threed/vector3) | The right vector |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### div(Vector3 lhs, double rhs) {#div-com.aspose.threed.Vector3-double-}
```
public static Vector3 div(Vector3 lhs, double rhs)
```


Υπερφόρτωση τελεστή για /

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | The left vector |
| rhs | double | The right double value |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### dot(Vector3 rhs) {#dot-com.aspose.threed.Vector3-}
```
public double dot(Vector3 rhs)
```


Επιστρέφει το εσωτερικό γινόμενο δύο διανυσμάτων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Τιμή δεξιάς πλευράς. |

**Returns:**
double - The dot product of the two vectors.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Ελέγχει αν δύο vector3 είναι ίσα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το αντικείμενο για έλεγχο ισότητας. |

**Returns:**
boolean - True if all components are identically equal.
### get(int idx) {#get-int-}
```
public double get(int idx)
```


Επιστρέφει το στοιχείο του διανύσματος με βάση το δείκτη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| idx | int |  |

**Returns:**
double - vector's component by index.
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


Επιστρέφει το μέγεθος αυτού του διανύσματος.

**Returns:**
double - the length of this vector.
### getLength2() {#getLength2--}
```
public double getLength2()
```


Επιστρέφει το τετράγωνο του μήκους.

**Returns:**
double - the square of the length.
### getOne() {#getOne--}
```
public static Vector3 getOne()
```


Επιστρέφει το μοναδιαίο διάνυσμα (1, 1, 1).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (1, 1, 1)
### getUnitX() {#getUnitX--}
```
public static Vector3 getUnitX()
```


Επιστρέφει το μοναδιαίο διάνυσμα (1, 0, 0).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (1, 0, 0)
### getUnitY() {#getUnitY--}
```
public static Vector3 getUnitY()
```


Επιστρέφει το μοναδιαίο διάνυσμα (0, 1, 0).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (0, 1, 0)
### getUnitZ() {#getUnitZ--}
```
public static Vector3 getUnitZ()
```


Επιστρέφει το μοναδιαίο διάνυσμα (0, 0, 1).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (0, 0, 1)
### getZero() {#getZero--}
```
public static Vector3 getZero()
```


Επιστρέφει το μοναδιαίο διάνυσμα (0, 0, 0).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (0, 0, 0)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει τον κωδικό κατακερματισμού του Vector3.

**Returns:**
int - The hash code of the [Vector3](../../com.aspose.threed/vector3)
### mul(Vector3 lhs, Vector3 rhs) {#mul-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 mul(Vector3 lhs, Vector3 rhs)
```


Υπερφόρτωση τελεστή για \*

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | The left vector |
| rhs | [Vector3](../../com.aspose.threed/vector3) | The right vector |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### mul(Vector3 lhs, double rhs) {#mul-com.aspose.threed.Vector3-double-}
```
public static Vector3 mul(Vector3 lhs, double rhs)
```


Υπερφόρτωση τελεστή για \*

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | The left vector |
| rhs | double | The right double value |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### mul(double lhs, Vector3 rhs) {#mul-double-com.aspose.threed.Vector3-}
```
public static Vector3 mul(double lhs, Vector3 rhs)
```


Υπερφόρτωση τελεστή για \*

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs | double | The left scalar |
| rhs | [Vector3](../../com.aspose.threed/vector3) | The right vector |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### negative(Vector3 v) {#negative-com.aspose.threed.Vector3-}
```
public static Vector3 negative(Vector3 v)
```


Operator overloading for -

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) | The origin vector |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### normalize() {#normalize--}
```
public Vector3 normalize()
```


Κανονικοποιεί αυτήν την instance.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Normalized vector.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_eq(Vector3 lhs, Vector3 rhs) {#op-eq-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static boolean op_eq(Vector3 lhs, Vector3 rhs)
```


Equal operator for Vector3

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Left hand side value. |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Τιμή δεξιάς πλευράς. |

**Returns:**
boolean - True if all components are identically equal.
### op_ne(Vector3 lhs, Vector3 rhs) {#op-ne-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static boolean op_ne(Vector3 lhs, Vector3 rhs)
```


Not-equal operator for Vector3

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Left hand side value. |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Τιμή δεξιάς πλευράς. |

**Returns:**
boolean - True if two vectors are not equal.
### set(double newX, double newY, double newZ) {#set-double-double-double-}
```
public void set(double newX, double newY, double newZ)
```


Ορίζει τα συστατικά x/y/z σε μία κλήση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newX | double | Το στοιχείο x. |
| newY | double | Το στοιχείο y. |
| newZ | double | Το στοιχείο z. |

### set(int idx, double value) {#set-int-double-}
```
public void set(int idx, double value)
```


Sets vector's component by index.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| idx | int |  |
| τιμή | double | Νέα τιμή |

### sin() {#sin--}
```
public Vector3 sin()
```


Υπολογίζει το ημίτονο σε κάθε συνιστώσα.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Calculated [Vector3](../../com.aspose.threed/vector3).
### sub(Vector3 lhs, Vector3 rhs) {#sub-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 sub(Vector3 lhs, Vector3 rhs)
```


Operator overloading for - (minus)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | The left vector |
| rhs | [Vector3](../../com.aspose.threed/vector3) | The right vector |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### toString() {#toString--}
```
public String toString()
```


Returns a java.lang.String that represents the current [Vector3](../../com.aspose.threed/vector3).

**Returns:**
java.lang.String - A java.lang.String that represents the current [Vector3](../../com.aspose.threed/vector3).
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

