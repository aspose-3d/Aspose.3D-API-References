---
title: BooleanOperand
second_title: Aspose.3D for Java API Reference
description: Αυτή η κλάση ενσωματώνει το μετασχηματισμένο πλέγμα ως τελεστή Boolean λειτουργιών.
type: docs
weight: 22
url: /el/java/com.aspose.threed/booleanoperand/
---

**Inheritance:**
java.lang.Object
```
public class BooleanOperand
```

Αυτή η κλάση ενσωματώνει το μετασχηματισμένο πλέγμα ως τελεστή της Boolean λειτουργίας.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOperand()](#getOperand--) | Λαμβάνει τον τελεστή, μπορεί να είναι ένα στιγμιότυπο του [HalfSpace](../../com.aspose.threed/halfspace), του [IMeshConvertible](../../com.aspose.threed/imeshconvertible) ή του [Node](../../com.aspose.threed/node). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [of(Entity mesh)](#of-com.aspose.threed.Entity-) | Δημιουργήστε ένα αντικείμενο [BooleanOperand](../../com.aspose.threed/booleanoperand) από ένα ακατέργαστο αντικείμενο [IMeshConvertible](../../com.aspose.threed/imeshconvertible). |
| [of(Entity mesh, Matrix4 transform)](#of-com.aspose.threed.Entity-com.aspose.threed.Matrix4-) | Δημιουργήστε ένα αντικείμενο [BooleanOperand](../../com.aspose.threed/booleanoperand) από ένα αντικείμενο [IMeshConvertible](../../com.aspose.threed/imeshconvertible) και καθορισμένο μετασχηματισμό. |
| [of(Node node)](#of-com.aspose.threed.Node-) | Δημιουργήστε ένα αντικείμενο [BooleanOperand](../../com.aspose.threed/booleanoperand) από έναν κόμβο· απαιτείται μια έγκυρη οντότητα που υλοποιεί το [IMeshConvertible](../../com.aspose.threed/imeshconvertible). |
| [toString()](#toString--) | Λαμβάνει την αναπαράσταση ως συμβολοσειρά του [BooleanOperand](../../com.aspose.threed/booleanoperand). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getOperand() {#getOperand--}
```
public A3DObject getOperand()
```


Λαμβάνει τον τελεστή, μπορεί να είναι ένα στιγμιότυπο του [HalfSpace](../../com.aspose.threed/halfspace), του [IMeshConvertible](../../com.aspose.threed/imeshconvertible) ή του [Node](../../com.aspose.threed/node).

**Returns:**
[A3DObject](../../com.aspose.threed/a3dobject) - the operand, it can be an instance of [HalfSpace](../../com.aspose.threed/halfspace), [IMeshConvertible](../../com.aspose.threed/imeshconvertible) or [Node](../../com.aspose.threed/node).
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




### of(Entity mesh) {#of-com.aspose.threed.Entity-}
```
public static BooleanOperand of(Entity mesh)
```


Δημιουργήστε ένα αντικείμενο [BooleanOperand](../../com.aspose.threed/booleanoperand) από ένα ακατέργαστο αντικείμενο [IMeshConvertible](../../com.aspose.threed/imeshconvertible).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mesh | [Entity](../../com.aspose.threed/entity) | Το πλέγμα που χρησιμοποιείται ως τελεστέο της Boolean λειτουργίας, μπορεί να είναι μια παρουσία του [IMeshConvertible](../../com.aspose.threed/imeshconvertible) ή του [HalfSpace](../../com.aspose.threed/halfspace). |

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - An instance of [BooleanOperand](../../com.aspose.threed/booleanoperand)
### of(Entity mesh, Matrix4 transform) {#of-com.aspose.threed.Entity-com.aspose.threed.Matrix4-}
```
public static BooleanOperand of(Entity mesh, Matrix4 transform)
```


Δημιουργήστε ένα αντικείμενο [BooleanOperand](../../com.aspose.threed/booleanoperand) από ένα αντικείμενο [IMeshConvertible](../../com.aspose.threed/imeshconvertible) και καθορισμένο μετασχηματισμό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mesh | [Entity](../../com.aspose.threed/entity) | Το πλέγμα που χρησιμοποιείται ως τελεστέο της Boolean λειτουργίας, μπορεί να είναι μια παρουσία του [IMeshConvertible](../../com.aspose.threed/imeshconvertible) ή του [HalfSpace](../../com.aspose.threed/halfspace). |
| transform | [Matrix4](../../com.aspose.threed/matrix4) | Ο μετασχηματισμός του αντικειμένου πλέγματος. |

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - An instance of [BooleanOperand](../../com.aspose.threed/booleanoperand)
### of(Node node) {#of-com.aspose.threed.Node-}
```
public static BooleanOperand of(Node node)
```


Δημιουργήστε ένα αντικείμενο [BooleanOperand](../../com.aspose.threed/booleanoperand) από έναν κόμβο· απαιτείται μια έγκυρη οντότητα που υλοποιεί το [IMeshConvertible](../../com.aspose.threed/imeshconvertible).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | Μια παρουσία του [Node](../../com.aspose.threed/node) με μια έγκυρη οντότητα που υλοποιεί το [IMeshConvertible](../../com.aspose.threed/imeshconvertible). |

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - An instance of [BooleanOperand](../../com.aspose.threed/booleanoperand)
### toString() {#toString--}
```
public String toString()
```


Λαμβάνει την αναπαράσταση ως συμβολοσειρά του [BooleanOperand](../../com.aspose.threed/booleanoperand).

**Returns:**
java.lang.String - Η αναπαράσταση ως συμβολοσειρά του [BooleanOperand](../../com.aspose.threed/booleanoperand).
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

