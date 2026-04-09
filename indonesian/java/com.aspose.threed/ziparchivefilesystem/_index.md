---
title: ZipArchiveFileSystem
second_title: Referensi API Aspose.3D untuk Java
description: Sistem file untuk menyediakan akses hanya-baca ke file zip atau aliran zip yang ditentukan.
type: docs
weight: 221
url: /id/java/com.aspose.threed/ziparchivefilesystem/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.FileSystem](../../com.aspose.threed/filesystem)
```
public class ZipArchiveFileSystem extends FileSystem
```

Sistem file untuk menyediakan akses hanya-baca ke file zip atau aliran zip yang ditentukan. Sistem file akan dibuang setelah operasi buka/simpan. **Example:** Kode berikut menunjukkan cara mengimpor file, dan menyediakan file dependensi dalam file arsip zip.

```
var inputFile = "input.fbx";
     var format = FileFormat.detect(inputFile);
     //create a load options instance and specify a zip file system
     var opt = format.createLoadOptions();
     opt.setFileSystem(new ZipArchiveFileSystem("textures.zip"));
     //load the file
     var scene = Scene.fromFile(inputFile, opt);
```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ZipArchiveFileSystem(Stream stream, String baseDir)](#ZipArchiveFileSystem-com.aspose.csporter.helpers.Stream-java.lang.String-) | Bangun sebuah [ZipArchiveFileSystem](../../com.aspose.threed/ziparchivefilesystem) melalui aliran. |
| [ZipArchiveFileSystem(Stream stream)](#ZipArchiveFileSystem-com.aspose.csporter.helpers.Stream-) | Bangun sebuah [ZipArchiveFileSystem](../../com.aspose.threed/ziparchivefilesystem) melalui aliran. |
| [ZipArchiveFileSystem(String fileName)](#ZipArchiveFileSystem-java.lang.String-) | Bangun sebuah [ZipArchiveFileSystem](../../com.aspose.threed/ziparchivefilesystem) melalui nama file. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [close()](#close--) | Buang ZipArchiveFileSystem dan lepaskan sumber daya internalnya. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readFile(String fileName, IOConfig options)](#readFile-java.lang.String-com.aspose.threed.IOConfig-) | Buka file untuk membaca |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeFile(String fileName, IOConfig options)](#writeFile-java.lang.String-com.aspose.threed.IOConfig-) | Buka file untuk menulis, tidak diimplementasikan dalam kelas ini. |
### ZipArchiveFileSystem(Stream stream, String baseDir) {#ZipArchiveFileSystem-com.aspose.csporter.helpers.Stream-java.lang.String-}
```
public ZipArchiveFileSystem(Stream stream, String baseDir)
```


Bangun sebuah [ZipArchiveFileSystem](../../com.aspose.threed/ziparchivefilesystem) melalui aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | com.aspose.csporter.helpers.Stream |  |
| baseDir | java.lang.String |  |

### ZipArchiveFileSystem(Stream stream) {#ZipArchiveFileSystem-com.aspose.csporter.helpers.Stream-}
```
public ZipArchiveFileSystem(Stream stream)
```


Bangun sebuah [ZipArchiveFileSystem](../../com.aspose.threed/ziparchivefilesystem) melalui aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | com.aspose.csporter.helpers.Stream |  |

### ZipArchiveFileSystem(String fileName) {#ZipArchiveFileSystem-java.lang.String-}
```
public ZipArchiveFileSystem(String fileName)
```


Bangun sebuah [ZipArchiveFileSystem](../../com.aspose.threed/ziparchivefilesystem) melalui nama file.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | java.lang.String |  |

### close() {#close--}
```
public void close()
```


Buang ZipArchiveFileSystem dan lepaskan sumber daya internalnya.

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




### readFile(String fileName, IOConfig options) {#readFile-java.lang.String-com.aspose.threed.IOConfig-}
```
public Stream readFile(String fileName, IOConfig options)
```


Buka file untuk membaca

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | java.lang.String |  |
| options | [IOConfig](../../com.aspose.threed/ioconfig) |  |

**Returns:**
com.aspose.csporter.helpers.Stream
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

### writeFile(String fileName, IOConfig options) {#writeFile-java.lang.String-com.aspose.threed.IOConfig-}
```
public Stream writeFile(String fileName, IOConfig options)
```


Buka file untuk menulis, tidak diimplementasikan dalam kelas ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | java.lang.String |  |
| options | [IOConfig](../../com.aspose.threed/ioconfig) |  |

**Returns:**
com.aspose.csporter.helpers.Stream
