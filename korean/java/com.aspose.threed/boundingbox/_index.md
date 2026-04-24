---
title: BoundingBox
second_title: Aspose.3D for Java API 레퍼런스
description: 축에 정렬된 경계 상자 예시  다음 코드는 Entity 인스턴스에서 경계 상자를 가져오는 방법을 보여줍니다.
type: docs
weight: 24
url: /ko/java/com.aspose.threed/boundingbox/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class BoundingBox implements Struct<BoundingBox>, Serializable
```

축 정렬 경계 상자 **예시:** 다음 코드는 Entity 인스턴스로부터 경계 상자를 얻는 방법을 보여줍니다.

```
var sphere = new Sphere();
      var boundingBox = sphere.getBoundingBox();
      System.out.println("Bounding box = " + boundingBox);
```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [BoundingBox(Vector3 minimum, Vector3 maximum)](#BoundingBox-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | 주어진 최소 및 최대 코너로 유한 경계 상자를 초기화합니다 |
| [BoundingBox(double minX, double minY, double minZ, double maxX, double maxY, double maxZ)](#BoundingBox-double-double-double-double-double-double-) | 주어진 최소 및 최대 코너로 유한 경계 상자를 초기화합니다 |
| [BoundingBox()](#BoundingBox--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(BoundingBox bbox)](#contains-com.aspose.threed.BoundingBox-) | 현재 경계 상자 안에 포함되는지 확인하기 위한 경계 상자. |
| [contains(Vector3 p)](#contains-com.aspose.threed.Vector3-) | 점 p가 경계 상자 안에 있는지 확인합니다 |
| [copyFrom(BoundingBox src)](#copyFrom-com.aspose.threed.BoundingBox-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 두 객체가 같은지 결정합니다 |
| [fromGeometry(Geometry geometry)](#fromGeometry-com.aspose.threed.Geometry-) | 주어진 기하학에서 경계 상자를 구성합니다 |
| [getCenter()](#getCenter--) | 경계 상자의 중심. |
| [getClass()](#getClass--) |  |
| [getExtent()](#getExtent--) | 경계 상자의 범위를 가져옵니다. |
| [getInfinite()](#getInfinite--) | 무한 경계 상자 |
| [getMaximum()](#getMaximum--) | 경계 상자의 최대 코너 |
| [getMinimum()](#getMinimum--) | 경계 상자의 최소 코너 |
| [getNull()](#getNull--) | null 경계 상자 |
| [getSize()](#getSize--) | 경계 상자의 크기 |
| [hashCode()](#hashCode--) | 이 인스턴스의 해시 코드를 반환합니다 |
| [merge(BoundingBox bb)](#merge-com.aspose.threed.BoundingBox-) | 새 상자를 현재 경계 상자에 병합합니다. |
| [merge(Vector3 pt)](#merge-com.aspose.threed.Vector3-) | 현재 경계 상자를 주어진 점과 병합합니다 |
| [merge(Vector4 pt)](#merge-com.aspose.threed.Vector4-) | 현재 경계 상자를 주어진 점과 병합합니다 |
| [merge(double x, double y, double z)](#merge-double-double-double-) | 현재 경계 상자를 주어진 점과 병합합니다 |
| [mul(BoundingBox bbox, Matrix4 mat)](#mul-com.aspose.threed.BoundingBox-com.aspose.threed.Matrix4-) | 곱셈에 대한 연산자 오버로드, 새로운 경계 상자의 최소 및 최대 코너가 행렬에 의해 변환됩니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [overlapsWith(BoundingBox box)](#overlapsWith-com.aspose.threed.BoundingBox-) | 현재 경계 상자가 지정된 경계 상자와 겹치는지 확인합니다. |
| [scale()](#scale--) | 포함된 모든 점 중 절대값이 가장 큰 좌표 값을 계산합니다. |
| [toString()](#toString--) | 경계 상자의 문자열 표현을 가져옵니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BoundingBox(Vector3 minimum, Vector3 maximum) {#BoundingBox-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public BoundingBox(Vector3 minimum, Vector3 maximum)
```


