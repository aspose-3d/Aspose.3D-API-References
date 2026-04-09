---
title: Vector3
second_title: Aspose.3D for Java API Reference
description: Un vettore con tre componenti.
type: docs
weight: 202
url: /it/java/com.aspose.threed/vector3/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.threed.Struct, java.io.Serializable
```
public final class Vector3 implements Comparable<Vector3>, Struct<Vector3>, Serializable
```

Un vettore con tre componenti.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Vector3(double x, double y, double z)](#Vector3-double-double-double-) | Inizializza una nuova istanza della struct [Vector3](../../com.aspose.threed/vector3). |
| [Vector3(FVector3 vec)](#Vector3-com.aspose.threed.FVector3-) | Inizializza una nuova istanza della struct [Vector3](../../com.aspose.threed/vector3). |
| [Vector3(double v)](#Vector3-double-) | Inizializza una nuova istanza della struct [Vector3](../../com.aspose.threed/vector3). |
| [Vector3(Vector4 vec4)](#Vector3-com.aspose.threed.Vector4-) | Inizializza una nuova istanza della struct [Vector3](../../com.aspose.threed/vector3). |
| [Vector3()](#Vector3--) |  |
## Campi

| Campo | Descrizione |
| --- | --- |
| [x](#x) | La componente x. |
| [y](#y) | La componente y. |
| [z](#z) | La componente z. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add(Vector3 lhs, Vector3 rhs)](#add-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Sovraccarico dell'operatore per + |
| [angleBetween(Vector3 dir)](#angleBetween-com.aspose.threed.Vector3-) | Calcola l'angolo interno tra due direzioni. Le due direzioni possono essere vettori non normalizzati. |
| [angleBetween(Vector3 dir, Vector3 up)](#angleBetween-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Calcola l'angolo interno tra due direzioni. Le due direzioni possono essere vettori non normalizzati. |
| [clone()](#clone--) |  |
| [compareTo(Vector3 other)](#compareTo-com.aspose.threed.Vector3-) | Confronta il vettore corrente con un'altra istanza. |
| [copyFrom(Vector3 src)](#copyFrom-com.aspose.threed.Vector3-) |  |
| [cos()](#cos--) | Calcola il coseno su ogni componente. |
| [create(Vector3 v)](#create-com.aspose.threed.Vector3-) | Operatore di conversione esplicita per convertire Vector3 in FVector3. |
| [cross(Vector3 rhs)](#cross-com.aspose.threed.Vector3-) | Prodotto vettoriale di due vettori. |
| [div(Vector3 lhs, Vector3 rhs)](#div-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Sovraccarico dell'operatore per / |
| [div(Vector3 lhs, double rhs)](#div-com.aspose.threed.Vector3-double-) | Sovraccarico dell'operatore per / |
| [dot(Vector3 rhs)](#dot-com.aspose.threed.Vector3-) | Restituisce il prodotto scalare di due vettori. |
| [equals(Object obj)](#equals-java.lang.Object-) | Verifica se due vector3 sono uguali. |
| [get(int idx)](#get-int-) | Restituisce la componente del vettore per indice. |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Restituisce la lunghezza di questo vettore. |
| [getLength2()](#getLength2--) | Restituisce il quadrato della lunghezza. |
| [getOne()](#getOne--) | Restituisce il vettore unitario (1, 1, 1). |
| [getUnitX()](#getUnitX--) | Restituisce il vettore unitario (1, 0, 0). |
| [getUnitY()](#getUnitY--) | Restituisce il vettore unitario (0, 1, 0). |
| [getUnitZ()](#getUnitZ--) | Restituisce il vettore unitario (0, 0, 1). |
| [getZero()](#getZero--) | Restituisce il vettore unitario (0, 0, 0). |
| [hashCode()](#hashCode--) | Restituisce il codice hash di Vector3. |
| [mul(Vector3 lhs, Vector3 rhs)](#mul-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Sovraccarico dell'operatore per \* |
| [mul(Vector3 lhs, double rhs)](#mul-com.aspose.threed.Vector3-double-) | Sovraccarico dell'operatore per \* |
| [mul(double lhs, Vector3 rhs)](#mul-double-com.aspose.threed.Vector3-) | Sovraccarico dell'operatore per \* |
| [negative(Vector3 v)](#negative-com.aspose.threed.Vector3-) | Operator overloading for - |
| [normalize()](#normalize--) | Normalizes this instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(Vector3 lhs, Vector3 rhs)](#op-eq-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Equal operator for Vector3 |
| [op_ne(Vector3 lhs, Vector3 rhs)](#op-ne-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Not-equal operator for Vector3 |
| [set(double newX, double newY, double newZ)](#set-double-double-double-) | Sets the x/y/z component in one call. |
| [set(int idx, double value)](#set-int-double-) | Sets vector's component by index. |
| [sin()](#sin--) | Calculates sine on each component |
| [sub(Vector3 lhs, Vector3 rhs)](#sub-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Operator overloading for - (minus) |
| [toString()](#toString--) | Returns a java.lang.String that represents the current [Vector3](../../com.aspose.threed/vector3). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Vector3(double x, double y, double z) {#Vector3-double-double-double-}
```
public Vector3(double x, double y, double z)
```


Inizializza una nuova istanza della struct [Vector3](../../com.aspose.threed/vector3).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | double | The x coordinate. |
| y | double | The y coordinate. |
| z | double | The z coordinate. |

### Vector3(FVector3 vec) {#Vector3-com.aspose.threed.FVector3-}
```
public Vector3(FVector3 vec)
```


Inizializza una nuova istanza della struct [Vector3](../../com.aspose.threed/vector3).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vec | [FVector3](../../com.aspose.threed/fvector3) | The x coordinate. |

### Vector3(double v) {#Vector3-double-}
```
public Vector3(double v)
```


Inizializza una nuova istanza della struct [Vector3](../../com.aspose.threed/vector3).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| v | double | V. |

### Vector3(Vector4 vec4) {#Vector3-com.aspose.threed.Vector4-}
```
public Vector3(Vector4 vec4)
```


Inizializza una nuova istanza della struct [Vector3](../../com.aspose.threed/vector3).

**Parameters:**
| Parametro | Tipo | Descrizione |
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

### add(Vector3 lhs, Vector3 rhs) {#add-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 add(Vector3 lhs, Vector3 rhs)
```


Sovraccarico dell'operatore per +

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | The left vector |
| rhs | [Vector3](../../com.aspose.threed/vector3) | The right vector |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### angleBetween(Vector3 dir) {#angleBetween-com.aspose.threed.Vector3-}
```
public double angleBetween(Vector3 dir)
```


Calcola l'angolo interno tra due direzioni. Le due direzioni possono essere vettori non normalizzati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dir | [Vector3](../../com.aspose.threed/vector3) | The direction vector to compare with |

**Returns:**
double - inner angle in radian
### angleBetween(Vector3 dir, Vector3 up) {#angleBetween-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public double angleBetween(Vector3 dir, Vector3 up)
```


Calcola l'angolo interno tra due direzioni. Le due direzioni possono essere vettori non normalizzati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dir | [Vector3](../../com.aspose.threed/vector3) | The direction vector to compare with |
| up | [Vector3](../../com.aspose.threed/vector3) | The up vector of the two direction's shared plane |

**Returns:**
double - inner angle in radian
### clone() {#clone--}
```
public Vector3 clone()
```


Clone current instance

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### compareTo(Vector3 other) {#compareTo-com.aspose.threed.Vector3-}
```
public int compareTo(Vector3 other)
```


Confronta il vettore corrente con un'altra istanza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
int
### copyFrom(Vector3 src) {#copyFrom-com.aspose.threed.Vector3-}
```
public void copyFrom(Vector3 src)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| src | [Vector3](../../com.aspose.threed/vector3) |  |

### cos() {#cos--}
```
public Vector3 cos()
```


Calcola il coseno su ogni componente.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Calculated [Vector3](../../com.aspose.threed/vector3).
### create(Vector3 v) {#create-com.aspose.threed.Vector3-}
```
public static FVector3 create(Vector3 v)
```


Operatore di conversione esplicita per convertire Vector3 in FVector3.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### cross(Vector3 rhs) {#cross-com.aspose.threed.Vector3-}
```
public Vector3 cross(Vector3 rhs)
```


Prodotto vettoriale di due vettori.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Valore del lato destro. |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Cross product of two [Vector3](../../com.aspose.threed/vector3)s.
### div(Vector3 lhs, Vector3 rhs) {#div-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 div(Vector3 lhs, Vector3 rhs)
```


Sovraccarico dell'operatore per /

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | The left vector |
| rhs | [Vector3](../../com.aspose.threed/vector3) | The right vector |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### div(Vector3 lhs, double rhs) {#div-com.aspose.threed.Vector3-double-}
```
public static Vector3 div(Vector3 lhs, double rhs)
```


Sovraccarico dell'operatore per /

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | The left vector |
| rhs | double | Il valore double destro |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### dot(Vector3 rhs) {#dot-com.aspose.threed.Vector3-}
```
public double dot(Vector3 rhs)
```


Restituisce il prodotto scalare di due vettori.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Valore del lato destro. |

**Returns:**
double - Il prodotto scalare dei due vettori.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Verifica se due vector3 sono uguali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'oggetto da verificare l'uguaglianza. |

**Returns:**
boolean - Vero se tutti i componenti sono identicamente uguali.
### get(int idx) {#get-int-}
```
public double get(int idx)
```


Restituisce la componente del vettore per indice.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| idx | int |  |

**Returns:**
double - componente del vettore per indice.
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


Restituisce la lunghezza di questo vettore.

**Returns:**
double - la lunghezza di questo vettore.
### getLength2() {#getLength2--}
```
public double getLength2()
```


Restituisce il quadrato della lunghezza.

**Returns:**
double - il quadrato della lunghezza.
### getOne() {#getOne--}
```
public static Vector3 getOne()
```


Restituisce il vettore unitario (1, 1, 1).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (1, 1, 1)
### getUnitX() {#getUnitX--}
```
public static Vector3 getUnitX()
```


Restituisce il vettore unitario (1, 0, 0).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (1, 0, 0)
### getUnitY() {#getUnitY--}
```
public static Vector3 getUnitY()
```


Restituisce il vettore unitario (0, 1, 0).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (0, 1, 0)
### getUnitZ() {#getUnitZ--}
```
public static Vector3 getUnitZ()
```


Restituisce il vettore unitario (0, 0, 1).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (0, 0, 1)
### getZero() {#getZero--}
```
public static Vector3 getZero()
```


Restituisce il vettore unitario (0, 0, 0).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (0, 0, 0)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce il codice hash di Vector3.

**Returns:**
int - Il codice hash del [Vector3](../../com.aspose.threed/vector3)
### mul(Vector3 lhs, Vector3 rhs) {#mul-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 mul(Vector3 lhs, Vector3 rhs)
```


Sovraccarico dell'operatore per \*

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | The left vector |
| rhs | [Vector3](../../com.aspose.threed/vector3) | The right vector |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### mul(Vector3 lhs, double rhs) {#mul-com.aspose.threed.Vector3-double-}
```
public static Vector3 mul(Vector3 lhs, double rhs)
```


Sovraccarico dell'operatore per \*

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | The left vector |
| rhs | double | Il valore double destro |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### mul(double lhs, Vector3 rhs) {#mul-double-com.aspose.threed.Vector3-}
```
public static Vector3 mul(double lhs, Vector3 rhs)
```


Sovraccarico dell'operatore per \*

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs | double | Lo scalare sinistro |
| rhs | [Vector3](../../com.aspose.threed/vector3) | The right vector |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### negative(Vector3 v) {#negative-com.aspose.threed.Vector3-}
```
public static Vector3 negative(Vector3 v)
```


Operator overloading for -

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) | Il vettore di origine |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### normalize() {#normalize--}
```
public Vector3 normalize()
```


Normalizes this instance.

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


Equal operator for Vector3

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Valore del lato sinistro. |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Valore del lato destro. |

**Returns:**
boolean - Vero se tutti i componenti sono identicamente uguali.
### op_ne(Vector3 lhs, Vector3 rhs) {#op-ne-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static boolean op_ne(Vector3 lhs, Vector3 rhs)
```


Not-equal operator for Vector3

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Valore del lato sinistro. |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Valore del lato destro. |

**Returns:**
boolean - Vero se due vettori non sono uguali.
### set(double newX, double newY, double newZ) {#set-double-double-double-}
```
public void set(double newX, double newY, double newZ)
```


Sets the x/y/z component in one call.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newX | double | La componente x. |
| newY | double | La componente y. |
| newZ | double | La componente z. |

### set(int idx, double value) {#set-int-double-}
```
public void set(int idx, double value)
```


Sets vector's component by index.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| idx | int |  |
| valore | double | Nuovo valore |

### sin() {#sin--}
```
public Vector3 sin()
```


Calculates sine on each component

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Calculated [Vector3](../../com.aspose.threed/vector3).
### sub(Vector3 lhs, Vector3 rhs) {#sub-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 sub(Vector3 lhs, Vector3 rhs)
```


Operator overloading for - (minus)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | The left vector |
| rhs | [Vector3](../../com.aspose.threed/vector3) | The right vector |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### toString() {#toString--}
```
public String toString()
```


Returns a java.lang.String that represents the current [Vector3](../../com.aspose.threed/vector3).

**Returns:**
java.lang.String - Una java.lang.String che rappresenta l'attuale [Vector3](../../com.aspose.threed/vector3).
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

