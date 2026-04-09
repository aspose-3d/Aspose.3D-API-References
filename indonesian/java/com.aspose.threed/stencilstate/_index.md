---
title: StencilState
second_title: Referensi API Aspose.3D untuk Java
description: Status stencil per wajah.
type: docs
weight: 175
url: /id/java/com.aspose.threed/stencilstate/
---

**Inheritance:**
java.lang.Object
```
public class StencilState
```

Status stencil per wajah.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan objek yang ditentukan. |
| [getClass()](#getClass--) |  |
| [getCompare()](#getCompare--) | Mendapatkan fungsi perbandingan yang digunakan dalam uji stensil |
| [getDepthFailAction()](#getDepthFailAction--) | Mendapatkan aksi stensil ketika uji stensil lulus tetapi uji kedalaman gagal. |
| [getFailAction()](#getFailAction--) | Mendapatkan aksi stensil ketika uji stensil gagal. |
| [getPassAction()](#getPassAction--) | Mendapatkan aksi stensil ketika baik uji stensil maupun uji kedalaman lulus. |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk instance ini. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompare(CompareFunction value)](#setCompare-com.aspose.threed.CompareFunction-) | Mengatur fungsi perbandingan yang digunakan dalam uji stensil |
| [setDepthFailAction(StencilAction value)](#setDepthFailAction-com.aspose.threed.StencilAction-) | Mengatur aksi stensil ketika uji stensil lulus tetapi uji kedalaman gagal. |
| [setFailAction(StencilAction value)](#setFailAction-com.aspose.threed.StencilAction-) | Mengatur aksi stensil ketika uji stensil gagal. |
| [setPassAction(StencilAction value)](#setPassAction-com.aspose.threed.StencilAction-) | Mengatur aksi stensil ketika baik uji stensil maupun uji kedalaman lulus. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCompare() {#getCompare--}
```
public CompareFunction getCompare()
```


Mendapatkan fungsi perbandingan yang digunakan dalam uji stensil

**Returns:**
[CompareFunction](../../com.aspose.threed/comparefunction) - the compare function used in stencil test
### getDepthFailAction() {#getDepthFailAction--}
```
public StencilAction getDepthFailAction()
```


Mendapatkan aksi stensil ketika uji stensil lulus tetapi uji kedalaman gagal.

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction) - the stencil action when stencil test pass but depth test fails.
### getFailAction() {#getFailAction--}
```
public StencilAction getFailAction()
```


Mendapatkan aksi stensil ketika uji stensil gagal.

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction) - the stencil action when stencil test fails.
### getPassAction() {#getPassAction--}
```
public StencilAction getPassAction()
```


Mendapatkan aksi stensil ketika baik uji stensil maupun uji kedalaman lulus.

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction) - the stencil action when both stencil test and depth test passes.
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




### setCompare(CompareFunction value) {#setCompare-com.aspose.threed.CompareFunction-}
```
public void setCompare(CompareFunction value)
```


Mengatur fungsi perbandingan yang digunakan dalam uji stensil

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [CompareFunction](../../com.aspose.threed/comparefunction) | Nilai baru |

### setDepthFailAction(StencilAction value) {#setDepthFailAction-com.aspose.threed.StencilAction-}
```
public void setDepthFailAction(StencilAction value)
```


Mengatur aksi stensil ketika uji stensil lulus tetapi uji kedalaman gagal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [StencilAction](../../com.aspose.threed/stencilaction) | Nilai baru |

### setFailAction(StencilAction value) {#setFailAction-com.aspose.threed.StencilAction-}
```
public void setFailAction(StencilAction value)
```


Mengatur aksi stensil ketika uji stensil gagal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [StencilAction](../../com.aspose.threed/stencilaction) | Nilai baru |

### setPassAction(StencilAction value) {#setPassAction-com.aspose.threed.StencilAction-}
```
public void setPassAction(StencilAction value)
```


Mengatur aksi stensil ketika baik uji stensil maupun uji kedalaman lulus.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [StencilAction](../../com.aspose.threed/stencilaction) | Nilai baru |

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

