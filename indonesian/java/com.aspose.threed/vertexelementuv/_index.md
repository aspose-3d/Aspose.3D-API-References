---
title: VertexElementUV
second_title: Referensi API Aspose.3D untuk Java
description: Mendefinisikan koordinat UV untuk komponen yang ditentukan.
type: docs
weight: 220
url: /id/java/com.aspose.threed/vertexelementuv/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.VertexElement](../../com.aspose.threed/vertexelement), [com.aspose.threed.VertexElementVector4](../../com.aspose.threed/vertexelementvector4)
```
public class VertexElementUV extends VertexElementVector4
```

Mendefinisikan koordinat UV untuk komponen yang ditentukan. Sebuah geometri dapat memiliki beberapa elemen [VertexElementUV](../../com.aspose.threed/vertexelementuv), dan masing‑masing memiliki [TextureMapping](../../com.aspose.threed/texturemapping)s yang berbeda.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [VertexElementUV()](#VertexElementUV--) | Menginisialisasi instance baru dari kelas [VertexElementUV](../../com.aspose.threed/vertexelementuv). |
| [VertexElementUV(TextureMapping textureMapping)](#VertexElementUV-com.aspose.threed.TextureMapping-) | Menginisialisasi instance baru dari kelas [VertexElementUV](../../com.aspose.threed/vertexelementuv). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [addData(Iterable<Vector2> data)](#addData-java.lang.Iterable-com.aspose.threed.Vector2--) | Tambahkan satu set [Vector2](../../com.aspose.threed/vector2) ke VertexElementUV.Data. |
| [addData2(Iterable<Vector3> data)](#addData2-java.lang.Iterable-com.aspose.threed.Vector3--) | Tambahkan satu set [Vector3](../../com.aspose.threed/vector3) ke VertexElementUV.Data. |
| [clear()](#clear--) | Menghapus semua elemen dari array direct dan indeks. |
| [clone(boolean withData)](#clone-boolean-) | Menduplikasi secara mendalam elemen vertex |
| [clone(boolean withDirect, boolean withIndice)](#clone-boolean-boolean-) |  |
| [copyTo(VertexElementVector4 target)](#copyTo-com.aspose.threed.VertexElementVector4-) | Menyalin data ke elemen yang ditentukan |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | Mendapatkan data vertex |
| [getIndices()](#getIndices--) | Mendapatkan data indeks |
| [getMappingMode()](#getMappingMode--) | Mendapatkan cara elemen dipetakan. |
| [getName()](#getName--) | Mendapatkan nama. |
| [getReferenceMode()](#getReferenceMode--) | Mendapatkan cara elemen direferensikan |
| [getVertexElementType()](#getVertexElementType--) | Mendapatkan tipe dari [VertexElement](../../com.aspose.threed/vertexelement) |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setData(Vector4[] data)](#setData-com.aspose.threed.Vector4---) | Muat data |
| [setIndices(int[] data)](#setIndices-int---) | Muat indeks |
| [setMappingMode(MappingMode value)](#setMappingMode-com.aspose.threed.MappingMode-) | Mengatur cara elemen dipetakan. |
| [setName(String value)](#setName-java.lang.String-) | Mengatur nama. |
| [setReferenceMode(ReferenceMode value)](#setReferenceMode-com.aspose.threed.ReferenceMode-) | Mengatur cara elemen direferensikan. |
| [toString()](#toString--) | Representasi string dari elemen vertex. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VertexElementUV() {#VertexElementUV--}
```
public VertexElementUV()
```


Menginisialisasi instance baru dari kelas [VertexElementUV](../../com.aspose.threed/vertexelementuv). Tipe pemetaan tekstur default adalah [TextureMapping.DIFFUSE](../../com.aspose.threed/texturemapping\#DIFFUSE)

### VertexElementUV(TextureMapping textureMapping) {#VertexElementUV-com.aspose.threed.TextureMapping-}
```
public VertexElementUV(TextureMapping textureMapping)
```


Menginisialisasi instance baru dari kelas [VertexElementUV](../../com.aspose.threed/vertexelementuv).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| textureMapping | [TextureMapping](../../com.aspose.threed/texturemapping) | Tipe pemetaan tekstur. |

### addData(Iterable<Vector2> data) {#addData-java.lang.Iterable-com.aspose.threed.Vector2--}
```
public void addData(Iterable<Vector2> data)
```


Tambahkan satu set [Vector2](../../com.aspose.threed/vector2) ke VertexElementUV.Data. Ini adalah pintasan, metode ini akan mengonversi [Vector2](../../com.aspose.threed/vector2) menjadi [Vector4](../../com.aspose.threed/vector4) dengan z menjadi 0 dan w menjadi 0.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | java.lang.Iterable<com.aspose.threed.Vector2> |  |

### addData2(Iterable<Vector3> data) {#addData2-java.lang.Iterable-com.aspose.threed.Vector3--}
```
public void addData2(Iterable<Vector3> data)
```


Tambahkan satu set [Vector3](../../com.aspose.threed/vector3) ke VertexElementUV.Data. Ini adalah pintasan, metode ini akan mengonversi [Vector3](../../com.aspose.threed/vector3) menjadi [Vector4](../../com.aspose.threed/vector4) dengan w menjadi 0.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | java.lang.Iterable<com.aspose.threed.Vector3> |  |

### clear() {#clear--}
```
public void clear()
```


Menghapus semua elemen dari array direct dan indeks.

### clone(boolean withData) {#clone-boolean-}
```
public VertexElement clone(boolean withData)
```


Menduplikasi secara mendalam elemen vertex

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| withData | boolean | Menduplikasi vertex dengan array direct dan index |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement)
### clone(boolean withDirect, boolean withIndice) {#clone-boolean-boolean-}
```
public VertexElement clone(boolean withDirect, boolean withIndice)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| withDirect | boolean |  |
| withIndice | boolean |  |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement)
### copyTo(VertexElementVector4 target) {#copyTo-com.aspose.threed.VertexElementVector4-}
```
public void copyTo(VertexElementVector4 target)
```


Menyalin data ke elemen yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| target | [VertexElementVector4](../../com.aspose.threed/vertexelementvector4) | Target. |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getData() {#getData--}
```
public List<Vector4> getData()
```


Mendapatkan data vertex

**Returns:**
java.util.List<com.aspose.threed.Vector4> - data vertex
### getIndices() {#getIndices--}
```
public List<Integer> getIndices()
```


Mendapatkan data indeks

**Returns:**
java.util.List<java.lang.Integer> - data indeks
### getMappingMode() {#getMappingMode--}
```
public MappingMode getMappingMode()
```


Mendapatkan cara elemen dipetakan.

**Returns:**
[MappingMode](../../com.aspose.threed/mappingmode) - how the element is mapped.
### getName() {#getName--}
```
public String getName()
```


Mendapatkan nama.

**Returns:**
java.lang.String - nama.
### getReferenceMode() {#getReferenceMode--}
```
public ReferenceMode getReferenceMode()
```


Mendapatkan cara elemen direferensikan

**Returns:**
[ReferenceMode](../../com.aspose.threed/referencemode) - how the element is referenced.
### getVertexElementType() {#getVertexElementType--}
```
public VertexElementType getVertexElementType()
```


Mendapatkan tipe dari [VertexElement](../../com.aspose.threed/vertexelement)

**Returns:**
[VertexElementType](../../com.aspose.threed/vertexelementtype) - the type of the [VertexElement](../../com.aspose.threed/vertexelement)
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




### setData(Vector4[] data) {#setData-com.aspose.threed.Vector4---}
```
public void setData(Vector4[] data)
```


Muat data

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | [Vector4\[\]](../../com.aspose.threed/vector4) |  |

### setIndices(int[] data) {#setIndices-int---}
```
public void setIndices(int[] data)
```


Muat indeks

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | int[] |  |

### setMappingMode(MappingMode value) {#setMappingMode-com.aspose.threed.MappingMode-}
```
public void setMappingMode(MappingMode value)
```


Mengatur cara elemen dipetakan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [MappingMode](../../com.aspose.threed/mappingmode) | Nilai baru |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Mengatur nama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nilai baru |

### setReferenceMode(ReferenceMode value) {#setReferenceMode-com.aspose.threed.ReferenceMode-}
```
public void setReferenceMode(ReferenceMode value)
```


Mengatur cara elemen direferensikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ReferenceMode](../../com.aspose.threed/referencemode) | Nilai baru |

### toString() {#toString--}
```
public String toString()
```


Representasi string dari elemen vertex.

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

