---
title: "TransformBuilder"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Le  est utilisé pour construire une matrice de transformation par une chaîne de transformations."
type: docs
weight: 191
url: /fr/java/com.aspose.threed/transformbuilder/
---

**Inheritance:**
java.lang.Object
```
public class TransformBuilder
```

Le [TransformBuilder](../../com.aspose.threed/transformbuilder) est utilisé pour construire une matrice de transformation par une chaîne de transformations. **Exemple :** Le code suivant montre comment créer une matrice à partir d'un ensemble d'opérations

```
TransformBuilder tb = new TransformBuilder();
     tb.translate(10, 20, 0);
     tb.scale(10, 10, 10);
     tb.rotateEulerDegree(90, 0, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TransformBuilder(Matrix4 initial, ComposeOrder order)](#TransformBuilder-com.aspose.threed.Matrix4-com.aspose.threed.ComposeOrder-) | Construit un [TransformBuilder](../../com.aspose.threed/transformbuilder) avec une matrice de transformation initiale et un ordre de composition spécifié |
| [TransformBuilder(ComposeOrder order)](#TransformBuilder-com.aspose.threed.ComposeOrder-) | Construit un [TransformBuilder](../../com.aspose.threed/transformbuilder) avec une matrice de transformation identité initiale et un ordre de composition spécifié |
| [TransformBuilder()](#TransformBuilder--) | Construit un [TransformBuilder](../../com.aspose.threed/transformbuilder) avec une matrice de transformation identité initiale et un ordre de composition spécifié |
## Méthodes

| Méthode | Description |
| --- | --- |
| [append(Matrix4 m)](#append-com.aspose.threed.Matrix4-) | Ajoute la nouvelle matrice de transformation à la chaîne de transformations. |
| [compose(Matrix4 m)](#compose-com.aspose.threed.Matrix4-) | Ajoute ou préfixe l'argument à la matrice interne. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getComposeOrder()](#getComposeOrder--) | Obtient l'ordre de composition de la chaîne. |
| [getMatrix()](#getMatrix--) | Obtient la valeur actuelle de la matrice |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [prepend(Matrix4 m)](#prepend-com.aspose.threed.Matrix4-) | Préfixe la nouvelle matrice de transformation à la chaîne de transformations. |
| [rearrange(Axis newX, Axis newY, Axis newZ)](#rearrange-com.aspose.threed.Axis-com.aspose.threed.Axis-com.aspose.threed.Axis-) | Réorganise la disposition des axes. |
| [reset()](#reset--) | Réinitialise la transformation à la matrice identité |
| [rotate(Quaternion q)](#rotate-com.aspose.threed.Quaternion-) | Enchaîner une rotation par un quaternion **Exemple:** |
| [rotateDegree(Vector3 rot, RotationOrder order)](#rotateDegree-com.aspose.threed.Vector3-com.aspose.threed.RotationOrder-) | Ajouter une rotation avec l'ordre spécifié |
| [rotateDegree(double angle, Vector3 axis)](#rotateDegree-double-com.aspose.threed.Vector3-) | Enchaîner une transformation de rotation en degrés |
| [rotateEulerDegree(double degX, double degY, double degZ)](#rotateEulerDegree-double-double-double-) | Enchaîner une rotation par angles d'Euler en degrés **Exemple:** |
| [rotateEulerRadian(Vector3 r)](#rotateEulerRadian-com.aspose.threed.Vector3-) | Enchaîner une rotation par angles d'Euler en radians **Exemple:** |
| [rotateEulerRadian(double x, double y, double z)](#rotateEulerRadian-double-double-double-) | Enchaîner une rotation par angles d'Euler en radians **Exemple:** |
| [rotateRadian(Vector3 rot, RotationOrder order)](#rotateRadian-com.aspose.threed.Vector3-com.aspose.threed.RotationOrder-) | Ajouter une rotation avec l'ordre spécifié |
| [rotateRadian(double angle, Vector3 axis)](#rotateRadian-double-com.aspose.threed.Vector3-) | Enchaîner une transformation de rotation en radians |
| [scale(Vector3 s)](#scale-com.aspose.threed.Vector3-) | Enchaîner une transformation d'échelle **Exemple:** |
| [scale(double s)](#scale-double-) | Enchaîner une matrice de transformation d'échelle avec un composant mis à l'échelle par s **Exemple:** |
| [scale(double x, double y, double z)](#scale-double-double-double-) | Enchaîner une matrice de transformation d'échelle **Exemple:** |
| [setComposeOrder(ComposeOrder value)](#setComposeOrder-com.aspose.threed.ComposeOrder-) | Définit l'ordre de composition de la chaîne. |
| [setMatrix(Matrix4 value)](#setMatrix-com.aspose.threed.Matrix4-) | Définit la valeur actuelle de la matrice |
| [toString()](#toString--) |  |
| [translate(Vector3 v)](#translate-com.aspose.threed.Vector3-) | Enchaîner une transformation de translation **Exemple:** |
| [translate(double tx, double ty, double tz)](#translate-double-double-double-) | Enchaîner une transformation de translation **Exemple:** |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TransformBuilder(Matrix4 initial, ComposeOrder order) {#TransformBuilder-com.aspose.threed.Matrix4-com.aspose.threed.ComposeOrder-}
```
public TransformBuilder(Matrix4 initial, ComposeOrder order)
```


Construit un [TransformBuilder](../../com.aspose.threed/transformbuilder) avec une matrice de transformation initiale et un ordre de composition spécifié

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| initial | [Matrix4](../../com.aspose.threed/matrix4) |  |
| order | [ComposeOrder](../../com.aspose.threed/composeorder) |  |

### TransformBuilder(ComposeOrder order) {#TransformBuilder-com.aspose.threed.ComposeOrder-}
```
public TransformBuilder(ComposeOrder order)
```


Construit un [TransformBuilder](../../com.aspose.threed/transformbuilder) avec une matrice de transformation identité initiale et un ordre de composition spécifié

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| order | [ComposeOrder](../../com.aspose.threed/composeorder) |  |

### TransformBuilder() {#TransformBuilder--}
```
public TransformBuilder()
```


Construit un [TransformBuilder](../../com.aspose.threed/transformbuilder) avec une matrice de transformation identité initiale et un ordre de composition spécifié

### append(Matrix4 m) {#append-com.aspose.threed.Matrix4-}
```
public TransformBuilder append(Matrix4 m)
```


Ajoute la nouvelle matrice de transformation à la chaîne de transformations.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| m | [Matrix4](../../com.aspose.threed/matrix4) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### compose(Matrix4 m) {#compose-com.aspose.threed.Matrix4-}
```
public void compose(Matrix4 m)
```


Ajoute ou préfixe l'argument à la matrice interne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| m | [Matrix4](../../com.aspose.threed/matrix4) |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
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


Obtient l'ordre de composition de la chaîne.

**Returns:**
[ComposeOrder](../../com.aspose.threed/composeorder) - the chain compose order.
### getMatrix() {#getMatrix--}
```
public Matrix4 getMatrix()
```


Obtient la valeur actuelle de la matrice

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


Préfixe la nouvelle matrice de transformation à la chaîne de transformations.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| m | [Matrix4](../../com.aspose.threed/matrix4) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### rearrange(Axis newX, Axis newY, Axis newZ) {#rearrange-com.aspose.threed.Axis-com.aspose.threed.Axis-com.aspose.threed.Axis-}
```
public TransformBuilder rearrange(Axis newX, Axis newY, Axis newZ)
```


Réorganise la disposition des axes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newX | [Axis](../../com.aspose.threed/axis) | La nouvelle source du composant x |
| newY | [Axis](../../com.aspose.threed/axis) | La nouvelle source du composant y |
| newZ | [Axis](../../com.aspose.threed/axis) | La nouvelle source du composant z |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### reset() {#reset--}
```
public void reset()
```


Réinitialise la transformation à la matrice identité

### rotate(Quaternion q) {#rotate-com.aspose.threed.Quaternion-}
```
public TransformBuilder rotate(Quaternion q)
```


Enchaîner une rotation par un quaternion **Exemple:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotate(Quaternion.fromEulerAngle(0, Math.PI, 0));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### rotateDegree(Vector3 rot, RotationOrder order) {#rotateDegree-com.aspose.threed.Vector3-com.aspose.threed.RotationOrder-}
```
public void rotateDegree(Vector3 rot, RotationOrder order)
```


Ajouter une rotation avec l'ordre spécifié

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rot | [Vector3](../../com.aspose.threed/vector3) | Rotation en degrés |
| order | [RotationOrder](../../com.aspose.threed/rotationorder) |  |

### rotateDegree(double angle, Vector3 axis) {#rotateDegree-double-com.aspose.threed.Vector3-}
```
public TransformBuilder rotateDegree(double angle, Vector3 axis)
```


Enchaîner une transformation de rotation en degrés

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | double | L'angle à faire pivoter en degré |
|  | axis | [Vector3](../../com.aspose.threed/vector3) | L'axe à faire pivoter **Exemple:** |

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


Enchaîner une rotation par angles d'Euler en degrés **Exemple:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotateEulerDegree(0, 90, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Paramètre | Type | Description |
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


Enchaîner une rotation par angles d'Euler en radians **Exemple:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotateEulerRadian(new Vector3(0, Math.PI, 0));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| r | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### rotateEulerRadian(double x, double y, double z) {#rotateEulerRadian-double-double-double-}
```
public TransformBuilder rotateEulerRadian(double x, double y, double z)
```


Enchaîner une rotation par angles d'Euler en radians **Exemple:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotateEulerRadian(0, Math.PI, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Paramètre | Type | Description |
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


Ajouter une rotation avec l'ordre spécifié

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | rot | [Vector3](../../com.aspose.threed/vector3) | Rotation en radians **Exemple:** |

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


Enchaîner une transformation de rotation en radians

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | double | L'angle à faire pivoter en radian |
|  | axis | [Vector3](../../com.aspose.threed/vector3) | L'axe à faire pivoter **Exemple:** |

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


Enchaîner une transformation d'échelle **Exemple:**

```
TransformBuilder tb = new TransformBuilder();
     tb.scale(new Vector3(10, 10, 10));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| s | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### scale(double s) {#scale-double-}
