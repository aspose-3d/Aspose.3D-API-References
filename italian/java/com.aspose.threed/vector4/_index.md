---
title: Vector4
second_title: Aspose.3D for Java API Reference
description: Un vettore con quattro componenti.
type: docs
weight: 203
url: /it/java/com.aspose.threed/vector4/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.threed.Struct, java.io.Serializable
```
public final class Vector4 implements Comparable<Vector4>, Struct<Vector4>, Serializable
```

Un vettore con quattro componenti.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Vector4(Vector3 vec, double w)](#Vector4-com.aspose.threed.Vector3-double-) | Inizializza una nuova istanza della struct [Vector4](../../com.aspose.threed/vector4). |
| [Vector4(Vector3 vec)](#Vector4-com.aspose.threed.Vector3-) | Inizializza una nuova istanza della struct [Vector4](../../com.aspose.threed/vector4). |
| [Vector4(FVector4 vec)](#Vector4-com.aspose.threed.FVector4-) | Inizializza una nuova istanza della struct [Vector4](../../com.aspose.threed/vector4). |
| [Vector4(double x, double y, double z)](#Vector4-double-double-double-) | Inizializza una nuova istanza della struct [Vector4](../../com.aspose.threed/vector4). |
| [Vector4(double x, double y, double z, double w)](#Vector4-double-double-double-double-) | Inizializza una nuova istanza della struct [Vector4](../../com.aspose.threed/vector4). |
| [Vector4()](#Vector4--) |  |
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
| [add(Vector4 lhs, Vector4 rhs)](#add-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | Sovraccarico dell'operatore per + |
| [clone()](#clone--) |  |
| [compareTo(Vector4 other)](#compareTo-com.aspose.threed.Vector4-) | Confronta il vettore corrente con un'altra istanza. |
| [copyFrom(Vector4 src)](#copyFrom-com.aspose.threed.Vector4-) |  |
| [create(Vector4 v)](#create-com.aspose.threed.Vector4-) | Operatore di conversione esplicita per castare Vector4 a FVector4 |
| [equals(Object obj)](#equals-java.lang.Object-) | Verifica se due vettori sono uguali |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | Ottiene il codice hash di questo vettore |
| [mul(Vector4 lhs, Vector4 rhs)](#mul-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | Sovraccarico dell'operatore per \* |
| [mul(Vector4 lhs, double rhs)](#mul-com.aspose.threed.Vector4-double-) | Sovraccarico dell'operatore per \* |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [set(double newX, double newY, double newZ)](#set-double-double-double-) | Imposta le componenti xyz del vettore contemporaneamente, w verrà impostato a 1 |
| [set(double newX, double newY, double newZ, double newW)](#set-double-double-double-double-) | Imposta tutte le componenti del vettore contemporaneamente |
| [sub(Vector4 lhs, Vector4 rhs)](#sub-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | Operator overloading for - (minus) |
| [toString()](#toString--) | Restituisce una java.lang.String che rappresenta l'attuale [Vector4](../../com.aspose.threed/vector4). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Vector4(Vector3 vec, double w) {#Vector4-com.aspose.threed.Vector3-double-}
```
public Vector4(Vector3 vec, double w)
```


Inizializza una nuova istanza della struct [Vector4](../../com.aspose.threed/vector4).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) | Vec. |
| w | double | La larghezza. |

### Vector4(Vector3 vec) {#Vector4-com.aspose.threed.Vector3-}
```
public Vector4(Vector3 vec)
```


Inizializza una nuova istanza della struct [Vector4](../../com.aspose.threed/vector4).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) | Vec. |

### Vector4(FVector4 vec) {#Vector4-com.aspose.threed.FVector4-}
```
public Vector4(FVector4 vec)
```


Inizializza una nuova istanza della struct [Vector4](../../com.aspose.threed/vector4).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vec | [FVector4](../../com.aspose.threed/fvector4) | Vec. |

### Vector4(double x, double y, double z) {#Vector4-double-double-double-}
```
public Vector4(double x, double y, double z)
```


Inizializza una nuova istanza della struct [Vector4](../../com.aspose.threed/vector4).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | double | The x coordinate. |
| y | double | The y coordinate. |
| z | double | The z coordinate. |

### Vector4(double x, double y, double z, double w) {#Vector4-double-double-double-double-}
```
public Vector4(double x, double y, double z, double w)
```


Inizializza una nuova istanza della struct [Vector4](../../com.aspose.threed/vector4).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | double | The x coordinate. |
| y | double | The y coordinate. |
| z | double | The z coordinate. |
| w | double | La larghezza. |

### Vector4() {#Vector4--}
```
public Vector4()
```


### w {#w}
```
public double w
```


Il componente w.

### x {#x}
```
public double x
```


La componente x.

### y {#y}
```
public double y
```


La componente y.

### z {#z}
```
public double z
```


La componente z.

### add(Vector4 lhs, Vector4 rhs) {#add-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public static Vector4 add(Vector4 lhs, Vector4 rhs)
```


Sovraccarico dell'operatore per +

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | The left vector |
| rhs | [Vector4](../../com.aspose.threed/vector4) | The right vector |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### clone() {#clone--}
```
public Vector4 clone()
```


Clone current instance

**Returns:**
[Vector4](../../com.aspose.threed/vector4)
### compareTo(Vector4 other) {#compareTo-com.aspose.threed.Vector4-}
```
public int compareTo(Vector4 other)
```


Confronta il vettore corrente con un'altra istanza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | [Vector4](../../com.aspose.threed/vector4) |  |

**Returns:**
int
### copyFrom(Vector4 src) {#copyFrom-com.aspose.threed.Vector4-}
```
public void copyFrom(Vector4 src)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| src | [Vector4](../../com.aspose.threed/vector4) |  |

### create(Vector4 v) {#create-com.aspose.threed.Vector4-}
```
public static FVector4 create(Vector4 v)
```


Operatore di conversione esplicita per castare Vector4 a FVector4

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| v | [Vector4](../../com.aspose.threed/vector4) |  |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Verifica se due vettori sono uguali

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


Ottiene il codice hash di questo vettore

**Returns:**
int
### mul(Vector4 lhs, Vector4 rhs) {#mul-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public static Vector4 mul(Vector4 lhs, Vector4 rhs)
```


Sovraccarico dell'operatore per \*

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | The left vector |
| rhs | [Vector4](../../com.aspose.threed/vector4) | The right vector |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### mul(Vector4 lhs, double rhs) {#mul-com.aspose.threed.Vector4-double-}
```
public static Vector4 mul(Vector4 lhs, double rhs)
```


Sovraccarico dell'operatore per \*

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | The left vector |
| rhs | double | Il valore double destro |

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


Imposta le componenti xyz del vettore contemporaneamente, w verrà impostato a 1

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newX | double | Nuova componente X. |
| newY | double | Nuova componente Y. |
| newZ | double | Nuova componente Z. |

### set(double newX, double newY, double newZ, double newW) {#set-double-double-double-double-}
```
public void set(double newX, double newY, double newZ, double newW)
```


Imposta tutte le componenti del vettore contemporaneamente

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newX | double | Nuova componente X. |
| newY | double | Nuova componente Y. |
| newZ | double | Nuova componente Z. |
| newW | double | Nuovo componente W. |

### sub(Vector4 lhs, Vector4 rhs) {#sub-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public static Vector4 sub(Vector4 lhs, Vector4 rhs)
```


Operator overloading for - (minus)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | The left vector |
| rhs | [Vector4](../../com.aspose.threed/vector4) | The right vector |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### toString() {#toString--}
```
public String toString()
```


Restituisce una java.lang.String che rappresenta l'attuale [Vector4](../../com.aspose.threed/vector4).

**Returns:**
java.lang.String - Una java.lang.String che rappresenta l'attuale [Vector4](../../com.aspose.threed/vector4).
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

