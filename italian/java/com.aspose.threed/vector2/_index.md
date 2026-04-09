---
title: Vector2
second_title: Aspose.3D for Java API Reference
description: Un vettore con due componenti.
type: docs
weight: 201
url: /it/java/com.aspose.threed/vector2/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.threed.Struct, java.io.Serializable
```
public final class Vector2 implements Comparable<Vector2>, Struct<Vector2>, Serializable
```

Un vettore con due componenti.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Vector2(double s)](#Vector2-double-) | Inizializza una nuova istanza della struct [Vector2](../../com.aspose.threed/vector2). |
| [Vector2(Vector3 s)](#Vector2-com.aspose.threed.Vector3-) | Inizializza una nuova istanza della struct [Vector2](../../com.aspose.threed/vector2). |
| [Vector2(FVector2 vec)](#Vector2-com.aspose.threed.FVector2-) | Inizializza una nuova istanza della struct [Vector2](../../com.aspose.threed/vector2). |
| [Vector2(double x, double y)](#Vector2-double-double-) | Inizializza una nuova istanza della struct [Vector2](../../com.aspose.threed/vector2). |
| [Vector2()](#Vector2--) |  |
## Campi

| Campo | Descrizione |
| --- | --- |
| [x](#x) | La componente x. |
| [y](#y) | La componente y. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add(Vector2 lhs, Vector2 rhs)](#add-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Operatore di addizione per Vector2 |
| [clone()](#clone--) |  |
| [compareTo(Vector2 other)](#compareTo-com.aspose.threed.Vector2-) | Confronta il vettore corrente con un'altra istanza. |
| [copyFrom(Vector2 src)](#copyFrom-com.aspose.threed.Vector2-) |  |
| [create(Vector2 v)](#create-com.aspose.threed.Vector2-) | Operatore di conversione esplicita per convertire Vector2 in FVector2 |
| [cross(Vector2 v)](#cross-com.aspose.threed.Vector2-) | Prodotto vettoriale di due vettori. |
| [div(Vector2 lhs, double rhs)](#div-com.aspose.threed.Vector2-double-) | Operatore di divisione per Vector2 |
| [dot(Vector2 rhs)](#dot-com.aspose.threed.Vector2-) | Restituisce il prodotto scalare di due vettori. |
| [equals(Vector2 rhs)](#equals-com.aspose.threed.Vector2-) | Verifica se due vector2 sono uguali |
| [equals(Object obj)](#equals-java.lang.Object-) | Verifica se due vector2 sono uguali |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Restituisce la lunghezza. |
| [getU()](#getU--) | Restituisce la componente U se il [Vector2](../../com.aspose.threed/vector2) è usato come coordinata di mappatura. |
| [getV()](#getV--) | Restituisce la componente V se il [Vector2](../../com.aspose.threed/vector2) è usato come coordinata di mappatura. |
| [hashCode()](#hashCode--) | Restituisce il codice hash di Vector2 |
| [mul(Vector2 lhs, double rhs)](#mul-com.aspose.threed.Vector2-double-) | Operatore di moltiplicazione per Vector2 |
| [mul(double lhs, Vector2 rhs)](#mul-double-com.aspose.threed.Vector2-) | Operatore di moltiplicazione per Vector2 |
| [normalize()](#normalize--) | Normalizes this instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(Vector2 lhs, Vector2 rhs)](#op-eq-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Operatore di uguaglianza per Vector2 |
| [op_ne(Vector2 lhs, Vector2 rhs)](#op-ne-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Operatore di disuguaglianza per Vector2 |
| [setU(double value)](#setU-double-) | Imposta la componente U se il [Vector2](../../com.aspose.threed/vector2) è usato come coordinata di mappatura. |
| [setV(double value)](#setV-double-) | Imposta la componente V se il [Vector2](../../com.aspose.threed/vector2) è usato come coordinata di mappatura. |
| [sub(Vector2 lhs, Vector2 rhs)](#sub-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Operatore di sottrazione per Vector2 |
| [toString()](#toString--) | Restituisce una java.lang.String che rappresenta il corrente [Vector2](../../com.aspose.threed/vector2). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Vector2(double s) {#Vector2-double-}
```
public Vector2(double s)
```


Inizializza una nuova istanza della struct [Vector2](../../com.aspose.threed/vector2).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | double | S. |

### Vector2(Vector3 s) {#Vector2-com.aspose.threed.Vector3-}
```
public Vector2(Vector3 s)
```


Inizializza una nuova istanza della struct [Vector2](../../com.aspose.threed/vector2).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | [Vector3](../../com.aspose.threed/vector3) | S. |

### Vector2(FVector2 vec) {#Vector2-com.aspose.threed.FVector2-}
```
public Vector2(FVector2 vec)
```


Inizializza una nuova istanza della struct [Vector2](../../com.aspose.threed/vector2).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vec | [FVector2](../../com.aspose.threed/fvector2) | Vettore in float. |

### Vector2(double x, double y) {#Vector2-double-double-}
```
public Vector2(double x, double y)
```


Inizializza una nuova istanza della struct [Vector2](../../com.aspose.threed/vector2).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | double | The x coordinate. |
| y | double | The y coordinate. |

### Vector2() {#Vector2--}
```
public Vector2()
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

### add(Vector2 lhs, Vector2 rhs) {#add-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static Vector2 add(Vector2 lhs, Vector2 rhs)
```


Operatore di addizione per Vector2

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Valore del lato sinistro. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Valore del lato destro. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of addition.
### clone() {#clone--}
```
public Vector2 clone()
```


Clone current instance

**Returns:**
[Vector2](../../com.aspose.threed/vector2)
### compareTo(Vector2 other) {#compareTo-com.aspose.threed.Vector2-}
```
public int compareTo(Vector2 other)
```


Confronta il vettore corrente con un'altra istanza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
int
### copyFrom(Vector2 src) {#copyFrom-com.aspose.threed.Vector2-}
```
public void copyFrom(Vector2 src)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| src | [Vector2](../../com.aspose.threed/vector2) |  |

### create(Vector2 v) {#create-com.aspose.threed.Vector2-}
```
public static FVector2 create(Vector2 v)
```


Operatore di conversione esplicita per convertire Vector2 in FVector2

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| v | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2)
### cross(Vector2 v) {#cross-com.aspose.threed.Vector2-}
```
public double cross(Vector2 v)
```


Prodotto vettoriale di due vettori.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| v | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
double
### div(Vector2 lhs, double rhs) {#div-com.aspose.threed.Vector2-double-}
```
public static Vector2 div(Vector2 lhs, double rhs)
```


Operatore di divisione per Vector2

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Valore del lato sinistro. |
| rhs | double | Valore del lato destro. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of division.
### dot(Vector2 rhs) {#dot-com.aspose.threed.Vector2-}
```
public double dot(Vector2 rhs)
```


Restituisce il prodotto scalare di due vettori.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Valore del lato destro. |

**Returns:**
double - Il prodotto scalare dei due vettori.
### equals(Vector2 rhs) {#equals-com.aspose.threed.Vector2-}
```
public boolean equals(Vector2 rhs)
```


Verifica se due vector2 sono uguali

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Il valore del lato destro. |

**Returns:**
boolean - Vero se tutti i componenti sono identicamente uguali.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Verifica se due vector2 sono uguali

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'oggetto da confrontare. |

**Returns:**
boolean - Vero se tutti i componenti sono identicamente uguali.
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


Restituisce la lunghezza.

**Returns:**
double - la lunghezza.
### getU() {#getU--}
```
public double getU()
```


Ottiene la componente U se il [Vector2](../../com.aspose.threed/vector2) è usato come coordinata di mappatura. È un alias della componente x.

**Returns:**
double - la componente U se il [Vector2](../../com.aspose.threed/vector2) è usato come coordinata di mappatura. È un alias della componente x.
### getV() {#getV--}
```
public double getV()
```


Ottiene la componente V se il [Vector2](../../com.aspose.threed/vector2) è usato come coordinata di mappatura. È un alias della componente y.

**Returns:**
double - la componente V se il [Vector2](../../com.aspose.threed/vector2) è usato come coordinata di mappatura. È un alias della componente y.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce il codice hash di Vector2

**Returns:**
int - Il codice hash del [Vector2](../../com.aspose.threed/vector2)
### mul(Vector2 lhs, double rhs) {#mul-com.aspose.threed.Vector2-double-}
```
public static Vector2 mul(Vector2 lhs, double rhs)
```


Operatore di moltiplicazione per Vector2

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Valore del lato sinistro. |
| rhs | double | Valore del lato destro. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of multiply.
### mul(double lhs, Vector2 rhs) {#mul-double-com.aspose.threed.Vector2-}
```
public static Vector2 mul(double lhs, Vector2 rhs)
```


Operatore di moltiplicazione per Vector2

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs | double | Valore del lato sinistro. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Valore del lato destro. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of multiply.
### normalize() {#normalize--}
```
public Vector2 normalize()
```


Normalizes this instance.

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


Operatore di uguaglianza per Vector2

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Valore del lato sinistro. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Valore del lato destro. |

**Returns:**
boolean - Vero se tutti i componenti sono identicamente uguali.
### op_ne(Vector2 lhs, Vector2 rhs) {#op-ne-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static boolean op_ne(Vector2 lhs, Vector2 rhs)
```


Operatore di disuguaglianza per Vector2

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Valore del lato sinistro. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Valore del lato destro. |

**Returns:**
boolean - Vero se due vettori non sono uguali.
### setU(double value) {#setU-double-}
```
public void setU(double value)
```


Imposta la componente U se il [Vector2](../../com.aspose.threed/vector2) è usato come coordinata di mappatura. È un alias della componente x.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### setV(double value) {#setV-double-}
```
public void setV(double value)
```


Imposta la componente V se il [Vector2](../../com.aspose.threed/vector2) è usato come coordinata di mappatura. È un alias della componente y.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### sub(Vector2 lhs, Vector2 rhs) {#sub-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static Vector2 sub(Vector2 lhs, Vector2 rhs)
```


Operatore di sottrazione per Vector2

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Valore del lato sinistro. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Valore del lato destro. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of substraction.
### toString() {#toString--}
```
public String toString()
```


Restituisce una java.lang.String che rappresenta il corrente [Vector2](../../com.aspose.threed/vector2).

**Returns:**
java.lang.String - Una java.lang.String che rappresenta il corrente [Vector2](../../com.aspose.threed/vector2).
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

