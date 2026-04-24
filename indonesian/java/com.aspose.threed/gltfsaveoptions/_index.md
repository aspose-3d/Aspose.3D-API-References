---
title: GltfSaveOptions
second_title: Referensi API Aspose.3D untuk Java
description: Opsi simpan untuk format glTF.
type: docs
weight: 74
url: /id/java/com.aspose.threed/gltfsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class GltfSaveOptions extends SaveOptions
```

Opsi simpan untuk format glTF.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [GltfSaveOptions(FileContentType contentType)](#GltfSaveOptions-com.aspose.threed.FileContentType-) | Konstruktor dari [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions) |
| [GltfSaveOptions(FileFormat format)](#GltfSaveOptions-com.aspose.threed.FileFormat-) | Konstruktor dari [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions) |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getApplyUnitScale()](#getApplyUnitScale--) | Terapkan [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) ke mesh. |
| [getBufferFile()](#getBufferFile--) | Nama file dari file buffer eksternal yang digunakan untuk menyimpan data biner. |
| [getClass()](#getClass--) |  |
| [getDracoCompression()](#getDracoCompression--) | Mendapatkan apakah kompresi draco diaktifkan |
| [getEmbedAssets()](#getEmbedAssets--) | Sematkan semua aset eksternal sebagai base64 ke dalam satu file dalam mode ASCII, nilai default adalah false. |
| [getEncoding()](#getEncoding--) | Mendapatkan encoding default untuk file berbasis teks. |
| [getExportTextures()](#getExportTextures--) | Mencoba menyalin tekstur yang digunakan dalam adegan ke direktori output. |
| [getExternalDracoEncoder()](#getExternalDracoEncoder--) | Gunakan encoder draco eksternal untuk mempercepat kecepatan kompresi draco. |
| [getFallbackNormal()](#getFallbackNormal--) | Ketika pengekspor GLTF2 mendeteksi normal yang tidak valid, ini akan digunakan sebagai pengganti nilai aslinya untuk melewati validasi. |
| [getFileFormat()](#getFileFormat--) | Mendapatkan format file yang ditentukan dalam opsi Simpan/Muat saat ini. |
| [getFileName()](#getFileName--) | Nama file dari adegan ekspor/impor. |
| [getFileSystem()](#getFileSystem--) | Izinkan pengguna mengatur cara mengelola dependensi eksternal selama muat/simpan. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Mendapatkan kelas pabrik untuk FileSystem. |
| [getFlipTexCoordV()](#getFlipTexCoordV--) | Balik komponen koordinat tekstur v(t), nilai default adalah true. |
| [getImageFormat()](#getImageFormat--) | Standard glTF hanya mendukung PNG/JPG sebagai format teksturnya, opsi ini akan memandu bagaimana Aspose.3D mengonversi gambar non-standar ke format yang didukung selama proses ekspor. |
| [getLookupPaths()](#getLookupPaths--) | Beberapa file seperti OBJ bergantung pada file eksternal, jalur pencarian akan memungkinkan Aspose.3D mencari file eksternal untuk dimuat. |
| [getMaterialConverter()](#getMaterialConverter--) | Konverter khusus untuk mengonversi material geometri menjadi material PBR. Jika tidak ditetapkan, pengekspor glTF 2.0 akan secara otomatis mengonversi material standar menjadi material PBR. |
| [getPrettyPrint()](#getPrettyPrint--) | Konten JSON dari file GLTF diindentasi untuk kemudahan membaca manusia, nilai default adalah false. |
| [getSaveExtras()](#getSaveExtras--) | Simpan properti dinamis objek scene ke dalam bidang 'extra' di file glTF yang dihasilkan. |
| [getUseCommonMaterials()](#getUseCommonMaterials--) | Serialisasikan material menggunakan ekstensi material umum KHR, nilai default adalah false. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setApplyUnitScale(boolean value)](#setApplyUnitScale-boolean-) | Terapkan [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) ke mesh. |
| [setBufferFile(String value)](#setBufferFile-java.lang.String-) | Nama file dari file buffer eksternal yang digunakan untuk menyimpan data biner. |
| [setDracoCompression(boolean value)](#setDracoCompression-boolean-) | Menentukan apakah akan mengaktifkan kompresi draco. |
| [setEmbedAssets(boolean value)](#setEmbedAssets-boolean-) | Sematkan semua aset eksternal sebagai base64 ke dalam satu file dalam mode ASCII, nilai default adalah false. |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Mengatur encoding default untuk file berbasis teks. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | Mencoba menyalin tekstur yang digunakan dalam adegan ke direktori output. |
| [setExternalDracoEncoder(String value)](#setExternalDracoEncoder-java.lang.String-) | Gunakan encoder draco eksternal untuk mempercepat kecepatan kompresi draco. |
| [setFallbackNormal(Vector3 value)](#setFallbackNormal-com.aspose.threed.Vector3-) | Ketika pengekspor GLTF2 mendeteksi normal yang tidak valid, ini akan digunakan sebagai pengganti nilai aslinya untuk melewati validasi. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Nama file dari adegan ekspor/impor. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Izinkan pengguna mengatur cara mengelola dependensi eksternal selama muat/simpan. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Mengatur kelas pabrik untuk FileSystem. |
| [setFlipTexCoordV(boolean value)](#setFlipTexCoordV-boolean-) | Balik komponen koordinat tekstur v(t), nilai default adalah true. |
| [setImageFormat(GltfEmbeddedImageFormat value)](#setImageFormat-com.aspose.threed.GltfEmbeddedImageFormat-) | Standard glTF hanya mendukung PNG/JPG sebagai format teksturnya, opsi ini akan memandu bagaimana Aspose.3D mengonversi gambar non-standar ke format yang didukung selama proses ekspor. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Beberapa file seperti OBJ bergantung pada file eksternal, jalur pencarian akan memungkinkan Aspose.3D mencari file eksternal untuk dimuat. |
| [setMaterialConverter(MaterialConverter value)](#setMaterialConverter-com.aspose.threed.MaterialConverter-) | Konverter khusus untuk mengonversi material geometri menjadi material PBR. Jika tidak ditetapkan, pengekspor glTF 2.0 akan secara otomatis mengonversi material standar menjadi material PBR. |
| [setPrettyPrint(boolean value)](#setPrettyPrint-boolean-) | Konten JSON dari file GLTF diindentasi untuk kemudahan membaca manusia, nilai default adalah false. |
| [setSaveExtras(boolean value)](#setSaveExtras-boolean-) | Simpan properti dinamis objek scene ke dalam bidang 'extra' di file glTF yang dihasilkan. |
| [setUseCommonMaterials(boolean value)](#setUseCommonMaterials-boolean-) | Serialisasikan material menggunakan ekstensi material umum KHR, nilai default adalah false. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GltfSaveOptions(FileContentType contentType) {#GltfSaveOptions-com.aspose.threed.FileContentType-}
```
public GltfSaveOptions(FileContentType contentType)
```


Konstruktor dari [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) |  |

### GltfSaveOptions(FileFormat format) {#GltfSaveOptions-com.aspose.threed.FileFormat-}
```
public GltfSaveOptions(FileFormat format)
```


Konstruktor dari [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| format | [FileFormat](../../com.aspose.threed/fileformat) |  |

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
### getApplyUnitScale() {#getApplyUnitScale--}
```
public boolean getApplyUnitScale()
```


Terapkan [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) ke mesh. Nilai default adalah false.

**Returns:**
boolean - Terapkan [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) ke mesh. Nilai default adalah false.
### getBufferFile() {#getBufferFile--}
```
public String getBufferFile()
```


Nama file dari buffer eksternal yang digunakan untuk menyimpan data biner. Jika file ini tidak ditentukan, Aspose.3D akan menghasilkan nama untuk Anda. Ini diabaikan saat mengekspor glTF dalam mode biner.

**Returns:**
java.lang.String - Nama file dari buffer eksternal yang digunakan untuk menyimpan data biner. Jika file ini tidak ditentukan, Aspose.3D akan menghasilkan nama untuk Anda. Ini diabaikan saat mengekspor glTF dalam mode biner.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDracoCompression() {#getDracoCompression--}
```
public boolean getDracoCompression()
```


Mendapatkan apakah kompresi draco diaktifkan

**Returns:**
boolean - apakah akan mengaktifkan kompresi draco
### getEmbedAssets() {#getEmbedAssets--}
```
public boolean getEmbedAssets()
```


Sematkan semua aset eksternal sebagai base64 ke dalam satu file dalam mode ASCII, nilai default adalah false.

**Returns:**
boolean - Menyematkan semua aset eksternal sebagai base64 ke dalam satu file dalam mode ASCII, nilai default adalah false.
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


Mendapatkan encoding default untuk file berbasis teks. Nilai default adalah null yang berarti pengimpor/pengekspor akan menentukan encoding yang akan digunakan.

**Returns:**
java.nio.charset.Charset - encoding default untuk file berbasis teks. Nilai default adalah null yang berarti pengimpor/pengekspor akan menentukan encoding yang akan digunakan.
### getExportTextures() {#getExportTextures--}
```
public boolean getExportTextures()
```


Mencoba menyalin tekstur yang digunakan dalam adegan ke direktori output.

**Returns:**
boolean - Mencoba menyalin tekstur yang digunakan dalam adegan ke direktori output.
### getExternalDracoEncoder() {#getExternalDracoEncoder--}
```
public String getExternalDracoEncoder()
```


Gunakan encoder draco eksternal untuk mempercepat kecepatan kompresi draco.

**Returns:**
java.lang.String - Gunakan encoder draco eksternal untuk mempercepat kecepatan kompresi draco. **Remarks:** Aspose.3D akan membuat proses sub baru untuk mengkodekan mesh ke format draco, gunakan dengan risiko Anda sendiri.
### getFallbackNormal() {#getFallbackNormal--}
```
public Vector3 getFallbackNormal()
```


Ketika pengekspor GLTF2 mendeteksi normal yang tidak valid, nilai ini akan digunakan menggantikan nilai aslinya untuk melewati validasi. Nilai default adalah (0, 1, 0).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - When GLTF2 exporter detected an invalid normal, this will be used instead of its original value to bypass the validation. Default value is (0, 1, 0)
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
### getFlipTexCoordV() {#getFlipTexCoordV--}
```
public boolean getFlipTexCoordV()
```


Balik komponen koordinat tekstur v(t), nilai default adalah true.

**Returns:**
boolean - Membalik komponen koordinat tekstur v(t), nilai default adalah true.
### getImageFormat() {#getImageFormat--}
```
public GltfEmbeddedImageFormat getImageFormat()
```


Standard glTF hanya mendukung PNG/JPG sebagai format teksturnya, opsi ini akan memandu bagaimana Aspose.3D mengonversi gambar non-standar ke format yang didukung selama proses ekspor. Nilai default adalah [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG)

**Returns:**
[GltfEmbeddedImageFormat](../../com.aspose.threed/gltfembeddedimageformat) - Standard glTF only supports PNG/JPG as its texture format, this option will guide how Aspose.3D convert the non-standard images to supported format during the exporting. Default value is [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG)
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


Konverter khusus untuk mengonversi material geometri menjadi material PBR. Jika tidak ditetapkan, pengekspor glTF 2.0 akan secara otomatis mengonversi material standar menjadi material PBR. Nilai default adalah null. Properti ini digunakan saat mengekspor sebuah scene ke file glTF 2.0.

**Returns:**
[MaterialConverter](../../com.aspose.threed/materialconverter) - Custom converter to convert the geometry's material to PBR material If this is unassigned, glTF 2.0 exporter will automatically convert the standard material to PBR material. Default value is null This property is used when exporting a scene to a glTF 2.0 file.
### getPrettyPrint() {#getPrettyPrint--}
```
public boolean getPrettyPrint()
```


Konten JSON dari file GLTF diindentasi untuk kemudahan membaca manusia, nilai default adalah false.

**Returns:**
boolean - Konten JSON dari file GLTF diindentasi untuk kemudahan membaca manusia, nilai default adalah false.
### getSaveExtras() {#getSaveExtras--}
```
public boolean getSaveExtras()
```


Simpan properti dinamis objek scene ke dalam bidang 'extra' di file GLTF yang dihasilkan. Ini berguna untuk menyediakan data spesifik aplikasi. Nilai default adalah false.

**Returns:**
boolean - Simpan properti dinamis objek scene ke dalam bidang 'extra' di file GLTF yang dihasilkan. Ini berguna untuk menyediakan data spesifik aplikasi. Nilai default adalah false.
### getUseCommonMaterials() {#getUseCommonMaterials--}
```
public boolean getUseCommonMaterials()
```


Serialisasikan material menggunakan ekstensi material umum KHR, nilai default adalah false. Mengatur ini ke false akan menyebabkan Aspose.3D mengekspor sekumpulan shader vertex/fragment jika [getExportShaders](../../com.aspose.threed/gltfsaveoptions\#getExportShaders)

**Returns:**
boolean - Serialisasikan material menggunakan ekstensi material umum KHR, nilai default adalah false. Mengatur ini ke false akan menyebabkan Aspose.3D mengekspor sekumpulan shader vertex/fragment jika [getExportShaders](../../com.aspose.threed/gltfsaveoptions\#getExportShaders) **Remarks:** Properti ini hanya berfungsi untuk glTF 1.0
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




### setApplyUnitScale(boolean value) {#setApplyUnitScale-boolean-}
```
public void setApplyUnitScale(boolean value)
```


Terapkan [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) ke mesh. Nilai default adalah false.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

### setBufferFile(String value) {#setBufferFile-java.lang.String-}
```
public void setBufferFile(String value)
```


Nama file dari buffer eksternal yang digunakan untuk menyimpan data biner. Jika file ini tidak ditentukan, Aspose.3D akan menghasilkan nama untuk Anda. Ini diabaikan saat mengekspor glTF dalam mode biner.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nilai baru |

### setDracoCompression(boolean value) {#setDracoCompression-boolean-}
```
public void setDracoCompression(boolean value)
```


Menentukan apakah akan mengaktifkan kompresi draco.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

### setEmbedAssets(boolean value) {#setEmbedAssets-boolean-}
```
public void setEmbedAssets(boolean value)
```


Sematkan semua aset eksternal sebagai base64 ke dalam satu file dalam mode ASCII, nilai default adalah false.

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

### setExportTextures(boolean value) {#setExportTextures-boolean-}
```
public void setExportTextures(boolean value)
```


Mencoba menyalin tekstur yang digunakan dalam adegan ke direktori output.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

### setExternalDracoEncoder(String value) {#setExternalDracoEncoder-java.lang.String-}
```
public void setExternalDracoEncoder(String value)
```


Gunakan encoder draco eksternal untuk mempercepat kecepatan kompresi draco.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nilai baru **Remarks:** Aspose.3D akan membuat proses sub baru untuk mengkodekan mesh ke format draco, gunakan dengan risiko Anda sendiri. |

### setFallbackNormal(Vector3 value) {#setFallbackNormal-com.aspose.threed.Vector3-}
```
public void setFallbackNormal(Vector3 value)
```


Ketika pengekspor GLTF2 mendeteksi normal yang tidak valid, nilai ini akan digunakan menggantikan nilai aslinya untuk melewati validasi. Nilai default adalah (0, 1, 0).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nilai baru |

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

### setFlipTexCoordV(boolean value) {#setFlipTexCoordV-boolean-}
```
public void setFlipTexCoordV(boolean value)
```


Balik komponen koordinat tekstur v(t), nilai default adalah true.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

### setImageFormat(GltfEmbeddedImageFormat value) {#setImageFormat-com.aspose.threed.GltfEmbeddedImageFormat-}
```
public void setImageFormat(GltfEmbeddedImageFormat value)
```


Standard glTF hanya mendukung PNG/JPG sebagai format teksturnya, opsi ini akan memandu bagaimana Aspose.3D mengonversi gambar non-standar ke format yang didukung selama proses ekspor. Nilai default adalah [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [GltfEmbeddedImageFormat](../../com.aspose.threed/gltfembeddedimageformat) | Nilai baru |

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


Konverter khusus untuk mengonversi material geometri menjadi material PBR. Jika tidak ditetapkan, pengekspor glTF 2.0 akan secara otomatis mengonversi material standar menjadi material PBR. Nilai default adalah null. Properti ini digunakan saat mengekspor sebuah scene ke file glTF 2.0.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [MaterialConverter](../../com.aspose.threed/materialconverter) | Nilai baru |

### setPrettyPrint(boolean value) {#setPrettyPrint-boolean-}
```
public void setPrettyPrint(boolean value)
```


Konten JSON dari file GLTF diindentasi untuk kemudahan membaca manusia, nilai default adalah false.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

### setSaveExtras(boolean value) {#setSaveExtras-boolean-}
```
public void setSaveExtras(boolean value)
```


Simpan properti dinamis objek scene ke dalam bidang 'extra' di file GLTF yang dihasilkan. Ini berguna untuk menyediakan data spesifik aplikasi. Nilai default adalah false.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

### setUseCommonMaterials(boolean value) {#setUseCommonMaterials-boolean-}
```
public void setUseCommonMaterials(boolean value)
```


Serialisasikan material menggunakan ekstensi material umum KHR, nilai default adalah false. Mengatur ini ke false akan menyebabkan Aspose.3D mengekspor sekumpulan shader vertex/fragment jika [getExportShaders](../../com.aspose.threed/gltfsaveoptions\#getExportShaders)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru **Remarks:** Properti ini hanya berfungsi untuk glTF 1.0 |

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

