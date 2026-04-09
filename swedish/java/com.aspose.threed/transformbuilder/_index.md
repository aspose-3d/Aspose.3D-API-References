---
title: TransformBuilder
second_title: Aspose.3D for Java API-referens
description: Den  används för att bygga en transformmatris genom en kedja av transformationer.
type: docs
weight: 191
url: /sv/java/com.aspose.threed/transformbuilder/
---

**Inheritance:**
java.lang.Object
```
public class TransformBuilder
```

Den [TransformBuilder](../../com.aspose.threed/transformbuilder) används för att bygga en transformmatris genom en kedja av transformationer. **Exempel:** Följande kod visar hur man skapar en matris genom en uppsättning operationer

```
TransformBuilder tb = new TransformBuilder();
     tb.translate(10, 20, 0);
     tb.scale(10, 10, 10);
     tb.rotateEulerDegree(90, 0, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [TransformBuilder(Matrix4 initial, ComposeOrder order)](#TransformBuilder-com.aspose.threed.Matrix4-com.aspose.threed.ComposeOrder-) | Skapa en [TransformBuilder](../../com.aspose.threed/transformbuilder) med initial transformmatris och specificerad sammansättningsordning |
| [TransformBuilder(ComposeOrder order)](#TransformBuilder-com.aspose.threed.ComposeOrder-) | Skapa en [TransformBuilder](../../com.aspose.threed/transformbuilder) med initial identitets-transformmatris och specificerad sammansättningsordning |
| [TransformBuilder()](#TransformBuilder--) | Skapa en [TransformBuilder](../../com.aspose.threed/transformbuilder) med initial identitets-transformmatris och specificerad sammansättningsordning |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [append(Matrix4 m)](#append-com.aspose.threed.Matrix4-) | Lägg till den nya transformmatrisen i transformkedjan. |
| [compose(Matrix4 m)](#compose-com.aspose.threed.Matrix4-) | Lägg till eller sätt in argumentet i den interna matrisen. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getComposeOrder()](#getComposeOrder--) | Hämtar kedjans sammansättningsordning. |
| [getMatrix()](#getMatrix--) | Hämtar det aktuella matrisvärdet |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [prepend(Matrix4 m)](#prepend-com.aspose.threed.Matrix4-) | Sätt in den nya transformmatrisen i början av transformkedjan. |
| [rearrange(Axis newX, Axis newY, Axis newZ)](#rearrange-com.aspose.threed.Axis-com.aspose.threed.Axis-com.aspose.threed.Axis-) | Omarrangera layouten för axeln. |
| [reset()](#reset--) | Återställ transformen till identitetsmatrisen |
| [rotate(Quaternion q)](#rotate-com.aspose.threed.Quaternion-) | Kedja en rotation med en kvaternion **Exempel:** |
| [rotateDegree(Vector3 rot, RotationOrder order)](#rotateDegree-com.aspose.threed.Vector3-com.aspose.threed.RotationOrder-) | Lägg till rotation med angiven ordning |
| [rotateDegree(double angle, Vector3 axis)](#rotateDegree-double-com.aspose.threed.Vector3-) | Kedja en rotationstransform i grader |
| [rotateEulerDegree(double degX, double degY, double degZ)](#rotateEulerDegree-double-double-double-) | Kedja en rotation med Euler‑vinklar i grader **Exempel:** |
| [rotateEulerRadian(Vector3 r)](#rotateEulerRadian-com.aspose.threed.Vector3-) | Kedja en rotation med Euler‑vinklar i radianer **Exempel:** |
| [rotateEulerRadian(double x, double y, double z)](#rotateEulerRadian-double-double-double-) | Kedja en rotation med Euler‑vinklar i radianer **Exempel:** |
| [rotateRadian(Vector3 rot, RotationOrder order)](#rotateRadian-com.aspose.threed.Vector3-com.aspose.threed.RotationOrder-) | Lägg till rotation med angiven ordning |
| [rotateRadian(double angle, Vector3 axis)](#rotateRadian-double-com.aspose.threed.Vector3-) | Kedja en rotationstransform i radianer |
| [scale(Vector3 s)](#scale-com.aspose.threed.Vector3-) | Kedja en skalningstransform **Exempel:** |
| [scale(double s)](#scale-double-) | Kedja en skalningstransformmatris med en komponent skalad med s **Exempel:** |
| [scale(double x, double y, double z)](#scale-double-double-double-) | Kedja en skalningstransformmatris **Exempel:** |
| [setComposeOrder(ComposeOrder value)](#setComposeOrder-com.aspose.threed.ComposeOrder-) | Ställer in kedjans sammansättningsordning. |
| [setMatrix(Matrix4 value)](#setMatrix-com.aspose.threed.Matrix4-) | Ställer in det aktuella matrisvärdet |
| [toString()](#toString--) |  |
| [translate(Vector3 v)](#translate-com.aspose.threed.Vector3-) | Kedja en translatetransform **Exempel:** |
| [translate(double tx, double ty, double tz)](#translate-double-double-double-) | Kedja en translatetransform **Exempel:** |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TransformBuilder(Matrix4 initial, ComposeOrder order) {#TransformBuilder-com.aspose.threed.Matrix4-com.aspose.threed.ComposeOrder-}
```
public TransformBuilder(Matrix4 initial, ComposeOrder order)
```


Skapa en [TransformBuilder](../../com.aspose.threed/transformbuilder) med initial transformmatris och specificerad sammansättningsordning

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| initial | [Matrix4](../../com.aspose.threed/matrix4) |  |
| order | [ComposeOrder](../../com.aspose.threed/composeorder) |  |

### TransformBuilder(ComposeOrder order) {#TransformBuilder-com.aspose.threed.ComposeOrder-}
```
public TransformBuilder(ComposeOrder order)
```


Skapa en [TransformBuilder](../../com.aspose.threed/transformbuilder) med initial identitets-transformmatris och specificerad sammansättningsordning

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| order | [ComposeOrder](../../com.aspose.threed/composeorder) |  |

### TransformBuilder() {#TransformBuilder--}
```
public TransformBuilder()
```


Skapa en [TransformBuilder](../../com.aspose.threed/transformbuilder) med initial identitets-transformmatris och specificerad sammansättningsordning

### append(Matrix4 m) {#append-com.aspose.threed.Matrix4-}
```
public TransformBuilder append(Matrix4 m)
```


Lägg till den nya transformmatrisen i transformkedjan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| m | [Matrix4](../../com.aspose.threed/matrix4) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### compose(Matrix4 m) {#compose-com.aspose.threed.Matrix4-}
```
public void compose(Matrix4 m)
```


Lägg till eller sätt in argumentet i den interna matrisen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| m | [Matrix4](../../com.aspose.threed/matrix4) |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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


Hämtar kedjans sammansättningsordning.

**Returns:**
[ComposeOrder](../../com.aspose.threed/composeorder) - the chain compose order.
### getMatrix() {#getMatrix--}
```
public Matrix4 getMatrix()
```


Hämtar det aktuella matrisvärdet

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


Sätt in den nya transformmatrisen i början av transformkedjan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| m | [Matrix4](../../com.aspose.threed/matrix4) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### rearrange(Axis newX, Axis newY, Axis newZ) {#rearrange-com.aspose.threed.Axis-com.aspose.threed.Axis-com.aspose.threed.Axis-}
```
public TransformBuilder rearrange(Axis newX, Axis newY, Axis newZ)
```


Omarrangera layouten för axeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newX | [Axis](../../com.aspose.threed/axis) | Den nya x‑komponentens källa |
| newY | [Axis](../../com.aspose.threed/axis) | Den nya y‑komponentens källa |
| newZ | [Axis](../../com.aspose.threed/axis) | Den nya z‑komponentens källa |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### reset() {#reset--}
```
public void reset()
```


Återställ transformen till identitetsmatrisen

### rotate(Quaternion q) {#rotate-com.aspose.threed.Quaternion-}
```
public TransformBuilder rotate(Quaternion q)
```


Kedja en rotation med en kvaternion **Exempel:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotate(Quaternion.fromEulerAngle(0, Math.PI, 0));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### rotateDegree(Vector3 rot, RotationOrder order) {#rotateDegree-com.aspose.threed.Vector3-com.aspose.threed.RotationOrder-}
```
public void rotateDegree(Vector3 rot, RotationOrder order)
```


Lägg till rotation med angiven ordning

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rot | [Vector3](../../com.aspose.threed/vector3) | Rotation i grader |
| order | [RotationOrder](../../com.aspose.threed/rotationorder) |  |

### rotateDegree(double angle, Vector3 axis) {#rotateDegree-double-com.aspose.threed.Vector3-}
```
public TransformBuilder rotateDegree(double angle, Vector3 axis)
```


Kedja en rotationstransform i grader

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| angle | double | Vinkeln att rotera i grader |
|  | axis | [Vector3](../../com.aspose.threed/vector3) | Axeln att rotera **Exempel:** |

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


Kedja en rotation med Euler‑vinklar i grader **Exempel:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotateEulerDegree(0, 90, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parameter | Typ | Beskrivning |
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


Kedja en rotation med Euler‑vinklar i radianer **Exempel:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotateEulerRadian(new Vector3(0, Math.PI, 0));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| r | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### rotateEulerRadian(double x, double y, double z) {#rotateEulerRadian-double-double-double-}
```
public TransformBuilder rotateEulerRadian(double x, double y, double z)
```


Kedja en rotation med Euler‑vinklar i radianer **Exempel:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotateEulerRadian(0, Math.PI, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parameter | Typ | Beskrivning |
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


Lägg till rotation med angiven ordning

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | rot | [Vector3](../../com.aspose.threed/vector3) | Rotation i radianer **Exempel:** |

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


Kedja en rotationstransform i radianer

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| angle | double | Vinkeln att rotera i radianer |
|  | axis | [Vector3](../../com.aspose.threed/vector3) | Axeln att rotera **Exempel:** |

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


Kedja en skalningstransform **Exempel:**

```
TransformBuilder tb = new TransformBuilder();
     tb.scale(new Vector3(10, 10, 10));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### scale(double s) {#scale-double-}
