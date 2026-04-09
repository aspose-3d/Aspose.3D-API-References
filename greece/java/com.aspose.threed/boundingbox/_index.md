---
title: BoundingBox
second_title: Aspose.3D for Java API Reference
description: The axis-aligned bounding box Example  The following code shows how to get a bounding box from an Entity instance.
type: docs
weight: 24
url: /el/java/com.aspose.threed/boundingbox/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class BoundingBox implements Struct<BoundingBox>, Serializable
```

Το πλαίσιο περιβάλλουσας ευθυγράμμισης άξονα **Example:** Ο παρακάτω κώδικας δείχνει πώς να λάβετε μια πλαίσιο περιβάλλουσας από ένα στιγμιότυπο Entity.

```
var sphere = new Sphere();
      var boundingBox = sphere.getBoundingBox();
      System.out.println("Bounding box = " + boundingBox);
```
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [BoundingBox(Vector3 minimum, Vector3 maximum)](#BoundingBox-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Αρχικοποιήστε ένα πεπερασμένο πλαίσιο περιβάλλοντος με δεδομένες ελάχιστες και μέγιστες γωνίες |
| [BoundingBox(double minX, double minY, double minZ, double maxX, double maxY, double maxZ)](#BoundingBox-double-double-double-double-double-double-) | Αρχικοποιήστε ένα πεπερασμένο πλαίσιο περιβάλλοντος με δεδομένες ελάχιστες και μέγιστες γωνίες |
| [BoundingBox()](#BoundingBox--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(BoundingBox bbox)](#contains-com.aspose.threed.BoundingBox-) | The bounding box to check if it's inside current bounding box. |
| [contains(Vector3 p)](#contains-com.aspose.threed.Vector3-) | Check if the point p is inside the bounding box |
| [copyFrom(BoundingBox src)](#copyFrom-com.aspose.threed.BoundingBox-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines if two objects are equal |
| [fromGeometry(Geometry geometry)](#fromGeometry-com.aspose.threed.Geometry-) | Construct a bounding box from given geometry |
| [getCenter()](#getCenter--) | Το κέντρο του πλαισίου περιβάλλοντος. |
| [getClass()](#getClass--) |  |
| [getExtent()](#getExtent--) | Επιστρέφει το μέγεθος του πλαισίου περιβάλλοντος. |
| [getInfinite()](#getInfinite--) | Το άπειρο πλαίσιο περιβάλλοντος |
| [getMaximum()](#getMaximum--) | Η μέγιστη γωνία του πλαισίου περιβάλλοντος |
| [getMinimum()](#getMinimum--) | Η ελάχιστη γωνία του πλαισίου περιβάλλοντος |
| [getNull()](#getNull--) | Το μηδενικό πλαίσιο περιβάλλοντος |
| [getSize()](#getSize--) | Το μέγεθος του πλαισίου περιβάλλοντος |
| [hashCode()](#hashCode--) | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία |
| [merge(BoundingBox bb)](#merge-com.aspose.threed.BoundingBox-) | Συγχωνεύει το νέο πλαίσιο στο τρέχον πλαίσιο περιβάλλοντος. |
| [merge(Vector3 pt)](#merge-com.aspose.threed.Vector3-) | Συγχώνευση του τρέχοντος πλαισίου περιβάλλοντος με το δοσμένο σημείο |
| [merge(Vector4 pt)](#merge-com.aspose.threed.Vector4-) | Συγχώνευση του τρέχοντος πλαισίου περιβάλλοντος με το δοσμένο σημείο |
| [merge(double x, double y, double z)](#merge-double-double-double-) | Συγχώνευση του τρέχοντος πλαισίου περιβάλλοντος με το δοσμένο σημείο |
| [mul(BoundingBox bbox, Matrix4 mat)](#mul-com.aspose.threed.BoundingBox-com.aspose.threed.Matrix4-) | Υπερφόρτωση τελεστή για πολλαπλασιασμό, οι ελάχιστες και μέγιστες γωνίες του νέου πλαισίου περιβάλλοντος θα μετασχηματιστούν από τον πίνακα. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [overlapsWith(BoundingBox box)](#overlapsWith-com.aspose.threed.BoundingBox-) | Έλεγχος εάν το τρέχον πλαίσιο περιβάλλοντος επικαλύπτεται με το καθορισμένο πλαίσιο περιβάλλοντος. |
| [scale()](#scale--) | Υπολογίζει την απόλυτη μεγαλύτερη τιμή συντεταγμένης οποιουδήποτε περιεχόμενου σημείου. |
| [toString()](#toString--) | Επιστρέφει την αναπαράσταση συμβολοσειράς του πλαισίου περιβάλλοντος. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BoundingBox(Vector3 minimum, Vector3 maximum) {#BoundingBox-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public BoundingBox(Vector3 minimum, Vector3 maximum)
```


