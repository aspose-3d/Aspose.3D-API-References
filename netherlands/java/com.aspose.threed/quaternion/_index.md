---
title: Quaternion
second_title: Aspose.3D for Java API-referentie
description: Quaternion wordt meestal gebruikt om rotatie uit te voeren in computergraphics.
type: docs
weight: 143
url: /nl/java/com.aspose.threed/quaternion/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class Quaternion implements Struct<Quaternion>, Serializable
```

Quaternion wordt meestal gebruikt om rotatie uit te voeren in computergraphics.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Quaternion(double w, double x, double y, double z)](#Quaternion-double-double-double-double-) | Initialiseert een nieuw exemplaar van de [Quaternion](../../com.aspose.threed/quaternion) klasse. |
| [Quaternion()](#Quaternion--) |  |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [IDENTITY](#IDENTITY) | De identiteitsquaternion. |
| [w](#w) | De w‑component. |
| [x](#x) | De x-component. |
| [y](#y) | De y-component. |
| [z](#z) | De z-component. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [add(Quaternion lhs, Quaternion rhs)](#add-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Operatoroverbelasting voor + |
| [clone()](#clone--) |  |
| [concat(Quaternion rhs)](#concat-com.aspose.threed.Quaternion-) | Concateneer twee quaternionen |
| [conjugate()](#conjugate--) | Retourneert een geconjugeerde quaternion van de huidige quaternion |
| [copyFrom(Quaternion src)](#copyFrom-com.aspose.threed.Quaternion-) |  |
| [div(Quaternion lhs, double rhs)](#div-com.aspose.threed.Quaternion-double-) | Operatoroverbelasting voor / |
| [dot(Quaternion q)](#dot-com.aspose.threed.Quaternion-) | Dotproduct |
| [equals(Object obj)](#equals-java.lang.Object-) | Controleer of twee quaternionen gelijk zijn |
| [eulerAngles()](#eulerAngles--) | Converteert een quaternion naar een rotatie weergegeven door Euler-hoeken. Alle componenten zijn in radialen. |
| [fromAngleAxis(double a, Vector3 axis)](#fromAngleAxis-double-com.aspose.threed.Vector3-) | Maakt een quaternion rond een gegeven as en roteert met de klok mee |
| [fromEulerAngle(Vector3 eulerAngle)](#fromEulerAngle-com.aspose.threed.Vector3-) | Maakt een quaternion van een gegeven Euler-hoek |
| [fromEulerAngle(double pitch, double yaw, double roll)](#fromEulerAngle-double-double-double-) | Maakt een quaternion van een gegeven Euler-hoek |
| [fromRotation(Vector3 orig, Vector3 dest)](#fromRotation-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Maakt een quaternion die roteert van de oorspronkelijke naar de doelrichting |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Berekent de lengte van de quaternion |
| [hashCode()](#hashCode--) | Berekent de hashcode van de Quaternion |
| [interpolate(float t, Quaternion from, Quaternion to)](#interpolate-float-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Vult deze quaternion met de geïnterpoleerde waarde tussen de gegeven quaternion-argumenten voor een t tussen van en tot. |
| [inverse()](#inverse--) | Retourneert een inverse quaternion van de huidige quaternion |
| [mul(Quaternion lhs, Quaternion rhs)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Operatoroverbelasting voor \* |
| [mul(Quaternion q, Vector3 v)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector3-) | Operatoroverbelasting voor \* |
| [mul(Quaternion q, Vector4 v)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector4-) | Operatoroverbelasting voor \* |
| [mul(Quaternion lhs, double rhs)](#mul-com.aspose.threed.Quaternion-double-) | Operatoroverbelasting voor \* |
| [mul(Vector3 v, Quaternion q)](#mul-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-) | Operatoroverbelasting voor \* |
| [normalize()](#normalize--) | Normaliseer de quaternion |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(Quaternion lhs, Quaternion rhs)](#op-eq-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Gelijkheidsoperator voor quaternion |
| [op_ne(Quaternion lhs, Quaternion rhs)](#op-ne-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Niet-gelijkheidsoperator voor quaternion |
| [slerp(double t, Quaternion v1, Quaternion v2)](#slerp-double-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Voer sferische lineaire interpolatie uit tussen twee waarden |
| [toAngleAxis(double[] angle, Vector3 axis)](#toAngleAxis-double---com.aspose.threed.Vector3-) | Decomposeer de quaternion in hoek en as |
| [toMatrix()](#toMatrix--) | Converteer de door quaternion gepresenteerde rotatie naar een transformatiematrix. |
| [toMatrix(Vector3 translation)](#toMatrix-com.aspose.threed.Vector3-) | Converteer de door quaternion gepresenteerde rotatie naar een transformatiematrix. |
| [toString()](#toString--) | Berekent de weergave van de quaternion als string |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Quaternion(double w, double x, double y, double z) {#Quaternion-double-double-double-double-}
```
public Quaternion(double w, double x, double y, double z)
```


Initialiseert een nieuw exemplaar van de [Quaternion](../../com.aspose.threed/quaternion) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| w | double | w component van het quaternion |
| x | double | x component van het quaternion |
| y | double | y component van het quaternion |
| z | double | z component van het quaternion |

### Quaternion() {#Quaternion--}
```
public Quaternion()
```


### IDENTITY {#IDENTITY}
```
public static final Quaternion IDENTITY
```


De identiteitsquaternion.

### w {#w}
```
public double w
```


De w‑component.

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

### add(Quaternion lhs, Quaternion rhs) {#add-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion add(Quaternion lhs, Quaternion rhs)
```


