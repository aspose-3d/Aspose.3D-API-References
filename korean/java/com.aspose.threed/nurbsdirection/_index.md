---
title: NurbsDirection
second_title: Aspose.3D for Java API 레퍼런스
description: 3D 에는 두 개의 방향이 있으며, 와 가 각각의 방향에 대한 데이터를 정의합니다.
type: docs
weight: 113
url: /ko/java/com.aspose.threed/nurbsdirection/
---

**Inheritance:**
java.lang.Object
```
public class NurbsDirection
```

3D [NurbsSurface](../../com.aspose.threed/nurbssurface)에는 두 개의 방향이 있으며, [NurbsSurface.getU](../../com.aspose.threed/nurbssurface\\#getU)와 [NurbsSurface.getV](../../com.aspose.threed/nurbssurface\\#getV)입니다. [NurbsDirection](../../com.aspose.threed/nurbsdirection)은 각 방향에 대한 데이터를 정의합니다. 방향은 실제로 NURBS 곡선이며, 이는 [getOrder](../../com.aspose.threed/nurbsdirection\\#getOrder), [getKnotVectors](../../com.aspose.threed/nurbsdirection\\#getKnotVectors) 및 [NurbsSurface](../../com.aspose.threed/nurbssurface)에서 정의된 가중 제어점 집합에 의해 정의됩니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [NurbsDirection()](#NurbsDirection--) | 새로운 [NurbsDirection](../../com.aspose.threed/nurbsdirection) 인스턴스를 생성합니다 |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | 현재 방향의 제어점 수를 가져옵니다. |
| [getDegree()](#getDegree--) | NURBS 곡선의 차수를 가져옵니다. 차수는 Order - 1 로 정의됩니다 |
| [getDivisions()](#getDivisions--) | 현재 방향에서 인접한 제어점 사이의 분할 수를 가져옵니다. |
| [getKnotVectors()](#getKnotVectors--) | 노트 벡터를 가져옵니다. 이는 매개변수 값들의 순서로, 제어점이 NURBS 곡선에 영향을 미치는 위치와 방식을 결정합니다. |
| [getMultiplicity()](#getMultiplicity--) | 중복도를 가져옵니다. |
| [getOrder()](#getOrder--) | NURBS 곡선의 차수를 가져옵니다. 이는 곡선상의 특정 점에 영향을 주는 인접 제어점의 수를 정의합니다. |
| [getType()](#getType--) | 현재 방향의 유형을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCount(int value)](#setCount-int-) | 현재 방향의 제어점 수를 설정합니다. |
| [setDegree(int value)](#setDegree-int-) | NURBS 곡선의 차수를 설정합니다. 차수는 Order - 1 로 정의됩니다 |
| [setDivisions(int value)](#setDivisions-int-) | 현재 방향에서 인접한 제어점 사이의 분할 수를 설정합니다. |
| [setOrder(int value)](#setOrder-int-) | NURBS 곡선의 차수를 설정합니다. 이는 곡선상의 특정 점에 영향을 주는 인접 제어점의 수를 정의합니다. |
| [setType(NurbsType value)](#setType-com.aspose.threed.NurbsType-) | 현재 방향의 유형을 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NurbsDirection() {#NurbsDirection--}
```
public NurbsDirection()
```


새로운 [NurbsDirection](../../com.aspose.threed/nurbsdirection) 인스턴스를 생성합니다

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public int getCount()
```


현재 방향의 제어점 수를 가져옵니다.

**Returns:**
int - 현재 방향의 제어점 수.
### getDegree() {#getDegree--}
```
public int getDegree()
```


NURBS 곡선의 차수를 가져옵니다. 차수는 Order - 1 로 정의됩니다

**Returns:**
int - NURBS 곡선의 차수이며, 차수는 Order - 1 로 정의됩니다
### getDivisions() {#getDivisions--}
```
public int getDivisions()
```


현재 방향에서 인접한 제어점 사이의 분할 수를 가져옵니다.

**Returns:**
int - 현재 방향에서 인접한 제어점 사이의 분할 수.
### getKnotVectors() {#getKnotVectors--}
```
public List<Double> getKnotVectors()
```


노트 벡터를 가져옵니다. 이는 매개변수 값들의 순서로, 제어점이 NURBS 곡선에 영향을 미치는 위치와 방식을 결정합니다.

**Returns:**
java.util.List<java.lang.Double> - 노트 벡터이며, 이는 매개변수 값들의 순서로 제어점이 NURBS 곡선에 영향을 미치는 위치와 방식을 결정합니다.
### getMultiplicity() {#getMultiplicity--}
```
public List<Integer> getMultiplicity()
```


중복도를 가져옵니다.

**Returns:**
java.util.List<java.lang.Integer> - 다중성.
### getOrder() {#getOrder--}
```
public int getOrder()
```


NURBS 곡선의 차수를 가져옵니다. 이는 곡선상의 특정 점에 영향을 주는 인접 제어점의 수를 정의합니다.

**Returns:**
int - NURBS 곡선의 차수이며, 곡선상의 임의의 점에 영향을 주는 인접 제어점들의 수를 정의합니다.
### getType() {#getType--}
```
public NurbsType getType()
```


현재 방향의 유형을 가져옵니다.

**Returns:**
[NurbsType](../../com.aspose.threed/nurbstype) - the type of the current direction.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setCount(int value) {#setCount-int-}
```
public void setCount(int value)
```


현재 방향의 제어점 수를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 새 값 |

### setDegree(int value) {#setDegree-int-}
```
public void setDegree(int value)
```


NURBS 곡선의 차수를 설정합니다. 차수는 Order - 1 로 정의됩니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 새 값 |

### setDivisions(int value) {#setDivisions-int-}
```
public void setDivisions(int value)
```


현재 방향에서 인접한 제어점 사이의 분할 수를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 새 값 |

### setOrder(int value) {#setOrder-int-}
```
public void setOrder(int value)
```


NURBS 곡선의 차수를 설정합니다. 이는 곡선상의 특정 점에 영향을 주는 인접 제어점의 수를 정의합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 새 값 |

### setType(NurbsType value) {#setType-com.aspose.threed.NurbsType-}
```
public void setType(NurbsType value)
```


현재 방향의 유형을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [NurbsType](../../com.aspose.threed/nurbstype) | 새 값 |

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

