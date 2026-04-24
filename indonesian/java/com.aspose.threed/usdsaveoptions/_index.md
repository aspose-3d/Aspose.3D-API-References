---
title: UsdSaveOptions
second_title: Referensi API Aspose.3D untuk Java
description: Opsi simpan untuk format USD/USDZ.
type: docs
weight: 200
url: /id/java/com.aspose.threed/usdsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class UsdSaveOptions extends SaveOptions
```

Opsi simpan untuk format USD/USDZ.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [UsdSaveOptions()](#UsdSaveOptions--) | Inisialisasi baru [UsdSaveOptions](../../com.aspose.threed/usdsaveoptions) dengan format [FileFormat.USD](../../com.aspose.threed/fileformat\#USD) |
| [UsdSaveOptions(FileFormat fileFormat)](#UsdSaveOptions-com.aspose.threed.FileFormat-) | Inisialisasi baru [UsdSaveOptions](../../com.aspose.threed/usdsaveoptions) dengan format USD/USDZ yang ditentukan. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEncoding()](#getEncoding--) | Mendapatkan encoding default untuk file berbasis teks. |
| [getExportMetaData()](#getExportMetaData--) | Ekspor properti node melalui bidang customData milik USD. |
| [getExportTextures()](#getExportTextures--) | Mencoba menyalin tekstur yang digunakan dalam adegan ke direktori output. |
| [getFileFormat()](#getFileFormat--) | Mendapatkan format file yang ditentukan dalam opsi Simpan/Muat saat ini. |
| [getFileName()](#getFileName--) | Nama file dari adegan ekspor/impor. |
| [getFileSystem()](#getFileSystem--) | Izinkan pengguna mengatur cara mengelola dependensi eksternal selama muat/simpan. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Mendapatkan kelas pabrik untuk FileSystem. |
| [getLookupPaths()](#getLookupPaths--) | Beberapa file seperti OBJ bergantung pada file eksternal, jalur pencarian akan memungkinkan Aspose.3D mencari file eksternal untuk dimuat. |
| [getMaterialConverter()](#getMaterialConverter--) | Konverter khusus untuk mengubah material geometri menjadi material PBR. Jika ini tidak ditetapkan, pengekspor USD akan secara otomatis mengubah material standar menjadi material PBR. |
| [getPrimitiveToMesh()](#getPrimitiveToMesh--) | Ubah entitas primitif menjadi mesh selama proses ekspor. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Mengatur encoding default untuk file berbasis teks. |
| [setExportMetaData(boolean value)](#setExportMetaData-boolean-) | Ekspor properti node melalui bidang customData milik USD. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | Mencoba menyalin tekstur yang digunakan dalam adegan ke direktori output. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Nama file dari adegan ekspor/impor. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Izinkan pengguna mengatur cara mengelola dependensi eksternal selama muat/simpan. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Mengatur kelas pabrik untuk FileSystem. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Beberapa file seperti OBJ bergantung pada file eksternal, jalur pencarian akan memungkinkan Aspose.3D mencari file eksternal untuk dimuat. |
| [setMaterialConverter(MaterialConverter value)](#setMaterialConverter-com.aspose.threed.MaterialConverter-) | Konverter khusus untuk mengubah material geometri menjadi material PBR. Jika ini tidak ditetapkan, pengekspor USD akan secara otomatis mengubah material standar menjadi material PBR. |
| [setPrimitiveToMesh(boolean value)](#setPrimitiveToMesh-boolean-) | Ubah entitas primitif menjadi mesh selama proses ekspor. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### UsdSaveOptions() {#UsdSaveOptions--}
```
public UsdSaveOptions()
```


Inisialisasi baru [UsdSaveOptions](../../com.aspose.threed/usdsaveoptions) dengan format [FileFormat.USD](../../com.aspose.threed/fileformat\#USD)

### UsdSaveOptions(FileFormat fileFormat) {#UsdSaveOptions-com.aspose.threed.FileFormat-}
```
public UsdSaveOptions(FileFormat fileFormat)
```


Inisialisasi baru [UsdSaveOptions](../../com.aspose.threed/usdsaveoptions) dengan format USD/USDZ yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileFormat | [FileFormat](../../com.aspose.threed/fileformat) |  |

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
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


Mendapatkan encoding default untuk file berbasis teks. Nilai default adalah null yang berarti pengimpor/pengekspor akan menentukan encoding yang akan digunakan.

**Returns:**
java.nio.charset.Charset - encoding default untuk file berbasis teks. Nilai default adalah null yang berarti pengimpor/pengekspor akan menentukan encoding yang akan digunakan.
### getExportMetaData() {#getExportMetaData--}
```
public boolean getExportMetaData()
```


Ekspor properti node melalui bidang customData milik USD.

**Returns:**
boolean - Ekspor properti node melalui bidang customData USD.
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
### getMaterialConverter() {#getMaterialConverter--}
```
public MaterialConverter getMaterialConverter()
```


Konverter khusus untuk mengubah material geometri menjadi material PBR. Jika tidak ditetapkan, pengekspor USD akan secara otomatis mengubah material standar menjadi material PBR. Nilai default adalah null.

**Returns:**
[MaterialConverter](../../com.aspose.threed/materialconverter) - Custom converter to convert the geometry's material to PBR material If this is unassigned, USD exporter will automatically convert the standard material to PBR material. Default value is null
### getPrimitiveToMesh() {#getPrimitiveToMesh--}
```
public boolean getPrimitiveToMesh()
```


Ubah entitas primitif menjadi mesh selama proses ekspor. Atau langsung enkode primitif ke file output (akan menggunakan definisi ekstensi Aspose untuk primitif tidak resmi seperti Dish, Torus). Nilai default adalah true.

**Returns:**
boolean - Ubah entitas primitif menjadi mesh selama proses ekspor. Atau langsung enkode primitif ke file output (akan menggunakan definisi ekstensi Aspose untuk primitif tidak resmi seperti Dish, Torus). Nilai default adalah true.
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




### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


Mengatur enkoding default untuk file berbasis teks. Nilai default adalah null yang berarti pengimpor/pengekspor akan menentukan enkoding yang akan digunakan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.nio.charset.Charset | Nilai baru |

### setExportMetaData(boolean value) {#setExportMetaData-boolean-}
```
public void setExportMetaData(boolean value)
```


Ekspor properti node melalui bidang customData milik USD.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

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

### setMaterialConverter(MaterialConverter value) {#setMaterialConverter-com.aspose.threed.MaterialConverter-}
```
public void setMaterialConverter(MaterialConverter value)
```


Konverter khusus untuk mengubah material geometri menjadi material PBR. Jika tidak ditetapkan, pengekspor USD akan secara otomatis mengubah material standar menjadi material PBR. Nilai default adalah null.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [MaterialConverter](../../com.aspose.threed/materialconverter) | Nilai baru |

### setPrimitiveToMesh(boolean value) {#setPrimitiveToMesh-boolean-}
```
public void setPrimitiveToMesh(boolean value)
```


Ubah entitas primitif menjadi mesh selama proses ekspor. Atau langsung enkode primitif ke file output (akan menggunakan definisi ekstensi Aspose untuk primitif tidak resmi seperti Dish, Torus). Nilai default adalah true.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

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