```
public TransformBuilder scale(double s)
```


Kedja en skalningstransformmatris med en komponent skalad med s **Exempel:**

```
TransformBuilder tb = new TransformBuilder();
     tb.scale(10);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | double |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### scale(double x, double y, double z) {#scale-double-double-double-}
```
public TransformBuilder scale(double x, double y, double z)
```


Kedja en skalningstransformmatris **Exempel:**

```
TransformBuilder tb = new TransformBuilder();
     tb.scale(10, 10, 10);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parameter | Typ | Beskrivning |
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


Ställer in kedjans sammansättningsordning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ComposeOrder](../../com.aspose.threed/composeorder) | Nytt värde |

### setMatrix(Matrix4 value) {#setMatrix-com.aspose.threed.Matrix4-}
```
public void setMatrix(Matrix4 value)
```


Ställer in det aktuella matrisvärdet

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | Nytt värde |

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


Kedja en translatetransform **Exempel:**

```
TransformBuilder tb = new TransformBuilder();
     tb.translate(new Vector3(0, 10, 0));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### translate(double tx, double ty, double tz) {#translate-double-double-double-}
```
public TransformBuilder translate(double tx, double ty, double tz)
```


Kedja en translatetransform **Exempel:**

```
TransformBuilder tb = new TransformBuilder();
     tb.translate(0, 10, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

