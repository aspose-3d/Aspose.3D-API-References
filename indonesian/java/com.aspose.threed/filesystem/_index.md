---
title: FileSystem
second_title: Referensi API Aspose.3D untuk Java
description: Enkapsulasi sistem file.
type: docs
weight: 67
url: /id/java/com.aspose.threed/filesystem/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public abstract class FileSystem implements Closeable
```

Enkapsulasi sistem file. Aspose.3D akan menggunakan ini untuk membaca/menulis dependensi. **Example:** Kode berikut menunjukkan cara mengimpor file, dan menyediakan file dependensi dalam direktori yang diberikan

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
| [FileSystem()](#FileSystem--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [close()](#close--) | Hapus File system dan lepaskan sumber dayanya. |
| [createDummyFileSystem()](#createDummyFileSystem--) | Buat sistem file tiruan, operasi membaca/menulis adalah operasi tiruan. |
| [createLocalFileSystem(String directory)](#createLocalFileSystem-java.lang.String-) | Inisialisasi [FileSystem](../../com.aspose.threed/filesystem) baru yang hanya mengakses direktori lokal. |
| [createMemoryFileSystem()](#createMemoryFileSystem--) | Buat sistem file berbasis memori yang akan memetakan operasi membaca/menulis ke memori. |
| [createMemoryFileSystem(HashMap<String,MemoryStream> files)](#createMemoryFileSystem-java.util.HashMap-java.lang.String-com.aspose.threed.MemoryStream--) | Buat sistem file berbasis memori yang akan memetakan operasi membaca/menulis ke memori. |
| [createZipFileSystem(Stream stream)](#createZipFileSystem-com.aspose.threed.Stream-) | Buat sistem file untuk menyediakan akses hanya-baca ke file zip atau aliran zip yang ditentukan. |
| [createZipFileSystem(Stream stream, String baseDir)](#createZipFileSystem-com.aspose.threed.Stream-java.lang.String-) | Buat sistem file untuk menyediakan akses hanya-baca ke file zip atau aliran zip yang ditentukan. |
| [createZipFileSystem(String fileName)](#createZipFileSystem-java.lang.String-) | Sistem file untuk menyediakan akses hanya-baca ke file zip atau aliran zip yang ditentukan. |
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
### FileSystem() {#FileSystem--}
```
public FileSystem()
```


### close() {#close--}
```
public void close()
```


Hapus File system dan lepaskan sumber dayanya.

### createDummyFileSystem() {#createDummyFileSystem--}
```
public static FileSystem createDummyFileSystem()
```


Buat sistem file tiruan, operasi membaca/menulis adalah operasi tiruan.

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A dummy file system **Example:** The following code shows how to export file to memory, and ignore all dependent file generation.

```
//create a scene with material
     Scene scene = new Scene();
     scene.getRootNode().createChildNode(new Box()).setMaterial(new LambertMaterial());
     //create a save option and specify the file system, so the dependent file will be written to memory
     var opt = FileFormat.WAVEFRONTOBJ.createSaveOptions();
     var dfs = FileSystem.CreateDummyFileSystem();
     opt.setFileSystem(dfs);
     //obj's material file name is associated with the obj's file name, so we need a explicit name.
     opt.setFileName("test.obj");
     try (var ms = new MemoryStream())
     {
         scene.save(ms, opt);
     }
```
### createLocalFileSystem(String directory) {#createLocalFileSystem-java.lang.String-}
```
public static FileSystem createLocalFileSystem(String directory)
```


Inisialisasi [FileSystem](../../com.aspose.threed/filesystem) baru yang hanya mengakses direktori lokal. Semua operasi membaca/menulis file pada instance FileSystem ini akan dipetakan ke direktori yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| direktori | java.lang.String | Direktori dalam sistem file fisik Anda sebagai direktori root virtual. |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A new instance of file system to provide local file access
### createMemoryFileSystem() {#createMemoryFileSystem--}
```
public static FileSystem createMemoryFileSystem()
```


Buat sistem file berbasis memori yang akan memetakan operasi membaca/menulis ke memori.

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A memory-based file system **Example:** The following code shows how to export file to memory, includes the dependent file by using MemoryFileSystem.

```
//create a scene with material
     Scene scene = new Scene();
     scene.getRootNode().createChildNode(new Box()).setMaterial(new LambertMaterial());
     //create a save option and specify the file system, so the dependent file will be written to memory
     var opt = FileFormat.WAVEFRONTOBJ.createSaveOptions();
     var mfs = new HashMap<String, MemoryStream>();
     opt.setFileSystem(FileSystem.createMemoryFileSystem(mfs));
     //obj's material file name is associated with the obj's file name, so we need a explicit name.
     opt.setFileName("test.obj");
     try (var ms = new MemoryStream())
     {
         scene.save(ms, opt);
     }
     //the test.obj was written to variable ms, and we can also get the test.mtl file content by
     var materialFile = mfs.get("test.mtl");
