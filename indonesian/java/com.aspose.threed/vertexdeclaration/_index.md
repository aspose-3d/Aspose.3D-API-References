---
title: VertexDeclaration
second_title: Referensi API Aspose.3D untuk Java
description: Deklarasi struktur vertex yang didefinisikan secara khusus
type: docs
weight: 206
url: /id/java/com.aspose.threed/vertexdeclaration/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable, java.lang.Comparable
```
public final class VertexDeclaration implements Iterable<VertexField>, Comparable<VertexDeclaration>
```

Deklarasi struktur vertex yang didefinisikan secara khusus
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [VertexDeclaration()](#VertexDeclaration--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [addField(int dataType, VertexFieldSemantic semantic)](#addField-int-com.aspose.threed.VertexFieldSemantic-) | Tambahkan bidang vertex baru |
| [addField(int dataType, VertexFieldSemantic semantic, int index)](#addField-int-com.aspose.threed.VertexFieldSemantic-int-) | Tambahkan bidang vertex baru |
| [addField(int dataType, VertexFieldSemantic semantic, int index, String alias)](#addField-int-com.aspose.threed.VertexFieldSemantic-int-java.lang.String-) | Tambahkan bidang vertex baru |
| [clear()](#clear--) | Bersihkan semua bidang. |
| [compareTo(VertexDeclaration other)](#compareTo-com.aspose.threed.VertexDeclaration-) | Membandingkan instance ini dengan objek yang ditentukan dan mengembalikan indikasi nilai relatif mereka. |
| [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah instance ini dan objek yang ditentukan, yang juga harus berupa objek [VertexDeclaration](../../com.aspose.threed/vertexdeclaration), memiliki nilai yang sama. |
| [fromGeometry(Geometry geometry, boolean useFloat)](#fromGeometry-com.aspose.threed.Geometry-boolean-) | Buat sebuah [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) berdasarkan tata letak [Geometry](../../com.aspose.threed/geometry). |
| [get(int index)](#get-int-) | Mendapatkan [VertexField](../../com.aspose.threed/vertexfield) berdasarkan indeks |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Mendapatkan jumlah semua bidang yang didefinisikan dalam [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) ini |
| [getSealed()](#getSealed--) | Sebuah [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) akan disegel ketika telah digunakan oleh [TriMesh](../../com.aspose.threed/trimesh), tidak ada modifikasi lagi yang diizinkan. |
| [getSize()](#getSize--) | Ukuran dalam byte dari struktur vertex. |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk string ini. |
| [iterator()](#iterator--) | Mendapatkan enumerator untuk menelusuri semua bidang vertex dalam instance ini. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Representasi string dari [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VertexDeclaration() {#VertexDeclaration--}
```
public VertexDeclaration()
```


### addField(int dataType, VertexFieldSemantic semantic) {#addField-int-com.aspose.threed.VertexFieldSemantic-}
```
public VertexField addField(int dataType, VertexFieldSemantic semantic)
```


Tambahkan bidang vertex baru

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dataType | int | Tipe data dari bidang vertex. |
| semantic | [VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) | Untuk apa bidang ini akan digunakan |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield)
### addField(int dataType, VertexFieldSemantic semantic, int index) {#addField-int-com.aspose.threed.VertexFieldSemantic-int-}
```
public VertexField addField(int dataType, VertexFieldSemantic semantic, int index)
```


Tambahkan bidang vertex baru

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dataType | int | Tipe data dari bidang vertex. |
| semantic | [VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) | Untuk apa bidang ini akan digunakan |
| indeks | int | Indeks untuk semantik bidang yang sama, -1 untuk pembuatan otomatis |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield)
### addField(int dataType, VertexFieldSemantic semantic, int index, String alias) {#addField-int-com.aspose.threed.VertexFieldSemantic-int-java.lang.String-}
```
public VertexField addField(int dataType, VertexFieldSemantic semantic, int index, String alias)
```


Tambahkan bidang vertex baru

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dataType | int | Tipe data dari bidang vertex. |
| semantic | [VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) | Untuk apa bidang ini akan digunakan |
| indeks | int | Indeks untuk semantik bidang yang sama, -1 untuk pembuatan otomatis |
| alias | java.lang.String | Nama alias dari bidang |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield)
### clear() {#clear--}
```
public void clear()
```


Bersihkan semua bidang.

### compareTo(VertexDeclaration other) {#compareTo-com.aspose.threed.VertexDeclaration-}
```
public int compareTo(VertexDeclaration other)
```


Membandingkan instance ini dengan objek yang ditentukan dan mengembalikan indikasi nilai relatif mereka.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |  |

**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Menentukan apakah instance ini dan objek yang ditentukan, yang juga harus berupa objek [VertexDeclaration](../../com.aspose.threed/vertexdeclaration), memiliki nilai yang sama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromGeometry(Geometry geometry, boolean useFloat) {#fromGeometry-com.aspose.threed.Geometry-boolean-}
```
public static VertexDeclaration fromGeometry(Geometry geometry, boolean useFloat)
```


Buat sebuah [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) berdasarkan tata letak [Geometry](../../com.aspose.threed/geometry).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| geometry | [Geometry](../../com.aspose.threed/geometry) |  |
| useFloat | boolean | Gunakan float alih-alih tipe double |

**Returns:**
[VertexDeclaration](../../com.aspose.threed/vertexdeclaration)
### get(int index) {#get-int-}
```
public VertexField get(int index)
```


Mendapatkan [VertexField](../../com.aspose.threed/vertexfield) berdasarkan indeks

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks | int |  |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield) - the [VertexField](../../com.aspose.threed/vertexfield) by index
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public int getCount()
```


Mendapatkan jumlah semua bidang yang didefinisikan dalam [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) ini

**Returns:**
int - jumlah semua bidang yang didefinisikan dalam [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) ini
### getSealed() {#getSealed--}
```
public boolean getSealed()
```


Sebuah [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) akan disegel ketika telah digunakan oleh [TriMesh](../../com.aspose.threed/trimesh), tidak ada modifikasi lagi yang diizinkan.

**Returns:**
boolean - Sebuah [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) akan disegel ketika telah digunakan oleh [TriMesh](../../com.aspose.threed/trimesh), tidak ada modifikasi lagi yang diizinkan.
### getSize() {#getSize--}
```
public int getSize()
```


Ukuran dalam byte dari struktur vertex.

**Returns:**
int - Ukuran dalam byte dari struktur vertex.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan kode hash untuk string ini.

**Returns:**
int - Kode hash integer bertanda 32-bit.
### iterator() {#iterator--}
```
public Iterator<VertexField> iterator()
```


Mendapatkan enumerator untuk menelusuri semua bidang vertex dalam instance ini.

**Returns:**
java.util.Iterator<com.aspose.threed.VertexField> - Enumerator
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


Representasi string dari [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)

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

