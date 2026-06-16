---
title: "BoundingBox"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Le boîtier englobant aligné sur les axes Exemple  Le code suivant montre comment obtenir un boîtier englobant à partir d'une instance d'Entity."
type: docs
weight: 24
url: /fr/java/com.aspose.threed/boundingbox/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class BoundingBox implements Struct<BoundingBox>, Serializable
```

La boîte englobante alignée sur les axes **Example:** Le code suivant montre comment obtenir une boîte englobante à partir d'une instance d'Entity.

```
var sphere = new Sphere();
      var boundingBox = sphere.getBoundingBox();
      System.out.println("Bounding box = " + boundingBox);
```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [BoundingBox(Vector3 minimum, Vector3 maximum)](#BoundingBox-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Initialiser une boîte englobante finie avec les coins minimum et maximum donnés |
| [BoundingBox(double minX, double minY, double minZ, double maxX, double maxY, double maxZ)](#BoundingBox-double-double-double-double-double-double-) | Initialiser une boîte englobante finie avec les coins minimum et maximum donnés |
| [BoundingBox()](#BoundingBox--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(BoundingBox bbox)](#contains-com.aspose.threed.BoundingBox-) | Le boîtier englobant pour vérifier s'il est à l'intérieur du boîtier englobant actuel. |
| [contains(Vector3 p)](#contains-com.aspose.threed.Vector3-) | Vérifier si le point p est à l'intérieur du boîtier englobant |
| [copyFrom(BoundingBox src)](#copyFrom-com.aspose.threed.BoundingBox-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si deux objets sont égaux |
| [fromGeometry(Geometry geometry)](#fromGeometry-com.aspose.threed.Geometry-) | Construire un boîtier englobant à partir de la géométrie donnée |
| [getCenter()](#getCenter--) | Le centre du boîtier englobant. |
| [getClass()](#getClass--) |  |
| [getExtent()](#getExtent--) | Obtient l'étendue de la boîte englobante. |
| [getInfinite()](#getInfinite--) | La boîte englobante infinie |
| [getMaximum()](#getMaximum--) | Le coin maximum de la boîte englobante |
| [getMinimum()](#getMinimum--) | Le coin minimum de la boîte englobante |
| [getNull()](#getNull--) | La boîte englobante nulle |
| [getSize()](#getSize--) | La taille du boîtier englobant |
| [hashCode()](#hashCode--) | Renvoie le code de hachage pour cette instance |
| [merge(BoundingBox bb)](#merge-com.aspose.threed.BoundingBox-) | Fusionne la nouvelle boîte dans la boîte englobante actuelle. |
| [merge(Vector3 pt)](#merge-com.aspose.threed.Vector3-) | Fusionner le boîtier englobant actuel avec le point donné |
| [merge(Vector4 pt)](#merge-com.aspose.threed.Vector4-) | Fusionner le boîtier englobant actuel avec le point donné |
| [merge(double x, double y, double z)](#merge-double-double-double-) | Fusionner le boîtier englobant actuel avec le point donné |
| [mul(BoundingBox bbox, Matrix4 mat)](#mul-com.aspose.threed.BoundingBox-com.aspose.threed.Matrix4-) | Surcharge d'opérateur pour la multiplication, les coins minimum et maximum du nouveau boîtier englobant seront transformés par la matrice. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [overlapsWith(BoundingBox box)](#overlapsWith-com.aspose.threed.BoundingBox-) | Vérifier si le boîtier englobant actuel chevauche le boîtier englobant spécifié. |
| [scale()](#scale--) | Calcule la valeur absolue la plus grande d'une coordonnée de tout point contenu. |
| [toString()](#toString--) | Obtient la représentation sous forme de chaîne de la boîte englobante. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BoundingBox(Vector3 minimum, Vector3 maximum) {#BoundingBox-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public BoundingBox(Vector3 minimum, Vector3 maximum)
```


Initialiser une boîte englobante finie avec les coins minimum et maximum donnés

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| minimum | [Vector3](../../com.aspose.threed/vector3) | Le coin minimum |
|  | maximum | [Vector3](../../com.aspose.threed/vector3) | Le coin maximum **Exemple:** Le code suivant montre comment construire un boîtier englobant à partir des coins minimum et maximum. |

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


Initialiser une boîte englobante finie avec les coins minimum et maximum donnés

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| minX | double | Le X du coin minimum |
| minY | double | Le Y du coin minimum |
| minZ | double | Le Z du coin minimum |
| maxX | double | Le X du coin maximum |
| maxY | double | Le Y du coin maximum |
|  | maxZ | double | Le Z du coin maximum **Exemple:** Le code suivant montre comment construire une boîte englobante à partir des coins minimum et maximum. |

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


Cloner l'instance actuelle

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox)
### contains(BoundingBox bbox) {#contains-com.aspose.threed.BoundingBox-}
```
public boolean contains(BoundingBox bbox)
```


Le boîtier englobant pour vérifier s'il est à l'intérieur du boîtier englobant actuel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bbox | [BoundingBox](../../com.aspose.threed/boundingbox) |  |

**Returns:**
boolean
### contains(Vector3 p) {#contains-com.aspose.threed.Vector3-}
```
public boolean contains(Vector3 p)
```


Vérifier si le point p est à l'intérieur du boîtier englobant

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| p | [Vector3](../../com.aspose.threed/vector3) | Le point à tester |