주어진 최소 및 최대 코너로 유한 경계 상자를 초기화합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| minimum | [Vector3](../../com.aspose.threed/vector3) | 최소 코너 |
|  | maximum | [Vector3](../../com.aspose.threed/vector3) | 최대 코너 **Example:** 다음 코드는 최소 및 최대 코너에서 경계 상자를 구성하는 방법을 보여줍니다. |

```
var minimum = new Vector3(0, 0, 0);
  var maximum = new Vector3(10, 10, 10);
  var boundingBox = new BoundingBox(minimum, maximum);
  System.out.println("Bounding box = " + boundingBox);
``` |

### BoundingBox(double minX, double minY, double minZ, double maxX, double maxY, double maxZ) {#BoundingBox-double-double-double-double-double-double-}
```
public BoundingBox(double minX, double minY, double minZ, double maxX, double maxY, double maxZ)
```


주어진 최소 및 최대 코너로 유한 경계 상자를 초기화합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| minX | double | 최소 코너의 X |
| minY | double | 최소 코너의 Y |
| minZ | double | 최소 코너의 Z |
| maxX | double | 최대 코너의 X |
| maxY | double | 최대 코너의 Y |
|  | maxZ | double | 최대 코너의 Z **예시:** 다음 코드는 최소 및 최대 코너로부터 경계 상자를 구성하는 방법을 보여줍니다. |

```
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
  System.out.println("Bounding box = " + boundingBox);
``` |

### BoundingBox() {#BoundingBox--}
```
public BoundingBox()
```


### clone() {#clone--}
```
public BoundingBox clone()
```


현재 인스턴스를 복제합니다

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox)
### contains(BoundingBox bbox) {#contains-com.aspose.threed.BoundingBox-}
```
public boolean contains(BoundingBox bbox)
```


현재 경계 상자 안에 포함되는지 확인하기 위한 경계 상자.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bbox | [BoundingBox](../../com.aspose.threed/boundingbox) |  |

**Returns:**
boolean
### contains(Vector3 p) {#contains-com.aspose.threed.Vector3-}
```
public boolean contains(Vector3 p)
```


점 p가 경계 상자 안에 있는지 확인합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| p | [Vector3](../../com.aspose.threed/vector3) | 테스트할 점 |

**Returns:**
boolean - 점이 경계 상자 안에 있으면 True **예시:** 다음 코드는 점이 경계 상자 안에 있는지 확인하는 방법을 보여줍니다.

```
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
  var pt = new Vector3(4, 4, 4);
  System.out.println("Bounding box overlaps = " + boundingBox.contains(pt));
```
### copyFrom(BoundingBox src) {#copyFrom-com.aspose.threed.BoundingBox-}
```
public void copyFrom(BoundingBox src)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| src | [BoundingBox](../../com.aspose.threed/boundingbox) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


두 객체가 같은지 결정합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 비교할 객체 |

**Returns:**
boolean - 두 객체가 같으면 true
### fromGeometry(Geometry geometry) {#fromGeometry-com.aspose.threed.Geometry-}
```
public static BoundingBox fromGeometry(Geometry geometry)
```


주어진 기하학에서 경계 상자를 구성합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| geometry | [Geometry](../../com.aspose.threed/geometry) | 경계 상자를 계산할 기하학 |

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The bounding box of given geometry **Example:** The following code shows how to construct a bounding box from a geometry instance.

```
var sphere = (new Sphere()).toMesh();
  var boundingBox = BoundingBox.fromGeometry(sphere);
  System.out.println("Bounding box = " + boundingBox);
