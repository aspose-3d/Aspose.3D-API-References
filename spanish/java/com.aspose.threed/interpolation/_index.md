---
title: Interpolaci\u00f3n
second_title: Referencia de API de Aspose.3D para Java
description: El tipo de interpolaci\u00f3n de los fotogramas clave.
type: docs
weight: 283
url: /es/java/com.aspose.threed/interpolation/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Interpolation extends Enum<Interpolation>
```

El tipo de interpolación del fotograma clave.
## Campos

| Campo | Descripción |
| --- | --- |
| [BEZIER](#BEZIER) | Una spline B\u00e9zier o Hermite. |
| [B_SPLINE](#B-SPLINE) | Los splines b\u00e1sicos se definen mediante una serie de puntos de control, para los cuales se garantiza que la curva solo pase por el primer y el \u00faltimo punto. |
| [CARDINAL_SPLINE](#CARDINAL-SPLINE) | Una spline cardinal es una spline cúbica de Hermite cuyas tangentes se definen por los puntos finales y un parámetro de tensión. |
| [CONSTANT](#CONSTANT) | El valor permanecerá constante al valor del primer punto hasta el siguiente segmento. |
| [LINEAR](#LINEAR) | La interpolación lineal es una línea recta entre dos puntos. |
| [TCB_SPLINE](#TCB-SPLINE) | También llamada spline de Kochanek-Bartels, el comportamiento de la tangente se define por tensión/sesgo/continuidad |
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
### BEZIER {#BEZIER}
```
public static final Interpolation BEZIER
```


Una spline B\u00e9zier o Hermite.

### B_SPLINE {#B-SPLINE}
```
public static final Interpolation B_SPLINE
```


Los splines b\u00e1sicos se definen mediante una serie de puntos de control, para los cuales se garantiza que la curva solo pase por el primer y el \u00faltimo punto.

### CARDINAL_SPLINE {#CARDINAL-SPLINE}
```
public static final Interpolation CARDINAL_SPLINE
```


Una spline cardinal es una spline cúbica de Hermite cuyas tangentes se definen por los puntos finales y un parámetro de tensión.

### CONSTANT {#CONSTANT}
```
public static final Interpolation CONSTANT
```


El valor permanecerá constante al valor del primer punto hasta el siguiente segmento.

### LINEAR {#LINEAR}
```
public static final Interpolation LINEAR
```


La interpolación lineal es una línea recta entre dos puntos.

### TCB_SPLINE {#TCB-SPLINE}
```
public static final Interpolation TCB_SPLINE
```


También llamada spline de Kochanek-Bartels, el comportamiento de la tangente se define por tensión/sesgo/continuidad

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
public static Interpolation valueOf(String name)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String |  |

**Returns:**
[Interpolation](../../com.aspose.threed/interpolation)
### values() {#values--}
```
public static Interpolation[] values()
```




**Returns:**
com.aspose.threed.Interpolation[]
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

