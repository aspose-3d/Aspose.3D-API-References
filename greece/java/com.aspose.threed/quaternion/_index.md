---
title: "Quaternion"
second_title: "Aspose.3D for Java API Reference"
description: "Το Quaternion χρησιμοποιείται συνήθως για την εκτέλεση περιστροφής στην υπολογιστική γραφική."
type: docs
weight: 143
url: /el/java/com.aspose.threed/quaternion/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class Quaternion implements Struct<Quaternion>, Serializable
```

Το Quaternion χρησιμοποιείται συνήθως για την εκτέλεση περιστροφής στην υπολογιστική γραφική.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Quaternion(double w, double x, double y, double z)](#Quaternion-double-double-double-double-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Quaternion](../../com.aspose.threed/quaternion). |
| [Quaternion()](#Quaternion--) |  |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [IDENTITY](#IDENTITY) | Το quaternion ταυτότητας. |
| [w](#w) | Το w συστατικό. |
| [x](#x) | Το στοιχείο x. |
| [y](#y) | Το στοιχείο y. |
| [z](#z) | Το στοιχείο z. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [add(Quaternion lhs, Quaternion rhs)](#add-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Υπερφόρτωση τελεστή για + |
| [clone()](#clone--) |  |
| [concat(Quaternion rhs)](#concat-com.aspose.threed.Quaternion-) | Συνένωση δύο quaternion. |
| [conjugate()](#conjugate--) | Επιστρέφει ένα συζυγές quaternion του τρέχοντος quaternion. |
| [copyFrom(Quaternion src)](#copyFrom-com.aspose.threed.Quaternion-) |  |
| [div(Quaternion lhs, double rhs)](#div-com.aspose.threed.Quaternion-double-) | Υπερφόρτωση τελεστή για / |
| [dot(Quaternion q)](#dot-com.aspose.threed.Quaternion-) | Γινόμενο σημείων. |
| [equals(Object obj)](#equals-java.lang.Object-) | Έλεγχος εάν δύο quaternion είναι ίσα. |
| [eulerAngles()](#eulerAngles--) | Μετατρέπει το quaternion σε περιστροφή που αναπαρίσταται από γωνίες Euler. Όλα τα στοιχεία είναι σε ακτίνια. |
| [fromAngleAxis(double a, Vector3 axis)](#fromAngleAxis-double-com.aspose.threed.Vector3-) | Δημιουργεί ένα quaternion γύρω από τον δοσμένο άξονα και περιστρέφει δεξιόστροφα. |
| [fromEulerAngle(Vector3 eulerAngle)](#fromEulerAngle-com.aspose.threed.Vector3-) | Δημιουργεί quaternion από τη δοσμένη γωνία Euler. |
| [fromEulerAngle(double pitch, double yaw, double roll)](#fromEulerAngle-double-double-double-) | Δημιουργεί quaternion από τη δοσμένη γωνία Euler. |
| [fromRotation(Vector3 orig, Vector3 dest)](#fromRotation-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Δημιουργεί ένα quaternion που περιστρέφει από την αρχική προς την κατεύθυνση προορισμού. |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Λαμβάνει το μήκος του quaternion. |
| [hashCode()](#hashCode--) | Λαμβάνει τον κωδικό κατακερματισμού του Quaternion. |
| [interpolate(float t, Quaternion from, Quaternion to)](#interpolate-float-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Γεμίζει αυτό το quaternion με την παρεμβολή τιμής μεταξύ των δοσμένων επιχειρημάτων quaternion για t μεταξύ του από και του προς. |
| [inverse()](#inverse--) | Επιστρέφει ένα αντίστροφο quaternion του τρέχοντος quaternion. |
| [mul(Quaternion lhs, Quaternion rhs)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Υπερφόρτωση τελεστή για \* |
| [mul(Quaternion q, Vector3 v)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector3-) | Υπερφόρτωση τελεστή για \* |
| [mul(Quaternion q, Vector4 v)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector4-) | Υπερφόρτωση τελεστή για \* |
| [mul(Quaternion lhs, double rhs)](#mul-com.aspose.threed.Quaternion-double-) | Υπερφόρτωση τελεστή για \* |
| [mul(Vector3 v, Quaternion q)](#mul-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-) | Υπερφόρτωση τελεστή για \* |
| [normalize()](#normalize--) | Κανονικοποίηση του quaternion. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(Quaternion lhs, Quaternion rhs)](#op-eq-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Τελεστής ισότητας για quaternion. |
| [op_ne(Quaternion lhs, Quaternion rhs)](#op-ne-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Τελεστής ανισότητας για quaternion. |
| [slerp(double t, Quaternion v1, Quaternion v2)](#slerp-double-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Εκτελεί σφαιρική γραμμική παρεμβολή μεταξύ δύο τιμών. |
| [toAngleAxis(double[] angle, Vector3 axis)](#toAngleAxis-double---com.aspose.threed.Vector3-) | Αποσυνθέτει το quaternion σε γωνία και άξονα. |
| [toMatrix()](#toMatrix--) | Μετατρέπει την περιστροφή που παρουσιάζεται από το quaternion σε πίνακα μετασχηματισμού. |
| [toMatrix(Vector3 translation)](#toMatrix-com.aspose.threed.Vector3-) | Μετατρέπει την περιστροφή που παρουσιάζεται από το quaternion σε πίνακα μετασχηματισμού. |
| [toString()](#toString--) | Λαμβάνει την αναπαράσταση του quaternion ως συμβολοσειρά. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Quaternion(double w, double x, double y, double z) {#Quaternion-double-double-double-double-}
```
public Quaternion(double w, double x, double y, double z)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [Quaternion](../../com.aspose.threed/quaternion).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| w | double | Συστατικό w του quaternion |
| x | double | Συστατικό x του quaternion |
| y | double | συνιστώσα y του quaternion |
| z | double | συνιστώσα z του quaternion |

