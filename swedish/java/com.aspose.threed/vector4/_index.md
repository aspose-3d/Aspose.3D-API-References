---
title: Vector4
second_title: Aspose.3D for Java API-referens
description: En vektor med fyra komponenter.
type: docs
weight: 203
url: /sv/java/com.aspose.threed/vector4/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.threed.Struct, java.io.Serializable
```
public final class Vector4 implements Comparable<Vector4>, Struct<Vector4>, Serializable
```

En vektor med fyra komponenter.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Vector4(Vector3 vec, double w)](#Vector4-com.aspose.threed.Vector3-double-) | Initierar en ny instans av strukturen [Vector4](../../com.aspose.threed/vector4). |
| [Vector4(Vector3 vec)](#Vector4-com.aspose.threed.Vector3-) | Initierar en ny instans av strukturen [Vector4](../../com.aspose.threed/vector4). |
| [Vector4(FVector4 vec)](#Vector4-com.aspose.threed.FVector4-) | Initierar en ny instans av strukturen [Vector4](../../com.aspose.threed/vector4). |
| [Vector4(double x, double y, double z)](#Vector4-double-double-double-) | Initierar en ny instans av strukturen [Vector4](../../com.aspose.threed/vector4). |
| [Vector4(double x, double y, double z, double w)](#Vector4-double-double-double-double-) | Initierar en ny instans av strukturen [Vector4](../../com.aspose.threed/vector4). |
| [Vector4()](#Vector4--) |  |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [w](#w) | w-komponenten. |
| [x](#x) | x-komponenten. |
| [y](#y) | y-komponenten. |
| [z](#z) | z-komponenten. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add(Vector4 lhs, Vector4 rhs)](#add-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | Operatoröverladdning för + |
| [clone()](#clone--) |  |
| [compareTo(Vector4 other)](#compareTo-com.aspose.threed.Vector4-) | Jämför den aktuella vektorn med en annan instans. |
| [copyFrom(Vector4 src)](#copyFrom-com.aspose.threed.Vector4-) |  |
| [create(Vector4 v)](#create-com.aspose.threed.Vector4-) | Explicit konverteringsoperator för att kasta Vector4 till FVector4 |
| [equals(Object obj)](#equals-java.lang.Object-) | Kontrollera om två vektorer är lika |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | Hämtar hashkoden för denna vektor. |
| [mul(Vector4 lhs, Vector4 rhs)](#mul-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | Operatoröverladdning för \* |
| [mul(Vector4 lhs, double rhs)](#mul-com.aspose.threed.Vector4-double-) | Operatoröverladdning för \* |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [set(double newX, double newY, double newZ)](#set-double-double-double-) | Ställer in vektorns xyz‑komponenter på en gång, w kommer att sättas till 1. |
| [set(double newX, double newY, double newZ, double newW)](#set-double-double-double-double-) | Ställer in vektorns alla komponenter på en gång. |
| [sub(Vector4 lhs, Vector4 rhs)](#sub-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | Operator overloading for - (minus) |
| [toString()](#toString--) | Returnerar en java.lang.String som representerar den aktuella [Vector4](../../com.aspose.threed/vector4). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Vector4(Vector3 vec, double w) {#Vector4-com.aspose.threed.Vector3-double-}
```
public Vector4(Vector3 vec, double w)
```


Initierar en ny instans av strukturen [Vector4](../../com.aspose.threed/vector4).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) | Vektor. |
| w | double | Bredden. |

### Vector4(Vector3 vec) {#Vector4-com.aspose.threed.Vector3-}
```
public Vector4(Vector3 vec)
```


Initierar en ny instans av strukturen [Vector4](../../com.aspose.threed/vector4).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) | Vektor. |

### Vector4(FVector4 vec) {#Vector4-com.aspose.threed.FVector4-}
```
public Vector4(FVector4 vec)
```


Initierar en ny instans av strukturen [Vector4](../../com.aspose.threed/vector4).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vec | [FVector4](../../com.aspose.threed/fvector4) | Vektor. |

### Vector4(double x, double y, double z) {#Vector4-double-double-double-}
```
public Vector4(double x, double y, double z)
```


Initierar en ny instans av strukturen [Vector4](../../com.aspose.threed/vector4).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | double | The x coordinate. |
| y | double | The y coordinate. |
| z | double | The z coordinate. |

### Vector4(double x, double y, double z, double w) {#Vector4-double-double-double-double-}
```
public Vector4(double x, double y, double z, double w)
```


Initierar en ny instans av strukturen [Vector4](../../com.aspose.threed/vector4).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | double | The x coordinate. |
| y | double | The y coordinate. |
| z | double | The z coordinate. |
| w | double | Bredden. |

### Vector4() {#Vector4--}
```
public Vector4()
```


### w {#w}
```
public double w
```


w-komponenten.

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

### z {#z}
```
public double z
```


z-komponenten.

### add(Vector4 lhs, Vector4 rhs) {#add-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public static Vector4 add(Vector4 lhs, Vector4 rhs)
```


Operatoröverladdning för +

**Parameters:**
| Parameter | Typ | Beskrivning |
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


Jämför den aktuella vektorn med en annan instans.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | [Vector4](../../com.aspose.threed/vector4) |  |

**Returns:**
int
### copyFrom(Vector4 src) {#copyFrom-com.aspose.threed.Vector4-}
```
public void copyFrom(Vector4 src)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| src | [Vector4](../../com.aspose.threed/vector4) |  |

### create(Vector4 v) {#create-com.aspose.threed.Vector4-}
```
public static FVector4 create(Vector4 v)
```


Explicit konverteringsoperator för att kasta Vector4 till FVector4

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| v | [Vector4](../../com.aspose.threed/vector4) |  |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Kontrollera om två vektorer är lika

**Parameters:**
| Parameter | Typ | Beskrivning |
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


Hämtar hashkoden för denna vektor.

**Returns:**
int
### mul(Vector4 lhs, Vector4 rhs) {#mul-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public static Vector4 mul(Vector4 lhs, Vector4 rhs)
```


Operatoröverladdning för \*

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | The left vector |
| rhs | [Vector4](../../com.aspose.threed/vector4) | The right vector |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### mul(Vector4 lhs, double rhs) {#mul-com.aspose.threed.Vector4-double-}
```
public static Vector4 mul(Vector4 lhs, double rhs)
```


Operatoröverladdning för \*

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | The left vector |
| rhs | double | The right double value |

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


Ställer in vektorns xyz‑komponenter på en gång, w kommer att sättas till 1.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newX | double | Ny X‑komponent. |
| newY | double | Ny Y‑komponent. |
| newZ | double | Ny Z‑komponent. |

### set(double newX, double newY, double newZ, double newW) {#set-double-double-double-double-}
```
public void set(double newX, double newY, double newZ, double newW)
```


Ställer in vektorns alla komponenter på en gång.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newX | double | Ny X‑komponent. |
| newY | double | Ny Y‑komponent. |
| newZ | double | Ny Z‑komponent. |
| newW | double | Ny W-komponent. |

### sub(Vector4 lhs, Vector4 rhs) {#sub-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public static Vector4 sub(Vector4 lhs, Vector4 rhs)
```


Operator overloading for - (minus)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | The left vector |
| rhs | [Vector4](../../com.aspose.threed/vector4) | The right vector |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### toString() {#toString--}
```
public String toString()
```


Returnerar en java.lang.String som representerar den aktuella [Vector4](../../com.aspose.threed/vector4).

**Returns:**
java.lang.String - En java.lang.String som representerar den aktuella [Vector4](../../com.aspose.threed/vector4).
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

