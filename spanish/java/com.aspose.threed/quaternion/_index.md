---
title: Quaternion
second_title: Referencia de API de Aspose.3D para Java
description: Los cuaterniones se usan normalmente para realizar rotaciones en gráficos por computadora.
type: docs
weight: 143
url: /es/java/com.aspose.threed/quaternion/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class Quaternion implements Struct<Quaternion>, Serializable
```

Los cuaterniones se usan normalmente para realizar rotaciones en gráficos por computadora.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Quaternion(double w, double x, double y, double z)](#Quaternion-double-double-double-double-) | Inicializa una nueva instancia de la clase [Quaternion](../../com.aspose.threed/quaternion). |
| [Quaternion()](#Quaternion--) |  |
## Campos

| Campo | Descripción |
| --- | --- |
| [IDENTITY](#IDENTITY) | El cuaternión de identidad. |
| [w](#w) | El componente w. |
| [x](#x) | El componente x. |
| [y](#y) | El componente y. |
| [z](#z) | El componente z. |
## Métodos

| Método | Descripción |
| --- | --- |
| [add(Quaternion lhs, Quaternion rhs)](#add-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Sobrecarga de operador para + |
| [clone()](#clone--) |  |
| [concat(Quaternion rhs)](#concat-com.aspose.threed.Quaternion-) | Concatenar dos cuaterniones |
| [conjugate()](#conjugate--) | Devuelve un cuaternión conjugado del cuaternión actual |
| [copyFrom(Quaternion src)](#copyFrom-com.aspose.threed.Quaternion-) |  |
| [div(Quaternion lhs, double rhs)](#div-com.aspose.threed.Quaternion-double-) | Sobrecarga de operador para / |
| [dot(Quaternion q)](#dot-com.aspose.threed.Quaternion-) | Producto punto |
| [equals(Object obj)](#equals-java.lang.Object-) | Comprobar si dos cuaterniones son iguales |
| [eulerAngles()](#eulerAngles--) | Convierte el cuaternión a una rotación representada por ángulos de Euler. Todos los componentes están en radianes. |
| [fromAngleAxis(double a, Vector3 axis)](#fromAngleAxis-double-com.aspose.threed.Vector3-) | Crea un cuaternión alrededor del eje dado y lo rota en sentido horario |
| [fromEulerAngle(Vector3 eulerAngle)](#fromEulerAngle-com.aspose.threed.Vector3-) | Crea un cuaternión a partir del ángulo de Euler dado |
| [fromEulerAngle(double pitch, double yaw, double roll)](#fromEulerAngle-double-double-double-) | Crea un cuaternión a partir del ángulo de Euler dado |
| [fromRotation(Vector3 orig, Vector3 dest)](#fromRotation-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Crea un cuaternión que rota de la dirección original a la de destino |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Obtiene la longitud del cuaternión |
| [hashCode()](#hashCode--) | Obtiene el código hash del cuaternión |
| [interpolate(float t, Quaternion from, Quaternion to)](#interpolate-float-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Rellena este cuaternión con el valor interpolado entre los argumentos de cuaternión dados para un t entre 'from' y 'to'. |
| [inverse()](#inverse--) | Devuelve un cuaternión inverso del cuaternión actual |
| [mul(Quaternion lhs, Quaternion rhs)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Sobrecarga de operador para \* |
| [mul(Quaternion q, Vector3 v)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector3-) | Sobrecarga de operador para \* |
| [mul(Quaternion q, Vector4 v)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector4-) | Sobrecarga de operador para \* |
| [mul(Quaternion lhs, double rhs)](#mul-com.aspose.threed.Quaternion-double-) | Sobrecarga de operador para \* |
| [mul(Vector3 v, Quaternion q)](#mul-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-) | Sobrecarga de operador para \* |
| [normalize()](#normalize--) | Normaliza el cuaternión |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(Quaternion lhs, Quaternion rhs)](#op-eq-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Operador de igualdad para cuaternión |
| [op_ne(Quaternion lhs, Quaternion rhs)](#op-ne-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Operador de desigualdad para cuaternión |
| [slerp(double t, Quaternion v1, Quaternion v2)](#slerp-double-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Realiza una interpolación lineal esférica entre dos valores |
| [toAngleAxis(double[] angle, Vector3 axis)](#toAngleAxis-double---com.aspose.threed.Vector3-) | Descompone el cuaternión en ángulo y eje |
| [toMatrix()](#toMatrix--) | Convierte la rotación presentada por el cuaternión a una matriz de transformación. |
| [toMatrix(Vector3 translation)](#toMatrix-com.aspose.threed.Vector3-) | Convierte la rotación presentada por el cuaternión a una matriz de transformación. |
| [toString()](#toString--) | Obtiene la representación del cuaternión en cadena |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Quaternion(double w, double x, double y, double z) {#Quaternion-double-double-double-double-}
```
public Quaternion(double w, double x, double y, double z)
```


Inicializa una nueva instancia de la clase [Quaternion](../../com.aspose.threed/quaternion).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| w | double | componente w del cuaternión |
| x | double | componente x del cuaternión |
| y | double | componente y del cuaternión |
| z | double | componente z del cuaternión |

### Quaternion() {#Quaternion--}
```
public Quaternion()
```


### IDENTITY {#IDENTITY}
```
public static final Quaternion IDENTITY
```


El cuaternión de identidad.

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

### add(Quaternion lhs, Quaternion rhs) {#add-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion add(Quaternion lhs, Quaternion rhs)
```


