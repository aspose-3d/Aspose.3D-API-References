---
title: BoundingBox
second_title: Aspose.3D for Java API-referens
description: Den axeljusterade begränsningsboxen Exempel  Följande kod visar hur man får en begränsningsbox från en Entity‑instans.
type: docs
weight: 24
url: /sv/java/com.aspose.threed/boundingbox/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class BoundingBox implements Struct<BoundingBox>, Serializable
```

Den axeljusterade begränsningsboxen **Example:** Följande kod visar hur man får en begränsningsbox från en Entity-instans.

```
var sphere = new Sphere();
      var boundingBox = sphere.getBoundingBox();
      System.out.println("Bounding box = " + boundingBox);
```
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [BoundingBox(Vector3 minimum, Vector3 maximum)](#BoundingBox-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Initiera en ändlig avgränsningsbox med angivet minsta och största hörn |
| [BoundingBox(double minX, double minY, double minZ, double maxX, double maxY, double maxZ)](#BoundingBox-double-double-double-double-double-double-) | Initiera en ändlig avgränsningsbox med angivet minsta och största hörn |
| [BoundingBox()](#BoundingBox--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(BoundingBox bbox)](#contains-com.aspose.threed.BoundingBox-) | Begränsningsboxen för att kontrollera om den är innanför den aktuella begränsningsboxen. |
| [contains(Vector3 p)](#contains-com.aspose.threed.Vector3-) | Kontrollera om punkten p är innanför begränsningsboxen |
| [copyFrom(BoundingBox src)](#copyFrom-com.aspose.threed.BoundingBox-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om två objekt är lika |
| [fromGeometry(Geometry geometry)](#fromGeometry-com.aspose.threed.Geometry-) | Konstruera en begränsningsbox från given geometri |
| [getCenter()](#getCenter--) | Centrum för begränsningsboxen. |
| [getClass()](#getClass--) |  |
| [getExtent()](#getExtent--) | Hämtar omfattningen av avgränsningsboxen. |
| [getInfinite()](#getInfinite--) | Den oändliga avgränsningsboxen |
| [getMaximum()](#getMaximum--) | Det maximala hörnet av avgränsningsboxen |
| [getMinimum()](#getMinimum--) | Det minsta hörnet av avgränsningsboxen |
| [getNull()](#getNull--) | Den nullavgränsningsboxen |
| [getSize()](#getSize--) | Storleken på begränsningsboxen |
| [hashCode()](#hashCode--) | Returnerar hash‑koden för detta objekt |
| [merge(BoundingBox bb)](#merge-com.aspose.threed.BoundingBox-) | Slår ihop den nya boxen med den aktuella avgränsningsboxen. |
| [merge(Vector3 pt)](#merge-com.aspose.threed.Vector3-) | Slå samman aktuell begränsningsbox med given punkt |
| [merge(Vector4 pt)](#merge-com.aspose.threed.Vector4-) | Slå samman aktuell begränsningsbox med given punkt |
| [merge(double x, double y, double z)](#merge-double-double-double-) | Slå samman aktuell begränsningsbox med given punkt |
| [mul(BoundingBox bbox, Matrix4 mat)](#mul-com.aspose.threed.BoundingBox-com.aspose.threed.Matrix4-) | Operatoröverkörning för multiplikation, den nya begränsningsboxens minsta och största hörn kommer att transformeras av matrisen. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [overlapsWith(BoundingBox box)](#overlapsWith-com.aspose.threed.BoundingBox-) | Kontrollera om aktuell begränsningsbox överlappar med angiven begränsningsbox. |
| [scale()](#scale--) | Beräknar det absoluta största koordinatvärdet för någon innehållen punkt. |
| [toString()](#toString--) | Hämtar strängrepresentationen av avgränsningsboxen. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BoundingBox(Vector3 minimum, Vector3 maximum) {#BoundingBox-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public BoundingBox(Vector3 minimum, Vector3 maximum)
```


Initiera en ändlig avgränsningsbox med angivet minsta och största hörn

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| minimum | [Vector3](../../com.aspose.threed/vector3) | Det minsta hörnet |
|  | maximum | [Vector3](../../com.aspose.threed/vector3) | Det största hörnet **Example:** Följande kod visar hur man konstruerar en begränsningsbox från minsta och största hörn. |

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


Initiera en ändlig avgränsningsbox med angivet minsta och största hörn

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| minX | double | Det minsta hörnets X |
| minY | double | Det minsta hörnets Y |
| minZ | double | Det minsta hörnets Z |
| maxX | double | Det största hörnets X |
| maxY | double | Det största hörnets Y |
|  | maxZ | double | Det största hörnets Z **Exempel:** Följande kod visar hur man konstruerar en begränsningsruta från minsta och största hörnen. |

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


Begränsningsboxen för att kontrollera om den är innanför den aktuella begränsningsboxen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bbox | [BoundingBox](../../com.aspose.threed/boundingbox) |  |

**Returns:**
boolean
### contains(Vector3 p) {#contains-com.aspose.threed.Vector3-}
```
public boolean contains(Vector3 p)
```


Kontrollera om punkten p är innanför begränsningsboxen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| p | [Vector3](../../com.aspose.threed/vector3) | Punkten att testa |

**Returns:**
boolean - Sant om punkten är innanför begränsningsrutan **Exempel:** Följande kod visar hur man kontrollerar om en punkt är innanför begränsningsrutan.

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| src | [BoundingBox](../../com.aspose.threed/boundingbox) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer om två objekt är lika

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Objektet att jämföra |

