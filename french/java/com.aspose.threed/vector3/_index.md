---
title: "Vector3"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Un vecteur à trois composantes."
type: docs
weight: 202
url: /fr/java/com.aspose.threed/vector3/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.threed.Struct, java.io.Serializable
```
public final class Vector3 implements Comparable<Vector3>, Struct<Vector3>, Serializable
```

Un vecteur à trois composantes.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Vector3(double x, double y, double z)](#Vector3-double-double-double-) | Initialise une nouvelle instance de la structure [Vector3](../../com.aspose.threed/vector3). |
| [Vector3(FVector3 vec)](#Vector3-com.aspose.threed.FVector3-) | Initialise une nouvelle instance de la structure [Vector3](../../com.aspose.threed/vector3). |
| [Vector3(double v)](#Vector3-double-) | Initialise une nouvelle instance de la structure [Vector3](../../com.aspose.threed/vector3). |
| [Vector3(Vector4 vec4)](#Vector3-com.aspose.threed.Vector4-) | Initialise une nouvelle instance de la structure [Vector3](../../com.aspose.threed/vector3). |
| [Vector3()](#Vector3--) |  |
## Champs

| Champ | Description |
| --- | --- |
| [x](#x) | Le composant x. |
| [y](#y) | Le composant y. |
| [z](#z) | Le composant z. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [add(Vector3 lhs, Vector3 rhs)](#add-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Surcharge d'opérateur pour + |
| [angleBetween(Vector3 dir)](#angleBetween-com.aspose.threed.Vector3-) | Calcule l'angle interne entre deux directions. Les deux directions peuvent être des vecteurs non normalisés. |
| [angleBetween(Vector3 dir, Vector3 up)](#angleBetween-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Calcule l'angle interne entre deux directions. Les deux directions peuvent être des vecteurs non normalisés. |
| [clone()](#clone--) |  |
| [compareTo(Vector3 other)](#compareTo-com.aspose.threed.Vector3-) | Compare le vecteur actuel à une autre instance. |
| [copyFrom(Vector3 src)](#copyFrom-com.aspose.threed.Vector3-) |  |
| [cos()](#cos--) | Calcule le cosinus sur chaque composant. |
| [create(Vector3 v)](#create-com.aspose.threed.Vector3-) | Opérateur de conversion explicite pour convertir Vector3 en FVector3. |
| [cross(Vector3 rhs)](#cross-com.aspose.threed.Vector3-) | Produit vectoriel de deux vecteurs. |
| [div(Vector3 lhs, Vector3 rhs)](#div-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Surcharge d'opérateur pour /. |
| [div(Vector3 lhs, double rhs)](#div-com.aspose.threed.Vector3-double-) | Surcharge d'opérateur pour /. |
| [dot(Vector3 rhs)](#dot-com.aspose.threed.Vector3-) | Obtient le produit scalaire de deux vecteurs. |
| [equals(Object obj)](#equals-java.lang.Object-) | Vérifie si deux vector3 sont égaux. |
| [get(int idx)](#get-int-) | Obtient le composant du vecteur par indice. |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Obtient la longueur de ce vecteur. |
| [getLength2()](#getLength2--) | Obtient le carré de la longueur. |
| [getOne()](#getOne--) | Obtient le vecteur unitaire (1, 1, 1). |
| [getUnitX()](#getUnitX--) | Obtient le vecteur unitaire (1, 0, 0). |
| [getUnitY()](#getUnitY--) | Obtient le vecteur unitaire (0, 1, 0). |
| [getUnitZ()](#getUnitZ--) | Obtient le vecteur unitaire (0, 0, 1). |
| [getZero()](#getZero--) | Obtient le vecteur unitaire (0, 0, 0). |
| [hashCode()](#hashCode--) | Obtient le code de hachage de Vector3. |
| [mul(Vector3 lhs, Vector3 rhs)](#mul-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Surcharge d'opérateur pour \* |
| [mul(Vector3 lhs, double rhs)](#mul-com.aspose.threed.Vector3-double-) | Surcharge d'opérateur pour \* |
| [mul(double lhs, Vector3 rhs)](#mul-double-com.aspose.threed.Vector3-) | Surcharge d'opérateur pour \* |
| [negative(Vector3 v)](#negative-com.aspose.threed.Vector3-) | Surcharge d'opérateur pour - |
| [normalize()](#normalize--) | Normalise cette instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(Vector3 lhs, Vector3 rhs)](#op-eq-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Opérateur d'égalité pour Vector3 |
| [op_ne(Vector3 lhs, Vector3 rhs)](#op-ne-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Opérateur de non-égalité pour Vector3 |
| [set(double newX, double newY, double newZ)](#set-double-double-double-) | Définit les composantes x/y/z en un seul appel. |
| [set(int idx, double value)](#set-int-double-) | Définit la composante du vecteur par indice. |
| [sin()](#sin--) | Calcule le sinus de chaque composante |
| [sub(Vector3 lhs, Vector3 rhs)](#sub-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Surcharge d'opérateur pour - (moins) |
| [toString()](#toString--) | Renvoie un java.lang.String qui représente le [Vector3](../../com.aspose.threed/vector3) actuel. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Vector3(double x, double y, double z) {#Vector3-double-double-double-}
```
public Vector3(double x, double y, double z)
```


Initialise une nouvelle instance de la structure [Vector3](../../com.aspose.threed/vector3).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | double | La coordonnée x. |
| y | double | La coordonnée y. |
| z | double | La coordonnée z. |

### Vector3(FVector3 vec) {#Vector3-com.aspose.threed.FVector3-}
```
public Vector3(FVector3 vec)
```


Initialise une nouvelle instance de la structure [Vector3](../../com.aspose.threed/vector3).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| vec | [FVector3](../../com.aspose.threed/fvector3) | La coordonnée x. |

### Vector3(double v) {#Vector3-double-}
```
public Vector3(double v)
```


Initialise une nouvelle instance de la structure [Vector3](../../com.aspose.threed/vector3).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| v | double | V. |

### Vector3(Vector4 vec4) {#Vector3-com.aspose.threed.Vector4-}
```
public Vector3(Vector4 vec4)
```


Initialise une nouvelle instance de la structure [Vector3](../../com.aspose.threed/vector3).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| vec4 | [Vector4](../../com.aspose.threed/vector4) | Vec4. |

### Vector3() {#Vector3--}
```
public Vector3()
```


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

### add(Vector3 lhs, Vector3 rhs) {#add-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 add(Vector3 lhs, Vector3 rhs)
```


Surcharge d'opérateur pour +

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Le vecteur gauche |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Le vecteur droit |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### angleBetween(Vector3 dir) {#angleBetween-com.aspose.threed.Vector3-}
```
public double angleBetween(Vector3 dir)
```


Calcule l'angle interne entre deux directions. Les deux directions peuvent être des vecteurs non normalisés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dir | [Vector3](../../com.aspose.threed/vector3) | Le vecteur direction à comparer avec |

**Returns:**
double - angle interne en radians
### angleBetween(Vector3 dir, Vector3 up) {#angleBetween-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public double angleBetween(Vector3 dir, Vector3 up)
```


Calcule l'angle interne entre deux directions. Les deux directions peuvent être des vecteurs non normalisés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dir | [Vector3](../../com.aspose.threed/vector3) | Le vecteur direction à comparer avec |
| up | [Vector3](../../com.aspose.threed/vector3) | Le vecteur haut du plan partagé par les deux directions |

**Returns:**
double - angle interne en radians
### clone() {#clone--}
```
public Vector3 clone()
```


Cloner l'instance actuelle

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### compareTo(Vector3 other) {#compareTo-com.aspose.threed.Vector3-}
```
public int compareTo(Vector3 other)
```


Compare le vecteur actuel à une autre instance.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| other | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
int
### copyFrom(Vector3 src) {#copyFrom-com.aspose.threed.Vector3-}
```
public void copyFrom(Vector3 src)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| src | [Vector3](../../com.aspose.threed/vector3) |  |

### cos() {#cos--}
```
public Vector3 cos()
```


Calcule le cosinus sur chaque composant.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Calculated [Vector3](../../com.aspose.threed/vector3).
### create(Vector3 v) {#create-com.aspose.threed.Vector3-}
```
public static FVector3 create(Vector3 v)
```


Opérateur de conversion explicite pour convertir Vector3 en FVector3.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### cross(Vector3 rhs) {#cross-com.aspose.threed.Vector3-}
```
public Vector3 cross(Vector3 rhs)
```


Produit vectoriel de deux vecteurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Valeur du côté droit. |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Cross product of two [Vector3](../../com.aspose.threed/vector3)s.
### div(Vector3 lhs, Vector3 rhs) {#div-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 div(Vector3 lhs, Vector3 rhs)
```


Surcharge d'opérateur pour /.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Le vecteur gauche |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Le vecteur droit |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### div(Vector3 lhs, double rhs) {#div-com.aspose.threed.Vector3-double-}
```
public static Vector3 div(Vector3 lhs, double rhs)
```


Surcharge d'opérateur pour /.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Le vecteur gauche |
| rhs | double | La valeur double de droite |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### dot(Vector3 rhs) {#dot-com.aspose.threed.Vector3-}
```
public double dot(Vector3 rhs)
```


Obtient le produit scalaire de deux vecteurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Valeur du côté droit. |

**Returns:**
double - Le produit scalaire des deux vecteurs.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Vérifie si deux vector3 sont égaux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | L'objet à vérifier l'égalité. |

**Returns:**
boolean - Vrai si tous les composants sont identiquement égaux.
### get(int idx) {#get-int-}
```
public double get(int idx)
```


Obtient le composant du vecteur par indice.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| idx | int |  |

**Returns:**
double - composante du vecteur par indice.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLength() {#getLength--}
```
public double getLength()
```


Obtient la longueur de ce vecteur.

**Returns:**
double - la longueur de ce vecteur.
### getLength2() {#getLength2--}
```
public double getLength2()
```


Obtient le carré de la longueur.

**Returns:**
double - le carré de la longueur.
### getOne() {#getOne--}
```
public static Vector3 getOne()
```


Obtient le vecteur unitaire (1, 1, 1).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (1, 1, 1)
### getUnitX() {#getUnitX--}
```
public static Vector3 getUnitX()
```


Obtient le vecteur unitaire (1, 0, 0).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (1, 0, 0)
### getUnitY() {#getUnitY--}
```
public static Vector3 getUnitY()
```


Obtient le vecteur unitaire (0, 1, 0).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (0, 1, 0)
### getUnitZ() {#getUnitZ--}
```
public static Vector3 getUnitZ()
```


Obtient le vecteur unitaire (0, 0, 1).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (0, 0, 1)
### getZero() {#getZero--}
```
public static Vector3 getZero()
```


Obtient le vecteur unitaire (0, 0, 0).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (0, 0, 0)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Obtient le code de hachage de Vector3.

**Returns:**
int - Le code de hachage du [Vector3](../../com.aspose.threed/vector3)
### mul(Vector3 lhs, Vector3 rhs) {#mul-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 mul(Vector3 lhs, Vector3 rhs)
```


Surcharge d'opérateur pour \*

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Le vecteur gauche |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Le vecteur droit |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### mul(Vector3 lhs, double rhs) {#mul-com.aspose.threed.Vector3-double-}
```
public static Vector3 mul(Vector3 lhs, double rhs)
```


Surcharge d'opérateur pour \*

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Le vecteur gauche |
| rhs | double | La valeur double de droite |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### mul(double lhs, Vector3 rhs) {#mul-double-com.aspose.threed.Vector3-}
```
public static Vector3 mul(double lhs, Vector3 rhs)
```


Surcharge d'opérateur pour \*

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| lhs | double | Le scalaire gauche |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Le vecteur droit |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### negative(Vector3 v) {#negative-com.aspose.threed.Vector3-}
```
public static Vector3 negative(Vector3 v)
```


Surcharge d'opérateur pour -

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) | Le vecteur d'origine |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### normalize() {#normalize--}
```
public Vector3 normalize()
```


Normalise cette instance.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Normalized vector.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_eq(Vector3 lhs, Vector3 rhs) {#op-eq-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static boolean op_eq(Vector3 lhs, Vector3 rhs)
```


Opérateur d'égalité pour Vector3

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Valeur du côté gauche. |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Valeur du côté droit. |

**Returns:**
boolean - Vrai si tous les composants sont identiquement égaux.
### op_ne(Vector3 lhs, Vector3 rhs) {#op-ne-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static boolean op_ne(Vector3 lhs, Vector3 rhs)
```


Opérateur de non-égalité pour Vector3

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Valeur du côté gauche. |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Valeur du côté droit. |

**Returns:**
boolean - Vrai si deux vecteurs ne sont pas égaux.
### set(double newX, double newY, double newZ) {#set-double-double-double-}
```
public void set(double newX, double newY, double newZ)
```


Définit les composantes x/y/z en un seul appel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newX | double | Le composant x. |
| newY | double | Le composant y. |
| newZ | double | Le composant z. |

### set(int idx, double value) {#set-int-double-}
```
public void set(int idx, double value)
```


Définit la composante du vecteur par indice.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| idx | int |  |
| valeur | double | Nouvelle valeur |

### sin() {#sin--}
```
public Vector3 sin()
```


Calcule le sinus de chaque composante

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Calculated [Vector3](../../com.aspose.threed/vector3).
### sub(Vector3 lhs, Vector3 rhs) {#sub-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 sub(Vector3 lhs, Vector3 rhs)
```


Surcharge d'opérateur pour - (moins)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Le vecteur gauche |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Le vecteur droit |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### toString() {#toString--}
```
public String toString()
```


Renvoie un java.lang.String qui représente le [Vector3](../../com.aspose.threed/vector3) actuel.

**Returns:**
java.lang.String - Un java.lang.String qui représente le [Vector3](../../com.aspose.threed/vector3) actuel.
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