Sobrecarga de operador para +

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Cuaternión izquierdo |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Cuaternión derecho |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### clone() {#clone--}
```
public Quaternion clone()
```


Clonar la instancia actual

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### concat(Quaternion rhs) {#concat-com.aspose.threed.Quaternion-}
```
public Quaternion concat(Quaternion rhs)
```


Concatenar dos cuaterniones

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) |  |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### conjugate() {#conjugate--}
```
public Quaternion conjugate()
```


Devuelve un cuaternión conjugado del cuaternión actual

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - The conjugate quaternion.
### copyFrom(Quaternion src) {#copyFrom-com.aspose.threed.Quaternion-}
```
public void copyFrom(Quaternion src)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| src | [Quaternion](../../com.aspose.threed/quaternion) |  |

### div(Quaternion lhs, double rhs) {#div-com.aspose.threed.Quaternion-double-}
```
public static Quaternion div(Quaternion lhs, double rhs)
```


Sobrecarga de operador para /

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Cuaternión izquierdo |
| rhs | double | Cuaternión derecho |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### dot(Quaternion q) {#dot-com.aspose.threed.Quaternion-}
```
public double dot(Quaternion q)
```


Producto punto

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | El cuaternión |

**Returns:**
double - Valor del punto
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Comprobar si dos cuaterniones son iguales

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El objeto para comprobar igualdad. |

**Returns:**
boolean - Verdadero si todos los componentes son idénticamente iguales.
### eulerAngles() {#eulerAngles--}
```
public Vector3 eulerAngles()
```


Convierte el cuaternión a una rotación representada por ángulos de Euler. Todos los componentes están en radianes.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### fromAngleAxis(double a, Vector3 axis) {#fromAngleAxis-double-com.aspose.threed.Vector3-}
```
public static Quaternion fromAngleAxis(double a, Vector3 axis)
```


Crea un cuaternión alrededor del eje dado y lo rota en sentido horario

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | double | Rotación en sentido horario en radianes |
| axis | [Vector3](../../com.aspose.threed/vector3) | Eje |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromEulerAngle(Vector3 eulerAngle) {#fromEulerAngle-com.aspose.threed.Vector3-}
```
public static Quaternion fromEulerAngle(Vector3 eulerAngle)
```


Crea un cuaternión a partir del ángulo de Euler dado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| eulerAngle | [Vector3](../../com.aspose.threed/vector3) | Ángulo de Euler en radianes |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromEulerAngle(double pitch, double yaw, double roll) {#fromEulerAngle-double-double-double-}
```
public static Quaternion fromEulerAngle(double pitch, double yaw, double roll)
```


Crea un cuaternión a partir del ángulo de Euler dado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cabeceo | double | Cabeceo en radianes |
| guiñada | double | Guiñada en radianes |
| balanceo | double | Balanceo en radianes |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromRotation(Vector3 orig, Vector3 dest) {#fromRotation-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Quaternion fromRotation(Vector3 orig, Vector3 dest)
```


Crea un cuaternión que rota de la dirección original a la de destino

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| orig | [Vector3](../../com.aspose.threed/vector3) | Dirección original |
| dest | [Vector3](../../com.aspose.threed/vector3) | Dirección de destino |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
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


Obtiene la longitud del cuaternión

**Returns:**
double - la longitud del cuaternión
### hashCode() {#hashCode--}
```
public int hashCode()
```


Obtiene el código hash del cuaternión

