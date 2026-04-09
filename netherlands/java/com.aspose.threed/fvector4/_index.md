---
title: FVector4
second_title: Aspose.3D for Java API-referentie
description: Een float-vector met vier componenten.
type: docs
weight: 61
url: /nl/java/com.aspose.threed/fvector4/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class FVector4 implements Struct<FVector4>, Serializable
```

Een float-vector met vier componenten.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [FVector4(float x, float y, float z, float w)](#FVector4-float-float-float-float-) | Initialiseert een nieuw exemplaar van de [FVector4](../../com.aspose.threed/fvector4). |
| [FVector4(float x, float y, float z)](#FVector4-float-float-float-) | Initialiseert een nieuw exemplaar van de [FVector4](../../com.aspose.threed/fvector4). |
| [FVector4(Color color)](#FVector4-java.awt.Color-) | Initialiseert een nieuw exemplaar van de [FVector4](../../com.aspose.threed/fvector4). |
| [FVector4(Vector4 vec)](#FVector4-com.aspose.threed.Vector4-) | Initialiseert een nieuw exemplaar van de [FVector4](../../com.aspose.threed/fvector4). |
| [FVector4(Vector3 vec)](#FVector4-com.aspose.threed.Vector3-) | Initialiseert een nieuw exemplaar van de [FVector4](../../com.aspose.threed/fvector4). |
| [FVector4(Vector3 vec, float w)](#FVector4-com.aspose.threed.Vector3-float-) | Initialiseert een nieuw exemplaar van de [FVector4](../../com.aspose.threed/fvector4). |
| [FVector4()](#FVector4--) |  |
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
| [add(FVector4 lhs, FVector4 rhs)](#add-com.aspose.threed.FVector4-com.aspose.threed.FVector4-) | Operatoroverbelasting voor + |
| [clone()](#clone--) |  |
| [copyFrom(FVector4 src)](#copyFrom-com.aspose.threed.FVector4-) |  |
| [create(FVector4 v)](#create-com.aspose.threed.FVector4-) | Expliciete conversie‑operator om Vector4 te casten naar FVector4 |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [mul(FVector4 lhs, FVector4 rhs)](#mul-com.aspose.threed.FVector4-com.aspose.threed.FVector4-) | Operatoroverbelasting voor \* |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [sub(FVector4 lhs, FVector4 rhs)](#sub-com.aspose.threed.FVector4-com.aspose.threed.FVector4-) | Operatoroverbelasting voor - (minus) |
| [toString()](#toString--) | Retourneert een string die de [FVector4](../../com.aspose.threed/fvector4) vertegenwoordigt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FVector4(float x, float y, float z, float w) {#FVector4-float-float-float-float-}
```
public FVector4(float x, float y, float z, float w)
```


Initialiseert een nieuw exemplaar van de [FVector4](../../com.aspose.threed/fvector4).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | X‑component |
| y | float | Y‑component |
| z | float | Z‑component |
| w | float | W‑component |

### FVector4(float x, float y, float z) {#FVector4-float-float-float-}
```
public FVector4(float x, float y, float z)
```


Initialiseert een nieuw exemplaar van de [FVector4](../../com.aspose.threed/fvector4).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | X‑component |
| y | float | Y‑component |
| z | float | Z‑component |

### FVector4(Color color) {#FVector4-java.awt.Color-}
```
public FVector4(Color color)
```


Initialiseert een nieuw exemplaar van de [FVector4](../../com.aspose.threed/fvector4).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| kleur | java.awt.Color |  |

### FVector4(Vector4 vec) {#FVector4-com.aspose.threed.Vector4-}
```
public FVector4(Vector4 vec)
```


Initialiseert een nieuw exemplaar van de [FVector4](../../com.aspose.threed/fvector4).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| vec | [Vector4](../../com.aspose.threed/vector4) |  |

### FVector4(Vector3 vec) {#FVector4-com.aspose.threed.Vector3-}
```
public FVector4(Vector3 vec)
```


Initialiseert een nieuw exemplaar van de [FVector4](../../com.aspose.threed/fvector4).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) |  |

### FVector4(Vector3 vec, float w) {#FVector4-com.aspose.threed.Vector3-float-}
```
public FVector4(Vector3 vec, float w)
```


Initialiseert een nieuw exemplaar van de [FVector4](../../com.aspose.threed/fvector4).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) |  |
| w | float |  |

### FVector4() {#FVector4--}
```
public FVector4()
```


### w {#w}
```
public float w
```


De w‑component.

### x {#x}
```
public float x
```


De x-component.

### y {#y}
```
public float y
```


De y-component.

### z {#z}
```
public float z
```


De z-component.

### add(FVector4 lhs, FVector4 rhs) {#add-com.aspose.threed.FVector4-com.aspose.threed.FVector4-}
```
public static FVector4 add(FVector4 lhs, FVector4 rhs)
```


Operatoroverbelasting voor +

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs | [FVector4](../../com.aspose.threed/fvector4) | De linker vector |
| rhs | [FVector4](../../com.aspose.threed/fvector4) | De rechter vector |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4) - Result vector
### clone() {#clone--}
```
public FVector4 clone()
```


Kloon huidige instantie

**Returns:**
[FVector4](../../com.aspose.threed/fvector4)
### copyFrom(FVector4 src) {#copyFrom-com.aspose.threed.FVector4-}
```
public void copyFrom(FVector4 src)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| src | [FVector4](../../com.aspose.threed/fvector4) |  |

### create(FVector4 v) {#create-com.aspose.threed.FVector4-}
```
public static Vector4 create(FVector4 v)
```


Expliciete conversie‑operator om Vector4 te casten naar FVector4

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| v | [FVector4](../../com.aspose.threed/fvector4) |  |

**Returns:**
[Vector4](../../com.aspose.threed/vector4)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




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




**Returns:**
int
### mul(FVector4 lhs, FVector4 rhs) {#mul-com.aspose.threed.FVector4-com.aspose.threed.FVector4-}
```
public static FVector4 mul(FVector4 lhs, FVector4 rhs)
```


Operatoroverbelasting voor \*

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs | [FVector4](../../com.aspose.threed/fvector4) | De linker vector |
| rhs | [FVector4](../../com.aspose.threed/fvector4) | De rechter vector |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4) - Result vector
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### sub(FVector4 lhs, FVector4 rhs) {#sub-com.aspose.threed.FVector4-com.aspose.threed.FVector4-}
```
public static FVector4 sub(FVector4 lhs, FVector4 rhs)
```


Operatoroverbelasting voor - (minus)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs | [FVector4](../../com.aspose.threed/fvector4) | De linker vector |
| rhs | [FVector4](../../com.aspose.threed/fvector4) | De rechter vector |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4) - Result vector
### toString() {#toString--}
```
public String toString()
```


Retourneert een string die de [FVector4](../../com.aspose.threed/fvector4) vertegenwoordigt.

**Returns:**
java.lang.String - De stringrepresentatie van de huidige vector.
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

