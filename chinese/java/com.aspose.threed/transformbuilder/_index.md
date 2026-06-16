---
title: "TransformBuilder"
second_title: "Aspose.3D for Java API 参考"
description: "该  用于通过一系列变换构建变换矩阵。"
type: docs
weight: 191
url: /zh/java/com.aspose.threed/transformbuilder/
---

**Inheritance:**
java.lang.Object
```
public class TransformBuilder
```

该 [TransformBuilder](../../com.aspose.threed/transformbuilder) 用于通过一系列变换构建变换矩阵。 **Example:** 以下代码展示了如何通过一组操作创建矩阵。

```
TransformBuilder tb = new TransformBuilder();
     tb.translate(10, 20, 0);
     tb.scale(10, 10, 10);
     tb.rotateEulerDegree(90, 0, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TransformBuilder(Matrix4 initial, ComposeOrder order)](#TransformBuilder-com.aspose.threed.Matrix4-com.aspose.threed.ComposeOrder-) | 使用初始变换矩阵和指定的组合顺序构造一个 [TransformBuilder](../../com.aspose.threed/transformbuilder) |
| [TransformBuilder(ComposeOrder order)](#TransformBuilder-com.aspose.threed.ComposeOrder-) | 使用初始单位变换矩阵和指定的组合顺序构造一个 [TransformBuilder](../../com.aspose.threed/transformbuilder) |
| [TransformBuilder()](#TransformBuilder--) | 使用初始单位变换矩阵和指定的组合顺序构造一个 [TransformBuilder](../../com.aspose.threed/transformbuilder) |
## 方法

| 方法 | 描述 |
| --- | --- |
| [append(Matrix4 m)](#append-com.aspose.threed.Matrix4-) | 将新的变换矩阵追加到变换链中。 |
| [compose(Matrix4 m)](#compose-com.aspose.threed.Matrix4-) | 将参数追加或前置到内部矩阵。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getComposeOrder()](#getComposeOrder--) | 获取链的组合顺序。 |
| [getMatrix()](#getMatrix--) | 获取当前矩阵值 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [prepend(Matrix4 m)](#prepend-com.aspose.threed.Matrix4-) | 将新的变换矩阵前置到变换链中。 |
| [rearrange(Axis newX, Axis newY, Axis newZ)](#rearrange-com.aspose.threed.Axis-com.aspose.threed.Axis-com.aspose.threed.Axis-) | 重新排列轴的布局。 |
| [reset()](#reset--) | 将变换重置为单位矩阵 |
| [rotate(Quaternion q)](#rotate-com.aspose.threed.Quaternion-) | 通过四元数链式旋转 **Example:** |
| [rotateDegree(Vector3 rot, RotationOrder order)](#rotateDegree-com.aspose.threed.Vector3-com.aspose.threed.RotationOrder-) | 按指定顺序追加旋转 |
| [rotateDegree(double angle, Vector3 axis)](#rotateDegree-double-com.aspose.threed.Vector3-) | 以度数链式旋转变换 |
| [rotateEulerDegree(double degX, double degY, double degZ)](#rotateEulerDegree-double-double-double-) | 以度数通过欧拉角链式旋转 **Example:** |
| [rotateEulerRadian(Vector3 r)](#rotateEulerRadian-com.aspose.threed.Vector3-) | 以弧度通过欧拉角链式旋转 **Example:** |
| [rotateEulerRadian(double x, double y, double z)](#rotateEulerRadian-double-double-double-) | 以弧度通过欧拉角链式旋转 **Example:** |
| [rotateRadian(Vector3 rot, RotationOrder order)](#rotateRadian-com.aspose.threed.Vector3-com.aspose.threed.RotationOrder-) | 按指定顺序追加旋转 |
| [rotateRadian(double angle, Vector3 axis)](#rotateRadian-double-com.aspose.threed.Vector3-) | 以弧度链式旋转变换 |
| [scale(Vector3 s)](#scale-com.aspose.threed.Vector3-) | 链式缩放变换 **Example:** |
| [scale(double s)](#scale-double-) | 链式缩放变换矩阵，其中一个分量按 s 缩放 **Example:** |
| [scale(double x, double y, double z)](#scale-double-double-double-) | 链式缩放变换矩阵 **Example:** |
| [setComposeOrder(ComposeOrder value)](#setComposeOrder-com.aspose.threed.ComposeOrder-) | 设置链式组合顺序。 |
| [setMatrix(Matrix4 value)](#setMatrix-com.aspose.threed.Matrix4-) | 设置当前矩阵值 |
| [toString()](#toString--) |  |
| [translate(Vector3 v)](#translate-com.aspose.threed.Vector3-) | 链式平移变换 **Example:** |
| [translate(double tx, double ty, double tz)](#translate-double-double-double-) | 链式平移变换 **Example:** |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TransformBuilder(Matrix4 initial, ComposeOrder order) {#TransformBuilder-com.aspose.threed.Matrix4-com.aspose.threed.ComposeOrder-}
```
public TransformBuilder(Matrix4 initial, ComposeOrder order)
```


使用初始变换矩阵和指定的组合顺序构造一个 [TransformBuilder](../../com.aspose.threed/transformbuilder)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| initial | [Matrix4](../../com.aspose.threed/matrix4) |  |
| order | [ComposeOrder](../../com.aspose.threed/composeorder) |  |

### TransformBuilder(ComposeOrder order) {#TransformBuilder-com.aspose.threed.ComposeOrder-}
```
public TransformBuilder(ComposeOrder order)
```


使用初始单位变换矩阵和指定的组合顺序构造一个 [TransformBuilder](../../com.aspose.threed/transformbuilder)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| order | [ComposeOrder](../../com.aspose.threed/composeorder) |  |

### TransformBuilder() {#TransformBuilder--}
```
public TransformBuilder()
```


使用初始单位变换矩阵和指定的组合顺序构造一个 [TransformBuilder](../../com.aspose.threed/transformbuilder)

### append(Matrix4 m) {#append-com.aspose.threed.Matrix4-}
```
public TransformBuilder append(Matrix4 m)
```


将新的变换矩阵追加到变换链中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| m | [Matrix4](../../com.aspose.threed/matrix4) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### compose(Matrix4 m) {#compose-com.aspose.threed.Matrix4-}
```
public void compose(Matrix4 m)
```


将参数追加或前置到内部矩阵。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| m | [Matrix4](../../com.aspose.threed/matrix4) |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
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


获取链的组合顺序。

**Returns:**
[ComposeOrder](../../com.aspose.threed/composeorder) - the chain compose order.
### getMatrix() {#getMatrix--}
```
public Matrix4 getMatrix()
```


获取当前矩阵值

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


将新的变换矩阵前置到变换链中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| m | [Matrix4](../../com.aspose.threed/matrix4) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### rearrange(Axis newX, Axis newY, Axis newZ) {#rearrange-com.aspose.threed.Axis-com.aspose.threed.Axis-com.aspose.threed.Axis-}
```
public TransformBuilder rearrange(Axis newX, Axis newY, Axis newZ)
```


重新排列轴的布局。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newX | [Axis](../../com.aspose.threed/axis) | 新的 x 分量来源 |
| newY | [Axis](../../com.aspose.threed/axis) | 新的 y 分量来源 |
| newZ | [Axis](../../com.aspose.threed/axis) | 新的 z 分量来源 |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### reset() {#reset--}
```
public void reset()
```


将变换重置为单位矩阵

### rotate(Quaternion q) {#rotate-com.aspose.threed.Quaternion-}
```
public TransformBuilder rotate(Quaternion q)
```


通过四元数链式旋转 **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotate(Quaternion.fromEulerAngle(0, Math.PI, 0));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### rotateDegree(Vector3 rot, RotationOrder order) {#rotateDegree-com.aspose.threed.Vector3-com.aspose.threed.RotationOrder-}
```
public void rotateDegree(Vector3 rot, RotationOrder order)
```


按指定顺序追加旋转

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rot | [Vector3](../../com.aspose.threed/vector3) | 以度数旋转 |
| order | [RotationOrder](../../com.aspose.threed/rotationorder) |  |

### rotateDegree(double angle, Vector3 axis) {#rotateDegree-double-com.aspose.threed.Vector3-}
```
public TransformBuilder rotateDegree(double angle, Vector3 axis)
```


以度数链式旋转变换

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| angle | double | 旋转角度（度） |
|  | axis | [Vector3](../../com.aspose.threed/vector3) | 旋转轴 **Example:** |

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


以度数通过欧拉角链式旋转 **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotateEulerDegree(0, 90, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| 参数 | 类型 | 描述 |
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


以弧度通过欧拉角链式旋转 **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotateEulerRadian(new Vector3(0, Math.PI, 0));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| r | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### rotateEulerRadian(double x, double y, double z) {#rotateEulerRadian-double-double-double-}
```
public TransformBuilder rotateEulerRadian(double x, double y, double z)
```


以弧度通过欧拉角链式旋转 **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotateEulerRadian(0, Math.PI, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| 参数 | 类型 | 描述 |
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


按指定顺序追加旋转

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | rot | [Vector3](../../com.aspose.threed/vector3) | 以弧度旋转 **Example:** |

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


以弧度链式旋转变换

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| angle | double | 旋转角度（弧度） |
|  | axis | [Vector3](../../com.aspose.threed/vector3) | 旋转轴 **Example:** |

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


链式缩放变换 **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.scale(new Vector3(10, 10, 10));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### scale(double s) {#scale-double-}
```
public TransformBuilder scale(double s)
```


链式缩放变换矩阵，其中一个分量按 s 缩放 **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.scale(10);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | double |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### scale(double x, double y, double z) {#scale-double-double-double-}
```
public TransformBuilder scale(double x, double y, double z)
```


链式缩放变换矩阵 **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.scale(10, 10, 10);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| 参数 | 类型 | 描述 |
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


设置链式组合顺序。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ComposeOrder](../../com.aspose.threed/composeorder) | 新值 |

### setMatrix(Matrix4 value) {#setMatrix-com.aspose.threed.Matrix4-}
```
public void setMatrix(Matrix4 value)
```


设置当前矩阵值

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | 新值 |

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


链式平移变换 **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.translate(new Vector3(0, 10, 0));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### translate(double tx, double ty, double tz) {#translate-double-double-double-}
```
public TransformBuilder translate(double tx, double ty, double tz)
```


链式平移变换 **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.translate(0, 10, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| 参数 | 类型 | 描述 |
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