```
### getCenter() {#getCenter--}
```
public Vector3 getCenter()
```


경계 상자의 중심.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The center of the bounding box.
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
### getInfinite() {#getInfinite--}
```
public static BoundingBox getInfinite()
```


무한 경계 상자

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The infinite bounding box
### getMaximum() {#getMaximum--}
```
public Vector3 getMaximum()
```


경계 상자의 최대 코너

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The maximum corner of the bounding box
### getMinimum() {#getMinimum--}
```
public Vector3 getMinimum()
```


경계 상자의 최소 코너

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The minimum corner of the bounding box
### getNull() {#getNull--}
```
public static BoundingBox getNull()
```


null 경계 상자

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The null bounding box
### getSize() {#getSize--}
```
public Vector3 getSize()
```


경계 상자의 크기

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The size of the bounding box
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 인스턴스의 해시 코드를 반환합니다

**Returns:**
int - 경계 상자의 해시 코드
### merge(BoundingBox bb) {#merge-com.aspose.threed.BoundingBox-}
```
public void merge(BoundingBox bb)
```


새 상자를 현재 경계 상자에 병합합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bb | [BoundingBox](../../com.aspose.threed/boundingbox) | 병합할 경계 상자 |

### merge(Vector3 pt) {#merge-com.aspose.threed.Vector3-}
```
public void merge(Vector3 pt)
```


현재 경계 상자를 주어진 점과 병합합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | pt | [Vector3](../../com.aspose.threed/vector3) | 경계 상자에 병합될 점 **예시:** 다음 코드는 점을 경계 상자에 병합하는 방법을 보여줍니다. |

```
var boundingBox = BoundingBox.getNull();
  boundingBox.Merge(new Vector3(1, 10, -1));
  System.out.println("Bounding box = " + boundingBox);
``` |

### merge(Vector4 pt) {#merge-com.aspose.threed.Vector4-}
```
public void merge(Vector4 pt)
```


현재 경계 상자를 주어진 점과 병합합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | pt | [Vector4](../../com.aspose.threed/vector4) | 경계 상자에 병합될 점 **예시:** 다음 코드는 점을 경계 상자에 병합하는 방법을 보여줍니다. |

```
var boundingBox = BoundingBox.getNull();
  boundingBox.Merge(new Vector4(1, 10, -1));
  System.out.println("Bounding box = " + boundingBox);
``` |

### merge(double x, double y, double z) {#merge-double-double-double-}
```
public void merge(double x, double y, double z)
```


현재 경계 상자를 주어진 점과 병합합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | double | 경계 상자에 병합될 점 |
| y | double | 경계 상자에 병합될 점 |
|  | z | double | 경계 상자에 병합될 점 **예시:** 다음 코드는 점을 경계 상자에 병합하는 방법을 보여줍니다. |

```
var boundingBox = BoundingBox.getNull();
  boundingBox.Merge(1, 10, -1);
  System.out.println("Bounding box = " + boundingBox);
``` |

### mul(BoundingBox bbox, Matrix4 mat) {#mul-com.aspose.threed.BoundingBox-com.aspose.threed.Matrix4-}
```
public static BoundingBox mul(BoundingBox bbox, Matrix4 mat)
```


곱셈에 대한 연산자 오버로드, 새로운 경계 상자의 최소 및 최대 코너가 행렬에 의해 변환됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bbox | [BoundingBox](../../com.aspose.threed/boundingbox) | 입력 경계 상자. |
| mat | [Matrix4](../../com.aspose.threed/matrix4) | 경계 상자의 코너를 변환하는 데 사용되는 행렬 |

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The product of bounding box and transform matrix.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### overlapsWith(BoundingBox box) {#overlapsWith-com.aspose.threed.BoundingBox-}
```
public boolean overlapsWith(BoundingBox box)
```


현재 경계 상자가 지정된 경계 상자와 겹치는지 확인합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| box | [BoundingBox](../../com.aspose.threed/boundingbox) | 테스트할 다른 경계 상자 |

**Returns:**
boolean - 현재 경계 상자가 주어진 상자와 겹치면 True **예시:** 다음 코드는 두 경계 상자가 서로 겹치는지 확인하는 방법을 보여줍니다.

```
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
  var bbox2 = new BoundingBox(1, 1, 1, 11, 11, 11);
  System.out.println("Bounding box overlaps = " + boundingBox.overlapsWith(bbox2));
```
### scale() {#scale--}
```
public double scale()
```


포함된 모든 점 중 절대값이 가장 큰 좌표 값을 계산합니다.

**Returns:**
double - 포함된 모든 점 중 계산된 절대 최대 좌표값.
### toString() {#toString--}
```
public String toString()
```


경계 상자의 문자열 표현을 가져옵니다.

**Returns:**
java.lang.String - 경계 상자의 문자열 표현.
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

