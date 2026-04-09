---
title: FVector2
second_title: Aspose.3D for Java API Reference
description: Un vettore float con due componenti.
type: docs
weight: 59
url: /it/java/com.aspose.threed/fvector2/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class FVector2 implements Struct<FVector2>, Serializable
```

Un vettore float con due componenti.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FVector2(float x, float y)](#FVector2-float-float-) | Inizializza una nuova istanza di [FVector2](../../com.aspose.threed/fvector2). |
| [FVector2(Vector2 vec)](#FVector2-com.aspose.threed.Vector2-) | Inizializza una nuova istanza di [FVector2](../../com.aspose.threed/fvector2). |
| [FVector2()](#FVector2--) |  |
## Campi

| Campo | Descrizione |
| --- | --- |
| [x](#x) | La componente x. |
| [y](#y) | La componente y. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add(FVector2 a, FVector2 b)](#add-com.aspose.threed.FVector2-com.aspose.threed.FVector2-) | \+ Sovraccarico dell'operatore |
| [clone()](#clone--) |  |
| [copyFrom(FVector2 src)](#copyFrom-com.aspose.threed.FVector2-) |  |
| [create(FVector2 v)](#create-com.aspose.threed.FVector2-) | Operatore di conversione esplicita per convertire FVector2 in Vector2 |
| [equals(FVector2 rhs)](#equals-com.aspose.threed.FVector2-) | Verifica se due vettori sono uguali |
| [equals(Object obj)](#equals-java.lang.Object-) | Verifica se due vettori sono uguali |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | Restituisce il codice hash di questa istanza |
| [mul(FVector2 a, float b)](#mul-com.aspose.threed.FVector2-float-) | \* Sovraccarico dell'operatore |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(FVector2 a, FVector2 b)](#op-eq-com.aspose.threed.FVector2-com.aspose.threed.FVector2-) | == Sovraccarico dell'operatore |
| [op_ne(FVector2 a, FVector2 b)](#op-ne-com.aspose.threed.FVector2-com.aspose.threed.FVector2-) | != Sovraccarico dell'operatore |
| [sub(FVector2 a, FVector2 b)](#sub-com.aspose.threed.FVector2-com.aspose.threed.FVector2-) | \- Sovraccarico dell'operatore |
| [toString()](#toString--) | Restituisce una stringa che rappresenta il [FVector2](../../com.aspose.threed/fvector2) |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FVector2(float x, float y) {#FVector2-float-float-}
```
public FVector2(float x, float y)
```


Inizializza una nuova istanza di [FVector2](../../com.aspose.threed/fvector2).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | Componente X del vettore |
| y | float | Componente Y del vettore |

### FVector2(Vector2 vec) {#FVector2-com.aspose.threed.Vector2-}
```
public FVector2(Vector2 vec)
```


Inizializza una nuova istanza di [FVector2](../../com.aspose.threed/fvector2).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vec | [Vector2](../../com.aspose.threed/vector2) | Vector2 di tipo double |

### FVector2() {#FVector2--}
```
public FVector2()
```


### x {#x}
```
public float x
```


La componente x.

### y {#y}
```
public float y
```


La componente y.

### add(FVector2 a, FVector2 b) {#add-com.aspose.threed.FVector2-com.aspose.threed.FVector2-}
```
public static FVector2 add(FVector2 a, FVector2 b)
```


\+ Sovraccarico dell'operatore

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | Primo vettore |
| b | [FVector2](../../com.aspose.threed/fvector2) | Secondo vettore |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| src | [FVector2](../../com.aspose.threed/fvector2) |  |

### create(FVector2 v) {#create-com.aspose.threed.FVector2-}
```
public static Vector2 create(FVector2 v)
```


Operatore di conversione esplicita per convertire FVector2 in Vector2

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| v | [FVector2](../../com.aspose.threed/fvector2) | Vector 2 di tipo float. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2)
### equals(FVector2 rhs) {#equals-com.aspose.threed.FVector2-}
```
public boolean equals(FVector2 rhs)
```


Verifica se due vettori sono uguali

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rhs | [FVector2](../../com.aspose.threed/fvector2) |  |

**Returns:**
boolean - Vero se tutti i componenti sono uguali.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Verifica se due vettori sono uguali

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean - Vero se l'input è un vettore e tutti i componenti sono uguali.
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


Restituisce il codice hash di questa istanza

**Returns:**
int - Il codice hash del vettore.
### mul(FVector2 a, float b) {#mul-com.aspose.threed.FVector2-float-}
```
public static FVector2 mul(FVector2 a, float b)
```


\* Sovraccarico dell'operatore

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | Primo vettore |
| b | float | Secondo vettore |

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


== Sovraccarico dell'operatore

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | Primo vettore |
| b | [FVector2](../../com.aspose.threed/fvector2) | Secondo vettore |

**Returns:**
boolean - Vero se tutti i componenti sono uguali.
### op_ne(FVector2 a, FVector2 b) {#op-ne-com.aspose.threed.FVector2-com.aspose.threed.FVector2-}
```
public static boolean op_ne(FVector2 a, FVector2 b)
```


!= Operator overloading

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | Primo vettore |
| b | [FVector2](../../com.aspose.threed/fvector2) | Secondo vettore |

**Returns:**
boolean - Vero se qualche componente è diverso.
### sub(FVector2 a, FVector2 b) {#sub-com.aspose.threed.FVector2-com.aspose.threed.FVector2-}
```
public static FVector2 sub(FVector2 a, FVector2 b)
```


\- Sovraccarico dell'operatore

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | Primo vettore |
| b | [FVector2](../../com.aspose.threed/fvector2) | Secondo vettore |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - The difference of two vectors.
### toString() {#toString--}
```
public String toString()
```


Restituisce una stringa che rappresenta il [FVector2](../../com.aspose.threed/fvector2)

**Returns:**
java.lang.String - Rappresentazione stringa del vettore corrente.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

