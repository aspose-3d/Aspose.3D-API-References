---
title: Vector3
second_title: Referencia de API de Aspose.3D para Java
description: Un vector con tres componentes.
type: docs
weight: 202
url: /es/java/com.aspose.threed/vector3/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.threed.Struct, java.io.Serializable
```
public final class Vector3 implements Comparable<Vector3>, Struct<Vector3>, Serializable
```

Un vector con tres componentes.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Vector3(double x, double y, double z)](#Vector3-double-double-double-) | Inicializa una nueva instancia de la estructura [Vector3](../../com.aspose.threed/vector3). |
| [Vector3(FVector3 vec)](#Vector3-com.aspose.threed.FVector3-) | Inicializa una nueva instancia de la estructura [Vector3](../../com.aspose.threed/vector3). |
| [Vector3(double v)](#Vector3-double-) | Inicializa una nueva instancia de la estructura [Vector3](../../com.aspose.threed/vector3). |
| [Vector3(Vector4 vec4)](#Vector3-com.aspose.threed.Vector4-) | Inicializa una nueva instancia de la estructura [Vector3](../../com.aspose.threed/vector3). |
| [Vector3()](#Vector3--) |  |
## Campos

| Campo | Descripción |
| --- | --- |
| [x](#x) | El componente x. |
| [y](#y) | El componente y. |
| [z](#z) | El componente z. |
## Métodos

| Método | Descripción |
| --- | --- |
| [add(Vector3 lhs, Vector3 rhs)](#add-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Sobrecarga de operador para + |
| [angleBetween(Vector3 dir)](#angleBetween-com.aspose.threed.Vector3-) | Calcula el ángulo interno entre dos direcciones. Las dos direcciones pueden ser vectores no normalizados. |
| [angleBetween(Vector3 dir, Vector3 up)](#angleBetween-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Calcula el ángulo interno entre dos direcciones. Las dos direcciones pueden ser vectores no normalizados. |
| [clone()](#clone--) |  |
| [compareTo(Vector3 other)](#compareTo-com.aspose.threed.Vector3-) | Compara el vector actual con otra instancia. |
| [copyFrom(Vector3 src)](#copyFrom-com.aspose.threed.Vector3-) |  |
| [cos()](#cos--) | Calcula el coseno en cada componente. |
| [create(Vector3 v)](#create-com.aspose.threed.Vector3-) | Operador de conversión explícita para convertir Vector3 a FVector3. |
| [cross(Vector3 rhs)](#cross-com.aspose.threed.Vector3-) | Producto cruzado de dos vectores. |
| [div(Vector3 lhs, Vector3 rhs)](#div-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Sobrecarga de operador para / |
| [div(Vector3 lhs, double rhs)](#div-com.aspose.threed.Vector3-double-) | Sobrecarga de operador para / |
| [dot(Vector3 rhs)](#dot-com.aspose.threed.Vector3-) | Obtiene el producto punto de dos vectores. |
| [equals(Object obj)](#equals-java.lang.Object-) | Comprueba si dos vector3 son iguales. |
| [get(int idx)](#get-int-) | Obtiene el componente del vector por índice. |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Obtiene la longitud de este vector. |
| [getLength2()](#getLength2--) | Obtiene el cuadrado de la longitud. |
| [getOne()](#getOne--) | Obtiene el vector unitario (1, 1, 1). |
| [getUnitX()](#getUnitX--) | Obtiene el vector unitario (1, 0, 0). |
| [getUnitY()](#getUnitY--) | Obtiene el vector unitario (0, 1, 0). |
| [getUnitZ()](#getUnitZ--) | Obtiene el vector unitario (0, 0, 1). |
| [getZero()](#getZero--) | Obtiene el vector unitario (0, 0, 0). |
| [hashCode()](#hashCode--) | Obtiene el código hash de Vector3. |
| [mul(Vector3 lhs, Vector3 rhs)](#mul-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Sobrecarga de operador para \* |
| [mul(Vector3 lhs, double rhs)](#mul-com.aspose.threed.Vector3-double-) | Sobrecarga de operador para \* |
| [mul(double lhs, Vector3 rhs)](#mul-double-com.aspose.threed.Vector3-) | Sobrecarga de operador para \* |
| [negative(Vector3 v)](#negative-com.aspose.threed.Vector3-) | Sobrecarga de operador para - |
| [normalize()](#normalize--) | Normaliza esta instancia. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(Vector3 lhs, Vector3 rhs)](#op-eq-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Operador de igualdad para Vector3 |
| [op_ne(Vector3 lhs, Vector3 rhs)](#op-ne-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Operador de desigualdad para Vector3 |
| [set(double newX, double newY, double newZ)](#set-double-double-double-) | Establece el componente x/y/z en una sola llamada. |
| [set(int idx, double value)](#set-int-double-) | Establece el componente del vector por índice. |
| [sin()](#sin--) | Calcula el seno en cada componente |
| [sub(Vector3 lhs, Vector3 rhs)](#sub-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Sobrecarga de operador para - (menos) |
| [toString()](#toString--) | Devuelve un java.lang.String que representa el actual [Vector3](../../com.aspose.threed/vector3). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Vector3(double x, double y, double z) {#Vector3-double-double-double-}
```
public Vector3(double x, double y, double z)
```


Inicializa una nueva instancia de la estructura [Vector3](../../com.aspose.threed/vector3).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | double | La coordenada x. |
| y | double | La coordenada y. |
| z | double | La coordenada z. |

### Vector3(FVector3 vec) {#Vector3-com.aspose.threed.FVector3-}
```
public Vector3(FVector3 vec)
```


Inicializa una nueva instancia de la estructura [Vector3](../../com.aspose.threed/vector3).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vec | [FVector3](../../com.aspose.threed/fvector3) | La coordenada x. |

### Vector3(double v) {#Vector3-double-}
```
public Vector3(double v)
```


Inicializa una nueva instancia de la estructura [Vector3](../../com.aspose.threed/vector3).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| v | double | V. |

### Vector3(Vector4 vec4) {#Vector3-com.aspose.threed.Vector4-}
```
public Vector3(Vector4 vec4)
```


Inicializa una nueva instancia de la estructura [Vector3](../../com.aspose.threed/vector3).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vec4 | [Vector4](../../com.aspose.threed/vector4) | Vec4. |

### Vector3() {#Vector3--}
```
public Vector3()
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

### z {#z}
```
public double z
```


El componente z.

### add(Vector3 lhs, Vector3 rhs) {#add-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 add(Vector3 lhs, Vector3 rhs)
```


Sobrecarga de operador para +

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | El vector izquierdo |
| rhs | [Vector3](../../com.aspose.threed/vector3) | El vector derecho |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### angleBetween(Vector3 dir) {#angleBetween-com.aspose.threed.Vector3-}
```
public double angleBetween(Vector3 dir)
```


Calcula el ángulo interno entre dos direcciones. Las dos direcciones pueden ser vectores no normalizados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dir | [Vector3](../../com.aspose.threed/vector3) | El vector de dirección con el que comparar |

**Returns:**
double - ángulo interno en radianes
### angleBetween(Vector3 dir, Vector3 up) {#angleBetween-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public double angleBetween(Vector3 dir, Vector3 up)
```


Calcula el ángulo interno entre dos direcciones. Las dos direcciones pueden ser vectores no normalizados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dir | [Vector3](../../com.aspose.threed/vector3) | El vector de dirección con el que comparar |
| up | [Vector3](../../com.aspose.threed/vector3) | El vector ascendente del plano compartido de las dos direcciones |

**Returns:**
double - ángulo interno en radianes
### clone() {#clone--}
```
public Vector3 clone()
```


Clonar la instancia actual

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### compareTo(Vector3 other) {#compareTo-com.aspose.threed.Vector3-}
```
public int compareTo(Vector3 other)
```


Compara el vector actual con otra instancia.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
int
### copyFrom(Vector3 src) {#copyFrom-com.aspose.threed.Vector3-}
```
public void copyFrom(Vector3 src)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| src | [Vector3](../../com.aspose.threed/vector3) |  |

### cos() {#cos--}
```
public Vector3 cos()
```


Calcula el coseno en cada componente.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Calculated [Vector3](../../com.aspose.threed/vector3).
### create(Vector3 v) {#create-com.aspose.threed.Vector3-}
```
public static FVector3 create(Vector3 v)
```


Operador de conversión explícita para convertir Vector3 a FVector3.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### cross(Vector3 rhs) {#cross-com.aspose.threed.Vector3-}
```
public Vector3 cross(Vector3 rhs)
```


Producto cruzado de dos vectores.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Valor del lado derecho. |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Cross product of two [Vector3](../../com.aspose.threed/vector3)s.
### div(Vector3 lhs, Vector3 rhs) {#div-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 div(Vector3 lhs, Vector3 rhs)
```


Sobrecarga de operador para /

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | El vector izquierdo |
| rhs | [Vector3](../../com.aspose.threed/vector3) | El vector derecho |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### div(Vector3 lhs, double rhs) {#div-com.aspose.threed.Vector3-double-}
```
public static Vector3 div(Vector3 lhs, double rhs)
```


Sobrecarga de operador para /

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | El vector izquierdo |
| rhs | double | El valor doble de la derecha |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### dot(Vector3 rhs) {#dot-com.aspose.threed.Vector3-}
```
public double dot(Vector3 rhs)
```


Obtiene el producto punto de dos vectores.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Valor del lado derecho. |

**Returns:**
double - El producto punto de los dos vectores.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Comprueba si dos vector3 son iguales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El objeto para comprobar igualdad. |

**Returns:**
boolean - Verdadero si todos los componentes son idénticamente iguales.
### get(int idx) {#get-int-}
```
public double get(int idx)
```


Obtiene el componente del vector por índice.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| idx | int |  |

**Returns:**
double - componente del vector por índice.
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


Obtiene la longitud de este vector.

**Returns:**
double - la longitud de este vector.
### getLength2() {#getLength2--}
```
public double getLength2()
```


Obtiene el cuadrado de la longitud.

**Returns:**
double - el cuadrado de la longitud.
### getOne() {#getOne--}
```
public static Vector3 getOne()
```


Obtiene el vector unitario (1, 1, 1).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (1, 1, 1)
### getUnitX() {#getUnitX--}
```
public static Vector3 getUnitX()
```


Obtiene el vector unitario (1, 0, 0).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (1, 0, 0)
### getUnitY() {#getUnitY--}
```
public static Vector3 getUnitY()
```


Obtiene el vector unitario (0, 1, 0).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (0, 1, 0)
### getUnitZ() {#getUnitZ--}
```
public static Vector3 getUnitZ()
```


Obtiene el vector unitario (0, 0, 1).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (0, 0, 1)
### getZero() {#getZero--}
```
public static Vector3 getZero()
```


Obtiene el vector unitario (0, 0, 0).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (0, 0, 0)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Obtiene el código hash de Vector3.

**Returns:**
int - El código hash del [Vector3](../../com.aspose.threed/vector3)
### mul(Vector3 lhs, Vector3 rhs) {#mul-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 mul(Vector3 lhs, Vector3 rhs)
```


Sobrecarga de operador para \*

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | El vector izquierdo |
| rhs | [Vector3](../../com.aspose.threed/vector3) | El vector derecho |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### mul(Vector3 lhs, double rhs) {#mul-com.aspose.threed.Vector3-double-}
```
public static Vector3 mul(Vector3 lhs, double rhs)
```


Sobrecarga de operador para \*

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | El vector izquierdo |
| rhs | double | El valor doble de la derecha |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### mul(double lhs, Vector3 rhs) {#mul-double-com.aspose.threed.Vector3-}
```
public static Vector3 mul(double lhs, Vector3 rhs)
```


Sobrecarga de operador para \*

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs | double | El escalar izquierdo |
| rhs | [Vector3](../../com.aspose.threed/vector3) | El vector derecho |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### negative(Vector3 v) {#negative-com.aspose.threed.Vector3-}
```
public static Vector3 negative(Vector3 v)
```


Sobrecarga de operador para -

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) | El vector origen |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### normalize() {#normalize--}
```
public Vector3 normalize()
```


Normaliza esta instancia.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Normalized vector.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_eq(Vector3 lhs, Vector3 rhs) {#op-eq-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static boolean op_eq(Vector3 lhs, Vector3 rhs)
```


Operador de igualdad para Vector3

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Valor del lado izquierdo. |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Valor del lado derecho. |

**Returns:**
boolean - Verdadero si todos los componentes son idénticamente iguales.
### op_ne(Vector3 lhs, Vector3 rhs) {#op-ne-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static boolean op_ne(Vector3 lhs, Vector3 rhs)
```


Operador de desigualdad para Vector3

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Valor del lado izquierdo. |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Valor del lado derecho. |

**Returns:**
boolean - Verdadero si dos vectores no son iguales.
### set(double newX, double newY, double newZ) {#set-double-double-double-}
```
public void set(double newX, double newY, double newZ)
```


Establece el componente x/y/z en una sola llamada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newX | double | El componente x. |
| newY | double | El componente y. |
| newZ | double | El componente z. |

### set(int idx, double value) {#set-int-double-}
```
public void set(int idx, double value)
```


Establece el componente del vector por índice.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| idx | int |  |
| valor | double | Nuevo valor |

### sin() {#sin--}
```
public Vector3 sin()
```


Calcula el seno en cada componente

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Calculated [Vector3](../../com.aspose.threed/vector3).
### sub(Vector3 lhs, Vector3 rhs) {#sub-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 sub(Vector3 lhs, Vector3 rhs)
```


Sobrecarga de operador para - (menos)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | El vector izquierdo |
| rhs | [Vector3](../../com.aspose.threed/vector3) | El vector derecho |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### toString() {#toString--}
```
public String toString()
```


Devuelve un java.lang.String que representa el actual [Vector3](../../com.aspose.threed/vector3).

**Returns:**
java.lang.String - Un java.lang.String que representa el [Vector3](../../com.aspose.threed/vector3) actual.
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