**Returns:**
boolean - sant om två objekt är lika
### fromGeometry(Geometry geometry) {#fromGeometry-com.aspose.threed.Geometry-}
```
public static BoundingBox fromGeometry(Geometry geometry)
```


Konstruera en begränsningsbox från given geometri

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| geometry | [Geometry](../../com.aspose.threed/geometry) | Geometrin för att beräkna begränsningsrutan |

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


Centrum för begränsningsboxen.

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


Hämtar omfattningen av avgränsningsboxen.

**Returns:**
[BoundingBoxExtent](../../com.aspose.threed/boundingboxextent) - the extent of the bounding box.
### getInfinite() {#getInfinite--}
```
public static BoundingBox getInfinite()
```


Den oändliga avgränsningsboxen

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The infinite bounding box
### getMaximum() {#getMaximum--}
```
public Vector3 getMaximum()
```


Det maximala hörnet av avgränsningsboxen

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The maximum corner of the bounding box
### getMinimum() {#getMinimum--}
```
public Vector3 getMinimum()
```


Det minsta hörnet av avgränsningsboxen

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The minimum corner of the bounding box
### getNull() {#getNull--}
```
public static BoundingBox getNull()
```


Den nullavgränsningsboxen

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The null bounding box
### getSize() {#getSize--}
```
public Vector3 getSize()
```


Storleken på begränsningsboxen

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The size of the bounding box
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar hash‑koden för detta objekt

**Returns:**
int - Hashkoden för begränsningsrutan
### merge(BoundingBox bb) {#merge-com.aspose.threed.BoundingBox-}
```
public void merge(BoundingBox bb)
```


Slår ihop den nya boxen med den aktuella avgränsningsboxen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bb | [BoundingBox](../../com.aspose.threed/boundingbox) | Avgränsningsboxen att slå ihop |

### merge(Vector3 pt) {#merge-com.aspose.threed.Vector3-}
```
public void merge(Vector3 pt)
```


Slå samman aktuell begränsningsbox med given punkt

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | pt | [Vector3](../../com.aspose.threed/vector3) | Punkten som ska slås ihop med begränsningsrutan **Exempel:** Följande kod visar hur man slår ihop en punkt med begränsningsrutan. |

```
var boundingBox = BoundingBox.getNull();
  boundingBox.Merge(new Vector3(1, 10, -1));
  System.out.println("Bounding box = " + boundingBox);
``` |

### merge(Vector4 pt) {#merge-com.aspose.threed.Vector4-}
```
public void merge(Vector4 pt)
```


Slå samman aktuell begränsningsbox med given punkt

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | pt | [Vector4](../../com.aspose.threed/vector4) | Punkten som ska slås ihop med begränsningsrutan **Exempel:** Följande kod visar hur man slår ihop en punkt med begränsningsrutan. |

```
var boundingBox = BoundingBox.getNull();
  boundingBox.Merge(new Vector4(1, 10, -1));
  System.out.println("Bounding box = " + boundingBox);
``` |

### merge(double x, double y, double z) {#merge-double-double-double-}
```
public void merge(double x, double y, double z)
```


Slå samman aktuell begränsningsbox med given punkt

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | double | Punkten som ska slås ihop med begränsningsrutan |
| y | double | Punkten som ska slås ihop med begränsningsrutan |
|  | z | double | Punkten som ska slås ihop med begränsningsrutan **Exempel:** Följande kod visar hur man slår ihop en punkt med begränsningsrutan. |

```
var boundingBox = BoundingBox.getNull();
  boundingBox.Merge(1, 10, -1);
  System.out.println("Bounding box = " + boundingBox);
``` |

### mul(BoundingBox bbox, Matrix4 mat) {#mul-com.aspose.threed.BoundingBox-com.aspose.threed.Matrix4-}
```
public static BoundingBox mul(BoundingBox bbox, Matrix4 mat)
```


Operatoröverkörning för multiplikation, den nya begränsningsboxens minsta och största hörn kommer att transformeras av matrisen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bbox | [BoundingBox](../../com.aspose.threed/boundingbox) | Den inmatade begränsningsrutan. |
| mat | [Matrix4](../../com.aspose.threed/matrix4) | Matrisen som används för att transformera begränsningsrutans hörn |

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


Kontrollera om aktuell begränsningsbox överlappar med angiven begränsningsbox.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| box | [BoundingBox](../../com.aspose.threed/boundingbox) | Den andra begränsningsrutan att testa |

**Returns:**
boolean - Sant om den aktuella begränsningsrutan överlappar med den givna. **Exempel:** Följande kod visar hur man kontrollerar om två begränsningsrutor överlappar varandra.

```
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
  var bbox2 = new BoundingBox(1, 1, 1, 11, 11, 11);
  System.out.println("Bounding box overlaps = " + boundingBox.overlapsWith(bbox2));
```
### scale() {#scale--}
```
public double scale()
```


Beräknar det absoluta största koordinatvärdet för någon innehållen punkt.

**Returns:**
double - det beräknade absoluta största koordinatvärdet för någon innesluten punkt.
### toString() {#toString--}
```
public String toString()
```


Hämtar strängrepresentationen av avgränsningsboxen.

**Returns:**
java.lang.String - Strängrepresentationen av begränsningsrutan.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

