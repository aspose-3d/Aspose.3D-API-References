---
title: Vector3
second_title: Aspose.3D for Java API 레퍼런스
description: 세 구성 요소를 가진 벡터입니다.
type: docs
weight: 202
url: /ko/java/com.aspose.threed/vector3/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.threed.Struct, java.io.Serializable
```
public final class Vector3 implements Comparable<Vector3>, Struct<Vector3>, Serializable
```

세 구성 요소를 가진 벡터입니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Vector3(double x, double y, double z)](#Vector3-double-double-double-) | [Vector3](../../com.aspose.threed/vector3) 구조체의 새 인스턴스를 초기화합니다. |
| [Vector3(FVector3 vec)](#Vector3-com.aspose.threed.FVector3-) | [Vector3](../../com.aspose.threed/vector3) 구조체의 새 인스턴스를 초기화합니다. |
| [Vector3(double v)](#Vector3-double-) | [Vector3](../../com.aspose.threed/vector3) 구조체의 새 인스턴스를 초기화합니다. |
| [Vector3(Vector4 vec4)](#Vector3-com.aspose.threed.Vector4-) | [Vector3](../../com.aspose.threed/vector3) 구조체의 새 인스턴스를 초기화합니다. |
| [Vector3()](#Vector3--) |  |
## 필드

| 필드 | 설명 |
| --- | --- |
| [x](#x) | x 구성 요소. |
| [y](#y) | y 구성 요소. |
| [z](#z) | z 구성 요소. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [add(Vector3 lhs, Vector3 rhs)](#add-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | 연산자 오버로드 (+) |
| [angleBetween(Vector3 dir)](#angleBetween-com.aspose.threed.Vector3-) | 두 방향 사이의 내부 각도를 계산합니다. 두 방향은 정규화되지 않은 벡터일 수 있습니다. |
| [angleBetween(Vector3 dir, Vector3 up)](#angleBetween-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | 두 방향 사이의 내부 각도를 계산합니다. 두 방향은 정규화되지 않은 벡터일 수 있습니다. |
| [clone()](#clone--) |  |
| [compareTo(Vector3 other)](#compareTo-com.aspose.threed.Vector3-) | 현재 벡터를 다른 인스턴스와 비교합니다. |
| [copyFrom(Vector3 src)](#copyFrom-com.aspose.threed.Vector3-) |  |
| [cos()](#cos--) | 각 구성 요소에 대한 코사인을 계산합니다. |
| [create(Vector3 v)](#create-com.aspose.threed.Vector3-) | Vector3를 FVector3로 변환하는 명시적 변환 연산자 |
| [cross(Vector3 rhs)](#cross-com.aspose.threed.Vector3-) | 두 벡터의 외적 |
| [div(Vector3 lhs, Vector3 rhs)](#div-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | 연산자 오버로드 (/) |
| [div(Vector3 lhs, double rhs)](#div-com.aspose.threed.Vector3-double-) | 연산자 오버로드 (/) |
| [dot(Vector3 rhs)](#dot-com.aspose.threed.Vector3-) | 두 벡터의 내적을 가져옵니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 두 vector3가 같은지 확인합니다. |
| [get(int idx)](#get-int-) | 인덱스로 벡터의 구성 요소를 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | 이 벡터의 길이를 가져옵니다. |
| [getLength2()](#getLength2--) | 길이의 제곱을 가져옵니다. |
| [getOne()](#getOne--) | 단위 벡터 (1, 1, 1)를 가져옵니다. |
| [getUnitX()](#getUnitX--) | 단위 벡터 (1, 0, 0)를 가져옵니다. |
| [getUnitY()](#getUnitY--) | 단위 벡터 (0, 1, 0)를 가져옵니다. |
| [getUnitZ()](#getUnitZ--) | 단위 벡터 (0, 0, 1)를 가져옵니다. |
| [getZero()](#getZero--) | 단위 벡터 (0, 0, 0)를 가져옵니다. |
| [hashCode()](#hashCode--) | Vector3의 해시 코드를 가져옵니다. |
| [mul(Vector3 lhs, Vector3 rhs)](#mul-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | 연산자 오버로드 (\*) |
| [mul(Vector3 lhs, double rhs)](#mul-com.aspose.threed.Vector3-double-) | 연산자 오버로드 (\*) |
| [mul(double lhs, Vector3 rhs)](#mul-double-com.aspose.threed.Vector3-) | 연산자 오버로드 (\*) |
| [negative(Vector3 v)](#negative-com.aspose.threed.Vector3-) | 연산자 오버로드 - |
| [normalize()](#normalize--) | 이 인스턴스를 정규화합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(Vector3 lhs, Vector3 rhs)](#op-eq-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Vector3에 대한 동등 연산자 |
| [op_ne(Vector3 lhs, Vector3 rhs)](#op-ne-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Vector3에 대한 부등 연산자 |
| [set(double newX, double newY, double newZ)](#set-double-double-double-) | 한 번의 호출로 x/y/z 구성 요소를 설정합니다. |
| [set(int idx, double value)](#set-int-double-) | 인덱스로 벡터의 구성 요소를 설정합니다. |
| [sin()](#sin--) | 각 구성 요소에 대한 사인을 계산합니다. |
| [sub(Vector3 lhs, Vector3 rhs)](#sub-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | 연산자 오버로드 - (마이너스) |
| [toString()](#toString--) | 현재 [Vector3](../../com.aspose.threed/vector3)를 나타내는 java.lang.String을 반환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Vector3(double x, double y, double z) {#Vector3-double-double-double-}
```
public Vector3(double x, double y, double z)
```


[Vector3](../../com.aspose.threed/vector3) 구조체의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | double | x 좌표입니다. |
| y | double | y 좌표입니다. |
| z | double | z 좌표입니다. |

### Vector3(FVector3 vec) {#Vector3-com.aspose.threed.FVector3-}
```
public Vector3(FVector3 vec)
```


[Vector3](../../com.aspose.threed/vector3) 구조체의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| vec | [FVector3](../../com.aspose.threed/fvector3) | x 좌표입니다. |

### Vector3(double v) {#Vector3-double-}
```
public Vector3(double v)
```


[Vector3](../../com.aspose.threed/vector3) 구조체의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| v | double | V. |

### Vector3(Vector4 vec4) {#Vector3-com.aspose.threed.Vector4-}
```
public Vector3(Vector4 vec4)
```


[Vector3](../../com.aspose.threed/vector3) 구조체의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| vec4 | [Vector4](../../com.aspose.threed/vector4) | Vec4. |

### Vector3() {#Vector3--}
```
public Vector3()
```


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

### add(Vector3 lhs, Vector3 rhs) {#add-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 add(Vector3 lhs, Vector3 rhs)
```


연산자 오버로드 (+)

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | 왼쪽 벡터 |
| rhs | [Vector3](../../com.aspose.threed/vector3) | 오른쪽 벡터 |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### angleBetween(Vector3 dir) {#angleBetween-com.aspose.threed.Vector3-}
```
public double angleBetween(Vector3 dir)
```


두 방향 사이의 내부 각도를 계산합니다. 두 방향은 정규화되지 않은 벡터일 수 있습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dir | [Vector3](../../com.aspose.threed/vector3) | 비교할 방향 벡터 |

**Returns:**
double - 내부 각도(라디안)
### angleBetween(Vector3 dir, Vector3 up) {#angleBetween-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public double angleBetween(Vector3 dir, Vector3 up)
```


두 방향 사이의 내부 각도를 계산합니다. 두 방향은 정규화되지 않은 벡터일 수 있습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dir | [Vector3](../../com.aspose.threed/vector3) | 비교할 방향 벡터 |
| up | [Vector3](../../com.aspose.threed/vector3) | 두 방향이 공유하는 평면의 위쪽 벡터 |

**Returns:**
double - 내부 각도(라디안)
### clone() {#clone--}
```
public Vector3 clone()
```


현재 인스턴스를 복제합니다

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### compareTo(Vector3 other) {#compareTo-com.aspose.threed.Vector3-}
```
public int compareTo(Vector3 other)
```


현재 벡터를 다른 인스턴스와 비교합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
int
### copyFrom(Vector3 src) {#copyFrom-com.aspose.threed.Vector3-}
```
public void copyFrom(Vector3 src)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| src | [Vector3](../../com.aspose.threed/vector3) |  |

### cos() {#cos--}
```
public Vector3 cos()
```


각 구성 요소에 대한 코사인을 계산합니다.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Calculated [Vector3](../../com.aspose.threed/vector3).
### create(Vector3 v) {#create-com.aspose.threed.Vector3-}
```
public static FVector3 create(Vector3 v)
```


Vector3를 FVector3로 변환하는 명시적 변환 연산자

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### cross(Vector3 rhs) {#cross-com.aspose.threed.Vector3-}
```
public Vector3 cross(Vector3 rhs)
```


두 벡터의 외적

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rhs | [Vector3](../../com.aspose.threed/vector3) | 우변 값. |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Cross product of two [Vector3](../../com.aspose.threed/vector3)s.
### div(Vector3 lhs, Vector3 rhs) {#div-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 div(Vector3 lhs, Vector3 rhs)
```


연산자 오버로드 (/)

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | 왼쪽 벡터 |
| rhs | [Vector3](../../com.aspose.threed/vector3) | 오른쪽 벡터 |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### div(Vector3 lhs, double rhs) {#div-com.aspose.threed.Vector3-double-}
```
public static Vector3 div(Vector3 lhs, double rhs)
```


연산자 오버로드 (/)

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | 왼쪽 벡터 |
| rhs | double | 오른쪽 double 값 |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### dot(Vector3 rhs) {#dot-com.aspose.threed.Vector3-}
```
public double dot(Vector3 rhs)
```


두 벡터의 내적을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rhs | [Vector3](../../com.aspose.threed/vector3) | 우변 값. |

**Returns:**
double - 두 벡터의 내적.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


두 vector3가 같은지 확인합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 동등성을 확인할 객체. |

**Returns:**
boolean - 모든 구성 요소가 동일하게 같은 경우 True.
### get(int idx) {#get-int-}
```
public double get(int idx)
```


인덱스로 벡터의 구성 요소를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| idx | int |  |

**Returns:**
double - 인덱스로 지정한 벡터의 구성 요소.
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


이 벡터의 길이를 가져옵니다.

**Returns:**
double - 이 벡터의 길이.
### getLength2() {#getLength2--}
```
public double getLength2()
```


길이의 제곱을 가져옵니다.

**Returns:**
double - 길이의 제곱.
### getOne() {#getOne--}
```
public static Vector3 getOne()
```


단위 벡터 (1, 1, 1)를 가져옵니다.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (1, 1, 1)
### getUnitX() {#getUnitX--}
```
public static Vector3 getUnitX()
```


단위 벡터 (1, 0, 0)를 가져옵니다.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (1, 0, 0)
### getUnitY() {#getUnitY--}
```
public static Vector3 getUnitY()
```


단위 벡터 (0, 1, 0)를 가져옵니다.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (0, 1, 0)
### getUnitZ() {#getUnitZ--}
```
public static Vector3 getUnitZ()
```


단위 벡터 (0, 0, 1)를 가져옵니다.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (0, 0, 1)
### getZero() {#getZero--}
```
public static Vector3 getZero()
```


단위 벡터 (0, 0, 0)를 가져옵니다.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (0, 0, 0)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Vector3의 해시 코드를 가져옵니다.

**Returns:**
int - [Vector3](../../com.aspose.threed/vector3)의 해시 코드.
### mul(Vector3 lhs, Vector3 rhs) {#mul-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 mul(Vector3 lhs, Vector3 rhs)
```


연산자 오버로드 (\*)

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | 왼쪽 벡터 |
| rhs | [Vector3](../../com.aspose.threed/vector3) | 오른쪽 벡터 |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### mul(Vector3 lhs, double rhs) {#mul-com.aspose.threed.Vector3-double-}
```
public static Vector3 mul(Vector3 lhs, double rhs)
```


연산자 오버로드 (\*)

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | 왼쪽 벡터 |
| rhs | double | 오른쪽 double 값 |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### mul(double lhs, Vector3 rhs) {#mul-double-com.aspose.threed.Vector3-}
```
public static Vector3 mul(double lhs, Vector3 rhs)
```


연산자 오버로드 (\*)

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs | double | 왼쪽 스칼라 |
| rhs | [Vector3](../../com.aspose.threed/vector3) | 오른쪽 벡터 |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### negative(Vector3 v) {#negative-com.aspose.threed.Vector3-}
```
public static Vector3 negative(Vector3 v)
```


연산자 오버로드 -

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) | 원점 벡터 |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### normalize() {#normalize--}
```
public Vector3 normalize()
```


이 인스턴스를 정규화합니다.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Normalized vector.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_eq(Vector3 lhs, Vector3 rhs) {#op-eq-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static boolean op_eq(Vector3 lhs, Vector3 rhs)
```


Vector3에 대한 동등 연산자

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | 좌변 값. |
| rhs | [Vector3](../../com.aspose.threed/vector3) | 우변 값. |

**Returns:**
boolean - 모든 구성 요소가 동일하게 같은 경우 True.
### op_ne(Vector3 lhs, Vector3 rhs) {#op-ne-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static boolean op_ne(Vector3 lhs, Vector3 rhs)
```


Vector3에 대한 부등 연산자

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | 좌변 값. |
| rhs | [Vector3](../../com.aspose.threed/vector3) | 우변 값. |

**Returns:**
boolean - 두 벡터가 같지 않은 경우 True.
### set(double newX, double newY, double newZ) {#set-double-double-double-}
```
public void set(double newX, double newY, double newZ)
```


한 번의 호출로 x/y/z 구성 요소를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newX | double | x 구성 요소. |
| newY | double | y 구성 요소. |
| newZ | double | z 구성 요소. |

### set(int idx, double value) {#set-int-double-}
```
public void set(int idx, double value)
```


인덱스로 벡터의 구성 요소를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| idx | int |  |
| 값 | double | 새 값 |

### sin() {#sin--}
```
public Vector3 sin()
```


각 구성 요소에 대한 사인을 계산합니다.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Calculated [Vector3](../../com.aspose.threed/vector3).
### sub(Vector3 lhs, Vector3 rhs) {#sub-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 sub(Vector3 lhs, Vector3 rhs)
```


연산자 오버로드 - (마이너스)

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | 왼쪽 벡터 |
| rhs | [Vector3](../../com.aspose.threed/vector3) | 오른쪽 벡터 |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### toString() {#toString--}
```
public String toString()
```


현재 [Vector3](../../com.aspose.threed/vector3)를 나타내는 java.lang.String을 반환합니다.

**Returns:**
java.lang.String - 현재 [Vector3](../../com.aspose.threed/vector3)를 나타내는 java.lang.String.
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

