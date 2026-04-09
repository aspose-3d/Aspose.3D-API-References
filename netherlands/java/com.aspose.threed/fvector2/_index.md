---
title: FVector2
second_title: Aspose.3D for Java API-referentie
description: Een float-vector met twee componenten.
type: docs
weight: 59
url: /nl/java/com.aspose.threed/fvector2/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class FVector2 implements Struct<FVector2>, Serializable
```

Een float-vector met twee componenten.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [FVector2(float x, float y)](#FVector2-float-float-) | Initialiseert een nieuw exemplaar van de [FVector2](../../com.aspose.threed/fvector2). |
| [FVector2(Vector2 vec)](#FVector2-com.aspose.threed.Vector2-) | Initialiseert een nieuw exemplaar van de [FVector2](../../com.aspose.threed/fvector2). |
| [FVector2()](#FVector2--) |  |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [x](#x) | De x-component. |
| [y](#y) | De y-component. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [add(FVector2 a, FVector2 b)](#add-com.aspose.threed.FVector2-com.aspose.threed.FVector2-) | \+ Operatoroverbelasting |
| [clone()](#clone--) |  |
| [copyFrom(FVector2 src)](#copyFrom-com.aspose.threed.FVector2-) |  |
| [create(FVector2 v)](#create-com.aspose.threed.FVector2-) | Expliciete conversie-operator om FVector2 naar Vector2 te casten |
| [equals(FVector2 rhs)](#equals-com.aspose.threed.FVector2-) | Controleren of twee vectoren gelijk zijn |
| [equals(Object obj)](#equals-java.lang.Object-) | Controleren of twee vectoren gelijk zijn |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | Haalt de hashcode van deze instantie op |
| [mul(FVector2 a, float b)](#mul-com.aspose.threed.FVector2-float-) | \* Operatoroverbelasting |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(FVector2 a, FVector2 b)](#op-eq-com.aspose.threed.FVector2-com.aspose.threed.FVector2-) | == Operatoroverbelasting |
| [op_ne(FVector2 a, FVector2 b)](#op-ne-com.aspose.threed.FVector2-com.aspose.threed.FVector2-) | != Operatoroverbelasting |
| [sub(FVector2 a, FVector2 b)](#sub-com.aspose.threed.FVector2-com.aspose.threed.FVector2-) | \- Operatoroverbelasting |
| [toString()](#toString--) | Retourneert een string die de [FVector2](../../com.aspose.threed/fvector2) voorstelt |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FVector2(float x, float y) {#FVector2-float-float-}
```
public FVector2(float x, float y)
```


Initialiseert een nieuw exemplaar van de [FVector2](../../com.aspose.threed/fvector2).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | X-component van de vector |
| y | float | Y-component van de vector |

### FVector2(Vector2 vec) {#FVector2-com.aspose.threed.Vector2-}
```
public FVector2(Vector2 vec)
```


Initialiseert een nieuw exemplaar van de [FVector2](../../com.aspose.threed/fvector2).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| vec | [Vector2](../../com.aspose.threed/vector2) | Vector2 van het type double |

### FVector2() {#FVector2--}
```
public FVector2()
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

### add(FVector2 a, FVector2 b) {#add-com.aspose.threed.FVector2-com.aspose.threed.FVector2-}
```
public static FVector2 add(FVector2 a, FVector2 b)
```


\+ Operatoroverbelasting

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | Eerste vector |
| b | [FVector2](../../com.aspose.threed/fvector2) | Tweede vector |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - The sum of two vectors.
### clone() {#clone--}
```
public FVector2 clone()
```


Kloon huidige instantie

**Returns:**
[FVector2](../../com.aspose.threed/fvector2)
### copyFrom(FVector2 src) {#copyFrom-com.aspose.threed.FVector2-}
```
public void copyFrom(FVector2 src)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| src | [FVector2](../../com.aspose.threed/fvector2) |  |

### create(FVector2 v) {#create-com.aspose.threed.FVector2-}
```
public static Vector2 create(FVector2 v)
```


Expliciete conversie-operator om FVector2 naar Vector2 te casten

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| v | [FVector2](../../com.aspose.threed/fvector2) | Vector 2 van het type float. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2)
### equals(FVector2 rhs) {#equals-com.aspose.threed.FVector2-}
```
public boolean equals(FVector2 rhs)
```


Controleren of twee vectoren gelijk zijn

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rhs | [FVector2](../../com.aspose.threed/fvector2) |  |

**Returns:**
boolean - Waar als alle componenten gelijk zijn.
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
boolean - Waar als de invoer een vector is en alle componenten gelijk zijn.
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


Haalt de hashcode van deze instantie op

**Returns:**
int - De hashcode van de vector.
### mul(FVector2 a, float b) {#mul-com.aspose.threed.FVector2-float-}
```
public static FVector2 mul(FVector2 a, float b)
```


\* Operatoroverbelasting

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | Eerste vector |
| b | float | Tweede vector |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - The product of two vectors.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_eq(FVector2 a, FVector2 b) {#op-eq-com.aspose.threed.FVector2-com.aspose.threed.FVector2-}
```
public static boolean op_eq(FVector2 a, FVector2 b)
```


== Operatoroverbelasting

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | Eerste vector |
| b | [FVector2](../../com.aspose.threed/fvector2) | Tweede vector |

**Returns:**
boolean - Waar als alle componenten gelijk zijn.
### op_ne(FVector2 a, FVector2 b) {#op-ne-com.aspose.threed.FVector2-com.aspose.threed.FVector2-}
```
public static boolean op_ne(FVector2 a, FVector2 b)
```


!= Operator overloading

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | Eerste vector |
| b | [FVector2](../../com.aspose.threed/fvector2) | Tweede vector |

**Returns:**
boolean - Waar als een component verschillend is.
### sub(FVector2 a, FVector2 b) {#sub-com.aspose.threed.FVector2-com.aspose.threed.FVector2-}
```
public static FVector2 sub(FVector2 a, FVector2 b)
```


\- Operatoroverbelasting

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | Eerste vector |
| b | [FVector2](../../com.aspose.threed/fvector2) | Tweede vector |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - The difference of two vectors.
### toString() {#toString--}
```
public String toString()
```


Retourneert een string die de [FVector2](../../com.aspose.threed/fvector2) voorstelt

**Returns:**
java.lang.String - Stringrepresentatie van de huidige vector.
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

