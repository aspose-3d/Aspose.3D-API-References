---
title: PatchDirectionType
second_title: Referencia de API de Aspose.3D para Java
description: Tipos de direcciones de parche.
type: docs
weight: 287
url: /es/java/com.aspose.threed/patchdirectiontype/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PatchDirectionType extends Enum<PatchDirectionType>
```

Tipos de dirección del parche.
## Campos

| Campo | Descripción |
| --- | --- |
|  | [BASIS_SPLINE](#BASIS-SPLINE) | [La dirección del parche es una spline base.][] |


[The patch direction is a basis spline.]: https://en.wikipedia.org/wiki/B-spline |
|  | [BEZIER](#BEZIER) | [La dirección del parche es una curva Bézier.][] |


[The patch direction is a Bezier curve.]: https://en.wikipedia.org/wiki/B%C3%A9zier_curve |
| [CARDINAL_SPLINE](#CARDINAL-SPLINE) | parche cardinal. |
|  | [LINEAR](#LINEAR) | [La dirección del parche es una curva lineal.][] |


[The patch direction is a linear curve.]: https://en.wikipedia.org/wiki/B%C3%A9zier_curve#Linear_curves |
| [QUADRATIC_BEZIER](#QUADRATIC-BEZIER) | El parche Bézier cuadrático. |
## Métodos

| Método | Descripción |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BASIS_SPLINE {#BASIS-SPLINE}
```
public static final PatchDirectionType BASIS_SPLINE
```


[The patch direction is a basis spline.][]


[The patch direction is a basis spline.]: https://en.wikipedia.org/wiki/B-spline

### BEZIER {#BEZIER}
```
public static final PatchDirectionType BEZIER
```


[The patch direction is a Bezier curve.][]


[The patch direction is a Bezier curve.]: https://en.wikipedia.org/wiki/B%C3%A9zier_curve

### CARDINAL_SPLINE {#CARDINAL-SPLINE}
```
public static final PatchDirectionType CARDINAL_SPLINE
```


parche cardinal. [La dirección del parche es una spline cardinal.][]


[The patch direction is a cardinal spline.]: https://en.wikipedia.org/wiki/Cubic_Hermite_spline#Cardinal_spline

### LINEAR {#LINEAR}
```
public static final PatchDirectionType LINEAR
```


[The patch direction is a linear curve.][]


[The patch direction is a linear curve.]: https://en.wikipedia.org/wiki/B%C3%A9zier_curve#Linear_curves

### QUADRATIC_BEZIER {#QUADRATIC-BEZIER}
```
public static final PatchDirectionType QUADRATIC_BEZIER
```


El parche Bézier cuadrático. [La dirección del parche es una curva cuadrática.][]


[The patch direction is a quadratic curve.]: https://en.wikipedia.org/wiki/B%C3%A9zier_curve#Quadratic_curves

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
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
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PatchDirectionType valueOf(String name)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String |  |

**Returns:**
[PatchDirectionType](../../com.aspose.threed/patchdirectiontype)
### values() {#values--}
```
public static PatchDirectionType[] values()
```




**Returns:**
com.aspose.threed.PatchDirectionType[]
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

