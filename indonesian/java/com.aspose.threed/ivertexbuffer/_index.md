---
title: IVertexBuffer
second_title: Referensi API Aspose.3D untuk Java
description: Buffer verteks menyimpan data verteks poligon yang akan dikirim ke pipeline rendering.
type: docs
weight: 259
url: /id/java/com.aspose.threed/ivertexbuffer/
---

**All Implemented Interfaces:**
[com.aspose.threed.IBuffer](../../com.aspose.threed/ibuffer)
```
public interface IVertexBuffer extends IBuffer
```

Buffer verteks menyimpan data verteks poligon yang akan dikirim ke pipeline rendering.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getVertexDeclaration()](#getVertexDeclaration--) | Mendapatkan deklarasi verteks |
| [loadData(TriMesh mesh)](#loadData-com.aspose.threed.TriMesh-) | Muat data verteks dari [TriMesh](../../com.aspose.threed/trimesh) |
| [loadData(Object array)](#loadData-java.lang.Object-) | Muat data dari array |
| [loadData(long data, int size)](#loadData-long-int-) | Muat data dari posisi yang diberikan |
### getVertexDeclaration() {#getVertexDeclaration--}
```
public abstract VertexDeclaration getVertexDeclaration()
```


Mendapatkan deklarasi verteks

**Returns:**
[VertexDeclaration](../../com.aspose.threed/vertexdeclaration) - the vertex declaration
### loadData(TriMesh mesh) {#loadData-com.aspose.threed.TriMesh-}
```
public abstract void loadData(TriMesh mesh)
```


Muat data verteks dari [TriMesh](../../com.aspose.threed/trimesh)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mesh | [TriMesh](../../com.aspose.threed/trimesh) |  |

### loadData(Object array) {#loadData-java.lang.Object-}
```
public abstract void loadData(Object array)
```


Muat data dari array

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | java.lang.Object |  |

### loadData(long data, int size) {#loadData-long-int-}
```
public abstract void loadData(long data, int size)
```


Muat data dari posisi yang diberikan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | long |  |
| ukuran | int |  |

