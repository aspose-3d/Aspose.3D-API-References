---
title: BoundingBox
second_title: Aspose.3D for Java API-referentie
description: De as-uitgelijnde BoundingBox Voorbeeld  De volgende code laat zien hoe je een BoundingBox krijgt van een Entity‑instantie.
type: docs
weight: 24
url: /nl/java/com.aspose.threed/boundingbox/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class BoundingBox implements Struct<BoundingBox>, Serializable
```

De as‑gealigneerde begrenzingsdoos **Example:** De volgende code laat zien hoe je een begrenzingsdoos krijgt van een Entity‑instantie.

```
var sphere = new Sphere();
      var boundingBox = sphere.getBoundingBox();
      System.out.println("Bounding box = " + boundingBox);
```
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [BoundingBox(Vector3 minimum, Vector3 maximum)](#BoundingBox-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Initialiseer een eindige begrenzingsdoos met de opgegeven minimale en maximale hoek |
| [BoundingBox(double minX, double minY, double minZ, double maxX, double maxY, double maxZ)](#BoundingBox-double-double-double-double-double-double-) | Initialiseer een eindige begrenzingsdoos met de opgegeven minimale en maximale hoek |
| [BoundingBox()](#BoundingBox--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(BoundingBox bbox)](#contains-com.aspose.threed.BoundingBox-) | De BoundingBox om te controleren of deze zich binnen de huidige BoundingBox bevindt. |
| [contains(Vector3 p)](#contains-com.aspose.threed.Vector3-) | Controleer of punt p zich binnen de BoundingBox bevindt |
| [copyFrom(BoundingBox src)](#copyFrom-com.aspose.threed.BoundingBox-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of twee objecten gelijk zijn |
| [fromGeometry(Geometry geometry)](#fromGeometry-com.aspose.threed.Geometry-) | Construeer een BoundingBox van gegeven geometrie |
| [getCenter()](#getCenter--) | Het midden van de BoundingBox. |
| [getClass()](#getClass--) |  |
| [getExtent()](#getExtent--) | Haalt de omvang van de begrenzingsdoos op. |
| [getInfinite()](#getInfinite--) | De oneindige begrenzingsdoos |
| [getMaximum()](#getMaximum--) | De maximale hoek van de begrenzingsdoos |
| [getMinimum()](#getMinimum--) | De minimale hoek van de begrenzingsdoos |
| [getNull()](#getNull--) | De nulbegrenzingsdoos |
| [getSize()](#getSize--) | De grootte van de BoundingBox |
| [hashCode()](#hashCode--) | Retourneert de hashcode voor deze instantie |
| [merge(BoundingBox bb)](#merge-com.aspose.threed.BoundingBox-) | Voegt de nieuwe doos samen met de huidige begrenzingsdoos. |
| [merge(Vector3 pt)](#merge-com.aspose.threed.Vector3-) | Voeg de huidige BoundingBox samen met het opgegeven punt |
| [merge(Vector4 pt)](#merge-com.aspose.threed.Vector4-) | Voeg de huidige BoundingBox samen met het opgegeven punt |
| [merge(double x, double y, double z)](#merge-double-double-double-) | Voeg de huidige BoundingBox samen met het opgegeven punt |
| [mul(BoundingBox bbox, Matrix4 mat)](#mul-com.aspose.threed.BoundingBox-com.aspose.threed.Matrix4-) | Operatoroverloading voor vermenigvuldiging, de minimum- en maximumhoek van de nieuwe BoundingBox worden getransformeerd door de matrix. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [overlapsWith(BoundingBox box)](#overlapsWith-com.aspose.threed.BoundingBox-) | Controleer of de huidige BoundingBox overlapt met de opgegeven BoundingBox. |
| [scale()](#scale--) | Berekent de absolute grootste coördinaatwaarde van elk punt dat zich binnen bevindt. |
| [toString()](#toString--) | Haalt de tekenreeksrepresentatie van de begrenzingsdoos op. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BoundingBox(Vector3 minimum, Vector3 maximum) {#BoundingBox-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public BoundingBox(Vector3 minimum, Vector3 maximum)
```


Initialiseer een eindige begrenzingsdoos met de opgegeven minimale en maximale hoek

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| minimum | [Vector3](../../com.aspose.threed/vector3) | De minimale hoek |
|  | maximum | [Vector3](../../com.aspose.threed/vector3) | De maximale hoek **Example:** De volgende code laat zien hoe je een BoundingBox construeert van minimum- en maximumhoeken. |

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


Initialiseer een eindige begrenzingsdoos met de opgegeven minimale en maximale hoek

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| minX | double | De X van de minimumhoek |
| minY | double | De Y van de minimale hoek |
| minZ | double | De Z van de minimale hoek |
| maxX | double | De X van de maximale hoek |
| maxY | double | De Y van de maximale hoek |
|  | maxZ | double | De Z van de maximale hoek **Voorbeeld:** De volgende code laat zien hoe je een bounding box kunt construeren vanuit de minimale en maximale hoeken. |

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


Kloon huidige instantie

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox)
### contains(BoundingBox bbox) {#contains-com.aspose.threed.BoundingBox-}
```
public boolean contains(BoundingBox bbox)
```


De BoundingBox om te controleren of deze zich binnen de huidige BoundingBox bevindt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bbox | [BoundingBox](../../com.aspose.threed/boundingbox) |  |

**Returns:**
boolean
### contains(Vector3 p) {#contains-com.aspose.threed.Vector3-}
```
public boolean contains(Vector3 p)
```


Controleer of punt p zich binnen de BoundingBox bevindt

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| p | [Vector3](../../com.aspose.threed/vector3) | Het punt om te testen |

