---
title: TransformBuilder
second_title: Aspose.3D for Java API 레퍼런스
description: The  은 변환 행렬을 변환 체인의 연속으로 구축하는 데 사용됩니다.
type: docs
weight: 191
url: /ko/java/com.aspose.threed/transformbuilder/
---

**Inheritance:**
java.lang.Object
```
public class TransformBuilder
```

The [TransformBuilder](../../com.aspose.threed/transformbuilder) 은 변환 행렬을 변환 체인의 연속으로 구축하는 데 사용됩니다. **Example:** 다음 코드는 일련의 연산으로 행렬을 만드는 방법을 보여줍니다

```
TransformBuilder tb = new TransformBuilder();
     tb.translate(10, 20, 0);
     tb.scale(10, 10, 10);
     tb.rotateEulerDegree(90, 0, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [TransformBuilder(Matrix4 initial, ComposeOrder order)](#TransformBuilder-com.aspose.threed.Matrix4-com.aspose.threed.ComposeOrder-) | 초기 변환 행렬과 지정된 합성 순서를 사용하여 [TransformBuilder](../../com.aspose.threed/transformbuilder)를 구성합니다 |
| [TransformBuilder(ComposeOrder order)](#TransformBuilder-com.aspose.threed.ComposeOrder-) | 초기 단위 변환 행렬과 지정된 합성 순서를 사용하여 [TransformBuilder](../../com.aspose.threed/transformbuilder)를 구성합니다 |
| [TransformBuilder()](#TransformBuilder--) | 초기 단위 변환 행렬과 지정된 합성 순서를 사용하여 [TransformBuilder](../../com.aspose.threed/transformbuilder)를 구성합니다 |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [append(Matrix4 m)](#append-com.aspose.threed.Matrix4-) | 새 변환 행렬을 변환 체인에 추가합니다. |
| [compose(Matrix4 m)](#compose-com.aspose.threed.Matrix4-) | 인수를 내부 행렬에 추가하거나 앞에 삽입합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getComposeOrder()](#getComposeOrder--) | 체인의 합성 순서를 가져옵니다. |
| [getMatrix()](#getMatrix--) | 현재 행렬 값을 가져옵니다 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [prepend(Matrix4 m)](#prepend-com.aspose.threed.Matrix4-) | 새 변환 행렬을 변환 체인의 앞에 삽입합니다. |
| [rearrange(Axis newX, Axis newY, Axis newZ)](#rearrange-com.aspose.threed.Axis-com.aspose.threed.Axis-com.aspose.threed.Axis-) | 축의 레이아웃을 재배열합니다. |
| [reset()](#reset--) | 변환을 단위 행렬로 재설정합니다 |
| [rotate(Quaternion q)](#rotate-com.aspose.threed.Quaternion-) | 쿼터니언으로 회전을 연결 **Example:** |
| [rotateDegree(Vector3 rot, RotationOrder order)](#rotateDegree-com.aspose.threed.Vector3-com.aspose.threed.RotationOrder-) | 지정된 순서로 회전 추가 |
| [rotateDegree(double angle, Vector3 axis)](#rotateDegree-double-com.aspose.threed.Vector3-) | 각도 단위로 회전 변환을 연결 |
| [rotateEulerDegree(double degX, double degY, double degZ)](#rotateEulerDegree-double-double-double-) | 오일러 각도(도)로 회전을 연결 **Example:** |
| [rotateEulerRadian(Vector3 r)](#rotateEulerRadian-com.aspose.threed.Vector3-) | 오일러 각도(라디안)로 회전을 연결 **Example:** |
| [rotateEulerRadian(double x, double y, double z)](#rotateEulerRadian-double-double-double-) | 오일러 각도(라디안)로 회전을 연결 **Example:** |
| [rotateRadian(Vector3 rot, RotationOrder order)](#rotateRadian-com.aspose.threed.Vector3-com.aspose.threed.RotationOrder-) | 지정된 순서로 회전 추가 |
| [rotateRadian(double angle, Vector3 axis)](#rotateRadian-double-com.aspose.threed.Vector3-) | 라디안 단위로 회전 변환을 연결 |
| [scale(Vector3 s)](#scale-com.aspose.threed.Vector3-) | 스케일 변환을 연결 **Example:** |
| [scale(double s)](#scale-double-) | 구성 요소가 s로 스케일된 스케일 변환 행렬을 연결 **Example:** |
| [scale(double x, double y, double z)](#scale-double-double-double-) | 스케일 변환 행렬을 연결 **Example:** |
| [setComposeOrder(ComposeOrder value)](#setComposeOrder-com.aspose.threed.ComposeOrder-) | 체인 합성 순서를 설정합니다. |
| [setMatrix(Matrix4 value)](#setMatrix-com.aspose.threed.Matrix4-) | 현재 행렬 값을 설정합니다. |
| [toString()](#toString--) |  |
| [translate(Vector3 v)](#translate-com.aspose.threed.Vector3-) | 평행 이동 변환을 연결 **Example:** |
| [translate(double tx, double ty, double tz)](#translate-double-double-double-) | 평행 이동 변환을 연결 **Example:** |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TransformBuilder(Matrix4 initial, ComposeOrder order) {#TransformBuilder-com.aspose.threed.Matrix4-com.aspose.threed.ComposeOrder-}
```
public TransformBuilder(Matrix4 initial, ComposeOrder order)
```


초기 변환 행렬과 지정된 합성 순서를 사용하여 [TransformBuilder](../../com.aspose.threed/transformbuilder)를 구성합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| initial | [Matrix4](../../com.aspose.threed/matrix4) |  |
| order | [ComposeOrder](../../com.aspose.threed/composeorder) |  |

### TransformBuilder(ComposeOrder order) {#TransformBuilder-com.aspose.threed.ComposeOrder-}
```
public TransformBuilder(ComposeOrder order)
```


초기 단위 변환 행렬과 지정된 합성 순서를 사용하여 [TransformBuilder](../../com.aspose.threed/transformbuilder)를 구성합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| order | [ComposeOrder](../../com.aspose.threed/composeorder) |  |

### TransformBuilder() {#TransformBuilder--}
```
public TransformBuilder()
```


초기 단위 변환 행렬과 지정된 합성 순서를 사용하여 [TransformBuilder](../../com.aspose.threed/transformbuilder)를 구성합니다

### append(Matrix4 m) {#append-com.aspose.threed.Matrix4-}
```
public TransformBuilder append(Matrix4 m)
```


새 변환 행렬을 변환 체인에 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| m | [Matrix4](../../com.aspose.threed/matrix4) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### compose(Matrix4 m) {#compose-com.aspose.threed.Matrix4-}
```
public void compose(Matrix4 m)
```


인수를 내부 행렬에 추가하거나 앞에 삽입합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| m | [Matrix4](../../com.aspose.threed/matrix4) |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
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


체인의 합성 순서를 가져옵니다.

**Returns:**
[ComposeOrder](../../com.aspose.threed/composeorder) - the chain compose order.
### getMatrix() {#getMatrix--}
```
public Matrix4 getMatrix()
```


현재 행렬 값을 가져옵니다

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


새 변환 행렬을 변환 체인의 앞에 삽입합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| m | [Matrix4](../../com.aspose.threed/matrix4) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### rearrange(Axis newX, Axis newY, Axis newZ) {#rearrange-com.aspose.threed.Axis-com.aspose.threed.Axis-com.aspose.threed.Axis-}
```
public TransformBuilder rearrange(Axis newX, Axis newY, Axis newZ)
```


축의 레이아웃을 재배열합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newX | [Axis](../../com.aspose.threed/axis) | 새 x 구성 요소 소스 |
| newY | [Axis](../../com.aspose.threed/axis) | 새 y 구성 요소 소스 |
| newZ | [Axis](../../com.aspose.threed/axis) | 새 z 구성 요소 소스 |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### reset() {#reset--}
```
public void reset()
```


변환을 단위 행렬로 재설정합니다

### rotate(Quaternion q) {#rotate-com.aspose.threed.Quaternion-}
```
public TransformBuilder rotate(Quaternion q)
```


쿼터니언으로 회전을 연결 **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotate(Quaternion.fromEulerAngle(0, Math.PI, 0));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### rotateDegree(Vector3 rot, RotationOrder order) {#rotateDegree-com.aspose.threed.Vector3-com.aspose.threed.RotationOrder-}
```
public void rotateDegree(Vector3 rot, RotationOrder order)
```


지정된 순서로 회전 추가

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rot | [Vector3](../../com.aspose.threed/vector3) | 각도 단위 회전 |
| order | [RotationOrder](../../com.aspose.threed/rotationorder) |  |

### rotateDegree(double angle, Vector3 axis) {#rotateDegree-double-com.aspose.threed.Vector3-}
```
public TransformBuilder rotateDegree(double angle, Vector3 axis)
```


각도 단위로 회전 변환을 연결

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| angle | double | 회전할 각도(도) |
|  | axis | [Vector3](../../com.aspose.threed/vector3) | 회전 축 **Example:** |

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


오일러 각도(도)로 회전을 연결 **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotateEulerDegree(0, 90, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| 매개변수 | 형식 | 설명 |
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


오일러 각도(라디안)로 회전을 연결 **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotateEulerRadian(new Vector3(0, Math.PI, 0));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| r | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### rotateEulerRadian(double x, double y, double z) {#rotateEulerRadian-double-double-double-}
```
public TransformBuilder rotateEulerRadian(double x, double y, double z)
```


오일러 각도(라디안)로 회전을 연결 **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotateEulerRadian(0, Math.PI, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| 매개변수 | 형식 | 설명 |
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


지정된 순서로 회전 추가

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | rot | [Vector3](../../com.aspose.threed/vector3) | 라디안 단위 회전 **Example:** |

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


라디안 단위로 회전 변환을 연결

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| angle | double | 회전할 각도(라디안) |
|  | axis | [Vector3](../../com.aspose.threed/vector3) | 회전 축 **Example:** |

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


스케일 변환을 연결 **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.scale(new Vector3(10, 10, 10));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| s | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### scale(double s) {#scale-double-}
```
public TransformBuilder scale(double s)
```


구성 요소가 s로 스케일된 스케일 변환 행렬을 연결 **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.scale(10);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| s | double |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### scale(double x, double y, double z) {#scale-double-double-double-}
```
public TransformBuilder scale(double x, double y, double z)
```


스케일 변환 행렬을 연결 **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.scale(10, 10, 10);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| 매개변수 | 형식 | 설명 |
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


체인 합성 순서를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ComposeOrder](../../com.aspose.threed/composeorder) | 새 값 |

### setMatrix(Matrix4 value) {#setMatrix-com.aspose.threed.Matrix4-}
```
public void setMatrix(Matrix4 value)
```


현재 행렬 값을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | 새 값 |

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


평행 이동 변환을 연결 **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.translate(new Vector3(0, 10, 0));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### translate(double tx, double ty, double tz) {#translate-double-double-double-}
```
public TransformBuilder translate(double tx, double ty, double tz)
```


평행 이동 변환을 연결 **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.translate(0, 10, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| 매개변수 | 형식 | 설명 |
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

