---
title: BoundingBox
second_title: Aspose.3D for Java API Reference
description: Il BoundingBox allineato agli assi Esempio  Il codice seguente mostra come ottenere un BoundingBox da un'istanza di Entity.
type: docs
weight: 24
url: /it/java/com.aspose.threed/boundingbox/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class BoundingBox implements Struct<BoundingBox>, Serializable
```

Il bounding box allineato agli assi **Esempio:** Il codice seguente mostra come ottenere un bounding box da un'istanza di Entity.

```
var sphere = new Sphere();
      var boundingBox = sphere.getBoundingBox();
      System.out.println("Bounding box = " + boundingBox);
```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [BoundingBox(Vector3 minimum, Vector3 maximum)](#BoundingBox-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Inizializza un box di delimitazione finito con gli angoli minimo e massimo specificati |
| [BoundingBox(double minX, double minY, double minZ, double maxX, double maxY, double maxZ)](#BoundingBox-double-double-double-double-double-double-) | Inizializza un box di delimitazione finito con gli angoli minimo e massimo specificati |
| [BoundingBox()](#BoundingBox--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(BoundingBox bbox)](#contains-com.aspose.threed.BoundingBox-) | Il bounding box per verificare se è all'interno del bounding box corrente. |
| [contains(Vector3 p)](#contains-com.aspose.threed.Vector3-) | Verifica se il punto p è all'interno del bounding box |
| [copyFrom(BoundingBox src)](#copyFrom-com.aspose.threed.BoundingBox-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se due oggetti sono uguali |
| [fromGeometry(Geometry geometry)](#fromGeometry-com.aspose.threed.Geometry-) | Costruisci un bounding box dalla geometria fornita |
| [getCenter()](#getCenter--) | Il centro del bounding box. |
| [getClass()](#getClass--) |  |
| [getExtent()](#getExtent--) | Restituisce l'estensione del box di delimitazione. |
| [getInfinite()](#getInfinite--) | Il box di delimitazione infinito |
| [getMaximum()](#getMaximum--) | L'angolo massimo del box di delimitazione |
| [getMinimum()](#getMinimum--) | L'angolo minimo del box di delimitazione |
| [getNull()](#getNull--) | Il box di delimitazione nullo |
| [getSize()](#getSize--) | La dimensione del bounding box |
| [hashCode()](#hashCode--) | Restituisce il codice hash per questa istanza |
| [merge(BoundingBox bb)](#merge-com.aspose.threed.BoundingBox-) | Unisce il nuovo box al box di delimitazione corrente. |
| [merge(Vector3 pt)](#merge-com.aspose.threed.Vector3-) | Unisci il bounding box corrente con il punto fornito |
| [merge(Vector4 pt)](#merge-com.aspose.threed.Vector4-) | Unisci il bounding box corrente con il punto fornito |
| [merge(double x, double y, double z)](#merge-double-double-double-) | Unisci il bounding box corrente con il punto fornito |
| [mul(BoundingBox bbox, Matrix4 mat)](#mul-com.aspose.threed.BoundingBox-com.aspose.threed.Matrix4-) | Sovraccarico dell'operatore per la moltiplicazione, gli angoli minimo e massimo del nuovo bounding box saranno trasformati dalla matrice. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [overlapsWith(BoundingBox box)](#overlapsWith-com.aspose.threed.BoundingBox-) | Verifica se il bounding box corrente si sovrappone al bounding box specificato. |
| [scale()](#scale--) | Calcola il valore assoluto più grande della coordinata di qualsiasi punto contenuto. |
| [toString()](#toString--) | Restituisce la rappresentazione stringa del box di delimitazione. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BoundingBox(Vector3 minimum, Vector3 maximum) {#BoundingBox-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public BoundingBox(Vector3 minimum, Vector3 maximum)
```


Inizializza un box di delimitazione finito con gli angoli minimo e massimo specificati

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| minimum | [Vector3](../../com.aspose.threed/vector3) | L'angolo minimo |
|  | maximum | [Vector3](../../com.aspose.threed/vector3) | L'angolo massimo **Example:** Il codice seguente mostra come costruire un bounding box da angoli minimo e massimo. |

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


Inizializza un box di delimitazione finito con gli angoli minimo e massimo specificati

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| minX | double | L'X dell'angolo minimo |
| minY | double | Il Y dell'angolo minimo |
| minZ | double | Il Z dell'angolo minimo |
| maxX | double | Il X dell'angolo massimo |
| maxY | double | Il Y dell'angolo massimo |
|  | maxZ | double | Il Z dell'angolo massimo **Example:** Il codice seguente mostra come costruire un bounding box dagli angoli minimo e massimo. |

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


Il bounding box per verificare se è all'interno del bounding box corrente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bbox | [BoundingBox](../../com.aspose.threed/boundingbox) |  |

**Returns:**
boolean
### contains(Vector3 p) {#contains-com.aspose.threed.Vector3-}
```
public boolean contains(Vector3 p)
```


Verifica se il punto p è all'interno del bounding box

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| p | [Vector3](../../com.aspose.threed/vector3) | Il punto da testare |

