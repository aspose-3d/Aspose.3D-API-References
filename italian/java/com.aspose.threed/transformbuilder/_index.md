---
title: TransformBuilder
second_title: Aspose.3D for Java API Reference
description: The  is used to build transform matrix by a chain of transformations.
type: docs
weight: 191
url: /it/java/com.aspose.threed/transformbuilder/
---

**Inheritance:**
java.lang.Object
```
public class TransformBuilder
```

The [TransformBuilder](../../com.aspose.threed/transformbuilder) is used to build transform matrix by a chain of transformations. **Example:** The following code shows how to create a matrix by a set of operation

```
TransformBuilder tb = new TransformBuilder();
     tb.translate(10, 20, 0);
     tb.scale(10, 10, 10);
     tb.rotateEulerDegree(90, 0, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TransformBuilder(Matrix4 initial, ComposeOrder order)](#TransformBuilder-com.aspose.threed.Matrix4-com.aspose.threed.ComposeOrder-) | Construct a [TransformBuilder](../../com.aspose.threed/transformbuilder) with initial transform matrix and specified compose order |
| [TransformBuilder(ComposeOrder order)](#TransformBuilder-com.aspose.threed.ComposeOrder-) | Construct a [TransformBuilder](../../com.aspose.threed/transformbuilder) with initial identity transform matrix and specified compose order |
| [TransformBuilder()](#TransformBuilder--) | Construct a [TransformBuilder](../../com.aspose.threed/transformbuilder) with initial identity transform matrix and specified compose order |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [append(Matrix4 m)](#append-com.aspose.threed.Matrix4-) | Append the new transform matrix to the transform chain. |
| [compose(Matrix4 m)](#compose-com.aspose.threed.Matrix4-) | Append or prepend the argument to internal matrix. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getComposeOrder()](#getComposeOrder--) | Gets the chain compose order. |
| [getMatrix()](#getMatrix--) | Gets the current matrix value |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [prepend(Matrix4 m)](#prepend-com.aspose.threed.Matrix4-) | Prepend the new transform matrix to the transform chain. |
| [rearrange(Axis newX, Axis newY, Axis newZ)](#rearrange-com.aspose.threed.Axis-com.aspose.threed.Axis-com.aspose.threed.Axis-) | Rearrange the layout of the axis. |
| [reset()](#reset--) | Reset the transform to identity matrix |
| [rotate(Quaternion q)](#rotate-com.aspose.threed.Quaternion-) | Concatena una rotazione tramite un quaternion **Esempio:** |
| [rotateDegree(Vector3 rot, RotationOrder order)](#rotateDegree-com.aspose.threed.Vector3-com.aspose.threed.RotationOrder-) | Aggiungi rotazione con ordine specificato |
| [rotateDegree(double angle, Vector3 axis)](#rotateDegree-double-com.aspose.threed.Vector3-) | Concatena una trasformazione di rotazione in gradi |
| [rotateEulerDegree(double degX, double degY, double degZ)](#rotateEulerDegree-double-double-double-) | Concatena una rotazione tramite angoli di Eulero in gradi **Esempio:** |
| [rotateEulerRadian(Vector3 r)](#rotateEulerRadian-com.aspose.threed.Vector3-) | Concatena una rotazione tramite angoli di Eulero in radianti **Esempio:** |
| [rotateEulerRadian(double x, double y, double z)](#rotateEulerRadian-double-double-double-) | Concatena una rotazione tramite angoli di Eulero in radianti **Esempio:** |
| [rotateRadian(Vector3 rot, RotationOrder order)](#rotateRadian-com.aspose.threed.Vector3-com.aspose.threed.RotationOrder-) | Aggiungi rotazione con ordine specificato |
| [rotateRadian(double angle, Vector3 axis)](#rotateRadian-double-com.aspose.threed.Vector3-) | Concatena una trasformazione di rotazione in radianti |
| [scale(Vector3 s)](#scale-com.aspose.threed.Vector3-) | Concatena una trasformazione di scala **Esempio:** |
| [scale(double s)](#scale-double-) | Concatena una matrice di trasformazione di scala con un componente scalato di s **Esempio:** |
| [scale(double x, double y, double z)](#scale-double-double-double-) | Concatena una matrice di trasformazione di scala **Esempio:** |
| [setComposeOrder(ComposeOrder value)](#setComposeOrder-com.aspose.threed.ComposeOrder-) | Imposta l'ordine di composizione della catena. |
| [setMatrix(Matrix4 value)](#setMatrix-com.aspose.threed.Matrix4-) | Imposta il valore corrente della matrice |
| [toString()](#toString--) |  |
| [translate(Vector3 v)](#translate-com.aspose.threed.Vector3-) | Concatena una trasformazione di traslazione **Esempio:** |
| [translate(double tx, double ty, double tz)](#translate-double-double-double-) | Concatena una trasformazione di traslazione **Esempio:** |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TransformBuilder(Matrix4 initial, ComposeOrder order) {#TransformBuilder-com.aspose.threed.Matrix4-com.aspose.threed.ComposeOrder-}
```
public TransformBuilder(Matrix4 initial, ComposeOrder order)
```


Construct a [TransformBuilder](../../com.aspose.threed/transformbuilder) with initial transform matrix and specified compose order

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| initial | [Matrix4](../../com.aspose.threed/matrix4) |  |
| order | [ComposeOrder](../../com.aspose.threed/composeorder) |  |

### TransformBuilder(ComposeOrder order) {#TransformBuilder-com.aspose.threed.ComposeOrder-}
```
public TransformBuilder(ComposeOrder order)
```


Construct a [TransformBuilder](../../com.aspose.threed/transformbuilder) with initial identity transform matrix and specified compose order

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| order | [ComposeOrder](../../com.aspose.threed/composeorder) |  |

### TransformBuilder() {#TransformBuilder--}
```
public TransformBuilder()
```


Construct a [TransformBuilder](../../com.aspose.threed/transformbuilder) with initial identity transform matrix and specified compose order

### append(Matrix4 m) {#append-com.aspose.threed.Matrix4-}
```
public TransformBuilder append(Matrix4 m)
```


Append the new transform matrix to the transform chain.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| m | [Matrix4](../../com.aspose.threed/matrix4) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### compose(Matrix4 m) {#compose-com.aspose.threed.Matrix4-}
```
public void compose(Matrix4 m)
```


Append or prepend the argument to internal matrix.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| m | [Matrix4](../../com.aspose.threed/matrix4) |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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
### getComposeOrder() {#getComposeOrder--}
```
public ComposeOrder getComposeOrder()
```


Gets the chain compose order.

**Returns:**
[ComposeOrder](../../com.aspose.threed/composeorder) - the chain compose order.
### getMatrix() {#getMatrix--}
```
public Matrix4 getMatrix()
```


Gets the current matrix value

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the current matrix value
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




### prepend(Matrix4 m) {#prepend-com.aspose.threed.Matrix4-}
```
public TransformBuilder prepend(Matrix4 m)
```


Prepend the new transform matrix to the transform chain.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| m | [Matrix4](../../com.aspose.threed/matrix4) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### rearrange(Axis newX, Axis newY, Axis newZ) {#rearrange-com.aspose.threed.Axis-com.aspose.threed.Axis-com.aspose.threed.Axis-}
```
public TransformBuilder rearrange(Axis newX, Axis newY, Axis newZ)
```


Rearrange the layout of the axis.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newX | [Axis](../../com.aspose.threed/axis) | La nuova sorgente del componente x |
| newY | [Axis](../../com.aspose.threed/axis) | La nuova sorgente del componente y |
| newZ | [Axis](../../com.aspose.threed/axis) | La nuova sorgente del componente z |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### reset() {#reset--}
```
public void reset()
```


Reset the transform to identity matrix

### rotate(Quaternion q) {#rotate-com.aspose.threed.Quaternion-}
```
public TransformBuilder rotate(Quaternion q)
```


Concatena una rotazione tramite un quaternion **Esempio:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotate(Quaternion.fromEulerAngle(0, Math.PI, 0));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### rotateDegree(Vector3 rot, RotationOrder order) {#rotateDegree-com.aspose.threed.Vector3-com.aspose.threed.RotationOrder-}
```
public void rotateDegree(Vector3 rot, RotationOrder order)
```


Aggiungi rotazione con ordine specificato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rot | [Vector3](../../com.aspose.threed/vector3) | Rotazione in gradi |
| order | [RotationOrder](../../com.aspose.threed/rotationorder) |  |

### rotateDegree(double angle, Vector3 axis) {#rotateDegree-double-com.aspose.threed.Vector3-}
```
public TransformBuilder rotateDegree(double angle, Vector3 axis)
```


Concatena una trasformazione di rotazione in gradi

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angle | double | L'angolo da ruotare in gradi |
|  | axis | [Vector3](../../com.aspose.threed/vector3) | L'asse da ruotare **Esempio:** |

```
TransformBuilder tb = new TransformBuilder();
     tb.rotateDegree(90, Vector3.getUnitY());
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
``` |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### rotateEulerDegree(double degX, double degY, double degZ) {#rotateEulerDegree-double-double-double-}
```
public TransformBuilder rotateEulerDegree(double degX, double degY, double degZ)
```


Concatena una rotazione tramite angoli di Eulero in gradi **Esempio:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotateEulerDegree(0, 90, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| degX | double |  |
| degY | double |  |
| degZ | double |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### rotateEulerRadian(Vector3 r) {#rotateEulerRadian-com.aspose.threed.Vector3-}
```
public TransformBuilder rotateEulerRadian(Vector3 r)
```


Concatena una rotazione tramite angoli di Eulero in radianti **Esempio:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotateEulerRadian(new Vector3(0, Math.PI, 0));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| r | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### rotateEulerRadian(double x, double y, double z) {#rotateEulerRadian-double-double-double-}
```
public TransformBuilder rotateEulerRadian(double x, double y, double z)
```


Concatena una rotazione tramite angoli di Eulero in radianti **Esempio:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotateEulerRadian(0, Math.PI, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | double |  |
| y | double |  |
| z | double |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### rotateRadian(Vector3 rot, RotationOrder order) {#rotateRadian-com.aspose.threed.Vector3-com.aspose.threed.RotationOrder-}
```
public void rotateRadian(Vector3 rot, RotationOrder order)
```


Aggiungi rotazione con ordine specificato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | rot | [Vector3](../../com.aspose.threed/vector3) | Rotazione in radianti **Esempio:** |

```
TransformBuilder tb = new TransformBuilder();
     tb.rotateRadian(new Vector3(0.3, 0.4, 0.1), RotationOrder.YZX);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
