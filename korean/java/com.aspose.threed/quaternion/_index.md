---
title: 쿼터니언
second_title: Aspose.3D for Java API 레퍼런스
description: 쿼터니언은 일반적으로 컴퓨터 그래픽에서 회전을 수행하는 데 사용됩니다.
type: docs
weight: 143
url: /ko/java/com.aspose.threed/quaternion/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class Quaternion implements Struct<Quaternion>, Serializable
```

쿼터니언은 일반적으로 컴퓨터 그래픽에서 회전을 수행하는 데 사용됩니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Quaternion(double w, double x, double y, double z)](#Quaternion-double-double-double-double-) | 새로운 [Quaternion](../../com.aspose.threed/quaternion) 클래스 인스턴스를 초기화합니다. |
| [Quaternion()](#Quaternion--) |  |
## 필드

| 필드 | 설명 |
| --- | --- |
| [IDENTITY](#IDENTITY) | 그 Identity 쿼터니언. |
| [w](#w) | w 구성 요소입니다. |
| [x](#x) | x 구성 요소. |
| [y](#y) | y 구성 요소. |
| [z](#z) | z 구성 요소. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [add(Quaternion lhs, Quaternion rhs)](#add-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | 연산자 오버로드 (+) |
| [clone()](#clone--) |  |
| [concat(Quaternion rhs)](#concat-com.aspose.threed.Quaternion-) | 두 개의 쿼터니언을 연결합니다. |
| [conjugate()](#conjugate--) | 현재 쿼터니언의 켤레 쿼터니언을 반환합니다. |
| [copyFrom(Quaternion src)](#copyFrom-com.aspose.threed.Quaternion-) |  |
| [div(Quaternion lhs, double rhs)](#div-com.aspose.threed.Quaternion-double-) | 연산자 오버로드 (/) |
| [dot(Quaternion q)](#dot-com.aspose.threed.Quaternion-) | 점곱 |
| [equals(Object obj)](#equals-java.lang.Object-) | 두 개의 쿼터니언이 같은지 확인합니다. |
| [eulerAngles()](#eulerAngles--) | 쿼터니언을 오일러 각으로 표현된 회전으로 변환합니다. 모든 구성 요소는 라디안 단위입니다. |
| [fromAngleAxis(double a, Vector3 axis)](#fromAngleAxis-double-com.aspose.threed.Vector3-) | 주어진 축을 중심으로 시계 방향으로 회전하는 쿼터니언을 생성합니다. |
| [fromEulerAngle(Vector3 eulerAngle)](#fromEulerAngle-com.aspose.threed.Vector3-) | 주어진 오일러 각에서 쿼터니언을 생성합니다. |
| [fromEulerAngle(double pitch, double yaw, double roll)](#fromEulerAngle-double-double-double-) | 주어진 오일러 각에서 쿼터니언을 생성합니다. |
| [fromRotation(Vector3 orig, Vector3 dest)](#fromRotation-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | 원래 방향에서 목표 방향으로 회전하는 쿼터니언을 생성합니다. |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | 쿼터니언의 길이를 가져옵니다. |
| [hashCode()](#hashCode--) | 쿼터니언의 해시 코드를 가져옵니다. |
| [interpolate(float t, Quaternion from, Quaternion to)](#interpolate-float-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | 주어진 쿼터니언 인수 사이에서 t가 from과 to 사이일 때 보간된 값으로 이 쿼터니언을 채웁니다. |
| [inverse()](#inverse--) | 현재 쿼터니언의 역 쿼터니언을 반환합니다. |
| [mul(Quaternion lhs, Quaternion rhs)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | 연산자 오버로드 (\*) |
| [mul(Quaternion q, Vector3 v)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector3-) | 연산자 오버로드 (\*) |
| [mul(Quaternion q, Vector4 v)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector4-) | 연산자 오버로드 (\*) |
| [mul(Quaternion lhs, double rhs)](#mul-com.aspose.threed.Quaternion-double-) | 연산자 오버로드 (\*) |
| [mul(Vector3 v, Quaternion q)](#mul-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-) | 연산자 오버로드 (\*) |
| [normalize()](#normalize--) | 쿼터니언을 정규화합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(Quaternion lhs, Quaternion rhs)](#op-eq-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | 쿼터니언에 대한 등호 연산자 |
| [op_ne(Quaternion lhs, Quaternion rhs)](#op-ne-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | 쿼터니언에 대한 부등호 연산자 |
| [slerp(double t, Quaternion v1, Quaternion v2)](#slerp-double-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | 두 값 사이에 구형 선형 보간을 수행합니다. |
| [toAngleAxis(double[] angle, Vector3 axis)](#toAngleAxis-double---com.aspose.threed.Vector3-) | 쿼터니언을 각도와 축으로 분해합니다. |
| [toMatrix()](#toMatrix--) | 쿼터니언이 나타내는 회전을 변환 행렬로 변환합니다. |
| [toMatrix(Vector3 translation)](#toMatrix-com.aspose.threed.Vector3-) | 쿼터니언이 나타내는 회전을 변환 행렬로 변환합니다. |
| [toString()](#toString--) | 쿼터니언의 문자열 표현을 가져옵니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Quaternion(double w, double x, double y, double z) {#Quaternion-double-double-double-double-}
```
public Quaternion(double w, double x, double y, double z)
```


새로운 [Quaternion](../../com.aspose.threed/quaternion) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| w | double | w component of the quaternion |
| x | double | x component of the quaternion |
| y | double | y component of the quaternion |
| z | double | z component of the quaternion |

### Quaternion() {#Quaternion--}
```
public Quaternion()
```


### IDENTITY {#IDENTITY}
```
public static final Quaternion IDENTITY
```


그 Identity 쿼터니언.

### w {#w}
```
public double w
```


w 구성 요소입니다.

### x {#x}
```
public double x
```


x 구성 요소.

### y {#y}
```
public double y
```


y 구성 요소.

### z {#z}
```
public double z
```


z 구성 요소.

### add(Quaternion lhs, Quaternion rhs) {#add-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion add(Quaternion lhs, Quaternion rhs)
```


