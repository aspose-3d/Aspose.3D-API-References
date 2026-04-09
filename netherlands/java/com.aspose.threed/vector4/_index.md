---
title: Vector4
second_title: Aspose.3D for Java API-referentie
description: Een vector met vier componenten.
type: docs
weight: 203
url: /nl/java/com.aspose.threed/vector4/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.threed.Struct, java.io.Serializable
```
public final class Vector4 implements Comparable<Vector4>, Struct<Vector4>, Serializable
```

Een vector met vier componenten.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Vector4(Vector3 vec, double w)](#Vector4-com.aspose.threed.Vector3-double-) | Initialiseert een nieuw exemplaar van de [Vector4](../../com.aspose.threed/vector4) struct. |
| [Vector4(Vector3 vec)](#Vector4-com.aspose.threed.Vector3-) | Initialiseert een nieuw exemplaar van de [Vector4](../../com.aspose.threed/vector4) struct. |
| [Vector4(FVector4 vec)](#Vector4-com.aspose.threed.FVector4-) | Initialiseert een nieuw exemplaar van de [Vector4](../../com.aspose.threed/vector4) struct. |
| [Vector4(double x, double y, double z)](#Vector4-double-double-double-) | Initialiseert een nieuw exemplaar van de [Vector4](../../com.aspose.threed/vector4) struct. |
| [Vector4(double x, double y, double z, double w)](#Vector4-double-double-double-double-) | Initialiseert een nieuw exemplaar van de [Vector4](../../com.aspose.threed/vector4) struct. |
| [Vector4()](#Vector4--) |  |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [w](#w) | De w‑component. |
| [x](#x) | De x-component. |
| [y](#y) | De y-component. |
| [z](#z) | De z-component. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [add(Vector4 lhs, Vector4 rhs)](#add-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | Operatoroverbelasting voor + |
| [clone()](#clone--) |  |
| [compareTo(Vector4 other)](#compareTo-com.aspose.threed.Vector4-) | Vergelijk de huidige vector met een ander exemplaar. |
| [copyFrom(Vector4 src)](#copyFrom-com.aspose.threed.Vector4-) |  |
| [create(Vector4 v)](#create-com.aspose.threed.Vector4-) | Expliciete conversie‑operator om Vector4 te casten naar FVector4 |
| [equals(Object obj)](#equals-java.lang.Object-) | Controleren of twee vectoren gelijk zijn |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | Haalt de hashcode van deze vector op. |
| [mul(Vector4 lhs, Vector4 rhs)](#mul-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | Operatoroverbelasting voor \* |
| [mul(Vector4 lhs, double rhs)](#mul-com.aspose.threed.Vector4-double-) | Operatoroverbelasting voor \* |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [set(double newX, double newY, double newZ)](#set-double-double-double-) | Stelt de xyz-componenten van de vector in één keer in, w wordt op 1 gezet. |
| [set(double newX, double newY, double newZ, double newW)](#set-double-double-double-double-) | Stelt alle componenten van de vector in één keer in. |
| [sub(Vector4 lhs, Vector4 rhs)](#sub-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | Operatoroverbelasting voor - (minus) |
| [toString()](#toString--) | Retourneert een java.lang.String die de huidige [Vector4](../../com.aspose.threed/vector4) vertegenwoordigt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Vector4(Vector3 vec, double w) {#Vector4-com.aspose.threed.Vector3-double-}
```
public Vector4(Vector3 vec, double w)
```


Initialiseert een nieuw exemplaar van de [Vector4](../../com.aspose.threed/vector4) struct.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) | Vec. |
| w | double | De breedte. |

### Vector4(Vector3 vec) {#Vector4-com.aspose.threed.Vector3-}
```
public Vector4(Vector3 vec)
```


Initialiseert een nieuw exemplaar van de [Vector4](../../com.aspose.threed/vector4) struct.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) | Vec. |

### Vector4(FVector4 vec) {#Vector4-com.aspose.threed.FVector4-}
```
public Vector4(FVector4 vec)
```


Initialiseert een nieuw exemplaar van de [Vector4](../../com.aspose.threed/vector4) struct.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| vec | [FVector4](../../com.aspose.threed/fvector4) | Vec. |

### Vector4(double x, double y, double z) {#Vector4-double-double-double-}
```
public Vector4(double x, double y, double z)
```


Initialiseert een nieuw exemplaar van de [Vector4](../../com.aspose.threed/vector4) struct.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | double | De x-coördinaat. |
| y | double | De y-coördinaat. |
| z | double | De z-coördinaat. |

### Vector4(double x, double y, double z, double w) {#Vector4-double-double-double-double-}
```
public Vector4(double x, double y, double z, double w)
```


Initialiseert een nieuw exemplaar van de [Vector4](../../com.aspose.threed/vector4) struct.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | double | De x-coördinaat. |
| y | double | De y-coördinaat. |
| z | double | De z-coördinaat. |
| w | double | De breedte. |

### Vector4() {#Vector4--}
```
public Vector4()
```


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

### add(Vector4 lhs, Vector4 rhs) {#add-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public static Vector4 add(Vector4 lhs, Vector4 rhs)
```


Operatoroverbelasting voor +

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | De linker vector |
| rhs | [Vector4](../../com.aspose.threed/vector4) | De rechter vector |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### clone() {#clone--}
```
public Vector4 clone()
```


Kloon huidige instantie

**Returns:**
[Vector4](../../com.aspose.threed/vector4)
### compareTo(Vector4 other) {#compareTo-com.aspose.threed.Vector4-}
```
public int compareTo(Vector4 other)
```


Vergelijk de huidige vector met een ander exemplaar.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | [Vector4](../../com.aspose.threed/vector4) |  |

**Returns:**
int
### copyFrom(Vector4 src) {#copyFrom-com.aspose.threed.Vector4-}
```
public void copyFrom(Vector4 src)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| src | [Vector4](../../com.aspose.threed/vector4) |  |

### create(Vector4 v) {#create-com.aspose.threed.Vector4-}
```
public static FVector4 create(Vector4 v)
```


Expliciete conversie‑operator om Vector4 te casten naar FVector4

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| v | [Vector4](../../com.aspose.threed/vector4) |  |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Controleren of twee vectoren gelijk zijn

**Parameters:**
| Parameter | Type | Beschrijving |
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


Haalt de hashcode van deze vector op.

**Returns:**
int
### mul(Vector4 lhs, Vector4 rhs) {#mul-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public static Vector4 mul(Vector4 lhs, Vector4 rhs)
```


Operatoroverbelasting voor \*

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | De linker vector |
| rhs | [Vector4](../../com.aspose.threed/vector4) | De rechter vector |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### mul(Vector4 lhs, double rhs) {#mul-com.aspose.threed.Vector4-double-}
```
public static Vector4 mul(Vector4 lhs, double rhs)
```


Operatoroverbelasting voor \*

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | De linker vector |
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


Stelt de xyz-componenten van de vector in één keer in, w wordt op 1 gezet.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newX | double | Nieuwe X-component. |
| newY | double | Nieuwe Y-component. |
| newZ | double | Nieuwe Z-component. |

### set(double newX, double newY, double newZ, double newW) {#set-double-double-double-double-}
```
public void set(double newX, double newY, double newZ, double newW)
```


Stelt alle componenten van de vector in één keer in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newX | double | Nieuwe X-component. |
| newY | double | Nieuwe Y-component. |
| newZ | double | Nieuwe Z-component. |
| newW | double | Nieuw W-component. |

### sub(Vector4 lhs, Vector4 rhs) {#sub-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public static Vector4 sub(Vector4 lhs, Vector4 rhs)
```


Operatoroverbelasting voor - (minus)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | De linker vector |
| rhs | [Vector4](../../com.aspose.threed/vector4) | De rechter vector |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### toString() {#toString--}
```
public String toString()
```


Retourneert een java.lang.String die de huidige [Vector4](../../com.aspose.threed/vector4) vertegenwoordigt.

**Returns:**
java.lang.String - Een java.lang.String die de huidige [Vector4](../../com.aspose.threed/vector4) vertegenwoordigt.
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