Αρχικοποιήστε ένα πεπερασμένο πλαίσιο περιβάλλοντος με δεδομένες ελάχιστες και μέγιστες γωνίες

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| minimum | [Vector3](../../com.aspose.threed/vector3) | Η ελάχιστη γωνία |
|  | maximum | [Vector3](../../com.aspose.threed/vector3) | Η μέγιστη γωνία **Example:** Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε ένα πλαίσιο περιβάλλοντος από τις ελάχιστες και μέγιστες γωνίες. |

```
var minimum = new Vector3(0, 0, 0);
  var maximum = new Vector3(10, 10, 10);
  var boundingBox = new BoundingBox(minimum, maximum);
  System.out.println("Bounding box = " + boundingBox);
``` |

### BoundingBox(double minX, double minY, double minZ, double maxX, double maxY, double maxZ) {#BoundingBox-double-double-double-double-double-double-}
```
public BoundingBox(double minX, double minY, double minZ, double maxX, double maxY, double maxZ)
```


Αρχικοποιήστε ένα πεπερασμένο πλαίσιο περιβάλλοντος με δεδομένες ελάχιστες και μέγιστες γωνίες

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| minX | double | Το X της ελάχιστης γωνίας |
| minY | double | Το Y της ελάχιστης γωνίας |
| minZ | double | Το Z της ελάχιστης γωνίας |
| maxX | double | Το X της μέγιστης γωνίας |
| maxY | double | Το Y της μέγιστης γωνίας |
|  | maxZ | double | Το Z της μέγιστης γωνίας **Example:** Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε ένα πλαίσιο περιβάλλοντος από τις ελάχιστες και μέγιστες γωνίες. |

```
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
  System.out.println("Bounding box = " + boundingBox);
``` |

### BoundingBox() {#BoundingBox--}
```
public BoundingBox()
```


### clone() {#clone--}
```
public BoundingBox clone()
```


Clone current instance

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox)
### contains(BoundingBox bbox) {#contains-com.aspose.threed.BoundingBox-}
```
public boolean contains(BoundingBox bbox)
```


The bounding box to check if it's inside current bounding box.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bbox | [BoundingBox](../../com.aspose.threed/boundingbox) |  |

**Returns:**
boolean
### contains(Vector3 p) {#contains-com.aspose.threed.Vector3-}
```
public boolean contains(Vector3 p)
```


Check if the point p is inside the bounding box

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| p | [Vector3](../../com.aspose.threed/vector3) | Το σημείο για δοκιμή |

**Returns:**
boolean - Αληθές εάν το σημείο βρίσκεται μέσα στο πλαίσιο περιβάλλοντος **Example:** Ο παρακάτω κώδικας δείχνει πώς να ελέγξετε εάν ένα σημείο βρίσκεται μέσα στο πλαίσιο περιβάλλοντος.

```
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
  var pt = new Vector3(4, 4, 4);
  System.out.println("Bounding box overlaps = " + boundingBox.contains(pt));
```
### copyFrom(BoundingBox src) {#copyFrom-com.aspose.threed.BoundingBox-}
```
public void copyFrom(BoundingBox src)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| src | [BoundingBox](../../com.aspose.threed/boundingbox) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines if two objects are equal

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το αντικείμενο για σύγκριση |

**Returns:**
boolean - αληθές εάν δύο αντικείμενα είναι ίσα
### fromGeometry(Geometry geometry) {#fromGeometry-com.aspose.threed.Geometry-}
```
public static BoundingBox fromGeometry(Geometry geometry)
```


Construct a bounding box from given geometry

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| geometry | [Geometry](../../com.aspose.threed/geometry) | Η γεωμετρία για τον υπολογισμό του πλαισίου περιβάλλοντος |

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The bounding box of given geometry **Example:** The following code shows how to construct a bounding box from a geometry instance.

```
var sphere = (new Sphere()).toMesh();
  var boundingBox = BoundingBox.fromGeometry(sphere);
  System.out.println("Bounding box = " + boundingBox);
