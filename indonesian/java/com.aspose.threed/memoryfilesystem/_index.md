---
title: MemoryFileSystem
second_title: Referensi API Aspose.3D untuk Java
description: The  akan memetakan operasi baca/tulis ke memori.
type: docs
weight: 95
url: /id/java/com.aspose.threed/memoryfilesystem/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.FileSystem](../../com.aspose.threed/filesystem)
```
public class MemoryFileSystem extends FileSystem
```

The [MemoryFileSystem](../../com.aspose.threed/memoryfilesystem) akan memetakan operasi baca/tulis ke memori. **Example:** Kode berikut menunjukkan cara mengekspor file ke memori, termasuk file dependensi dengan menggunakan MemoryFileSystem.

```
//create a scene with material
     Scene scene = new Scene();
     scene.getRootNode().createChildNode(new Box()).setMaterial(new LambertMaterial());
     //create a save option and specify the file system, so the dependent file will be written to memory
     var opt = FileFormat.WAVEFRONTOBJ.createSaveOptions();
     var mfs = new MemoryFileSystem();
     opt.setFileSystem(mfs);
     //obj's material file name is associated with the obj's file name, so we need a explicit name.
     opt.setFileName("test.obj");
     try (var ms = new MemoryStream())
     {
         scene.save(ms, opt);
     }
     //the test.obj was written to variable ms, and we can also get the test.mtl file content by
     var materialFile = mfs.getFileContent("test.mtl");
```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MemoryFileSystem()](#MemoryFileSystem--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [close()](#close--) | Hapus File system dan lepaskan sumber dayanya. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFileContent(String fileName)](#getFileContent-java.lang.String-) | Mengembalikan konten mentah dari file yang ditentukan. |
| [getFileNames()](#getFileNames--) | Nama file yang ada dalam sistem file memori ini. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readFile(String fileName, IOConfig options)](#readFile-java.lang.String-com.aspose.threed.IOConfig-) | Buat aliran untuk membaca dependensi. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeFile(String fileName, IOConfig options)](#writeFile-java.lang.String-com.aspose.threed.IOConfig-) | Buat aliran untuk menulis dependensi. |
### MemoryFileSystem() {#MemoryFileSystem--}
```
public MemoryFileSystem()
```


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
### getFileContent(String fileName) {#getFileContent-java.lang.String-}
```
public byte[] getFileContent(String fileName)
```


Mengembalikan konten mentah dari file yang ditentukan. Melempar java.io.FileNotFoundException jika file yang dimaksud tidak ada.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | java.lang.String |  |

**Returns:**
byte[]
### getFileNames() {#getFileNames--}
```
public List<String> getFileNames()
```


Nama file yang ada dalam sistem file memori ini.

**Returns:**
java.util.List<java.lang.String>
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