``` |
| order | [RotationOrder](../../com.aspose.threed/rotationorder) |  |

### rotateRadian(double angle, Vector3 axis) {#rotateRadian-double-com.aspose.threed.Vector3-}
```
public TransformBuilder rotateRadian(double angle, Vector3 axis)
```


Concatena una trasformazione di rotazione in radianti

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angle | double | L'angolo da ruotare in radianti |
|  | axis | [Vector3](../../com.aspose.threed/vector3) | L'asse da ruotare **Esempio:** |

```
TransformBuilder tb = new TransformBuilder();
     tb.rotateRadian(Math.PI, Vector3.getUnitY());
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
``` |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### scale(Vector3 s) {#scale-com.aspose.threed.Vector3-}
```
public TransformBuilder scale(Vector3 s)
```


Concatena una trasformazione di scala **Esempio:**

```
TransformBuilder tb = new TransformBuilder();
     tb.scale(new Vector3(10, 10, 10));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### scale(double s) {#scale-double-}
```
public TransformBuilder scale(double s)
```


Concatena una matrice di trasformazione di scala con un componente scalato di s **Esempio:**

```
TransformBuilder tb = new TransformBuilder();
     tb.scale(10);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | double |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### scale(double x, double y, double z) {#scale-double-double-double-}
```
public TransformBuilder scale(double x, double y, double z)
```


Concatena una matrice di trasformazione di scala **Esempio:**

```
TransformBuilder tb = new TransformBuilder();
     tb.scale(10, 10, 10);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | double |  |
| y | double |  |
| z | double |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### setComposeOrder(ComposeOrder value) {#setComposeOrder-com.aspose.threed.ComposeOrder-}
```
public void setComposeOrder(ComposeOrder value)
```


Imposta l'ordine di composizione della catena.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ComposeOrder](../../com.aspose.threed/composeorder) | Nuovo valore |

### setMatrix(Matrix4 value) {#setMatrix-com.aspose.threed.Matrix4-}
```
public void setMatrix(Matrix4 value)
```


Imposta il valore corrente della matrice

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | Nuovo valore |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### translate(Vector3 v) {#translate-com.aspose.threed.Vector3-}
```
public TransformBuilder translate(Vector3 v)
```


Concatena una trasformazione di traslazione **Esempio:**

```
TransformBuilder tb = new TransformBuilder();
     tb.translate(new Vector3(0, 10, 0));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### translate(double tx, double ty, double tz) {#translate-double-double-double-}
```
public TransformBuilder translate(double tx, double ty, double tz)
```


Concatena una trasformazione di traslazione **Esempio:**

```
TransformBuilder tb = new TransformBuilder();
     tb.translate(0, 10, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tx | double |  |
| ty | double |  |
| tz | double |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

