---
title: "TransformBuilder"
second_title: "Aspose.3D for Java API Referansı"
description: "Bu  bir dizi dönüşümle dönüşüm matrisini oluşturmak için kullanılır."
type: docs
weight: 191
url: /tr/java/com.aspose.threed/transformbuilder/
---

**Inheritance:**
java.lang.Object
```
public class TransformBuilder
```

Bu [TransformBuilder](../../com.aspose.threed/transformbuilder) bir dizi dönüşümle dönüşüm matrisini oluşturmak için kullanılır. **Example:** Aşağıdaki kod, bir dizi işlemle nasıl matris oluşturulacağını gösterir

```
TransformBuilder tb = new TransformBuilder();
     tb.translate(10, 20, 0);
     tb.scale(10, 10, 10);
     tb.rotateEulerDegree(90, 0, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TransformBuilder(Matrix4 initial, ComposeOrder order)](#TransformBuilder-com.aspose.threed.Matrix4-com.aspose.threed.ComposeOrder-) | Başlangıç dönüşüm matrisine ve belirtilen birleştirme sırasına sahip bir [TransformBuilder](../../com.aspose.threed/transformbuilder) oluşturun |
| [TransformBuilder(ComposeOrder order)](#TransformBuilder-com.aspose.threed.ComposeOrder-) | Başlangıç kimlik dönüşüm matrisine ve belirtilen birleştirme sırasına sahip bir [TransformBuilder](../../com.aspose.threed/transformbuilder) oluşturun |
| [TransformBuilder()](#TransformBuilder--) | Başlangıç kimlik dönüşüm matrisine ve belirtilen birleştirme sırasına sahip bir [TransformBuilder](../../com.aspose.threed/transformbuilder) oluşturun |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [append(Matrix4 m)](#append-com.aspose.threed.Matrix4-) | Yeni dönüşüm matrisini dönüşüm zincirine ekle. |
| [compose(Matrix4 m)](#compose-com.aspose.threed.Matrix4-) | Argümanı iç matrisine ekle veya ön ekle. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getComposeOrder()](#getComposeOrder--) | Zincir birleştirme sırasını alır. |
| [getMatrix()](#getMatrix--) | Mevcut matris değerini alır |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [prepend(Matrix4 m)](#prepend-com.aspose.threed.Matrix4-) | Yeni dönüşüm matrisini dönüşüm zincirinin başına ekle. |
| [rearrange(Axis newX, Axis newY, Axis newZ)](#rearrange-com.aspose.threed.Axis-com.aspose.threed.Axis-com.aspose.threed.Axis-) | Eksenin düzenini yeniden düzenle. |
| [reset()](#reset--) | Dönüşümü kimlik matrisine sıfırla |
| [rotate(Quaternion q)](#rotate-com.aspose.threed.Quaternion-) | Bir kuaternion ile dönüşümü zincirle **Example:** |
| [rotateDegree(Vector3 rot, RotationOrder order)](#rotateDegree-com.aspose.threed.Vector3-com.aspose.threed.RotationOrder-) | Belirtilen sırayla dönüşüm ekle |
| [rotateDegree(double angle, Vector3 axis)](#rotateDegree-double-com.aspose.threed.Vector3-) | Derece cinsinden bir dönüşüm dönüşümünü zincirle |
| [rotateEulerDegree(double degX, double degY, double degZ)](#rotateEulerDegree-double-double-double-) | Derece cinsinden Euler açılarıyla bir dönüşümü zincirle **Example:** |
| [rotateEulerRadian(Vector3 r)](#rotateEulerRadian-com.aspose.threed.Vector3-) | Radyan cinsinden Euler açılarıyla bir dönüşümü zincirle **Example:** |
| [rotateEulerRadian(double x, double y, double z)](#rotateEulerRadian-double-double-double-) | Radyan cinsinden Euler açılarıyla bir dönüşümü zincirle **Example:** |
| [rotateRadian(Vector3 rot, RotationOrder order)](#rotateRadian-com.aspose.threed.Vector3-com.aspose.threed.RotationOrder-) | Belirtilen sırayla dönüşüm ekle |
| [rotateRadian(double angle, Vector3 axis)](#rotateRadian-double-com.aspose.threed.Vector3-) | Radyan cinsinden bir dönüşüm dönüşümünü zincirle |
| [scale(Vector3 s)](#scale-com.aspose.threed.Vector3-) | Bir ölçek dönüşümünü zincirle **Example:** |
| [scale(double s)](#scale-double-) | s ile ölçeklendirilmiş bir bileşen içeren bir ölçekleme dönüşüm matrisini zincirle **Example:** |
| [scale(double x, double y, double z)](#scale-double-double-double-) | Bir ölçekleme dönüşüm matrisini zincirle **Example:** |
| [setComposeOrder(ComposeOrder value)](#setComposeOrder-com.aspose.threed.ComposeOrder-) | Zincir birleştirme sırasını ayarlar. |
| [setMatrix(Matrix4 value)](#setMatrix-com.aspose.threed.Matrix4-) | Mevcut matris değerini ayarlar |
| [toString()](#toString--) |  |
| [translate(Vector3 v)](#translate-com.aspose.threed.Vector3-) | Bir çeviri dönüşümünü zincirle **Example:** |
| [translate(double tx, double ty, double tz)](#translate-double-double-double-) | Bir çeviri dönüşümünü zincirle **Example:** |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TransformBuilder(Matrix4 initial, ComposeOrder order) {#TransformBuilder-com.aspose.threed.Matrix4-com.aspose.threed.ComposeOrder-}
```
public TransformBuilder(Matrix4 initial, ComposeOrder order)
```


Başlangıç dönüşüm matrisine ve belirtilen birleştirme sırasına sahip bir [TransformBuilder](../../com.aspose.threed/transformbuilder) oluşturun

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| initial | [Matrix4](../../com.aspose.threed/matrix4) |  |
| order | [ComposeOrder](../../com.aspose.threed/composeorder) |  |

### TransformBuilder(ComposeOrder order) {#TransformBuilder-com.aspose.threed.ComposeOrder-}
```
public TransformBuilder(ComposeOrder order)
```


Başlangıç kimlik dönüşüm matrisine ve belirtilen birleştirme sırasına sahip bir [TransformBuilder](../../com.aspose.threed/transformbuilder) oluşturun

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| order | [ComposeOrder](../../com.aspose.threed/composeorder) |  |

### TransformBuilder() {#TransformBuilder--}
```
public TransformBuilder()
```


Başlangıç kimlik dönüşüm matrisine ve belirtilen birleştirme sırasına sahip bir [TransformBuilder](../../com.aspose.threed/transformbuilder) oluşturun

### append(Matrix4 m) {#append-com.aspose.threed.Matrix4-}
```
public TransformBuilder append(Matrix4 m)
```


Yeni dönüşüm matrisini dönüşüm zincirine ekle.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| m | [Matrix4](../../com.aspose.threed/matrix4) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### compose(Matrix4 m) {#compose-com.aspose.threed.Matrix4-}
```
public void compose(Matrix4 m)
```


Argümanı iç matrisine ekle veya ön ekle.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| m | [Matrix4](../../com.aspose.threed/matrix4) |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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


Zincir birleştirme sırasını alır.

**Returns:**
[ComposeOrder](../../com.aspose.threed/composeorder) - the chain compose order.
### getMatrix() {#getMatrix--}
```
public Matrix4 getMatrix()
```


Mevcut matris değerini alır

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


Yeni dönüşüm matrisini dönüşüm zincirinin başına ekle.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| m | [Matrix4](../../com.aspose.threed/matrix4) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### rearrange(Axis newX, Axis newY, Axis newZ) {#rearrange-com.aspose.threed.Axis-com.aspose.threed.Axis-com.aspose.threed.Axis-}
```
public TransformBuilder rearrange(Axis newX, Axis newY, Axis newZ)
```


Eksenin düzenini yeniden düzenle.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newX | [Axis](../../com.aspose.threed/axis) | Yeni x bileşen kaynağı |
| newY | [Axis](../../com.aspose.threed/axis) | Yeni y bileşen kaynağı |
| newZ | [Axis](../../com.aspose.threed/axis) | Yeni z bileşen kaynağı |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### reset() {#reset--}
```
public void reset()
```


Dönüşümü kimlik matrisine sıfırla

### rotate(Quaternion q) {#rotate-com.aspose.threed.Quaternion-}
```
public TransformBuilder rotate(Quaternion q)
```


Bir kuaternion ile dönüşümü zincirle **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotate(Quaternion.fromEulerAngle(0, Math.PI, 0));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### rotateDegree(Vector3 rot, RotationOrder order) {#rotateDegree-com.aspose.threed.Vector3-com.aspose.threed.RotationOrder-}
```
public void rotateDegree(Vector3 rot, RotationOrder order)
```


Belirtilen sırayla dönüşüm ekle

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rot | [Vector3](../../com.aspose.threed/vector3) | Derece cinsinden dönüşüm |
| order | [RotationOrder](../../com.aspose.threed/rotationorder) |  |

### rotateDegree(double angle, Vector3 axis) {#rotateDegree-double-com.aspose.threed.Vector3-}
```
public TransformBuilder rotateDegree(double angle, Vector3 axis)
```


Derece cinsinden bir dönüşüm dönüşümünü zincirle

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| açı | double | Derece cinsinden döndürme açısı |
|  | axis | [Vector3](../../com.aspose.threed/vector3) | Döndürme ekseni **Example:** |

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


Derece cinsinden Euler açılarıyla bir dönüşümü zincirle **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotateEulerDegree(0, 90, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parametre | Tür | Açıklama |
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


Radyan cinsinden Euler açılarıyla bir dönüşümü zincirle **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotateEulerRadian(new Vector3(0, Math.PI, 0));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| r | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### rotateEulerRadian(double x, double y, double z) {#rotateEulerRadian-double-double-double-}
```
public TransformBuilder rotateEulerRadian(double x, double y, double z)
```


Radyan cinsinden Euler açılarıyla bir dönüşümü zincirle **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotateEulerRadian(0, Math.PI, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parametre | Tür | Açıklama |
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


Belirtilen sırayla dönüşüm ekle

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | rot | [Vector3](../../com.aspose.threed/vector3) | Radyan cinsinden dönüşüm **Example:** |

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


Radyan cinsinden bir dönüşüm dönüşümünü zincirle

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| açı | double | Radyan cinsinden döndürme açısı |
|  | axis | [Vector3](../../com.aspose.threed/vector3) | Döndürme ekseni **Example:** |

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


Bir ölçek dönüşümünü zincirle **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.scale(new Vector3(10, 10, 10));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### scale(double s) {#scale-double-}
```
public TransformBuilder scale(double s)
```


s ile ölçeklendirilmiş bir bileşen içeren bir ölçekleme dönüşüm matrisini zincirle **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.scale(10);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | double |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### scale(double x, double y, double z) {#scale-double-double-double-}
```
public TransformBuilder scale(double x, double y, double z)
```


Bir ölçekleme dönüşüm matrisini zincirle **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.scale(10, 10, 10);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parametre | Tür | Açıklama |
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


Zincir birleştirme sırasını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ComposeOrder](../../com.aspose.threed/composeorder) | Yeni değer |

### setMatrix(Matrix4 value) {#setMatrix-com.aspose.threed.Matrix4-}
```
public void setMatrix(Matrix4 value)
```


Mevcut matris değerini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | Yeni değer |

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


Bir çeviri dönüşümünü zincirle **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.translate(new Vector3(0, 10, 0));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### translate(double tx, double ty, double tz) {#translate-double-double-double-}
```
public TransformBuilder translate(double tx, double ty, double tz)
```


Bir çeviri dönüşümünü zincirle **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.translate(0, 10, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