```
### createMemoryFileSystem(HashMap<String,MemoryStream> files) {#createMemoryFileSystem-java.util.HashMap-java.lang.String-com.aspose.threed.MemoryStream--}
```
public static FileSystem createMemoryFileSystem(HashMap<String,MemoryStream> files)
```


Buat sistem file berbasis memori yang akan memetakan operasi membaca/menulis ke memori.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| file | java.util.HashMap<java.lang.String,com.aspose.threed.MemoryStream> | Ini memungkinkan Anda untuk membaca/menulis file virtual. |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A memory-based file system **Example:** The following code shows how to export file to memory, includes the dependent file by using MemoryFileSystem.

```
//create a scene with material
     Scene scene = new Scene();
     scene.getRootNode().createChildNode(new Box()).setMaterial(new LambertMaterial());
     //create a save option and specify the file system, so the dependent file will be written to memory
     var opt = FileFormat.WAVEFRONTOBJ.createSaveOptions();
     var mfs = new HashMap<String, MemoryStream>();
     opt.setFileSystem(FileSystem.createMemoryFileSystem(mfs));
     //obj's material file name is associated with the obj's file name, so we need a explicit name.
     opt.setFileName("test.obj");
     try (var ms = new MemoryStream())
     {
         scene.save(ms, opt);
     }
     //the test.obj was written to variable ms, and we can also get the test.mtl file content by
     var materialFile = mfs.get("test.mtl");
```
### createZipFileSystem(Stream stream) {#createZipFileSystem-com.aspose.threed.Stream-}
```
public static FileSystem createZipFileSystem(Stream stream)
```


Buat sistem file untuk menyediakan akses hanya-baca ke file zip atau aliran zip yang ditentukan. Sistem file akan dibuang setelah operasi buka/simpan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Aliran untuk mengakses file zip |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A zip file system
### createZipFileSystem(Stream stream, String baseDir) {#createZipFileSystem-com.aspose.threed.Stream-java.lang.String-}
```
public static FileSystem createZipFileSystem(Stream stream, String baseDir)
```


Buat sistem file untuk menyediakan akses hanya-baca ke file zip atau aliran zip yang ditentukan. Sistem file akan dibuang setelah operasi buka/simpan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Aliran untuk mengakses file zip |
| baseDir | java.lang.String | Direktori dasar di dalam file zip. |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A zip file system
### createZipFileSystem(String fileName) {#createZipFileSystem-java.lang.String-}
```
public static FileSystem createZipFileSystem(String fileName)
```


Sistem file untuk menyediakan akses hanya-baca ke file zip atau aliran zip yang ditentukan. Sistem file akan dibuang setelah operasi buka/simpan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | java.lang.String | Nama file untuk file zip. |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A zip file system
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
public abstract Stream readFile(String fileName, IOConfig options)
```


Buat aliran untuk membaca dependensi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | java.lang.String | Nama file untuk dibuka membaca |
| options | [IOConfig](../../com.aspose.threed/ioconfig) | Opsi simpan atau muat |

**Returns:**
[Stream](../../com.aspose.threed/stream) - Stream for reading the file.
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
public abstract Stream writeFile(String fileName, IOConfig options)
```


Buat aliran untuk menulis dependensi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | java.lang.String | Nama file untuk dibuka untuk menulis |
| options | [IOConfig](../../com.aspose.threed/ioconfig) | Opsi simpan atau muat |

**Returns:**
[Stream](../../com.aspose.threed/stream) - Stream for writing the file
