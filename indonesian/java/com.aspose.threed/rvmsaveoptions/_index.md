---
title: RvmSaveOptions
second_title: Referensi API Aspose.3D untuk Java
description: Opsi simpan untuk file RVM Aveva PDMS.
type: docs
weight: 158
url: /id/java/com.aspose.threed/rvmsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class RvmSaveOptions extends SaveOptions
```

Opsi penyimpanan untuk file Aveva PDMS RVM. **Contoh:** Kode berikut menunjukkan cara mengekspor atribut dalam RVM.

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [RvmSaveOptions()](#RvmSaveOptions--) | Konstruktor dari [RvmSaveOptions](../../com.aspose.threed/rvmsaveoptions) |
| [RvmSaveOptions(FileContentType contentType)](#RvmSaveOptions-com.aspose.threed.FileContentType-) | Konstruktor dari [RvmSaveOptions](../../com.aspose.threed/rvmsaveoptions) |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttributeListFile()](#getAttributeListFile--) | Mendapatkan nama file dari file daftar atribut, pengekspor akan menghasilkan nama berdasarkan nama file .rvm ketika properti ini tidak didefinisikan, nilai default adalah null. |
| [getAttributePrefix()](#getAttributePrefix--) | Mendapatkan awalan dari atribut yang akan diekspor, properti yang diekspor tidak akan mengandung awalan, properti kustom dengan awalan berbeda tidak akan diekspor, nilai default adalah 'rvm:'. |
| [getAuthor()](#getAuthor--) | Informasi penulis, nilai default adalah '3d@aspose' |
| [getClass()](#getClass--) |  |
| [getCreationTime()](#getCreationTime--) | Stempel waktu yang mengekspor file ini, nilai default adalah waktu saat ini |
| [getEncoding()](#getEncoding--) | Mendapatkan encoding default untuk file berbasis teks. |
| [getExportAttributes()](#getExportAttributes--) | Mendapatkan apakah akan mengekspor daftar atribut ke file .att eksternal, nilai default adalah false. |
| [getExportTextures()](#getExportTextures--) | Mencoba menyalin tekstur yang digunakan dalam adegan ke direktori output. |
| [getFileFormat()](#getFileFormat--) | Mendapatkan format file yang ditentukan dalam opsi Simpan/Muat saat ini. |
| [getFileName()](#getFileName--) | Nama file dari adegan ekspor/impor. |
| [getFileNote()](#getFileNote--) | Catatan file di header file. |
| [getFileSystem()](#getFileSystem--) | Izinkan pengguna mengatur cara mengelola dependensi eksternal selama muat/simpan. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Mendapatkan kelas pabrik untuk FileSystem. |
| [getLookupPaths()](#getLookupPaths--) | Beberapa file seperti OBJ bergantung pada file eksternal, jalur pencarian akan memungkinkan Aspose.3D mencari file eksternal untuk dimuat. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAttributeListFile(String value)](#setAttributeListFile-java.lang.String-) | Mengatur nama file daftar atribut, pengekspor akan menghasilkan nama berdasarkan nama file .rvm ketika properti ini tidak ditentukan, nilai default adalah null. |
| [setAttributePrefix(String value)](#setAttributePrefix-java.lang.String-) | Mengatur awalan atribut yang akan diekspor, properti yang diekspor tidak akan memiliki awalan, properti khusus dengan awalan berbeda tidak akan diekspor, nilai default adalah 'rvm:'. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Informasi penulis, nilai default adalah '3d@aspose' |
| [setCreationTime(String value)](#setCreationTime-java.lang.String-) | Stempel waktu yang mengekspor file ini, nilai default adalah waktu saat ini |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Mengatur encoding default untuk file berbasis teks. |
| [setExportAttributes(boolean value)](#setExportAttributes-boolean-) | Mengatur apakah akan mengekspor daftar atribut ke file .att eksternal, nilai default adalah false. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | Mencoba menyalin tekstur yang digunakan dalam adegan ke direktori output. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Nama file dari adegan ekspor/impor. |
| [setFileNote(String value)](#setFileNote-java.lang.String-) | Catatan file di header file. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Izinkan pengguna mengatur cara mengelola dependensi eksternal selama muat/simpan. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Mengatur kelas pabrik untuk FileSystem. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Beberapa file seperti OBJ bergantung pada file eksternal, jalur pencarian akan memungkinkan Aspose.3D mencari file eksternal untuk dimuat. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RvmSaveOptions() {#RvmSaveOptions--}
```
public RvmSaveOptions()
```


Konstruktor dari [RvmSaveOptions](../../com.aspose.threed/rvmsaveoptions)

### RvmSaveOptions(FileContentType contentType) {#RvmSaveOptions-com.aspose.threed.FileContentType-}
```
public RvmSaveOptions(FileContentType contentType)
```


Konstruktor dari [RvmSaveOptions](../../com.aspose.threed/rvmsaveoptions)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) | File RVM teks atau biner? |

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
### getAttributeListFile() {#getAttributeListFile--}
```
public String getAttributeListFile()
```


Mendapatkan nama file dari file daftar atribut, pengekspor akan menghasilkan nama berdasarkan nama file .rvm ketika properti ini tidak didefinisikan, nilai default adalah null.

**Returns:**
java.lang.String - nama file daftar atribut, pengekspor akan menghasilkan nama berdasarkan nama file .rvm ketika properti ini tidak ditentukan, nilai default adalah null. **Example:** Kode berikut menunjukkan cara mengekspor atribut dalam RVM.

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
```
### getAttributePrefix() {#getAttributePrefix--}
```
public String getAttributePrefix()
```