```
### getCenter() {#getCenter--}
```
public Vector3 getCenter()
```


Το κέντρο του πλαισίου περιβάλλοντος.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The center of the bounding box.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getExtent() {#getExtent--}
```
public BoundingBoxExtent getExtent()
```


Επιστρέφει το μέγεθος του πλαισίου περιβάλλοντος.

**Returns:**
[BoundingBoxExtent](../../com.aspose.threed/boundingboxextent) - the extent of the bounding box.
### getInfinite() {#getInfinite--}
```
public static BoundingBox getInfinite()
```


Το άπειρο πλαίσιο περιβάλλοντος

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The infinite bounding box
### getMaximum() {#getMaximum--}
```
public Vector3 getMaximum()
```


Η μέγιστη γωνία του πλαισίου περιβάλλοντος

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The maximum corner of the bounding box
### getMinimum() {#getMinimum--}
```
public Vector3 getMinimum()
```


Η ελάχιστη γωνία του πλαισίου περιβάλλοντος

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The minimum corner of the bounding box
### getNull() {#getNull--}
```
public static BoundingBox getNull()
```


Το μηδενικό πλαίσιο περιβάλλοντος

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The null bounding box
### getSize() {#getSize--}
```
public Vector3 getSize()
```


Το μέγεθος του πλαισίου περιβάλλοντος

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The size of the bounding box
### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία

**Returns:**
int - The hash code of the bounding box
### merge(BoundingBox bb) {#merge-com.aspose.threed.BoundingBox-}
```
public void merge(BoundingBox bb)
```


Συγχωνεύει το νέο πλαίσιο στο τρέχον πλαίσιο περιβάλλοντος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bb | [BoundingBox](../../com.aspose.threed/boundingbox) | Το πλαίσιο περιβάλλοντος για συγχώνευση |

### merge(Vector3 pt) {#merge-com.aspose.threed.Vector3-}
```
public void merge(Vector3 pt)
```


Συγχώνευση του τρέχοντος πλαισίου περιβάλλοντος με το δοσμένο σημείο

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | pt | [Vector3](../../com.aspose.threed/vector3) | The point to be merged into the bounding box **Example:** The following code shows how to merge a point to bounding box. |

```
var boundingBox = BoundingBox.getNull();
  boundingBox.Merge(new Vector3(1, 10, -1));
  System.out.println("Bounding box = " + boundingBox);
``` |

### merge(Vector4 pt) {#merge-com.aspose.threed.Vector4-}
```
public void merge(Vector4 pt)
```


Συγχώνευση του τρέχοντος πλαισίου περιβάλλοντος με το δοσμένο σημείο

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | pt | [Vector4](../../com.aspose.threed/vector4) | The point to be merged into the bounding box **Example:** The following code shows how to merge a point to bounding box. |

```
var boundingBox = BoundingBox.getNull();
  boundingBox.Merge(new Vector4(1, 10, -1));
  System.out.println("Bounding box = " + boundingBox);
``` |

### merge(double x, double y, double z) {#merge-double-double-double-}
```
public void merge(double x, double y, double z)
```


Συγχώνευση του τρέχοντος πλαισίου περιβάλλοντος με το δοσμένο σημείο

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | double | The point to be merged into the bounding box |
| y | double | The point to be merged into the bounding box |
|  | z | double | The point to be merged into the bounding box **Example:** The following code shows how to merge a point to bounding box. |

```
var boundingBox = BoundingBox.getNull();
  boundingBox.Merge(1, 10, -1);
  System.out.println("Bounding box = " + boundingBox);
``` |

### mul(BoundingBox bbox, Matrix4 mat) {#mul-com.aspose.threed.BoundingBox-com.aspose.threed.Matrix4-}
```
public static BoundingBox mul(BoundingBox bbox, Matrix4 mat)
```


Υπερφόρτωση τελεστή για πολλαπλασιασμό, οι ελάχιστες και μέγιστες γωνίες του νέου πλαισίου περιβάλλοντος θα μετασχηματιστούν από τον πίνακα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bbox | [BoundingBox](../../com.aspose.threed/boundingbox) | The input bounding box. |
| mat | [Matrix4](../../com.aspose.threed/matrix4) | The matrix used to transform the bounding box's corners |

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The product of bounding box and transform matrix.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### overlapsWith(BoundingBox box) {#overlapsWith-com.aspose.threed.BoundingBox-}
```
public boolean overlapsWith(BoundingBox box)
```


Έλεγχος εάν το τρέχον πλαίσιο περιβάλλοντος επικαλύπτεται με το καθορισμένο πλαίσιο περιβάλλοντος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| box | [BoundingBox](../../com.aspose.threed/boundingbox) | The other bounding box to test |

**Returns:**
boolean - True if the current bounding box overlaps with the given one. **Example:** The following code shows how to check if two bounding boxes overlaps with each other.

```
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
  var bbox2 = new BoundingBox(1, 1, 1, 11, 11, 11);
  System.out.println("Bounding box overlaps = " + boundingBox.overlapsWith(bbox2));
```
### scale() {#scale--}
```
public double scale()
```


Υπολογίζει την απόλυτη μεγαλύτερη τιμή συντεταγμένης οποιουδήποτε περιεχόμενου σημείου.

**Returns:**
double - the calculated absolute largest coordinate value of any contained point.
### toString() {#toString--}
```
public String toString()
```


Επιστρέφει την αναπαράσταση συμβολοσειράς του πλαισίου περιβάλλοντος.

**Returns:**
java.lang.String - The string representation of the bounding box.
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

