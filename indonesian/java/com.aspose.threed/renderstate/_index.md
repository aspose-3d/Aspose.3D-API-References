---
title: "RenderState"
second_title: "Referensi API Aspose.3D untuk Java"
description: "Status render untuk membangun pipeline. Perubahan yang dibuat pada status render tidak akan memengaruhi instance pipeline yang dibuat."
type: docs
weight: 151
url: /id/java/com.aspose.threed/renderstate/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable, java.lang.Comparable
```
public class RenderState implements Closeable, Comparable<RenderState>
```

Status render untuk membangun pipeline. Perubahan yang dibuat pada status render tidak akan memengaruhi instance pipeline yang dibuat.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [RenderState()](#RenderState--) | Konstruktor dari [RenderState](../../com.aspose.threed/renderstate) |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [close()](#close--) | Buang [RenderState](../../com.aspose.threed/renderstate) dan lepaskan semua sumber daya internal. |
| [compareTo(RenderState other)](#compareTo-com.aspose.threed.RenderState-) | Bandingkan keadaan render dengan instance lain. |
| [equals(Object obj)](#equals-java.lang.Object-) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan objek yang ditentukan. |
| [getBlend()](#getBlend--) | Aktifkan atau nonaktifkan pencampuran fragmen. |
| [getBlendColor()](#getBlendColor--) | Mendapatkan warna pencampuran yang digunakan dalam [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) |
| [getClass()](#getClass--) |  |
| [getCullFace()](#getCullFace--) | Aktifkan atau nonaktifkan pemotongan muka. |
| [getCullFaceMode()](#getCullFaceMode--) | Mendapatkan muka mana yang akan dipotong. |
| [getDepthFunction()](#getDepthFunction--) | Mendapatkan fungsi perbandingan yang digunakan dalam pengujian kedalaman. |
| [getDepthMask()](#getDepthMask--) | Aktifkan atau nonaktifkan penulisan kedalaman. |
| [getDepthTest()](#getDepthTest--) | Aktifkan atau nonaktifkan pengujian kedalaman. |
| [getDestinationBlendFactor()](#getDestinationBlendFactor--) | Mendapatkan cara warna dicampur. |
| [getFrontFace()](#getFrontFace--) | Mendapatkan urutan mana yang menjadi muka depan. |
| [getPolygonMode()](#getPolygonMode--) | Mendapatkan mode render poligon. |
| [getScissorTest()](#getScissorTest--) | Aktifkan atau nonaktifkan pengujian gunting. |
| [getSourceBlendFactor()](#getSourceBlendFactor--) | Mendapatkan cara warna dicampur. |
| [getStencilBackFace()](#getStencilBackFace--) | Mendapatkan status stensil untuk muka belakang. |
| [getStencilFrontFace()](#getStencilFrontFace--) | Mendapatkan status stensil untuk muka depan. |
| [getStencilMask()](#getStencilMask--) | Mendapatkan masker yang di-AND-kan dengan nilai referensi dan nilai stensil yang disimpan ketika pengujian selesai. |
| [getStencilReference()](#getStencilReference--) | Mendapatkan nilai referensi untuk pengujian stensil. |
| [getStencilTest()](#getStencilTest--) | Aktifkan atau nonaktifkan pengujian stensil. |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk instance ini. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlend(boolean value)](#setBlend-boolean-) | Aktifkan atau nonaktifkan pencampuran fragmen. |
| [setBlendColor(FVector4 value)](#setBlendColor-com.aspose.threed.FVector4-) | Mengatur warna pencampuran yang digunakan dalam [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) |
| [setCullFace(boolean value)](#setCullFace-boolean-) | Aktifkan atau nonaktifkan pemotongan muka. |
| [setCullFaceMode(int value)](#setCullFaceMode-int-) | Mengatur muka mana yang akan dipotong. |
| [setDepthFunction(CompareFunction value)](#setDepthFunction-com.aspose.threed.CompareFunction-) | Mengatur fungsi perbandingan yang digunakan dalam pengujian kedalaman. |
| [setDepthMask(boolean value)](#setDepthMask-boolean-) | Aktifkan atau nonaktifkan penulisan kedalaman. |
| [setDepthTest(boolean value)](#setDepthTest-boolean-) | Aktifkan atau nonaktifkan pengujian kedalaman. |
| [setDestinationBlendFactor(BlendFactor value)](#setDestinationBlendFactor-com.aspose.threed.BlendFactor-) | Mengatur cara warna dicampur. |
| [setFrontFace(FrontFace value)](#setFrontFace-com.aspose.threed.FrontFace-) | Mengatur urutan mana yang menjadi muka depan. |
| [setPolygonMode(PolygonMode value)](#setPolygonMode-com.aspose.threed.PolygonMode-) | Mengatur mode render poligon. |
| [setScissorTest(boolean value)](#setScissorTest-boolean-) | Aktifkan atau nonaktifkan pengujian gunting. |
| [setSourceBlendFactor(BlendFactor value)](#setSourceBlendFactor-com.aspose.threed.BlendFactor-) | Mengatur cara warna dicampur. |
| [setStencilMask(int value)](#setStencilMask-int-) | Mengatur masker yang di-AND dengan nilai referensi dan nilai stencil yang disimpan ketika pengujian selesai. |
| [setStencilReference(int value)](#setStencilReference-int-) | Mengatur nilai referensi untuk pengujian stencil. |
| [setStencilTest(boolean value)](#setStencilTest-boolean-) | Aktifkan atau nonaktifkan pengujian stensil. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RenderState() {#RenderState--}
```
public RenderState()
```


Konstruktor dari [RenderState](../../com.aspose.threed/renderstate)

### close() {#close--}
```
public void close()
```


Buang [RenderState](../../com.aspose.threed/renderstate) dan lepaskan semua sumber daya internal.

### compareTo(RenderState other) {#compareTo-com.aspose.threed.RenderState-}
```
public int compareTo(RenderState other)
```


Bandingkan keadaan render dengan instance lain.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | [RenderState](../../com.aspose.threed/renderstate) | Keadaan render lain untuk dibandingkan |

**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan objek yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getBlend() {#getBlend--}
```
public boolean getBlend()
```


Aktifkan atau nonaktifkan pencampuran fragmen.

**Returns:**
boolean - Aktifkan atau nonaktifkan pencampuran fragmen.
### getBlendColor() {#getBlendColor--}
```
public FVector4 getBlendColor()
```


Mendapatkan warna pencampuran yang digunakan dalam [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR)

**Returns:**
[FVector4](../../com.aspose.threed/fvector4) - the blend color where used in [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCullFace() {#getCullFace--}
```
public boolean getCullFace()
```


Aktifkan atau nonaktifkan pemotongan muka.

**Returns:**
boolean - Aktifkan atau nonaktifkan cull face
### getCullFaceMode() {#getCullFaceMode--}
```
public int getCullFaceMode()
```


Mendapatkan muka mana yang akan dipotong.

**Returns:**
int - wajah mana yang akan di-cull.
### getDepthFunction() {#getDepthFunction--}
```
public CompareFunction getDepthFunction()
```


Mendapatkan fungsi perbandingan yang digunakan dalam pengujian kedalaman.

**Returns:**
[CompareFunction](../../com.aspose.threed/comparefunction) - the compare function used in depth test
### getDepthMask() {#getDepthMask--}
```
public boolean getDepthMask()
```


Aktifkan atau nonaktifkan penulisan kedalaman.

**Returns:**
boolean - Aktifkan atau nonaktifkan penulisan kedalaman.
### getDepthTest() {#getDepthTest--}
```
public boolean getDepthTest()
```


Aktifkan atau nonaktifkan pengujian kedalaman.

**Returns:**
boolean - Aktifkan atau nonaktifkan pengujian kedalaman.
### getDestinationBlendFactor() {#getDestinationBlendFactor--}
```
public BlendFactor getDestinationBlendFactor()
```


Mendapatkan cara warna dicampur.

**Returns:**
[BlendFactor](../../com.aspose.threed/blendfactor) - how the color is blended.
### getFrontFace() {#getFrontFace--}
```
public FrontFace getFrontFace()
```


Mendapatkan urutan mana yang menjadi muka depan.

**Returns:**
[FrontFace](../../com.aspose.threed/frontface) - which order is front face.
### getPolygonMode() {#getPolygonMode--}
```
public PolygonMode getPolygonMode()
```


Mendapatkan mode render poligon.

**Returns:**
[PolygonMode](../../com.aspose.threed/polygonmode) - the polygon's render mode.
### getScissorTest() {#getScissorTest--}
```
public boolean getScissorTest()
```


Aktifkan atau nonaktifkan pengujian gunting.

**Returns:**
boolean - Aktifkan atau nonaktifkan scissor test
### getSourceBlendFactor() {#getSourceBlendFactor--}
```
public BlendFactor getSourceBlendFactor()
```


Mendapatkan cara warna dicampur.

**Returns:**
[BlendFactor](../../com.aspose.threed/blendfactor) - how the color is blended.
### getStencilBackFace() {#getStencilBackFace--}
```
public StencilState getStencilBackFace()
```


Mendapatkan status stensil untuk muka belakang.

**Returns:**
[StencilState](../../com.aspose.threed/stencilstate) - the stencil state for back face.
### getStencilFrontFace() {#getStencilFrontFace--}
```
public StencilState getStencilFrontFace()
```


Mendapatkan status stensil untuk muka depan.

**Returns:**
[StencilState](../../com.aspose.threed/stencilstate) - the stencil state for front face.
### getStencilMask() {#getStencilMask--}
```
public int getStencilMask()
```


Mendapatkan masker yang di-AND-kan dengan nilai referensi dan nilai stensil yang disimpan ketika pengujian selesai.

**Returns:**
int - masker yang di-AND dengan nilai referensi dan nilai stencil yang disimpan ketika pengujian selesai.
### getStencilReference() {#getStencilReference--}
```
public int getStencilReference()
```


Mendapatkan nilai referensi untuk pengujian stensil.

**Returns:**
int - nilai referensi untuk pengujian stencil.
### getStencilTest() {#getStencilTest--}
```
public boolean getStencilTest()
```


Aktifkan atau nonaktifkan pengujian stensil.

**Returns:**
boolean - Aktifkan atau nonaktifkan pengujian stencil.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan kode hash untuk instance ini.

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




### setBlend(boolean value) {#setBlend-boolean-}
```
public void setBlend(boolean value)
```


Aktifkan atau nonaktifkan pencampuran fragmen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

### setBlendColor(FVector4 value) {#setBlendColor-com.aspose.threed.FVector4-}
```
public void setBlendColor(FVector4 value)
```


Mengatur warna pencampuran yang digunakan dalam [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [FVector4](../../com.aspose.threed/fvector4) | Nilai baru |

### setCullFace(boolean value) {#setCullFace-boolean-}
```
public void setCullFace(boolean value)
```


Aktifkan atau nonaktifkan pemotongan muka.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

### setCullFaceMode(int value) {#setCullFaceMode-int-}
```
public void setCullFaceMode(int value)
```


Mengatur muka mana yang akan dipotong.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Nilai baru |

### setDepthFunction(CompareFunction value) {#setDepthFunction-com.aspose.threed.CompareFunction-}
```
public void setDepthFunction(CompareFunction value)
```


Mengatur fungsi perbandingan yang digunakan dalam pengujian kedalaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [CompareFunction](../../com.aspose.threed/comparefunction) | Nilai baru |

### setDepthMask(boolean value) {#setDepthMask-boolean-}
```
public void setDepthMask(boolean value)
```


Aktifkan atau nonaktifkan penulisan kedalaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

### setDepthTest(boolean value) {#setDepthTest-boolean-}
```
public void setDepthTest(boolean value)
```


Aktifkan atau nonaktifkan pengujian kedalaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

### setDestinationBlendFactor(BlendFactor value) {#setDestinationBlendFactor-com.aspose.threed.BlendFactor-}
```
public void setDestinationBlendFactor(BlendFactor value)
```


Mengatur cara warna dicampur.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [BlendFactor](../../com.aspose.threed/blendfactor) | Nilai baru |

### setFrontFace(FrontFace value) {#setFrontFace-com.aspose.threed.FrontFace-}
```
public void setFrontFace(FrontFace value)
```


Mengatur urutan mana yang menjadi muka depan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [FrontFace](../../com.aspose.threed/frontface) | Nilai baru |

### setPolygonMode(PolygonMode value) {#setPolygonMode-com.aspose.threed.PolygonMode-}
```
public void setPolygonMode(PolygonMode value)
```


Mengatur mode render poligon.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [PolygonMode](../../com.aspose.threed/polygonmode) | Nilai baru |

### setScissorTest(boolean value) {#setScissorTest-boolean-}
```
public void setScissorTest(boolean value)
```


Aktifkan atau nonaktifkan pengujian gunting.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

### setSourceBlendFactor(BlendFactor value) {#setSourceBlendFactor-com.aspose.threed.BlendFactor-}
```
public void setSourceBlendFactor(BlendFactor value)
```


Mengatur cara warna dicampur.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [BlendFactor](../../com.aspose.threed/blendfactor) | Nilai baru |

### setStencilMask(int value) {#setStencilMask-int-}
```
public void setStencilMask(int value)
```


Mengatur masker yang di-AND dengan nilai referensi dan nilai stencil yang disimpan ketika pengujian selesai.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Nilai baru |

### setStencilReference(int value) {#setStencilReference-int-}
```
public void setStencilReference(int value)
```


Mengatur nilai referensi untuk pengujian stencil.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Nilai baru |

### setStencilTest(boolean value) {#setStencilTest-boolean-}
```
public void setStencilTest(boolean value)
```


Aktifkan atau nonaktifkan pengujian stensil.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

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

