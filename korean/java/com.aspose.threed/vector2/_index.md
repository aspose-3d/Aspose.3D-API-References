---
title: Vector2
second_title: Aspose.3D for Java API 레퍼런스
description: 두 구성 요소를 가진 벡터입니다.
type: docs
weight: 201
url: /ko/java/com.aspose.threed/vector2/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.threed.Struct, java.io.Serializable
```
public final class Vector2 implements Comparable<Vector2>, Struct<Vector2>, Serializable
```

두 구성 요소를 가진 벡터입니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Vector2(double s)](#Vector2-double-) | [Vector2](../../com.aspose.threed/vector2) 구조체의 새 인스턴스를 초기화합니다. |
| [Vector2(Vector3 s)](#Vector2-com.aspose.threed.Vector3-) | [Vector2](../../com.aspose.threed/vector2) 구조체의 새 인스턴스를 초기화합니다. |
| [Vector2(FVector2 vec)](#Vector2-com.aspose.threed.FVector2-) | [Vector2](../../com.aspose.threed/vector2) 구조체의 새 인스턴스를 초기화합니다. |
| [Vector2(double x, double y)](#Vector2-double-double-) | [Vector2](../../com.aspose.threed/vector2) 구조체의 새 인스턴스를 초기화합니다. |
| [Vector2()](#Vector2--) |  |
## 필드

| 필드 | 설명 |
| --- | --- |
| [x](#x) | x 구성 요소. |
| [y](#y) | y 구성 요소. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [add(Vector2 lhs, Vector2 rhs)](#add-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Vector2의 덧셈 연산자 |
| [clone()](#clone--) |  |
| [compareTo(Vector2 other)](#compareTo-com.aspose.threed.Vector2-) | 현재 벡터를 다른 인스턴스와 비교합니다. |
| [copyFrom(Vector2 src)](#copyFrom-com.aspose.threed.Vector2-) |  |
| [create(Vector2 v)](#create-com.aspose.threed.Vector2-) | Vector2를 FVector2로 변환하는 명시적 변환 연산자 |
| [cross(Vector2 v)](#cross-com.aspose.threed.Vector2-) | 두 벡터의 외적 |
| [div(Vector2 lhs, double rhs)](#div-com.aspose.threed.Vector2-double-) | Vector2의 나눗셈 연산자 |
| [dot(Vector2 rhs)](#dot-com.aspose.threed.Vector2-) | 두 벡터의 내적을 가져옵니다. |
| [equals(Vector2 rhs)](#equals-com.aspose.threed.Vector2-) | 두 vector2가 같은지 확인합니다 |
| [equals(Object obj)](#equals-java.lang.Object-) | 두 vector2가 같은지 확인합니다 |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | 길이를 가져옵니다. |
| [getU()](#getU--) | [Vector2](../../com.aspose.threed/vector2)가 매핑 좌표로 사용될 때 U 구성 요소를 가져옵니다. |
| [getV()](#getV--) | [Vector2](../../com.aspose.threed/vector2)가 매핑 좌표로 사용될 때 V 구성 요소를 가져옵니다. |
| [hashCode()](#hashCode--) | Vector2의 해시 코드를 가져옵니다. |
| [mul(Vector2 lhs, double rhs)](#mul-com.aspose.threed.Vector2-double-) | Vector2의 곱셈 연산자 |
| [mul(double lhs, Vector2 rhs)](#mul-double-com.aspose.threed.Vector2-) | Vector2의 곱셈 연산자 |
| [normalize()](#normalize--) | 이 인스턴스를 정규화합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(Vector2 lhs, Vector2 rhs)](#op-eq-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Vector2에 대한 등호 연산자 |
| [op_ne(Vector2 lhs, Vector2 rhs)](#op-ne-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Vector2에 대한 같지 않음 연산자 |
| [setU(double value)](#setU-double-) | 매핑 좌표로 사용되는 경우 [Vector2](../../com.aspose.threed/vector2)의 U 구성 요소를 설정합니다. |
| [setV(double value)](#setV-double-) | 매핑 좌표로 사용되는 경우 [Vector2](../../com.aspose.threed/vector2)의 V 구성 요소를 설정합니다. |
| [sub(Vector2 lhs, Vector2 rhs)](#sub-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Vector2에 대한 뺄셈 연산자 |
| [toString()](#toString--) | 현재 [Vector2](../../com.aspose.threed/vector2)를 나타내는 java.lang.String을 반환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Vector2(double s) {#Vector2-double-}
```
public Vector2(double s)
```


[Vector2](../../com.aspose.threed/vector2) 구조체의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| s | double | S. |

### Vector2(Vector3 s) {#Vector2-com.aspose.threed.Vector3-}
```
public Vector2(Vector3 s)
```


[Vector2](../../com.aspose.threed/vector2) 구조체의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| s | [Vector3](../../com.aspose.threed/vector3) | S. |

### Vector2(FVector2 vec) {#Vector2-com.aspose.threed.FVector2-}
```
public Vector2(FVector2 vec)
```


[Vector2](../../com.aspose.threed/vector2) 구조체의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| vec | [FVector2](../../com.aspose.threed/fvector2) | float 형식의 벡터. |

### Vector2(double x, double y) {#Vector2-double-double-}
```
public Vector2(double x, double y)
```


[Vector2](../../com.aspose.threed/vector2) 구조체의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | double | x 좌표입니다. |
| y | double | y 좌표입니다. |

### Vector2() {#Vector2--}
```
public Vector2()
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

### add(Vector2 lhs, Vector2 rhs) {#add-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static Vector2 add(Vector2 lhs, Vector2 rhs)
```


Vector2의 덧셈 연산자

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | 좌변 값. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | 우변 값. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of addition.
### clone() {#clone--}
```
public Vector2 clone()
```


현재 인스턴스를 복제합니다

**Returns:**
[Vector2](../../com.aspose.threed/vector2)
### compareTo(Vector2 other) {#compareTo-com.aspose.threed.Vector2-}
```
public int compareTo(Vector2 other)
```


현재 벡터를 다른 인스턴스와 비교합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
int
### copyFrom(Vector2 src) {#copyFrom-com.aspose.threed.Vector2-}
```
public void copyFrom(Vector2 src)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| src | [Vector2](../../com.aspose.threed/vector2) |  |

### create(Vector2 v) {#create-com.aspose.threed.Vector2-}
```
public static FVector2 create(Vector2 v)
```


Vector2를 FVector2로 변환하는 명시적 변환 연산자

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| v | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2)
### cross(Vector2 v) {#cross-com.aspose.threed.Vector2-}
```
public double cross(Vector2 v)
```


두 벡터의 외적

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| v | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
double
### div(Vector2 lhs, double rhs) {#div-com.aspose.threed.Vector2-double-}
```
public static Vector2 div(Vector2 lhs, double rhs)
```


Vector2의 나눗셈 연산자

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | 좌변 값. |
| rhs | double | 우변 값. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of division.
### dot(Vector2 rhs) {#dot-com.aspose.threed.Vector2-}
```
public double dot(Vector2 rhs)
```


두 벡터의 내적을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rhs | [Vector2](../../com.aspose.threed/vector2) | 우변 값. |

**Returns:**
double - 두 벡터의 내적.
### equals(Vector2 rhs) {#equals-com.aspose.threed.Vector2-}
```
public boolean equals(Vector2 rhs)
```


두 vector2가 같은지 확인합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rhs | [Vector2](../../com.aspose.threed/vector2) | 우변 값. |

**Returns:**
boolean - 모든 구성 요소가 동일하게 같은 경우 True.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


두 vector2가 같은지 확인합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 비교할 객체. |

**Returns:**
boolean - 모든 구성 요소가 동일하게 같은 경우 True.
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


길이를 가져옵니다.

**Returns:**
double - 길이.
### getU() {#getU--}
```
public double getU()
```


매핑 좌표로 사용되는 경우 [Vector2](../../com.aspose.threed/vector2)의 U 구성 요소를 가져옵니다. x 구성 요소의 별칭입니다.

**Returns:**
double - 매핑 좌표로 사용되는 경우 [Vector2](../../com.aspose.threed/vector2)의 U 구성 요소. x 구성 요소의 별칭입니다.
### getV() {#getV--}
```
public double getV()
```


매핑 좌표로 사용되는 경우 [Vector2](../../com.aspose.threed/vector2)의 V 구성 요소를 가져옵니다. y 구성 요소의 별칭입니다.

**Returns:**
double - 매핑 좌표로 사용되는 경우 [Vector2](../../com.aspose.threed/vector2)의 V 구성 요소. y 구성 요소의 별칭입니다.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Vector2의 해시 코드를 가져옵니다.

**Returns:**
int - [Vector2](../../com.aspose.threed/vector2)의 해시 코드
### mul(Vector2 lhs, double rhs) {#mul-com.aspose.threed.Vector2-double-}
```
public static Vector2 mul(Vector2 lhs, double rhs)
```


Vector2의 곱셈 연산자

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | 좌변 값. |
| rhs | double | 우변 값. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of multiply.
### mul(double lhs, Vector2 rhs) {#mul-double-com.aspose.threed.Vector2-}
```
public static Vector2 mul(double lhs, Vector2 rhs)
```


Vector2의 곱셈 연산자

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs | double | 좌변 값. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | 우변 값. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of multiply.
### normalize() {#normalize--}
```
public Vector2 normalize()
```


이 인스턴스를 정규화합니다.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - Normalized vector.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_eq(Vector2 lhs, Vector2 rhs) {#op-eq-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static boolean op_eq(Vector2 lhs, Vector2 rhs)
```


Vector2에 대한 등호 연산자

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | 좌변 값. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | 우변 값. |

**Returns:**
boolean - 모든 구성 요소가 동일하게 같은 경우 True.
### op_ne(Vector2 lhs, Vector2 rhs) {#op-ne-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static boolean op_ne(Vector2 lhs, Vector2 rhs)
```


Vector2에 대한 같지 않음 연산자

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | 좌변 값. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | 우변 값. |

**Returns:**
boolean - 두 벡터가 같지 않은 경우 True.
### setU(double value) {#setU-double-}
```
public void setU(double value)
```


매핑 좌표로 사용되는 경우 [Vector2](../../com.aspose.threed/vector2)의 U 구성 요소를 설정합니다. x 구성 요소의 별칭입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 새 값 |

### setV(double value) {#setV-double-}
```
public void setV(double value)
```


매핑 좌표로 사용되는 경우 [Vector2](../../com.aspose.threed/vector2)의 V 구성 요소를 설정합니다. y 구성 요소의 별칭입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 새 값 |

### sub(Vector2 lhs, Vector2 rhs) {#sub-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static Vector2 sub(Vector2 lhs, Vector2 rhs)
```


Vector2에 대한 뺄셈 연산자

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | 좌변 값. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | 우변 값. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of substraction.
### toString() {#toString--}
```
public String toString()
```


현재 [Vector2](../../com.aspose.threed/vector2)를 나타내는 java.lang.String을 반환합니다.

**Returns:**
java.lang.String - 현재 [Vector2](../../com.aspose.threed/vector2)를 나타내는 java.lang.String.
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

