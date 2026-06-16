---
title: FVector2
second_title: Referencia de API de Aspose.3D para Java
description: Un vector flotante con dos componentes.
type: docs
weight: 59
url: /es/java/com.aspose.threed/fvector2/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class FVector2 implements Struct<FVector2>, Serializable
```

Un vector flotante con dos componentes.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [FVector2(float x, float y)](#FVector2-float-float-) | Inicializa una nueva instancia de [FVector2](../../com.aspose.threed/fvector2). |
| [FVector2(Vector2 vec)](#FVector2-com.aspose.threed.Vector2-) | Inicializa una nueva instancia de [FVector2](../../com.aspose.threed/fvector2). |
| [FVector2()](#FVector2--) |  |
## Campos

| Campo | Descripción |
| --- | --- |
| [x](#x) | El componente x. |
| [y](#y) | El componente y. |
## Métodos

| Método | Descripción |
| --- | --- |
| [add(FVector2 a, FVector2 b)](#add-com.aspose.threed.FVector2-com.aspose.threed.FVector2-) | \+ Sobrecarga de operadores |
| [clone()](#clone--) |  |
| [copyFrom(FVector2 src)](#copyFrom-com.aspose.threed.FVector2-) |  |
| [create(FVector2 v)](#create-com.aspose.threed.FVector2-) | Operador de conversión explícita para convertir FVector2 a Vector2 |
| [equals(FVector2 rhs)](#equals-com.aspose.threed.FVector2-) | Comprobar si dos vectores son iguales |
| [equals(Object obj)](#equals-java.lang.Object-) | Comprobar si dos vectores son iguales |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | Obtiene el código hash de esta instancia |
| [mul(FVector2 a, float b)](#mul-com.aspose.threed.FVector2-float-) | \* Sobrecarga de operadores |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(FVector2 a, FVector2 b)](#op-eq-com.aspose.threed.FVector2-com.aspose.threed.FVector2-) | == Sobrecarga de operadores |
| [op_ne(FVector2 a, FVector2 b)](#op-ne-com.aspose.threed.FVector2-com.aspose.threed.FVector2-) | != Sobrecarga de operadores |
| [sub(FVector2 a, FVector2 b)](#sub-com.aspose.threed.FVector2-com.aspose.threed.FVector2-) | \- Sobrecarga de operadores |
| [toString()](#toString--) | Devuelve una cadena que representa el [FVector2](../../com.aspose.threed/fvector2) |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FVector2(float x, float y) {#FVector2-float-float-}
```
public FVector2(float x, float y)
```


Inicializa una nueva instancia de [FVector2](../../com.aspose.threed/fvector2).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | Componente X del vector |
| y | float | Componente Y del vector |

### FVector2(Vector2 vec) {#FVector2-com.aspose.threed.Vector2-}
```
public FVector2(Vector2 vec)
```


Inicializa una nueva instancia de [FVector2](../../com.aspose.threed/fvector2).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vec | [Vector2](../../com.aspose.threed/vector2) | Vector2 en tipo double |

### FVector2() {#FVector2--}
```
public FVector2()
```


### x {#x}
```
public float x
```


El componente x.

### y {#y}
```
public float y
```


El componente y.

### add(FVector2 a, FVector2 b) {#add-com.aspose.threed.FVector2-com.aspose.threed.FVector2-}
```
public static FVector2 add(FVector2 a, FVector2 b)
```


\+ Sobrecarga de operadores

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | Primer vector |
| b | [FVector2](../../com.aspose.threed/fvector2) | Segundo vector |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - The sum of two vectors.
### clone() {#clone--}
```
public FVector2 clone()
```


Clonar la instancia actual

**Returns:**
[FVector2](../../com.aspose.threed/fvector2)
### copyFrom(FVector2 src) {#copyFrom-com.aspose.threed.FVector2-}
```
public void copyFrom(FVector2 src)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| src | [FVector2](../../com.aspose.threed/fvector2) |  |

### create(FVector2 v) {#create-com.aspose.threed.FVector2-}
```
public static Vector2 create(FVector2 v)
```


Operador de conversión explícita para convertir FVector2 a Vector2

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| v | [FVector2](../../com.aspose.threed/fvector2) | Vector 2 en tipo float. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2)
### equals(FVector2 rhs) {#equals-com.aspose.threed.FVector2-}
```
public boolean equals(FVector2 rhs)
```


Comprobar si dos vectores son iguales

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rhs | [FVector2](../../com.aspose.threed/fvector2) |  |

**Returns:**
boolean - Verdadero si todos los componentes son iguales.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Comprobar si dos vectores son iguales

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean - Verdadero si la entrada es un vector y todos los componentes son iguales.
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


Obtiene el código hash de esta instancia

**Returns:**
int - El código hash del vector.
### mul(FVector2 a, float b) {#mul-com.aspose.threed.FVector2-float-}
```
public static FVector2 mul(FVector2 a, float b)
```


\* Sobrecarga de operadores

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | Primer vector |
| b | float | Segundo vector |

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


== Sobrecarga de operadores

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | Primer vector |
| b | [FVector2](../../com.aspose.threed/fvector2) | Segundo vector |

**Returns:**
boolean - Verdadero si todos los componentes son iguales.
### op_ne(FVector2 a, FVector2 b) {#op-ne-com.aspose.threed.FVector2-com.aspose.threed.FVector2-}
```
public static boolean op_ne(FVector2 a, FVector2 b)
```


!= Operator overloading

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | Primer vector |
| b | [FVector2](../../com.aspose.threed/fvector2) | Segundo vector |

**Returns:**
boolean - Verdadero si algún componente es diferente.
### sub(FVector2 a, FVector2 b) {#sub-com.aspose.threed.FVector2-com.aspose.threed.FVector2-}
```
public static FVector2 sub(FVector2 a, FVector2 b)
```


\- Sobrecarga de operadores

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | Primer vector |
| b | [FVector2](../../com.aspose.threed/fvector2) | Segundo vector |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - The difference of two vectors.
### toString() {#toString--}
```
public String toString()
```


Devuelve una cadena que representa el [FVector2](../../com.aspose.threed/fvector2)

**Returns:**
java.lang.String - Representación en cadena del vector actual.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

