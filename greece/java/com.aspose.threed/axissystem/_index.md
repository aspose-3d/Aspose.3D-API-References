---
title: "AxisSystem"
second_title: "Aspose.3D for Java API Reference"
description: "Το σύστημα αξόνων είναι ένας συνδυασμός του διανύσματος ανόδου και του διανύσματος πρόσοψης του συστήματος συντεταγμένων."
type: docs
weight: 18
url: /el/java/com.aspose.threed/axissystem/
---

**Inheritance:**
java.lang.Object
```
public class AxisSystem
```

Το σύστημα αξόνων είναι ένας συνδυασμός του συστήματος συντεταγμένων, του διανύσματος ανόδου και του διανύσματος μπροστά.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [AxisSystem(CoordinateSystem coordinateSystem, Axis up)](#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-) | Δημιουργεί ένα νέο σύστημα αξόνων |
| [AxisSystem(Axis up, Axis front)](#AxisSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-) | Δημιουργεί ένα νέο σύστημα αξόνων |
| [AxisSystem(CoordinateSystem coordinateSystem, Axis up, Axis front)](#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-) | Δημιουργεί ένα νέο σύστημα αξόνων |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromAssetInfo(AssetInfo assetInfo)](#fromAssetInfo-com.aspose.threed.AssetInfo-) | Δημιουργήστε [AxisSystem](../../com.aspose.threed/axissystem) από [AssetInfo](../../com.aspose.threed/assetinfo) |
| [getClass()](#getClass--) |  |
| [getCoordinateSystem()](#getCoordinateSystem--) | Λαμβάνει το σύστημα συντεταγμένων αυτού του συστήματος αξόνων. |
| [getFront()](#getFront--) | Λαμβάνει το διάνυσμα πρόσοψης αυτού του συστήματος αξόνων |
| [getUp()](#getUp--) | Λαμβάνει το διάνυσμα ανόδου αυτού του συστήματος αξόνων. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [transformTo(AxisSystem targetSystem)](#transformTo-com.aspose.threed.AxisSystem-) | Δημιουργήστε έναν πίνακα που χρησιμοποιείται για τη μετατροπή από το τρέχον σύστημα αξόνων στο στόχο σύστημα αξόνων. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AxisSystem(CoordinateSystem coordinateSystem, Axis up) {#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-}
```
public AxisSystem(CoordinateSystem coordinateSystem, Axis up)
```


Δημιουργεί ένα νέο σύστημα αξόνων

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| coordinateSystem | [CoordinateSystem](../../com.aspose.threed/coordinatesystem) | Το σύστημα συντεταγμένων που χρησιμοποιείται σε αυτό το σύστημα αξόνων |
| up | [Axis](../../com.aspose.threed/axis) | Το διάνυσμα ανόδου του συστήματος αξόνων |

### AxisSystem(Axis up, Axis front) {#AxisSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-}
```
public AxisSystem(Axis up, Axis front)
```


Δημιουργεί ένα νέο σύστημα αξόνων

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| up | [Axis](../../com.aspose.threed/axis) | Το διάνυσμα ανόδου του συστήματος αξόνων |
| front | [Axis](../../com.aspose.threed/axis) | Το διάνυσμα πρόσοψης του συστήματος αξόνων |

### AxisSystem(CoordinateSystem coordinateSystem, Axis up, Axis front) {#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-}
```
public AxisSystem(CoordinateSystem coordinateSystem, Axis up, Axis front)
```


Δημιουργεί ένα νέο σύστημα αξόνων

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| coordinateSystem | [CoordinateSystem](../../com.aspose.threed/coordinatesystem) | Το σύστημα συντεταγμένων που χρησιμοποιείται σε αυτό το σύστημα αξόνων |
| up | [Axis](../../com.aspose.threed/axis) | Το διάνυσμα ανόδου του συστήματος αξόνων |
| front | [Axis](../../com.aspose.threed/axis) | Το διάνυσμα πρόσοψης του συστήματος αξόνων |

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
### fromAssetInfo(AssetInfo assetInfo) {#fromAssetInfo-com.aspose.threed.AssetInfo-}
```
public static AxisSystem fromAssetInfo(AssetInfo assetInfo)
```


Δημιουργήστε [AxisSystem](../../com.aspose.threed/axissystem) από [AssetInfo](../../com.aspose.threed/assetinfo)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| assetInfo | [AssetInfo](../../com.aspose.threed/assetinfo) | Από ποια πληροφορία περιουσιακού στοιχείου να διαβαστούν το σύστημα συντεταγμένων, το διάνυσμα επάνω και το μπροστινό διάνυσμα. |

**Returns:**
[AxisSystem](../../com.aspose.threed/axissystem) - Axis system containg coordinate system, up, front from given asset info
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCoordinateSystem() {#getCoordinateSystem--}
```
public CoordinateSystem getCoordinateSystem()
```


Λαμβάνει το σύστημα συντεταγμένων αυτού του συστήματος αξόνων.

**Returns:**
[CoordinateSystem](../../com.aspose.threed/coordinatesystem) - the coordinate system of this axis system.
### getFront() {#getFront--}
```
public Axis getFront()
```


Λαμβάνει το διάνυσμα πρόσοψης αυτού του συστήματος αξόνων

**Returns:**
[Axis](../../com.aspose.threed/axis) - the front vector of this axis system
### getUp() {#getUp--}
```
public Axis getUp()
```


Λαμβάνει το διάνυσμα ανόδου αυτού του συστήματος αξόνων.

**Returns:**
[Axis](../../com.aspose.threed/axis) - the up vector of this axis system.
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
### transformTo(AxisSystem targetSystem) {#transformTo-com.aspose.threed.AxisSystem-}
```
public Matrix4 transformTo(AxisSystem targetSystem)
```


Δημιουργήστε έναν πίνακα που χρησιμοποιείται για τη μετατροπή από το τρέχον σύστημα αξόνων στο στόχο σύστημα αξόνων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| targetSystem | [AxisSystem](../../com.aspose.threed/axissystem) | Σύστημα άξονα στόχου |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - A new transformation matrix to do the axis conversion
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

