---
title: Vector2
second_title: Aspose.3D for Java API-referentie
description: Een vector met twee componenten.
type: docs
weight: 201
url: /nl/java/com.aspose.threed/vector2/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.threed.Struct, java.io.Serializable
```
public final class Vector2 implements Comparable<Vector2>, Struct<Vector2>, Serializable
```

Een vector met twee componenten.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Vector2(double s)](#Vector2-double-) | Initialiseert een nieuw exemplaar van de struct [Vector2](../../com.aspose.threed/vector2). |
| [Vector2(Vector3 s)](#Vector2-com.aspose.threed.Vector3-) | Initialiseert een nieuw exemplaar van de struct [Vector2](../../com.aspose.threed/vector2). |
| [Vector2(FVector2 vec)](#Vector2-com.aspose.threed.FVector2-) | Initialiseert een nieuw exemplaar van de struct [Vector2](../../com.aspose.threed/vector2). |
| [Vector2(double x, double y)](#Vector2-double-double-) | Initialiseert een nieuw exemplaar van de struct [Vector2](../../com.aspose.threed/vector2). |
| [Vector2()](#Vector2--) |  |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [x](#x) | De x-component. |
| [y](#y) | De y-component. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [add(Vector2 lhs, Vector2 rhs)](#add-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Additie-operator voor Vector2 |
| [clone()](#clone--) |  |
| [compareTo(Vector2 other)](#compareTo-com.aspose.threed.Vector2-) | Vergelijk de huidige vector met een ander exemplaar. |
| [copyFrom(Vector2 src)](#copyFrom-com.aspose.threed.Vector2-) |  |
| [create(Vector2 v)](#create-com.aspose.threed.Vector2-) | Expliciete conversie-operator om Vector2 naar FVector2 te casten. |
| [cross(Vector2 v)](#cross-com.aspose.threed.Vector2-) | Kruisproduct van twee vectoren |
| [div(Vector2 lhs, double rhs)](#div-com.aspose.threed.Vector2-double-) | Delingsoperator voor Vector2. |
| [dot(Vector2 rhs)](#dot-com.aspose.threed.Vector2-) | Haalt het inproduct van twee vectoren op. |
| [equals(Vector2 rhs)](#equals-com.aspose.threed.Vector2-) | Controleer of twee vector2 gelijk zijn. |
| [equals(Object obj)](#equals-java.lang.Object-) | Controleer of twee vector2 gelijk zijn. |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Geeft de lengte terug. |
| [getU()](#getU--) | Haalt de U-component op als de [Vector2](../../com.aspose.threed/vector2) wordt gebruikt als een mapping-coördinaat. |
| [getV()](#getV--) | Haalt de V-component op als de [Vector2](../../com.aspose.threed/vector2) wordt gebruikt als een mapping-coördinaat. |
| [hashCode()](#hashCode--) | Geeft de hashcode van Vector2 terug. |
| [mul(Vector2 lhs, double rhs)](#mul-com.aspose.threed.Vector2-double-) | Multiplicatie-operator voor Vector2. |
| [mul(double lhs, Vector2 rhs)](#mul-double-com.aspose.threed.Vector2-) | Multiplicatie-operator voor Vector2. |
| [normalize()](#normalize--) | Normaliseert deze instantie. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(Vector2 lhs, Vector2 rhs)](#op-eq-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Gelijkheidsoperator voor Vector2 |
| [op_ne(Vector2 lhs, Vector2 rhs)](#op-ne-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Niet-gelijkheidsoperator voor Vector2 |
| [setU(double value)](#setU-double-) | Stelt de U-component in als de [Vector2](../../com.aspose.threed/vector2) wordt gebruikt als een mappingcoördinaat. |
| [setV(double value)](#setV-double-) | Stelt de V-component in als de [Vector2](../../com.aspose.threed/vector2) wordt gebruikt als een mappingcoördinaat. |
| [sub(Vector2 lhs, Vector2 rhs)](#sub-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Aftrekkingsoperator voor Vector2 |
| [toString()](#toString--) | Retourneert een java.lang.String die de huidige [Vector2](../../com.aspose.threed/vector2) vertegenwoordigt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Vector2(double s) {#Vector2-double-}
```
public Vector2(double s)
```


Initialiseert een nieuw exemplaar van de struct [Vector2](../../com.aspose.threed/vector2).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| s | double | S. |

### Vector2(Vector3 s) {#Vector2-com.aspose.threed.Vector3-}
```
public Vector2(Vector3 s)
```


Initialiseert een nieuw exemplaar van de struct [Vector2](../../com.aspose.threed/vector2).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| s | [Vector3](../../com.aspose.threed/vector3) | S. |

### Vector2(FVector2 vec) {#Vector2-com.aspose.threed.FVector2-}
```
public Vector2(FVector2 vec)
```


Initialiseert een nieuw exemplaar van de struct [Vector2](../../com.aspose.threed/vector2).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| vec | [FVector2](../../com.aspose.threed/fvector2) | Vector in float. |

### Vector2(double x, double y) {#Vector2-double-double-}
```
public Vector2(double x, double y)
```


Initialiseert een nieuw exemplaar van de struct [Vector2](../../com.aspose.threed/vector2).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | double | De x-coördinaat. |
| y | double | De y-coördinaat. |

### Vector2() {#Vector2--}
```
public Vector2()
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

### add(Vector2 lhs, Vector2 rhs) {#add-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static Vector2 add(Vector2 lhs, Vector2 rhs)
```


Additie-operator voor Vector2

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Left hand side value. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Right hand side value. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of addition.
### clone() {#clone--}
```
public Vector2 clone()
```


Kloon huidige instantie

**Returns:**
[Vector2](../../com.aspose.threed/vector2)
### compareTo(Vector2 other) {#compareTo-com.aspose.threed.Vector2-}
```
public int compareTo(Vector2 other)
```


Vergelijk de huidige vector met een ander exemplaar.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
int
### copyFrom(Vector2 src) {#copyFrom-com.aspose.threed.Vector2-}
```
public void copyFrom(Vector2 src)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| src | [Vector2](../../com.aspose.threed/vector2) |  |

### create(Vector2 v) {#create-com.aspose.threed.Vector2-}
```
public static FVector2 create(Vector2 v)
```


Expliciete conversie-operator om Vector2 naar FVector2 te casten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| v | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2)
### cross(Vector2 v) {#cross-com.aspose.threed.Vector2-}
```
public double cross(Vector2 v)
```


Kruisproduct van twee vectoren

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| v | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
double
### div(Vector2 lhs, double rhs) {#div-com.aspose.threed.Vector2-double-}
```
public static Vector2 div(Vector2 lhs, double rhs)
```


Delingsoperator voor Vector2.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Left hand side value. |
| rhs | double | Right hand side value. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of division.
### dot(Vector2 rhs) {#dot-com.aspose.threed.Vector2-}
```
public double dot(Vector2 rhs)
```


Haalt het inproduct van twee vectoren op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Right hand side value. |

**Returns:**
double - The dot product of the two vectors.
### equals(Vector2 rhs) {#equals-com.aspose.threed.Vector2-}
```
public boolean equals(Vector2 rhs)
```


Controleer of twee vector2 gelijk zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rhs | [Vector2](../../com.aspose.threed/vector2) | De waarde van de rechterkant. |

**Returns:**
boolean - True if all components are identically equal.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Controleer of twee vector2 gelijk zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Het object om te vergelijken. |

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


Geeft de lengte terug.

**Returns:**
double - de lengte.
### getU() {#getU--}
```
public double getU()
```


Haalt de U-component op als de [Vector2](../../com.aspose.threed/vector2) wordt gebruikt als een mappingcoördinaat. Het is een alias van de x-component.

**Returns:**
double - de U-component als de [Vector2](../../com.aspose.threed/vector2) wordt gebruikt als een mappingcoördinaat. Het is een alias van de x-component.
### getV() {#getV--}
```
public double getV()
```


Haalt de V-component op als de [Vector2](../../com.aspose.threed/vector2) wordt gebruikt als een mappingcoördinaat. Het is een alias van de y-component.

**Returns:**
double - de V-component als de [Vector2](../../com.aspose.threed/vector2) wordt gebruikt als een mappingcoördinaat. Het is een alias van de y-component.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Geeft de hashcode van Vector2 terug.

**Returns:**
int - De hashcode van de [Vector2](../../com.aspose.threed/vector2)
### mul(Vector2 lhs, double rhs) {#mul-com.aspose.threed.Vector2-double-}
```
public static Vector2 mul(Vector2 lhs, double rhs)
```


Multiplicatie-operator voor Vector2.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Left hand side value. |
| rhs | double | Right hand side value. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of multiply.
### mul(double lhs, Vector2 rhs) {#mul-double-com.aspose.threed.Vector2-}
```
public static Vector2 mul(double lhs, Vector2 rhs)
```


Multiplicatie-operator voor Vector2.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs | double | Left hand side value. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Right hand side value. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of multiply.
### normalize() {#normalize--}
```
public Vector2 normalize()
```


Normaliseert deze instantie.

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


Gelijkheidsoperator voor Vector2

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Left hand side value. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Right hand side value. |

**Returns:**
boolean - True if all components are identically equal.
### op_ne(Vector2 lhs, Vector2 rhs) {#op-ne-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static boolean op_ne(Vector2 lhs, Vector2 rhs)
```


Niet-gelijkheidsoperator voor Vector2

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Left hand side value. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Right hand side value. |

**Returns:**
boolean - True if two vectors are not equal.
### setU(double value) {#setU-double-}
```
public void setU(double value)
```


Stelt de U-component in als de [Vector2](../../com.aspose.threed/vector2) wordt gebruikt als een mappingcoördinaat. Het is een alias van de x-component.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

### setV(double value) {#setV-double-}
```
public void setV(double value)
```


Stelt de V-component in als de [Vector2](../../com.aspose.threed/vector2) wordt gebruikt als een mappingcoördinaat. Het is een alias van de y-component.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

### sub(Vector2 lhs, Vector2 rhs) {#sub-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static Vector2 sub(Vector2 lhs, Vector2 rhs)
```


Aftrekkingsoperator voor Vector2

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Left hand side value. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Right hand side value. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of substraction.
### toString() {#toString--}
```
public String toString()
```


Retourneert een java.lang.String die de huidige [Vector2](../../com.aspose.threed/vector2) vertegenwoordigt.

**Returns:**
java.lang.String - Een java.lang.String die de huidige [Vector2](../../com.aspose.threed/vector2) vertegenwoordigt.
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

