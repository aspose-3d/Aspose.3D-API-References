---
title: "TransformBuilder"
second_title: "Aspose.3D voor Java API-referentie"
description: "De  wordt gebruikt om een transformatiematrix te bouwen door een keten van transformaties."
type: docs
weight: 191
url: /nl/java/com.aspose.threed/transformbuilder/
---

**Inheritance:**
java.lang.Object
```
public class TransformBuilder
```

De [TransformBuilder](../../com.aspose.threed/transformbuilder) wordt gebruikt om een transformatiematrix te bouwen door een keten van transformaties. **Voorbeeld:** De volgende code toont hoe een matrix te maken met een reeks bewerkingen

```
TransformBuilder tb = new TransformBuilder();
     tb.translate(10, 20, 0);
     tb.scale(10, 10, 10);
     tb.rotateEulerDegree(90, 0, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [TransformBuilder(Matrix4 initial, ComposeOrder order)](#TransformBuilder-com.aspose.threed.Matrix4-com.aspose.threed.ComposeOrder-) | Construeer een [TransformBuilder](../../com.aspose.threed/transformbuilder) met een initiële transformatiematrix en opgegeven samenvoegvolgorde |
| [TransformBuilder(ComposeOrder order)](#TransformBuilder-com.aspose.threed.ComposeOrder-) | Construeer een [TransformBuilder](../../com.aspose.threed/transformbuilder) met een initiële identiteits‑transformatiematrix en opgegeven samenvoegvolgorde |
| [TransformBuilder()](#TransformBuilder--) | Construeer een [TransformBuilder](../../com.aspose.threed/transformbuilder) met een initiële identiteits‑transformatiematrix en opgegeven samenvoegvolgorde |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [append(Matrix4 m)](#append-com.aspose.threed.Matrix4-) | Voeg de nieuwe transformatiematrix toe aan de transformatieketen. |
| [compose(Matrix4 m)](#compose-com.aspose.threed.Matrix4-) | Voeg het argument toe of plaats het ervoor in de interne matrix. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getComposeOrder()](#getComposeOrder--) | Haalt de samenvoegvolgorde van de keten op. |
| [getMatrix()](#getMatrix--) | Haalt de huidige matrixwaarde op |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [prepend(Matrix4 m)](#prepend-com.aspose.threed.Matrix4-) | Plaats de nieuwe transformatiematrix vooraan in de transformatieketen. |
| [rearrange(Axis newX, Axis newY, Axis newZ)](#rearrange-com.aspose.threed.Axis-com.aspose.threed.Axis-com.aspose.threed.Axis-) | Herschik de lay-out van de as. |
| [reset()](#reset--) | Reset de transformatie naar de identiteitsmatrix |
| [rotate(Quaternion q)](#rotate-com.aspose.threed.Quaternion-) | Koppel een rotatie met een quaternion **Voorbeeld:** |
| [rotateDegree(Vector3 rot, RotationOrder order)](#rotateDegree-com.aspose.threed.Vector3-com.aspose.threed.RotationOrder-) | Voeg rotatie toe met gespecificeerde volgorde |
| [rotateDegree(double angle, Vector3 axis)](#rotateDegree-double-com.aspose.threed.Vector3-) | Koppel een rotatie-transformatie in graden |
| [rotateEulerDegree(double degX, double degY, double degZ)](#rotateEulerDegree-double-double-double-) | Koppel een rotatie met Euler-hoeken in graden **Voorbeeld:** |
| [rotateEulerRadian(Vector3 r)](#rotateEulerRadian-com.aspose.threed.Vector3-) | Koppel een rotatie met Euler-hoeken in radialen **Voorbeeld:** |
| [rotateEulerRadian(double x, double y, double z)](#rotateEulerRadian-double-double-double-) | Koppel een rotatie met Euler-hoeken in radialen **Voorbeeld:** |
| [rotateRadian(Vector3 rot, RotationOrder order)](#rotateRadian-com.aspose.threed.Vector3-com.aspose.threed.RotationOrder-) | Voeg rotatie toe met gespecificeerde volgorde |
| [rotateRadian(double angle, Vector3 axis)](#rotateRadian-double-com.aspose.threed.Vector3-) | Koppel een rotatie-transformatie in radialen |
| [scale(Vector3 s)](#scale-com.aspose.threed.Vector3-) | Koppel een schaal-transformatie **Voorbeeld:** |
| [scale(double s)](#scale-double-) | Koppel een schaal-transformatie matrix met een component geschaald met s **Voorbeeld:** |
| [scale(double x, double y, double z)](#scale-double-double-double-) | Koppel een schaal-transformatie matrix **Voorbeeld:** |
| [setComposeOrder(ComposeOrder value)](#setComposeOrder-com.aspose.threed.ComposeOrder-) | Stelt de samenstellingsvolgorde van de keten in. |
| [setMatrix(Matrix4 value)](#setMatrix-com.aspose.threed.Matrix4-) | Stelt de huidige matrixwaarde in |
| [toString()](#toString--) |  |
| [translate(Vector3 v)](#translate-com.aspose.threed.Vector3-) | Koppel een translatie-transformatie **Voorbeeld:** |
| [translate(double tx, double ty, double tz)](#translate-double-double-double-) | Koppel een translatie-transformatie **Voorbeeld:** |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TransformBuilder(Matrix4 initial, ComposeOrder order) {#TransformBuilder-com.aspose.threed.Matrix4-com.aspose.threed.ComposeOrder-}
```
public TransformBuilder(Matrix4 initial, ComposeOrder order)
```


Construeer een [TransformBuilder](../../com.aspose.threed/transformbuilder) met een initiële transformatiematrix en opgegeven samenvoegvolgorde

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| initial | [Matrix4](../../com.aspose.threed/matrix4) |  |
| order | [ComposeOrder](../../com.aspose.threed/composeorder) |  |

### TransformBuilder(ComposeOrder order) {#TransformBuilder-com.aspose.threed.ComposeOrder-}
```
public TransformBuilder(ComposeOrder order)
```


Construeer een [TransformBuilder](../../com.aspose.threed/transformbuilder) met een initiële identiteits‑transformatiematrix en opgegeven samenvoegvolgorde

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| order | [ComposeOrder](../../com.aspose.threed/composeorder) |  |

### TransformBuilder() {#TransformBuilder--}
```
public TransformBuilder()
```


Construeer een [TransformBuilder](../../com.aspose.threed/transformbuilder) met een initiële identiteits‑transformatiematrix en opgegeven samenvoegvolgorde

### append(Matrix4 m) {#append-com.aspose.threed.Matrix4-}
```
public TransformBuilder append(Matrix4 m)
```


Voeg de nieuwe transformatiematrix toe aan de transformatieketen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| m | [Matrix4](../../com.aspose.threed/matrix4) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### compose(Matrix4 m) {#compose-com.aspose.threed.Matrix4-}
```
public void compose(Matrix4 m)
```


Voeg het argument toe of plaats het ervoor in de interne matrix.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| m | [Matrix4](../../com.aspose.threed/matrix4) |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


Haalt de samenvoegvolgorde van de keten op.

**Returns:**
[ComposeOrder](../../com.aspose.threed/composeorder) - the chain compose order.
### getMatrix() {#getMatrix--}
```
public Matrix4 getMatrix()
```


Haalt de huidige matrixwaarde op

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


Plaats de nieuwe transformatiematrix vooraan in de transformatieketen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| m | [Matrix4](../../com.aspose.threed/matrix4) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### rearrange(Axis newX, Axis newY, Axis newZ) {#rearrange-com.aspose.threed.Axis-com.aspose.threed.Axis-com.aspose.threed.Axis-}
```
public TransformBuilder rearrange(Axis newX, Axis newY, Axis newZ)
```


Herschik de lay-out van de as.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newX | [Axis](../../com.aspose.threed/axis) | De nieuwe x-componentbron |
| newY | [Axis](../../com.aspose.threed/axis) | De nieuwe y-componentbron |
| newZ | [Axis](../../com.aspose.threed/axis) | De nieuwe z-componentbron |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### reset() {#reset--}
```
public void reset()
```


Reset de transformatie naar de identiteitsmatrix

### rotate(Quaternion q) {#rotate-com.aspose.threed.Quaternion-}
```
public TransformBuilder rotate(Quaternion q)
```


Koppel een rotatie met een quaternion **Voorbeeld:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotate(Quaternion.fromEulerAngle(0, Math.PI, 0));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### rotateDegree(Vector3 rot, RotationOrder order) {#rotateDegree-com.aspose.threed.Vector3-com.aspose.threed.RotationOrder-}
```
public void rotateDegree(Vector3 rot, RotationOrder order)
```


Voeg rotatie toe met gespecificeerde volgorde

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rot | [Vector3](../../com.aspose.threed/vector3) | Rotatie in graden |
| order | [RotationOrder](../../com.aspose.threed/rotationorder) |  |

### rotateDegree(double angle, Vector3 axis) {#rotateDegree-double-com.aspose.threed.Vector3-}
```
public TransformBuilder rotateDegree(double angle, Vector3 axis)
```


Koppel een rotatie-transformatie in graden

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hoek | double | De hoek om te roteren in graden |
|  | axis | [Vector3](../../com.aspose.threed/vector3) | De as om te roteren **Voorbeeld:** |

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


Koppel een rotatie met Euler-hoeken in graden **Voorbeeld:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotateEulerDegree(0, 90, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parameter | Type | Beschrijving |
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


Koppel een rotatie met Euler-hoeken in radialen **Voorbeeld:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotateEulerRadian(new Vector3(0, Math.PI, 0));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| r | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### rotateEulerRadian(double x, double y, double z) {#rotateEulerRadian-double-double-double-}
```
public TransformBuilder rotateEulerRadian(double x, double y, double z)
```


Koppel een rotatie met Euler-hoeken in radialen **Voorbeeld:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotateEulerRadian(0, Math.PI, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parameter | Type | Beschrijving |
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


Voeg rotatie toe met gespecificeerde volgorde

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | rot | [Vector3](../../com.aspose.threed/vector3) | Rotatie in radialen **Voorbeeld:** |

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


Koppel een rotatie-transformatie in radialen

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hoek | double | De hoek om te roteren in radialen |
|  | axis | [Vector3](../../com.aspose.threed/vector3) | De as om te roteren **Voorbeeld:** |

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


Koppel een schaal-transformatie **Voorbeeld:**

```
TransformBuilder tb = new TransformBuilder();
     tb.scale(new Vector3(10, 10, 10));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| s | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### scale(double s) {#scale-double-}
