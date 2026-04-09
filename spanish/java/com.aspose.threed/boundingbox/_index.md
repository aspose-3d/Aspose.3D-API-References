---
title: BoundingBox
second_title: Referencia de API de Aspose.3D para Java
description: El cuadro delimitador alineado a los ejes Ejemplo  El siguiente código muestra cómo obtener un cuadro delimitador a partir de una instancia de Entity.
type: docs
weight: 24
url: /es/java/com.aspose.threed/boundingbox/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class BoundingBox implements Struct<BoundingBox>, Serializable
```

El cuadro delimitador alineado a los ejes **Example:** El siguiente código muestra cómo obtener un cuadro delimitador a partir de una instancia de Entity.

```
var sphere = new Sphere();
      var boundingBox = sphere.getBoundingBox();
      System.out.println("Bounding box = " + boundingBox);
```
## Constructores

| Constructor | Descripción |
| --- | --- |
| [BoundingBox(Vector3 minimum, Vector3 maximum)](#BoundingBox-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Inicializa un cuadro delimitador finito con la esquina mínima y máxima dadas |
| [BoundingBox(double minX, double minY, double minZ, double maxX, double maxY, double maxZ)](#BoundingBox-double-double-double-double-double-double-) | Inicializa un cuadro delimitador finito con la esquina mínima y máxima dadas |
| [BoundingBox()](#BoundingBox--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(BoundingBox bbox)](#contains-com.aspose.threed.BoundingBox-) | El cuadro delimitador para comprobar si está dentro del cuadro delimitador actual. |
| [contains(Vector3 p)](#contains-com.aspose.threed.Vector3-) | Comprobar si el punto p está dentro del cuadro delimitador |
| [copyFrom(BoundingBox src)](#copyFrom-com.aspose.threed.BoundingBox-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si dos objetos son iguales |
| [fromGeometry(Geometry geometry)](#fromGeometry-com.aspose.threed.Geometry-) | Construir un cuadro delimitador a partir de la geometría dada |
| [getCenter()](#getCenter--) | El centro del cuadro delimitador. |
| [getClass()](#getClass--) |  |
| [getExtent()](#getExtent--) | Obtiene la extensión del cuadro delimitador. |
| [getInfinite()](#getInfinite--) | El cuadro delimitador infinito |
| [getMaximum()](#getMaximum--) | La esquina máxima del cuadro delimitador |
| [getMinimum()](#getMinimum--) | La esquina mínima del cuadro delimitador |
| [getNull()](#getNull--) | El cuadro delimitador nulo |
| [getSize()](#getSize--) | El tamaño del cuadro delimitador |
| [hashCode()](#hashCode--) | Devuelve el código hash para esta instancia |
| [merge(BoundingBox bb)](#merge-com.aspose.threed.BoundingBox-) | Fusiona el nuevo cuadro con el cuadro delimitador actual. |
| [merge(Vector3 pt)](#merge-com.aspose.threed.Vector3-) | Combinar el cuadro delimitador actual con el punto dado |
| [merge(Vector4 pt)](#merge-com.aspose.threed.Vector4-) | Combinar el cuadro delimitador actual con el punto dado |
| [merge(double x, double y, double z)](#merge-double-double-double-) | Combinar el cuadro delimitador actual con el punto dado |
| [mul(BoundingBox bbox, Matrix4 mat)](#mul-com.aspose.threed.BoundingBox-com.aspose.threed.Matrix4-) | Sobrecarga de operador para multiplicar, la esquina mínima y máxima del nuevo cuadro delimitador serán transformadas por la matriz. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [overlapsWith(BoundingBox box)](#overlapsWith-com.aspose.threed.BoundingBox-) | Comprobar si el cuadro delimitador actual se superpone con el cuadro delimitador especificado. |
| [scale()](#scale--) | Calcula el valor absoluto más grande de coordenada de cualquier punto contenido. |
| [toString()](#toString--) | Obtiene la representación en cadena del cuadro delimitador. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BoundingBox(Vector3 minimum, Vector3 maximum) {#BoundingBox-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public BoundingBox(Vector3 minimum, Vector3 maximum)
```


Inicializa un cuadro delimitador finito con la esquina mínima y máxima dadas

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| minimum | [Vector3](../../com.aspose.threed/vector3) | La esquina mínima |
|  | maximum | [Vector3](../../com.aspose.threed/vector3) | La esquina máxima **Ejemplo:** El siguiente código muestra cómo construir un cuadro delimitador a partir de las esquinas mínima y máxima. |

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


Inicializa un cuadro delimitador finito con la esquina mínima y máxima dadas

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| minX | double | La X de la esquina mínima |
| minY | double | La Y de la esquina mínima |
| minZ | double | La Z de la esquina mínima |
| maxX | double | La X de la esquina máxima |
| maxY | double | La Y de la esquina máxima |
|  | maxZ | double | La Z de la esquina máxima **Ejemplo:** El siguiente código muestra cómo construir un cuadro delimitador a partir de las esquinas mínima y máxima. |

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


Clonar la instancia actual

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox)
### contains(BoundingBox bbox) {#contains-com.aspose.threed.BoundingBox-}
```
public boolean contains(BoundingBox bbox)
```


El cuadro delimitador para comprobar si está dentro del cuadro delimitador actual.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bbox | [BoundingBox](../../com.aspose.threed/boundingbox) |  |

**Returns:**
boolean
### contains(Vector3 p) {#contains-com.aspose.threed.Vector3-}
```
public boolean contains(Vector3 p)
```


Comprobar si el punto p está dentro del cuadro delimitador

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| p | [Vector3](../../com.aspose.threed/vector3) | El punto a probar |