Operatoroverbelasting voor +

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Linker quaternion |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Rechter quaternion |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### clone() {#clone--}
```
public Quaternion clone()
```


Kloon huidige instantie

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### concat(Quaternion rhs) {#concat-com.aspose.threed.Quaternion-}
```
public Quaternion concat(Quaternion rhs)
```


Concateneer twee quaternionen

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) |  |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### conjugate() {#conjugate--}
```
public Quaternion conjugate()
```


Retourneert een geconjugeerde quaternion van de huidige quaternion

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - The conjugate quaternion.
### copyFrom(Quaternion src) {#copyFrom-com.aspose.threed.Quaternion-}
```
public void copyFrom(Quaternion src)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| src | [Quaternion](../../com.aspose.threed/quaternion) |  |

### div(Quaternion lhs, double rhs) {#div-com.aspose.threed.Quaternion-double-}
```
public static Quaternion div(Quaternion lhs, double rhs)
```


Operatoroverbelasting voor /

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Linker quaternion |
| rhs | double | Rechter quaternion |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### dot(Quaternion q) {#dot-com.aspose.threed.Quaternion-}
```
public double dot(Quaternion q)
```


Dotproduct

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | Het quaternion |

**Returns:**
double - Dot‑waarde
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Controleer of twee quaternionen gelijk zijn

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | The object to check equality. |

**Returns:**
boolean - True if all components are identically equal.
### eulerAngles() {#eulerAngles--}
```
public Vector3 eulerAngles()
```


Converteert een quaternion naar een rotatie weergegeven door Euler-hoeken. Alle componenten zijn in radialen.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### fromAngleAxis(double a, Vector3 axis) {#fromAngleAxis-double-com.aspose.threed.Vector3-}
```
public static Quaternion fromAngleAxis(double a, Vector3 axis)
```


Maakt een quaternion rond een gegeven as en roteert met de klok mee

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | double | Kloksgewijze rotatie in radialen |
| axis | [Vector3](../../com.aspose.threed/vector3) | As |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromEulerAngle(Vector3 eulerAngle) {#fromEulerAngle-com.aspose.threed.Vector3-}
```
public static Quaternion fromEulerAngle(Vector3 eulerAngle)
```


Maakt een quaternion van een gegeven Euler-hoek

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eulerAngle | [Vector3](../../com.aspose.threed/vector3) | Eulerhoek in radialen |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromEulerAngle(double pitch, double yaw, double roll) {#fromEulerAngle-double-double-double-}
```
public static Quaternion fromEulerAngle(double pitch, double yaw, double roll)
```


Maakt een quaternion van een gegeven Euler-hoek

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pitch | double | Pitch in radialen |
| yaw | double | Yaw in radialen |
| roll | double | Roll in radialen |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromRotation(Vector3 orig, Vector3 dest) {#fromRotation-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Quaternion fromRotation(Vector3 orig, Vector3 dest)
```


Maakt een quaternion die roteert van de oorspronkelijke naar de doelrichting

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| orig | [Vector3](../../com.aspose.threed/vector3) | Oorspronkelijke richting |
| dest | [Vector3](../../com.aspose.threed/vector3) | Bestemmingsrichting |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
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


Berekent de lengte van de quaternion

**Returns:**
double - de lengte van het quaternion
### hashCode() {#hashCode--}
```
public int hashCode()
```


Berekent de hashcode van de Quaternion