Mendapatkan awalan atribut yang akan diekspor, properti yang diekspor tidak akan memiliki awalan, properti khusus dengan awalan berbeda tidak akan diekspor, nilai default adalah 'rvm:'. Misalnya jika sebuah properti adalah rvm:Refno=345, atribut yang diekspor akan menjadi Refno = 345, awalan dihapus.

**Returns:**
java.lang.String - awalan atribut yang akan diekspor, properti yang diekspor tidak akan memiliki awalan, properti khusus dengan awalan berbeda tidak akan diekspor, nilai default adalah 'rvm:'. Misalnya jika sebuah properti adalah rvm:Refno=345, atribut yang diekspor akan menjadi Refno = 345, awalan dihapus. **Example:** Kode berikut menunjukkan cara mengekspor atribut dalam RVM.

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
```
### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Informasi penulis, nilai default adalah '3d@aspose'

**Returns:**
java.lang.String - Informasi penulis, nilai default adalah '3d@aspose' **Example:** Kode berikut menunjukkan cara mengekspor atribut dalam RVM.

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
```
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCreationTime() {#getCreationTime--}
```
public String getCreationTime()
```


Stempel waktu yang mengekspor file ini, nilai default adalah waktu saat ini

**Returns:**
java.lang.String - Stempel waktu yang mengekspor file ini, nilai default adalah waktu saat ini
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


Mendapatkan encoding default untuk file berbasis teks. Nilai default adalah null yang berarti pengimpor/pengekspor akan menentukan encoding yang akan digunakan.

**Returns:**
java.nio.charset.Charset - encoding default untuk file berbasis teks. Nilai default adalah null yang berarti pengimpor/pengekspor akan menentukan encoding yang akan digunakan.
### getExportAttributes() {#getExportAttributes--}
```
public boolean getExportAttributes()
```


Mendapatkan apakah akan mengekspor daftar atribut ke file .att eksternal, nilai default adalah false.

**Returns:**
boolean - apakah akan mengekspor daftar atribut ke file .att eksternal, nilai default adalah false. **Example:** Kode berikut menunjukkan cara mengekspor atribut dalam RVM.

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
```
### getExportTextures() {#getExportTextures--}
```
public boolean getExportTextures()
```


Mencoba menyalin tekstur yang digunakan dalam adegan ke direktori output.

**Returns:**
boolean - Mencoba menyalin tekstur yang digunakan dalam adegan ke direktori output.
### getFileFormat() {#getFileFormat--}
```
public FileFormat getFileFormat()
```


Mendapatkan format file yang ditentukan dalam opsi Simpan/Muat saat ini.

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - the file format that specified in current Save/Load option.
### getFileName() {#getFileName--}
```
public String getFileName()
```


Nama file dari adegan yang diekspor/diimpor. Ini opsional, tetapi berguna saat menyerialkan aset eksternal seperti material OBJ.

**Returns:**
java.lang.String - Nama file dari adegan yang diekspor/diimpor. Ini opsional, tetapi berguna saat menyerialkan aset eksternal seperti material OBJ.
### getFileNote() {#getFileNote--}
```
public String getFileNote()
```


Catatan file di header file.

**Returns:**
java.lang.String - Catatan file di header file. **Example:** Kode berikut menunjukkan cara mengekspor atribut dalam RVM.

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
```
### getFileSystem() {#getFileSystem--}
```
public FileSystem getFileSystem()
```


Izinkan pengguna mengatur cara mengelola dependensi eksternal selama muat/simpan.

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - Allow user to handle how to manage the external dependencies during load/save. **Example:** The default FileSystem is LocalFileSystem, it is not safe in environment like server side, But you can override the file system access by specifying a different implementation. Aspose.3D provides different FileSystem implementation like:

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

Dan Anda juga dapat menggunakan implementasi Anda sendiri.

```
Scene scene = new Scene();
             var material = new PhongMaterial();
             var boxNode = scene.getRootNode().createChildNode(new Box());
             boxNode.setMaterial(material);
 
             var opt = new ObjSaveOptions();
             var memFs = new HashMap<string, MemoryStream>();
             opt.setFileSystem(FileSystem.createMemoryFileSystem(memFs));
 			opt.setFileName("output.obj");
             try(var output = new ByteArrayOutputStream()) {
 				scene.save(output, opt);
 				//The material will be written to variable memFs named output.mtl
 				var materialInBytes = memFs["output.mtl"].toArray();
             }
```
### getFileSystemFactory() {#getFileSystemFactory--}
```
public static FileSystemFactory getFileSystemFactory()
```


Mendapatkan kelas pabrik untuk FileSystem. Pabrik default akan membuat com.aspose.threed.LocalFileSystem yang tidak cocok untuk lingkungan server.

**Returns:**
[FileSystemFactory](../../com.aspose.threed/filesystemfactory) - the factory class for FileSystem. The default factory will create com.aspose.threed.LocalFileSystem which is not suitable for server environment. **Example:** The default FileSystem in SaveOptions/LoadOptions is directory-based file system, You can override the default implementation by specify it through IOConfig.FileSystemFactory:

```
IOConfig.setFileSystemFactory(new FileSystemFactory() {
 				@Override
 				public FileSystem call() {
 					return FileSystem.createDummyFileSystem();
 				}
 			});
 
             Scene scene = new Scene();
             var material = new PhongMaterial();
             var boxNode = scene.getRootNode().createChildNode(new Box());
             boxNode.setMaterial(material);
 
             //opt.FileSystem would be dummy file system now
             var opt = new ObjSaveOptions();
             scene.Save("output.obj", opt);
             //the material file output.mtl will not be written to any places because we've configured a dummy file system as default implementation.
```
### getLookupPaths() {#getLookupPaths--}
```
public ArrayList<String> getLookupPaths()
```


Beberapa file seperti OBJ bergantung pada file eksternal, jalur pencarian akan memungkinkan Aspose.3D mencari file eksternal untuk dimuat.

**Returns:**
java.util.ArrayList<java.lang.String> - Beberapa file seperti OBJ bergantung pada file eksternal, jalur pencarian akan memungkinkan Aspose.3D mencari file eksternal untuk dimuat. **Example:** Kode berikut menunjukkan cara menentukan secara manual tekstur pencarian, sehingga pengimpor dapat menemukannya

```
var opt = new ObjLoadOptions();
             //Specify the lookup paths, so the textures can be located.
             opt.getLookupPaths().add("textures");
             var scene = Scene.fromFile("input.obj", opt);
             scene.save("output.glb");
```
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




### setAttributeListFile(String value) {#setAttributeListFile-java.lang.String-}
```
public void setAttributeListFile(String value)
```


Mengatur nama file daftar atribut, pengekspor akan menghasilkan nama berdasarkan nama file .rvm ketika properti ini tidak ditentukan, nilai default adalah null.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.lang.String | Nilai baru **Example:** Kode berikut menunjukkan cara mengekspor atribut dalam RVM. |

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
``` |

### setAttributePrefix(String value) {#setAttributePrefix-java.lang.String-}
```
public void setAttributePrefix(String value)
```


Mengatur awalan atribut yang akan diekspor, properti yang diekspor tidak akan memiliki awalan, properti khusus dengan awalan berbeda tidak akan diekspor, nilai default adalah 'rvm:'. Misalnya jika sebuah properti adalah rvm:Refno=345, atribut yang diekspor akan menjadi Refno = 345, awalan dihapus.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.lang.String | Nilai baru **Example:** Kode berikut menunjukkan cara mengekspor atribut dalam RVM. |

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
``` |

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


Informasi penulis, nilai default adalah '3d@aspose'

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.lang.String | Nilai baru **Example:** Kode berikut menunjukkan cara mengekspor atribut dalam RVM. |

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
``` |

### setCreationTime(String value) {#setCreationTime-java.lang.String-}
```
public void setCreationTime(String value)
```


Stempel waktu yang mengekspor file ini, nilai default adalah waktu saat ini

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nilai baru |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


Mengatur enkoding default untuk file berbasis teks. Nilai default adalah null yang berarti pengimpor/pengekspor akan menentukan enkoding yang akan digunakan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.nio.charset.Charset | Nilai baru |

### setExportAttributes(boolean value) {#setExportAttributes-boolean-}
```
public void setExportAttributes(boolean value)
```


Mengatur apakah akan mengekspor daftar atribut ke file .att eksternal, nilai default adalah false.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | boolean | Nilai baru **Example:** Kode berikut menunjukkan cara mengekspor atribut dalam RVM. |

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
``` |

### setExportTextures(boolean value) {#setExportTextures-boolean-}
```
public void setExportTextures(boolean value)
```


Mencoba menyalin tekstur yang digunakan dalam adegan ke direktori output.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public void setFileName(String value)
```


Nama file dari adegan yang diekspor/diimpor. Ini opsional, tetapi berguna saat menyerialkan aset eksternal seperti material OBJ.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nilai baru |

### setFileNote(String value) {#setFileNote-java.lang.String-}
```
public void setFileNote(String value)
```


Catatan file di header file.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.lang.String | Nilai baru **Example:** Kode berikut menunjukkan cara mengekspor atribut dalam RVM. |

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
``` |

### setFileSystem(FileSystem value) {#setFileSystem-com.aspose.threed.FileSystem-}
```
public void setFileSystem(FileSystem value)
```


Izinkan pengguna mengatur cara mengelola dependensi eksternal selama muat/simpan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [FileSystem](../../com.aspose.threed/filesystem) | Nilai baru **Example:** FileSystem default adalah LocalFileSystem, tidak aman di lingkungan seperti sisi server, Namun Anda dapat mengganti akses file system dengan menentukan implementasi yang berbeda. Aspose.3D menyediakan berbagai implementasi FileSystem seperti: |

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

Dan Anda juga dapat menggunakan implementasi Anda sendiri.

```
Scene scene = new Scene();
             var material = new PhongMaterial();
             var boxNode = scene.getRootNode().createChildNode(new Box());
             boxNode.setMaterial(material);
 
             var opt = new ObjSaveOptions();
             var memFs = new HashMap<string, MemoryStream>();
             opt.setFileSystem(FileSystem.createMemoryFileSystem(memFs));
 			opt.setFileName("output.obj");
             try(var output = new ByteArrayOutputStream()) {
 				scene.save(output, opt);
 				//The material will be written to variable memFs named output.mtl
 				var materialInBytes = memFs["output.mtl"].toArray();
             }
``` |

### setFileSystemFactory(FileSystemFactory value) {#setFileSystemFactory-com.aspose.threed.FileSystemFactory-}
```
public static void setFileSystemFactory(FileSystemFactory value)
```


Mengatur kelas pabrik untuk FileSystem. Pabrik default akan membuat com.aspose.threed.LocalFileSystem yang tidak cocok untuk lingkungan server.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [FileSystemFactory](../../com.aspose.threed/filesystemfactory) | Nilai baru **Example:** FileSystem default dalam SaveOptions/LoadOptions adalah file system berbasis direktori, Anda dapat mengganti implementasi default dengan menyebutkannya melalui IOConfig.FileSystemFactory: |

```
IOConfig.setFileSystemFactory(new FileSystemFactory() {
 				@Override
 				public FileSystem call() {
 					return FileSystem.createDummyFileSystem();
 				}
 			});
 
             Scene scene = new Scene();
             var material = new PhongMaterial();
             var boxNode = scene.getRootNode().createChildNode(new Box());
             boxNode.setMaterial(material);
 
             //opt.FileSystem would be dummy file system now
             var opt = new ObjSaveOptions();
             scene.Save("output.obj", opt);
             //the material file output.mtl will not be written to any places because we've configured a dummy file system as default implementation.
``` |

### setLookupPaths(ArrayList<String> value) {#setLookupPaths-java.util.ArrayList-java.lang.String--}
```
public void setLookupPaths(ArrayList<String> value)
```


Beberapa file seperti OBJ bergantung pada file eksternal, jalur pencarian akan memungkinkan Aspose.3D mencari file eksternal untuk dimuat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.util.ArrayList<java.lang.String> | Nilai baru **Example:** Kode berikut menunjukkan cara menentukan secara manual tekstur pencarian, sehingga pengimpor dapat menemukannya |

```
var opt = new ObjLoadOptions();
             //Specify the lookup paths, so the textures can be located.
             opt.getLookupPaths().add("textures");
             var scene = Scene.fromFile("input.obj", opt);
             scene.save("output.glb");
``` |

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

