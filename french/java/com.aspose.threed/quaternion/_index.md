---
title: "Quaternion"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Le quaternion est généralement utilisé pour effectuer des rotations en infographie."
type: docs
weight: 143
url: /fr/java/com.aspose.threed/quaternion/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class Quaternion implements Struct<Quaternion>, Serializable
```

Le quaternion est généralement utilisé pour effectuer des rotations en infographie.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Quaternion(double w, double x, double y, double z)](#Quaternion-double-double-double-double-) | Initialise une nouvelle instance de la classe [Quaternion](../../com.aspose.threed/quaternion). |
| [Quaternion()](#Quaternion--) |  |
## Champs

| Champ | Description |
| --- | --- |
| [IDENTITY](#IDENTITY) | Le quaternion d'identité. |
| [w](#w) | Le composant w. |
| [x](#x) | Le composant x. |
| [y](#y) | Le composant y. |
| [z](#z) | Le composant z. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [add(Quaternion lhs, Quaternion rhs)](#add-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Surcharge d'opérateur pour + |
| [clone()](#clone--) |  |
| [concat(Quaternion rhs)](#concat-com.aspose.threed.Quaternion-) | Concaténer deux quaternions |
| [conjugate()](#conjugate--) | Renvoie un quaternion conjugué du quaternion actuel |
| [copyFrom(Quaternion src)](#copyFrom-com.aspose.threed.Quaternion-) |  |
| [div(Quaternion lhs, double rhs)](#div-com.aspose.threed.Quaternion-double-) | Surcharge d'opérateur pour /. |
| [dot(Quaternion q)](#dot-com.aspose.threed.Quaternion-) | Produit scalaire |
| [equals(Object obj)](#equals-java.lang.Object-) | Vérifier si deux quaternions sont égaux |
| [eulerAngles()](#eulerAngles--) | Convertit le quaternion en rotation représentée par des angles d'Euler. Tous les composants sont en radians. |
| [fromAngleAxis(double a, Vector3 axis)](#fromAngleAxis-double-com.aspose.threed.Vector3-) | Crée un quaternion autour d'un axe donné et le fait pivoter dans le sens horaire |
| [fromEulerAngle(Vector3 eulerAngle)](#fromEulerAngle-com.aspose.threed.Vector3-) | Crée un quaternion à partir d'un angle d'Euler donné |
| [fromEulerAngle(double pitch, double yaw, double roll)](#fromEulerAngle-double-double-double-) | Crée un quaternion à partir d'un angle d'Euler donné |
| [fromRotation(Vector3 orig, Vector3 dest)](#fromRotation-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Crée un quaternion qui tourne de la direction originale à la direction de destination |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Obtient la longueur du quaternion |
| [hashCode()](#hashCode--) | Obtient le code de hachage du Quaternion |
| [interpolate(float t, Quaternion from, Quaternion to)](#interpolate-float-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Remplit ce quaternion avec la valeur interpolée entre les arguments quaternion fournis pour un t compris entre le point de départ et le point d'arrivée. |
| [inverse()](#inverse--) | Renvoie un quaternion inverse du quaternion actuel |
| [mul(Quaternion lhs, Quaternion rhs)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Surcharge d'opérateur pour \* |
| [mul(Quaternion q, Vector3 v)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector3-) | Surcharge d'opérateur pour \* |
| [mul(Quaternion q, Vector4 v)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector4-) | Surcharge d'opérateur pour \* |
| [mul(Quaternion lhs, double rhs)](#mul-com.aspose.threed.Quaternion-double-) | Surcharge d'opérateur pour \* |
| [mul(Vector3 v, Quaternion q)](#mul-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-) | Surcharge d'opérateur pour \* |
| [normalize()](#normalize--) | Normaliser le quaternion |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(Quaternion lhs, Quaternion rhs)](#op-eq-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Opérateur d'égalité pour le quaternion |
| [op_ne(Quaternion lhs, Quaternion rhs)](#op-ne-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Opérateur de différence pour le quaternion |
| [slerp(double t, Quaternion v1, Quaternion v2)](#slerp-double-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Effectuer une interpolation sphérique linéaire entre deux valeurs |
| [toAngleAxis(double[] angle, Vector3 axis)](#toAngleAxis-double---com.aspose.threed.Vector3-) | Décomposer le quaternion en angle et axe |
| [toMatrix()](#toMatrix--) | Convertir la rotation présentée par le quaternion en matrice de transformation. |
| [toMatrix(Vector3 translation)](#toMatrix-com.aspose.threed.Vector3-) | Convertir la rotation présentée par le quaternion en matrice de transformation. |
| [toString()](#toString--) | Obtient la représentation du quaternion sous forme de chaîne |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Quaternion(double w, double x, double y, double z) {#Quaternion-double-double-double-double-}
```
public Quaternion(double w, double x, double y, double z)
```


Initialise une nouvelle instance de la classe [Quaternion](../../com.aspose.threed/quaternion).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| w | double | composante w du quaternion |
| x | double | composante x du quaternion |
| y | double | composante y du quaternion |
| z | double | composante z du quaternion |

### Quaternion() {#Quaternion--}
```
public Quaternion()
```


### IDENTITY {#IDENTITY}
```
public static final Quaternion IDENTITY
```


Le quaternion d'identité.

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

### add(Quaternion lhs, Quaternion rhs) {#add-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion add(Quaternion lhs, Quaternion rhs)
```


