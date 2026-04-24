---
title: U3dSaveOptions
second_title: Referensi API Aspose.3D untuk Java
description: Opsi simpan untuk 3d universal
type: docs
weight: 198
url: /id/java/com.aspose.threed/u3dsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class U3dSaveOptions extends SaveOptions
```

Opsi simpan untuk 3d universal
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [U3dSaveOptions()](#U3dSaveOptions--) | Konstruktor dari [U3dSaveOptions](../../com.aspose.threed/u3dsaveoptions) |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEmbedTextures()](#getEmbedTextures--) | Sematkan tekstur eksternal ke dalam file U3D, nilai default adalah false. |
| [getEncoding()](#getEncoding--) | Mendapatkan encoding default untuk file berbasis teks. |
| [getExportNormals()](#getExportNormals--) | Mendapatkan apakah akan mengekspor data normal. |
| [getExportTextureCoordinates()](#getExportTextureCoordinates--) | Mendapatkan apakah akan mengekspor koordinat tekstur. |
| [getExportTextures()](#getExportTextures--) | Mencoba menyalin tekstur yang digunakan dalam adegan ke direktori output. |
| [getExportVertexDiffuse()](#getExportVertexDiffuse--) | Mendapatkan apakah akan mengekspor warna difus vertex. |
| [getExportVertexSpecular()](#getExportVertexSpecular--) | Mendapatkan apakah akan mengekspor warna spekular vertex. |
| [getFileFormat()](#getFileFormat--) | Mendapatkan format file yang ditentukan dalam opsi Simpan/Muat saat ini. |
| [getFileName()](#getFileName--) | Nama file dari adegan ekspor/impor. |
| [getFileSystem()](#getFileSystem--) | Izinkan pengguna mengatur cara mengelola dependensi eksternal selama muat/simpan. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Mendapatkan kelas pabrik untuk FileSystem. |
| [getFlipCoordinateSystem()](#getFlipCoordinateSystem--) | Mendapatkan apakah sistem koordinat dibalik untuk titik kontrol/normal selama impor/ekspor. |
| [getLookupPaths()](#getLookupPaths--) | Beberapa file seperti OBJ bergantung pada file eksternal, jalur pencarian akan memungkinkan Aspose.3D mencari file eksternal untuk dimuat. |
| [getMeshCompression()](#getMeshCompression--) | Mendapatkan apakah akan mengaktifkan kompresi data mesh. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setEmbedTextures(boolean value)](#setEmbedTextures-boolean-) | Sematkan tekstur eksternal ke dalam file U3D, nilai default adalah false. |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Mengatur encoding default untuk file berbasis teks. |
| [setExportNormals(boolean value)](#setExportNormals-boolean-) | Mengatur apakah akan mengekspor data normal. |
| [setExportTextureCoordinates(boolean value)](#setExportTextureCoordinates-boolean-) | Mengatur apakah akan mengekspor koordinat tekstur. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | Mencoba menyalin tekstur yang digunakan dalam adegan ke direktori output. |
| [setExportVertexDiffuse(boolean value)](#setExportVertexDiffuse-boolean-) | Mengatur apakah akan mengekspor warna difus vertex. |
| [setExportVertexSpecular(boolean value)](#setExportVertexSpecular-boolean-) | Mengatur apakah akan mengekspor warna spekular vertex. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Nama file dari adegan ekspor/impor. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Izinkan pengguna mengatur cara mengelola dependensi eksternal selama muat/simpan. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Mengatur kelas pabrik untuk FileSystem. |
| [setFlipCoordinateSystem(boolean value)](#setFlipCoordinateSystem-boolean-) | Mengatur apakah sistem koordinat dibalik untuk titik kontrol/normal selama impor/ekspor. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Beberapa file seperti OBJ bergantung pada file eksternal, jalur pencarian akan memungkinkan Aspose.3D mencari file eksternal untuk dimuat. |
| [setMeshCompression(boolean value)](#setMeshCompression-boolean-) | Mengatur apakah akan mengaktifkan kompresi data mesh. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### U3dSaveOptions() {#U3dSaveOptions--}
```
public U3dSaveOptions()
```


Konstruktor dari [U3dSaveOptions](../../com.aspose.threed/u3dsaveoptions)

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
### getEmbedTextures() {#getEmbedTextures--}
```
public boolean getEmbedTextures()
```


Sematkan tekstur eksternal ke dalam file U3D, nilai default adalah false.

**Returns:**
boolean - Sematkan tekstur eksternal ke dalam file U3D, nilai default adalah false.
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


Mendapatkan encoding default untuk file berbasis teks. Nilai default adalah null yang berarti pengimpor/pengekspor akan menentukan encoding yang akan digunakan.

**Returns:**
java.nio.charset.Charset - encoding default untuk file berbasis teks. Nilai default adalah null yang berarti pengimpor/pengekspor akan menentukan encoding yang akan digunakan.
### getExportNormals() {#getExportNormals--}
```
public boolean getExportNormals()
```


Mendapatkan apakah akan mengekspor data normal.

**Returns:**
boolean - apakah akan mengekspor data normal.
### getExportTextureCoordinates() {#getExportTextureCoordinates--}
```
public boolean getExportTextureCoordinates()
```


Mendapatkan apakah akan mengekspor koordinat tekstur.

**Returns:**
boolean - apakah akan mengekspor koordinat tekstur.
### getExportTextures() {#getExportTextures--}
```
public boolean getExportTextures()
```


Mencoba menyalin tekstur yang digunakan dalam adegan ke direktori output.

**Returns:**
boolean - Mencoba menyalin tekstur yang digunakan dalam adegan ke direktori output.
### getExportVertexDiffuse() {#getExportVertexDiffuse--}
```
public boolean getExportVertexDiffuse()
```


Mendapatkan apakah akan mengekspor warna difus vertex.

**Returns:**
boolean - apakah akan mengekspor warna difus vertex.
### getExportVertexSpecular() {#getExportVertexSpecular--}
```
public boolean getExportVertexSpecular()
```


Mendapatkan apakah akan mengekspor warna spekular vertex.

**Returns:**
boolean - apakah akan mengekspor warna spekular vertex.
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
### getFlipCoordinateSystem() {#getFlipCoordinateSystem--}
```
public boolean getFlipCoordinateSystem()
```


Mendapatkan apakah sistem koordinat dibalik untuk titik kontrol/normal selama impor/ekspor.

**Returns:**
boolean - apakah sistem koordinat dibalik untuk titik kontrol/normal selama impor/ekspor.
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
### getMeshCompression() {#getMeshCompression--}
```
public boolean getMeshCompression()
```


Mendapatkan apakah akan mengaktifkan kompresi data mesh.

**Returns:**
boolean - apakah akan mengaktifkan kompresi data mesh.
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




### setEmbedTextures(boolean value) {#setEmbedTextures-boolean-}
```
public void setEmbedTextures(boolean value)
```


Sematkan tekstur eksternal ke dalam file U3D, nilai default adalah false.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


Mengatur enkoding default untuk file berbasis teks. Nilai default adalah null yang berarti pengimpor/pengekspor akan menentukan enkoding yang akan digunakan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.nio.charset.Charset | Nilai baru |

### setExportNormals(boolean value) {#setExportNormals-boolean-}
```
public void setExportNormals(boolean value)
```


Mengatur apakah akan mengekspor data normal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

### setExportTextureCoordinates(boolean value) {#setExportTextureCoordinates-boolean-}
```
public void setExportTextureCoordinates(boolean value)
```


Mengatur apakah akan mengekspor koordinat tekstur.

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

### setExportVertexDiffuse(boolean value) {#setExportVertexDiffuse-boolean-}
```
public void setExportVertexDiffuse(boolean value)
```


Mengatur apakah akan mengekspor warna difus vertex.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

### setExportVertexSpecular(boolean value) {#setExportVertexSpecular-boolean-}
```
public void setExportVertexSpecular(boolean value)
```


Mengatur apakah akan mengekspor warna spekular vertex.

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

### setFlipCoordinateSystem(boolean value) {#setFlipCoordinateSystem-boolean-}
```
public void setFlipCoordinateSystem(boolean value)
```


Mengatur apakah sistem koordinat dibalik untuk titik kontrol/normal selama impor/ekspor.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

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

### setMeshCompression(boolean value) {#setMeshCompression-boolean-}
```
public void setMeshCompression(boolean value)
```


Mengatur apakah akan mengaktifkan kompresi data mesh.

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

