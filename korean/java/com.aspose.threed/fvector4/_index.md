---
title: FVector4
second_title: Aspose.3D for Java API 레퍼런스
description: 네 개 구성 요소를 가진 float 벡터.
type: docs
weight: 61
url: /ko/java/com.aspose.threed/fvector4/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class FVector4 implements Struct<FVector4>, Serializable
```

네 개 구성 요소를 가진 float 벡터.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [FVector4(float x, float y, float z, float w)](#FVector4-float-float-float-float-) | 새 인스턴스를 초기화합니다 [FVector4](../../com.aspose.threed/fvector4). |
| [FVector4(float x, float y, float z)](#FVector4-float-float-float-) | 새 인스턴스를 초기화합니다 [FVector4](../../com.aspose.threed/fvector4). |
| [FVector4(Color color)](#FVector4-java.awt.Color-) | 새 인스턴스를 초기화합니다 [FVector4](../../com.aspose.threed/fvector4). |
| [FVector4(Vector4 vec)](#FVector4-com.aspose.threed.Vector4-) | 새 인스턴스를 초기화합니다 [FVector4](../../com.aspose.threed/fvector4). |
| [FVector4(Vector3 vec)](#FVector4-com.aspose.threed.Vector3-) | 새 인스턴스를 초기화합니다 [FVector4](../../com.aspose.threed/fvector4). |
| [FVector4(Vector3 vec, float w)](#FVector4-com.aspose.threed.Vector3-float-) | 새 인스턴스를 초기화합니다 [FVector4](../../com.aspose.threed/fvector4). |
| [FVector4()](#FVector4--) |  |
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
| [add(FVector4 lhs, FVector4 rhs)](#add-com.aspose.threed.FVector4-com.aspose.threed.FVector4-) | 연산자 오버로드 (+) |
| [clone()](#clone--) |  |
| [copyFrom(FVector4 src)](#copyFrom-com.aspose.threed.FVector4-) |  |
| [create(FVector4 v)](#create-com.aspose.threed.FVector4-) | Vector4를 FVector4로 변환하는 명시적 변환 연산자 |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [mul(FVector4 lhs, FVector4 rhs)](#mul-com.aspose.threed.FVector4-com.aspose.threed.FVector4-) | 연산자 오버로드 (\*) |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [sub(FVector4 lhs, FVector4 rhs)](#sub-com.aspose.threed.FVector4-com.aspose.threed.FVector4-) | 연산자 오버로드 - (마이너스) |
| [toString()](#toString--) | [FVector4](../../com.aspose.threed/fvector4)를 나타내는 문자열을 반환합니다 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FVector4(float x, float y, float z, float w) {#FVector4-float-float-float-float-}
```
public FVector4(float x, float y, float z, float w)
```


새 인스턴스를 초기화합니다 [FVector4](../../com.aspose.threed/fvector4).

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | X 구성 요소 |
| y | float | Y 구성 요소 |
| z | float | Z 구성 요소 |
| w | float | W 구성 요소 |

### FVector4(float x, float y, float z) {#FVector4-float-float-float-}
```
public FVector4(float x, float y, float z)
```


새 인스턴스를 초기화합니다 [FVector4](../../com.aspose.threed/fvector4).

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | X 구성 요소 |
| y | float | Y 구성 요소 |
| z | float | Z 구성 요소 |

### FVector4(Color color) {#FVector4-java.awt.Color-}
```
public FVector4(Color color)
```


새 인스턴스를 초기화합니다 [FVector4](../../com.aspose.threed/fvector4).

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 색상 | java.awt.Color |  |

### FVector4(Vector4 vec) {#FVector4-com.aspose.threed.Vector4-}
```
public FVector4(Vector4 vec)
```


새 인스턴스를 초기화합니다 [FVector4](../../com.aspose.threed/fvector4).

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| vec | [Vector4](../../com.aspose.threed/vector4) |  |

### FVector4(Vector3 vec) {#FVector4-com.aspose.threed.Vector3-}
```
public FVector4(Vector3 vec)
```


새 인스턴스를 초기화합니다 [FVector4](../../com.aspose.threed/fvector4).

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) |  |

### FVector4(Vector3 vec, float w) {#FVector4-com.aspose.threed.Vector3-float-}
```
public FVector4(Vector3 vec, float w)
```


새 인스턴스를 초기화합니다 [FVector4](../../com.aspose.threed/fvector4).

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) |  |
| w | float |  |

### FVector4() {#FVector4--}
```
public FVector4()
```


### w {#w}
```
public float w
```


w 구성 요소입니다.

### x {#x}
```
public float x
```


x 구성 요소.

### y {#y}
```
public float y
```


y 구성 요소.

### z {#z}
```
public float z
```


z 구성 요소.

### add(FVector4 lhs, FVector4 rhs) {#add-com.aspose.threed.FVector4-com.aspose.threed.FVector4-}
```
public static FVector4 add(FVector4 lhs, FVector4 rhs)
```


연산자 오버로드 (+)

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs | [FVector4](../../com.aspose.threed/fvector4) | 왼쪽 벡터 |
| rhs | [FVector4](../../com.aspose.threed/fvector4) | 오른쪽 벡터 |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4) - Result vector
### clone() {#clone--}
```
public FVector4 clone()
```


현재 인스턴스를 복제합니다

**Returns:**
[FVector4](../../com.aspose.threed/fvector4)
### copyFrom(FVector4 src) {#copyFrom-com.aspose.threed.FVector4-}
```
public void copyFrom(FVector4 src)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| src | [FVector4](../../com.aspose.threed/fvector4) |  |

### create(FVector4 v) {#create-com.aspose.threed.FVector4-}
```
public static Vector4 create(FVector4 v)
```


Vector4를 FVector4로 변환하는 명시적 변환 연산자

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| v | [FVector4](../../com.aspose.threed/fvector4) |  |

**Returns:**
[Vector4](../../com.aspose.threed/vector4)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




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




**Returns:**
int
### mul(FVector4 lhs, FVector4 rhs) {#mul-com.aspose.threed.FVector4-com.aspose.threed.FVector4-}
```
public static FVector4 mul(FVector4 lhs, FVector4 rhs)
```


연산자 오버로드 (\*)

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs | [FVector4](../../com.aspose.threed/fvector4) | 왼쪽 벡터 |
| rhs | [FVector4](../../com.aspose.threed/fvector4) | 오른쪽 벡터 |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4) - Result vector
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### sub(FVector4 lhs, FVector4 rhs) {#sub-com.aspose.threed.FVector4-com.aspose.threed.FVector4-}
```
public static FVector4 sub(FVector4 lhs, FVector4 rhs)
```


연산자 오버로드 - (마이너스)

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs | [FVector4](../../com.aspose.threed/fvector4) | 왼쪽 벡터 |
| rhs | [FVector4](../../com.aspose.threed/fvector4) | 오른쪽 벡터 |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4) - Result vector
### toString() {#toString--}
```
public String toString()
```


[FVector4](../../com.aspose.threed/fvector4)를 나타내는 문자열을 반환합니다

**Returns:**
java.lang.String - 현재 벡터의 문자열 표현입니다.
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