**Returns:**
boolean - True if the point is inside the bounding box **Voorbeeld:** De volgende code laat zien hoe je controleert of een punt zich binnen de bounding box bevindt.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| src | [BoundingBox](../../com.aspose.threed/boundingbox) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bepaalt of twee objecten gelijk zijn

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Het object om te vergelijken |

**Returns:**
boolean - true als twee objecten gelijk zijn
### fromGeometry(Geometry geometry) {#fromGeometry-com.aspose.threed.Geometry-}
```
public static BoundingBox fromGeometry(Geometry geometry)
```


Construeer een BoundingBox van gegeven geometrie

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| geometry | [Geometry](../../com.aspose.threed/geometry) | De geometrie om de bounding box te berekenen |

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


Het midden van de BoundingBox.

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


Haalt de omvang van de begrenzingsdoos op.

**Returns:**
[BoundingBoxExtent](../../com.aspose.threed/boundingboxextent) - the extent of the bounding box.
### getInfinite() {#getInfinite--}
```
public static BoundingBox getInfinite()
```


De oneindige begrenzingsdoos

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The infinite bounding box
### getMaximum() {#getMaximum--}
```
public Vector3 getMaximum()
```


De maximale hoek van de begrenzingsdoos

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The maximum corner of the bounding box
### getMinimum() {#getMinimum--}
```
public Vector3 getMinimum()
```


De minimale hoek van de begrenzingsdoos

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The minimum corner of the bounding box
### getNull() {#getNull--}
```
public static BoundingBox getNull()
```


De nulbegrenzingsdoos

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The null bounding box
### getSize() {#getSize--}
```
public Vector3 getSize()
```


De grootte van de BoundingBox

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The size of the bounding box
### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert de hashcode voor deze instantie

**Returns:**
int - De hashcode van de bounding box
### merge(BoundingBox bb) {#merge-com.aspose.threed.BoundingBox-}
```
public void merge(BoundingBox bb)
```


Voegt de nieuwe doos samen met de huidige begrenzingsdoos.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bb | [BoundingBox](../../com.aspose.threed/boundingbox) | De te combineren begrenzingsdoos |

### merge(Vector3 pt) {#merge-com.aspose.threed.Vector3-}
```
public void merge(Vector3 pt)
```


Voeg de huidige BoundingBox samen met het opgegeven punt

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | pt | [Vector3](../../com.aspose.threed/vector3) | Het punt dat moet worden samengevoegd met de bounding box **Voorbeeld:** De volgende code laat zien hoe je een punt met een bounding box samenvoegt. |

```
var boundingBox = BoundingBox.getNull();
  boundingBox.Merge(new Vector3(1, 10, -1));
  System.out.println("Bounding box = " + boundingBox);
``` |

### merge(Vector4 pt) {#merge-com.aspose.threed.Vector4-}
```
public void merge(Vector4 pt)
```


Voeg de huidige BoundingBox samen met het opgegeven punt

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | pt | [Vector4](../../com.aspose.threed/vector4) | Het punt dat moet worden samengevoegd met de bounding box **Voorbeeld:** De volgende code laat zien hoe je een punt met een bounding box samenvoegt. |

```
var boundingBox = BoundingBox.getNull();
  boundingBox.Merge(new Vector4(1, 10, -1));
  System.out.println("Bounding box = " + boundingBox);
``` |

### merge(double x, double y, double z) {#merge-double-double-double-}
```
public void merge(double x, double y, double z)
```


Voeg de huidige BoundingBox samen met het opgegeven punt

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | double | Het punt dat moet worden samengevoegd met de bounding box |
| y | double | Het punt dat moet worden samengevoegd met de bounding box |
|  | z | double | Het punt dat moet worden samengevoegd met de bounding box **Voorbeeld:** De volgende code laat zien hoe je een punt met een bounding box samenvoegt. |

```
var boundingBox = BoundingBox.getNull();
  boundingBox.Merge(1, 10, -1);
  System.out.println("Bounding box = " + boundingBox);
``` |

### mul(BoundingBox bbox, Matrix4 mat) {#mul-com.aspose.threed.BoundingBox-com.aspose.threed.Matrix4-}
```
public static BoundingBox mul(BoundingBox bbox, Matrix4 mat)
```


Operatoroverloading voor vermenigvuldiging, de minimum- en maximumhoek van de nieuwe BoundingBox worden getransformeerd door de matrix.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bbox | [BoundingBox](../../com.aspose.threed/boundingbox) | De invoer bounding box. |
| mat | [Matrix4](../../com.aspose.threed/matrix4) | De matrix die wordt gebruikt om de hoeken van de bounding box te transformeren |

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


Controleer of de huidige BoundingBox overlapt met de opgegeven BoundingBox.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| box | [BoundingBox](../../com.aspose.threed/boundingbox) | De andere bounding box om te testen |

**Returns:**
boolean - True als de huidige bounding box overlapt met de opgegeven. **Voorbeeld:** De volgende code laat zien hoe je controleert of twee bounding boxes elkaar overlappen.

```
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
  var bbox2 = new BoundingBox(1, 1, 1, 11, 11, 11);
  System.out.println("Bounding box overlaps = " + boundingBox.overlapsWith(bbox2));
```
### scale() {#scale--}
```
public double scale()
```


Berekent de absolute grootste coördinaatwaarde van elk punt dat zich binnen bevindt.

**Returns:**
double - de berekende absolute grootste coördinaatwaarde van elk opgenomen punt.
### toString() {#toString--}
```
public String toString()
```


Haalt de tekenreeksrepresentatie van de begrenzingsdoos op.

**Returns:**
java.lang.String - De stringrepresentatie van de bounding box.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

