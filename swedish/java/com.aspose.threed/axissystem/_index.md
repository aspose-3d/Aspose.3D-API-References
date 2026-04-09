---
title: AxisSystem
second_title: Aspose.3D for Java API-referens
description: Axelsystem är en kombination av koordinatsystemets uppvektor och framvektor.
type: docs
weight: 18
url: /sv/java/com.aspose.threed/axissystem/
---

**Inheritance:**
java.lang.Object
```
public class AxisSystem
```

Axelsystemet är en kombination av koordinatsystem, uppvektor och framvektor.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [AxisSystem(CoordinateSystem coordinateSystem, Axis up)](#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-) | Skapar ett nytt axelsystem |
| [AxisSystem(Axis up, Axis front)](#AxisSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-) | Skapar ett nytt axelsystem |
| [AxisSystem(CoordinateSystem coordinateSystem, Axis up, Axis front)](#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-) | Skapar ett nytt axelsystem |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromAssetInfo(AssetInfo assetInfo)](#fromAssetInfo-com.aspose.threed.AssetInfo-) | Skapa [AxisSystem](../../com.aspose.threed/axissystem) från [AssetInfo](../../com.aspose.threed/assetinfo) |
| [getClass()](#getClass--) |  |
| [getCoordinateSystem()](#getCoordinateSystem--) | Hämtar koordinatsystemet för detta axelsystem. |
| [getFront()](#getFront--) | Hämtar framvektorn för detta axelsystem |
| [getUp()](#getUp--) | Hämtar uppvektorn för detta axelsystem. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [transformTo(AxisSystem targetSystem)](#transformTo-com.aspose.threed.AxisSystem-) | Skapa en matris som används för att konvertera från aktuellt axelsystem till målaxelsystem. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AxisSystem(CoordinateSystem coordinateSystem, Axis up) {#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-}
```
public AxisSystem(CoordinateSystem coordinateSystem, Axis up)
```


Skapar ett nytt axelsystem

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| coordinateSystem | [CoordinateSystem](../../com.aspose.threed/coordinatesystem) | Koordinatsystemet som används i detta axelsystem |
| up | [Axis](../../com.aspose.threed/axis) | Uppvektorn för axelsystemet |

### AxisSystem(Axis up, Axis front) {#AxisSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-}
```
public AxisSystem(Axis up, Axis front)
```


Skapar ett nytt axelsystem

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| up | [Axis](../../com.aspose.threed/axis) | Uppvektorn för axelsystemet |
| front | [Axis](../../com.aspose.threed/axis) | Framvektorn för axelsystemet |

### AxisSystem(CoordinateSystem coordinateSystem, Axis up, Axis front) {#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-}
```
public AxisSystem(CoordinateSystem coordinateSystem, Axis up, Axis front)
```


Skapar ett nytt axelsystem

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| coordinateSystem | [CoordinateSystem](../../com.aspose.threed/coordinatesystem) | Koordinatsystemet som används i detta axelsystem |
| up | [Axis](../../com.aspose.threed/axis) | Uppvektorn för axelsystemet |
| front | [Axis](../../com.aspose.threed/axis) | Framvektorn för axelsystemet |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromAssetInfo(AssetInfo assetInfo) {#fromAssetInfo-com.aspose.threed.AssetInfo-}
```
public static AxisSystem fromAssetInfo(AssetInfo assetInfo)
```


Skapa [AxisSystem](../../com.aspose.threed/axissystem) från [AssetInfo](../../com.aspose.threed/assetinfo)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| assetInfo | [AssetInfo](../../com.aspose.threed/assetinfo) | Från vilken asset info som koordinatsystem, uppvektor och framvektor ska läsas. |

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


Hämtar koordinatsystemet för detta axelsystem.

**Returns:**
[CoordinateSystem](../../com.aspose.threed/coordinatesystem) - the coordinate system of this axis system.
### getFront() {#getFront--}
```
public Axis getFront()
```


Hämtar framvektorn för detta axelsystem

**Returns:**
[Axis](../../com.aspose.threed/axis) - the front vector of this axis system
### getUp() {#getUp--}
```
public Axis getUp()
```


Hämtar uppvektorn för detta axelsystem.

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


Skapa en matris som används för att konvertera från aktuellt axelsystem till målaxelsystem.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| targetSystem | [AxisSystem](../../com.aspose.threed/axissystem) | Målaxelsystem |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

