---
title: "FVector3"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Un vecteur flottant à trois composants."
type: docs
weight: 60
url: /fr/java/com.aspose.threed/fvector3/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class FVector3 implements Struct<FVector3>, Serializable
```

Un vecteur flottant à trois composants.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FVector3(float x, float y, float z)](#FVector3-float-float-float-) | Initialise une nouvelle instance de [FVector3](../../com.aspose.threed/fvector3). |
| [FVector3(Vector3 vec)](#FVector3-com.aspose.threed.Vector3-) | Initialise une nouvelle instance de [FVector3](../../com.aspose.threed/fvector3). |
| [FVector3(Vector4 vec)](#FVector3-com.aspose.threed.Vector4-) | Initialise une nouvelle instance de [FVector4](../../com.aspose.threed/fvector4). |
| [FVector3()](#FVector3--) |  |
## Champs

| Champ | Description |
| --- | --- |
| [x](#x) | Le composant x. |
| [y](#y) | Le composant y. |
| [z](#z) | Le composant y. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [add(FVector3 a, FVector3 b)](#add-com.aspose.threed.FVector3-com.aspose.threed.FVector3-) | \+ Surcharge d'opérateur |
| [clone()](#clone--) |  |
| [copyFrom(FVector3 src)](#copyFrom-com.aspose.threed.FVector3-) |  |
| [create(FVector3 v)](#create-com.aspose.threed.FVector3-) | Opérateur de conversion explicite pour convertir FVector3 en Vector3 |
| [cross(FVector3 rhs)](#cross-com.aspose.threed.FVector3-) | Produit vectoriel de deux vecteurs. |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOne()](#getOne--) | Le vecteur d'échelle unité avec tous les composants égaux à 1 |
| [getZero()](#getZero--) | Le vecteur zéro. |
| [hashCode()](#hashCode--) |  |
| [mul(FVector3 a, float b)](#mul-com.aspose.threed.FVector3-float-) | \* Surcharge d'opérateur |
| [negative(FVector3 a)](#negative-com.aspose.threed.FVector3-) | \- Surcharge d'opérateur |
| [normalize()](#normalize--) | Normalise cette instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [sub(FVector3 a, FVector3 b)](#sub-com.aspose.threed.FVector3-com.aspose.threed.FVector3-) | \- Surcharge d'opérateur |
| [toString()](#toString--) | Renvoie une chaîne qui représente le [FVector3](../../com.aspose.threed/fvector3) |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FVector3(float x, float y, float z) {#FVector3-float-float-float-}
```
public FVector3(float x, float y, float z)
```


Initialise une nouvelle instance de [FVector3](../../com.aspose.threed/fvector3).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | Composante X du vecteur |
| y | float | Composante Y du vecteur |
| z | float | Composante Z du vecteur |

### FVector3(Vector3 vec) {#FVector3-com.aspose.threed.Vector3-}
```
public FVector3(Vector3 vec)
```


Initialise une nouvelle instance de [FVector3](../../com.aspose.threed/fvector3).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) | Vector3 en type double |

### FVector3(Vector4 vec) {#FVector3-com.aspose.threed.Vector4-}
```
public FVector3(Vector4 vec)
```


Initialise une nouvelle instance de [FVector4](../../com.aspose.threed/fvector4).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| vec | [Vector4](../../com.aspose.threed/vector4) | Vector4 en type double |

### FVector3() {#FVector3--}
```
public FVector3()
```


### x {#x}
```
public float x
```


Le composant x.

### y {#y}
```
public float y
```


Le composant y.

### z {#z}
```
public float z
```


Le composant y.

### add(FVector3 a, FVector3 b) {#add-com.aspose.threed.FVector3-com.aspose.threed.FVector3-}
```
public static FVector3 add(FVector3 a, FVector3 b)
```


\+ Surcharge d'opérateur

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | Premier vecteur |
| b | [FVector3](../../com.aspose.threed/fvector3) | Deuxième vecteur |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### clone() {#clone--}
```
public FVector3 clone()
```


Cloner l'instance actuelle

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### copyFrom(FVector3 src) {#copyFrom-com.aspose.threed.FVector3-}
```
public void copyFrom(FVector3 src)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| src | [FVector3](../../com.aspose.threed/fvector3) |  |

### create(FVector3 v) {#create-com.aspose.threed.FVector3-}
```
public static Vector3 create(FVector3 v)
```


Opérateur de conversion explicite pour convertir FVector3 en Vector3

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| v | [FVector3](../../com.aspose.threed/fvector3) | Vector3 en type float |

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### cross(FVector3 rhs) {#cross-com.aspose.threed.FVector3-}
```
public FVector3 cross(FVector3 rhs)
```


Produit vectoriel de deux vecteurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rhs | [FVector3](../../com.aspose.threed/fvector3) | Valeur du côté droit. |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Cross product of two [FVector3](../../com.aspose.threed/fvector3)s.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




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
### getOne() {#getOne--}
```
public static FVector3 getOne()
```


Le vecteur d'échelle unité avec tous les composants égaux à 1

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The unit scale vector with all components are all 1
### getZero() {#getZero--}
```
public static FVector3 getZero()
```


Le vecteur zéro.

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The Zero vector.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### mul(FVector3 a, float b) {#mul-com.aspose.threed.FVector3-float-}
```
public static FVector3 mul(FVector3 a, float b)
```


\* Surcharge d'opérateur

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | Premier vecteur |
| b | float | Deuxième vecteur |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The product of two vectors
### negative(FVector3 a) {#negative-com.aspose.threed.FVector3-}
```
public static FVector3 negative(FVector3 a)
```


\- Surcharge d'opérateur

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | Vecteur d'entrée |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The negative vector
### normalize() {#normalize--}
```
public FVector3 normalize()
```


Normalise cette instance.

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Normalized vector.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### sub(FVector3 a, FVector3 b) {#sub-com.aspose.threed.FVector3-com.aspose.threed.FVector3-}
```
public static FVector3 sub(FVector3 a, FVector3 b)
```


\- Surcharge d'opérateur

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | Premier vecteur |
| b | [FVector3](../../com.aspose.threed/fvector3) | Deuxième vecteur |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The difference of two vectors
### toString() {#toString--}
```
public String toString()
```


Renvoie une chaîne qui représente le [FVector3](../../com.aspose.threed/fvector3)

**Returns:**
java.lang.String - Représentation sous forme de chaîne de ce vecteur.
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

