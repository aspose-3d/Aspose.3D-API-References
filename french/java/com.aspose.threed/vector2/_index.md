---
title: "Vector2"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Un vecteur à deux composantes."
type: docs
weight: 201
url: /fr/java/com.aspose.threed/vector2/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.threed.Struct, java.io.Serializable
```
public final class Vector2 implements Comparable<Vector2>, Struct<Vector2>, Serializable
```

Un vecteur à deux composantes.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Vector2(double s)](#Vector2-double-) | Initialise une nouvelle instance de la structure [Vector2](../../com.aspose.threed/vector2). |
| [Vector2(Vector3 s)](#Vector2-com.aspose.threed.Vector3-) | Initialise une nouvelle instance de la structure [Vector2](../../com.aspose.threed/vector2). |
| [Vector2(FVector2 vec)](#Vector2-com.aspose.threed.FVector2-) | Initialise une nouvelle instance de la structure [Vector2](../../com.aspose.threed/vector2). |
| [Vector2(double x, double y)](#Vector2-double-double-) | Initialise une nouvelle instance de la structure [Vector2](../../com.aspose.threed/vector2). |
| [Vector2()](#Vector2--) |  |
## Champs

| Champ | Description |
| --- | --- |
| [x](#x) | Le composant x. |
| [y](#y) | Le composant y. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [add(Vector2 lhs, Vector2 rhs)](#add-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Opérateur d'addition pour Vector2 |
| [clone()](#clone--) |  |
| [compareTo(Vector2 other)](#compareTo-com.aspose.threed.Vector2-) | Compare le vecteur actuel à une autre instance. |
| [copyFrom(Vector2 src)](#copyFrom-com.aspose.threed.Vector2-) |  |
| [create(Vector2 v)](#create-com.aspose.threed.Vector2-) | Opérateur de conversion explicite pour convertir Vector2 en FVector2 |
| [cross(Vector2 v)](#cross-com.aspose.threed.Vector2-) | Produit vectoriel de deux vecteurs. |
| [div(Vector2 lhs, double rhs)](#div-com.aspose.threed.Vector2-double-) | Opérateur de division pour Vector2 |
| [dot(Vector2 rhs)](#dot-com.aspose.threed.Vector2-) | Obtient le produit scalaire de deux vecteurs. |
| [equals(Vector2 rhs)](#equals-com.aspose.threed.Vector2-) | Vérifier si deux vector2 sont égaux |
| [equals(Object obj)](#equals-java.lang.Object-) | Vérifier si deux vector2 sont égaux |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Obtient la longueur. |
| [getU()](#getU--) | Obtient le composant U si le [Vector2](../../com.aspose.threed/vector2) est utilisé comme coordonnée de mappage. |
| [getV()](#getV--) | Obtient le composant V si le [Vector2](../../com.aspose.threed/vector2) est utilisé comme coordonnée de mappage. |
| [hashCode()](#hashCode--) | Obtient le code de hachage de Vector2 |
| [mul(Vector2 lhs, double rhs)](#mul-com.aspose.threed.Vector2-double-) | Opérateur de multiplication pour Vector2 |
| [mul(double lhs, Vector2 rhs)](#mul-double-com.aspose.threed.Vector2-) | Opérateur de multiplication pour Vector2 |
| [normalize()](#normalize--) | Normalise cette instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(Vector2 lhs, Vector2 rhs)](#op-eq-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Opérateur d'égalité pour Vector2 |
| [op_ne(Vector2 lhs, Vector2 rhs)](#op-ne-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Opérateur de non-égalité pour Vector2 |
| [setU(double value)](#setU-double-) | Définit le composant U si le [Vector2](../../com.aspose.threed/vector2) est utilisé comme coordonnée de mappage. |
| [setV(double value)](#setV-double-) | Définit le composant V si le [Vector2](../../com.aspose.threed/vector2) est utilisé comme coordonnée de mappage. |
| [sub(Vector2 lhs, Vector2 rhs)](#sub-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Opérateur de soustraction pour Vector2 |
| [toString()](#toString--) | Renvoie un java.lang.String qui représente le [Vector2](../../com.aspose.threed/vector2) actuel. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Vector2(double s) {#Vector2-double-}
```
public Vector2(double s)
```


Initialise une nouvelle instance de la structure [Vector2](../../com.aspose.threed/vector2).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| s | double | S. |

### Vector2(Vector3 s) {#Vector2-com.aspose.threed.Vector3-}
```
public Vector2(Vector3 s)
```


Initialise une nouvelle instance de la structure [Vector2](../../com.aspose.threed/vector2).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| s | [Vector3](../../com.aspose.threed/vector3) | S. |

### Vector2(FVector2 vec) {#Vector2-com.aspose.threed.FVector2-}
```
public Vector2(FVector2 vec)
```


Initialise une nouvelle instance de la structure [Vector2](../../com.aspose.threed/vector2).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| vec | [FVector2](../../com.aspose.threed/fvector2) | Vecteur en float. |

### Vector2(double x, double y) {#Vector2-double-double-}
```
public Vector2(double x, double y)
```


Initialise une nouvelle instance de la structure [Vector2](../../com.aspose.threed/vector2).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | double | La coordonnée x. |
| y | double | La coordonnée y. |

### Vector2() {#Vector2--}
```
public Vector2()
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

### add(Vector2 lhs, Vector2 rhs) {#add-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static Vector2 add(Vector2 lhs, Vector2 rhs)
```


Opérateur d'addition pour Vector2

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Valeur du côté gauche. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Valeur du côté droit. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of addition.
### clone() {#clone--}
```
public Vector2 clone()
```


Cloner l'instance actuelle

**Returns:**
[Vector2](../../com.aspose.threed/vector2)
### compareTo(Vector2 other) {#compareTo-com.aspose.threed.Vector2-}
```
public int compareTo(Vector2 other)
```


Compare le vecteur actuel à une autre instance.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| other | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
int
### copyFrom(Vector2 src) {#copyFrom-com.aspose.threed.Vector2-}
```
public void copyFrom(Vector2 src)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| src | [Vector2](../../com.aspose.threed/vector2) |  |

### create(Vector2 v) {#create-com.aspose.threed.Vector2-}
```
public static FVector2 create(Vector2 v)
```


Opérateur de conversion explicite pour convertir Vector2 en FVector2

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| v | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2)
### cross(Vector2 v) {#cross-com.aspose.threed.Vector2-}
```
public double cross(Vector2 v)
```


Produit vectoriel de deux vecteurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| v | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
double
### div(Vector2 lhs, double rhs) {#div-com.aspose.threed.Vector2-double-}
```
public static Vector2 div(Vector2 lhs, double rhs)
```


Opérateur de division pour Vector2

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Valeur du côté gauche. |
| rhs | double | Valeur du côté droit. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of division.
### dot(Vector2 rhs) {#dot-com.aspose.threed.Vector2-}
```
public double dot(Vector2 rhs)
```


Obtient le produit scalaire de deux vecteurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Valeur du côté droit. |

**Returns:**
double - Le produit scalaire des deux vecteurs.
### equals(Vector2 rhs) {#equals-com.aspose.threed.Vector2-}
```
public boolean equals(Vector2 rhs)
```


Vérifier si deux vector2 sont égaux

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rhs | [Vector2](../../com.aspose.threed/vector2) | La valeur du côté droit. |

**Returns:**
boolean - Vrai si tous les composants sont identiquement égaux.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Vérifier si deux vector2 sont égaux

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | L'objet à comparer. |

**Returns:**
boolean - Vrai si tous les composants sont identiquement égaux.
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


Obtient la longueur.

**Returns:**
double - la longueur.
### getU() {#getU--}
```
public double getU()
```


Obtient le composant U si le [Vector2](../../com.aspose.threed/vector2) est utilisé comme coordonnée de mappage. C'est un alias du composant x.

**Returns:**
double - le composant U si le [Vector2](../../com.aspose.threed/vector2) est utilisé comme coordonnée de mappage. C'est un alias du composant x.
### getV() {#getV--}
```
public double getV()
```


Obtient le composant V si le [Vector2](../../com.aspose.threed/vector2) est utilisé comme coordonnée de mappage. C'est un alias du composant y.

**Returns:**
double - le composant V si le [Vector2](../../com.aspose.threed/vector2) est utilisé comme coordonnée de mappage. C'est un alias du composant y.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Obtient le code de hachage de Vector2

**Returns:**
int - Le code de hachage du [Vector2](../../com.aspose.threed/vector2)
### mul(Vector2 lhs, double rhs) {#mul-com.aspose.threed.Vector2-double-}
```
public static Vector2 mul(Vector2 lhs, double rhs)
```


Opérateur de multiplication pour Vector2

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Valeur du côté gauche. |
| rhs | double | Valeur du côté droit. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of multiply.
### mul(double lhs, Vector2 rhs) {#mul-double-com.aspose.threed.Vector2-}
```
public static Vector2 mul(double lhs, Vector2 rhs)
```


Opérateur de multiplication pour Vector2

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| lhs | double | Valeur du côté gauche. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Valeur du côté droit. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of multiply.
### normalize() {#normalize--}
```
public Vector2 normalize()
```


Normalise cette instance.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - Normalized vector.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_eq(Vector2 lhs, Vector2 rhs) {#op-eq-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static boolean op_eq(Vector2 lhs, Vector2 rhs)
```


Opérateur d'égalité pour Vector2

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Valeur du côté gauche. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Valeur du côté droit. |

**Returns:**
boolean - Vrai si tous les composants sont identiquement égaux.
### op_ne(Vector2 lhs, Vector2 rhs) {#op-ne-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static boolean op_ne(Vector2 lhs, Vector2 rhs)
```


Opérateur de non-égalité pour Vector2

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Valeur du côté gauche. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Valeur du côté droit. |

**Returns:**
boolean - Vrai si deux vecteurs ne sont pas égaux.
### setU(double value) {#setU-double-}
```
public void setU(double value)
```


Définit le composant U si le [Vector2](../../com.aspose.threed/vector2) est utilisé comme coordonnée de mappage. C'est un alias du composant x.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

### setV(double value) {#setV-double-}
```
public void setV(double value)
```


Définit le composant V si le [Vector2](../../com.aspose.threed/vector2) est utilisé comme coordonnée de mappage. C'est un alias du composant y.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

### sub(Vector2 lhs, Vector2 rhs) {#sub-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static Vector2 sub(Vector2 lhs, Vector2 rhs)
```


Opérateur de soustraction pour Vector2

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Valeur du côté gauche. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Valeur du côté droit. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of substraction.
### toString() {#toString--}
```
public String toString()
```


Renvoie un java.lang.String qui représente le [Vector2](../../com.aspose.threed/vector2) actuel.

**Returns:**
java.lang.String - Un java.lang.String qui représente le [Vector2](../../com.aspose.threed/vector2) actuel.
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

