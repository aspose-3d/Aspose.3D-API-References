---
title: "Vector4"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Un vecteur à quatre composantes."
type: docs
weight: 203
url: /fr/java/com.aspose.threed/vector4/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.threed.Struct, java.io.Serializable
```
public final class Vector4 implements Comparable<Vector4>, Struct<Vector4>, Serializable
```

Un vecteur à quatre composantes.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Vector4(Vector3 vec, double w)](#Vector4-com.aspose.threed.Vector3-double-) | Initialise une nouvelle instance de la structure [Vector4](../../com.aspose.threed/vector4). |
| [Vector4(Vector3 vec)](#Vector4-com.aspose.threed.Vector3-) | Initialise une nouvelle instance de la structure [Vector4](../../com.aspose.threed/vector4). |
| [Vector4(FVector4 vec)](#Vector4-com.aspose.threed.FVector4-) | Initialise une nouvelle instance de la structure [Vector4](../../com.aspose.threed/vector4). |
| [Vector4(double x, double y, double z)](#Vector4-double-double-double-) | Initialise une nouvelle instance de la structure [Vector4](../../com.aspose.threed/vector4). |
| [Vector4(double x, double y, double z, double w)](#Vector4-double-double-double-double-) | Initialise une nouvelle instance de la structure [Vector4](../../com.aspose.threed/vector4). |
| [Vector4()](#Vector4--) |  |
## Champs

| Champ | Description |
| --- | --- |
| [w](#w) | Le composant w. |
| [x](#x) | Le composant x. |
| [y](#y) | Le composant y. |
| [z](#z) | Le composant z. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [add(Vector4 lhs, Vector4 rhs)](#add-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | Surcharge d'opérateur pour + |
| [clone()](#clone--) |  |
| [compareTo(Vector4 other)](#compareTo-com.aspose.threed.Vector4-) | Compare le vecteur actuel à une autre instance. |
| [copyFrom(Vector4 src)](#copyFrom-com.aspose.threed.Vector4-) |  |
| [create(Vector4 v)](#create-com.aspose.threed.Vector4-) | Opérateur de conversion explicite pour convertir Vector4 en FVector4 |
| [equals(Object obj)](#equals-java.lang.Object-) | Vérifier si deux vecteurs sont égaux |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | Obtient le code de hachage de ce vecteur |
| [mul(Vector4 lhs, Vector4 rhs)](#mul-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | Surcharge d'opérateur pour \* |
| [mul(Vector4 lhs, double rhs)](#mul-com.aspose.threed.Vector4-double-) | Surcharge d'opérateur pour \* |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [set(double newX, double newY, double newZ)](#set-double-double-double-) | Définit les composantes xyz du vecteur en une fois, w sera défini à 1 |
| [set(double newX, double newY, double newZ, double newW)](#set-double-double-double-double-) | Définit toutes les composantes du vecteur en une fois |
| [sub(Vector4 lhs, Vector4 rhs)](#sub-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | Surcharge d'opérateur pour - (moins) |
| [toString()](#toString--) | Renvoie un java.lang.String qui représente le [Vector4](../../com.aspose.threed/vector4) actuel. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Vector4(Vector3 vec, double w) {#Vector4-com.aspose.threed.Vector3-double-}
```
public Vector4(Vector3 vec, double w)
```


Initialise une nouvelle instance de la structure [Vector4](../../com.aspose.threed/vector4).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) | Vec. |
| w | double | La largeur. |

### Vector4(Vector3 vec) {#Vector4-com.aspose.threed.Vector3-}
```
public Vector4(Vector3 vec)
```


Initialise une nouvelle instance de la structure [Vector4](../../com.aspose.threed/vector4).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) | Vec. |

### Vector4(FVector4 vec) {#Vector4-com.aspose.threed.FVector4-}
```
public Vector4(FVector4 vec)
```


Initialise une nouvelle instance de la structure [Vector4](../../com.aspose.threed/vector4).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| vec | [FVector4](../../com.aspose.threed/fvector4) | Vec. |

### Vector4(double x, double y, double z) {#Vector4-double-double-double-}
```
public Vector4(double x, double y, double z)
```


Initialise une nouvelle instance de la structure [Vector4](../../com.aspose.threed/vector4).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | double | La coordonnée x. |
| y | double | La coordonnée y. |
| z | double | La coordonnée z. |

### Vector4(double x, double y, double z, double w) {#Vector4-double-double-double-double-}
```
public Vector4(double x, double y, double z, double w)
```


Initialise une nouvelle instance de la structure [Vector4](../../com.aspose.threed/vector4).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | double | La coordonnée x. |
| y | double | La coordonnée y. |
| z | double | La coordonnée z. |
| w | double | La largeur. |

### Vector4() {#Vector4--}
```
public Vector4()
```


### w {#w}
```
public double w
```


Le composant w.

### x {#x}
```
public double x
```


Le composant x.

### y {#y}
```
public double y
```


Le composant y.

### z {#z}
```
public double z
```


Le composant z.

### add(Vector4 lhs, Vector4 rhs) {#add-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public static Vector4 add(Vector4 lhs, Vector4 rhs)
```


Surcharge d'opérateur pour +

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | Le vecteur gauche |
| rhs | [Vector4](../../com.aspose.threed/vector4) | Le vecteur droit |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### clone() {#clone--}
```
public Vector4 clone()
```


Cloner l'instance actuelle

**Returns:**
[Vector4](../../com.aspose.threed/vector4)
### compareTo(Vector4 other) {#compareTo-com.aspose.threed.Vector4-}
```
public int compareTo(Vector4 other)
```


Compare le vecteur actuel à une autre instance.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| other | [Vector4](../../com.aspose.threed/vector4) |  |

**Returns:**
int
### copyFrom(Vector4 src) {#copyFrom-com.aspose.threed.Vector4-}
```
public void copyFrom(Vector4 src)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| src | [Vector4](../../com.aspose.threed/vector4) |  |

### create(Vector4 v) {#create-com.aspose.threed.Vector4-}
```
public static FVector4 create(Vector4 v)
```


Opérateur de conversion explicite pour convertir Vector4 en FVector4

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| v | [Vector4](../../com.aspose.threed/vector4) |  |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Vérifier si deux vecteurs sont égaux

**Parameters:**
| Paramètre | Type | Description |
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
### hashCode() {#hashCode--}
```
public int hashCode()
```


Obtient le code de hachage de ce vecteur

**Returns:**
int
### mul(Vector4 lhs, Vector4 rhs) {#mul-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public static Vector4 mul(Vector4 lhs, Vector4 rhs)
```


Surcharge d'opérateur pour \*

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | Le vecteur gauche |
| rhs | [Vector4](../../com.aspose.threed/vector4) | Le vecteur droit |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### mul(Vector4 lhs, double rhs) {#mul-com.aspose.threed.Vector4-double-}
```
public static Vector4 mul(Vector4 lhs, double rhs)
```


Surcharge d'opérateur pour \*

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | Le vecteur gauche |
| rhs | double | La valeur double de droite |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### set(double newX, double newY, double newZ) {#set-double-double-double-}
```
public void set(double newX, double newY, double newZ)
```


Définit les composantes xyz du vecteur en une fois, w sera défini à 1

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newX | double | Nouvelle composante X. |
| newY | double | Nouvelle composante Y. |
| newZ | double | Nouvelle composante Z. |

### set(double newX, double newY, double newZ, double newW) {#set-double-double-double-double-}
```
public void set(double newX, double newY, double newZ, double newW)
```


Définit toutes les composantes du vecteur en une fois

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newX | double | Nouvelle composante X. |
| newY | double | Nouvelle composante Y. |
| newZ | double | Nouvelle composante Z. |
| newW | double | Nouveau composant W. |

### sub(Vector4 lhs, Vector4 rhs) {#sub-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public static Vector4 sub(Vector4 lhs, Vector4 rhs)
```


Surcharge d'opérateur pour - (moins)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | Le vecteur gauche |
| rhs | [Vector4](../../com.aspose.threed/vector4) | Le vecteur droit |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### toString() {#toString--}
```
public String toString()
```


Renvoie un java.lang.String qui représente le [Vector4](../../com.aspose.threed/vector4) actuel.

**Returns:**
java.lang.String - Une java.lang.String qui représente le [Vector4](../../com.aspose.threed/vector4) actuel.
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