**Returns:**
boolean - True se il punto è all'interno del bounding box **Example:** Il codice seguente mostra come verificare se un punto è all'interno del bounding box.

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| src | [BoundingBox](../../com.aspose.threed/boundingbox) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se due oggetti sono uguali

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'oggetto da confrontare |

**Returns:**
boolean - true se due oggetti sono uguali
### fromGeometry(Geometry geometry) {#fromGeometry-com.aspose.threed.Geometry-}
```
public static BoundingBox fromGeometry(Geometry geometry)
```


Costruisci un bounding box dalla geometria fornita

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| geometry | [Geometry](../../com.aspose.threed/geometry) | La geometria per calcolare il bounding box |

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


Il centro del bounding box.

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


Restituisce l'estensione del box di delimitazione.

**Returns:**
[BoundingBoxExtent](../../com.aspose.threed/boundingboxextent) - the extent of the bounding box.
### getInfinite() {#getInfinite--}
```
public static BoundingBox getInfinite()
```


Il box di delimitazione infinito

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The infinite bounding box
### getMaximum() {#getMaximum--}
```
public Vector3 getMaximum()
```


L'angolo massimo del box di delimitazione

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The maximum corner of the bounding box
### getMinimum() {#getMinimum--}
```
public Vector3 getMinimum()
```


L'angolo minimo del box di delimitazione

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The minimum corner of the bounding box
### getNull() {#getNull--}
```
public static BoundingBox getNull()
```


Il box di delimitazione nullo

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The null bounding box
### getSize() {#getSize--}
```
public Vector3 getSize()
```


La dimensione del bounding box

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The size of the bounding box
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce il codice hash per questa istanza

**Returns:**
int - Il codice hash del bounding box
### merge(BoundingBox bb) {#merge-com.aspose.threed.BoundingBox-}
```
public void merge(BoundingBox bb)
```


Unisce il nuovo box al box di delimitazione corrente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bb | [BoundingBox](../../com.aspose.threed/boundingbox) | Il box di delimitazione da unire |

### merge(Vector3 pt) {#merge-com.aspose.threed.Vector3-}
```
public void merge(Vector3 pt)
```


Unisci il bounding box corrente con il punto fornito

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | pt | [Vector3](../../com.aspose.threed/vector3) | Il punto da unire al bounding box **Example:** Il codice seguente mostra come unire un punto al bounding box. |

```
var boundingBox = BoundingBox.getNull();
  boundingBox.Merge(new Vector3(1, 10, -1));
  System.out.println("Bounding box = " + boundingBox);
``` |

### merge(Vector4 pt) {#merge-com.aspose.threed.Vector4-}
```
public void merge(Vector4 pt)
```


Unisci il bounding box corrente con il punto fornito

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | pt | [Vector4](../../com.aspose.threed/vector4) | Il punto da unire al bounding box **Example:** Il codice seguente mostra come unire un punto al bounding box. |

```
var boundingBox = BoundingBox.getNull();
  boundingBox.Merge(new Vector4(1, 10, -1));
  System.out.println("Bounding box = " + boundingBox);
``` |

### merge(double x, double y, double z) {#merge-double-double-double-}
```
public void merge(double x, double y, double z)
```


Unisci il bounding box corrente con il punto fornito

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | double | Il punto da unire al bounding box |
| y | double | Il punto da unire al bounding box |
|  | z | double | Il punto da unire al bounding box **Example:** Il codice seguente mostra come unire un punto al bounding box. |

```
var boundingBox = BoundingBox.getNull();
  boundingBox.Merge(1, 10, -1);
  System.out.println("Bounding box = " + boundingBox);
``` |

### mul(BoundingBox bbox, Matrix4 mat) {#mul-com.aspose.threed.BoundingBox-com.aspose.threed.Matrix4-}
```
public static BoundingBox mul(BoundingBox bbox, Matrix4 mat)
```


Sovraccarico dell'operatore per la moltiplicazione, gli angoli minimo e massimo del nuovo bounding box saranno trasformati dalla matrice.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bbox | [BoundingBox](../../com.aspose.threed/boundingbox) | Il bounding box di input. |
| mat | [Matrix4](../../com.aspose.threed/matrix4) | La matrice usata per trasformare gli angoli del bounding box |

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


Verifica se il bounding box corrente si sovrappone al bounding box specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| box | [BoundingBox](../../com.aspose.threed/boundingbox) | L'altro bounding box da testare |

**Returns:**
boolean - True se il bounding box corrente si sovrappone a quello fornito. **Example:** Il codice seguente mostra come verificare se due bounding box si sovrappongono tra loro.

```
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
  var bbox2 = new BoundingBox(1, 1, 1, 11, 11, 11);
  System.out.println("Bounding box overlaps = " + boundingBox.overlapsWith(bbox2));
```
### scale() {#scale--}
```
public double scale()
```


Calcola il valore assoluto più grande della coordinata di qualsiasi punto contenuto.

**Returns:**
double - il valore assoluto più grande della coordinata calcolata di qualsiasi punto contenuto.
### toString() {#toString--}
```
public String toString()
```


Restituisce la rappresentazione stringa del box di delimitazione.

**Returns:**
java.lang.String - La rappresentazione stringa del bounding box.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

