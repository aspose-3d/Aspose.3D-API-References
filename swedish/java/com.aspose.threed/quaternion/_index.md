---
title: Kvaternion
second_title: Aspose.3D for Java API-referens
description: Kvaternion används vanligtvis för att utföra rotation i datorgrafik.
type: docs
weight: 143
url: /sv/java/com.aspose.threed/quaternion/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class Quaternion implements Struct<Quaternion>, Serializable
```

Kvaternion används vanligtvis för att utföra rotation i datorgrafik.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Quaternion(double w, double x, double y, double z)](#Quaternion-double-double-double-double-) | Initierar en ny instans av klassen [Quaternion](../../com.aspose.threed/quaternion). |
| [Quaternion()](#Quaternion--) |  |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [IDENTITY](#IDENTITY) | Identitetskvaternionen. |
| [w](#w) | w-komponenten. |
| [x](#x) | x-komponenten. |
| [y](#y) | y-komponenten. |
| [z](#z) | z-komponenten. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add(Quaternion lhs, Quaternion rhs)](#add-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Operatoröverladdning för + |
| [clone()](#clone--) |  |
| [concat(Quaternion rhs)](#concat-com.aspose.threed.Quaternion-) | Konkatenera två kvaternioner |
| [conjugate()](#conjugate--) | Returnerar en konjugerad kvaternion av den aktuella kvaternionen |
| [copyFrom(Quaternion src)](#copyFrom-com.aspose.threed.Quaternion-) |  |
| [div(Quaternion lhs, double rhs)](#div-com.aspose.threed.Quaternion-double-) | Operatoröverladdning för / |
| [dot(Quaternion q)](#dot-com.aspose.threed.Quaternion-) | Punktprodukt |
| [equals(Object obj)](#equals-java.lang.Object-) | Kontrollera om två kvaternioner är lika |
| [eulerAngles()](#eulerAngles--) | Konverterar kvaternion till rotation representerad av Euler-vinklar. Alla komponenter är i radianer. |
| [fromAngleAxis(double a, Vector3 axis)](#fromAngleAxis-double-com.aspose.threed.Vector3-) | Skapar en kvaternion kring given axel och roterar medurs |
| [fromEulerAngle(Vector3 eulerAngle)](#fromEulerAngle-com.aspose.threed.Vector3-) | Skapar en kvaternion från given Euler-vinkel |
| [fromEulerAngle(double pitch, double yaw, double roll)](#fromEulerAngle-double-double-double-) | Skapar en kvaternion från given Euler-vinkel |
| [fromRotation(Vector3 orig, Vector3 dest)](#fromRotation-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Skapar en kvaternion som roterar från ursprunglig till destinationsriktning |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Hämtar längden på kvaternionen |
| [hashCode()](#hashCode--) | Hämtar hashkoden för Quaternion |
| [interpolate(float t, Quaternion from, Quaternion to)](#interpolate-float-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Fyller i denna kvaternion med det interpolerade värdet mellan de givna kvaternionargumenten för ett t mellan från och till. |
| [inverse()](#inverse--) | Returnerar en invers kvaternion av den aktuella kvaternionen |
| [mul(Quaternion lhs, Quaternion rhs)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Operatoröverladdning för \* |
| [mul(Quaternion q, Vector3 v)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector3-) | Operatoröverladdning för \* |
| [mul(Quaternion q, Vector4 v)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector4-) | Operatoröverladdning för \* |
| [mul(Quaternion lhs, double rhs)](#mul-com.aspose.threed.Quaternion-double-) | Operatoröverladdning för \* |
| [mul(Vector3 v, Quaternion q)](#mul-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-) | Operatoröverladdning för \* |
| [normalize()](#normalize--) | Normalisera kvaternionen |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(Quaternion lhs, Quaternion rhs)](#op-eq-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Likhetsoperator för kvaternion |
| [op_ne(Quaternion lhs, Quaternion rhs)](#op-ne-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Icke-likhetsoperator för kvaternion |
| [slerp(double t, Quaternion v1, Quaternion v2)](#slerp-double-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Utför sfärisk linjär interpolation mellan två värden |
| [toAngleAxis(double[] angle, Vector3 axis)](#toAngleAxis-double---com.aspose.threed.Vector3-) | Decomponera kvaternionen till vinkel och axel |
| [toMatrix()](#toMatrix--) | Konvertera rotationen som presenteras av kvaternionen till en transformmatris. |
| [toMatrix(Vector3 translation)](#toMatrix-com.aspose.threed.Vector3-) | Konvertera rotationen som presenteras av kvaternionen till en transformmatris. |
| [toString()](#toString--) | Hämtar representationen av kvaternionen som sträng |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Quaternion(double w, double x, double y, double z) {#Quaternion-double-double-double-double-}
```
public Quaternion(double w, double x, double y, double z)
```


Initierar en ny instans av klassen [Quaternion](../../com.aspose.threed/quaternion).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| w | double | w-komponent i kvaternionen |
| x | double | x-komponent i kvaternionen |
| y | double | y-komponent i kvaternionen |
| z | double | z-komponent i kvaternionen |

### Quaternion() {#Quaternion--}
```
public Quaternion()
```


### IDENTITY {#IDENTITY}
```
public static final Quaternion IDENTITY
```


Identitetskvaternionen.

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

### add(Quaternion lhs, Quaternion rhs) {#add-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion add(Quaternion lhs, Quaternion rhs)
```


