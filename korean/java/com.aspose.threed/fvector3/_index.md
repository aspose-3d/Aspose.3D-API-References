---
title: FVector3
second_title: Aspose.3D for Java API 레퍼런스
description: 세 개 구성 요소를 가진 float 벡터.
type: docs
weight: 60
url: /ko/java/com.aspose.threed/fvector3/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class FVector3 implements Struct<FVector3>, Serializable
```

세 개 구성 요소를 가진 float 벡터.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [FVector3(float x, float y, float z)](#FVector3-float-float-float-) | 새로운 [FVector3](../../com.aspose.threed/fvector3) 인스턴스를 초기화합니다. |
| [FVector3(Vector3 vec)](#FVector3-com.aspose.threed.Vector3-) | 새로운 [FVector3](../../com.aspose.threed/fvector3) 인스턴스를 초기화합니다. |
| [FVector3(Vector4 vec)](#FVector3-com.aspose.threed.Vector4-) | 새 인스턴스를 초기화합니다 [FVector4](../../com.aspose.threed/fvector4). |
| [FVector3()](#FVector3--) |  |
## 필드

| 필드 | 설명 |
| --- | --- |
| [x](#x) | x 구성 요소. |
| [y](#y) | y 구성 요소. |
| [z](#z) | y 구성 요소. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [add(FVector3 a, FVector3 b)](#add-com.aspose.threed.FVector3-com.aspose.threed.FVector3-) | \+ 연산자 오버로드 |
| [clone()](#clone--) |  |
| [copyFrom(FVector3 src)](#copyFrom-com.aspose.threed.FVector3-) |  |
| [create(FVector3 v)](#create-com.aspose.threed.FVector3-) | FVector3를 Vector3로 변환하는 명시적 변환 연산자 |
| [cross(FVector3 rhs)](#cross-com.aspose.threed.FVector3-) | 두 벡터의 외적 |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOne()](#getOne--) | 모든 구성 요소가 1인 단위 스케일 벡터 |
| [getZero()](#getZero--) | 제로 벡터입니다. |
| [hashCode()](#hashCode--) |  |
| [mul(FVector3 a, float b)](#mul-com.aspose.threed.FVector3-float-) | \* 연산자 오버로드 |
| [negative(FVector3 a)](#negative-com.aspose.threed.FVector3-) | \- 연산자 오버로드 |
| [normalize()](#normalize--) | 이 인스턴스를 정규화합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [sub(FVector3 a, FVector3 b)](#sub-com.aspose.threed.FVector3-com.aspose.threed.FVector3-) | \- 연산자 오버로드 |
| [toString()](#toString--) | [FVector3](../../com.aspose.threed/fvector3)를 나타내는 문자열을 반환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FVector3(float x, float y, float z) {#FVector3-float-float-float-}
```
public FVector3(float x, float y, float z)
```


새로운 [FVector3](../../com.aspose.threed/fvector3) 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 벡터의 X 구성 요소 |
| y | float | 벡터의 Y 구성 요소 |
| z | float | 벡터의 Z 구성 요소 |

### FVector3(Vector3 vec) {#FVector3-com.aspose.threed.Vector3-}
```
public FVector3(Vector3 vec)
```


새로운 [FVector3](../../com.aspose.threed/fvector3) 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) | double 타입의 Vector3 |

### FVector3(Vector4 vec) {#FVector3-com.aspose.threed.Vector4-}
```
public FVector3(Vector4 vec)
```


새 인스턴스를 초기화합니다 [FVector4](../../com.aspose.threed/fvector4).

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| vec | [Vector4](../../com.aspose.threed/vector4) | double 타입의 Vector4 |

### FVector3() {#FVector3--}
```
public FVector3()
```


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


y 구성 요소.

### add(FVector3 a, FVector3 b) {#add-com.aspose.threed.FVector3-com.aspose.threed.FVector3-}
```
public static FVector3 add(FVector3 a, FVector3 b)
```


\+ 연산자 오버로드

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | 첫 번째 벡터 |
| b | [FVector3](../../com.aspose.threed/fvector3) | 두 번째 벡터 |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### clone() {#clone--}
```
public FVector3 clone()
```


현재 인스턴스를 복제합니다

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### copyFrom(FVector3 src) {#copyFrom-com.aspose.threed.FVector3-}
```
public void copyFrom(FVector3 src)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| src | [FVector3](../../com.aspose.threed/fvector3) |  |

### create(FVector3 v) {#create-com.aspose.threed.FVector3-}
```
public static Vector3 create(FVector3 v)
```


FVector3를 Vector3로 변환하는 명시적 변환 연산자

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| v | [FVector3](../../com.aspose.threed/fvector3) | float 타입의 Vector3 |

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### cross(FVector3 rhs) {#cross-com.aspose.threed.FVector3-}
```
public FVector3 cross(FVector3 rhs)
```


두 벡터의 외적

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rhs | [FVector3](../../com.aspose.threed/fvector3) | 우변 값. |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Cross product of two [FVector3](../../com.aspose.threed/fvector3)s.
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
### getOne() {#getOne--}
```
public static FVector3 getOne()
```


모든 구성 요소가 1인 단위 스케일 벡터

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The unit scale vector with all components are all 1
### getZero() {#getZero--}
```
public static FVector3 getZero()
```


제로 벡터입니다.

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The Zero vector.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### mul(FVector3 a, float b) {#mul-com.aspose.threed.FVector3-float-}
```
public static FVector3 mul(FVector3 a, float b)
```


\* 연산자 오버로드

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | 첫 번째 벡터 |
| b | float | 두 번째 벡터 |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The product of two vectors
### negative(FVector3 a) {#negative-com.aspose.threed.FVector3-}
```
public static FVector3 negative(FVector3 a)
```


\- 연산자 오버로드

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | 입력 벡터 |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The negative vector
### normalize() {#normalize--}
```
public FVector3 normalize()
```


이 인스턴스를 정규화합니다.

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Normalized vector.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### sub(FVector3 a, FVector3 b) {#sub-com.aspose.threed.FVector3-com.aspose.threed.FVector3-}
```
public static FVector3 sub(FVector3 a, FVector3 b)
```


\- 연산자 오버로드

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | 첫 번째 벡터 |
| b | [FVector3](../../com.aspose.threed/fvector3) | 두 번째 벡터 |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The difference of two vectors
### toString() {#toString--}
```
public String toString()
```


[FVector3](../../com.aspose.threed/fvector3)를 나타내는 문자열을 반환합니다.

**Returns:**
java.lang.String - 이 벡터의 문자열 표현.
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