연산자 오버로드 (+)

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Left quaternion |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Right quaternion |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### clone() {#clone--}
```
public Quaternion clone()
```


현재 인스턴스를 복제합니다

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### concat(Quaternion rhs) {#concat-com.aspose.threed.Quaternion-}
```
public Quaternion concat(Quaternion rhs)
```


두 개의 쿼터니언을 연결합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) |  |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### conjugate() {#conjugate--}
```
public Quaternion conjugate()
```


현재 쿼터니언의 켤레 쿼터니언을 반환합니다.

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - The conjugate quaternion.
### copyFrom(Quaternion src) {#copyFrom-com.aspose.threed.Quaternion-}
```
public void copyFrom(Quaternion src)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| src | [Quaternion](../../com.aspose.threed/quaternion) |  |

### div(Quaternion lhs, double rhs) {#div-com.aspose.threed.Quaternion-double-}
```
public static Quaternion div(Quaternion lhs, double rhs)
```


연산자 오버로드 (/)

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Left quaternion |
| rhs | double | Right quaternion |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### dot(Quaternion q) {#dot-com.aspose.threed.Quaternion-}
```
public double dot(Quaternion q)
```


점곱

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | The quaternion |

**Returns:**
double - Dot value
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


두 개의 쿼터니언이 같은지 확인합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 동등성을 확인할 객체. |

**Returns:**
boolean - 모든 구성 요소가 동일하게 같은 경우 True.
### eulerAngles() {#eulerAngles--}
```
public Vector3 eulerAngles()
```


쿼터니언을 오일러 각으로 표현된 회전으로 변환합니다. 모든 구성 요소는 라디안 단위입니다.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### fromAngleAxis(double a, Vector3 axis) {#fromAngleAxis-double-com.aspose.threed.Vector3-}
```
public static Quaternion fromAngleAxis(double a, Vector3 axis)
```


주어진 축을 중심으로 시계 방향으로 회전하는 쿼터니언을 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | double | Clockwise rotation in radian |
| axis | [Vector3](../../com.aspose.threed/vector3) | Axis |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromEulerAngle(Vector3 eulerAngle) {#fromEulerAngle-com.aspose.threed.Vector3-}
```
public static Quaternion fromEulerAngle(Vector3 eulerAngle)
```


주어진 오일러 각에서 쿼터니언을 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| eulerAngle | [Vector3](../../com.aspose.threed/vector3) | Euler angle in radian |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromEulerAngle(double pitch, double yaw, double roll) {#fromEulerAngle-double-double-double-}
```
public static Quaternion fromEulerAngle(double pitch, double yaw, double roll)
```


주어진 오일러 각에서 쿼터니언을 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pitch | double | Pitch in radian |
| yaw | double | Yaw in radian |
| roll | double | Roll in radian |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromRotation(Vector3 orig, Vector3 dest) {#fromRotation-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Quaternion fromRotation(Vector3 orig, Vector3 dest)
```


원래 방향에서 목표 방향으로 회전하는 쿼터니언을 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| orig | [Vector3](../../com.aspose.threed/vector3) | Original direction |
| dest | [Vector3](../../com.aspose.threed/vector3) | Destination direction |

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


쿼터니언의 길이를 가져옵니다.