```
public TransformBuilder scale(double s)
```


Koppel een schaal-transformatie matrix met een component geschaald met s **Voorbeeld:**

```
TransformBuilder tb = new TransformBuilder();
     tb.scale(10);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| s | double |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### scale(double x, double y, double z) {#scale-double-double-double-}
```
public TransformBuilder scale(double x, double y, double z)
```


Koppel een schaal-transformatie matrix **Voorbeeld:**

```
TransformBuilder tb = new TransformBuilder();
     tb.scale(10, 10, 10);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parameter | Type | Beschrijving |
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


Stelt de samenstellingsvolgorde van de keten in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ComposeOrder](../../com.aspose.threed/composeorder) | Nieuwe waarde |

### setMatrix(Matrix4 value) {#setMatrix-com.aspose.threed.Matrix4-}
```
public void setMatrix(Matrix4 value)
```


Stelt de huidige matrixwaarde in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | Nieuwe waarde |

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


Koppel een translatie-transformatie **Voorbeeld:**

```
TransformBuilder tb = new TransformBuilder();
     tb.translate(new Vector3(0, 10, 0));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### translate(double tx, double ty, double tz) {#translate-double-double-double-}
```
public TransformBuilder translate(double tx, double ty, double tz)
```


Koppel een translatie-transformatie **Voorbeeld:**

```
TransformBuilder tb = new TransformBuilder();
     tb.translate(0, 10, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

