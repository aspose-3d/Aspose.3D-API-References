---
title: FVector2
second_title: Aspose.3D for Java API 레퍼런스
description: 두 개 구성 요소를 가진 float 벡터.
type: docs
weight: 59
url: /ko/java/com.aspose.threed/fvector2/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class FVector2 implements Struct<FVector2>, Serializable
```

두 개 구성 요소를 가진 float 벡터.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [FVector2(float x, float y)](#FVector2-float-float-) | [FVector2](../../com.aspose.threed/fvector2)의 새 인스턴스를 초기화합니다. |
| [FVector2(Vector2 vec)](#FVector2-com.aspose.threed.Vector2-) | [FVector2](../../com.aspose.threed/fvector2)의 새 인스턴스를 초기화합니다. |
| [FVector2()](#FVector2--) |  |
## 필드

| 필드 | 설명 |
| --- | --- |
| [x](#x) | x 구성 요소. |
| [y](#y) | y 구성 요소. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [add(FVector2 a, FVector2 b)](#add-com.aspose.threed.FVector2-com.aspose.threed.FVector2-) | \+ 연산자 오버로드 |
| [clone()](#clone--) |  |
| [copyFrom(FVector2 src)](#copyFrom-com.aspose.threed.FVector2-) |  |
| [create(FVector2 v)](#create-com.aspose.threed.FVector2-) | FVector2를 Vector2로 변환하는 명시적 변환 연산자 |
| [equals(FVector2 rhs)](#equals-com.aspose.threed.FVector2-) | 두 벡터가 같은지 확인 |
| [equals(Object obj)](#equals-java.lang.Object-) | 두 벡터가 같은지 확인 |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | 이 인스턴스의 해시 코드를 가져옵니다 |
| [mul(FVector2 a, float b)](#mul-com.aspose.threed.FVector2-float-) | \* 연산자 오버로드 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(FVector2 a, FVector2 b)](#op-eq-com.aspose.threed.FVector2-com.aspose.threed.FVector2-) | == 연산자 오버로드 |
| [op_ne(FVector2 a, FVector2 b)](#op-ne-com.aspose.threed.FVector2-com.aspose.threed.FVector2-) | != 연산자 오버로드 |
| [sub(FVector2 a, FVector2 b)](#sub-com.aspose.threed.FVector2-com.aspose.threed.FVector2-) | \- 연산자 오버로드 |
| [toString()](#toString--) | [FVector2](../../com.aspose.threed/fvector2)를 나타내는 문자열을 반환합니다 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FVector2(float x, float y) {#FVector2-float-float-}
```
public FVector2(float x, float y)
```


[FVector2](../../com.aspose.threed/fvector2)의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 벡터의 X 구성 요소 |
| y | float | 벡터의 Y 구성 요소 |

### FVector2(Vector2 vec) {#FVector2-com.aspose.threed.Vector2-}
```
public FVector2(Vector2 vec)
```


[FVector2](../../com.aspose.threed/fvector2)의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| vec | [Vector2](../../com.aspose.threed/vector2) | double 형식의 Vector2 |

### FVector2() {#FVector2--}
```
public FVector2()
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

### add(FVector2 a, FVector2 b) {#add-com.aspose.threed.FVector2-com.aspose.threed.FVector2-}
```
public static FVector2 add(FVector2 a, FVector2 b)
```


\+ 연산자 오버로드

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | 첫 번째 벡터 |
| b | [FVector2](../../com.aspose.threed/fvector2) | 두 번째 벡터 |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - The sum of two vectors.
### clone() {#clone--}
```
public FVector2 clone()
```


현재 인스턴스를 복제합니다

**Returns:**
[FVector2](../../com.aspose.threed/fvector2)
### copyFrom(FVector2 src) {#copyFrom-com.aspose.threed.FVector2-}
```
public void copyFrom(FVector2 src)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| src | [FVector2](../../com.aspose.threed/fvector2) |  |

### create(FVector2 v) {#create-com.aspose.threed.FVector2-}
```
public static Vector2 create(FVector2 v)
```


FVector2를 Vector2로 변환하는 명시적 변환 연산자

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| v | [FVector2](../../com.aspose.threed/fvector2) | float 형식의 Vector 2. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2)
### equals(FVector2 rhs) {#equals-com.aspose.threed.FVector2-}
```
public boolean equals(FVector2 rhs)
```


두 벡터가 같은지 확인

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rhs | [FVector2](../../com.aspose.threed/fvector2) |  |

**Returns:**
boolean - 모든 구성 요소가 같으면 True.
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
boolean - 입력이 벡터이고 모든 구성 요소가 같으면 True.
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


이 인스턴스의 해시 코드를 가져옵니다

**Returns:**
int - 벡터의 해시 코드.
### mul(FVector2 a, float b) {#mul-com.aspose.threed.FVector2-float-}
```
public static FVector2 mul(FVector2 a, float b)
```


\* 연산자 오버로드

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | 첫 번째 벡터 |
| b | float | 두 번째 벡터 |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - The product of two vectors.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_eq(FVector2 a, FVector2 b) {#op-eq-com.aspose.threed.FVector2-com.aspose.threed.FVector2-}
```
public static boolean op_eq(FVector2 a, FVector2 b)
```


== 연산자 오버로드

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | 첫 번째 벡터 |
| b | [FVector2](../../com.aspose.threed/fvector2) | 두 번째 벡터 |

**Returns:**
boolean - 모든 구성 요소가 같으면 True.
### op_ne(FVector2 a, FVector2 b) {#op-ne-com.aspose.threed.FVector2-com.aspose.threed.FVector2-}
```
public static boolean op_ne(FVector2 a, FVector2 b)
```


!= Operator overloading

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | 첫 번째 벡터 |
| b | [FVector2](../../com.aspose.threed/fvector2) | 두 번째 벡터 |

**Returns:**
boolean - 어떤 구성 요소라도 다르면 True.
### sub(FVector2 a, FVector2 b) {#sub-com.aspose.threed.FVector2-com.aspose.threed.FVector2-}
```
public static FVector2 sub(FVector2 a, FVector2 b)
```


\- 연산자 오버로드

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | 첫 번째 벡터 |
| b | [FVector2](../../com.aspose.threed/fvector2) | 두 번째 벡터 |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - The difference of two vectors.
### toString() {#toString--}
```
public String toString()
```


[FVector2](../../com.aspose.threed/fvector2)를 나타내는 문자열을 반환합니다

**Returns:**
java.lang.String - 현재 벡터의 문자열 표현.
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