**Returns:**
double - the length of the quaternion
### hashCode() {#hashCode--}
```
public int hashCode()
```


쿼터니언의 해시 코드를 가져옵니다.

**Returns:**
int - The hash code of the [Quaternion](../../com.aspose.threed/quaternion)
### interpolate(float t, Quaternion from, Quaternion to) {#interpolate-float-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion interpolate(float t, Quaternion from, Quaternion to)
```


주어진 쿼터니언 인수 사이에서 t가 from과 to 사이일 때 보간된 값으로 이 쿼터니언을 채웁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| t | float | The coefficient to interpolate. |
| from | [Quaternion](../../com.aspose.threed/quaternion) | Source quaternion. |
| to | [Quaternion](../../com.aspose.threed/quaternion) | Target quaternion. |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - The interpolated quaternion.
### inverse() {#inverse--}
```
public Quaternion inverse()
```


현재 쿼터니언의 역 쿼터니언을 반환합니다.

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Inverse quaternion.
### mul(Quaternion lhs, Quaternion rhs) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion mul(Quaternion lhs, Quaternion rhs)
```


연산자 오버로드 (\*)

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Left quaternion |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Right quaternion |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### mul(Quaternion q, Vector3 v) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector3-}
```
public static Vector3 mul(Quaternion q, Vector3 v)
```


연산자 오버로드 (\*)

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | The rotation quaternion |
| v | [Vector3](../../com.aspose.threed/vector3) | 회전할 벡터 |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Rotated vector
### mul(Quaternion q, Vector4 v) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector4-}
```
public static Vector4 mul(Quaternion q, Vector4 v)
```


연산자 오버로드 (\*)

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | The rotation quaternion |
| v | [Vector4](../../com.aspose.threed/vector4) | 회전할 벡터 |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Rotated vector
### mul(Quaternion lhs, double rhs) {#mul-com.aspose.threed.Quaternion-double-}
```
public static Quaternion mul(Quaternion lhs, double rhs)
```


연산자 오버로드 (\*)

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Left quaternion |
| rhs | double | Right quaternion |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### mul(Vector3 v, Quaternion q) {#mul-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-}
```
public static Vector3 mul(Vector3 v, Quaternion q)
```


연산자 오버로드 (\*)

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) | The rotation quaternion |
| q | [Quaternion](../../com.aspose.threed/quaternion) | 회전할 벡터 |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Rotated vector
### normalize() {#normalize--}
```
public Quaternion normalize()
```


쿼터니언을 정규화합니다.

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


쿼터니언에 대한 등호 연산자

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | 좌변 값. |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | 우변 값. |

**Returns:**
boolean - 모든 구성 요소가 동일하게 같은 경우 True.
### op_ne(Quaternion lhs, Quaternion rhs) {#op-ne-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static boolean op_ne(Quaternion lhs, Quaternion rhs)
```


쿼터니언에 대한 부등호 연산자

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | 좌변 값. |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | 우변 값. |

**Returns:**
boolean - 두 쿼터니언이 같지 않을 경우 True.
### slerp(double t, Quaternion v1, Quaternion v2) {#slerp-double-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion slerp(double t, Quaternion v1, Quaternion v2)
```


두 값 사이에 구형 선형 보간을 수행합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| t | double | t는 0에서 1 사이입니다 |
| v1 | [Quaternion](../../com.aspose.threed/quaternion) | 첫 번째 값 |
| v2 | [Quaternion](../../com.aspose.threed/quaternion) | 두 번째 값 |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### toAngleAxis(double[] angle, Vector3 axis) {#toAngleAxis-double---com.aspose.threed.Vector3-}
```
public void toAngleAxis(double[] angle, Vector3 axis)
```


쿼터니언을 각도와 축으로 분해합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| angle | double[] | 회전할 각도, 라디안 단위. |
| axis | [Vector3](../../com.aspose.threed/vector3) | 회전 축. |

### toMatrix() {#toMatrix--}
```
public Matrix4 toMatrix()
```


쿼터니언이 나타내는 회전을 변환 행렬로 변환합니다.

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - The matrix representation of current quaternion.
### toMatrix(Vector3 translation) {#toMatrix-com.aspose.threed.Vector3-}
```
public Matrix4 toMatrix(Vector3 translation)
```


쿼터니언이 나타내는 회전을 변환 행렬로 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| translation | [Vector3](../../com.aspose.threed/vector3) | 행렬의 변환 부분. |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - The matrix representation of current quaternion.
### toString() {#toString--}
```
public String toString()
```


쿼터니언의 문자열 표현을 가져옵니다.

**Returns:**
java.lang.String - 객체 문자열
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

