---
title: RendererVariableManager
second_title: Referensi API Aspose.3D untuk Java
description: Kelas ini mengelola variabel yang digunakan dalam rendering
type: docs
weight: 154
url: /id/java/com.aspose.threed/renderervariablemanager/
---

**Inheritance:**
java.lang.Object
```
public abstract class RendererVariableManager
```

Kelas ini mengelola variabel yang digunakan dalam rendering
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCameraPosition()](#getCameraPosition--) | Posisi kamera dalam sistem koordinat dunia |
| [getClass()](#getClass--) |  |
| [getDepthBias()](#getDepthBias--) | Bias kedalaman untuk pemetaan bayangan, nilai default adalah 0.001 |
| [getMatrixLightSpace()](#getMatrixLightSpace--) | Matriks untuk transformasi ruang cahaya |
| [getMatrixProjection()](#getMatrixProjection--) | Matriks untuk transformasi proyeksi |
| [getMatrixView()](#getMatrixView--) | Matriks untuk transformasi tampilan |
| [getMatrixViewProjection()](#getMatrixViewProjection--) | Matriks untuk transformasi tampilan dan proyeksi. |
| [getMatrixWorld()](#getMatrixWorld--) | Matriks untuk transformasi dunia |
| [getMatrixWorldNormal()](#getMatrixWorldNormal--) | Matriks untuk mengonversi normal dari objek ke ruang dunia. |
| [getMatrixWorldViewProjection()](#getMatrixWorldViewProjection--) | Matriks untuk tampilan dunia dan transformasi proyeksi |
| [getShadowCaster()](#getShadowCaster--) | Posisi pembuat bayangan dalam sistem koordinat dunia |
| [getShadowmap()](#getShadowmap--) | Tekstur kedalaman yang digunakan untuk pemetaan bayangan |
| [getViewportSize()](#getViewportSize--) | Ukuran viewport, diukur dalam piksel |
| [getWorldAmbient()](#getWorldAmbient--) | Warna ambient yang didefinisikan dalam viewport. |
| [getWorldTime()](#getWorldTime--) | Waktu dalam detik |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCameraPosition(FVector3 value)](#setCameraPosition-com.aspose.threed.FVector3-) | Posisi kamera dalam sistem koordinat dunia |
| [setDepthBias(float value)](#setDepthBias-float-) | Bias kedalaman untuk pemetaan bayangan, nilai default adalah 0.001 |
| [setMatrixLightSpace(FMatrix4 value)](#setMatrixLightSpace-com.aspose.threed.FMatrix4-) | Matriks untuk transformasi ruang cahaya |
| [setMatrixProjection(FMatrix4 value)](#setMatrixProjection-com.aspose.threed.FMatrix4-) | Matriks untuk transformasi proyeksi |
| [setMatrixView(FMatrix4 value)](#setMatrixView-com.aspose.threed.FMatrix4-) | Matriks untuk transformasi tampilan |
| [setShadowCaster(FVector3 value)](#setShadowCaster-com.aspose.threed.FVector3-) | Posisi pembuat bayangan dalam sistem koordinat dunia |
| [setShadowmap(ITextureUnit value)](#setShadowmap-com.aspose.threed.ITextureUnit-) | Tekstur kedalaman yang digunakan untuk pemetaan bayangan |
| [setViewportSize(FVector2 value)](#setViewportSize-com.aspose.threed.FVector2-) | Ukuran viewport, diukur dalam piksel |
| [setWorldAmbient(FVector3 value)](#setWorldAmbient-com.aspose.threed.FVector3-) | Warna ambient yang didefinisikan dalam viewport. |
| [setWorldTime(float value)](#setWorldTime-float-) | Waktu dalam detik |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getCameraPosition() {#getCameraPosition--}
```
public FVector3 getCameraPosition()
```


Posisi kamera dalam sistem koordinat dunia

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


Bias kedalaman untuk pemetaan bayangan, nilai default adalah 0.001

**Returns:**
float - Bias kedalaman untuk pemetaan bayangan, nilai default adalah 0.001
### getMatrixLightSpace() {#getMatrixLightSpace--}
```
public FMatrix4 getMatrixLightSpace()
```


Matriks untuk transformasi ruang cahaya

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for light space transformation
### getMatrixProjection() {#getMatrixProjection--}
```
public FMatrix4 getMatrixProjection()
```


Matriks untuk transformasi proyeksi

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for projection transformation
### getMatrixView() {#getMatrixView--}
```
public FMatrix4 getMatrixView()
```


Matriks untuk transformasi tampilan

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for view transformation
### getMatrixViewProjection() {#getMatrixViewProjection--}
```
public FMatrix4 getMatrixViewProjection()
```


Matriks untuk transformasi tampilan dan proyeksi.

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for view and projection transformation.
### getMatrixWorld() {#getMatrixWorld--}
```
public FMatrix4 getMatrixWorld()
```


Matriks untuk transformasi dunia

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for world transformation
### getMatrixWorldNormal() {#getMatrixWorldNormal--}
```
public FMatrix4 getMatrixWorldNormal()
```


Matriks untuk mengonversi normal dari objek ke ruang dunia.

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for converting normal from object to world space.
### getMatrixWorldViewProjection() {#getMatrixWorldViewProjection--}
```
public FMatrix4 getMatrixWorldViewProjection()
```


Matriks untuk tampilan dunia dan transformasi proyeksi

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for world view and projection transformation
### getShadowCaster() {#getShadowCaster--}
```
public FVector3 getShadowCaster()
```


Posisi pembuat bayangan dalam sistem koordinat dunia

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Position of shadow caster in world coordinate system
### getShadowmap() {#getShadowmap--}
```
public ITextureUnit getShadowmap()
```


Tekstur kedalaman yang digunakan untuk pemetaan bayangan

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit) - The depth texture used for shadow mapping
### getViewportSize() {#getViewportSize--}
```
public FVector2 getViewportSize()
```


Ukuran viewport, diukur dalam piksel

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - Size of viewport, measured in pixel
### getWorldAmbient() {#getWorldAmbient--}
```
public FVector3 getWorldAmbient()
```


Warna ambient yang didefinisikan dalam viewport.

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Ambient color defined in viewport.
### getWorldTime() {#getWorldTime--}
```
public float getWorldTime()
```


Waktu dalam detik

**Returns:**
float - Waktu dalam detik
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


Posisi kamera dalam sistem koordinat dunia

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | Nilai baru |

### setDepthBias(float value) {#setDepthBias-float-}
```
public void setDepthBias(float value)
```


Bias kedalaman untuk pemetaan bayangan, nilai default adalah 0.001

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Nilai baru |

### setMatrixLightSpace(FMatrix4 value) {#setMatrixLightSpace-com.aspose.threed.FMatrix4-}
```
public void setMatrixLightSpace(FMatrix4 value)
```


Matriks untuk transformasi ruang cahaya

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | Nilai baru |

### setMatrixProjection(FMatrix4 value) {#setMatrixProjection-com.aspose.threed.FMatrix4-}
```
public void setMatrixProjection(FMatrix4 value)
```


Matriks untuk transformasi proyeksi

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | Nilai baru |

### setMatrixView(FMatrix4 value) {#setMatrixView-com.aspose.threed.FMatrix4-}
```
public void setMatrixView(FMatrix4 value)
```


Matriks untuk transformasi tampilan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | Nilai baru |

### setShadowCaster(FVector3 value) {#setShadowCaster-com.aspose.threed.FVector3-}
```
public void setShadowCaster(FVector3 value)
```


Posisi pembuat bayangan dalam sistem koordinat dunia

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | Nilai baru |

### setShadowmap(ITextureUnit value) {#setShadowmap-com.aspose.threed.ITextureUnit-}
```
public void setShadowmap(ITextureUnit value)
```


Tekstur kedalaman yang digunakan untuk pemetaan bayangan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ITextureUnit](../../com.aspose.threed/itextureunit) | Nilai baru |

### setViewportSize(FVector2 value) {#setViewportSize-com.aspose.threed.FVector2-}
```
public void setViewportSize(FVector2 value)
```


Ukuran viewport, diukur dalam piksel

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [FVector2](../../com.aspose.threed/fvector2) | Nilai baru |

### setWorldAmbient(FVector3 value) {#setWorldAmbient-com.aspose.threed.FVector3-}
```
public void setWorldAmbient(FVector3 value)
```


Warna ambient yang didefinisikan dalam viewport.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | Nilai baru |

### setWorldTime(float value) {#setWorldTime-float-}
```
public void setWorldTime(float value)
```


Waktu dalam detik

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Nilai baru |

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