### Quaternion() {#Quaternion--}
```
public Quaternion()
```


### IDENTITY {#IDENTITY}
```
public static final Quaternion IDENTITY
```


Το quaternion ταυτότητας.

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

### add(Quaternion lhs, Quaternion rhs) {#add-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion add(Quaternion lhs, Quaternion rhs)
```


Υπερφόρτωση τελεστή για +

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Αριστερό quaternion |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Δεξί quaternion |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### clone() {#clone--}
```
public Quaternion clone()
```


Κλωνοποίηση τρέχουσας παρουσίας

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### concat(Quaternion rhs) {#concat-com.aspose.threed.Quaternion-}
```
public Quaternion concat(Quaternion rhs)
```


Συνένωση δύο quaternion.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) |  |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### conjugate() {#conjugate--}
```
public Quaternion conjugate()
```


Επιστρέφει ένα συζυγές quaternion του τρέχοντος quaternion.

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - The conjugate quaternion.
### copyFrom(Quaternion src) {#copyFrom-com.aspose.threed.Quaternion-}
```
public void copyFrom(Quaternion src)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| src | [Quaternion](../../com.aspose.threed/quaternion) |  |

### div(Quaternion lhs, double rhs) {#div-com.aspose.threed.Quaternion-double-}
```
public static Quaternion div(Quaternion lhs, double rhs)
```


Υπερφόρτωση τελεστή για /

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Αριστερό quaternion |
| rhs | double | Δεξί quaternion |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### dot(Quaternion q) {#dot-com.aspose.threed.Quaternion-}
```
public double dot(Quaternion q)
```


Γινόμενο σημείων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | Το quaternion |

**Returns:**
double - Τιμή Dot
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Έλεγχος εάν δύο quaternion είναι ίσα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το αντικείμενο για έλεγχο ισότητας. |

