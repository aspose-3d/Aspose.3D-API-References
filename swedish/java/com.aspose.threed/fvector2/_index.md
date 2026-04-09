---
title: FVector2
second_title: Aspose.3D for Java API-referens
description: En float-vektor med två komponenter.
type: docs
weight: 59
url: /sv/java/com.aspose.threed/fvector2/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class FVector2 implements Struct<FVector2>, Serializable
```

En float-vektor med två komponenter.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [FVector2(float x, float y)](#FVector2-float-float-) | Initierar en ny instans av [FVector2](../../com.aspose.threed/fvector2). |
| [FVector2(Vector2 vec)](#FVector2-com.aspose.threed.Vector2-) | Initierar en ny instans av [FVector2](../../com.aspose.threed/fvector2). |
| [FVector2()](#FVector2--) |  |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [x](#x) | x-komponenten. |
| [y](#y) | y-komponenten. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add(FVector2 a, FVector2 b)](#add-com.aspose.threed.FVector2-com.aspose.threed.FVector2-) | \+ Operatoröverladdning |
| [clone()](#clone--) |  |
| [copyFrom(FVector2 src)](#copyFrom-com.aspose.threed.FVector2-) |  |
| [create(FVector2 v)](#create-com.aspose.threed.FVector2-) | Explicit konverteringsoperator för att kasta FVector2 till Vector2 |
| [equals(FVector2 rhs)](#equals-com.aspose.threed.FVector2-) | Kontrollera om två vektorer är lika |
| [equals(Object obj)](#equals-java.lang.Object-) | Kontrollera om två vektorer är lika |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | Hämtar hashkoden för denna instans |
| [mul(FVector2 a, float b)](#mul-com.aspose.threed.FVector2-float-) | \* operatoröverladdning |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(FVector2 a, FVector2 b)](#op-eq-com.aspose.threed.FVector2-com.aspose.threed.FVector2-) | == Operatoröverladdning |
| [op_ne(FVector2 a, FVector2 b)](#op-ne-com.aspose.threed.FVector2-com.aspose.threed.FVector2-) | != Operatoröverladdning |
| [sub(FVector2 a, FVector2 b)](#sub-com.aspose.threed.FVector2-com.aspose.threed.FVector2-) | \- Operatoröverladdning |
| [toString()](#toString--) | Returnerar en sträng som representerar [FVector2](../../com.aspose.threed/fvector2) |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FVector2(float x, float y) {#FVector2-float-float-}
```
public FVector2(float x, float y)
```


Initierar en ny instans av [FVector2](../../com.aspose.threed/fvector2).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-komponent av vektorn |
| y | float | Y-komponent av vektorn |

### FVector2(Vector2 vec) {#FVector2-com.aspose.threed.Vector2-}
```
public FVector2(Vector2 vec)
```


Initierar en ny instans av [FVector2](../../com.aspose.threed/fvector2).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vec | [Vector2](../../com.aspose.threed/vector2) | Vector2 i dubbeltyp |

### FVector2() {#FVector2--}
```
public FVector2()
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

### add(FVector2 a, FVector2 b) {#add-com.aspose.threed.FVector2-com.aspose.threed.FVector2-}
```
public static FVector2 add(FVector2 a, FVector2 b)
```


\+ Operatoröverladdning

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | Första vektorn |
| b | [FVector2](../../com.aspose.threed/fvector2) | Andra vektorn |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - The sum of two vectors.
### clone() {#clone--}
```
public FVector2 clone()
```


Clone current instance

**Returns:**
[FVector2](../../com.aspose.threed/fvector2)
### copyFrom(FVector2 src) {#copyFrom-com.aspose.threed.FVector2-}
```
public void copyFrom(FVector2 src)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| src | [FVector2](../../com.aspose.threed/fvector2) |  |

### create(FVector2 v) {#create-com.aspose.threed.FVector2-}
```
public static Vector2 create(FVector2 v)
```


Explicit konverteringsoperator för att kasta FVector2 till Vector2

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| v | [FVector2](../../com.aspose.threed/fvector2) | Vector 2 i flyttalstyp. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2)
### equals(FVector2 rhs) {#equals-com.aspose.threed.FVector2-}
```
public boolean equals(FVector2 rhs)
```


Kontrollera om två vektorer är lika

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rhs | [FVector2](../../com.aspose.threed/fvector2) |  |

**Returns:**
boolean - Sant om alla komponenter är lika.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Kontrollera om två vektorer är lika

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean - Sant om indata är en vektor och alla komponenter är lika.
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


Hämtar hashkoden för denna instans

**Returns:**
int - Hashkoden för vektorn.
### mul(FVector2 a, float b) {#mul-com.aspose.threed.FVector2-float-}
```
public static FVector2 mul(FVector2 a, float b)
```


\* operatoröverladdning

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | Första vektorn |
| b | float | Andra vektorn |

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


== Operatoröverladdning

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | Första vektorn |
| b | [FVector2](../../com.aspose.threed/fvector2) | Andra vektorn |

**Returns:**
boolean - Sant om alla komponenter är lika.
### op_ne(FVector2 a, FVector2 b) {#op-ne-com.aspose.threed.FVector2-com.aspose.threed.FVector2-}
```
public static boolean op_ne(FVector2 a, FVector2 b)
```


!= Operator overloading

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | Första vektorn |
| b | [FVector2](../../com.aspose.threed/fvector2) | Andra vektorn |

**Returns:**
boolean - Sant om någon komponent är annorlunda.
### sub(FVector2 a, FVector2 b) {#sub-com.aspose.threed.FVector2-com.aspose.threed.FVector2-}
```
public static FVector2 sub(FVector2 a, FVector2 b)
```


\- Operatoröverladdning

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | Första vektorn |
| b | [FVector2](../../com.aspose.threed/fvector2) | Andra vektorn |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - The difference of two vectors.
### toString() {#toString--}
```
public String toString()
```


Returnerar en sträng som representerar [FVector2](../../com.aspose.threed/fvector2)

**Returns:**
java.lang.String - Strängrepresentation av aktuell vektor.
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

