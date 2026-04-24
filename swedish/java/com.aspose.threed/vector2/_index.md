---
title: Vector2
second_title: Aspose.3D for Java API-referens
description: En vektor med två komponenter.
type: docs
weight: 201
url: /sv/java/com.aspose.threed/vector2/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.threed.Struct, java.io.Serializable
```
public final class Vector2 implements Comparable<Vector2>, Struct<Vector2>, Serializable
```

En vektor med två komponenter.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Vector2(double s)](#Vector2-double-) | Initierar en ny instans av strukturen [Vector2](../../com.aspose.threed/vector2). |
| [Vector2(Vector3 s)](#Vector2-com.aspose.threed.Vector3-) | Initierar en ny instans av strukturen [Vector2](../../com.aspose.threed/vector2). |
| [Vector2(FVector2 vec)](#Vector2-com.aspose.threed.FVector2-) | Initierar en ny instans av strukturen [Vector2](../../com.aspose.threed/vector2). |
| [Vector2(double x, double y)](#Vector2-double-double-) | Initierar en ny instans av strukturen [Vector2](../../com.aspose.threed/vector2). |
| [Vector2()](#Vector2--) |  |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [x](#x) | x-komponenten. |
| [y](#y) | y-komponenten. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add(Vector2 lhs, Vector2 rhs)](#add-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Additionsoperator för Vector2 |
| [clone()](#clone--) |  |
| [compareTo(Vector2 other)](#compareTo-com.aspose.threed.Vector2-) | Jämför den aktuella vektorn med en annan instans. |
| [copyFrom(Vector2 src)](#copyFrom-com.aspose.threed.Vector2-) |  |
| [create(Vector2 v)](#create-com.aspose.threed.Vector2-) | Explicit konverteringsoperator för att kasta Vector2 till FVector2 |
| [cross(Vector2 v)](#cross-com.aspose.threed.Vector2-) | Korsprodukt av två vektorer. |
| [div(Vector2 lhs, double rhs)](#div-com.aspose.threed.Vector2-double-) | Divisionsoperator för Vector2 |
| [dot(Vector2 rhs)](#dot-com.aspose.threed.Vector2-) | Hämtar skalärprodukten av två vektorer. |
| [equals(Vector2 rhs)](#equals-com.aspose.threed.Vector2-) | Kontrollera om två vector2 är lika |
| [equals(Object obj)](#equals-java.lang.Object-) | Kontrollera om två vector2 är lika |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Hämtar längden. |
| [getU()](#getU--) | Hämtar U-komponenten om [Vector2](../../com.aspose.threed/vector2) används som en mappningskoordinat. |
| [getV()](#getV--) | Hämtar V-komponenten om [Vector2](../../com.aspose.threed/vector2) används som en mappningskoordinat. |
| [hashCode()](#hashCode--) | Hämtar hashkoden för Vector2 |
| [mul(Vector2 lhs, double rhs)](#mul-com.aspose.threed.Vector2-double-) | Multiplikationsoperator för Vector2 |
| [mul(double lhs, Vector2 rhs)](#mul-double-com.aspose.threed.Vector2-) | Multiplikationsoperator för Vector2 |
| [normalize()](#normalize--) | Normalizes this instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(Vector2 lhs, Vector2 rhs)](#op-eq-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Likhetsoperator för Vector2 |
| [op_ne(Vector2 lhs, Vector2 rhs)](#op-ne-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Icke‑likhetsoperator för Vector2 |
| [setU(double value)](#setU-double-) | Ställer in U‑komponenten om [Vector2](../../com.aspose.threed/vector2) används som en kartläggningskoordinat. |
| [setV(double value)](#setV-double-) | Ställer in V‑komponenten om [Vector2](../../com.aspose.threed/vector2) används som en kartläggningskoordinat. |
| [sub(Vector2 lhs, Vector2 rhs)](#sub-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Subtraktionsoperator för Vector2 |
| [toString()](#toString--) | Returnerar en java.lang.String som representerar den aktuella [Vector2](../../com.aspose.threed/vector2). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Vector2(double s) {#Vector2-double-}
```
public Vector2(double s)
```


Initierar en ny instans av strukturen [Vector2](../../com.aspose.threed/vector2).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | double | S. |

### Vector2(Vector3 s) {#Vector2-com.aspose.threed.Vector3-}
```
public Vector2(Vector3 s)
```


Initierar en ny instans av strukturen [Vector2](../../com.aspose.threed/vector2).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | [Vector3](../../com.aspose.threed/vector3) | S. |

### Vector2(FVector2 vec) {#Vector2-com.aspose.threed.FVector2-}
```
public Vector2(FVector2 vec)
```


Initierar en ny instans av strukturen [Vector2](../../com.aspose.threed/vector2).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vec | [FVector2](../../com.aspose.threed/fvector2) | Vektor i float. |

### Vector2(double x, double y) {#Vector2-double-double-}
```
public Vector2(double x, double y)
```


Initierar en ny instans av strukturen [Vector2](../../com.aspose.threed/vector2).

**Parameters:**
| Parameter | Typ | Beskrivning |
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


x-komponenten.

### y {#y}
```
public double y
```


y-komponenten.

### add(Vector2 lhs, Vector2 rhs) {#add-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static Vector2 add(Vector2 lhs, Vector2 rhs)
```


Additionsoperator för Vector2

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Left hand side value. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Right hand side value. |

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


Jämför den aktuella vektorn med en annan instans.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
int
### copyFrom(Vector2 src) {#copyFrom-com.aspose.threed.Vector2-}
```
public void copyFrom(Vector2 src)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| src | [Vector2](../../com.aspose.threed/vector2) |  |

### create(Vector2 v) {#create-com.aspose.threed.Vector2-}
```
public static FVector2 create(Vector2 v)
```


Explicit konverteringsoperator för att kasta Vector2 till FVector2

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| v | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2)
### cross(Vector2 v) {#cross-com.aspose.threed.Vector2-}
```
public double cross(Vector2 v)
```


Korsprodukt av två vektorer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| v | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
double
### div(Vector2 lhs, double rhs) {#div-com.aspose.threed.Vector2-double-}
```
public static Vector2 div(Vector2 lhs, double rhs)
```


Divisionsoperator för Vector2

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Left hand side value. |
| rhs | double | Right hand side value. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of division.
### dot(Vector2 rhs) {#dot-com.aspose.threed.Vector2-}
```
public double dot(Vector2 rhs)
```


Hämtar skalärprodukten av två vektorer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Right hand side value. |

**Returns:**
double - The dot product of the two vectors.
### equals(Vector2 rhs) {#equals-com.aspose.threed.Vector2-}
```
public boolean equals(Vector2 rhs)
```


Kontrollera om två vector2 är lika

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Värdet på höger sida. |

**Returns:**
boolean - True if all components are identically equal.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Kontrollera om två vector2 är lika

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Objektet att jämföra. |

**Returns:**
boolean - True if all components are identically equal.
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


Hämtar längden.

**Returns:**
double - längden.
### getU() {#getU--}
```
public double getU()
```


Hämtar U‑komponenten om [Vector2](../../com.aspose.threed/vector2) används som en kartläggningskoordinat. Det är ett alias för x‑komponenten.

**Returns:**
double - U‑komponenten om [Vector2](../../com.aspose.threed/vector2) används som en kartläggningskoordinat. Det är ett alias för x‑komponenten.
### getV() {#getV--}
```
public double getV()
```


Hämtar V‑komponenten om [Vector2](../../com.aspose.threed/vector2) används som en kartläggningskoordinat. Det är ett alias för y‑komponenten.

**Returns:**
double - V‑komponenten om [Vector2](../../com.aspose.threed/vector2) används som en kartläggningskoordinat. Det är ett alias för y‑komponenten.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hämtar hashkoden för Vector2

**Returns:**
int - Hashkoden för [Vector2](../../com.aspose.threed/vector2)
### mul(Vector2 lhs, double rhs) {#mul-com.aspose.threed.Vector2-double-}
```
public static Vector2 mul(Vector2 lhs, double rhs)
```


Multiplikationsoperator för Vector2

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Left hand side value. |
| rhs | double | Right hand side value. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of multiply.
### mul(double lhs, Vector2 rhs) {#mul-double-com.aspose.threed.Vector2-}
```
public static Vector2 mul(double lhs, Vector2 rhs)
```


Multiplikationsoperator för Vector2

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs | double | Left hand side value. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Right hand side value. |

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


Likhetsoperator för Vector2

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Left hand side value. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Right hand side value. |

**Returns:**
boolean - True if all components are identically equal.
### op_ne(Vector2 lhs, Vector2 rhs) {#op-ne-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static boolean op_ne(Vector2 lhs, Vector2 rhs)
```


Icke‑likhetsoperator för Vector2

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Left hand side value. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Right hand side value. |

**Returns:**
boolean - True if two vectors are not equal.
### setU(double value) {#setU-double-}
```
public void setU(double value)
```


Ställer in U‑komponenten om [Vector2](../../com.aspose.threed/vector2) används som en kartläggningskoordinat. Det är ett alias för x‑komponenten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Nytt värde |

### setV(double value) {#setV-double-}
```
public void setV(double value)
```


Ställer in V‑komponenten om [Vector2](../../com.aspose.threed/vector2) används som en kartläggningskoordinat. Det är ett alias för y‑komponenten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Nytt värde |

### sub(Vector2 lhs, Vector2 rhs) {#sub-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static Vector2 sub(Vector2 lhs, Vector2 rhs)
```


Subtraktionsoperator för Vector2

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Left hand side value. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Right hand side value. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of substraction.
### toString() {#toString--}
```
public String toString()
```


Returnerar en java.lang.String som representerar den aktuella [Vector2](../../com.aspose.threed/vector2).

**Returns:**
java.lang.String - En java.lang.String som representerar den aktuella [Vector2](../../com.aspose.threed/vector2).
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