Operatoröverladdning för +

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Vänster kvaternion |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Höger kvaternion |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### clone() {#clone--}
```
public Quaternion clone()
```


Clone current instance

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### concat(Quaternion rhs) {#concat-com.aspose.threed.Quaternion-}
```
public Quaternion concat(Quaternion rhs)
```


Konkatenera två kvaternioner

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) |  |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### conjugate() {#conjugate--}
```
public Quaternion conjugate()
```


Returnerar en konjugerad kvaternion av den aktuella kvaternionen

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - The conjugate quaternion.
### copyFrom(Quaternion src) {#copyFrom-com.aspose.threed.Quaternion-}
```
public void copyFrom(Quaternion src)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| src | [Quaternion](../../com.aspose.threed/quaternion) |  |

### div(Quaternion lhs, double rhs) {#div-com.aspose.threed.Quaternion-double-}
```
public static Quaternion div(Quaternion lhs, double rhs)
```


Operatoröverladdning för /

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Vänster kvaternion |
| rhs | double | Höger kvaternion |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### dot(Quaternion q) {#dot-com.aspose.threed.Quaternion-}
```
public double dot(Quaternion q)
```


Punktprodukt

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | Kvaternionen |

**Returns:**
double - Punktvärde
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Kontrollera om två kvaternioner är lika

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | The object to check equality. |

**Returns:**
boolean - True if all components are identically equal.
### eulerAngles() {#eulerAngles--}
```
public Vector3 eulerAngles()
```


Konverterar kvaternion till rotation representerad av Euler-vinklar. Alla komponenter är i radianer.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### fromAngleAxis(double a, Vector3 axis) {#fromAngleAxis-double-com.aspose.threed.Vector3-}
```
public static Quaternion fromAngleAxis(double a, Vector3 axis)
```


Skapar en kvaternion kring given axel och roterar medurs

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | double | Medurs rotation i radian |
| axis | [Vector3](../../com.aspose.threed/vector3) | Axel |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromEulerAngle(Vector3 eulerAngle) {#fromEulerAngle-com.aspose.threed.Vector3-}
```
public static Quaternion fromEulerAngle(Vector3 eulerAngle)
```


Skapar en kvaternion från given Euler-vinkel

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| eulerAngle | [Vector3](../../com.aspose.threed/vector3) | Eulervinkel i radian |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromEulerAngle(double pitch, double yaw, double roll) {#fromEulerAngle-double-double-double-}
```
public static Quaternion fromEulerAngle(double pitch, double yaw, double roll)
```


Skapar en kvaternion från given Euler-vinkel

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nick | double | Nick i radian |
| gir | double | Gir i radian |
| rullning | double | Rullning i radian |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromRotation(Vector3 orig, Vector3 dest) {#fromRotation-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Quaternion fromRotation(Vector3 orig, Vector3 dest)
```


Skapar en kvaternion som roterar från ursprunglig till destinationsriktning

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| orig | [Vector3](../../com.aspose.threed/vector3) | Ursprunglig riktning |
| dest | [Vector3](../../com.aspose.threed/vector3) | Målriktning |

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


Hämtar längden på kvaternionen

**Returns:**
double - längden på kvaternionen
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hämtar hashkoden för Quaternion