**Returns:**
boolean - Vrai si le point est à l'intérieur de la boîte englobante **Exemple:** Le code suivant montre comment vérifier si un point est à l'intérieur de la boîte englobante.

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
| Paramètre | Type | Description |
| --- | --- | --- |
| src | [BoundingBox](../../com.aspose.threed/boundingbox) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si deux objets sont égaux

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | L'objet à comparer |

**Returns:**
boolean - vrai si deux objets sont égaux
### fromGeometry(Geometry geometry) {#fromGeometry-com.aspose.threed.Geometry-}
```
public static BoundingBox fromGeometry(Geometry geometry)
```


Construire un boîtier englobant à partir de la géométrie donnée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| geometry | [Geometry](../../com.aspose.threed/geometry) | La géométrie pour calculer la boîte englobante |

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


Le centre du boîtier englobant.

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


Obtient l'étendue de la boîte englobante.

**Returns:**
[BoundingBoxExtent](../../com.aspose.threed/boundingboxextent) - the extent of the bounding box.
### getInfinite() {#getInfinite--}
```
public static BoundingBox getInfinite()
```


La boîte englobante infinie

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The infinite bounding box
### getMaximum() {#getMaximum--}
```
public Vector3 getMaximum()
```


Le coin maximum de la boîte englobante

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The maximum corner of the bounding box
### getMinimum() {#getMinimum--}
```
public Vector3 getMinimum()
```


Le coin minimum de la boîte englobante

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The minimum corner of the bounding box
### getNull() {#getNull--}
```
public static BoundingBox getNull()
```


La boîte englobante nulle

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The null bounding box
### getSize() {#getSize--}
```
public Vector3 getSize()
```


La taille du boîtier englobant

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The size of the bounding box
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie le code de hachage pour cette instance

**Returns:**
int - Le code de hachage de la boîte englobante
### merge(BoundingBox bb) {#merge-com.aspose.threed.BoundingBox-}
```
public void merge(BoundingBox bb)
```


Fusionne la nouvelle boîte dans la boîte englobante actuelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bb | [BoundingBox](../../com.aspose.threed/boundingbox) | La boîte englobante à fusionner |

### merge(Vector3 pt) {#merge-com.aspose.threed.Vector3-}
```
public void merge(Vector3 pt)
```


Fusionner le boîtier englobant actuel avec le point donné

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | pt | [Vector3](../../com.aspose.threed/vector3) | Le point à fusionner dans la boîte englobante **Exemple:** Le code suivant montre comment fusionner un point dans la boîte englobante. |

```
var boundingBox = BoundingBox.getNull();
  boundingBox.Merge(new Vector3(1, 10, -1));
  System.out.println("Bounding box = " + boundingBox);
``` |

### merge(Vector4 pt) {#merge-com.aspose.threed.Vector4-}
```
public void merge(Vector4 pt)
```


Fusionner le boîtier englobant actuel avec le point donné

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | pt | [Vector4](../../com.aspose.threed/vector4) | Le point à fusionner dans la boîte englobante **Exemple:** Le code suivant montre comment fusionner un point dans la boîte englobante. |

```
var boundingBox = BoundingBox.getNull();
  boundingBox.Merge(new Vector4(1, 10, -1));
  System.out.println("Bounding box = " + boundingBox);
``` |

### merge(double x, double y, double z) {#merge-double-double-double-}
```
public void merge(double x, double y, double z)
```


Fusionner le boîtier englobant actuel avec le point donné

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | double | Le point à fusionner dans la boîte englobante |
| y | double | Le point à fusionner dans la boîte englobante |
|  | z | double | Le point à fusionner dans la boîte englobante **Exemple:** Le code suivant montre comment fusionner un point dans la boîte englobante. |

```
var boundingBox = BoundingBox.getNull();
  boundingBox.Merge(1, 10, -1);
  System.out.println("Bounding box = " + boundingBox);
``` |

### mul(BoundingBox bbox, Matrix4 mat) {#mul-com.aspose.threed.BoundingBox-com.aspose.threed.Matrix4-}
```
public static BoundingBox mul(BoundingBox bbox, Matrix4 mat)
```


Surcharge d'opérateur pour la multiplication, les coins minimum et maximum du nouveau boîtier englobant seront transformés par la matrice.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bbox | [BoundingBox](../../com.aspose.threed/boundingbox) | La boîte englobante d'entrée. |
| mat | [Matrix4](../../com.aspose.threed/matrix4) | La matrice utilisée pour transformer les coins de la boîte englobante |

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


Vérifier si le boîtier englobant actuel chevauche le boîtier englobant spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| box | [BoundingBox](../../com.aspose.threed/boundingbox) | L'autre boîte englobante à tester |

**Returns:**
boolean - Vrai si la boîte englobante actuelle chevauche celle donnée. **Exemple:** Le code suivant montre comment vérifier si deux boîtes englobantes se chevauchent.

```
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
  var bbox2 = new BoundingBox(1, 1, 1, 11, 11, 11);
  System.out.println("Bounding box overlaps = " + boundingBox.overlapsWith(bbox2));
```
### scale() {#scale--}
```
public double scale()
```


Calcule la valeur absolue la plus grande d'une coordonnée de tout point contenu.

**Returns:**
double - la valeur absolue maximale calculée de toute coordonnée d'un point contenu.
### toString() {#toString--}
```
public String toString()
```


Obtient la représentation sous forme de chaîne de la boîte englobante.

**Returns:**
java.lang.String - La représentation sous forme de chaîne de la boîte englobante.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

