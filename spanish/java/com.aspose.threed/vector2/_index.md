---
title: Vector2
second_title: Referencia de API de Aspose.3D para Java
description: Un vector con dos componentes.
type: docs
weight: 201
url: /es/java/com.aspose.threed/vector2/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.threed.Struct, java.io.Serializable
```
public final class Vector2 implements Comparable<Vector2>, Struct<Vector2>, Serializable
```

Un vector con dos componentes.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Vector2(double s)](#Vector2-double-) | Inicializa una nueva instancia de la estructura [Vector2](../../com.aspose.threed/vector2). |
| [Vector2(Vector3 s)](#Vector2-com.aspose.threed.Vector3-) | Inicializa una nueva instancia de la estructura [Vector2](../../com.aspose.threed/vector2). |
| [Vector2(FVector2 vec)](#Vector2-com.aspose.threed.FVector2-) | Inicializa una nueva instancia de la estructura [Vector2](../../com.aspose.threed/vector2). |
| [Vector2(double x, double y)](#Vector2-double-double-) | Inicializa una nueva instancia de la estructura [Vector2](../../com.aspose.threed/vector2). |
| [Vector2()](#Vector2--) |  |
## Campos

| Campo | Descripción |
| --- | --- |
| [x](#x) | El componente x. |
| [y](#y) | El componente y. |
## Métodos

| Método | Descripción |
| --- | --- |
| [add(Vector2 lhs, Vector2 rhs)](#add-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Operador de suma para Vector2 |
| [clone()](#clone--) |  |
| [compareTo(Vector2 other)](#compareTo-com.aspose.threed.Vector2-) | Compara el vector actual con otra instancia. |
| [copyFrom(Vector2 src)](#copyFrom-com.aspose.threed.Vector2-) |  |
| [create(Vector2 v)](#create-com.aspose.threed.Vector2-) | Operador de conversión explícita para convertir Vector2 a FVector2 |
| [cross(Vector2 v)](#cross-com.aspose.threed.Vector2-) | Producto cruzado de dos vectores. |
| [div(Vector2 lhs, double rhs)](#div-com.aspose.threed.Vector2-double-) | Operador de división para Vector2 |
| [dot(Vector2 rhs)](#dot-com.aspose.threed.Vector2-) | Obtiene el producto punto de dos vectores. |
| [equals(Vector2 rhs)](#equals-com.aspose.threed.Vector2-) | Comprobar si dos vector2 son iguales |
| [equals(Object obj)](#equals-java.lang.Object-) | Comprobar si dos vector2 son iguales |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Obtiene la longitud. |
| [getU()](#getU--) | Obtiene el componente U si la [Vector2](../../com.aspose.threed/vector2) se usa como coordenada de mapeo. |
| [getV()](#getV--) | Obtiene el componente V si la [Vector2](../../com.aspose.threed/vector2) se usa como coordenada de mapeo. |
| [hashCode()](#hashCode--) | Obtiene el código hash de Vector2 |
| [mul(Vector2 lhs, double rhs)](#mul-com.aspose.threed.Vector2-double-) | Operador de multiplicación para Vector2 |
| [mul(double lhs, Vector2 rhs)](#mul-double-com.aspose.threed.Vector2-) | Operador de multiplicación para Vector2 |
| [normalize()](#normalize--) | Normaliza esta instancia. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(Vector2 lhs, Vector2 rhs)](#op-eq-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Operador de igualdad para Vector2 |
| [op_ne(Vector2 lhs, Vector2 rhs)](#op-ne-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Operador de desigualdad para Vector2 |
| [setU(double value)](#setU-double-) | Establece el componente U si el [Vector2](../../com.aspose.threed/vector2) se usa como coordenada de mapeo. |
| [setV(double value)](#setV-double-) | Establece el componente V si el [Vector2](../../com.aspose.threed/vector2) se usa como coordenada de mapeo. |
| [sub(Vector2 lhs, Vector2 rhs)](#sub-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Operador de sustracción para Vector2 |
| [toString()](#toString--) | Devuelve un java.lang.String que representa el [Vector2](../../com.aspose.threed/vector2) actual. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Vector2(double s) {#Vector2-double-}
```
public Vector2(double s)
```


Inicializa una nueva instancia de la estructura [Vector2](../../com.aspose.threed/vector2).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | double | S. |

### Vector2(Vector3 s) {#Vector2-com.aspose.threed.Vector3-}
```
public Vector2(Vector3 s)
```


Inicializa una nueva instancia de la estructura [Vector2](../../com.aspose.threed/vector2).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | [Vector3](../../com.aspose.threed/vector3) | S. |

### Vector2(FVector2 vec) {#Vector2-com.aspose.threed.FVector2-}
```
public Vector2(FVector2 vec)
```


Inicializa una nueva instancia de la estructura [Vector2](../../com.aspose.threed/vector2).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vec | [FVector2](../../com.aspose.threed/fvector2) | Vector en float. |

### Vector2(double x, double y) {#Vector2-double-double-}
```
public Vector2(double x, double y)
```


Inicializa una nueva instancia de la estructura [Vector2](../../com.aspose.threed/vector2).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | double | La coordenada x. |
| y | double | La coordenada y. |

### Vector2() {#Vector2--}
```
public Vector2()
```


### x {#x}
```
public double x
```


El componente x.

### y {#y}
```
public double y
```


El componente y.

### add(Vector2 lhs, Vector2 rhs) {#add-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static Vector2 add(Vector2 lhs, Vector2 rhs)
```


Operador de suma para Vector2

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Valor del lado izquierdo. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Valor del lado derecho. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of addition.
### clone() {#clone--}
```
public Vector2 clone()
```


Clonar la instancia actual

**Returns:**
[Vector2](../../com.aspose.threed/vector2)
### compareTo(Vector2 other) {#compareTo-com.aspose.threed.Vector2-}
```
public int compareTo(Vector2 other)
```


Compara el vector actual con otra instancia.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
int
### copyFrom(Vector2 src) {#copyFrom-com.aspose.threed.Vector2-}
```
public void copyFrom(Vector2 src)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| src | [Vector2](../../com.aspose.threed/vector2) |  |

### create(Vector2 v) {#create-com.aspose.threed.Vector2-}
```
public static FVector2 create(Vector2 v)
```


Operador de conversión explícita para convertir Vector2 a FVector2

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| v | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2)
### cross(Vector2 v) {#cross-com.aspose.threed.Vector2-}
```
public double cross(Vector2 v)
```


Producto cruzado de dos vectores.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| v | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
double
### div(Vector2 lhs, double rhs) {#div-com.aspose.threed.Vector2-double-}
```
public static Vector2 div(Vector2 lhs, double rhs)
```


Operador de división para Vector2

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Valor del lado izquierdo. |
| rhs | double | Valor del lado derecho. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of division.
### dot(Vector2 rhs) {#dot-com.aspose.threed.Vector2-}
```
public double dot(Vector2 rhs)
```


Obtiene el producto punto de dos vectores.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Valor del lado derecho. |

**Returns:**
double - El producto punto de los dos vectores.
### equals(Vector2 rhs) {#equals-com.aspose.threed.Vector2-}
```
public boolean equals(Vector2 rhs)
```


Comprobar si dos vector2 son iguales

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rhs | [Vector2](../../com.aspose.threed/vector2) | El valor del lado derecho. |

**Returns:**
boolean - Verdadero si todos los componentes son idénticamente iguales.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Comprobar si dos vector2 son iguales

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El objeto a comparar. |

**Returns:**
boolean - Verdadero si todos los componentes son idénticamente iguales.
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


Obtiene la longitud.

**Returns:**
double - la longitud.
### getU() {#getU--}
```
public double getU()
```


Obtiene el componente U si el [Vector2](../../com.aspose.threed/vector2) se usa como coordenada de mapeo. Es un alias del componente x.

**Returns:**
double - el componente U si el [Vector2](../../com.aspose.threed/vector2) se usa como coordenada de mapeo. Es un alias del componente x.
### getV() {#getV--}
```
public double getV()
```


Obtiene el componente V si el [Vector2](../../com.aspose.threed/vector2) se usa como coordenada de mapeo. Es un alias del componente y.

**Returns:**
double - el componente V si el [Vector2](../../com.aspose.threed/vector2) se usa como coordenada de mapeo. Es un alias del componente y.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Obtiene el código hash de Vector2

**Returns:**
int - El código hash del [Vector2](../../com.aspose.threed/vector2)
### mul(Vector2 lhs, double rhs) {#mul-com.aspose.threed.Vector2-double-}
```
public static Vector2 mul(Vector2 lhs, double rhs)
```


Operador de multiplicación para Vector2

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Valor del lado izquierdo. |
| rhs | double | Valor del lado derecho. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of multiply.
### mul(double lhs, Vector2 rhs) {#mul-double-com.aspose.threed.Vector2-}
```
public static Vector2 mul(double lhs, Vector2 rhs)
```


Operador de multiplicación para Vector2

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs | double | Valor del lado izquierdo. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Valor del lado derecho. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of multiply.
### normalize() {#normalize--}
```
public Vector2 normalize()
```


Normaliza esta instancia.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - Normalized vector.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_eq(Vector2 lhs, Vector2 rhs) {#op-eq-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static boolean op_eq(Vector2 lhs, Vector2 rhs)
```


Operador de igualdad para Vector2

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Valor del lado izquierdo. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Valor del lado derecho. |

**Returns:**
boolean - Verdadero si todos los componentes son idénticamente iguales.
### op_ne(Vector2 lhs, Vector2 rhs) {#op-ne-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static boolean op_ne(Vector2 lhs, Vector2 rhs)
```


Operador de desigualdad para Vector2

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Valor del lado izquierdo. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Valor del lado derecho. |

**Returns:**
boolean - Verdadero si dos vectores no son iguales.
### setU(double value) {#setU-double-}
```
public void setU(double value)
```


Establece el componente U si el [Vector2](../../com.aspose.threed/vector2) se usa como coordenada de mapeo. Es un alias del componente x.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor |

### setV(double value) {#setV-double-}
```
public void setV(double value)
```


Establece el componente V si el [Vector2](../../com.aspose.threed/vector2) se usa como coordenada de mapeo. Es un alias del componente y.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor |

### sub(Vector2 lhs, Vector2 rhs) {#sub-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static Vector2 sub(Vector2 lhs, Vector2 rhs)
```


Operador de sustracción para Vector2

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Valor del lado izquierdo. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Valor del lado derecho. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of substraction.
### toString() {#toString--}
```
public String toString()
```


Devuelve un java.lang.String que representa el [Vector2](../../com.aspose.threed/vector2) actual.

**Returns:**
java.lang.String - Un java.lang.String que representa el [Vector2](../../com.aspose.threed/vector2) actual.
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