**Returns:**
int - Hashkoden för [Quaternion](../../com.aspose.threed/quaternion)
### interpolate(float t, Quaternion from, Quaternion to) {#interpolate-float-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion interpolate(float t, Quaternion from, Quaternion to)
```


Fyller i denna kvaternion med det interpolerade värdet mellan de givna kvaternionargumenten för ett t mellan från och till.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| t | float | Koefficienten för interpolering. |
| from | [Quaternion](../../com.aspose.threed/quaternion) | Källkvaternion. |
| to | [Quaternion](../../com.aspose.threed/quaternion) | Målkvaternion. |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - The interpolated quaternion.
### inverse() {#inverse--}
```
public Quaternion inverse()
```


Returnerar en invers kvaternion av den aktuella kvaternionen

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Inverse quaternion.
### mul(Quaternion lhs, Quaternion rhs) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion mul(Quaternion lhs, Quaternion rhs)
```


Operatoröverladdning för \*

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Vänster kvaternion |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Höger kvaternion |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### mul(Quaternion q, Vector3 v) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector3-}
```
public static Vector3 mul(Quaternion q, Vector3 v)
```


Operatoröverladdning för \*

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | Rotationskvaternionen |
| v | [Vector3](../../com.aspose.threed/vector3) | Vektor att rotera |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Rotated vector
### mul(Quaternion q, Vector4 v) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector4-}
```
public static Vector4 mul(Quaternion q, Vector4 v)
```


Operatoröverladdning för \*

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | Rotationskvaternionen |
| v | [Vector4](../../com.aspose.threed/vector4) | Vektor att rotera |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Rotated vector
### mul(Quaternion lhs, double rhs) {#mul-com.aspose.threed.Quaternion-double-}
```
public static Quaternion mul(Quaternion lhs, double rhs)
```


Operatoröverladdning för \*

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Vänster kvaternion |
| rhs | double | Höger kvaternion |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### mul(Vector3 v, Quaternion q) {#mul-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-}
```
public static Vector3 mul(Vector3 v, Quaternion q)
```


Operatoröverladdning för \*

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) | Rotationskvaternionen |
| q | [Quaternion](../../com.aspose.threed/quaternion) | Vektor att rotera |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Rotated vector
### normalize() {#normalize--}
```
public Quaternion normalize()
```


Normalisera kvaternionen

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


Likhetsoperator för kvaternion

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Left hand side value. |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Right hand side value. |

**Returns:**
boolean - True if all components are identically equal.
### op_ne(Quaternion lhs, Quaternion rhs) {#op-ne-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static boolean op_ne(Quaternion lhs, Quaternion rhs)
```


Icke-likhetsoperator för kvaternion

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Left hand side value. |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Right hand side value. |

**Returns:**
boolean - Sant om två kvaternioner inte är lika.
### slerp(double t, Quaternion v1, Quaternion v2) {#slerp-double-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion slerp(double t, Quaternion v1, Quaternion v2)
```


Utför sfärisk linjär interpolation mellan två värden

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| t | double | t är mellan 0 och 1 |
| v1 | [Quaternion](../../com.aspose.threed/quaternion) | Första värdet |
| v2 | [Quaternion](../../com.aspose.threed/quaternion) | Andra värdet |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### toAngleAxis(double[] angle, Vector3 axis) {#toAngleAxis-double---com.aspose.threed.Vector3-}
```
public void toAngleAxis(double[] angle, Vector3 axis)
```


Decomponera kvaternionen till vinkel och axel

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| angle | double[] | Vinkeln att rotera, i radian. |
| axis | [Vector3](../../com.aspose.threed/vector3) | Axeln som roterar kring. |

### toMatrix() {#toMatrix--}
```
public Matrix4 toMatrix()
```


Konvertera rotationen som presenteras av kvaternionen till en transformmatris.

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - The matrix representation of current quaternion.
### toMatrix(Vector3 translation) {#toMatrix-com.aspose.threed.Vector3-}
```
public Matrix4 toMatrix(Vector3 translation)
```


Konvertera rotationen som presenteras av kvaternionen till en transformmatris.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| translation | [Vector3](../../com.aspose.threed/vector3) | Översättningsdelen av matrisen. |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - The matrix representation of current quaternion.
### toString() {#toString--}
```
public String toString()
```


Hämtar representationen av kvaternionen som sträng

**Returns:**
java.lang.String - Objektsträng
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

