---
title: IIndexBuffer
second_title: Referensi API Aspose.3D untuk Java
description: Buffer indeks menjelaskan geometri yang digunakan dalam pipeline render.
type: docs
weight: 242
url: /id/java/com.aspose.threed/iindexbuffer/
---

**All Implemented Interfaces:**
[com.aspose.threed.IBuffer](../../com.aspose.threed/ibuffer)
```
public interface IIndexBuffer extends IBuffer
```

Buffer indeks menjelaskan geometri yang digunakan dalam pipeline render.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getCount()](#getCount--) | Mendapatkan jumlah indeks dalam buffer ini. |
| [getIndexDataType()](#getIndexDataType--) | Mendapatkan tipe data setiap elemen. |
| [loadData(TriMesh mesh)](#loadData-com.aspose.threed.TriMesh-) | Muat data indeks dari [TriMesh](../../com.aspose.threed/trimesh) |
| [loadData(int[] indices)](#loadData-int---) | Muat data indeks |
| [loadData(short[] indices)](#loadData-short---) | Muat data indeks |
### getCount() {#getCount--}
```
public abstract int getCount()
```


Mendapatkan jumlah indeks dalam buffer ini.

**Returns:**
int - jumlah indeks dalam buffer ini.
### getIndexDataType() {#getIndexDataType--}
```
public abstract IndexDataType getIndexDataType()
```


Mendapatkan tipe data setiap elemen.

**Returns:**
[IndexDataType](../../com.aspose.threed/indexdatatype) - the data type of each element.
### loadData(TriMesh mesh) {#loadData-com.aspose.threed.TriMesh-}
```
public abstract void loadData(TriMesh mesh)
```


Muat data indeks dari [TriMesh](../../com.aspose.threed/trimesh)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mesh | [TriMesh](../../com.aspose.threed/trimesh) |  |

### loadData(int[] indices) {#loadData-int---}
```
public abstract void loadData(int[] indices)
```


Muat data indeks

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks | int[] |  |

### loadData(short[] indices) {#loadData-short---}
```
public abstract void loadData(short[] indices)
```


Muat data indeks

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks | short[] |  |

