---
title: LocalFileSystem
second_title: Referensi API Aspose.3D untuk Java
description: The  akan memetakan operasi baca/tulis ke direktori lokal.
type: docs
weight: 91
url: /id/java/com.aspose.threed/localfilesystem/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.FileSystem](../../com.aspose.threed/filesystem)
```
public class LocalFileSystem extends FileSystem
```

[LocalFileSystem](../../com.aspose.threed/localfilesystem) akan memetakan operasi baca/tulis ke direktori lokal. **Example:** Kode berikut menunjukkan cara mengimpor file, dan menyediakan file dependensi dalam direktori tertentu

```
var inputFile = "input.fbx";
     var format = FileFormat.detect(inputFile);
     //create a load options instance and specify a zip file system
     var opt = format.createLoadOptions();
     opt.setFileSystem(new LocalFileSystem("textures/"));
     //load the file
     var scene = Scene.fromFile(inputFile, opt);
```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [LocalFileSystem(String directory)](#LocalFileSystem-java.lang.String-) | Inisialisasi [LocalFileSystem](../../com.aspose.threed/localfilesystem) baru dengan direktori dasar yang ditentukan. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [close()](#close--) | Hapus File system dan lepaskan sumber dayanya. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readFile(String fileName, IOConfig options)](#readFile-java.lang.String-com.aspose.threed.IOConfig-) | Buat aliran untuk membaca dependensi. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeFile(String fileName, IOConfig options)](#writeFile-java.lang.String-com.aspose.threed.IOConfig-) | Buat aliran untuk menulis dependensi. |
### LocalFileSystem(String directory) {#LocalFileSystem-java.lang.String-}
```
public LocalFileSystem(String directory)
```


Inisialisasi [LocalFileSystem](../../com.aspose.threed/localfilesystem) baru dengan direktori dasar yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| direktori | java.lang.String |  |

### close() {#close--}
```
public void close()
```


Hapus File system dan lepaskan sumber dayanya.

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


Buat aliran untuk membaca dependensi.

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


Buat aliran untuk menulis dependensi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | java.lang.String |  |
| options | [IOConfig](../../com.aspose.threed/ioconfig) |  |

**Returns:**
com.aspose.csporter.helpers.Stream