**Returns:**
int - De hashcode van de [Quaternion](../../com.aspose.threed/quaternion)
### interpolate(float t, Quaternion from, Quaternion to) {#interpolate-float-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion interpolate(float t, Quaternion from, Quaternion to)
```


Vult deze quaternion met de geïnterpoleerde waarde tussen de gegeven quaternion-argumenten voor een t tussen van en tot.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| t | float | De coëfficiënt om te interpoleren. |
| from | [Quaternion](../../com.aspose.threed/quaternion) | Bron quaternion. |
| to | [Quaternion](../../com.aspose.threed/quaternion) | Doel quaternion. |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - The interpolated quaternion.
### inverse() {#inverse--}
```
public Quaternion inverse()
```


Retourneert een inverse quaternion van de huidige quaternion

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Inverse quaternion.
### mul(Quaternion lhs, Quaternion rhs) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion mul(Quaternion lhs, Quaternion rhs)
```


Operatoroverbelasting voor \*

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Linker quaternion |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Rechter quaternion |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### mul(Quaternion q, Vector3 v) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector3-}
```
public static Vector3 mul(Quaternion q, Vector3 v)
```


Operatoroverbelasting voor \*

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | Het rotatiequaternion |
| v | [Vector3](../../com.aspose.threed/vector3) | Vector om te roteren |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Rotated vector
### mul(Quaternion q, Vector4 v) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector4-}
```
public static Vector4 mul(Quaternion q, Vector4 v)
```


Operatoroverbelasting voor \*

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | Het rotatiequaternion |
| v | [Vector4](../../com.aspose.threed/vector4) | Vector om te roteren |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Rotated vector
### mul(Quaternion lhs, double rhs) {#mul-com.aspose.threed.Quaternion-double-}
```
public static Quaternion mul(Quaternion lhs, double rhs)
```


Operatoroverbelasting voor \*

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Linker quaternion |
| rhs | double | Rechter quaternion |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### mul(Vector3 v, Quaternion q) {#mul-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-}
```
public static Vector3 mul(Vector3 v, Quaternion q)
```


Operatoroverbelasting voor \*

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) | Het rotatiequaternion |
| q | [Quaternion](../../com.aspose.threed/quaternion) | Vector om te roteren |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Rotated vector
### normalize() {#normalize--}
```
public Quaternion normalize()
```


Normaliseer de quaternion

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Normalized quaternion.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_eq(Quaternion lhs, Quaternion rhs) {#op-eq-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static boolean op_eq(Quaternion lhs, Quaternion rhs)
```


Gelijkheidsoperator voor quaternion

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Left hand side value. |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Right hand side value. |

**Returns:**
boolean - True if all components are identically equal.
### op_ne(Quaternion lhs, Quaternion rhs) {#op-ne-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static boolean op_ne(Quaternion lhs, Quaternion rhs)
```


Niet-gelijkheidsoperator voor quaternion

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Left hand side value. |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Right hand side value. |

**Returns:**
boolean - Waar als twee quaternionen niet gelijk zijn.
### slerp(double t, Quaternion v1, Quaternion v2) {#slerp-double-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion slerp(double t, Quaternion v1, Quaternion v2)
```


Voer sferische lineaire interpolatie uit tussen twee waarden

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| t | double | t is tussen 0 en 1 |
| v1 | [Quaternion](../../com.aspose.threed/quaternion) | Eerste waarde |
| v2 | [Quaternion](../../com.aspose.threed/quaternion) | Tweede waarde |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### toAngleAxis(double[] angle, Vector3 axis) {#toAngleAxis-double---com.aspose.threed.Vector3-}
```
public void toAngleAxis(double[] angle, Vector3 axis)
```


Decomposeer de quaternion in hoek en as

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| angle | double[] | De hoek om te roteren, in radialen. |
| axis | [Vector3](../../com.aspose.threed/vector3) | De as waaromheen wordt geroteerd. |

### toMatrix() {#toMatrix--}
```
public Matrix4 toMatrix()
```


Converteer de door quaternion gepresenteerde rotatie naar een transformatiematrix.

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - The matrix representation of current quaternion.
### toMatrix(Vector3 translation) {#toMatrix-com.aspose.threed.Vector3-}
```
public Matrix4 toMatrix(Vector3 translation)
```


Converteer de door quaternion gepresenteerde rotatie naar een transformatiematrix.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| translation | [Vector3](../../com.aspose.threed/vector3) | Het translatiedeel van de matrix. |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - The matrix representation of current quaternion.
### toString() {#toString--}
```
public String toString()
```


Berekent de weergave van de quaternion als string

**Returns:**
java.lang.String - Objecttekenreeks
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

