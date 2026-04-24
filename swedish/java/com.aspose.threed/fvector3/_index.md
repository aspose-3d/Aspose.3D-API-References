---
title: FVector3
second_title: Aspose.3D for Java API-referens
description: En float-vektor med tre komponenter.
type: docs
weight: 60
url: /sv/java/com.aspose.threed/fvector3/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class FVector3 implements Struct<FVector3>, Serializable
```

En float-vektor med tre komponenter.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [FVector3(float x, float y, float z)](#FVector3-float-float-float-) | Initierar en ny instans av [FVector3](../../com.aspose.threed/fvector3). |
| [FVector3(Vector3 vec)](#FVector3-com.aspose.threed.Vector3-) | Initierar en ny instans av [FVector3](../../com.aspose.threed/fvector3). |
| [FVector3(Vector4 vec)](#FVector3-com.aspose.threed.Vector4-) | Initierar en ny instans av [FVector4](../../com.aspose.threed/fvector4). |
| [FVector3()](#FVector3--) |  |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [x](#x) | x-komponenten. |
| [y](#y) | y-komponenten. |
| [z](#z) | y-komponenten. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add(FVector3 a, FVector3 b)](#add-com.aspose.threed.FVector3-com.aspose.threed.FVector3-) | \+ Operatoröverladdning |
| [clone()](#clone--) |  |
| [copyFrom(FVector3 src)](#copyFrom-com.aspose.threed.FVector3-) |  |
| [create(FVector3 v)](#create-com.aspose.threed.FVector3-) | Explicit konverteringsoperator för att kasta FVector3 till Vector3 |
| [cross(FVector3 rhs)](#cross-com.aspose.threed.FVector3-) | Korsprodukt av två vektorer. |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOne()](#getOne--) | Enhetsvektorn med alla komponenter lika med 1 |
| [getZero()](#getZero--) | Nollvektorn. |
| [hashCode()](#hashCode--) |  |
| [mul(FVector3 a, float b)](#mul-com.aspose.threed.FVector3-float-) | \* Operatoröverladdning |
| [negative(FVector3 a)](#negative-com.aspose.threed.FVector3-) | \- Operatoröverladdning |
| [normalize()](#normalize--) | Normalizes this instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [sub(FVector3 a, FVector3 b)](#sub-com.aspose.threed.FVector3-com.aspose.threed.FVector3-) | \- Operatoröverladdning |
| [toString()](#toString--) | Returnerar en sträng som representerar [FVector3](../../com.aspose.threed/fvector3) |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FVector3(float x, float y, float z) {#FVector3-float-float-float-}
```
public FVector3(float x, float y, float z)
```


Initierar en ny instans av [FVector3](../../com.aspose.threed/fvector3).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-komponent av vektorn |
| y | float | Y-komponent av vektorn |
| z | float | Z-komponenten av vektorn |

### FVector3(Vector3 vec) {#FVector3-com.aspose.threed.Vector3-}
```
public FVector3(Vector3 vec)
```


Initierar en ny instans av [FVector3](../../com.aspose.threed/fvector3).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) | Vector3 i double-typ |

### FVector3(Vector4 vec) {#FVector3-com.aspose.threed.Vector4-}
```
public FVector3(Vector4 vec)
```


Initierar en ny instans av [FVector4](../../com.aspose.threed/fvector4).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vec | [Vector4](../../com.aspose.threed/vector4) | Vector4 i double-typ |

### FVector3() {#FVector3--}
```
public FVector3()
```


### x {#x}
```
public float x
```


x-komponenten.

### y {#y}
```
public float y
```


y-komponenten.

### z {#z}
```
public float z
```


y-komponenten.

### add(FVector3 a, FVector3 b) {#add-com.aspose.threed.FVector3-com.aspose.threed.FVector3-}
```
public static FVector3 add(FVector3 a, FVector3 b)
```


\+ Operatoröverladdning

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | Första vektorn |
| b | [FVector3](../../com.aspose.threed/fvector3) | Andra vektorn |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### clone() {#clone--}
```
public FVector3 clone()
```


Clone current instance

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### copyFrom(FVector3 src) {#copyFrom-com.aspose.threed.FVector3-}
```
public void copyFrom(FVector3 src)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| src | [FVector3](../../com.aspose.threed/fvector3) |  |

### create(FVector3 v) {#create-com.aspose.threed.FVector3-}
```
public static Vector3 create(FVector3 v)
```


Explicit konverteringsoperator för att kasta FVector3 till Vector3

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| v | [FVector3](../../com.aspose.threed/fvector3) | Vector3 i float-typ |

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### cross(FVector3 rhs) {#cross-com.aspose.threed.FVector3-}
```
public FVector3 cross(FVector3 rhs)
```


Korsprodukt av två vektorer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rhs | [FVector3](../../com.aspose.threed/fvector3) | Right hand side value. |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Cross product of two [FVector3](../../com.aspose.threed/fvector3)s.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




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
### getOne() {#getOne--}
```
public static FVector3 getOne()
```


Enhetsvektorn med alla komponenter lika med 1

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The unit scale vector with all components are all 1
### getZero() {#getZero--}
```
public static FVector3 getZero()
```


Nollvektorn.

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


\* Operatoröverladdning

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | Första vektorn |
| b | float | Andra vektorn |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The product of two vectors
### negative(FVector3 a) {#negative-com.aspose.threed.FVector3-}
```
public static FVector3 negative(FVector3 a)
```


\- Operatoröverladdning

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | Indata-vektor |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The negative vector
### normalize() {#normalize--}
```
public FVector3 normalize()
```


Normalizes this instance.

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


\- Operatoröverladdning

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | Första vektorn |
| b | [FVector3](../../com.aspose.threed/fvector3) | Andra vektorn |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The difference of two vectors
### toString() {#toString--}
```
public String toString()
```


Returnerar en sträng som representerar [FVector3](../../com.aspose.threed/fvector3)

**Returns:**
java.lang.String - Strängrepresentation av denna vektor.
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

