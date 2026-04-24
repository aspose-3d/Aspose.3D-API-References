---
title: BoundingBox2D
second_title: Aspose.3D for Java API 레퍼런스
description: 축에 정렬된 2D 경계 상자
type: docs
weight: 25
url: /ko/java/com.aspose.threed/boundingbox2d/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class BoundingBox2D implements Struct<BoundingBox2D>, Serializable
```

[Vector2](../../com.aspose.threed/vector2)에 대한 축 정렬 경계 상자
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [BoundingBox2D(Vector2 minimum, Vector2 maximum)](#BoundingBox2D-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | 주어진 최소 및 최대 코너로 유한 경계 상자를 초기화합니다 |
| [BoundingBox2D()](#BoundingBox2D--) |  |
## 필드

| 필드 | 설명 |
| --- | --- |
| [INFINITE](#INFINITE) | 무한 경계 상자 |
| [NULL](#NULL) | null 경계 상자 |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [clone()](#clone--) |  |
| [copyFrom(BoundingBox2D src)](#copyFrom-com.aspose.threed.BoundingBox2D-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtent()](#getExtent--) | 경계 상자의 범위를 가져옵니다. |
| [getMaximum()](#getMaximum--) | 경계 상자의 최대 코너 |
| [getMinimum()](#getMinimum--) | 경계 상자의 최소 코너 |
| [hashCode()](#hashCode--) |  |
| [merge(BoundingBox2D bb)](#merge-com.aspose.threed.BoundingBox2D-) | 새 상자를 현재 경계 상자에 병합합니다. |
| [merge(Vector2 pt)](#merge-com.aspose.threed.Vector2-) | 새 상자를 현재 경계 상자에 병합합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | 경계 상자의 문자열 표현을 가져옵니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BoundingBox2D(Vector2 minimum, Vector2 maximum) {#BoundingBox2D-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public BoundingBox2D(Vector2 minimum, Vector2 maximum)
```


주어진 최소 및 최대 코너로 유한 경계 상자를 초기화합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| minimum | [Vector2](../../com.aspose.threed/vector2) | 최소 코너 |
| maximum | [Vector2](../../com.aspose.threed/vector2) | 최대 코너 |

### BoundingBox2D() {#BoundingBox2D--}
```
public BoundingBox2D()
```


### INFINITE {#INFINITE}
```
public static final BoundingBox2D INFINITE
```


무한 경계 상자

### NULL {#NULL}
```
public static final BoundingBox2D NULL
```


null 경계 상자

### clone() {#clone--}
```
public BoundingBox2D clone()
```


현재 인스턴스를 복제합니다

**Returns:**
[BoundingBox2D](../../com.aspose.threed/boundingbox2d)
### copyFrom(BoundingBox2D src) {#copyFrom-com.aspose.threed.BoundingBox2D-}
```
public void copyFrom(BoundingBox2D src)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| src | [BoundingBox2D](../../com.aspose.threed/boundingbox2d) |  |

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
### getExtent() {#getExtent--}
```
public BoundingBoxExtent getExtent()
```


경계 상자의 범위를 가져옵니다.

**Returns:**
[BoundingBoxExtent](../../com.aspose.threed/boundingboxextent) - the extent of the bounding box.
### getMaximum() {#getMaximum--}
```
public Vector2 getMaximum()
```


경계 상자의 최대 코너

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The maximum corner of the bounding box
### getMinimum() {#getMinimum--}
```
public Vector2 getMinimum()
```


경계 상자의 최소 코너

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The minimum corner of the bounding box
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### merge(BoundingBox2D bb) {#merge-com.aspose.threed.BoundingBox2D-}
```
public void merge(BoundingBox2D bb)
```


새 상자를 현재 경계 상자에 병합합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bb | [BoundingBox2D](../../com.aspose.threed/boundingbox2d) | 병합할 경계 상자 |

### merge(Vector2 pt) {#merge-com.aspose.threed.Vector2-}
```
public void merge(Vector2 pt)
```


새 상자를 현재 경계 상자에 병합합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pt | [Vector2](../../com.aspose.threed/vector2) | 병합할 점 |

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


경계 상자의 문자열 표현을 가져옵니다.

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

