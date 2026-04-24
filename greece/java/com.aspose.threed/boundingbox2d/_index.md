---
title: BoundingBox2D
second_title: Aspose.3D for Java API Reference
description: Το πλαίσιο περιβάλλοντος ευθυγραμμισμένο με τον άξονα για
type: docs
weight: 25
url: /el/java/com.aspose.threed/boundingbox2d/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class BoundingBox2D implements Struct<BoundingBox2D>, Serializable
```

Το πλαίσιο περιβάλλοντος ευθυγραμμισμένο με τον άξονα για [Vector2](../../com.aspose.threed/vector2)
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [BoundingBox2D(Vector2 minimum, Vector2 maximum)](#BoundingBox2D-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Αρχικοποιήστε ένα πεπερασμένο πλαίσιο περιβάλλοντος με δεδομένες ελάχιστες και μέγιστες γωνίες |
| [BoundingBox2D()](#BoundingBox2D--) |  |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [INFINITE](#INFINITE) | Το άπειρο πλαίσιο περιβάλλοντος |
| [NULL](#NULL) | Το μηδενικό πλαίσιο περιβάλλοντος |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [clone()](#clone--) |  |
| [copyFrom(BoundingBox2D src)](#copyFrom-com.aspose.threed.BoundingBox2D-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtent()](#getExtent--) | Επιστρέφει το μέγεθος του πλαισίου περιβάλλοντος. |
| [getMaximum()](#getMaximum--) | Η μέγιστη γωνία του πλαισίου περιβάλλοντος |
| [getMinimum()](#getMinimum--) | Η ελάχιστη γωνία του πλαισίου περιβάλλοντος |
| [hashCode()](#hashCode--) |  |
| [merge(BoundingBox2D bb)](#merge-com.aspose.threed.BoundingBox2D-) | Συγχωνεύει το νέο πλαίσιο στο τρέχον πλαίσιο περιβάλλοντος. |
| [merge(Vector2 pt)](#merge-com.aspose.threed.Vector2-) | Συγχωνεύει το νέο πλαίσιο στο τρέχον πλαίσιο περιβάλλοντος. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Επιστρέφει την αναπαράσταση συμβολοσειράς του πλαισίου περιβάλλοντος. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BoundingBox2D(Vector2 minimum, Vector2 maximum) {#BoundingBox2D-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public BoundingBox2D(Vector2 minimum, Vector2 maximum)
```


Αρχικοποιήστε ένα πεπερασμένο πλαίσιο περιβάλλοντος με δεδομένες ελάχιστες και μέγιστες γωνίες

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| minimum | [Vector2](../../com.aspose.threed/vector2) | Η ελάχιστη γωνία |
| maximum | [Vector2](../../com.aspose.threed/vector2) | Η μέγιστη γωνία |

### BoundingBox2D() {#BoundingBox2D--}
```
public BoundingBox2D()
```


### INFINITE {#INFINITE}
```
public static final BoundingBox2D INFINITE
```


Το άπειρο πλαίσιο περιβάλλοντος

### NULL {#NULL}
```
public static final BoundingBox2D NULL
```


Το μηδενικό πλαίσιο περιβάλλοντος

### clone() {#clone--}
```
public BoundingBox2D clone()
```


Clone current instance

**Returns:**
[BoundingBox2D](../../com.aspose.threed/boundingbox2d)
### copyFrom(BoundingBox2D src) {#copyFrom-com.aspose.threed.BoundingBox2D-}
```
public void copyFrom(BoundingBox2D src)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| src | [BoundingBox2D](../../com.aspose.threed/boundingbox2d) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




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
### getExtent() {#getExtent--}
```
public BoundingBoxExtent getExtent()
```


Επιστρέφει το μέγεθος του πλαισίου περιβάλλοντος.

**Returns:**
[BoundingBoxExtent](../../com.aspose.threed/boundingboxextent) - the extent of the bounding box.
### getMaximum() {#getMaximum--}
```
public Vector2 getMaximum()
```


Η μέγιστη γωνία του πλαισίου περιβάλλοντος

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The maximum corner of the bounding box
### getMinimum() {#getMinimum--}
```
public Vector2 getMinimum()
```


Η ελάχιστη γωνία του πλαισίου περιβάλλοντος

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The minimum corner of the bounding box
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### merge(BoundingBox2D bb) {#merge-com.aspose.threed.BoundingBox2D-}
```
public void merge(BoundingBox2D bb)
```


Συγχωνεύει το νέο πλαίσιο στο τρέχον πλαίσιο περιβάλλοντος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bb | [BoundingBox2D](../../com.aspose.threed/boundingbox2d) | Το πλαίσιο περιβάλλοντος για συγχώνευση |

### merge(Vector2 pt) {#merge-com.aspose.threed.Vector2-}
```
public void merge(Vector2 pt)
```


Συγχωνεύει το νέο πλαίσιο στο τρέχον πλαίσιο περιβάλλοντος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pt | [Vector2](../../com.aspose.threed/vector2) | Το σημείο για συγχώνευση |

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


Επιστρέφει την αναπαράσταση συμβολοσειράς του πλαισίου περιβάλλοντος.

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

