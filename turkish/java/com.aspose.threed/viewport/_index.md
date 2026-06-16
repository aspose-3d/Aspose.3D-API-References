---
title: "Viewport"
second_title: "Aspose.3D for Java API Referansı"
description: "A  sahneyi renderlemek için en az bir viewport içerir."
type: docs
weight: 229
url: /tr/java/com.aspose.threed/viewport/
---

**Inheritance:**
java.lang.Object
```
public class Viewport
```

Bir [IRenderTarget](../../com.aspose.threed/irendertarget) sahneyi renderlemek için en az bir viewport içerir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [clone()](#clone--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArea()](#getArea--) | Viewport'un render hedefindeki alanını alır. |
| [getBackgroundColor()](#getBackgroundColor--) | Viewport'un arka plan rengini alır. |
| [getClass()](#getClass--) |  |
| [getDepthClear()](#getDepthClear--) | Derinlik tampon biti ayarlı iken viewport'u temizlerken kullanılan derinlik değerini alır. |
| [getEnabled()](#getEnabled--) | Bu viewport'u etkinleştir veya devre dışı bırak. |
| [getFrustum()](#getFrustum--) | Bu [Viewport](../../com.aspose.threed/viewport) kamerasını alır. |
| [getRenderTarget()](#getRenderTarget--) | Bu viewport'u oluşturan render hedefini alır. |
| [getZOrder()](#getZOrder--) | Görünüm penceresinin Z-sırasını alır. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArea(RelativeRectangle value)](#setArea-com.aspose.threed.RelativeRectangle-) | Görünüm penceresinin alanını render hedefinde ayarlar. |
| [setBackgroundColor(Vector3 value)](#setBackgroundColor-com.aspose.threed.Vector3-) | Görünüm penceresinin arka plan rengini ayarlar. |
| [setDepthClear(float value)](#setDepthClear-float-) | Derinlik tamponu biti ayarlı iken görünüm penceresini temizlerken kullanılan derinlik değerini ayarlar. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Bu viewport'u etkinleştir veya devre dışı bırak. |
| [setFrustum(Frustum value)](#setFrustum-com.aspose.threed.Frustum-) | Bu [Viewport](../../com.aspose.threed/viewport) kamerasını ayarlar. |
| [setZOrder(int value)](#setZOrder-int-) | Görünüm penceresinin Z-sırasını ayarlar. |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getArea() {#getArea--}
```
public RelativeRectangle getArea()
```


Viewport'un render hedefindeki alanını alır.

**Returns:**
[RelativeRectangle](../../com.aspose.threed/relativerectangle) - the area of the viewport in render target.
### getBackgroundColor() {#getBackgroundColor--}
```
public Vector3 getBackgroundColor()
```


Viewport'un arka plan rengini alır.

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


Derinlik tampon biti ayarlı iken viewport'u temizlerken kullanılan derinlik değerini alır.

**Returns:**
float - Derinlik tamponu biti ayarlı iken görünüm penceresini temizlerken kullanılan derinlik değeri.
### getEnabled() {#getEnabled--}
```
public boolean getEnabled()
```


Bu viewport'u etkinleştir veya devre dışı bırak.

**Returns:**
boolean - Bu görünüm penceresini etkinleştir veya devre dışı bırak.
### getFrustum() {#getFrustum--}
```
public Frustum getFrustum()
```


Bu [Viewport](../../com.aspose.threed/viewport) kamerasını alır.

**Returns:**
[Frustum](../../com.aspose.threed/frustum) - the camera of this [Viewport](../../com.aspose.threed/viewport)
### getRenderTarget() {#getRenderTarget--}
```
public IRenderTarget getRenderTarget()
```


Bu viewport'u oluşturan render hedefini alır.

**Returns:**
[IRenderTarget](../../com.aspose.threed/irendertarget) - the render target that created this viewport.
### getZOrder() {#getZOrder--}
```
public int getZOrder()
```


Görünüm penceresinin Z-sırasını alır.

**Returns:**
int - Görünüm penceresinin Z-sırası.
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


Görünüm penceresinin alanını render hedefinde ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | Yeni değer |

### setBackgroundColor(Vector3 value) {#setBackgroundColor-com.aspose.threed.Vector3-}
```
public void setBackgroundColor(Vector3 value)
```


Görünüm penceresinin arka plan rengini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Yeni değer |

### setDepthClear(float value) {#setDepthClear-float-}
```
public void setDepthClear(float value)
```


Derinlik tamponu biti ayarlı iken görünüm penceresini temizlerken kullanılan derinlik değerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Yeni değer |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public void setEnabled(boolean value)
```


Bu viewport'u etkinleştir veya devre dışı bırak.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setFrustum(Frustum value) {#setFrustum-com.aspose.threed.Frustum-}
```
public void setFrustum(Frustum value)
```


Bu [Viewport](../../com.aspose.threed/viewport) kamerasını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Frustum](../../com.aspose.threed/frustum) | Yeni değer |

### setZOrder(int value) {#setZOrder-int-}
```
public void setZOrder(int value)
```


Görünüm penceresinin Z-sırasını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Yeni değer |

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

