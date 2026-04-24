---
title: Vector4
second_title: Aspose.3D for Java API 레퍼런스
description: 네 구성 요소를 가진 벡터입니다.
type: docs
weight: 203
url: /ko/java/com.aspose.threed/vector4/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.threed.Struct, java.io.Serializable
```
public final class Vector4 implements Comparable<Vector4>, Struct<Vector4>, Serializable
```

네 구성 요소를 가진 벡터입니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Vector4(Vector3 vec, double w)](#Vector4-com.aspose.threed.Vector3-double-) | 새로운 [Vector4](../../com.aspose.threed/vector4) 구조체 인스턴스를 초기화합니다. |
| [Vector4(Vector3 vec)](#Vector4-com.aspose.threed.Vector3-) | 새로운 [Vector4](../../com.aspose.threed/vector4) 구조체 인스턴스를 초기화합니다. |
| [Vector4(FVector4 vec)](#Vector4-com.aspose.threed.FVector4-) | 새로운 [Vector4](../../com.aspose.threed/vector4) 구조체 인스턴스를 초기화합니다. |
| [Vector4(double x, double y, double z)](#Vector4-double-double-double-) | 새로운 [Vector4](../../com.aspose.threed/vector4) 구조체 인스턴스를 초기화합니다. |
| [Vector4(double x, double y, double z, double w)](#Vector4-double-double-double-double-) | 새로운 [Vector4](../../com.aspose.threed/vector4) 구조체 인스턴스를 초기화합니다. |
| [Vector4()](#Vector4--) |  |
## 필드

| 필드 | 설명 |
| --- | --- |
| [w](#w) | w 구성 요소입니다. |
| [x](#x) | x 구성 요소. |
| [y](#y) | y 구성 요소. |
| [z](#z) | z 구성 요소. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [add(Vector4 lhs, Vector4 rhs)](#add-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | 연산자 오버로드 (+) |
| [clone()](#clone--) |  |
| [compareTo(Vector4 other)](#compareTo-com.aspose.threed.Vector4-) | 현재 벡터를 다른 인스턴스와 비교합니다. |
| [copyFrom(Vector4 src)](#copyFrom-com.aspose.threed.Vector4-) |  |
| [create(Vector4 v)](#create-com.aspose.threed.Vector4-) | Vector4를 FVector4로 변환하는 명시적 변환 연산자 |
| [equals(Object obj)](#equals-java.lang.Object-) | 두 벡터가 같은지 확인 |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | 이 벡터의 해시 코드를 가져옵니다. |
| [mul(Vector4 lhs, Vector4 rhs)](#mul-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | 연산자 오버로드 (\*) |
| [mul(Vector4 lhs, double rhs)](#mul-com.aspose.threed.Vector4-double-) | 연산자 오버로드 (\*) |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [set(double newX, double newY, double newZ)](#set-double-double-double-) | 벡터의 xyz 구성 요소를 한 번에 설정합니다, w는 1로 설정됩니다. |
| [set(double newX, double newY, double newZ, double newW)](#set-double-double-double-double-) | 벡터의 모든 구성 요소를 한 번에 설정합니다. |
| [sub(Vector4 lhs, Vector4 rhs)](#sub-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | 연산자 오버로드 - (마이너스) |
| [toString()](#toString--) | 현재 [Vector4](../../com.aspose.threed/vector4)를 나타내는 java.lang.String을 반환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Vector4(Vector3 vec, double w) {#Vector4-com.aspose.threed.Vector3-double-}
```
public Vector4(Vector3 vec, double w)
```


새로운 [Vector4](../../com.aspose.threed/vector4) 구조체 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) | 벡터. |
| w | double | 너비. |

### Vector4(Vector3 vec) {#Vector4-com.aspose.threed.Vector3-}
```
public Vector4(Vector3 vec)
```


새로운 [Vector4](../../com.aspose.threed/vector4) 구조체 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) | 벡터. |

### Vector4(FVector4 vec) {#Vector4-com.aspose.threed.FVector4-}
```
public Vector4(FVector4 vec)
```


새로운 [Vector4](../../com.aspose.threed/vector4) 구조체 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| vec | [FVector4](../../com.aspose.threed/fvector4) | 벡터. |

### Vector4(double x, double y, double z) {#Vector4-double-double-double-}
```
public Vector4(double x, double y, double z)
```


새로운 [Vector4](../../com.aspose.threed/vector4) 구조체 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | double | x 좌표입니다. |
| y | double | y 좌표입니다. |
| z | double | z 좌표입니다. |

### Vector4(double x, double y, double z, double w) {#Vector4-double-double-double-double-}
```
public Vector4(double x, double y, double z, double w)
```


새로운 [Vector4](../../com.aspose.threed/vector4) 구조체 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | double | x 좌표입니다. |
| y | double | y 좌표입니다. |
| z | double | z 좌표입니다. |
| w | double | 너비. |

### Vector4() {#Vector4--}
```
public Vector4()
```


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

### add(Vector4 lhs, Vector4 rhs) {#add-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public static Vector4 add(Vector4 lhs, Vector4 rhs)
```


연산자 오버로드 (+)

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | 왼쪽 벡터 |
| rhs | [Vector4](../../com.aspose.threed/vector4) | 오른쪽 벡터 |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### clone() {#clone--}
```
public Vector4 clone()
```


현재 인스턴스를 복제합니다

**Returns:**
[Vector4](../../com.aspose.threed/vector4)
### compareTo(Vector4 other) {#compareTo-com.aspose.threed.Vector4-}
```
public int compareTo(Vector4 other)
```


현재 벡터를 다른 인스턴스와 비교합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | [Vector4](../../com.aspose.threed/vector4) |  |

**Returns:**
int
### copyFrom(Vector4 src) {#copyFrom-com.aspose.threed.Vector4-}
```
public void copyFrom(Vector4 src)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| src | [Vector4](../../com.aspose.threed/vector4) |  |

### create(Vector4 v) {#create-com.aspose.threed.Vector4-}
```
public static FVector4 create(Vector4 v)
```


Vector4를 FVector4로 변환하는 명시적 변환 연산자

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| v | [Vector4](../../com.aspose.threed/vector4) |  |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


두 벡터가 같은지 확인

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 벡터의 해시 코드를 가져옵니다.

**Returns:**
int
### mul(Vector4 lhs, Vector4 rhs) {#mul-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public static Vector4 mul(Vector4 lhs, Vector4 rhs)
```


연산자 오버로드 (\*)

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | 왼쪽 벡터 |
| rhs | [Vector4](../../com.aspose.threed/vector4) | 오른쪽 벡터 |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### mul(Vector4 lhs, double rhs) {#mul-com.aspose.threed.Vector4-double-}
```
public static Vector4 mul(Vector4 lhs, double rhs)
```


연산자 오버로드 (\*)

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | 왼쪽 벡터 |
| rhs | double | 오른쪽 double 값 |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### set(double newX, double newY, double newZ) {#set-double-double-double-}
```
public void set(double newX, double newY, double newZ)
```


벡터의 xyz 구성 요소를 한 번에 설정합니다, w는 1로 설정됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newX | double | 새 X 구성 요소. |
| newY | double | 새 Y 구성 요소. |
| newZ | double | 새 Z 구성 요소. |

### set(double newX, double newY, double newZ, double newW) {#set-double-double-double-double-}
```
public void set(double newX, double newY, double newZ, double newW)
```


벡터의 모든 구성 요소를 한 번에 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newX | double | 새 X 구성 요소. |
| newY | double | 새 Y 구성 요소. |
| newZ | double | 새 Z 구성 요소. |
| newW | double | 새 W 구성 요소. |

### sub(Vector4 lhs, Vector4 rhs) {#sub-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public static Vector4 sub(Vector4 lhs, Vector4 rhs)
```


연산자 오버로드 - (마이너스)

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | 왼쪽 벡터 |
| rhs | [Vector4](../../com.aspose.threed/vector4) | 오른쪽 벡터 |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### toString() {#toString--}
```
public String toString()
```


현재 [Vector4](../../com.aspose.threed/vector4)를 나타내는 java.lang.String을 반환합니다.

**Returns:**
java.lang.String - 현재 [Vector4](../../com.aspose.threed/vector4)를 나타내는 java.lang.String.
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