Surcharge d'opérateur pour +

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Quaternion gauche |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Quaternion droit |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### clone() {#clone--}
```
public Quaternion clone()
```


Cloner l'instance actuelle

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### concat(Quaternion rhs) {#concat-com.aspose.threed.Quaternion-}
```
public Quaternion concat(Quaternion rhs)
```


Concaténer deux quaternions

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) |  |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### conjugate() {#conjugate--}
```
public Quaternion conjugate()
```


Renvoie un quaternion conjugué du quaternion actuel

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - The conjugate quaternion.
### copyFrom(Quaternion src) {#copyFrom-com.aspose.threed.Quaternion-}
```
public void copyFrom(Quaternion src)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| src | [Quaternion](../../com.aspose.threed/quaternion) |  |

### div(Quaternion lhs, double rhs) {#div-com.aspose.threed.Quaternion-double-}
```
public static Quaternion div(Quaternion lhs, double rhs)
```


Surcharge d'opérateur pour /.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Quaternion gauche |
| rhs | double | Quaternion droit |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### dot(Quaternion q) {#dot-com.aspose.threed.Quaternion-}
```
public double dot(Quaternion q)
```


Produit scalaire

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | Le quaternion |

**Returns:**
double - Valeur du produit scalaire
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Vérifier si deux quaternions sont égaux

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | L'objet à vérifier l'égalité. |

**Returns:**
boolean - Vrai si tous les composants sont identiquement égaux.
### eulerAngles() {#eulerAngles--}
```
public Vector3 eulerAngles()
```


Convertit le quaternion en rotation représentée par des angles d'Euler. Tous les composants sont en radians.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### fromAngleAxis(double a, Vector3 axis) {#fromAngleAxis-double-com.aspose.threed.Vector3-}
```
public static Quaternion fromAngleAxis(double a, Vector3 axis)
```


Crée un quaternion autour d'un axe donné et le fait pivoter dans le sens horaire

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | double | Rotation horaire en radian |
| axis | [Vector3](../../com.aspose.threed/vector3) | Axe |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromEulerAngle(Vector3 eulerAngle) {#fromEulerAngle-com.aspose.threed.Vector3-}
```
public static Quaternion fromEulerAngle(Vector3 eulerAngle)
```


Crée un quaternion à partir d'un angle d'Euler donné

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| eulerAngle | [Vector3](../../com.aspose.threed/vector3) | Angle d'Euler en radian |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromEulerAngle(double pitch, double yaw, double roll) {#fromEulerAngle-double-double-double-}
```
public static Quaternion fromEulerAngle(double pitch, double yaw, double roll)
```


Crée un quaternion à partir d'un angle d'Euler donné

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tangage | double | Tangage en radian |
| lacet | double | Lacet en radian |
| roulis | double | Roulis en radian |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromRotation(Vector3 orig, Vector3 dest) {#fromRotation-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Quaternion fromRotation(Vector3 orig, Vector3 dest)
```


Crée un quaternion qui tourne de la direction originale à la direction de destination

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| orig | [Vector3](../../com.aspose.threed/vector3) | Direction d'origine |
| dest | [Vector3](../../com.aspose.threed/vector3) | Direction de destination |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
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


Obtient la longueur du quaternion

**Returns:**
double - la longueur du quaternion
### hashCode() {#hashCode--}
```
public int hashCode()
```


Obtient le code de hachage du Quaternion

