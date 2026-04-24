---
title: AxisSystem
second_title: Aspose.3D for Java API 레퍼런스
description: 축 시스템은 좌표계의 위쪽 벡터와 앞쪽 벡터의 조합입니다.
type: docs
weight: 18
url: /ko/java/com.aspose.threed/axissystem/
---

**Inheritance:**
java.lang.Object
```
public class AxisSystem
```

축 시스템은 좌표계, 업 벡터 및 프론트 벡터의 조합입니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [AxisSystem(CoordinateSystem coordinateSystem, Axis up)](#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-) | 새 축 시스템을 생성합니다. |
| [AxisSystem(Axis up, Axis front)](#AxisSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-) | 새 축 시스템을 생성합니다. |
| [AxisSystem(CoordinateSystem coordinateSystem, Axis up, Axis front)](#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-) | 새 축 시스템을 생성합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromAssetInfo(AssetInfo assetInfo)](#fromAssetInfo-com.aspose.threed.AssetInfo-) | [AxisSystem](../../com.aspose.threed/axissystem)를 [AssetInfo](../../com.aspose.threed/assetinfo)에서 생성합니다. |
| [getClass()](#getClass--) |  |
| [getCoordinateSystem()](#getCoordinateSystem--) | 이 축 시스템의 좌표계를 가져옵니다. |
| [getFront()](#getFront--) | 이 축 시스템의 앞쪽 벡터를 가져옵니다. |
| [getUp()](#getUp--) | 이 축 시스템의 위쪽 벡터를 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [transformTo(AxisSystem targetSystem)](#transformTo-com.aspose.threed.AxisSystem-) | 현재 축 시스템에서 대상 축 시스템으로 변환하는 데 사용되는 행렬을 생성합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AxisSystem(CoordinateSystem coordinateSystem, Axis up) {#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-}
```
public AxisSystem(CoordinateSystem coordinateSystem, Axis up)
```


새 축 시스템을 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| coordinateSystem | [CoordinateSystem](../../com.aspose.threed/coordinatesystem) | 이 축 시스템에서 사용되는 좌표계 |
| up | [Axis](../../com.aspose.threed/axis) | 축 시스템의 위쪽 벡터 |

### AxisSystem(Axis up, Axis front) {#AxisSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-}
```
public AxisSystem(Axis up, Axis front)
```


새 축 시스템을 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| up | [Axis](../../com.aspose.threed/axis) | 축 시스템의 위쪽 벡터 |
| front | [Axis](../../com.aspose.threed/axis) | 축 시스템의 앞쪽 벡터 |

### AxisSystem(CoordinateSystem coordinateSystem, Axis up, Axis front) {#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-}
```
public AxisSystem(CoordinateSystem coordinateSystem, Axis up, Axis front)
```


새 축 시스템을 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| coordinateSystem | [CoordinateSystem](../../com.aspose.threed/coordinatesystem) | 이 축 시스템에서 사용되는 좌표계 |
| up | [Axis](../../com.aspose.threed/axis) | 축 시스템의 위쪽 벡터 |
| front | [Axis](../../com.aspose.threed/axis) | 축 시스템의 앞쪽 벡터 |

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
### fromAssetInfo(AssetInfo assetInfo) {#fromAssetInfo-com.aspose.threed.AssetInfo-}
```
public static AxisSystem fromAssetInfo(AssetInfo assetInfo)
```


[AxisSystem](../../com.aspose.threed/axissystem)를 [AssetInfo](../../com.aspose.threed/assetinfo)에서 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| assetInfo | [AssetInfo](../../com.aspose.threed/assetinfo) | 좌표계, 위쪽 및 앞쪽 벡터를 읽을 AssetInfo |

**Returns:**
[AxisSystem](../../com.aspose.threed/axissystem) - Axis system containg coordinate system, up, front from given asset info
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCoordinateSystem() {#getCoordinateSystem--}
```
public CoordinateSystem getCoordinateSystem()
```


이 축 시스템의 좌표계를 가져옵니다.

**Returns:**
[CoordinateSystem](../../com.aspose.threed/coordinatesystem) - the coordinate system of this axis system.
### getFront() {#getFront--}
```
public Axis getFront()
```


이 축 시스템의 앞쪽 벡터를 가져옵니다.

**Returns:**
[Axis](../../com.aspose.threed/axis) - the front vector of this axis system
### getUp() {#getUp--}
```
public Axis getUp()
```


이 축 시스템의 위쪽 벡터를 가져옵니다.

**Returns:**
[Axis](../../com.aspose.threed/axis) - the up vector of this axis system.
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




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transformTo(AxisSystem targetSystem) {#transformTo-com.aspose.threed.AxisSystem-}
```
public Matrix4 transformTo(AxisSystem targetSystem)
```


현재 축 시스템에서 대상 축 시스템으로 변환하는 데 사용되는 행렬을 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| targetSystem | [AxisSystem](../../com.aspose.threed/axissystem) | 대상 축 시스템 |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - A new transformation matrix to do the axis conversion
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