**Returns:**
int - El código hash del [Quaternion](../../com.aspose.threed/quaternion)
### interpolate(float t, Quaternion from, Quaternion to) {#interpolate-float-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion interpolate(float t, Quaternion from, Quaternion to)
```


Rellena este cuaternión con el valor interpolado entre los argumentos de cuaternión dados para un t entre 'from' y 'to'.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| t | float | El coeficiente para interpolar. |
| from | [Quaternion](../../com.aspose.threed/quaternion) | Cuaternión de origen. |
| to | [Quaternion](../../com.aspose.threed/quaternion) | Cuaternión de destino. |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - The interpolated quaternion.
### inverse() {#inverse--}
```
public Quaternion inverse()
```


Devuelve un cuaternión inverso del cuaternión actual

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Inverse quaternion.
### mul(Quaternion lhs, Quaternion rhs) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion mul(Quaternion lhs, Quaternion rhs)
```


Sobrecarga de operador para \*

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Cuaternión izquierdo |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Cuaternión derecho |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### mul(Quaternion q, Vector3 v) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector3-}
```
public static Vector3 mul(Quaternion q, Vector3 v)
```


Sobrecarga de operador para \*

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | El cuaternión de rotación |
| v | [Vector3](../../com.aspose.threed/vector3) | Vector a rotar |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Rotated vector
### mul(Quaternion q, Vector4 v) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector4-}
```
public static Vector4 mul(Quaternion q, Vector4 v)
```


Sobrecarga de operador para \*

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | El cuaternión de rotación |
| v | [Vector4](../../com.aspose.threed/vector4) | Vector a rotar |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Rotated vector
### mul(Quaternion lhs, double rhs) {#mul-com.aspose.threed.Quaternion-double-}
```
public static Quaternion mul(Quaternion lhs, double rhs)
```


Sobrecarga de operador para \*

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Cuaternión izquierdo |
| rhs | double | Cuaternión derecho |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### mul(Vector3 v, Quaternion q) {#mul-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-}
```
public static Vector3 mul(Vector3 v, Quaternion q)
```


Sobrecarga de operador para \*

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) | El cuaternión de rotación |
| q | [Quaternion](../../com.aspose.threed/quaternion) | Vector a rotar |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Rotated vector
### normalize() {#normalize--}
```
public Quaternion normalize()
```


Normaliza el cuaternión

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Normalized quaternion.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_eq(Quaternion lhs, Quaternion rhs) {#op-eq-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static boolean op_eq(Quaternion lhs, Quaternion rhs)
```


Operador de igualdad para cuaternión

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Valor del lado izquierdo. |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Valor del lado derecho. |

**Returns:**
boolean - Verdadero si todos los componentes son idénticamente iguales.
### op_ne(Quaternion lhs, Quaternion rhs) {#op-ne-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static boolean op_ne(Quaternion lhs, Quaternion rhs)
```


Operador de desigualdad para cuaternión

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Valor del lado izquierdo. |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Valor del lado derecho. |

**Returns:**
booleano - Verdadero si dos cuaterniones no son iguales.
### slerp(double t, Quaternion v1, Quaternion v2) {#slerp-double-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion slerp(double t, Quaternion v1, Quaternion v2)
```


Realiza una interpolación lineal esférica entre dos valores

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| t | double | t está entre 0 y 1 |
| v1 | [Quaternion](../../com.aspose.threed/quaternion) | Primer valor |
| v2 | [Quaternion](../../com.aspose.threed/quaternion) | Segundo valor |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### toAngleAxis(double[] angle, Vector3 axis) {#toAngleAxis-double---com.aspose.threed.Vector3-}
```
public void toAngleAxis(double[] angle, Vector3 axis)
```


Descompone el cuaternión en ángulo y eje

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| angle | double[] | El ángulo a rotar, en radianes. |
| axis | [Vector3](../../com.aspose.threed/vector3) | El eje alrededor del cual gira. |

### toMatrix() {#toMatrix--}
```
public Matrix4 toMatrix()
```


Convierte la rotación presentada por el cuaternión a una matriz de transformación.

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - The matrix representation of current quaternion.
### toMatrix(Vector3 translation) {#toMatrix-com.aspose.threed.Vector3-}
```
public Matrix4 toMatrix(Vector3 translation)
```


Convierte la rotación presentada por el cuaternión a una matriz de transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| translation | [Vector3](../../com.aspose.threed/vector3) | La parte de traslación de la matriz. |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - The matrix representation of current quaternion.
### toString() {#toString--}
```
public String toString()
```


Obtiene la representación del cuaternión en cadena

**Returns:**
java.lang.String - Cadena del objeto
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

