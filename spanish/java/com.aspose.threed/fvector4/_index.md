---
title: FVector4
second_title: Referencia de API de Aspose.3D para Java
description: Un vector flotante con cuatro componentes.
type: docs
weight: 61
url: /es/java/com.aspose.threed/fvector4/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class FVector4 implements Struct<FVector4>, Serializable
```

Un vector flotante con cuatro componentes.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [FVector4(float x, float y, float z, float w)](#FVector4-float-float-float-float-) | Inicializa una nueva instancia de [FVector4](../../com.aspose.threed/fvector4). |
| [FVector4(float x, float y, float z)](#FVector4-float-float-float-) | Inicializa una nueva instancia de [FVector4](../../com.aspose.threed/fvector4). |
| [FVector4(Color color)](#FVector4-java.awt.Color-) | Inicializa una nueva instancia de [FVector4](../../com.aspose.threed/fvector4). |
| [FVector4(Vector4 vec)](#FVector4-com.aspose.threed.Vector4-) | Inicializa una nueva instancia de [FVector4](../../com.aspose.threed/fvector4). |
| [FVector4(Vector3 vec)](#FVector4-com.aspose.threed.Vector3-) | Inicializa una nueva instancia de [FVector4](../../com.aspose.threed/fvector4). |
| [FVector4(Vector3 vec, float w)](#FVector4-com.aspose.threed.Vector3-float-) | Inicializa una nueva instancia de [FVector4](../../com.aspose.threed/fvector4). |
| [FVector4()](#FVector4--) |  |
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
| [add(FVector4 lhs, FVector4 rhs)](#add-com.aspose.threed.FVector4-com.aspose.threed.FVector4-) | Sobrecarga de operador para + |
| [clone()](#clone--) |  |
| [copyFrom(FVector4 src)](#copyFrom-com.aspose.threed.FVector4-) |  |
| [create(FVector4 v)](#create-com.aspose.threed.FVector4-) | Operador de conversión explícita para convertir Vector4 a FVector4 |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [mul(FVector4 lhs, FVector4 rhs)](#mul-com.aspose.threed.FVector4-com.aspose.threed.FVector4-) | Sobrecarga de operador para \* |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [sub(FVector4 lhs, FVector4 rhs)](#sub-com.aspose.threed.FVector4-com.aspose.threed.FVector4-) | Sobrecarga de operador para - (menos) |
| [toString()](#toString--) | Devuelve una cadena que representa el [FVector4](../../com.aspose.threed/fvector4) |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FVector4(float x, float y, float z, float w) {#FVector4-float-float-float-float-}
```
public FVector4(float x, float y, float z, float w)
```


Inicializa una nueva instancia de [FVector4](../../com.aspose.threed/fvector4).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | Componente X |
| y | float | Componente Y |
| z | float | Componente Z |
| w | float | Componente W |

### FVector4(float x, float y, float z) {#FVector4-float-float-float-}
```
public FVector4(float x, float y, float z)
```


Inicializa una nueva instancia de [FVector4](../../com.aspose.threed/fvector4).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | Componente X |
| y | float | Componente Y |
| z | float | Componente Z |

### FVector4(Color color) {#FVector4-java.awt.Color-}
```
public FVector4(Color color)
```


Inicializa una nueva instancia de [FVector4](../../com.aspose.threed/fvector4).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| color | java.awt.Color |  |

### FVector4(Vector4 vec) {#FVector4-com.aspose.threed.Vector4-}
```
public FVector4(Vector4 vec)
```


Inicializa una nueva instancia de [FVector4](../../com.aspose.threed/fvector4).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vec | [Vector4](../../com.aspose.threed/vector4) |  |

### FVector4(Vector3 vec) {#FVector4-com.aspose.threed.Vector3-}
```
public FVector4(Vector3 vec)
```


Inicializa una nueva instancia de [FVector4](../../com.aspose.threed/fvector4).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) |  |

### FVector4(Vector3 vec, float w) {#FVector4-com.aspose.threed.Vector3-float-}
```
public FVector4(Vector3 vec, float w)
```


Inicializa una nueva instancia de [FVector4](../../com.aspose.threed/fvector4).

**Parameters:**
| Parámetro | Tipo | Descripción |
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


El componente w.

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

### z {#z}
```
public float z
```


El componente z.

### add(FVector4 lhs, FVector4 rhs) {#add-com.aspose.threed.FVector4-com.aspose.threed.FVector4-}
```
public static FVector4 add(FVector4 lhs, FVector4 rhs)
```


Sobrecarga de operador para +

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs | [FVector4](../../com.aspose.threed/fvector4) | El vector izquierdo |
| rhs | [FVector4](../../com.aspose.threed/fvector4) | El vector derecho |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4) - Result vector
### clone() {#clone--}
```
public FVector4 clone()
```


Clonar la instancia actual

**Returns:**
[FVector4](../../com.aspose.threed/fvector4)
### copyFrom(FVector4 src) {#copyFrom-com.aspose.threed.FVector4-}
```
public void copyFrom(FVector4 src)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| src | [FVector4](../../com.aspose.threed/fvector4) |  |

### create(FVector4 v) {#create-com.aspose.threed.FVector4-}
```
public static Vector4 create(FVector4 v)
```


Operador de conversión explícita para convertir Vector4 a FVector4

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| v | [FVector4](../../com.aspose.threed/fvector4) |  |

**Returns:**
[Vector4](../../com.aspose.threed/vector4)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




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




**Returns:**
int
### mul(FVector4 lhs, FVector4 rhs) {#mul-com.aspose.threed.FVector4-com.aspose.threed.FVector4-}
```
public static FVector4 mul(FVector4 lhs, FVector4 rhs)
```


Sobrecarga de operador para \*

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs | [FVector4](../../com.aspose.threed/fvector4) | El vector izquierdo |
| rhs | [FVector4](../../com.aspose.threed/fvector4) | El vector derecho |

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


Sobrecarga de operador para - (menos)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs | [FVector4](../../com.aspose.threed/fvector4) | El vector izquierdo |
| rhs | [FVector4](../../com.aspose.threed/fvector4) | El vector derecho |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4) - Result vector
### toString() {#toString--}
```
public String toString()
```


Devuelve una cadena que representa el [FVector4](../../com.aspose.threed/fvector4)

**Returns:**
java.lang.String - La representación en cadena del vector actual.
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

