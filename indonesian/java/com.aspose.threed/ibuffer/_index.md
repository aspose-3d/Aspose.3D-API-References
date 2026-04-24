---
title: IBuffer
second_title: Referensi API Aspose.3D untuk Java
description: Antarmuka dasar semua buffer terkelola yang digunakan dalam rendering.
type: docs
weight: 239
url: /id/java/com.aspose.threed/ibuffer/
---

**All Implemented Interfaces:**
java.io.Closeable
```
public interface IBuffer extends Closeable
```

Antarmuka dasar semua buffer terkelola yang digunakan dalam rendering.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getSize()](#getSize--) | Ukuran buffer ini dalam byte |
| [loadData(byte[] data)](#loadData-byte---) | Muat data ke dalam buffer saat ini |
### getSize() {#getSize--}
```
public abstract int getSize()
```


Ukuran buffer ini dalam byte

**Returns:**
int - Ukuran buffer ini dalam byte
### loadData(byte[] data) {#loadData-byte---}
```
public abstract void loadData(byte[] data)
```


Muat data ke dalam buffer saat ini

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | byte[] |  |

