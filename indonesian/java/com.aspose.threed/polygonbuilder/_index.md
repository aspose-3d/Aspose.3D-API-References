---
title: PolygonBuilder
second_title: Referensi API Aspose.3D untuk Java
description: Kelas pembantu untuk membangun poligon untuk  Example
type: docs
weight: 133
url: /id/java/com.aspose.threed/polygonbuilder/
---

**Inheritance:**
java.lang.Object
```
public final class PolygonBuilder
```

Kelas pembantu untuk membangun poligon untuk [Mesh](../../com.aspose.threed/mesh) **Contoh:**

```
Mesh mesh = new Mesh();
  PolygonBuilder builder = new PolygonBuilder(mesh);
  builder.begin();
  builder.addVertex(0);
  builder.addVertex(1);
  builder.addVertex(2);
  builder.end();
```

Sama dengan :

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
```

Jika semua indeks siap digunakan, [Mesh](../../com.aspose.threed/mesh) lebih disarankan, jika tidak [PolygonBuilder](../../com.aspose.threed/polygonbuilder) akan menjadi pilihan yang lebih baik.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PolygonBuilder(Mesh mesh)](#PolygonBuilder-com.aspose.threed.Mesh-) | Menginisialisasi sebuah instance baru dari kelas [PolygonBuilder](../../com.aspose.threed/polygonbuilder). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [addVertex(int index)](#addVertex-int-) | Menambahkan indeks vertex ke poligon |
| [begin()](#begin--) | Memulai penambahan poligon baru |
| [end()](#end--) | Menyelesaikan pembuatan poligon |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PolygonBuilder(Mesh mesh) {#PolygonBuilder-com.aspose.threed.Mesh-}
```
public PolygonBuilder(Mesh mesh)
```


Menginisialisasi sebuah instance baru dari kelas [PolygonBuilder](../../com.aspose.threed/polygonbuilder).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | Pada mesh mana poligon akan dibangun. |

### addVertex(int index) {#addVertex-int-}
```
public void addVertex(int index)
```


Menambahkan indeks vertex ke poligon

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks | int |  |

### begin() {#begin--}
```
public void begin()
```


Memulai penambahan poligon baru

### end() {#end--}
```
public void end()
```


Menyelesaikan pembuatan poligon

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

