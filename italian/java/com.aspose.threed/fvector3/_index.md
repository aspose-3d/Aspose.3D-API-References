---
title: FVector3
second_title: Aspose.3D for Java API Reference
description: Un vettore float con tre componenti.
type: docs
weight: 60
url: /it/java/com.aspose.threed/fvector3/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class FVector3 implements Struct<FVector3>, Serializable
```

Un vettore float con tre componenti.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FVector3(float x, float y, float z)](#FVector3-float-float-float-) | Inizializza una nuova istanza di [FVector3](../../com.aspose.threed/fvector3). |
| [FVector3(Vector3 vec)](#FVector3-com.aspose.threed.Vector3-) | Inizializza una nuova istanza di [FVector3](../../com.aspose.threed/fvector3). |
| [FVector3(Vector4 vec)](#FVector3-com.aspose.threed.Vector4-) | Inizializza una nuova istanza di [FVector4](../../com.aspose.threed/fvector4). |
| [FVector3()](#FVector3--) |  |
## Campi

| Campo | Descrizione |
| --- | --- |
| [x](#x) | La componente x. |
| [y](#y) | La componente y. |
| [z](#z) | La componente y. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add(FVector3 a, FVector3 b)](#add-com.aspose.threed.FVector3-com.aspose.threed.FVector3-) | \+ Sovraccarico dell'operatore |
| [clone()](#clone--) |  |
| [copyFrom(FVector3 src)](#copyFrom-com.aspose.threed.FVector3-) |  |
| [create(FVector3 v)](#create-com.aspose.threed.FVector3-) | Operatore di conversione esplicita per castare FVector3 a Vector3 |
| [cross(FVector3 rhs)](#cross-com.aspose.threed.FVector3-) | Prodotto vettoriale di due vettori. |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOne()](#getOne--) | Il vettore di scala unitario con tutti i componenti uguali a 1 |
| [getZero()](#getZero--) | Il vettore Zero. |
| [hashCode()](#hashCode--) |  |
| [mul(FVector3 a, float b)](#mul-com.aspose.threed.FVector3-float-) | \* Overloading dell'operatore |
| [negative(FVector3 a)](#negative-com.aspose.threed.FVector3-) | \- Sovraccarico dell'operatore |
| [normalize()](#normalize--) | Normalizes this instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [sub(FVector3 a, FVector3 b)](#sub-com.aspose.threed.FVector3-com.aspose.threed.FVector3-) | \- Sovraccarico dell'operatore |
| [toString()](#toString--) | Restituisce una stringa che rappresenta [FVector3](../../com.aspose.threed/fvector3) |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FVector3(float x, float y, float z) {#FVector3-float-float-float-}
```
public FVector3(float x, float y, float z)
```


Inizializza una nuova istanza di [FVector3](../../com.aspose.threed/fvector3).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | Componente X del vettore |
| y | float | Componente Y del vettore |
| z | float | Componente Z del vettore |

### FVector3(Vector3 vec) {#FVector3-com.aspose.threed.Vector3-}
```
public FVector3(Vector3 vec)
```


Inizializza una nuova istanza di [FVector3](../../com.aspose.threed/fvector3).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) | Vector3 di tipo double |

### FVector3(Vector4 vec) {#FVector3-com.aspose.threed.Vector4-}
```
public FVector3(Vector4 vec)
```


Inizializza una nuova istanza di [FVector4](../../com.aspose.threed/fvector4).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vec | [Vector4](../../com.aspose.threed/vector4) | Vector4 di tipo double |

### FVector3() {#FVector3--}
```
public FVector3()
```


### x {#x}
```
public float x
```


La componente x.

### y {#y}
```
public float y
```


La componente y.

### z {#z}
```
public float z
```


La componente y.

### add(FVector3 a, FVector3 b) {#add-com.aspose.threed.FVector3-com.aspose.threed.FVector3-}
```
public static FVector3 add(FVector3 a, FVector3 b)
```


\+ Sovraccarico dell'operatore

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | Primo vettore |
| b | [FVector3](../../com.aspose.threed/fvector3) | Secondo vettore |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### clone() {#clone--}
```
public FVector3 clone()
```


Clone current instance

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### copyFrom(FVector3 src) {#copyFrom-com.aspose.threed.FVector3-}
```
public void copyFrom(FVector3 src)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| src | [FVector3](../../com.aspose.threed/fvector3) |  |

### create(FVector3 v) {#create-com.aspose.threed.FVector3-}
```
public static Vector3 create(FVector3 v)
```


Operatore di conversione esplicita per castare FVector3 a Vector3

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| v | [FVector3](../../com.aspose.threed/fvector3) | Vector3 di tipo float |

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### cross(FVector3 rhs) {#cross-com.aspose.threed.FVector3-}
```
public FVector3 cross(FVector3 rhs)
```


Prodotto vettoriale di due vettori.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rhs | [FVector3](../../com.aspose.threed/fvector3) | Valore del lato destro. |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Cross product of two [FVector3](../../com.aspose.threed/fvector3)s.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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


Il vettore di scala unitario con tutti i componenti uguali a 1

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The unit scale vector with all components are all 1
### getZero() {#getZero--}
```
public static FVector3 getZero()
```


Il vettore Zero.

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


\* Overloading dell'operatore

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | Primo vettore |
| b | float | Secondo vettore |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The product of two vectors
### negative(FVector3 a) {#negative-com.aspose.threed.FVector3-}
```
public static FVector3 negative(FVector3 a)
```


\- Sovraccarico dell'operatore

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | Vettore di input |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The negative vector
### normalize() {#normalize--}
```
public FVector3 normalize()
```


Normalizes this instance.

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


\- Sovraccarico dell'operatore

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | Primo vettore |
| b | [FVector3](../../com.aspose.threed/fvector3) | Secondo vettore |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The difference of two vectors
### toString() {#toString--}
```
public String toString()
```


Restituisce una stringa che rappresenta [FVector3](../../com.aspose.threed/fvector3)

**Returns:**
java.lang.String - Rappresentazione stringa di questo vettore.
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