**Returns:**
boolean - Verdadero si el punto está dentro del cuadro delimitador **Ejemplo:** El siguiente código muestra cómo comprobar si un punto está dentro del cuadro delimitador.

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| src | [BoundingBox](../../com.aspose.threed/boundingbox) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si dos objetos son iguales

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El objeto a comparar |

**Returns:**
boolean - verdadero si dos objetos son iguales
### fromGeometry(Geometry geometry) {#fromGeometry-com.aspose.threed.Geometry-}
```
public static BoundingBox fromGeometry(Geometry geometry)
```


Construir un cuadro delimitador a partir de la geometría dada

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| geometry | [Geometry](../../com.aspose.threed/geometry) | La geometría para calcular el cuadro delimitador |

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


El centro del cuadro delimitador.

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


Obtiene la extensión del cuadro delimitador.

**Returns:**
[BoundingBoxExtent](../../com.aspose.threed/boundingboxextent) - the extent of the bounding box.
### getInfinite() {#getInfinite--}
```
public static BoundingBox getInfinite()
```


El cuadro delimitador infinito

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The infinite bounding box
### getMaximum() {#getMaximum--}
```
public Vector3 getMaximum()
```


La esquina máxima del cuadro delimitador

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The maximum corner of the bounding box
### getMinimum() {#getMinimum--}
```
public Vector3 getMinimum()
```


La esquina mínima del cuadro delimitador

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The minimum corner of the bounding box
### getNull() {#getNull--}
```
public static BoundingBox getNull()
```


El cuadro delimitador nulo

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The null bounding box
### getSize() {#getSize--}
```
public Vector3 getSize()
```


El tamaño del cuadro delimitador

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The size of the bounding box
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve el código hash para esta instancia

**Returns:**
int - El código hash del cuadro delimitador
### merge(BoundingBox bb) {#merge-com.aspose.threed.BoundingBox-}
```
public void merge(BoundingBox bb)
```


Fusiona el nuevo cuadro con el cuadro delimitador actual.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bb | [BoundingBox](../../com.aspose.threed/boundingbox) | El cuadro delimitador a fusionar |

### merge(Vector3 pt) {#merge-com.aspose.threed.Vector3-}
```
public void merge(Vector3 pt)
```


Combinar el cuadro delimitador actual con el punto dado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | pt | [Vector3](../../com.aspose.threed/vector3) | El punto que se fusionará en el cuadro delimitador **Ejemplo:** El siguiente código muestra cómo fusionar un punto al cuadro delimitador. |

```
var boundingBox = BoundingBox.getNull();
  boundingBox.Merge(new Vector3(1, 10, -1));
  System.out.println("Bounding box = " + boundingBox);
``` |

### merge(Vector4 pt) {#merge-com.aspose.threed.Vector4-}
```
public void merge(Vector4 pt)
```


Combinar el cuadro delimitador actual con el punto dado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | pt | [Vector4](../../com.aspose.threed/vector4) | El punto que se fusionará en el cuadro delimitador **Ejemplo:** El siguiente código muestra cómo fusionar un punto al cuadro delimitador. |

```
var boundingBox = BoundingBox.getNull();
  boundingBox.Merge(new Vector4(1, 10, -1));
  System.out.println("Bounding box = " + boundingBox);
``` |

### merge(double x, double y, double z) {#merge-double-double-double-}
```
public void merge(double x, double y, double z)
```


Combinar el cuadro delimitador actual con el punto dado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | double | El punto que se fusionará en el cuadro delimitador |
| y | double | El punto que se fusionará en el cuadro delimitador |
|  | z | double | El punto que se fusionará en el cuadro delimitador **Ejemplo:** El siguiente código muestra cómo fusionar un punto al cuadro delimitador. |

```
var boundingBox = BoundingBox.getNull();
  boundingBox.Merge(1, 10, -1);
  System.out.println("Bounding box = " + boundingBox);
``` |

### mul(BoundingBox bbox, Matrix4 mat) {#mul-com.aspose.threed.BoundingBox-com.aspose.threed.Matrix4-}
```
public static BoundingBox mul(BoundingBox bbox, Matrix4 mat)
```


Sobrecarga de operador para multiplicar, la esquina mínima y máxima del nuevo cuadro delimitador serán transformadas por la matriz.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bbox | [BoundingBox](../../com.aspose.threed/boundingbox) | El cuadro delimitador de entrada. |
| mat | [Matrix4](../../com.aspose.threed/matrix4) | La matriz utilizada para transformar las esquinas del cuadro delimitador |

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


Comprobar si el cuadro delimitador actual se superpone con el cuadro delimitador especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| box | [BoundingBox](../../com.aspose.threed/boundingbox) | El otro cuadro delimitador a probar |

**Returns:**
boolean - Verdadero si el cuadro delimitador actual se superpone con el dado. **Ejemplo:** El siguiente código muestra cómo comprobar si dos cuadros delimitadores se superponen entre sí.

```
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
  var bbox2 = new BoundingBox(1, 1, 1, 11, 11, 11);
  System.out.println("Bounding box overlaps = " + boundingBox.overlapsWith(bbox2));
```
### scale() {#scale--}
```
public double scale()
```


Calcula el valor absoluto más grande de coordenada de cualquier punto contenido.

**Returns:**
double - el valor absoluto más grande calculado de cualquier coordenada de punto contenido.
### toString() {#toString--}
```
public String toString()
```


Obtiene la representación en cadena del cuadro delimitador.

**Returns:**
java.lang.String - La representación en cadena del cuadro delimitador.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

