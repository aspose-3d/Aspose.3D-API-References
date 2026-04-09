---
title: AxisSystem
second_title: Aspose.3D for Java API リファレンス
description: 軸システムは座標系の上ベクトルと前ベクトルの組み合わせです。
type: docs
weight: 18
url: /ja/java/com.aspose.threed/axissystem/
---

**Inheritance:**
java.lang.Object
```
public class AxisSystem
```

軸系は座標系、上ベクトル、前ベクトルの組み合わせです。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [AxisSystem(CoordinateSystem coordinateSystem, Axis up)](#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-) | 新しい軸システムを作成します |
| [AxisSystem(Axis up, Axis front)](#AxisSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-) | 新しい軸システムを作成します |
| [AxisSystem(CoordinateSystem coordinateSystem, Axis up, Axis front)](#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-) | 新しい軸システムを作成します |
## Methods

| Method | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromAssetInfo(AssetInfo assetInfo)](#fromAssetInfo-com.aspose.threed.AssetInfo-) | [AxisSystem](../../com.aspose.threed/axissystem) を [AssetInfo](../../com.aspose.threed/assetinfo) から作成する |
| [getClass()](#getClass--) |  |
| [getCoordinateSystem()](#getCoordinateSystem--) | この軸システムの座標系を取得します。 |
| [getFront()](#getFront--) | この軸システムの前ベクトルを取得します。 |
| [getUp()](#getUp--) | この軸システムの上ベクトルを取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [transformTo(AxisSystem targetSystem)](#transformTo-com.aspose.threed.AxisSystem-) | 現在の軸システムから目標軸システムへ変換するために使用される行列を作成します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AxisSystem(CoordinateSystem coordinateSystem, Axis up) {#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-}
```
public AxisSystem(CoordinateSystem coordinateSystem, Axis up)
```


新しい軸システムを作成します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| coordinateSystem | [CoordinateSystem](../../com.aspose.threed/coordinatesystem) | この軸システムで使用される座標系 |
| up | [Axis](../../com.aspose.threed/axis) | 軸システムの上ベクトル |

### AxisSystem(Axis up, Axis front) {#AxisSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-}
```
public AxisSystem(Axis up, Axis front)
```


新しい軸システムを作成します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| up | [Axis](../../com.aspose.threed/axis) | 軸システムの上ベクトル |
| front | [Axis](../../com.aspose.threed/axis) | 軸システムの前ベクトル |

### AxisSystem(CoordinateSystem coordinateSystem, Axis up, Axis front) {#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-}
```
public AxisSystem(CoordinateSystem coordinateSystem, Axis up, Axis front)
```


新しい軸システムを作成します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| coordinateSystem | [CoordinateSystem](../../com.aspose.threed/coordinatesystem) | この軸システムで使用される座標系 |
| up | [Axis](../../com.aspose.threed/axis) | 軸システムの上ベクトル |
| front | [Axis](../../com.aspose.threed/axis) | 軸システムの前ベクトル |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromAssetInfo(AssetInfo assetInfo) {#fromAssetInfo-com.aspose.threed.AssetInfo-}
```
public static AxisSystem fromAssetInfo(AssetInfo assetInfo)
```


[AxisSystem](../../com.aspose.threed/axissystem) を [AssetInfo](../../com.aspose.threed/assetinfo) から作成する

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| assetInfo | [AssetInfo](../../com.aspose.threed/assetinfo) | どのアセット情報から座標系、上ベクトル、前ベクトルを読み取るか。 |

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


この軸システムの座標系を取得します。

**Returns:**
[CoordinateSystem](../../com.aspose.threed/coordinatesystem) - the coordinate system of this axis system.
### getFront() {#getFront--}
```
public Axis getFront()
```


この軸システムの前ベクトルを取得します。

**Returns:**
[Axis](../../com.aspose.threed/axis) - the front vector of this axis system
### getUp() {#getUp--}
```
public Axis getUp()
```


この軸システムの上ベクトルを取得します。

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


現在の軸システムから目標軸システムへ変換するために使用される行列を作成します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| targetSystem | [AxisSystem](../../com.aspose.threed/axissystem) | 目標軸システム |

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
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

