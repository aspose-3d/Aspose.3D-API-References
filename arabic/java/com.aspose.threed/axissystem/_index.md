---
title: "AxisSystem"
second_title: "مرجع Aspose.3D لـ Java API"
description: "نظام المحاور هو مزيج من نظام الإحداثيات والمتجه العلوي والمتجه الأمامي."
type: docs
weight: 18
url: /ar/java/com.aspose.threed/axissystem/
---

**Inheritance:**
java.lang.Object
```
public class AxisSystem
```

نظام المحاور هو مزيج من نظام الإحداثيات، المتجه العلوي والمتجه الأمامي.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [AxisSystem(CoordinateSystem coordinateSystem, Axis up)](#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-) | ينشئ نظام محاور جديد |
| [AxisSystem(Axis up, Axis front)](#AxisSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-) | ينشئ نظام محاور جديد |
| [AxisSystem(CoordinateSystem coordinateSystem, Axis up, Axis front)](#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-) | ينشئ نظام محاور جديد |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromAssetInfo(AssetInfo assetInfo)](#fromAssetInfo-com.aspose.threed.AssetInfo-) | إنشاء [AxisSystem](../../com.aspose.threed/axissystem) من [AssetInfo](../../com.aspose.threed/assetinfo) |
| [getClass()](#getClass--) |  |
| [getCoordinateSystem()](#getCoordinateSystem--) | يحصل على نظام الإحداثيات لهذا نظام المحاور. |
| [getFront()](#getFront--) | يحصل على المتجه الأمامي لهذا نظام المحاور |
| [getUp()](#getUp--) | يحصل على المتجه العلوي لهذا نظام المحاور. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [transformTo(AxisSystem targetSystem)](#transformTo-com.aspose.threed.AxisSystem-) | إنشاء مصفوفة تُستخدم للتحويل من نظام المحاور الحالي إلى نظام المحاور الهدف. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AxisSystem(CoordinateSystem coordinateSystem, Axis up) {#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-}
```
public AxisSystem(CoordinateSystem coordinateSystem, Axis up)
```


ينشئ نظام محاور جديد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| coordinateSystem | [CoordinateSystem](../../com.aspose.threed/coordinatesystem) | نظام الإحداثيات المستخدم في هذا نظام المحاور |
| up | [Axis](../../com.aspose.threed/axis) | المتجه العلوي لنظام المحاور |

### AxisSystem(Axis up, Axis front) {#AxisSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-}
```
public AxisSystem(Axis up, Axis front)
```


ينشئ نظام محاور جديد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| up | [Axis](../../com.aspose.threed/axis) | المتجه العلوي لنظام المحاور |
| front | [Axis](../../com.aspose.threed/axis) | المتجه الأمامي لنظام المحAxes |

### AxisSystem(CoordinateSystem coordinateSystem, Axis up, Axis front) {#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-}
```
public AxisSystem(CoordinateSystem coordinateSystem, Axis up, Axis front)
```


ينشئ نظام محاور جديد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| coordinateSystem | [CoordinateSystem](../../com.aspose.threed/coordinatesystem) | نظام الإحداثيات المستخدم في هذا نظام المحاور |
| up | [Axis](../../com.aspose.threed/axis) | المتجه العلوي لنظام المحاور |
| front | [Axis](../../com.aspose.threed/axis) | المتجه الأمامي لنظام المحAxes |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromAssetInfo(AssetInfo assetInfo) {#fromAssetInfo-com.aspose.threed.AssetInfo-}
```
public static AxisSystem fromAssetInfo(AssetInfo assetInfo)
```


إنشاء [AxisSystem](../../com.aspose.threed/axissystem) من [AssetInfo](../../com.aspose.threed/assetinfo)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| assetInfo | [AssetInfo](../../com.aspose.threed/assetinfo) | من أي AssetInfo لقراءة نظام الإحداثيات والمتجه العلوي والمتجه الأمامي. |

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


يحصل على نظام الإحداثيات لهذا نظام المحاور.

**Returns:**
[CoordinateSystem](../../com.aspose.threed/coordinatesystem) - the coordinate system of this axis system.
### getFront() {#getFront--}
```
public Axis getFront()
```


يحصل على المتجه الأمامي لهذا نظام المحاور

**Returns:**
[Axis](../../com.aspose.threed/axis) - the front vector of this axis system
### getUp() {#getUp--}
```
public Axis getUp()
```


يحصل على المتجه العلوي لهذا نظام المحاور.

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


إنشاء مصفوفة تُستخدم للتحويل من نظام المحاور الحالي إلى نظام المحاور الهدف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| targetSystem | [AxisSystem](../../com.aspose.threed/axissystem) | نظام المحاور الهدف |

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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

