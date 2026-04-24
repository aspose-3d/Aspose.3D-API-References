---
title: Vector4
second_title: Referencia de API de Aspose.3D para Java
description: Un vector con cuatro componentes.
type: docs
weight: 203
url: /es/java/com.aspose.threed/vector4/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.threed.Struct, java.io.Serializable
```
public final class Vector4 implements Comparable<Vector4>, Struct<Vector4>, Serializable
```

Un vector con cuatro componentes.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Vector4(Vector3 vec, double w)](#Vector4-com.aspose.threed.Vector3-double-) | Inicializa una nueva instancia de la estructura [Vector4](../../com.aspose.threed/vector4). |
| [Vector4(Vector3 vec)](#Vector4-com.aspose.threed.Vector3-) | Inicializa una nueva instancia de la estructura [Vector4](../../com.aspose.threed/vector4). |
| [Vector4(FVector4 vec)](#Vector4-com.aspose.threed.FVector4-) | Inicializa una nueva instancia de la estructura [Vector4](../../com.aspose.threed/vector4). |
| [Vector4(double x, double y, double z)](#Vector4-double-double-double-) | Inicializa una nueva instancia de la estructura [Vector4](../../com.aspose.threed/vector4). |
| [Vector4(double x, double y, double z, double w)](#Vector4-double-double-double-double-) | Inicializa una nueva instancia de la estructura [Vector4](../../com.aspose.threed/vector4). |
| [Vector4()](#Vector4--) |  |
## Campos

| Campo | Descripción |
| --- | --- |
| [w](#w) | El componente w. |
| [x](#x) | El componente x. |
| [y](#y) | El componente y. |
| [z](#z) | El componente z. |
## Métodos

| Método | Descripción |
| --- | --- |
| [add(Vector4 lhs, Vector4 rhs)](#add-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | Sobrecarga de operador para + |
| [clone()](#clone--) |  |
| [compareTo(Vector4 other)](#compareTo-com.aspose.threed.Vector4-) | Compara el vector actual con otra instancia. |
| [copyFrom(Vector4 src)](#copyFrom-com.aspose.threed.Vector4-) |  |
| [create(Vector4 v)](#create-com.aspose.threed.Vector4-) | Operador de conversión explícita para convertir Vector4 a FVector4 |
| [equals(Object obj)](#equals-java.lang.Object-) | Comprobar si dos vectores son iguales |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | Obtiene el código hash de este vector |
| [mul(Vector4 lhs, Vector4 rhs)](#mul-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | Sobrecarga de operador para \* |
| [mul(Vector4 lhs, double rhs)](#mul-com.aspose.threed.Vector4-double-) | Sobrecarga de operador para \* |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [set(double newX, double newY, double newZ)](#set-double-double-double-) | Establece los componentes xyz del vector de una vez, w se establecerá en 1 |
| [set(double newX, double newY, double newZ, double newW)](#set-double-double-double-double-) | Establece todos los componentes del vector de una vez |
| [sub(Vector4 lhs, Vector4 rhs)](#sub-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | Sobrecarga de operador para - (menos) |
| [toString()](#toString--) | Devuelve un java.lang.String que representa el [Vector4](../../com.aspose.threed/vector4) actual. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Vector4(Vector3 vec, double w) {#Vector4-com.aspose.threed.Vector3-double-}
```
public Vector4(Vector3 vec, double w)
```


Inicializa una nueva instancia de la estructura [Vector4](../../com.aspose.threed/vector4).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) | Vec. |
| w | double | El ancho. |

### Vector4(Vector3 vec) {#Vector4-com.aspose.threed.Vector3-}
```
public Vector4(Vector3 vec)
```


Inicializa una nueva instancia de la estructura [Vector4](../../com.aspose.threed/vector4).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) | Vec. |

### Vector4(FVector4 vec) {#Vector4-com.aspose.threed.FVector4-}
```
public Vector4(FVector4 vec)
```


Inicializa una nueva instancia de la estructura [Vector4](../../com.aspose.threed/vector4).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vec | [FVector4](../../com.aspose.threed/fvector4) | Vec. |

### Vector4(double x, double y, double z) {#Vector4-double-double-double-}
```
public Vector4(double x, double y, double z)
```


Inicializa una nueva instancia de la estructura [Vector4](../../com.aspose.threed/vector4).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | double | La coordenada x. |
| y | double | La coordenada y. |
| z | double | La coordenada z. |

### Vector4(double x, double y, double z, double w) {#Vector4-double-double-double-double-}
```
public Vector4(double x, double y, double z, double w)
```


Inicializa una nueva instancia de la estructura [Vector4](../../com.aspose.threed/vector4).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | double | La coordenada x. |
| y | double | La coordenada y. |
| z | double | La coordenada z. |
| w | double | El ancho. |

### Vector4() {#Vector4--}
```
public Vector4()
```


### w {#w}
```
public double w
```


El componente w.

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

### add(Vector4 lhs, Vector4 rhs) {#add-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public static Vector4 add(Vector4 lhs, Vector4 rhs)
```


Sobrecarga de operador para +

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | El vector izquierdo |
| rhs | [Vector4](../../com.aspose.threed/vector4) | El vector derecho |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### clone() {#clone--}
```
public Vector4 clone()
```


Clonar la instancia actual

**Returns:**
[Vector4](../../com.aspose.threed/vector4)
### compareTo(Vector4 other) {#compareTo-com.aspose.threed.Vector4-}
```
public int compareTo(Vector4 other)
```


Compara el vector actual con otra instancia.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | [Vector4](../../com.aspose.threed/vector4) |  |

**Returns:**
int
### copyFrom(Vector4 src) {#copyFrom-com.aspose.threed.Vector4-}
```
public void copyFrom(Vector4 src)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| src | [Vector4](../../com.aspose.threed/vector4) |  |

### create(Vector4 v) {#create-com.aspose.threed.Vector4-}
```
public static FVector4 create(Vector4 v)
```


Operador de conversión explícita para convertir Vector4 a FVector4

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| v | [Vector4](../../com.aspose.threed/vector4) |  |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4)
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


Obtiene el código hash de este vector

**Returns:**
int
### mul(Vector4 lhs, Vector4 rhs) {#mul-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public static Vector4 mul(Vector4 lhs, Vector4 rhs)
```


Sobrecarga de operador para \*

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | El vector izquierdo |
| rhs | [Vector4](../../com.aspose.threed/vector4) | El vector derecho |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### mul(Vector4 lhs, double rhs) {#mul-com.aspose.threed.Vector4-double-}
```
public static Vector4 mul(Vector4 lhs, double rhs)
```


Sobrecarga de operador para \*

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | El vector izquierdo |
| rhs | double | El valor doble de la derecha |

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


Establece los componentes xyz del vector de una vez, w se establecerá en 1

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newX | double | Nuevo componente X. |
| newY | double | Nuevo componente Y. |
| newZ | double | Nuevo componente Z. |

### set(double newX, double newY, double newZ, double newW) {#set-double-double-double-double-}
```
public void set(double newX, double newY, double newZ, double newW)
```


Establece todos los componentes del vector de una vez

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newX | double | Nuevo componente X. |
| newY | double | Nuevo componente Y. |
| newZ | double | Nuevo componente Z. |
| newW | double | Nuevo componente W. |

### sub(Vector4 lhs, Vector4 rhs) {#sub-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public static Vector4 sub(Vector4 lhs, Vector4 rhs)
```


Sobrecarga de operador para - (menos)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | El vector izquierdo |
| rhs | [Vector4](../../com.aspose.threed/vector4) | El vector derecho |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### toString() {#toString--}
```
public String toString()
```


Devuelve un java.lang.String que representa el [Vector4](../../com.aspose.threed/vector4) actual.

**Returns:**
java.lang.String - Un java.lang.String que representa el [Vector4](../../com.aspose.threed/vector4) actual.
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

