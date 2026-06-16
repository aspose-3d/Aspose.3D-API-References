---
title: "AxisSystem"
second_title: "Aspose.3D for Java API Referansı"
description: "Eksen sistemi, koordinat sisteminin yukarı vektörü ve ön vektörünün bir kombinasyonudur."
type: docs
weight: 18
url: /tr/java/com.aspose.threed/axissystem/
---

**Inheritance:**
java.lang.Object
```
public class AxisSystem
```

Eksen sistemi, koordinat sistemi, yukarı vektörü ve ön vektörünün bir kombinasyonudur.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [AxisSystem(CoordinateSystem coordinateSystem, Axis up)](#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-) | Yeni bir eksen sistemi oluşturur |
| [AxisSystem(Axis up, Axis front)](#AxisSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-) | Yeni bir eksen sistemi oluşturur |
| [AxisSystem(CoordinateSystem coordinateSystem, Axis up, Axis front)](#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-) | Yeni bir eksen sistemi oluşturur |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromAssetInfo(AssetInfo assetInfo)](#fromAssetInfo-com.aspose.threed.AssetInfo-) | Oluştur [AxisSystem](../../com.aspose.threed/axissystem) [AssetInfo](../../com.aspose.threed/assetinfo)'den |
| [getClass()](#getClass--) |  |
| [getCoordinateSystem()](#getCoordinateSystem--) | Bu eksen sisteminin koordinat sistemini alır. |
| [getFront()](#getFront--) | Bu eksen sisteminin ön vektörünü alır |
| [getUp()](#getUp--) | Bu eksen sisteminin yukarı vektörünü alır. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [transformTo(AxisSystem targetSystem)](#transformTo-com.aspose.threed.AxisSystem-) | Mevcut eksen sisteminden hedef eksen sistemine dönüştürmek için kullanılan bir matris oluştur. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AxisSystem(CoordinateSystem coordinateSystem, Axis up) {#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-}
```
public AxisSystem(CoordinateSystem coordinateSystem, Axis up)
```


Yeni bir eksen sistemi oluşturur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| coordinateSystem | [CoordinateSystem](../../com.aspose.threed/coordinatesystem) | Bu eksen sisteminde kullanılan koordinat sistemi |
| up | [Axis](../../com.aspose.threed/axis) | Eksen sisteminin yukarı vektörü |

### AxisSystem(Axis up, Axis front) {#AxisSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-}
```
public AxisSystem(Axis up, Axis front)
```


Yeni bir eksen sistemi oluşturur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| up | [Axis](../../com.aspose.threed/axis) | Eksen sisteminin yukarı vektörü |
| front | [Axis](../../com.aspose.threed/axis) | Eksen sisteminin ön vektörü |

### AxisSystem(CoordinateSystem coordinateSystem, Axis up, Axis front) {#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-}
```
public AxisSystem(CoordinateSystem coordinateSystem, Axis up, Axis front)
```


Yeni bir eksen sistemi oluşturur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| coordinateSystem | [CoordinateSystem](../../com.aspose.threed/coordinatesystem) | Bu eksen sisteminde kullanılan koordinat sistemi |
| up | [Axis](../../com.aspose.threed/axis) | Eksen sisteminin yukarı vektörü |
| front | [Axis](../../com.aspose.threed/axis) | Eksen sisteminin ön vektörü |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromAssetInfo(AssetInfo assetInfo) {#fromAssetInfo-com.aspose.threed.AssetInfo-}
```
public static AxisSystem fromAssetInfo(AssetInfo assetInfo)
```


Oluştur [AxisSystem](../../com.aspose.threed/axissystem) [AssetInfo](../../com.aspose.threed/assetinfo)'den

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| assetInfo | [AssetInfo](../../com.aspose.threed/assetinfo) | Koordinat sistemi, yukarı ve ön vektörünü okumak için hangi asset info kullanılacağını belirtir. |

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


Bu eksen sisteminin koordinat sistemini alır.

**Returns:**
[CoordinateSystem](../../com.aspose.threed/coordinatesystem) - the coordinate system of this axis system.
### getFront() {#getFront--}
```
public Axis getFront()
```


Bu eksen sisteminin ön vektörünü alır

**Returns:**
[Axis](../../com.aspose.threed/axis) - the front vector of this axis system
### getUp() {#getUp--}
```
public Axis getUp()
```


Bu eksen sisteminin yukarı vektörünü alır.

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


Mevcut eksen sisteminden hedef eksen sistemine dönüştürmek için kullanılan bir matris oluştur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| targetSystem | [AxisSystem](../../com.aspose.threed/axissystem) | Hedef eksen sistemi |

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

