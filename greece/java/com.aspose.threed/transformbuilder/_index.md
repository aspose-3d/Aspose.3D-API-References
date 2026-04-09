---
title: TransformBuilder
second_title: Aspose.3D for Java API Reference
description: Το  χρησιμοποιείται για την κατασκευή του μετασχηματιστικού πίνακα μέσω μιας αλυσίδας μετασχηματισμών.
type: docs
weight: 191
url: /el/java/com.aspose.threed/transformbuilder/
---

**Inheritance:**
java.lang.Object
```
public class TransformBuilder
```

Το [TransformBuilder](../../com.aspose.threed/transformbuilder) χρησιμοποιείται για την κατασκευή του μετασχηματιστικού πίνακα μέσω μιας αλυσίδας μετασχηματισμών. **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε έναν πίνακα με ένα σύνολο λειτουργιών

```
TransformBuilder tb = new TransformBuilder();
     tb.translate(10, 20, 0);
     tb.scale(10, 10, 10);
     tb.rotateEulerDegree(90, 0, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [TransformBuilder(Matrix4 initial, ComposeOrder order)](#TransformBuilder-com.aspose.threed.Matrix4-com.aspose.threed.ComposeOrder-) | Δομήστε ένα [TransformBuilder](../../com.aspose.threed/transformbuilder) με αρχικό μετασχηματιστικό πίνακα και καθορισμένη σειρά σύνθεσης |
| [TransformBuilder(ComposeOrder order)](#TransformBuilder-com.aspose.threed.ComposeOrder-) | Δομήστε ένα [TransformBuilder](../../com.aspose.threed/transformbuilder) με αρχικό πίνακα ταυτότητας και καθορισμένη σειρά σύνθεσης |
| [TransformBuilder()](#TransformBuilder--) | Δομήστε ένα [TransformBuilder](../../com.aspose.threed/transformbuilder) με αρχικό πίνακα ταυτότητας και καθορισμένη σειρά σύνθεσης |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [append(Matrix4 m)](#append-com.aspose.threed.Matrix4-) | Προσθέστε τον νέο μετασχηματιστικό πίνακα στην αλυσίδα μετασχηματισμών. |
| [compose(Matrix4 m)](#compose-com.aspose.threed.Matrix4-) | Προσθέστε ή προσαρτήστε το όρισμα στον εσωτερικό πίνακα. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getComposeOrder()](#getComposeOrder--) | Λαμβάνει τη σειρά σύνθεσης της αλυσίδας. |
| [getMatrix()](#getMatrix--) | Λαμβάνει την τρέχουσα τιμή του πίνακα |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [prepend(Matrix4 m)](#prepend-com.aspose.threed.Matrix4-) | Προσαρτήστε τον νέο μετασχηματιστικό πίνακα στην αλυσίδα μετασχηματισμών. |
| [rearrange(Axis newX, Axis newY, Axis newZ)](#rearrange-com.aspose.threed.Axis-com.aspose.threed.Axis-com.aspose.threed.Axis-) | Αναδιατάξτε τη διάταξη του άξονα. |
| [reset()](#reset--) | Επαναφέρετε τον μετασχηματισμό στον πίνακα ταυτότητας |
| [rotate(Quaternion q)](#rotate-com.aspose.threed.Quaternion-) | Συνδέστε μια περιστροφή με ένα quaternion **Example:** |
| [rotateDegree(Vector3 rot, RotationOrder order)](#rotateDegree-com.aspose.threed.Vector3-com.aspose.threed.RotationOrder-) | Προσθέστε περιστροφή με καθορισμένη σειρά |
| [rotateDegree(double angle, Vector3 axis)](#rotateDegree-double-com.aspose.threed.Vector3-) | Συνδέστε έναν μετασχηματισμό περιστροφής σε μοίρες |
| [rotateEulerDegree(double degX, double degY, double degZ)](#rotateEulerDegree-double-double-double-) | Συνδέστε μια περιστροφή με γωνίες Euler σε μοίρες **Example:** |
| [rotateEulerRadian(Vector3 r)](#rotateEulerRadian-com.aspose.threed.Vector3-) | Συνδέστε μια περιστροφή με γωνίες Euler σε ακτίνια **Example:** |
| [rotateEulerRadian(double x, double y, double z)](#rotateEulerRadian-double-double-double-) | Συνδέστε μια περιστροφή με γωνίες Euler σε ακτίνια **Example:** |
| [rotateRadian(Vector3 rot, RotationOrder order)](#rotateRadian-com.aspose.threed.Vector3-com.aspose.threed.RotationOrder-) | Προσθέστε περιστροφή με καθορισμένη σειρά |
| [rotateRadian(double angle, Vector3 axis)](#rotateRadian-double-com.aspose.threed.Vector3-) | Συνδέστε έναν μετασχηματισμό περιστροφής σε ακτίνια |
| [scale(Vector3 s)](#scale-com.aspose.threed.Vector3-) | Συνδέστε έναν μετασχηματισμό κλίμακας **Example:** |
| [scale(double s)](#scale-double-) | Συνδέστε έναν πίνακα μετασχηματισμού κλιμάκωσης με ένα στοιχείο κλιμακωμένο κατά s **Example:** |
| [scale(double x, double y, double z)](#scale-double-double-double-) | Συνδέστε έναν πίνακα μετασχηματισμού κλιμάκωσης **Example:** |
| [setComposeOrder(ComposeOrder value)](#setComposeOrder-com.aspose.threed.ComposeOrder-) | Ορίζει τη σειρά σύνθεσης της αλυσίδας. |
| [setMatrix(Matrix4 value)](#setMatrix-com.aspose.threed.Matrix4-) | Ορίζει την τρέχουσα τιμή του πίνακα |
| [toString()](#toString--) |  |
| [translate(Vector3 v)](#translate-com.aspose.threed.Vector3-) | Συνδέστε έναν μετασχηματισμό μετάφρασης **Example:** |
| [translate(double tx, double ty, double tz)](#translate-double-double-double-) | Συνδέστε έναν μετασχηματισμό μετάφρασης **Example:** |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TransformBuilder(Matrix4 initial, ComposeOrder order) {#TransformBuilder-com.aspose.threed.Matrix4-com.aspose.threed.ComposeOrder-}
```
public TransformBuilder(Matrix4 initial, ComposeOrder order)
```


Δομήστε ένα [TransformBuilder](../../com.aspose.threed/transformbuilder) με αρχικό μετασχηματιστικό πίνακα και καθορισμένη σειρά σύνθεσης

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| initial | [Matrix4](../../com.aspose.threed/matrix4) |  |
| order | [ComposeOrder](../../com.aspose.threed/composeorder) |  |

### TransformBuilder(ComposeOrder order) {#TransformBuilder-com.aspose.threed.ComposeOrder-}
```
public TransformBuilder(ComposeOrder order)
```


Δομήστε ένα [TransformBuilder](../../com.aspose.threed/transformbuilder) με αρχικό πίνακα ταυτότητας και καθορισμένη σειρά σύνθεσης

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| order | [ComposeOrder](../../com.aspose.threed/composeorder) |  |

### TransformBuilder() {#TransformBuilder--}
```
public TransformBuilder()
```


Δομήστε ένα [TransformBuilder](../../com.aspose.threed/transformbuilder) με αρχικό πίνακα ταυτότητας και καθορισμένη σειρά σύνθεσης

### append(Matrix4 m) {#append-com.aspose.threed.Matrix4-}
```
public TransformBuilder append(Matrix4 m)
```


Προσθέστε τον νέο μετασχηματιστικό πίνακα στην αλυσίδα μετασχηματισμών.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| m | [Matrix4](../../com.aspose.threed/matrix4) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### compose(Matrix4 m) {#compose-com.aspose.threed.Matrix4-}
```
public void compose(Matrix4 m)
```


Προσθέστε ή προσαρτήστε το όρισμα στον εσωτερικό πίνακα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| m | [Matrix4](../../com.aspose.threed/matrix4) |  |

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
### getComposeOrder() {#getComposeOrder--}
```
public ComposeOrder getComposeOrder()
```


Λαμβάνει τη σειρά σύνθεσης της αλυσίδας.

**Returns:**
[ComposeOrder](../../com.aspose.threed/composeorder) - the chain compose order.
### getMatrix() {#getMatrix--}
```
public Matrix4 getMatrix()
```


Λαμβάνει την τρέχουσα τιμή του πίνακα

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the current matrix value
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




### prepend(Matrix4 m) {#prepend-com.aspose.threed.Matrix4-}
```
public TransformBuilder prepend(Matrix4 m)
```


Προσαρτήστε τον νέο μετασχηματιστικό πίνακα στην αλυσίδα μετασχηματισμών.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| m | [Matrix4](../../com.aspose.threed/matrix4) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### rearrange(Axis newX, Axis newY, Axis newZ) {#rearrange-com.aspose.threed.Axis-com.aspose.threed.Axis-com.aspose.threed.Axis-}
```
public TransformBuilder rearrange(Axis newX, Axis newY, Axis newZ)
```


Αναδιατάξτε τη διάταξη του άξονα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newX | [Axis](../../com.aspose.threed/axis) | Η νέα πηγή του συνιστώσας x |
| newY | [Axis](../../com.aspose.threed/axis) | Η νέα πηγή του συνιστώσας y |
| newZ | [Axis](../../com.aspose.threed/axis) | Η νέα πηγή του συνιστώσας z |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### reset() {#reset--}
```
public void reset()
```


Επαναφέρετε τον μετασχηματισμό στον πίνακα ταυτότητας

### rotate(Quaternion q) {#rotate-com.aspose.threed.Quaternion-}
```
public TransformBuilder rotate(Quaternion q)
```


Συνδέστε μια περιστροφή με ένα quaternion **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotate(Quaternion.fromEulerAngle(0, Math.PI, 0));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### rotateDegree(Vector3 rot, RotationOrder order) {#rotateDegree-com.aspose.threed.Vector3-com.aspose.threed.RotationOrder-}
```
public void rotateDegree(Vector3 rot, RotationOrder order)
```


Προσθέστε περιστροφή με καθορισμένη σειρά

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rot | [Vector3](../../com.aspose.threed/vector3) | Περιστροφή σε μοίρες |
| order | [RotationOrder](../../com.aspose.threed/rotationorder) |  |

### rotateDegree(double angle, Vector3 axis) {#rotateDegree-double-com.aspose.threed.Vector3-}
```
public TransformBuilder rotateDegree(double angle, Vector3 axis)
```


Συνδέστε έναν μετασχηματισμό περιστροφής σε μοίρες

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| angle | double | Η γωνία περιστροφής σε μοίρες |
|  | axis | [Vector3](../../com.aspose.threed/vector3) | Ο άξονας περιστροφής **Example:** |

```
TransformBuilder tb = new TransformBuilder();
     tb.rotateDegree(90, Vector3.getUnitY());
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
``` |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### rotateEulerDegree(double degX, double degY, double degZ) {#rotateEulerDegree-double-double-double-}
```
public TransformBuilder rotateEulerDegree(double degX, double degY, double degZ)
```


Συνδέστε μια περιστροφή με γωνίες Euler σε μοίρες **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotateEulerDegree(0, 90, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| degX | double |  |
| degY | double |  |
| degZ | double |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### rotateEulerRadian(Vector3 r) {#rotateEulerRadian-com.aspose.threed.Vector3-}
```
public TransformBuilder rotateEulerRadian(Vector3 r)
```


Συνδέστε μια περιστροφή με γωνίες Euler σε ακτίνια **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotateEulerRadian(new Vector3(0, Math.PI, 0));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| r | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### rotateEulerRadian(double x, double y, double z) {#rotateEulerRadian-double-double-double-}
```
public TransformBuilder rotateEulerRadian(double x, double y, double z)
```


Συνδέστε μια περιστροφή με γωνίες Euler σε ακτίνια **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotateEulerRadian(0, Math.PI, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | double |  |
| y | double |  |
| z | double |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### rotateRadian(Vector3 rot, RotationOrder order) {#rotateRadian-com.aspose.threed.Vector3-com.aspose.threed.RotationOrder-}
```
public void rotateRadian(Vector3 rot, RotationOrder order)
```


Προσθέστε περιστροφή με καθορισμένη σειρά

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | rot | [Vector3](../../com.aspose.threed/vector3) | Περιστροφή σε ακτίνια **Example:** |

```
TransformBuilder tb = new TransformBuilder();
     tb.rotateRadian(new Vector3(0.3, 0.4, 0.1), RotationOrder.YZX);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
