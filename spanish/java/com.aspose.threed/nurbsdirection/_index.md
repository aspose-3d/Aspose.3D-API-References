---
title: NurbsDirection
second_title: Referencia de API de Aspose.3D para Java
description: Un 3D  tiene dos direcciones, la  y la , la  define datos para cada dirección.
type: docs
weight: 113
url: /es/java/com.aspose.threed/nurbsdirection/
---

**Inheritance:**
java.lang.Object
```
public class NurbsDirection
```

Un 3D [NurbsSurface](../../com.aspose.threed/nurbssurface) tiene dos direcciones, el [NurbsSurface.getU](../../com.aspose.threed/nurbssurface\#getU) y el [NurbsSurface.getV](../../com.aspose.threed/nurbssurface\#getV), el [NurbsDirection](../../com.aspose.threed/nurbsdirection) define datos para cada dirección. Una dirección es en realidad una curva NURBS, lo que significa que también está definida por su [getOrder](../../com.aspose.threed/nurbsdirection\#getOrder), un [getKnotVectors](../../com.aspose.threed/nurbsdirection\#getKnotVectors), y un conjunto de puntos de control ponderados (definidos en [NurbsSurface](../../com.aspose.threed/nurbssurface)).
## Constructores

| Constructor | Descripción |
| --- | --- |
| [NurbsDirection()](#NurbsDirection--) | Crea una nueva instancia de [NurbsDirection](../../com.aspose.threed/nurbsdirection) |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Obtiene el recuento de puntos de control en la dirección actual. |
| [getDegree()](#getDegree--) | Obtiene el grado de una curva NURBS, el grado se define como Orden - 1 |
| [getDivisions()](#getDivisions--) | Obtiene el número de divisiones entre puntos de control adyacentes en la dirección actual. |
| [getKnotVectors()](#getKnotVectors--) | Obtiene el vector de nudos, es una secuencia de valores de parámetros que determina dónde y cómo los puntos de control afectan a la curva NURBS. |
| [getMultiplicity()](#getMultiplicity--) | Obtiene la multiplicidad. |
| [getOrder()](#getOrder--) | Obtiene el orden de una curva NURBS, define la cantidad de puntos de control cercanos que influyen en cualquier punto de la curva. |
| [getType()](#getType--) | Obtiene el tipo de la dirección actual. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCount(int value)](#setCount-int-) | Establece el recuento de puntos de control en la dirección actual. |
| [setDegree(int value)](#setDegree-int-) | Establece el grado de una curva NURBS, el grado se define como Orden - 1 |
| [setDivisions(int value)](#setDivisions-int-) | Establece el número de divisiones entre puntos de control adyacentes en la dirección actual. |
| [setOrder(int value)](#setOrder-int-) | Establece el orden de una curva NURBS, define la cantidad de puntos de control cercanos que influyen en cualquier punto de la curva. |
| [setType(NurbsType value)](#setType-com.aspose.threed.NurbsType-) | Establece el tipo de la dirección actual. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NurbsDirection() {#NurbsDirection--}
```
public NurbsDirection()
```


Crea una nueva instancia de [NurbsDirection](../../com.aspose.threed/nurbsdirection)

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public int getCount()
```


Obtiene el recuento de puntos de control en la dirección actual.

**Returns:**
int - el recuento de puntos de control en la dirección actual.
### getDegree() {#getDegree--}
```
public int getDegree()
```


Obtiene el grado de una curva NURBS, el grado se define como Orden - 1

**Returns:**
int - el grado de una curva NURBS, el grado se define como Orden - 1
### getDivisions() {#getDivisions--}
```
public int getDivisions()
```


Obtiene el número de divisiones entre puntos de control adyacentes en la dirección actual.

**Returns:**
int - el número de divisiones entre puntos de control adyacentes en la dirección actual.
### getKnotVectors() {#getKnotVectors--}
```
public List<Double> getKnotVectors()
```


Obtiene el vector de nudos, es una secuencia de valores de parámetros que determina dónde y cómo los puntos de control afectan a la curva NURBS.

**Returns:**
java.util.List<java.lang.Double> - el vector de nudos, es una secuencia de valores de parámetros que determina dónde y cómo los puntos de control afectan a la curva NURBS.
### getMultiplicity() {#getMultiplicity--}
```
public List<Integer> getMultiplicity()
```


Obtiene la multiplicidad.

**Returns:**
java.util.List<java.lang.Integer> - la multiplicidad.
### getOrder() {#getOrder--}
```
public int getOrder()
```


Obtiene el orden de una curva NURBS, define la cantidad de puntos de control cercanos que influyen en cualquier punto de la curva.

**Returns:**
int - el orden de una curva NURBS, define el número de puntos de control cercanos que influyen en cualquier punto de la curva.
### getType() {#getType--}
```
public NurbsType getType()
```


Obtiene el tipo de la dirección actual.

**Returns:**
[NurbsType](../../com.aspose.threed/nurbstype) - the type of the current direction.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setCount(int value) {#setCount-int-}
```
public void setCount(int value)
```


Establece el recuento de puntos de control en la dirección actual.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Nuevo valor |

### setDegree(int value) {#setDegree-int-}
```
public void setDegree(int value)
```


Establece el grado de una curva NURBS, el grado se define como Orden - 1

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Nuevo valor |

### setDivisions(int value) {#setDivisions-int-}
```
public void setDivisions(int value)
```


Establece el número de divisiones entre puntos de control adyacentes en la dirección actual.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Nuevo valor |

### setOrder(int value) {#setOrder-int-}
```
public void setOrder(int value)
```


Establece el orden de una curva NURBS, define la cantidad de puntos de control cercanos que influyen en cualquier punto de la curva.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Nuevo valor |

### setType(NurbsType value) {#setType-com.aspose.threed.NurbsType-}
```
public void setType(NurbsType value)
```


Establece el tipo de la dirección actual.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [NurbsType](../../com.aspose.threed/nurbstype) | Nuevo valor |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

