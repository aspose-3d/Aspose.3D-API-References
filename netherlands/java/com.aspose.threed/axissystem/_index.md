---
title: "AxisSystem"
second_title: "Aspose.3D voor Java API-referentie"
description: "Axissysteem is een combinatie van het coördinatensysteem, de opwaartse vector en de frontvector."
type: docs
weight: 18
url: /nl/java/com.aspose.threed/axissystem/
---

**Inheritance:**
java.lang.Object
```
public class AxisSystem
```

Het assenstelsel is een combinatie van coördinatensysteem, up‑vector en front‑vector.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [AxisSystem(CoordinateSystem coordinateSystem, Axis up)](#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-) | Construeert een nieuw axissysteem |
| [AxisSystem(Axis up, Axis front)](#AxisSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-) | Construeert een nieuw axissysteem |
| [AxisSystem(CoordinateSystem coordinateSystem, Axis up, Axis front)](#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-) | Construeert een nieuw axissysteem |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromAssetInfo(AssetInfo assetInfo)](#fromAssetInfo-com.aspose.threed.AssetInfo-) | Maak [AxisSystem](../../com.aspose.threed/axissystem) van [AssetInfo](../../com.aspose.threed/assetinfo) |
| [getClass()](#getClass--) |  |
| [getCoordinateSystem()](#getCoordinateSystem--) | Haalt het coördinatensysteem op van dit axissysteem. |
| [getFront()](#getFront--) | Haalt de frontvector op van dit axissysteem |
| [getUp()](#getUp--) | Haalt de opwaartse vector op van dit axissysteem. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [transformTo(AxisSystem targetSystem)](#transformTo-com.aspose.threed.AxisSystem-) | Maak een matrix die wordt gebruikt om van het huidige axissysteem naar het doelaxissysteem te converteren. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AxisSystem(CoordinateSystem coordinateSystem, Axis up) {#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-}
```
public AxisSystem(CoordinateSystem coordinateSystem, Axis up)
```


Construeert een nieuw axissysteem

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| coordinateSystem | [CoordinateSystem](../../com.aspose.threed/coordinatesystem) | Het coördinatensysteem dat in dit axissysteem wordt gebruikt |
| up | [Axis](../../com.aspose.threed/axis) | De opwaartse vector van het axissysteem |

### AxisSystem(Axis up, Axis front) {#AxisSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-}
```
public AxisSystem(Axis up, Axis front)
```


Construeert een nieuw axissysteem

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| up | [Axis](../../com.aspose.threed/axis) | De opwaartse vector van het axissysteem |
| front | [Axis](../../com.aspose.threed/axis) | De frontvector van het axissysteem |

### AxisSystem(CoordinateSystem coordinateSystem, Axis up, Axis front) {#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-}
```
public AxisSystem(CoordinateSystem coordinateSystem, Axis up, Axis front)
```


Construeert een nieuw axissysteem

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| coordinateSystem | [CoordinateSystem](../../com.aspose.threed/coordinatesystem) | Het coördinatensysteem dat in dit axissysteem wordt gebruikt |
| up | [Axis](../../com.aspose.threed/axis) | De opwaartse vector van het axissysteem |
| front | [Axis](../../com.aspose.threed/axis) | De frontvector van het axissysteem |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromAssetInfo(AssetInfo assetInfo) {#fromAssetInfo-com.aspose.threed.AssetInfo-}
```
public static AxisSystem fromAssetInfo(AssetInfo assetInfo)
```


Maak [AxisSystem](../../com.aspose.threed/axissystem) van [AssetInfo](../../com.aspose.threed/assetinfo)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| assetInfo | [AssetInfo](../../com.aspose.threed/assetinfo) | Van welke asset‑info het coördinatensysteem, de opwaartse en de frontvector moeten worden gelezen. |

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


Haalt het coördinatensysteem op van dit axissysteem.

**Returns:**
[CoordinateSystem](../../com.aspose.threed/coordinatesystem) - the coordinate system of this axis system.
### getFront() {#getFront--}
```
public Axis getFront()
```


Haalt de frontvector op van dit axissysteem

**Returns:**
[Axis](../../com.aspose.threed/axis) - the front vector of this axis system
### getUp() {#getUp--}
```
public Axis getUp()
```


Haalt de opwaartse vector op van dit axissysteem.

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


Maak een matrix die wordt gebruikt om van het huidige axissysteem naar het doelaxissysteem te converteren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| targetSystem | [AxisSystem](../../com.aspose.threed/axissystem) | Doelaxissysteem |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

