---
title: "FVector2"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Un vecteur flottant à deux composants."
type: docs
weight: 59
url: /fr/java/com.aspose.threed/fvector2/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class FVector2 implements Struct<FVector2>, Serializable
```

Un vecteur flottant à deux composants.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FVector2(float x, float y)](#FVector2-float-float-) | Initialise une nouvelle instance de [FVector2](../../com.aspose.threed/fvector2). |
| [FVector2(Vector2 vec)](#FVector2-com.aspose.threed.Vector2-) | Initialise une nouvelle instance de [FVector2](../../com.aspose.threed/fvector2). |
| [FVector2()](#FVector2--) |  |
## Champs

| Champ | Description |
| --- | --- |
| [x](#x) | Le composant x. |
| [y](#y) | Le composant y. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [add(FVector2 a, FVector2 b)](#add-com.aspose.threed.FVector2-com.aspose.threed.FVector2-) | \+ Surcharge d'opérateur |
| [clone()](#clone--) |  |
| [copyFrom(FVector2 src)](#copyFrom-com.aspose.threed.FVector2-) |  |
| [create(FVector2 v)](#create-com.aspose.threed.FVector2-) | Opérateur de conversion explicite pour convertir FVector2 en Vector2 |
| [equals(FVector2 rhs)](#equals-com.aspose.threed.FVector2-) | Vérifier si deux vecteurs sont égaux |
| [equals(Object obj)](#equals-java.lang.Object-) | Vérifier si deux vecteurs sont égaux |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | Obtient le code de hachage de cette instance |
| [mul(FVector2 a, float b)](#mul-com.aspose.threed.FVector2-float-) | \* surcharge d'opérateur |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(FVector2 a, FVector2 b)](#op-eq-com.aspose.threed.FVector2-com.aspose.threed.FVector2-) | == Surcharge d'opérateur |
| [op_ne(FVector2 a, FVector2 b)](#op-ne-com.aspose.threed.FVector2-com.aspose.threed.FVector2-) | != Surcharge d'opérateur |
| [sub(FVector2 a, FVector2 b)](#sub-com.aspose.threed.FVector2-com.aspose.threed.FVector2-) | \- Surcharge d'opérateur |
| [toString()](#toString--) | Renvoie une chaîne qui représente le [FVector2](../../com.aspose.threed/fvector2) |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FVector2(float x, float y) {#FVector2-float-float-}
```
public FVector2(float x, float y)
```


Initialise une nouvelle instance de [FVector2](../../com.aspose.threed/fvector2).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | Composante X du vecteur |
| y | float | Composante Y du vecteur |

### FVector2(Vector2 vec) {#FVector2-com.aspose.threed.Vector2-}
```
public FVector2(Vector2 vec)
```


Initialise une nouvelle instance de [FVector2](../../com.aspose.threed/fvector2).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| vec | [Vector2](../../com.aspose.threed/vector2) | Vector2 de type double |

### FVector2() {#FVector2--}
```
public FVector2()
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

### add(FVector2 a, FVector2 b) {#add-com.aspose.threed.FVector2-com.aspose.threed.FVector2-}
```
public static FVector2 add(FVector2 a, FVector2 b)
```


\+ Surcharge d'opérateur

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | Premier vecteur |
| b | [FVector2](../../com.aspose.threed/fvector2) | Deuxième vecteur |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - The sum of two vectors.
### clone() {#clone--}
```
public FVector2 clone()
```


Cloner l'instance actuelle

**Returns:**
[FVector2](../../com.aspose.threed/fvector2)
### copyFrom(FVector2 src) {#copyFrom-com.aspose.threed.FVector2-}
```
public void copyFrom(FVector2 src)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| src | [FVector2](../../com.aspose.threed/fvector2) |  |

### create(FVector2 v) {#create-com.aspose.threed.FVector2-}
```
public static Vector2 create(FVector2 v)
```


Opérateur de conversion explicite pour convertir FVector2 en Vector2

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| v | [FVector2](../../com.aspose.threed/fvector2) | Vector 2 de type float. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2)
### equals(FVector2 rhs) {#equals-com.aspose.threed.FVector2-}
```
public boolean equals(FVector2 rhs)
```


Vérifier si deux vecteurs sont égaux

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rhs | [FVector2](../../com.aspose.threed/fvector2) |  |

**Returns:**
booléen - Vrai si toutes les composantes sont égales.
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
booléen - Vrai si l'entrée est un vecteur et que toutes les composantes sont égales.
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


Obtient le code de hachage de cette instance

**Returns:**
int - Le code de hachage du vecteur.
### mul(FVector2 a, float b) {#mul-com.aspose.threed.FVector2-float-}
```
public static FVector2 mul(FVector2 a, float b)
```


\* surcharge d'opérateur

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | Premier vecteur |
| b | float | Deuxième vecteur |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - The product of two vectors.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_eq(FVector2 a, FVector2 b) {#op-eq-com.aspose.threed.FVector2-com.aspose.threed.FVector2-}
```
public static boolean op_eq(FVector2 a, FVector2 b)
```


== Surcharge d'opérateur

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | Premier vecteur |
| b | [FVector2](../../com.aspose.threed/fvector2) | Deuxième vecteur |

**Returns:**
booléen - Vrai si toutes les composantes sont égales.
### op_ne(FVector2 a, FVector2 b) {#op-ne-com.aspose.threed.FVector2-com.aspose.threed.FVector2-}
```
public static boolean op_ne(FVector2 a, FVector2 b)
```


!= Operator overloading

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | Premier vecteur |
| b | [FVector2](../../com.aspose.threed/fvector2) | Deuxième vecteur |

**Returns:**
booléen - Vrai si une composante est différente.
### sub(FVector2 a, FVector2 b) {#sub-com.aspose.threed.FVector2-com.aspose.threed.FVector2-}
```
public static FVector2 sub(FVector2 a, FVector2 b)
```


\- Surcharge d'opérateur

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | Premier vecteur |
| b | [FVector2](../../com.aspose.threed/fvector2) | Deuxième vecteur |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - The difference of two vectors.
### toString() {#toString--}
```
public String toString()
```


Renvoie une chaîne qui représente le [FVector2](../../com.aspose.threed/fvector2)

**Returns:**
java.lang.String - Représentation sous forme de chaîne du vecteur actuel.
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