**Returns:**
boolean - Αληθές εάν όλα τα στοιχεία είναι ταυτόσημα ίσα.
### eulerAngles() {#eulerAngles--}
```
public Vector3 eulerAngles()
```


Μετατρέπει το quaternion σε περιστροφή που αναπαρίσταται από γωνίες Euler. Όλα τα στοιχεία είναι σε ακτίνια.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### fromAngleAxis(double a, Vector3 axis) {#fromAngleAxis-double-com.aspose.threed.Vector3-}
```
public static Quaternion fromAngleAxis(double a, Vector3 axis)
```


Δημιουργεί ένα quaternion γύρω από τον δοσμένο άξονα και περιστρέφει δεξιόστροφα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| α | double | Δεξιόστροφη περιστροφή σε ακτίνια |
| axis | [Vector3](../../com.aspose.threed/vector3) | Άξονας |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromEulerAngle(Vector3 eulerAngle) {#fromEulerAngle-com.aspose.threed.Vector3-}
```
public static Quaternion fromEulerAngle(Vector3 eulerAngle)
```


Δημιουργεί quaternion από τη δοσμένη γωνία Euler.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| eulerAngle | [Vector3](../../com.aspose.threed/vector3) | Γωνία Euler σε ακτίνια |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromEulerAngle(double pitch, double yaw, double roll) {#fromEulerAngle-double-double-double-}
```
public static Quaternion fromEulerAngle(double pitch, double yaw, double roll)
```


Δημιουργεί quaternion από τη δοσμένη γωνία Euler.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pitch | double | Κλίση σε ακτίνια |
| yaw | double | Yaw σε ακτίνια |
| κύλιση | double | Κύλιση σε ακτίνια |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromRotation(Vector3 orig, Vector3 dest) {#fromRotation-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Quaternion fromRotation(Vector3 orig, Vector3 dest)
```


Δημιουργεί ένα quaternion που περιστρέφει από την αρχική προς την κατεύθυνση προορισμού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| orig | [Vector3](../../com.aspose.threed/vector3) | Αρχική κατεύθυνση |
| dest | [Vector3](../../com.aspose.threed/vector3) | Κατεύθυνση προορισμού |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
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


Λαμβάνει το μήκος του quaternion.

**Returns:**
double - το μήκος του quaternion
### hashCode() {#hashCode--}
```
public int hashCode()
```


Λαμβάνει τον κωδικό κατακερματισμού του Quaternion.

**Returns:**
int - Ο κωδικός κατακερματισμού του [Quaternion](../../com.aspose.threed/quaternion)
### interpolate(float t, Quaternion from, Quaternion to) {#interpolate-float-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion interpolate(float t, Quaternion from, Quaternion to)
```


Γεμίζει αυτό το quaternion με την παρεμβολή τιμής μεταξύ των δοσμένων επιχειρημάτων quaternion για t μεταξύ του από και του προς.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| t | float | Ο συντελεστής για παρεμβολή. |
| from | [Quaternion](../../com.aspose.threed/quaternion) | Quaternion πηγής. |
| to | [Quaternion](../../com.aspose.threed/quaternion) | Quaternion στόχου. |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - The interpolated quaternion.
### inverse() {#inverse--}
```
public Quaternion inverse()
```


Επιστρέφει ένα αντίστροφο quaternion του τρέχοντος quaternion.

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Inverse quaternion.
### mul(Quaternion lhs, Quaternion rhs) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion mul(Quaternion lhs, Quaternion rhs)
```


Υπερφόρτωση τελεστή για \*

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Αριστερό quaternion |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Δεξί quaternion |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### mul(Quaternion q, Vector3 v) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector3-}
```
public static Vector3 mul(Quaternion q, Vector3 v)
```


Υπερφόρτωση τελεστή για \*

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | Το quaternion περιστροφής |
| v | [Vector3](../../com.aspose.threed/vector3) | Διάνυσμα προς περιστροφή |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Rotated vector
### mul(Quaternion q, Vector4 v) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector4-}
```
public static Vector4 mul(Quaternion q, Vector4 v)
```


Υπερφόρτωση τελεστή για \*

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | Το quaternion περιστροφής |
| v | [Vector4](../../com.aspose.threed/vector4) | Διάνυσμα προς περιστροφή |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Rotated vector
### mul(Quaternion lhs, double rhs) {#mul-com.aspose.threed.Quaternion-double-}
```
public static Quaternion mul(Quaternion lhs, double rhs)
```


Υπερφόρτωση τελεστή για \*

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Αριστερό quaternion |
| rhs | double | Δεξί quaternion |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### mul(Vector3 v, Quaternion q) {#mul-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-}
```
public static Vector3 mul(Vector3 v, Quaternion q)
```


Υπερφόρτωση τελεστή για \*

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) | Το quaternion περιστροφής |
| q | [Quaternion](../../com.aspose.threed/quaternion) | Διάνυσμα προς περιστροφή |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Rotated vector
### normalize() {#normalize--}
```
public Quaternion normalize()
```


Κανονικοποίηση του quaternion.

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Normalized quaternion.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_eq(Quaternion lhs, Quaternion rhs) {#op-eq-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static boolean op_eq(Quaternion lhs, Quaternion rhs)
```


Τελεστής ισότητας για quaternion.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Τιμή αριστερής πλευράς. |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Τιμή δεξιάς πλευράς. |

**Returns:**
boolean - Αληθές εάν όλα τα στοιχεία είναι ταυτόσημα ίσα.
### op_ne(Quaternion lhs, Quaternion rhs) {#op-ne-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static boolean op_ne(Quaternion lhs, Quaternion rhs)
```


Τελεστής ανισότητας για quaternion.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Τιμή αριστερής πλευράς. |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Τιμή δεξιάς πλευράς. |

**Returns:**
boolean - Αληθές εάν δύο τετραδόνια δεν είναι ίσα.
### slerp(double t, Quaternion v1, Quaternion v2) {#slerp-double-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion slerp(double t, Quaternion v1, Quaternion v2)
```


Εκτελεί σφαιρική γραμμική παρεμβολή μεταξύ δύο τιμών.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| t | double | t είναι μεταξύ 0 και 1 |
| v1 | [Quaternion](../../com.aspose.threed/quaternion) | Πρώτη τιμή |
| v2 | [Quaternion](../../com.aspose.threed/quaternion) | Δεύτερη τιμή |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### toAngleAxis(double[] angle, Vector3 axis) {#toAngleAxis-double---com.aspose.threed.Vector3-}
```
public void toAngleAxis(double[] angle, Vector3 axis)
```


Αποσυνθέτει το quaternion σε γωνία και άξονα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| γωνία | double[] | Η γωνία περιστροφής, σε ακτίνια. |
| axis | [Vector3](../../com.aspose.threed/vector3) | Ο άξονας γύρω από τον οποίο περιστρέφεται. |

### toMatrix() {#toMatrix--}
```
public Matrix4 toMatrix()
```


Μετατρέπει την περιστροφή που παρουσιάζεται από το quaternion σε πίνακα μετασχηματισμού.

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - The matrix representation of current quaternion.
### toMatrix(Vector3 translation) {#toMatrix-com.aspose.threed.Vector3-}
```
public Matrix4 toMatrix(Vector3 translation)
```


Μετατρέπει την περιστροφή που παρουσιάζεται από το quaternion σε πίνακα μετασχηματισμού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| translation | [Vector3](../../com.aspose.threed/vector3) | Το τμήμα μετάφρασης του πίνακα. |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - The matrix representation of current quaternion.
### toString() {#toString--}
```
public String toString()
```


Λαμβάνει την αναπαράσταση του quaternion ως συμβολοσειρά.

**Returns:**
java.lang.String - Συμβολοσειρά αντικειμένου
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

