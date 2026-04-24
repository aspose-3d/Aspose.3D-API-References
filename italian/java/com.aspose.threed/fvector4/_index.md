---
title: FVector4
second_title: Aspose.3D for Java API Reference
description: Un vettore float con quattro componenti.
type: docs
weight: 61
url: /it/java/com.aspose.threed/fvector4/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class FVector4 implements Struct<FVector4>, Serializable
```

Un vettore float con quattro componenti.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FVector4(float x, float y, float z, float w)](#FVector4-float-float-float-float-) | Inizializza una nuova istanza di [FVector4](../../com.aspose.threed/fvector4). |
| [FVector4(float x, float y, float z)](#FVector4-float-float-float-) | Inizializza una nuova istanza di [FVector4](../../com.aspose.threed/fvector4). |
| [FVector4(Color color)](#FVector4-java.awt.Color-) | Inizializza una nuova istanza di [FVector4](../../com.aspose.threed/fvector4). |
| [FVector4(Vector4 vec)](#FVector4-com.aspose.threed.Vector4-) | Inizializza una nuova istanza di [FVector4](../../com.aspose.threed/fvector4). |
| [FVector4(Vector3 vec)](#FVector4-com.aspose.threed.Vector3-) | Inizializza una nuova istanza di [FVector4](../../com.aspose.threed/fvector4). |
| [FVector4(Vector3 vec, float w)](#FVector4-com.aspose.threed.Vector3-float-) | Inizializza una nuova istanza di [FVector4](../../com.aspose.threed/fvector4). |
| [FVector4()](#FVector4--) |  |
## Campi

| Campo | Descrizione |
| --- | --- |
| [w](#w) | Il componente w. |
| [x](#x) | La componente x. |
| [y](#y) | La componente y. |
| [z](#z) | La componente z. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add(FVector4 lhs, FVector4 rhs)](#add-com.aspose.threed.FVector4-com.aspose.threed.FVector4-) | Sovraccarico dell'operatore per + |
| [clone()](#clone--) |  |
| [copyFrom(FVector4 src)](#copyFrom-com.aspose.threed.FVector4-) |  |
| [create(FVector4 v)](#create-com.aspose.threed.FVector4-) | Operatore di conversione esplicita per castare Vector4 a FVector4 |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [mul(FVector4 lhs, FVector4 rhs)](#mul-com.aspose.threed.FVector4-com.aspose.threed.FVector4-) | Sovraccarico dell'operatore per \* |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [sub(FVector4 lhs, FVector4 rhs)](#sub-com.aspose.threed.FVector4-com.aspose.threed.FVector4-) | Operator overloading for - (minus) |
| [toString()](#toString--) | Restituisce una stringa che rappresenta il [FVector4](../../com.aspose.threed/fvector4) |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FVector4(float x, float y, float z, float w) {#FVector4-float-float-float-float-}
```
public FVector4(float x, float y, float z, float w)
```


Inizializza una nuova istanza di [FVector4](../../com.aspose.threed/fvector4).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | Componente X |
| y | float | Componente Y |
| z | float | Componente Z |
| w | float | Componente W |

### FVector4(float x, float y, float z) {#FVector4-float-float-float-}
```
public FVector4(float x, float y, float z)
```


Inizializza una nuova istanza di [FVector4](../../com.aspose.threed/fvector4).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | Componente X |
| y | float | Componente Y |
| z | float | Componente Z |

### FVector4(Color color) {#FVector4-java.awt.Color-}
```
public FVector4(Color color)
```


Inizializza una nuova istanza di [FVector4](../../com.aspose.threed/fvector4).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| colore | java.awt.Color |  |

### FVector4(Vector4 vec) {#FVector4-com.aspose.threed.Vector4-}
```
public FVector4(Vector4 vec)
```


Inizializza una nuova istanza di [FVector4](../../com.aspose.threed/fvector4).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vec | [Vector4](../../com.aspose.threed/vector4) |  |

### FVector4(Vector3 vec) {#FVector4-com.aspose.threed.Vector3-}
```
public FVector4(Vector3 vec)
```


Inizializza una nuova istanza di [FVector4](../../com.aspose.threed/fvector4).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) |  |

### FVector4(Vector3 vec, float w) {#FVector4-com.aspose.threed.Vector3-float-}
```
public FVector4(Vector3 vec, float w)
```


Inizializza una nuova istanza di [FVector4](../../com.aspose.threed/fvector4).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) |  |
| w | float |  |

### FVector4() {#FVector4--}
```
public FVector4()
```


### w {#w}
```
public float w
```


Il componente w.

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


La componente z.

### add(FVector4 lhs, FVector4 rhs) {#add-com.aspose.threed.FVector4-com.aspose.threed.FVector4-}
```
public static FVector4 add(FVector4 lhs, FVector4 rhs)
```


Sovraccarico dell'operatore per +

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs | [FVector4](../../com.aspose.threed/fvector4) | The left vector |
| rhs | [FVector4](../../com.aspose.threed/fvector4) | The right vector |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4) - Result vector
### clone() {#clone--}
```
public FVector4 clone()
```


Clone current instance

**Returns:**
[FVector4](../../com.aspose.threed/fvector4)
### copyFrom(FVector4 src) {#copyFrom-com.aspose.threed.FVector4-}
```
public void copyFrom(FVector4 src)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| src | [FVector4](../../com.aspose.threed/fvector4) |  |

### create(FVector4 v) {#create-com.aspose.threed.FVector4-}
```
public static Vector4 create(FVector4 v)
```


Operatore di conversione esplicita per castare Vector4 a FVector4

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| v | [FVector4](../../com.aspose.threed/fvector4) |  |

**Returns:**
[Vector4](../../com.aspose.threed/vector4)
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
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### mul(FVector4 lhs, FVector4 rhs) {#mul-com.aspose.threed.FVector4-com.aspose.threed.FVector4-}
```
public static FVector4 mul(FVector4 lhs, FVector4 rhs)
```


Sovraccarico dell'operatore per \*

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs | [FVector4](../../com.aspose.threed/fvector4) | The left vector |
| rhs | [FVector4](../../com.aspose.threed/fvector4) | The right vector |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4) - Result vector
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### sub(FVector4 lhs, FVector4 rhs) {#sub-com.aspose.threed.FVector4-com.aspose.threed.FVector4-}
```
public static FVector4 sub(FVector4 lhs, FVector4 rhs)
```


Operator overloading for - (minus)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs | [FVector4](../../com.aspose.threed/fvector4) | The left vector |
| rhs | [FVector4](../../com.aspose.threed/fvector4) | The right vector |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4) - Result vector
### toString() {#toString--}
```
public String toString()
```


Restituisce una stringa che rappresenta il [FVector4](../../com.aspose.threed/fvector4)

**Returns:**
java.lang.String - La rappresentazione stringa del vettore corrente.
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

