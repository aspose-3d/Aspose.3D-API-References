---
title: Viewport
second_title: Referensi API Aspose.3D untuk Java
description: Sebuah  berisi setidaknya satu viewport untuk merender adegan.
type: docs
weight: 229
url: /id/java/com.aspose.threed/viewport/
---

**Inheritance:**
java.lang.Object
```
public class Viewport
```

Sebuah [IRenderTarget](../../com.aspose.threed/irendertarget) berisi setidaknya satu viewport untuk merender adegan.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [clone()](#clone--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArea()](#getArea--) | Mendapatkan area viewport dalam target render. |
| [getBackgroundColor()](#getBackgroundColor--) | Mendapatkan warna latar belakang viewport. |
| [getClass()](#getClass--) |  |
| [getDepthClear()](#getDepthClear--) | Mendapatkan nilai kedalaman yang digunakan saat membersihkan viewport dengan bit buffer kedalaman diatur. |
| [getEnabled()](#getEnabled--) | Aktifkan atau nonaktifkan viewport ini. |
| [getFrustum()](#getFrustum--) | Mendapatkan kamera dari [Viewport](../../com.aspose.threed/viewport) ini |
| [getRenderTarget()](#getRenderTarget--) | Mendapatkan target render yang membuat viewport ini. |
| [getZOrder()](#getZOrder--) | Mendapatkan urutan Z dari viewport. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArea(RelativeRectangle value)](#setArea-com.aspose.threed.RelativeRectangle-) | Mengatur area viewport dalam target render. |
| [setBackgroundColor(Vector3 value)](#setBackgroundColor-com.aspose.threed.Vector3-) | Mengatur warna latar belakang viewport. |
| [setDepthClear(float value)](#setDepthClear-float-) | Mengatur nilai kedalaman yang digunakan saat membersihkan viewport dengan bit penyangga kedalaman diatur. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Aktifkan atau nonaktifkan viewport ini. |
| [setFrustum(Frustum value)](#setFrustum-com.aspose.threed.Frustum-) | Mengatur kamera dari [Viewport](../../com.aspose.threed/viewport) ini |
| [setZOrder(int value)](#setZOrder-int-) | Mengatur urutan Z dari viewport. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### clone() {#clone--}
```
public Viewport clone()
```




**Returns:**
[Viewport](../../com.aspose.threed/viewport)
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
### getArea() {#getArea--}
```
public RelativeRectangle getArea()
```


Mendapatkan area viewport dalam target render.

**Returns:**
[RelativeRectangle](../../com.aspose.threed/relativerectangle) - the area of the viewport in render target.
### getBackgroundColor() {#getBackgroundColor--}
```
public Vector3 getBackgroundColor()
```


Mendapatkan warna latar belakang viewport.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the background color of the viewport.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDepthClear() {#getDepthClear--}
```
public float getDepthClear()
```


Mendapatkan nilai kedalaman yang digunakan saat membersihkan viewport dengan bit buffer kedalaman diatur.

**Returns:**
float - nilai kedalaman yang digunakan saat membersihkan viewport dengan bit penyangga kedalaman diatur.
### getEnabled() {#getEnabled--}
```
public boolean getEnabled()
```


Aktifkan atau nonaktifkan viewport ini.

**Returns:**
boolean - Aktifkan atau nonaktifkan viewport ini.
### getFrustum() {#getFrustum--}
```
public Frustum getFrustum()
```


Mendapatkan kamera dari [Viewport](../../com.aspose.threed/viewport) ini

**Returns:**
[Frustum](../../com.aspose.threed/frustum) - the camera of this [Viewport](../../com.aspose.threed/viewport)
### getRenderTarget() {#getRenderTarget--}
```
public IRenderTarget getRenderTarget()
```


Mendapatkan target render yang membuat viewport ini.

**Returns:**
[IRenderTarget](../../com.aspose.threed/irendertarget) - the render target that created this viewport.
### getZOrder() {#getZOrder--}
```
public int getZOrder()
```


Mendapatkan urutan Z dari viewport.

**Returns:**
int - urutan Z dari viewport.
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




### setArea(RelativeRectangle value) {#setArea-com.aspose.threed.RelativeRectangle-}
```
public void setArea(RelativeRectangle value)
```


Mengatur area viewport dalam target render.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | Nilai baru |

### setBackgroundColor(Vector3 value) {#setBackgroundColor-com.aspose.threed.Vector3-}
```
public void setBackgroundColor(Vector3 value)
```


Mengatur warna latar belakang viewport.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nilai baru |

### setDepthClear(float value) {#setDepthClear-float-}
```
public void setDepthClear(float value)
```


Mengatur nilai kedalaman yang digunakan saat membersihkan viewport dengan bit penyangga kedalaman diatur.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Nilai baru |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public void setEnabled(boolean value)
```


Aktifkan atau nonaktifkan viewport ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

### setFrustum(Frustum value) {#setFrustum-com.aspose.threed.Frustum-}
```
public void setFrustum(Frustum value)
```


Mengatur kamera dari [Viewport](../../com.aspose.threed/viewport) ini

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Frustum](../../com.aspose.threed/frustum) | Nilai baru |

### setZOrder(int value) {#setZOrder-int-}
```
public void setZOrder(int value)
```


Mengatur urutan Z dari viewport.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Nilai baru |

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

