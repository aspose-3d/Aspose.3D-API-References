---
title: "TransformBuilder"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "يُستخدم   لبناء مصفوفة التحويل عبر سلسلة من التحويلات."
type: docs
weight: 191
url: /ar/java/com.aspose.threed/transformbuilder/
---

**Inheritance:**
java.lang.Object
```
public class TransformBuilder
```

يُستخدم [TransformBuilder](../../com.aspose.threed/transformbuilder) لبناء مصفوفة التحويل عبر سلسلة من التحويلات. **مثال:** يُظهر الكود التالي كيفية إنشاء مصفوفة من خلال مجموعة من العمليات

```
TransformBuilder tb = new TransformBuilder();
     tb.translate(10, 20, 0);
     tb.scale(10, 10, 10);
     tb.rotateEulerDegree(90, 0, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [TransformBuilder(Matrix4 initial, ComposeOrder order)](#TransformBuilder-com.aspose.threed.Matrix4-com.aspose.threed.ComposeOrder-) | إنشاء [TransformBuilder](../../com.aspose.threed/transformbuilder) بمصفوفة تحويل أولية وترتيب تجميع محدد |
| [TransformBuilder(ComposeOrder order)](#TransformBuilder-com.aspose.threed.ComposeOrder-) | إنشاء [TransformBuilder](../../com.aspose.threed/transformbuilder) بمصفوفة تحويل هوية أولية وترتيب تجميع محدد |
| [TransformBuilder()](#TransformBuilder--) | إنشاء [TransformBuilder](../../com.aspose.threed/transformbuilder) بمصفوفة تحويل هوية أولية وترتيب تجميع محدد |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [append(Matrix4 m)](#append-com.aspose.threed.Matrix4-) | إلحاق مصفوفة التحويل الجديدة بسلسلة التحويل. |
| [compose(Matrix4 m)](#compose-com.aspose.threed.Matrix4-) | إلحاق أو إلحاق مسبق للمعامل إلى المصفوفة الداخلية. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getComposeOrder()](#getComposeOrder--) | يحصل على ترتيب تجميع السلسلة. |
| [getMatrix()](#getMatrix--) | يحصل على قيمة المصفوفة الحالية |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [prepend(Matrix4 m)](#prepend-com.aspose.threed.Matrix4-) | إلحاق مسبق لمصفوفة التحويل الجديدة بسلسلة التحويل. |
| [rearrange(Axis newX, Axis newY, Axis newZ)](#rearrange-com.aspose.threed.Axis-com.aspose.threed.Axis-com.aspose.threed.Axis-) | إعادة ترتيب تخطيط المحور. |
| [reset()](#reset--) | إعادة تعيين التحويل إلى مصفوفة الهوية |
| [rotate(Quaternion q)](#rotate-com.aspose.threed.Quaternion-) | سلسلة دوران بواسطة رباعية **Example:** |
| [rotateDegree(Vector3 rot, RotationOrder order)](#rotateDegree-com.aspose.threed.Vector3-com.aspose.threed.RotationOrder-) | إلحاق دوران بترتيب محدد |
| [rotateDegree(double angle, Vector3 axis)](#rotateDegree-double-com.aspose.threed.Vector3-) | سلسلة تحويل دوران بالدرجة |
| [rotateEulerDegree(double degX, double degY, double degZ)](#rotateEulerDegree-double-double-double-) | سلسلة دوران بواسطة زوايا أويلر بالدرجة **Example:** |
| [rotateEulerRadian(Vector3 r)](#rotateEulerRadian-com.aspose.threed.Vector3-) | سلسلة دوران بواسطة زوايا أويلر بالراديان **Example:** |
| [rotateEulerRadian(double x, double y, double z)](#rotateEulerRadian-double-double-double-) | سلسلة دوران بواسطة زوايا أويلر بالراديان **Example:** |
| [rotateRadian(Vector3 rot, RotationOrder order)](#rotateRadian-com.aspose.threed.Vector3-com.aspose.threed.RotationOrder-) | إلحاق دوران بترتيب محدد |
| [rotateRadian(double angle, Vector3 axis)](#rotateRadian-double-com.aspose.threed.Vector3-) | سلسلة تحويل دوران بالراديان |
| [scale(Vector3 s)](#scale-com.aspose.threed.Vector3-) | سلسلة تحويل مقياس **Example:** |
| [scale(double s)](#scale-double-) | سلسلة مصفوفة تحويل مقياس مع مكوّن مُقاس بـ s **Example:** |
| [scale(double x, double y, double z)](#scale-double-double-double-) | سلسلة مصفوفة تحويل مقياس **Example:** |
| [setComposeOrder(ComposeOrder value)](#setComposeOrder-com.aspose.threed.ComposeOrder-) | يضبط ترتيب تركيب السلسلة. |
| [setMatrix(Matrix4 value)](#setMatrix-com.aspose.threed.Matrix4-) | يضبط قيمة المصفوفة الحالية |
| [toString()](#toString--) |  |
| [translate(Vector3 v)](#translate-com.aspose.threed.Vector3-) | سلسلة تحويل إزاحة **Example:** |
| [translate(double tx, double ty, double tz)](#translate-double-double-double-) | سلسلة تحويل إزاحة **Example:** |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TransformBuilder(Matrix4 initial, ComposeOrder order) {#TransformBuilder-com.aspose.threed.Matrix4-com.aspose.threed.ComposeOrder-}
```
public TransformBuilder(Matrix4 initial, ComposeOrder order)
```


إنشاء [TransformBuilder](../../com.aspose.threed/transformbuilder) بمصفوفة تحويل أولية وترتيب تجميع محدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| initial | [Matrix4](../../com.aspose.threed/matrix4) |  |
| order | [ComposeOrder](../../com.aspose.threed/composeorder) |  |

### TransformBuilder(ComposeOrder order) {#TransformBuilder-com.aspose.threed.ComposeOrder-}
```
public TransformBuilder(ComposeOrder order)
```


إنشاء [TransformBuilder](../../com.aspose.threed/transformbuilder) بمصفوفة تحويل هوية أولية وترتيب تجميع محدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| order | [ComposeOrder](../../com.aspose.threed/composeorder) |  |

### TransformBuilder() {#TransformBuilder--}
```
public TransformBuilder()
```


إنشاء [TransformBuilder](../../com.aspose.threed/transformbuilder) بمصفوفة تحويل هوية أولية وترتيب تجميع محدد

### append(Matrix4 m) {#append-com.aspose.threed.Matrix4-}
```
public TransformBuilder append(Matrix4 m)
```


إلحاق مصفوفة التحويل الجديدة بسلسلة التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| m | [Matrix4](../../com.aspose.threed/matrix4) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### compose(Matrix4 m) {#compose-com.aspose.threed.Matrix4-}
```
public void compose(Matrix4 m)
```


إلحاق أو إلحاق مسبق للمعامل إلى المصفوفة الداخلية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| m | [Matrix4](../../com.aspose.threed/matrix4) |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
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


يحصل على ترتيب تجميع السلسلة.

**Returns:**
[ComposeOrder](../../com.aspose.threed/composeorder) - the chain compose order.
### getMatrix() {#getMatrix--}
```
public Matrix4 getMatrix()
```


يحصل على قيمة المصفوفة الحالية

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


إلحاق مسبق لمصفوفة التحويل الجديدة بسلسلة التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| m | [Matrix4](../../com.aspose.threed/matrix4) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### rearrange(Axis newX, Axis newY, Axis newZ) {#rearrange-com.aspose.threed.Axis-com.aspose.threed.Axis-com.aspose.threed.Axis-}
```
public TransformBuilder rearrange(Axis newX, Axis newY, Axis newZ)
```


إعادة ترتيب تخطيط المحور.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newX | [Axis](../../com.aspose.threed/axis) | مصدر المكوّن x الجديد |
| newY | [Axis](../../com.aspose.threed/axis) | مصدر المكوّن y الجديد |
| newZ | [Axis](../../com.aspose.threed/axis) | مصدر المكوّن z الجديد |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### reset() {#reset--}
```
public void reset()
```


إعادة تعيين التحويل إلى مصفوفة الهوية

### rotate(Quaternion q) {#rotate-com.aspose.threed.Quaternion-}
```
public TransformBuilder rotate(Quaternion q)
```


سلسلة دوران بواسطة رباعية **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotate(Quaternion.fromEulerAngle(0, Math.PI, 0));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### rotateDegree(Vector3 rot, RotationOrder order) {#rotateDegree-com.aspose.threed.Vector3-com.aspose.threed.RotationOrder-}
```
public void rotateDegree(Vector3 rot, RotationOrder order)
```


إلحاق دوران بترتيب محدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rot | [Vector3](../../com.aspose.threed/vector3) | دوران بالدرجات |
| order | [RotationOrder](../../com.aspose.threed/rotationorder) |  |

### rotateDegree(double angle, Vector3 axis) {#rotateDegree-double-com.aspose.threed.Vector3-}
```
public TransformBuilder rotateDegree(double angle, Vector3 axis)
```


سلسلة تحويل دوران بالدرجة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| زاوية | double | الزاوية للدوران بالدرجة |
|  | axis | [Vector3](../../com.aspose.threed/vector3) | المحور للدوران **Example:** |

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


سلسلة دوران بواسطة زوايا أويلر بالدرجة **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotateEulerDegree(0, 90, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| معامل | نوع | الوصف |
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


سلسلة دوران بواسطة زوايا أويلر بالراديان **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotateEulerRadian(new Vector3(0, Math.PI, 0));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| r | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### rotateEulerRadian(double x, double y, double z) {#rotateEulerRadian-double-double-double-}
```
public TransformBuilder rotateEulerRadian(double x, double y, double z)
```


سلسلة دوران بواسطة زوايا أويلر بالراديان **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotateEulerRadian(0, Math.PI, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| معامل | نوع | الوصف |
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


إلحاق دوران بترتيب محدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | rot | [Vector3](../../com.aspose.threed/vector3) | دوران بالراديان **Example:** |

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


سلسلة تحويل دوران بالراديان

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| زاوية | double | الزاوية للدوران بالراديان |
|  | axis | [Vector3](../../com.aspose.threed/vector3) | المحور للدوران **Example:** |

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


سلسلة تحويل مقياس **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.scale(new Vector3(10, 10, 10));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| s | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### scale(double s) {#scale-double-}
```
public TransformBuilder scale(double s)
```


سلسلة مصفوفة تحويل مقياس مع مكوّن مُقاس بـ s **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.scale(10);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| s | double |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### scale(double x, double y, double z) {#scale-double-double-double-}
```
public TransformBuilder scale(double x, double y, double z)
```


سلسلة مصفوفة تحويل مقياس **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.scale(10, 10, 10);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| معامل | نوع | الوصف |
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


يضبط ترتيب تركيب السلسلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ComposeOrder](../../com.aspose.threed/composeorder) | القيمة الجديدة |

### setMatrix(Matrix4 value) {#setMatrix-com.aspose.threed.Matrix4-}
```
public void setMatrix(Matrix4 value)
```


يضبط قيمة المصفوفة الحالية

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | القيمة الجديدة |

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


سلسلة تحويل إزاحة **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.translate(new Vector3(0, 10, 0));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### translate(double tx, double ty, double tz) {#translate-double-double-double-}
```
public TransformBuilder translate(double tx, double ty, double tz)
```


سلسلة تحويل إزاحة **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.translate(0, 10, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| معامل | نوع | الوصف |
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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

