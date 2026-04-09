---
title: Int2D
second_title: Aspose.3D for Java API 레퍼런스
description: 2017년 5월 17일 lexchou에 의해 생성되었습니다.
type: docs
weight: 86
url: /ko/java/com.aspose.threed/int2d/
---

**Inheritance:**
java.lang.Object
```
public final class Int2D
```

lexchou가 2017년 5월 17일에 작성함. 2차원 int 배열 래퍼
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Int2D(int rows, int columns)](#Int2D-int-int-) | 기본 데이터 할당으로 2D int 배열을 생성합니다. |
| [Int2D(int rows, int columns, int[] data)](#Int2D-int-int-int---) | 주어진 데이터로 2D int 배열을 생성합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int r, int c)](#get-int-int-) | 지정된 위치의 요소를 가져옵니다 |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) |  |
| [getLength(int rank)](#getLength-int-) |  |
| [getRows()](#getRows--) |  |
| [hashCode()](#hashCode--) |  |
| [length()](#length--) | 이 2D 배열의 전체 길이를 가져옵니다 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [set(int r, int c, int v)](#set-int-int-int-) | 지정된 위치에 요소를 설정합니다 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Int2D(int rows, int columns) {#Int2D-int-int-}
```
public Int2D(int rows, int columns)
```


기본 데이터 할당으로 2D int 배열을 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 행 | int | 2D 배열의 행 수 |
| 열 | int | 2D 배열의 열 수 |

### Int2D(int rows, int columns, int[] data) {#Int2D-int-int-int---}
```
public Int2D(int rows, int columns, int[] data)
```


주어진 데이터로 2D int 배열을 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 행 | int | 2D 배열의 행 수 |
| 열 | int | 2D 배열의 열 수 |
| 데이터 | int[] | 감싸는 배열, Float2D가 내부적으로 이 배열을 사용합니다. |

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
### get(int r, int c) {#get-int-int-}
```
public int get(int r, int c)
```


지정된 위치의 요소를 가져옵니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| r | int | 행 |
| c | int | 열 |

**Returns:**
int - 지정된 위치의 값
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColumns() {#getColumns--}
```
public int getColumns()
```




**Returns:**
int
### getLength(int rank) {#getLength-int-}
```
public int getLength(int rank)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 랭크 | int |  |

**Returns:**
int
### getRows() {#getRows--}
```
public int getRows()
```




**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### length() {#length--}
```
public int length()
```


이 2D 배열의 전체 길이를 가져옵니다

**Returns:**
int - 이 2D 배열의 전체 float 수
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### set(int r, int c, int v) {#set-int-int-int-}
```
public void set(int r, int c, int v)
```


지정된 위치에 요소를 설정합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| r | int | 행 |
| c | int | 열 |
| v | int | 값 |

### toString() {#toString--}
```
public String toString()
```




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