```
public TransformBuilder scale(double s)
```


Enchaîner une matrice de transformation d'échelle avec un composant mis à l'échelle par s **Exemple:**

```
TransformBuilder tb = new TransformBuilder();
     tb.scale(10);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| s | double |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### scale(double x, double y, double z) {#scale-double-double-double-}
```
public TransformBuilder scale(double x, double y, double z)
```


Enchaîner une matrice de transformation d'échelle **Exemple:**

```
TransformBuilder tb = new TransformBuilder();
     tb.scale(10, 10, 10);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Paramètre | Type | Description |
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


Définit l'ordre de composition de la chaîne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ComposeOrder](../../com.aspose.threed/composeorder) | Nouvelle valeur |

### setMatrix(Matrix4 value) {#setMatrix-com.aspose.threed.Matrix4-}
```
public void setMatrix(Matrix4 value)
```


Définit la valeur actuelle de la matrice

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | Nouvelle valeur |

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


Enchaîner une transformation de translation **Exemple:**

```
TransformBuilder tb = new TransformBuilder();
     tb.translate(new Vector3(0, 10, 0));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### translate(double tx, double ty, double tz) {#translate-double-double-double-}
```
public TransformBuilder translate(double tx, double ty, double tz)
```


Enchaîner une transformation de translation **Exemple:**

```
TransformBuilder tb = new TransformBuilder();
     tb.translate(0, 10, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

