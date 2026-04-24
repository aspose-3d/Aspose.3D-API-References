---
title: AxisSystem
second_title: Referensi API Aspose.3D untuk Java
description: Sistem sumbu adalah kombinasi dari sistem koordinat vektor atas dan vektor depan.
type: docs
weight: 18
url: /id/java/com.aspose.threed/axissystem/
---

**Inheritance:**
java.lang.Object
```
public class AxisSystem
```

Sistem sumbu adalah kombinasi dari sistem koordinat, vektor atas, dan vektor depan.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [AxisSystem(CoordinateSystem coordinateSystem, Axis up)](#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-) | Membuat sistem sumbu baru |
| [AxisSystem(Axis up, Axis front)](#AxisSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-) | Membuat sistem sumbu baru |
| [AxisSystem(CoordinateSystem coordinateSystem, Axis up, Axis front)](#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-) | Membuat sistem sumbu baru |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromAssetInfo(AssetInfo assetInfo)](#fromAssetInfo-com.aspose.threed.AssetInfo-) | Buat [AxisSystem](../../com.aspose.threed/axissystem) dari [AssetInfo](../../com.aspose.threed/assetinfo) |
| [getClass()](#getClass--) |  |
| [getCoordinateSystem()](#getCoordinateSystem--) | Mendapatkan sistem koordinat dari sistem sumbu ini. |
| [getFront()](#getFront--) | Mendapatkan vektor depan dari sistem sumbu ini |
| [getUp()](#getUp--) | Mendapatkan vektor atas dari sistem sumbu ini. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [transformTo(AxisSystem targetSystem)](#transformTo-com.aspose.threed.AxisSystem-) | Buat sebuah matriks yang digunakan untuk mengkonversi dari sistem sumbu saat ini ke sistem sumbu target. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AxisSystem(CoordinateSystem coordinateSystem, Axis up) {#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-}
```
public AxisSystem(CoordinateSystem coordinateSystem, Axis up)
```


Membuat sistem sumbu baru

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| coordinateSystem | [CoordinateSystem](../../com.aspose.threed/coordinatesystem) | Sistem koordinat yang digunakan dalam sistem sumbu ini |
| up | [Axis](../../com.aspose.threed/axis) | Vektor atas dari sistem sumbu |

### AxisSystem(Axis up, Axis front) {#AxisSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-}
```
public AxisSystem(Axis up, Axis front)
```


Membuat sistem sumbu baru

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| up | [Axis](../../com.aspose.threed/axis) | Vektor atas dari sistem sumbu |
| front | [Axis](../../com.aspose.threed/axis) | Vektor depan dari sistem sumbu |

### AxisSystem(CoordinateSystem coordinateSystem, Axis up, Axis front) {#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-}
```
public AxisSystem(CoordinateSystem coordinateSystem, Axis up, Axis front)
```


Membuat sistem sumbu baru

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| coordinateSystem | [CoordinateSystem](../../com.aspose.threed/coordinatesystem) | Sistem koordinat yang digunakan dalam sistem sumbu ini |
| up | [Axis](../../com.aspose.threed/axis) | Vektor atas dari sistem sumbu |
| front | [Axis](../../com.aspose.threed/axis) | Vektor depan dari sistem sumbu |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromAssetInfo(AssetInfo assetInfo) {#fromAssetInfo-com.aspose.threed.AssetInfo-}
```
public static AxisSystem fromAssetInfo(AssetInfo assetInfo)
```


Buat [AxisSystem](../../com.aspose.threed/axissystem) dari [AssetInfo](../../com.aspose.threed/assetinfo)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| assetInfo | [AssetInfo](../../com.aspose.threed/assetinfo) | Dari asset info mana untuk membaca sistem koordinat, vektor atas, dan vektor depan. |

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


Mendapatkan sistem koordinat dari sistem sumbu ini.

**Returns:**
[CoordinateSystem](../../com.aspose.threed/coordinatesystem) - the coordinate system of this axis system.
### getFront() {#getFront--}
```
public Axis getFront()
```


Mendapatkan vektor depan dari sistem sumbu ini

**Returns:**
[Axis](../../com.aspose.threed/axis) - the front vector of this axis system
### getUp() {#getUp--}
```
public Axis getUp()
```


Mendapatkan vektor atas dari sistem sumbu ini.

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


Buat sebuah matriks yang digunakan untuk mengkonversi dari sistem sumbu saat ini ke sistem sumbu target.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| targetSystem | [AxisSystem](../../com.aspose.threed/axissystem) | Sistem sumbu target |

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