``` |
| order | [RotationOrder](../../com.aspose.threed/rotationorder) |  |

### rotateRadian(double angle, Vector3 axis) {#rotateRadian-double-com.aspose.threed.Vector3-}
```
public TransformBuilder rotateRadian(double angle, Vector3 axis)
```


Συνδέστε έναν μετασχηματισμό περιστροφής σε ακτίνια

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| angle | double | Η γωνία περιστροφής σε ακτίνια |
|  | axis | [Vector3](../../com.aspose.threed/vector3) | Ο άξονας περιστροφής **Example:** |

```
TransformBuilder tb = new TransformBuilder();
     tb.rotateRadian(Math.PI, Vector3.getUnitY());
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
``` |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### scale(Vector3 s) {#scale-com.aspose.threed.Vector3-}
```
public TransformBuilder scale(Vector3 s)
```


Συνδέστε έναν μετασχηματισμό κλίμακας **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.scale(new Vector3(10, 10, 10));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### scale(double s) {#scale-double-}
```
public TransformBuilder scale(double s)
```


Συνδέστε έναν πίνακα μετασχηματισμού κλιμάκωσης με ένα στοιχείο κλιμακωμένο κατά s **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.scale(10);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | double |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### scale(double x, double y, double z) {#scale-double-double-double-}
```
public TransformBuilder scale(double x, double y, double z)
```


Συνδέστε έναν πίνακα μετασχηματισμού κλιμάκωσης **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.scale(10, 10, 10);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | double |  |
| y | double |  |
| z | double |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### setComposeOrder(ComposeOrder value) {#setComposeOrder-com.aspose.threed.ComposeOrder-}
```
public void setComposeOrder(ComposeOrder value)
```


Ορίζει τη σειρά σύνθεσης της αλυσίδας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ComposeOrder](../../com.aspose.threed/composeorder) | Νέα τιμή |

### setMatrix(Matrix4 value) {#setMatrix-com.aspose.threed.Matrix4-}
```
public void setMatrix(Matrix4 value)
```


Ορίζει την τρέχουσα τιμή του πίνακα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | Νέα τιμή |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### translate(Vector3 v) {#translate-com.aspose.threed.Vector3-}
```
public TransformBuilder translate(Vector3 v)
```


Συνδέστε έναν μετασχηματισμό μετάφρασης **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.translate(new Vector3(0, 10, 0));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### translate(double tx, double ty, double tz) {#translate-double-double-double-}
```
public TransformBuilder translate(double tx, double ty, double tz)
```


Συνδέστε έναν μετασχηματισμό μετάφρασης **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.translate(0, 10, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| tx | double |  |
| ty | double |  |
| tz | double |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
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

