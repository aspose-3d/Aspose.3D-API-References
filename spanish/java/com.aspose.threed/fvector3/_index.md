---
title: FVector3
second_title: Referencia de API de Aspose.3D para Java
description: Un vector flotante con tres componentes.
type: docs
weight: 60
url: /es/java/com.aspose.threed/fvector3/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class FVector3 implements Struct<FVector3>, Serializable
```

Un vector flotante con tres componentes.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [FVector3(float x, float y, float z)](#FVector3-float-float-float-) | Inicializa una nueva instancia de [FVector3](../../com.aspose.threed/fvector3). |
| [FVector3(Vector3 vec)](#FVector3-com.aspose.threed.Vector3-) | Inicializa una nueva instancia de [FVector3](../../com.aspose.threed/fvector3). |
| [FVector3(Vector4 vec)](#FVector3-com.aspose.threed.Vector4-) | Inicializa una nueva instancia de [FVector4](../../com.aspose.threed/fvector4). |
| [FVector3()](#FVector3--) |  |
## Campos

| Campo | Descripción |
| --- | --- |
| [x](#x) | El componente x. |
| [y](#y) | El componente y. |
| [z](#z) | El componente y. |
## Métodos

| Método | Descripción |
| --- | --- |
| [add(FVector3 a, FVector3 b)](#add-com.aspose.threed.FVector3-com.aspose.threed.FVector3-) | \+ Sobrecarga de operadores |
| [clone()](#clone--) |  |
| [copyFrom(FVector3 src)](#copyFrom-com.aspose.threed.FVector3-) |  |
| [create(FVector3 v)](#create-com.aspose.threed.FVector3-) | Operador de conversión explícita para convertir FVector3 a Vector3 |
| [cross(FVector3 rhs)](#cross-com.aspose.threed.FVector3-) | Producto cruzado de dos vectores. |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOne()](#getOne--) | El vector de escala unitario con todos los componentes iguales a 1 |
| [getZero()](#getZero--) | El vector cero. |
| [hashCode()](#hashCode--) |  |
| [mul(FVector3 a, float b)](#mul-com.aspose.threed.FVector3-float-) | \* Sobrecarga de operadores |
| [negative(FVector3 a)](#negative-com.aspose.threed.FVector3-) | \- Sobrecarga de operadores |
| [normalize()](#normalize--) | Normaliza esta instancia. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [sub(FVector3 a, FVector3 b)](#sub-com.aspose.threed.FVector3-com.aspose.threed.FVector3-) | \- Sobrecarga de operadores |
| [toString()](#toString--) | Devuelve una cadena que representa a [FVector3](../../com.aspose.threed/fvector3) |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FVector3(float x, float y, float z) {#FVector3-float-float-float-}
```
public FVector3(float x, float y, float z)
```


Inicializa una nueva instancia de [FVector3](../../com.aspose.threed/fvector3).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | Componente X del vector |
| y | float | Componente Y del vector |
| z | float | Componente Z del vector |

### FVector3(Vector3 vec) {#FVector3-com.aspose.threed.Vector3-}
```
public FVector3(Vector3 vec)
```


Inicializa una nueva instancia de [FVector3](../../com.aspose.threed/fvector3).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) | Vector3 en tipo double |

### FVector3(Vector4 vec) {#FVector3-com.aspose.threed.Vector4-}
```
public FVector3(Vector4 vec)
```


Inicializa una nueva instancia de [FVector4](../../com.aspose.threed/fvector4).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vec | [Vector4](../../com.aspose.threed/vector4) | Vector4 en tipo double |

### FVector3() {#FVector3--}
```
public FVector3()
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

### z {#z}
```
public float z
```


El componente y.

### add(FVector3 a, FVector3 b) {#add-com.aspose.threed.FVector3-com.aspose.threed.FVector3-}
```
public static FVector3 add(FVector3 a, FVector3 b)
```


\+ Sobrecarga de operadores

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | Primer vector |
| b | [FVector3](../../com.aspose.threed/fvector3) | Segundo vector |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### clone() {#clone--}
```
public FVector3 clone()
```


Clonar la instancia actual

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### copyFrom(FVector3 src) {#copyFrom-com.aspose.threed.FVector3-}
```
public void copyFrom(FVector3 src)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| src | [FVector3](../../com.aspose.threed/fvector3) |  |

### create(FVector3 v) {#create-com.aspose.threed.FVector3-}
```
public static Vector3 create(FVector3 v)
```


Operador de conversión explícita para convertir FVector3 a Vector3

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| v | [FVector3](../../com.aspose.threed/fvector3) | Vector3 en tipo float |

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### cross(FVector3 rhs) {#cross-com.aspose.threed.FVector3-}
```
public FVector3 cross(FVector3 rhs)
```


Producto cruzado de dos vectores.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rhs | [FVector3](../../com.aspose.threed/fvector3) | Valor del lado derecho. |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Cross product of two [FVector3](../../com.aspose.threed/fvector3)s.
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
### getOne() {#getOne--}
```
public static FVector3 getOne()
```


El vector de escala unitario con todos los componentes iguales a 1

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The unit scale vector with all components are all 1
### getZero() {#getZero--}
```
public static FVector3 getZero()
```


El vector cero.

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


\* Sobrecarga de operadores

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | Primer vector |
| b | float | Segundo vector |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The product of two vectors
### negative(FVector3 a) {#negative-com.aspose.threed.FVector3-}
```
public static FVector3 negative(FVector3 a)
```


\- Sobrecarga de operadores

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | Vector de entrada |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The negative vector
### normalize() {#normalize--}
```
public FVector3 normalize()
```


Normaliza esta instancia.

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


\- Sobrecarga de operadores

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | Primer vector |
| b | [FVector3](../../com.aspose.threed/fvector3) | Segundo vector |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The difference of two vectors
### toString() {#toString--}
```
public String toString()
```


Devuelve una cadena que representa a [FVector3](../../com.aspose.threed/fvector3)

**Returns:**
java.lang.String - Representación en cadena de este vector.
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

