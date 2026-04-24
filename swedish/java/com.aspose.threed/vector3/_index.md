---
title: Vector3
second_title: Aspose.3D for Java API-referens
description: En vektor med tre komponenter.
type: docs
weight: 202
url: /sv/java/com.aspose.threed/vector3/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.threed.Struct, java.io.Serializable
```
public final class Vector3 implements Comparable<Vector3>, Struct<Vector3>, Serializable
```

En vektor med tre komponenter.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Vector3(double x, double y, double z)](#Vector3-double-double-double-) | Initierar en ny instans av strukturen [Vector3](../../com.aspose.threed/vector3). |
| [Vector3(FVector3 vec)](#Vector3-com.aspose.threed.FVector3-) | Initierar en ny instans av strukturen [Vector3](../../com.aspose.threed/vector3). |
| [Vector3(double v)](#Vector3-double-) | Initierar en ny instans av strukturen [Vector3](../../com.aspose.threed/vector3). |
| [Vector3(Vector4 vec4)](#Vector3-com.aspose.threed.Vector4-) | Initierar en ny instans av strukturen [Vector3](../../com.aspose.threed/vector3). |
| [Vector3()](#Vector3--) |  |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [x](#x) | x-komponenten. |
| [y](#y) | y-komponenten. |
| [z](#z) | z-komponenten. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add(Vector3 lhs, Vector3 rhs)](#add-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Operatoröverladdning för + |
| [angleBetween(Vector3 dir)](#angleBetween-com.aspose.threed.Vector3-) | Beräkna den inre vinkeln mellan två riktningar. Två riktningar kan vara icke-normaliserade vektorer. |
| [angleBetween(Vector3 dir, Vector3 up)](#angleBetween-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Beräkna den inre vinkeln mellan två riktningar. Två riktningar kan vara icke-normaliserade vektorer. |
| [clone()](#clone--) |  |
| [compareTo(Vector3 other)](#compareTo-com.aspose.threed.Vector3-) | Jämför den aktuella vektorn med en annan instans. |
| [copyFrom(Vector3 src)](#copyFrom-com.aspose.threed.Vector3-) |  |
| [cos()](#cos--) | Beräknar cosinus för varje komponent. |
| [create(Vector3 v)](#create-com.aspose.threed.Vector3-) | Explicit konverteringsoperator för att kasta Vector3 till FVector3. |
| [cross(Vector3 rhs)](#cross-com.aspose.threed.Vector3-) | Korsprodukt av två vektorer. |
| [div(Vector3 lhs, Vector3 rhs)](#div-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Operatoröverladdning för / |
| [div(Vector3 lhs, double rhs)](#div-com.aspose.threed.Vector3-double-) | Operatoröverladdning för / |
| [dot(Vector3 rhs)](#dot-com.aspose.threed.Vector3-) | Hämtar skalärprodukten av två vektorer. |
| [equals(Object obj)](#equals-java.lang.Object-) | Kontrollera om två vector3 är lika. |
| [get(int idx)](#get-int-) | Hämtar vektorns komponent efter index. |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Hämtar längden på denna vektor. |
| [getLength2()](#getLength2--) | Hämtar kvadraten av längden. |
| [getOne()](#getOne--) | Hämtar enhetsvektor (1, 1, 1). |
| [getUnitX()](#getUnitX--) | Hämtar enhetsvektor (1, 0, 0). |
| [getUnitY()](#getUnitY--) | Hämtar enhetsvektor (0, 1, 0). |
| [getUnitZ()](#getUnitZ--) | Hämtar enhetsvektor (0, 0, 1). |
| [getZero()](#getZero--) | Hämtar enhetsvektor (0, 0, 0). |
| [hashCode()](#hashCode--) | Hämtar hashkoden för Vector3. |
| [mul(Vector3 lhs, Vector3 rhs)](#mul-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Operatoröverladdning för \* |
| [mul(Vector3 lhs, double rhs)](#mul-com.aspose.threed.Vector3-double-) | Operatoröverladdning för \* |
| [mul(double lhs, Vector3 rhs)](#mul-double-com.aspose.threed.Vector3-) | Operatoröverladdning för \* |
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


Initierar en ny instans av strukturen [Vector3](../../com.aspose.threed/vector3).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | double | The x coordinate. |
| y | double | The y coordinate. |
| z | double | The z coordinate. |

### Vector3(FVector3 vec) {#Vector3-com.aspose.threed.FVector3-}
```
public Vector3(FVector3 vec)
```


Initierar en ny instans av strukturen [Vector3](../../com.aspose.threed/vector3).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vec | [FVector3](../../com.aspose.threed/fvector3) | The x coordinate. |

### Vector3(double v) {#Vector3-double-}
```
public Vector3(double v)
```


Initierar en ny instans av strukturen [Vector3](../../com.aspose.threed/vector3).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| v | double | V. |

### Vector3(Vector4 vec4) {#Vector3-com.aspose.threed.Vector4-}
```
public Vector3(Vector4 vec4)
```


Initierar en ny instans av strukturen [Vector3](../../com.aspose.threed/vector3).

**Parameters:**
| Parameter | Typ | Beskrivning |
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

### add(Vector3 lhs, Vector3 rhs) {#add-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 add(Vector3 lhs, Vector3 rhs)
```


Operatoröverladdning för +

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | The left vector |
| rhs | [Vector3](../../com.aspose.threed/vector3) | The right vector |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### angleBetween(Vector3 dir) {#angleBetween-com.aspose.threed.Vector3-}
```
public double angleBetween(Vector3 dir)
```


Beräkna den inre vinkeln mellan två riktningar. Två riktningar kan vara icke-normaliserade vektorer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dir | [Vector3](../../com.aspose.threed/vector3) | The direction vector to compare with |

**Returns:**
double - inner angle in radian
### angleBetween(Vector3 dir, Vector3 up) {#angleBetween-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public double angleBetween(Vector3 dir, Vector3 up)
```


Beräkna den inre vinkeln mellan två riktningar. Två riktningar kan vara icke-normaliserade vektorer.

**Parameters:**
| Parameter | Typ | Beskrivning |
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


Jämför den aktuella vektorn med en annan instans.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
int
### copyFrom(Vector3 src) {#copyFrom-com.aspose.threed.Vector3-}
```
public void copyFrom(Vector3 src)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| src | [Vector3](../../com.aspose.threed/vector3) |  |

### cos() {#cos--}
```
public Vector3 cos()
```


Beräknar cosinus för varje komponent.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Calculated [Vector3](../../com.aspose.threed/vector3).
### create(Vector3 v) {#create-com.aspose.threed.Vector3-}
```
public static FVector3 create(Vector3 v)
```


Explicit konverteringsoperator för att kasta Vector3 till FVector3.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### cross(Vector3 rhs) {#cross-com.aspose.threed.Vector3-}
```
public Vector3 cross(Vector3 rhs)
```


Korsprodukt av två vektorer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Right hand side value. |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Cross product of two [Vector3](../../com.aspose.threed/vector3)s.
### div(Vector3 lhs, Vector3 rhs) {#div-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 div(Vector3 lhs, Vector3 rhs)
```


Operatoröverladdning för /

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | The left vector |
| rhs | [Vector3](../../com.aspose.threed/vector3) | The right vector |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### div(Vector3 lhs, double rhs) {#div-com.aspose.threed.Vector3-double-}
```
public static Vector3 div(Vector3 lhs, double rhs)
```


Operatoröverladdning för /

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | The left vector |
| rhs | double | The right double value |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### dot(Vector3 rhs) {#dot-com.aspose.threed.Vector3-}
```
public double dot(Vector3 rhs)
```


Hämtar skalärprodukten av två vektorer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Right hand side value. |

**Returns:**
double - The dot product of the two vectors.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Kontrollera om två vector3 är lika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | The object to check equality. |

**Returns:**
boolean - True if all components are identically equal.
### get(int idx) {#get-int-}
```
public double get(int idx)
```


Hämtar vektorns komponent efter index.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| idx | int |  |

**Returns:**
double - vector's component by index.
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


Hämtar längden på denna vektor.

**Returns:**
double - the length of this vector.
### getLength2() {#getLength2--}
```
public double getLength2()
```


Hämtar kvadraten av längden.

**Returns:**
double - the square of the length.
### getOne() {#getOne--}
```
public static Vector3 getOne()
```


Hämtar enhetsvektor (1, 1, 1).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (1, 1, 1)
### getUnitX() {#getUnitX--}
```
public static Vector3 getUnitX()
```


Hämtar enhetsvektor (1, 0, 0).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (1, 0, 0)
### getUnitY() {#getUnitY--}
```
public static Vector3 getUnitY()
```


Hämtar enhetsvektor (0, 1, 0).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (0, 1, 0)
### getUnitZ() {#getUnitZ--}
```
public static Vector3 getUnitZ()
```


Hämtar enhetsvektor (0, 0, 1).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (0, 0, 1)
### getZero() {#getZero--}
```
public static Vector3 getZero()
```


Hämtar enhetsvektor (0, 0, 0).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (0, 0, 0)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hämtar hashkoden för Vector3.

**Returns:**
int - The hash code of the [Vector3](../../com.aspose.threed/vector3)
### mul(Vector3 lhs, Vector3 rhs) {#mul-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 mul(Vector3 lhs, Vector3 rhs)
```


Operatoröverladdning för \*

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | The left vector |
| rhs | [Vector3](../../com.aspose.threed/vector3) | The right vector |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### mul(Vector3 lhs, double rhs) {#mul-com.aspose.threed.Vector3-double-}
```
public static Vector3 mul(Vector3 lhs, double rhs)
```


Operatoröverladdning för \*

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | The left vector |
| rhs | double | The right double value |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### mul(double lhs, Vector3 rhs) {#mul-double-com.aspose.threed.Vector3-}
```
public static Vector3 mul(double lhs, Vector3 rhs)
```


Operatoröverladdning för \*

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs | double | The left scalar |
| rhs | [Vector3](../../com.aspose.threed/vector3) | The right vector |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### negative(Vector3 v) {#negative-com.aspose.threed.Vector3-}
```
public static Vector3 negative(Vector3 v)
```


Operator overloading for -

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) | The origin vector |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Left hand side value. |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Right hand side value. |

**Returns:**
boolean - True if all components are identically equal.
### op_ne(Vector3 lhs, Vector3 rhs) {#op-ne-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static boolean op_ne(Vector3 lhs, Vector3 rhs)
```


Not-equal operator for Vector3

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Left hand side value. |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Right hand side value. |

**Returns:**
boolean - True if two vectors are not equal.
### set(double newX, double newY, double newZ) {#set-double-double-double-}
```
public void set(double newX, double newY, double newZ)
```


Sets the x/y/z component in one call.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newX | double | x-komponenten. |
| newY | double | y-komponenten. |
| newZ | double | z-komponenten. |

### set(int idx, double value) {#set-int-double-}
```
public void set(int idx, double value)
```


Sets vector's component by index.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| idx | int |  |
| värde | double | Nytt värde |

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
| Parameter | Typ | Beskrivning |
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
java.lang.String - A java.lang.String that represents the current [Vector3](../../com.aspose.threed/vector3).
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

