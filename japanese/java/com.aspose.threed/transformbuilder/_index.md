---
title: TransformBuilder
second_title: Aspose.3D for Java API リファレンス
description: 変換行列を変換チェーンで構築するために使用されます。
type: docs
weight: 191
url: /ja/java/com.aspose.threed/transformbuilder/
---

**Inheritance:**
java.lang.Object
```
public class TransformBuilder
```

The [TransformBuilder](../../com.aspose.threed/transformbuilder) は、変換のチェーンによって変換行列を構築するために使用されます。 **Example:** 以下のコードは、一連の操作で行列を作成する方法を示しています

```
TransformBuilder tb = new TransformBuilder();
     tb.translate(10, 20, 0);
     tb.scale(10, 10, 10);
     tb.rotateEulerDegree(90, 0, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```
## Constructors

| Constructor | 説明 |
| --- | --- |
| [TransformBuilder(Matrix4 initial, ComposeOrder order)](#TransformBuilder-com.aspose.threed.Matrix4-com.aspose.threed.ComposeOrder-) | 初期変換行列と指定された合成順序で [TransformBuilder](../../com.aspose.threed/transformbuilder) を構築します |
| [TransformBuilder(ComposeOrder order)](#TransformBuilder-com.aspose.threed.ComposeOrder-) | 初期の単位変換行列と指定された合成順序で [TransformBuilder](../../com.aspose.threed/transformbuilder) を構築します |
| [TransformBuilder()](#TransformBuilder--) | 初期の単位変換行列と指定された合成順序で [TransformBuilder](../../com.aspose.threed/transformbuilder) を構築します |
## Methods

| Method | 説明 |
| --- | --- |
| [append(Matrix4 m)](#append-com.aspose.threed.Matrix4-) | 新しい変換行列を変換チェーンに追加します。 |
| [compose(Matrix4 m)](#compose-com.aspose.threed.Matrix4-) | 引数を内部行列に追加または前置します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getComposeOrder()](#getComposeOrder--) | チェーンの合成順序を取得します。 |
| [getMatrix()](#getMatrix--) | 現在の行列値を取得します |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [prepend(Matrix4 m)](#prepend-com.aspose.threed.Matrix4-) | 新しい変換行列を変換チェーンの先頭に追加します。 |
| [rearrange(Axis newX, Axis newY, Axis newZ)](#rearrange-com.aspose.threed.Axis-com.aspose.threed.Axis-com.aspose.threed.Axis-) | 軸のレイアウトを再配置します。 |
| [reset()](#reset--) | 変換を単位行列にリセットします |
| [rotate(Quaternion q)](#rotate-com.aspose.threed.Quaternion-) | クォータニオンによる回転をチェーンする **Example:** |
| [rotateDegree(Vector3 rot, RotationOrder order)](#rotateDegree-com.aspose.threed.Vector3-com.aspose.threed.RotationOrder-) | 指定された順序で回転を追加する |
| [rotateDegree(double angle, Vector3 axis)](#rotateDegree-double-com.aspose.threed.Vector3-) | 度単位で回転変換をチェーンする |
| [rotateEulerDegree(double degX, double degY, double degZ)](#rotateEulerDegree-double-double-double-) | 度単位のオイラー角で回転をチェーンする **Example:** |
| [rotateEulerRadian(Vector3 r)](#rotateEulerRadian-com.aspose.threed.Vector3-) | ラジアン単位のオイラー角で回転をチェーンする **Example:** |
| [rotateEulerRadian(double x, double y, double z)](#rotateEulerRadian-double-double-double-) | ラジアン単位のオイラー角で回転をチェーンする **Example:** |
| [rotateRadian(Vector3 rot, RotationOrder order)](#rotateRadian-com.aspose.threed.Vector3-com.aspose.threed.RotationOrder-) | 指定された順序で回転を追加する |
| [rotateRadian(double angle, Vector3 axis)](#rotateRadian-double-com.aspose.threed.Vector3-) | ラジアン単位で回転変換をチェーンする |
| [scale(Vector3 s)](#scale-com.aspose.threed.Vector3-) | スケール変換をチェーンする **Example:** |
| [scale(double s)](#scale-double-) | コンポーネントが s でスケーリングされたスケーリング変換行列をチェーンする **Example:** |
| [scale(double x, double y, double z)](#scale-double-double-double-) | スケーリング変換行列をチェーンする **Example:** |
| [setComposeOrder(ComposeOrder value)](#setComposeOrder-com.aspose.threed.ComposeOrder-) | チェーンの合成順序を設定します。 |
| [setMatrix(Matrix4 value)](#setMatrix-com.aspose.threed.Matrix4-) | 現在の行列値を設定します |
| [toString()](#toString--) |  |
| [translate(Vector3 v)](#translate-com.aspose.threed.Vector3-) | 平行移動変換をチェーンする **Example:** |
| [translate(double tx, double ty, double tz)](#translate-double-double-double-) | 平行移動変換をチェーンする **Example:** |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TransformBuilder(Matrix4 initial, ComposeOrder order) {#TransformBuilder-com.aspose.threed.Matrix4-com.aspose.threed.ComposeOrder-}
```
public TransformBuilder(Matrix4 initial, ComposeOrder order)
```


初期変換行列と指定された合成順序で [TransformBuilder](../../com.aspose.threed/transformbuilder) を構築します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| initial | [Matrix4](../../com.aspose.threed/matrix4) |  |
| order | [ComposeOrder](../../com.aspose.threed/composeorder) |  |

### TransformBuilder(ComposeOrder order) {#TransformBuilder-com.aspose.threed.ComposeOrder-}
```
public TransformBuilder(ComposeOrder order)
```


初期の単位変換行列と指定された合成順序で [TransformBuilder](../../com.aspose.threed/transformbuilder) を構築します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| order | [ComposeOrder](../../com.aspose.threed/composeorder) |  |

### TransformBuilder() {#TransformBuilder--}
```
public TransformBuilder()
```


初期の単位変換行列と指定された合成順序で [TransformBuilder](../../com.aspose.threed/transformbuilder) を構築します

### append(Matrix4 m) {#append-com.aspose.threed.Matrix4-}
```
public TransformBuilder append(Matrix4 m)
```


新しい変換行列を変換チェーンに追加します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| m | [Matrix4](../../com.aspose.threed/matrix4) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### compose(Matrix4 m) {#compose-com.aspose.threed.Matrix4-}
```
public void compose(Matrix4 m)
```


引数を内部行列に追加または前置します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| m | [Matrix4](../../com.aspose.threed/matrix4) |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 説明 |
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


チェーンの合成順序を取得します。

**Returns:**
[ComposeOrder](../../com.aspose.threed/composeorder) - the chain compose order.
### getMatrix() {#getMatrix--}
```
public Matrix4 getMatrix()
```


現在の行列値を取得します

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


新しい変換行列を変換チェーンの先頭に追加します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| m | [Matrix4](../../com.aspose.threed/matrix4) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### rearrange(Axis newX, Axis newY, Axis newZ) {#rearrange-com.aspose.threed.Axis-com.aspose.threed.Axis-com.aspose.threed.Axis-}
```
public TransformBuilder rearrange(Axis newX, Axis newY, Axis newZ)
```


軸のレイアウトを再配置します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| newX | [Axis](../../com.aspose.threed/axis) | 新しい x 成分のソース |
| newY | [Axis](../../com.aspose.threed/axis) | 新しい y 成分のソース |
| newZ | [Axis](../../com.aspose.threed/axis) | 新しい z 成分のソース |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### reset() {#reset--}
```
public void reset()
```


変換を単位行列にリセットします

### rotate(Quaternion q) {#rotate-com.aspose.threed.Quaternion-}
```
public TransformBuilder rotate(Quaternion q)
```


クォータニオンによる回転をチェーンする **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotate(Quaternion.fromEulerAngle(0, Math.PI, 0));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### rotateDegree(Vector3 rot, RotationOrder order) {#rotateDegree-com.aspose.threed.Vector3-com.aspose.threed.RotationOrder-}
```
public void rotateDegree(Vector3 rot, RotationOrder order)
```


指定された順序で回転を追加する

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| rot | [Vector3](../../com.aspose.threed/vector3) | 度単位の回転 |
| order | [RotationOrder](../../com.aspose.threed/rotationorder) |  |

### rotateDegree(double angle, Vector3 axis) {#rotateDegree-double-com.aspose.threed.Vector3-}
```
public TransformBuilder rotateDegree(double angle, Vector3 axis)
```


度単位で回転変換をチェーンする

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| angle | double | 回転させる角度（度） |
|  | axis | [Vector3](../../com.aspose.threed/vector3) | 回転軸 **Example:** |

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


度単位のオイラー角で回転をチェーンする **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotateEulerDegree(0, 90, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parameter | Type | 説明 |
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


ラジアン単位のオイラー角で回転をチェーンする **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotateEulerRadian(new Vector3(0, Math.PI, 0));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| r | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### rotateEulerRadian(double x, double y, double z) {#rotateEulerRadian-double-double-double-}
```
public TransformBuilder rotateEulerRadian(double x, double y, double z)
```


ラジアン単位のオイラー角で回転をチェーンする **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotateEulerRadian(0, Math.PI, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parameter | Type | 説明 |
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


指定された順序で回転を追加する

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
|  | rot | [Vector3](../../com.aspose.threed/vector3) | ラジアン単位の回転 **Example:** |

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


ラジアン単位で回転変換をチェーンする

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| angle | double | 回転させる角度（ラジアン） |
|  | axis | [Vector3](../../com.aspose.threed/vector3) | 回転軸 **Example:** |

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


スケール変換をチェーンする **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.scale(new Vector3(10, 10, 10));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| s | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### scale(double s) {#scale-double-}
```
public TransformBuilder scale(double s)
```


コンポーネントが s でスケーリングされたスケーリング変換行列をチェーンする **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.scale(10);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| s | double |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### scale(double x, double y, double z) {#scale-double-double-double-}
```
public TransformBuilder scale(double x, double y, double z)
```


スケーリング変換行列をチェーンする **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.scale(10, 10, 10);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parameter | Type | 説明 |
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


チェーンの合成順序を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [ComposeOrder](../../com.aspose.threed/composeorder) | 新しい値 |

### setMatrix(Matrix4 value) {#setMatrix-com.aspose.threed.Matrix4-}
```
public void setMatrix(Matrix4 value)
```


現在の行列値を設定します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | 新しい値 |

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


平行移動変換をチェーンする **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.translate(new Vector3(0, 10, 0));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### translate(double tx, double ty, double tz) {#translate-double-double-double-}
```
public TransformBuilder translate(double tx, double ty, double tz)
```


平行移動変換をチェーンする **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.translate(0, 10, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parameter | Type | 説明 |
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
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

