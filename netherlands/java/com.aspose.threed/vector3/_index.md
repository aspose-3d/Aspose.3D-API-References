---
title: Vector3
second_title: Aspose.3D for Java API-referentie
description: Een vector met drie componenten.
type: docs
weight: 202
url: /nl/java/com.aspose.threed/vector3/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.threed.Struct, java.io.Serializable
```
public final class Vector3 implements Comparable<Vector3>, Struct<Vector3>, Serializable
```

Een vector met drie componenten.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Vector3(double x, double y, double z)](#Vector3-double-double-double-) | Initialiseert een nieuw exemplaar van de [Vector3](../../com.aspose.threed/vector3) struct. |
| [Vector3(FVector3 vec)](#Vector3-com.aspose.threed.FVector3-) | Initialiseert een nieuw exemplaar van de [Vector3](../../com.aspose.threed/vector3) struct. |
| [Vector3(double v)](#Vector3-double-) | Initialiseert een nieuw exemplaar van de [Vector3](../../com.aspose.threed/vector3) struct. |
| [Vector3(Vector4 vec4)](#Vector3-com.aspose.threed.Vector4-) | Initialiseert een nieuw exemplaar van de [Vector3](../../com.aspose.threed/vector3) struct. |
| [Vector3()](#Vector3--) |  |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [x](#x) | De x-component. |
| [y](#y) | De y-component. |
| [z](#z) | De z-component. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [add(Vector3 lhs, Vector3 rhs)](#add-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Operatoroverbelasting voor + |
| [angleBetween(Vector3 dir)](#angleBetween-com.aspose.threed.Vector3-) | Bereken de binnenhoek tussen twee richtingen. Twee richtingen kunnen niet-genormaliseerde vectoren zijn. |
| [angleBetween(Vector3 dir, Vector3 up)](#angleBetween-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Bereken de binnenhoek tussen twee richtingen. Twee richtingen kunnen niet-genormaliseerde vectoren zijn. |
| [clone()](#clone--) |  |
| [compareTo(Vector3 other)](#compareTo-com.aspose.threed.Vector3-) | Vergelijk de huidige vector met een ander exemplaar. |
| [copyFrom(Vector3 src)](#copyFrom-com.aspose.threed.Vector3-) |  |
| [cos()](#cos--) | Berekent de cosinus voor elk component |
| [create(Vector3 v)](#create-com.aspose.threed.Vector3-) | Expliciete conversie‑operator om Vector3 te casten naar FVector3 |
| [cross(Vector3 rhs)](#cross-com.aspose.threed.Vector3-) | Kruisproduct van twee vectoren |
| [div(Vector3 lhs, Vector3 rhs)](#div-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Operatoroverbelasting voor / |
| [div(Vector3 lhs, double rhs)](#div-com.aspose.threed.Vector3-double-) | Operatoroverbelasting voor / |
| [dot(Vector3 rhs)](#dot-com.aspose.threed.Vector3-) | Haalt het inproduct van twee vectoren op. |
| [equals(Object obj)](#equals-java.lang.Object-) | Controleer of twee vector3 gelijk zijn |
| [get(int idx)](#get-int-) | Haalt de component van de vector op op basis van index. |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Haalt de lengte van deze vector op. |
| [getLength2()](#getLength2--) | Haalt het kwadraat van de lengte op. |
| [getOne()](#getOne--) | Haalt eenheidsvector (1, 1, 1) op |
| [getUnitX()](#getUnitX--) | Haalt eenheidsvector (1, 0, 0) op |
| [getUnitY()](#getUnitY--) | Haalt eenheidsvector (0, 1, 0) op |
| [getUnitZ()](#getUnitZ--) | Haalt eenheidsvector (0, 0, 1) op |
| [getZero()](#getZero--) | Haalt eenheidsvector (0, 0, 0) op |
| [hashCode()](#hashCode--) | Haalt de hashcode van Vector3 op |
| [mul(Vector3 lhs, Vector3 rhs)](#mul-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Operatoroverbelasting voor \* |
| [mul(Vector3 lhs, double rhs)](#mul-com.aspose.threed.Vector3-double-) | Operatoroverbelasting voor \* |
| [mul(double lhs, Vector3 rhs)](#mul-double-com.aspose.threed.Vector3-) | Operatoroverbelasting voor \* |
| [negative(Vector3 v)](#negative-com.aspose.threed.Vector3-) | Operatoroverbelasting voor - |
| [normalize()](#normalize--) | Normaliseert deze instantie. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(Vector3 lhs, Vector3 rhs)](#op-eq-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Gelijke operator voor Vector3 |
| [op_ne(Vector3 lhs, Vector3 rhs)](#op-ne-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Niet-gelijke operator voor Vector3 |
| [set(double newX, double newY, double newZ)](#set-double-double-double-) | Stelt de x/y/z-component in één oproep in. |
| [set(int idx, double value)](#set-int-double-) | Stelt de component van de vector in op index. |
| [sin()](#sin--) | Berekent de sinus van elke component |
| [sub(Vector3 lhs, Vector3 rhs)](#sub-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Operatoroverbelasting voor - (minus) |
| [toString()](#toString--) | Retourneert een java.lang.String die de huidige [Vector3](../../com.aspose.threed/vector3) vertegenwoordigt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Vector3(double x, double y, double z) {#Vector3-double-double-double-}
```
public Vector3(double x, double y, double z)
```


Initialiseert een nieuw exemplaar van de [Vector3](../../com.aspose.threed/vector3) struct.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | double | De x-coördinaat. |
| y | double | De y-coördinaat. |
| z | double | De z-coördinaat. |

### Vector3(FVector3 vec) {#Vector3-com.aspose.threed.FVector3-}
```
public Vector3(FVector3 vec)
```


Initialiseert een nieuw exemplaar van de [Vector3](../../com.aspose.threed/vector3) struct.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| vec | [FVector3](../../com.aspose.threed/fvector3) | De x-coördinaat. |

### Vector3(double v) {#Vector3-double-}
```
public Vector3(double v)
```


Initialiseert een nieuw exemplaar van de [Vector3](../../com.aspose.threed/vector3) struct.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| v | double | V. |

### Vector3(Vector4 vec4) {#Vector3-com.aspose.threed.Vector4-}
```
public Vector3(Vector4 vec4)
```


Initialiseert een nieuw exemplaar van de [Vector3](../../com.aspose.threed/vector3) struct.

**Parameters:**
| Parameter | Type | Beschrijving |
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


De x-component.

### y {#y}
```
public double y
```


De y-component.

### z {#z}
```
public double z
```


De z-component.

### add(Vector3 lhs, Vector3 rhs) {#add-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 add(Vector3 lhs, Vector3 rhs)
```


Operatoroverbelasting voor +

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | De linker vector |
| rhs | [Vector3](../../com.aspose.threed/vector3) | De rechter vector |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### angleBetween(Vector3 dir) {#angleBetween-com.aspose.threed.Vector3-}
```
public double angleBetween(Vector3 dir)
```


Bereken de binnenhoek tussen twee richtingen. Twee richtingen kunnen niet-genormaliseerde vectoren zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dir | [Vector3](../../com.aspose.threed/vector3) | De richtingsvector om mee te vergelijken |

**Returns:**
double - binnenhoek in radialen
### angleBetween(Vector3 dir, Vector3 up) {#angleBetween-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public double angleBetween(Vector3 dir, Vector3 up)
```


Bereken de binnenhoek tussen twee richtingen. Twee richtingen kunnen niet-genormaliseerde vectoren zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dir | [Vector3](../../com.aspose.threed/vector3) | De richtingsvector om mee te vergelijken |
| up | [Vector3](../../com.aspose.threed/vector3) | De up-vector van het gedeelde vlak van de twee richtingen |

**Returns:**
double - binnenhoek in radialen
### clone() {#clone--}
```
public Vector3 clone()
```


Kloon huidige instantie

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### compareTo(Vector3 other) {#compareTo-com.aspose.threed.Vector3-}
```
public int compareTo(Vector3 other)
```


Vergelijk de huidige vector met een ander exemplaar.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
int
### copyFrom(Vector3 src) {#copyFrom-com.aspose.threed.Vector3-}
```
public void copyFrom(Vector3 src)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| src | [Vector3](../../com.aspose.threed/vector3) |  |

### cos() {#cos--}
```
public Vector3 cos()
```


Berekent de cosinus voor elk component

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Calculated [Vector3](../../com.aspose.threed/vector3).
### create(Vector3 v) {#create-com.aspose.threed.Vector3-}
```
public static FVector3 create(Vector3 v)
```


Expliciete conversie‑operator om Vector3 te casten naar FVector3

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### cross(Vector3 rhs) {#cross-com.aspose.threed.Vector3-}
```
public Vector3 cross(Vector3 rhs)
```


Kruisproduct van twee vectoren

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Right hand side value. |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Cross product of two [Vector3](../../com.aspose.threed/vector3)s.
### div(Vector3 lhs, Vector3 rhs) {#div-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 div(Vector3 lhs, Vector3 rhs)
```


Operatoroverbelasting voor /

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | De linker vector |
| rhs | [Vector3](../../com.aspose.threed/vector3) | De rechter vector |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### div(Vector3 lhs, double rhs) {#div-com.aspose.threed.Vector3-double-}
```
public static Vector3 div(Vector3 lhs, double rhs)
```


Operatoroverbelasting voor /

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | De linker vector |
| rhs | double | The right double value |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### dot(Vector3 rhs) {#dot-com.aspose.threed.Vector3-}
```
public double dot(Vector3 rhs)
```


Haalt het inproduct van twee vectoren op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Right hand side value. |

**Returns:**
double - The dot product of the two vectors.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Controleer of twee vector3 gelijk zijn

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | The object to check equality. |

**Returns:**
boolean - True if all components are identically equal.
### get(int idx) {#get-int-}
```
public double get(int idx)
```


Haalt de component van de vector op op basis van index.

**Parameters:**
| Parameter | Type | Beschrijving |
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


Haalt de lengte van deze vector op.

**Returns:**
double - the length of this vector.
### getLength2() {#getLength2--}
```
public double getLength2()
```


Haalt het kwadraat van de lengte op.

**Returns:**
double - the square of the length.
### getOne() {#getOne--}
```
public static Vector3 getOne()
```


Haalt eenheidsvector (1, 1, 1) op

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (1, 1, 1)
### getUnitX() {#getUnitX--}
```
public static Vector3 getUnitX()
```


Haalt eenheidsvector (1, 0, 0) op

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (1, 0, 0)
### getUnitY() {#getUnitY--}
```
public static Vector3 getUnitY()
```


Haalt eenheidsvector (0, 1, 0) op

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (0, 1, 0)
### getUnitZ() {#getUnitZ--}
```
public static Vector3 getUnitZ()
```


Haalt eenheidsvector (0, 0, 1) op

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (0, 0, 1)
### getZero() {#getZero--}
```
public static Vector3 getZero()
```


Haalt eenheidsvector (0, 0, 0) op

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (0, 0, 0)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Haalt de hashcode van Vector3 op

**Returns:**
int - The hash code of the [Vector3](../../com.aspose.threed/vector3)
### mul(Vector3 lhs, Vector3 rhs) {#mul-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 mul(Vector3 lhs, Vector3 rhs)
```


Operatoroverbelasting voor \*

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | De linker vector |
| rhs | [Vector3](../../com.aspose.threed/vector3) | De rechter vector |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### mul(Vector3 lhs, double rhs) {#mul-com.aspose.threed.Vector3-double-}
```
public static Vector3 mul(Vector3 lhs, double rhs)
```


Operatoroverbelasting voor \*

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | De linker vector |
| rhs | double | The right double value |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### mul(double lhs, Vector3 rhs) {#mul-double-com.aspose.threed.Vector3-}
```
public static Vector3 mul(double lhs, Vector3 rhs)
```


Operatoroverbelasting voor \*

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs | double | The left scalar |
| rhs | [Vector3](../../com.aspose.threed/vector3) | De rechter vector |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### negative(Vector3 v) {#negative-com.aspose.threed.Vector3-}
```
public static Vector3 negative(Vector3 v)
```


Operatoroverbelasting voor -

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) | The origin vector |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### normalize() {#normalize--}
```
public Vector3 normalize()
```


Normaliseert deze instantie.

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


Gelijke operator voor Vector3

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Left hand side value. |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Right hand side value. |

**Returns:**
boolean - True if all components are identically equal.
### op_ne(Vector3 lhs, Vector3 rhs) {#op-ne-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static boolean op_ne(Vector3 lhs, Vector3 rhs)
```


Niet-gelijke operator voor Vector3

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Left hand side value. |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Right hand side value. |

**Returns:**
boolean - True if two vectors are not equal.
### set(double newX, double newY, double newZ) {#set-double-double-double-}
```
public void set(double newX, double newY, double newZ)
```


Stelt de x/y/z-component in één oproep in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newX | double | De x-component. |
| newY | double | De y-component. |
| newZ | double | De z-component. |

### set(int idx, double value) {#set-int-double-}
```
public void set(int idx, double value)
```


Stelt de component van de vector in op index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| idx | int |  |
| waarde | double | Nieuwe waarde |

### sin() {#sin--}
```
public Vector3 sin()
```


Berekent de sinus van elke component

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Calculated [Vector3](../../com.aspose.threed/vector3).
### sub(Vector3 lhs, Vector3 rhs) {#sub-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 sub(Vector3 lhs, Vector3 rhs)
```


Operatoroverbelasting voor - (minus)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | De linker vector |
| rhs | [Vector3](../../com.aspose.threed/vector3) | De rechter vector |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### toString() {#toString--}
```
public String toString()
```


Retourneert een java.lang.String die de huidige [Vector3](../../com.aspose.threed/vector3) vertegenwoordigt.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