**Returns:**
int - Le code de hachage du [Quaternion](../../com.aspose.threed/quaternion)
### interpolate(float t, Quaternion from, Quaternion to) {#interpolate-float-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion interpolate(float t, Quaternion from, Quaternion to)
```


Remplit ce quaternion avec la valeur interpolée entre les arguments quaternion fournis pour un t compris entre le point de départ et le point d'arrivée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| t | float | Le coefficient à interpoler. |
| from | [Quaternion](../../com.aspose.threed/quaternion) | Quaternion source. |
| to | [Quaternion](../../com.aspose.threed/quaternion) | Quaternion cible. |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - The interpolated quaternion.
### inverse() {#inverse--}
```
public Quaternion inverse()
```


Renvoie un quaternion inverse du quaternion actuel

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Inverse quaternion.
### mul(Quaternion lhs, Quaternion rhs) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion mul(Quaternion lhs, Quaternion rhs)
```


Surcharge d'opérateur pour \*

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Quaternion gauche |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Quaternion droit |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### mul(Quaternion q, Vector3 v) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector3-}
```
public static Vector3 mul(Quaternion q, Vector3 v)
```


Surcharge d'opérateur pour \*

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | Le quaternion de rotation |
| v | [Vector3](../../com.aspose.threed/vector3) | Vecteur à faire pivoter |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Rotated vector
### mul(Quaternion q, Vector4 v) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector4-}
```
public static Vector4 mul(Quaternion q, Vector4 v)
```


Surcharge d'opérateur pour \*

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | Le quaternion de rotation |
| v | [Vector4](../../com.aspose.threed/vector4) | Vecteur à faire pivoter |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Rotated vector
### mul(Quaternion lhs, double rhs) {#mul-com.aspose.threed.Quaternion-double-}
```
public static Quaternion mul(Quaternion lhs, double rhs)
```


Surcharge d'opérateur pour \*

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Quaternion gauche |
| rhs | double | Quaternion droit |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### mul(Vector3 v, Quaternion q) {#mul-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-}
```
public static Vector3 mul(Vector3 v, Quaternion q)
```


Surcharge d'opérateur pour \*

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) | Le quaternion de rotation |
| q | [Quaternion](../../com.aspose.threed/quaternion) | Vecteur à faire pivoter |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Rotated vector
### normalize() {#normalize--}
```
public Quaternion normalize()
```


Normaliser le quaternion

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Normalized quaternion.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_eq(Quaternion lhs, Quaternion rhs) {#op-eq-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static boolean op_eq(Quaternion lhs, Quaternion rhs)
```


Opérateur d'égalité pour le quaternion

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Valeur du côté gauche. |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Valeur du côté droit. |

**Returns:**
boolean - Vrai si tous les composants sont identiquement égaux.
### op_ne(Quaternion lhs, Quaternion rhs) {#op-ne-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static boolean op_ne(Quaternion lhs, Quaternion rhs)
```


Opérateur de différence pour le quaternion

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Valeur du côté gauche. |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Valeur du côté droit. |

**Returns:**
boolean - Vrai si deux quaternions ne sont pas égaux.
### slerp(double t, Quaternion v1, Quaternion v2) {#slerp-double-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion slerp(double t, Quaternion v1, Quaternion v2)
```


Effectuer une interpolation sphérique linéaire entre deux valeurs

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| t | double | t est compris entre 0 et 1 |
| v1 | [Quaternion](../../com.aspose.threed/quaternion) | Première valeur |
| v2 | [Quaternion](../../com.aspose.threed/quaternion) | Deuxième valeur |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### toAngleAxis(double[] angle, Vector3 axis) {#toAngleAxis-double---com.aspose.threed.Vector3-}
```
public void toAngleAxis(double[] angle, Vector3 axis)
```


Décomposer le quaternion en angle et axe

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | double[] | L'angle à faire pivoter, en radian. |
| axis | [Vector3](../../com.aspose.threed/vector3) | L'axe autour duquel la rotation s'effectue. |

### toMatrix() {#toMatrix--}
```
public Matrix4 toMatrix()
```


Convertir la rotation présentée par le quaternion en matrice de transformation.

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - The matrix representation of current quaternion.
### toMatrix(Vector3 translation) {#toMatrix-com.aspose.threed.Vector3-}
```
public Matrix4 toMatrix(Vector3 translation)
```


Convertir la rotation présentée par le quaternion en matrice de transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| translation | [Vector3](../../com.aspose.threed/vector3) | La partie translation de la matrice. |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - The matrix representation of current quaternion.
### toString() {#toString--}
```
public String toString()
```


Obtient la représentation du quaternion sous forme de chaîne

**Returns:**
java.lang.String - Chaîne d'objet
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

