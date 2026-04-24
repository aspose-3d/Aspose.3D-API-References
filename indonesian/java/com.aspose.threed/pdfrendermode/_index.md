---
title: PdfRenderMode
second_title: Referensi API Aspose.3D untuk Java
description: Mode render menentukan gaya di mana karya seni 3D dirender.
type: docs
weight: 289
url: /id/java/com.aspose.threed/pdfrendermode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PdfRenderMode extends Enum<PdfRenderMode>
```

Mode render menentukan gaya di mana karya seni 3D dirender.
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [BOUNDING_BOX](#BOUNDING-BOX) | Menampilkan tepi kotak pembatas setiap node, selaras dengan sumbu ruang koordinat lokal untuk node tersebut. |
| [HIDDEN_WIREFRAME](#HIDDEN-WIREFRAME) | Menampilkan tepi dalam satu warna, meskipun menghapus tepi yang menghadap ke belakang dan terhalang. |
| [ILLUSTRATION](#ILLUSTRATION) | Menampilkan tepi siluet dengan permukaan, menghapus garis yang terhalang. |
| [SHADED_ILLUSTRATION](#SHADED-ILLUSTRATION) | Menampilkan tepi siluet dengan permukaan yang diterangi dan bertekstur serta istilah emisif tambahan untuk menghapus area yang kurang cahaya pada karya seni. |
| [SHADED_VERTICES](#SHADED-VERTICES) | Menampilkan hanya verteks, meskipun menggunakan warna verteks mereka dan menerapkan pencahayaan. |
| [SHADED_WIREFRAME](#SHADED-WIREFRAME) | Menampilkan hanya tepi, meskipun menginterpolasi warnanya antara dua verteks dan menerapkan pencahayaan. |
| [SOLID](#SOLID) | Menampilkan bentuk geometris yang bertekstur dan diterangi. |
| [SOLID_OUTLINE](#SOLID-OUTLINE) | Menampilkan tepi siluet dengan permukaan yang diterangi dan bertekstur, menghapus garis yang terhalang. |
| [SOLID_WIREFRAME](#SOLID-WIREFRAME) | Menampilkan bentuk geometris (segitiga) yang bertekstur dan diterangi dengan tepi berwarna satu di atasnya. |
| [TRANSPARENT](#TRANSPARENT) | Menampilkan bentuk geometris (segitiga) yang bertekstur dan diterangi dengan tingkat transparansi tambahan. |
| [TRANSPARENT_BOUNDING_BOX](#TRANSPARENT-BOUNDING-BOX) | Menampilkan wajah kotak pembatas setiap node, selaras dengan sumbu ruang koordinat lokal untuk node tersebut, dengan tingkat transparansi tambahan. |
| [TRANSPARENT_BOUNDING_BOX_OUTLINE](#TRANSPARENT-BOUNDING-BOX-OUTLINE) | Menampilkan tepi dan wajah kotak pembatas setiap node, selaras dengan sumbu ruang koordinat lokal untuk node tersebut, dengan tingkat transparansi tambahan. |
| [TRANSPARENT_WIREFRAME](#TRANSPARENT-WIREFRAME) | Menampilkan bentuk geometris (segitiga) yang bertekstur dan diterangi dengan tingkat transparansi tambahan, dengan tepi tak tembus berwarna satu di atasnya. |
| [VERTICES](#VERTICES) | Menampilkan hanya verteks dalam satu warna. |
| [WIREFRAME](#WIREFRAME) | Menampilkan hanya tepi dalam satu warna. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BOUNDING_BOX {#BOUNDING-BOX}
```
public static final PdfRenderMode BOUNDING_BOX
```


Menampilkan tepi kotak pembatas setiap node, selaras dengan sumbu ruang koordinat lokal untuk node tersebut.

### HIDDEN_WIREFRAME {#HIDDEN-WIREFRAME}
```
public static final PdfRenderMode HIDDEN_WIREFRAME
```


Menampilkan tepi dalam satu warna, meskipun menghapus tepi yang menghadap ke belakang dan terhalang.

### ILLUSTRATION {#ILLUSTRATION}
```
public static final PdfRenderMode ILLUSTRATION
```


Menampilkan tepi siluet dengan permukaan, menghapus garis yang terhalang.

### SHADED_ILLUSTRATION {#SHADED-ILLUSTRATION}
```
public static final PdfRenderMode SHADED_ILLUSTRATION
```


Menampilkan tepi siluet dengan permukaan yang diterangi dan bertekstur serta istilah emisif tambahan untuk menghapus area yang kurang cahaya pada karya seni.

### SHADED_VERTICES {#SHADED-VERTICES}
```
public static final PdfRenderMode SHADED_VERTICES
```


Menampilkan hanya verteks, meskipun menggunakan warna verteks mereka dan menerapkan pencahayaan.

### SHADED_WIREFRAME {#SHADED-WIREFRAME}
```
public static final PdfRenderMode SHADED_WIREFRAME
```


Menampilkan hanya tepi, meskipun menginterpolasi warnanya antara dua verteks dan menerapkan pencahayaan.

### SOLID {#SOLID}
```
public static final PdfRenderMode SOLID
```


Menampilkan bentuk geometris yang bertekstur dan diterangi.

### SOLID_OUTLINE {#SOLID-OUTLINE}
```
public static final PdfRenderMode SOLID_OUTLINE
```


Menampilkan tepi siluet dengan permukaan yang diterangi dan bertekstur, menghapus garis yang terhalang.

### SOLID_WIREFRAME {#SOLID-WIREFRAME}
```
public static final PdfRenderMode SOLID_WIREFRAME
```


Menampilkan bentuk geometris (segitiga) yang bertekstur dan diterangi dengan tepi berwarna satu di atasnya.

### TRANSPARENT {#TRANSPARENT}
```
public static final PdfRenderMode TRANSPARENT
```


Menampilkan bentuk geometris (segitiga) yang bertekstur dan diterangi dengan tingkat transparansi tambahan.

### TRANSPARENT_BOUNDING_BOX {#TRANSPARENT-BOUNDING-BOX}
```
public static final PdfRenderMode TRANSPARENT_BOUNDING_BOX
```


Menampilkan wajah kotak pembatas setiap node, selaras dengan sumbu ruang koordinat lokal untuk node tersebut, dengan tingkat transparansi tambahan.

### TRANSPARENT_BOUNDING_BOX_OUTLINE {#TRANSPARENT-BOUNDING-BOX-OUTLINE}
```
public static final PdfRenderMode TRANSPARENT_BOUNDING_BOX_OUTLINE
```


Menampilkan tepi dan wajah kotak pembatas setiap node, selaras dengan sumbu ruang koordinat lokal untuk node tersebut, dengan tingkat transparansi tambahan.

### TRANSPARENT_WIREFRAME {#TRANSPARENT-WIREFRAME}
```
public static final PdfRenderMode TRANSPARENT_WIREFRAME
```


Menampilkan bentuk geometris (segitiga) yang bertekstur dan diterangi dengan tingkat transparansi tambahan, dengan tepi tak tembus berwarna satu di atasnya.

### VERTICES {#VERTICES}
```
public static final PdfRenderMode VERTICES
```


Menampilkan hanya verteks dalam satu warna.

### WIREFRAME {#WIREFRAME}
```
public static final PdfRenderMode WIREFRAME
```


Menampilkan hanya tepi dalam satu warna.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
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
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PdfRenderMode valueOf(String name)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String |  |

**Returns:**
[PdfRenderMode](../../com.aspose.threed/pdfrendermode)
### values() {#values--}
```
public static PdfRenderMode[] values()
```




**Returns:**
com.aspose.threed.PdfRenderMode[]
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

