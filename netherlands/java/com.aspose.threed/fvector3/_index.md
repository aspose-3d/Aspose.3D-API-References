---
title: FVector3
second_title: Aspose.3D for Java API-referentie
description: Een float-vector met drie componenten.
type: docs
weight: 60
url: /nl/java/com.aspose.threed/fvector3/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class FVector3 implements Struct<FVector3>, Serializable
```

Een float-vector met drie componenten.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [FVector3(float x, float y, float z)](#FVector3-float-float-float-) | Initialiseert een nieuw exemplaar van de [FVector3](../../com.aspose.threed/fvector3). |
| [FVector3(Vector3 vec)](#FVector3-com.aspose.threed.Vector3-) | Initialiseert een nieuw exemplaar van de [FVector3](../../com.aspose.threed/fvector3). |
| [FVector3(Vector4 vec)](#FVector3-com.aspose.threed.Vector4-) | Initialiseert een nieuw exemplaar van de [FVector4](../../com.aspose.threed/fvector4). |
| [FVector3()](#FVector3--) |  |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [x](#x) | De x-component. |
| [y](#y) | De y-component. |
| [z](#z) | De y-component. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [add(FVector3 a, FVector3 b)](#add-com.aspose.threed.FVector3-com.aspose.threed.FVector3-) | \+ Operatoroverbelasting |
| [clone()](#clone--) |  |
| [copyFrom(FVector3 src)](#copyFrom-com.aspose.threed.FVector3-) |  |
| [create(FVector3 v)](#create-com.aspose.threed.FVector3-) | Expliciete conversie‑operator om FVector3 naar Vector3 te casten |
| [cross(FVector3 rhs)](#cross-com.aspose.threed.FVector3-) | Kruisproduct van twee vectoren |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOne()](#getOne--) | De eenheids-schaalvector waarvan alle componenten 1 zijn |
| [getZero()](#getZero--) | De nulvector. |
| [hashCode()](#hashCode--) |  |
| [mul(FVector3 a, float b)](#mul-com.aspose.threed.FVector3-float-) | \* Operator overloading |
| [negative(FVector3 a)](#negative-com.aspose.threed.FVector3-) | \- Operatoroverbelasting |
| [normalize()](#normalize--) | Normaliseert deze instantie. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [sub(FVector3 a, FVector3 b)](#sub-com.aspose.threed.FVector3-com.aspose.threed.FVector3-) | \- Operatoroverbelasting |
| [toString()](#toString--) | Retourneert een string die de [FVector3](../../com.aspose.threed/fvector3) vertegenwoordigt |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FVector3(float x, float y, float z) {#FVector3-float-float-float-}
```
public FVector3(float x, float y, float z)
```


Initialiseert een nieuw exemplaar van de [FVector3](../../com.aspose.threed/fvector3).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | X-component van de vector |
| y | float | Y-component van de vector |
| z | float | Z-component van de vector |

### FVector3(Vector3 vec) {#FVector3-com.aspose.threed.Vector3-}
```
public FVector3(Vector3 vec)
```


Initialiseert een nieuw exemplaar van de [FVector3](../../com.aspose.threed/fvector3).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) | Vector3 van het type double |

### FVector3(Vector4 vec) {#FVector3-com.aspose.threed.Vector4-}
```
public FVector3(Vector4 vec)
```


Initialiseert een nieuw exemplaar van de [FVector4](../../com.aspose.threed/fvector4).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| vec | [Vector4](../../com.aspose.threed/vector4) | Vector4 van het type double |

### FVector3() {#FVector3--}
```
public FVector3()
```


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


De y-component.

### add(FVector3 a, FVector3 b) {#add-com.aspose.threed.FVector3-com.aspose.threed.FVector3-}
```
public static FVector3 add(FVector3 a, FVector3 b)
```


\+ Operatoroverbelasting

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | Eerste vector |
| b | [FVector3](../../com.aspose.threed/fvector3) | Tweede vector |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### clone() {#clone--}
```
public FVector3 clone()
```


Kloon huidige instantie

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### copyFrom(FVector3 src) {#copyFrom-com.aspose.threed.FVector3-}
```
public void copyFrom(FVector3 src)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| src | [FVector3](../../com.aspose.threed/fvector3) |  |

### create(FVector3 v) {#create-com.aspose.threed.FVector3-}
```
public static Vector3 create(FVector3 v)
```


Expliciete conversie‑operator om FVector3 naar Vector3 te casten

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| v | [FVector3](../../com.aspose.threed/fvector3) | Vector3 van het type float |

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### cross(FVector3 rhs) {#cross-com.aspose.threed.FVector3-}
```
public FVector3 cross(FVector3 rhs)
```


Kruisproduct van twee vectoren

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rhs | [FVector3](../../com.aspose.threed/fvector3) | Right hand side value. |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Cross product of two [FVector3](../../com.aspose.threed/fvector3)s.
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
### getOne() {#getOne--}
```
public static FVector3 getOne()
```


De eenheids-schaalvector waarvan alle componenten 1 zijn

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The unit scale vector with all components are all 1
### getZero() {#getZero--}
```
public static FVector3 getZero()
```


De nulvector.

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The Zero vector.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### mul(FVector3 a, float b) {#mul-com.aspose.threed.FVector3-float-}
```
public static FVector3 mul(FVector3 a, float b)
```


\* Operator overloading

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | Eerste vector |
| b | float | Tweede vector |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The product of two vectors
### negative(FVector3 a) {#negative-com.aspose.threed.FVector3-}
```
public static FVector3 negative(FVector3 a)
```


\- Operatoroverbelasting

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | Invoervector |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The negative vector
### normalize() {#normalize--}
```
public FVector3 normalize()
```


Normaliseert deze instantie.

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Normalized vector.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### sub(FVector3 a, FVector3 b) {#sub-com.aspose.threed.FVector3-com.aspose.threed.FVector3-}
```
public static FVector3 sub(FVector3 a, FVector3 b)
```


\- Operatoroverbelasting

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | Eerste vector |
| b | [FVector3](../../com.aspose.threed/fvector3) | Tweede vector |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The difference of two vectors
### toString() {#toString--}
```
public String toString()
```


Retourneert een string die de [FVector3](../../com.aspose.threed/fvector3) vertegenwoordigt

**Returns:**
java.lang.String - Stringrepresentatie van deze vector.
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

