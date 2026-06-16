---
title: "RendererVariableManager"
second_title: "Aspose.3D for Java API Referansı"
description: "Bu sınıf, renderleme sırasında kullanılan değişkenleri yönetir"
type: docs
weight: 154
url: /tr/java/com.aspose.threed/renderervariablemanager/
---

**Inheritance:**
java.lang.Object
```
public abstract class RendererVariableManager
```

Bu sınıf, renderleme sırasında kullanılan değişkenleri yönetir
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCameraPosition()](#getCameraPosition--) | Kameranın dünya koordinat sistemindeki konumu. |
| [getClass()](#getClass--) |  |
| [getDepthBias()](#getDepthBias--) | Gölge haritalama için derinlik önyargısı, varsayılan değer 0.001'dir. |
| [getMatrixLightSpace()](#getMatrixLightSpace--) | Işık uzayı dönüşümü için matris. |
| [getMatrixProjection()](#getMatrixProjection--) | Projeksiyon dönüşümü için matris. |
| [getMatrixView()](#getMatrixView--) | Görünüm dönüşümü için matris. |
| [getMatrixViewProjection()](#getMatrixViewProjection--) | Görünüm ve projeksiyon dönüşümü için matris. |
| [getMatrixWorld()](#getMatrixWorld--) | Dünya dönüşümü için matris. |
| [getMatrixWorldNormal()](#getMatrixWorldNormal--) | Normal vektörünü nesneden dünya uzayına dönüştürmek için matris. |
| [getMatrixWorldViewProjection()](#getMatrixWorldViewProjection--) | Dünya görünümü ve projeksiyon dönüşümü için matris |
| [getShadowCaster()](#getShadowCaster--) | Gölge atan nesnenin dünya koordinat sistemindeki konumu |
| [getShadowmap()](#getShadowmap--) | Gölge haritalama için kullanılan derinlik dokusu |
| [getViewportSize()](#getViewportSize--) | Piksel cinsinden ölçülen görüntü alanının boyutu |
| [getWorldAmbient()](#getWorldAmbient--) | Görünüm alanında tanımlanan ortam rengi. |
| [getWorldTime()](#getWorldTime--) | Saniye cinsinden zaman |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCameraPosition(FVector3 value)](#setCameraPosition-com.aspose.threed.FVector3-) | Kameranın dünya koordinat sistemindeki konumu. |
| [setDepthBias(float value)](#setDepthBias-float-) | Gölge haritalama için derinlik önyargısı, varsayılan değer 0.001'dir. |
| [setMatrixLightSpace(FMatrix4 value)](#setMatrixLightSpace-com.aspose.threed.FMatrix4-) | Işık uzayı dönüşümü için matris. |
| [setMatrixProjection(FMatrix4 value)](#setMatrixProjection-com.aspose.threed.FMatrix4-) | Projeksiyon dönüşümü için matris. |
| [setMatrixView(FMatrix4 value)](#setMatrixView-com.aspose.threed.FMatrix4-) | Görünüm dönüşümü için matris. |
| [setShadowCaster(FVector3 value)](#setShadowCaster-com.aspose.threed.FVector3-) | Gölge atan nesnenin dünya koordinat sistemindeki konumu |
| [setShadowmap(ITextureUnit value)](#setShadowmap-com.aspose.threed.ITextureUnit-) | Gölge haritalama için kullanılan derinlik dokusu |
| [setViewportSize(FVector2 value)](#setViewportSize-com.aspose.threed.FVector2-) | Piksel cinsinden ölçülen görüntü alanının boyutu |
| [setWorldAmbient(FVector3 value)](#setWorldAmbient-com.aspose.threed.FVector3-) | Görünüm alanında tanımlanan ortam rengi. |
| [setWorldTime(float value)](#setWorldTime-float-) | Saniye cinsinden zaman |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getCameraPosition() {#getCameraPosition--}
```
public FVector3 getCameraPosition()
```


Kameranın dünya koordinat sistemindeki konumu.

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Camera's position in world coordinate system
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDepthBias() {#getDepthBias--}
```
public float getDepthBias()
```


Gölge haritalama için derinlik önyargısı, varsayılan değer 0.001'dir.

**Returns:**
float - Gölge haritalama için derinlik önyargısı, varsayılan değer 0.001
### getMatrixLightSpace() {#getMatrixLightSpace--}
```
public FMatrix4 getMatrixLightSpace()
```


Işık uzayı dönüşümü için matris.

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for light space transformation
### getMatrixProjection() {#getMatrixProjection--}
```
public FMatrix4 getMatrixProjection()
```


Projeksiyon dönüşümü için matris.

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for projection transformation
### getMatrixView() {#getMatrixView--}
```
public FMatrix4 getMatrixView()
```


Görünüm dönüşümü için matris.

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for view transformation
### getMatrixViewProjection() {#getMatrixViewProjection--}
```
public FMatrix4 getMatrixViewProjection()
```


Görünüm ve projeksiyon dönüşümü için matris.

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for view and projection transformation.
### getMatrixWorld() {#getMatrixWorld--}
```
public FMatrix4 getMatrixWorld()
```


Dünya dönüşümü için matris.

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for world transformation
### getMatrixWorldNormal() {#getMatrixWorldNormal--}
```
public FMatrix4 getMatrixWorldNormal()
```


Normal vektörünü nesneden dünya uzayına dönüştürmek için matris.

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for converting normal from object to world space.
### getMatrixWorldViewProjection() {#getMatrixWorldViewProjection--}
```
public FMatrix4 getMatrixWorldViewProjection()
```


Dünya görünümü ve projeksiyon dönüşümü için matris

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for world view and projection transformation
### getShadowCaster() {#getShadowCaster--}
```
public FVector3 getShadowCaster()
```


Gölge atan nesnenin dünya koordinat sistemindeki konumu

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Position of shadow caster in world coordinate system
### getShadowmap() {#getShadowmap--}
```
public ITextureUnit getShadowmap()
```


Gölge haritalama için kullanılan derinlik dokusu

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit) - The depth texture used for shadow mapping
### getViewportSize() {#getViewportSize--}
```
public FVector2 getViewportSize()
```


Piksel cinsinden ölçülen görüntü alanının boyutu

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - Size of viewport, measured in pixel
### getWorldAmbient() {#getWorldAmbient--}
```
public FVector3 getWorldAmbient()
```


Görünüm alanında tanımlanan ortam rengi.

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Ambient color defined in viewport.
### getWorldTime() {#getWorldTime--}
```
public float getWorldTime()
```


Saniye cinsinden zaman

**Returns:**
float - Saniye cinsinden zaman
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




### setCameraPosition(FVector3 value) {#setCameraPosition-com.aspose.threed.FVector3-}
```
public void setCameraPosition(FVector3 value)
```


Kameranın dünya koordinat sistemindeki konumu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | Yeni değer |

### setDepthBias(float value) {#setDepthBias-float-}
```
public void setDepthBias(float value)
```


Gölge haritalama için derinlik önyargısı, varsayılan değer 0.001'dir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Yeni değer |

### setMatrixLightSpace(FMatrix4 value) {#setMatrixLightSpace-com.aspose.threed.FMatrix4-}
```
public void setMatrixLightSpace(FMatrix4 value)
```


Işık uzayı dönüşümü için matris.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | Yeni değer |

### setMatrixProjection(FMatrix4 value) {#setMatrixProjection-com.aspose.threed.FMatrix4-}
```
public void setMatrixProjection(FMatrix4 value)
```


Projeksiyon dönüşümü için matris.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | Yeni değer |

### setMatrixView(FMatrix4 value) {#setMatrixView-com.aspose.threed.FMatrix4-}
```
public void setMatrixView(FMatrix4 value)
```


Görünüm dönüşümü için matris.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | Yeni değer |

### setShadowCaster(FVector3 value) {#setShadowCaster-com.aspose.threed.FVector3-}
```
public void setShadowCaster(FVector3 value)
```


Gölge atan nesnenin dünya koordinat sistemindeki konumu

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | Yeni değer |

### setShadowmap(ITextureUnit value) {#setShadowmap-com.aspose.threed.ITextureUnit-}
```
public void setShadowmap(ITextureUnit value)
```


Gölge haritalama için kullanılan derinlik dokusu

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ITextureUnit](../../com.aspose.threed/itextureunit) | Yeni değer |

### setViewportSize(FVector2 value) {#setViewportSize-com.aspose.threed.FVector2-}
```
public void setViewportSize(FVector2 value)
```


Piksel cinsinden ölçülen görüntü alanının boyutu

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [FVector2](../../com.aspose.threed/fvector2) | Yeni değer |

### setWorldAmbient(FVector3 value) {#setWorldAmbient-com.aspose.threed.FVector3-}
```
public void setWorldAmbient(FVector3 value)
```


Görünüm alanında tanımlanan ortam rengi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | Yeni değer |

### setWorldTime(float value) {#setWorldTime-float-}
```
public void setWorldTime(float value)
```


Saniye cinsinden zaman

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Yeni değer |

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

