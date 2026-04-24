---
title: EndPoint
second_title: Aspose.3D for Java API 레퍼런스
description: 곡선을 자르기 위한 끝점은 매개변수 값이거나 직교점일 수 있습니다.
type: docs
weight: 51
url: /ko/java/com.aspose.threed/endpoint/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class EndPoint implements Struct<EndPoint>, Serializable
```

곡선을 트리밍하는 끝점으로, 매개변수 값이나 직교 좌표점이 될 수 있습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [EndPoint(Vector3 point)](#EndPoint-com.aspose.threed.Vector3-) | 직교점에서 [EndPoint](../../com.aspose.threed/endpoint)를 구성합니다. |
| [EndPoint(double v)](#EndPoint-double-) | 실수 매개변수에서 [EndPoint](../../com.aspose.threed/endpoint)를 구성합니다. |
| [EndPoint()](#EndPoint--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [clone()](#clone--) |  |
| [copyFrom(EndPoint src)](#copyFrom-com.aspose.threed.EndPoint-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromDegree(double degree)](#fromDegree-double-) | 도를 단위로 하는 끝점을 생성합니다. |
| [fromRadian(double degree)](#fromRadian-double-) | 라디안을 단위로 하는 끝점을 생성합니다. |
| [getAsPoint()](#getAsPoint--) | 끝점을 직교점으로 가져오며, 예외가 발생할 수 있습니다. |
| [getAsValue()](#getAsValue--) | 끝점을 실수 매개변수로 가져오며, 예외가 발생합니다. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [isCartesianPoint()](#isCartesianPoint--) | 끝점이 직교점인가요? |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | 현재 끝점의 문자열 표현을 반환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EndPoint(Vector3 point) {#EndPoint-com.aspose.threed.Vector3-}
```
public EndPoint(Vector3 point)
```


직교점에서 [EndPoint](../../com.aspose.threed/endpoint)를 구성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point | [Vector3](../../com.aspose.threed/vector3) | 구성할 점 |

### EndPoint(double v) {#EndPoint-double-}
```
public EndPoint(double v)
```


실수 매개변수에서 [EndPoint](../../com.aspose.threed/endpoint)를 구성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| v | double | 끝점을 구성하기 위한 실수 매개변수 |

### EndPoint() {#EndPoint--}
```
public EndPoint()
```


### clone() {#clone--}
```
public EndPoint clone()
```


현재 인스턴스를 복제합니다

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint)
### copyFrom(EndPoint src) {#copyFrom-com.aspose.threed.EndPoint-}
```
public void copyFrom(EndPoint src)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| src | [EndPoint](../../com.aspose.threed/endpoint) |  |

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
### fromDegree(double degree) {#fromDegree-double-}
```
public static EndPoint fromDegree(double degree)
```


도를 단위로 하는 끝점을 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| degree | double | 도 단위 값 |

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint) - An end point constructed from degree
### fromRadian(double degree) {#fromRadian-double-}
```
public static EndPoint fromRadian(double degree)
```


라디안을 단위로 하는 끝점을 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| degree | double | 라디안 단위 값 |

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint) - An end point constructed from radian
### getAsPoint() {#getAsPoint--}
```
public Vector3 getAsPoint()
```


끝점을 직교점으로 가져오며, 예외가 발생할 수 있습니다.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the end point as Cartesian point, or thrown an exception.
### getAsValue() {#getAsValue--}
```
public double getAsValue()
```


끝점을 실수 매개변수로 가져오며, 예외가 발생합니다.

**Returns:**
double - 끝점을 실수 매개변수로, 예외가 발생할 수 있습니다.
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
### isCartesianPoint() {#isCartesianPoint--}
```
public boolean isCartesianPoint()
```


끝점이 직교점인가요?

**Returns:**
boolean - 끝점이 직교점인가요?
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


현재 끝점의 문자열 표현을 반환합니다.

**Returns:**
java.lang.String
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

