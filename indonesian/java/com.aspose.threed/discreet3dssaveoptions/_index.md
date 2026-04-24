---
title: Discreet3dsSaveOptions
second_title: Referensi API Aspose.3D untuk Java
description: Opsi penyimpanan untuk file 3DS.
type: docs
weight: 44
url: /id/java/com.aspose.threed/discreet3dssaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class Discreet3dsSaveOptions extends SaveOptions
```

Opsi penyimpanan untuk file 3DS.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Discreet3dsSaveOptions()](#Discreet3dsSaveOptions--) | Konstruktor dari [Discreet3dsSaveOptions](../../com.aspose.threed/discreet3dssaveoptions) |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDuplicatedNameCounterBase()](#getDuplicatedNameCounterBase--) | Penghitung yang digunakan untuk menghasilkan nama baru bagi nama yang duplikat, nilai default adalah 2. |
| [getDuplicatedNameCounterFormat()](#getDuplicatedNameCounterFormat--) | Format penghitung duplikat, nilai default adalah string kosong. |
| [getDuplicatedNameSeparator()](#getDuplicatedNameSeparator--) | Pemisah antara nama objek dan penghitung duplikat, nilai default adalah "\_". |
| [getEncoding()](#getEncoding--) | Mendapatkan encoding default untuk file berbasis teks. |
| [getExportCamera()](#getExportCamera--) | Mendapatkan apakah mengekspor semua kamera dalam adegan. |
| [getExportLight()](#getExportLight--) | Mendapatkan apakah mengekspor semua lampu dalam adegan. |
| [getExportTextures()](#getExportTextures--) | Mencoba menyalin tekstur yang digunakan dalam adegan ke direktori output. |
| [getFileFormat()](#getFileFormat--) | Mendapatkan format file yang ditentukan dalam opsi Simpan/Muat saat ini. |
| [getFileName()](#getFileName--) | Nama file dari adegan ekspor/impor. |
| [getFileSystem()](#getFileSystem--) | Izinkan pengguna mengatur cara mengelola dependensi eksternal selama muat/simpan. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Mendapatkan kelas pabrik untuk FileSystem. |
| [getFlipCoordinateSystem()](#getFlipCoordinateSystem--) | Mendapatkan pembalikan sistem koordinat titik kontrol/normal selama impor/ekspor. |
| [getGammaCorrectedColor()](#getGammaCorrectedColor--) | File 3ds dapat berisi warna asli dan warna yang dikoreksi gamma untuk atribut yang sama, Mengatur ini ke true akan menggunakan warna yang dikoreksi gamma jika memungkinkan, jika tidak Aspose.3D akan mencoba menggunakan warna asli. |
| [getHighPreciseColor()](#getHighPreciseColor--) | Jika ini true, file 3ds yang dihasilkan akan menggunakan warna dengan presisi tinggi, artinya setiap saluran merah/hijau/biru berada dalam format float 32bit. |
| [getLookupPaths()](#getLookupPaths--) | Beberapa file seperti OBJ bergantung pada file eksternal, jalur pencarian akan memungkinkan Aspose.3D mencari file eksternal untuk dimuat. |
| [getMasterScale()](#getMasterScale--) | Mendapatkan skala utama yang digunakan saat mengekspor. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDuplicatedNameCounterBase(int value)](#setDuplicatedNameCounterBase-int-) | Penghitung yang digunakan untuk menghasilkan nama baru bagi nama yang duplikat, nilai default adalah 2. |
| [setDuplicatedNameCounterFormat(String value)](#setDuplicatedNameCounterFormat-java.lang.String-) | Format penghitung duplikat, nilai default adalah string kosong. |
| [setDuplicatedNameSeparator(String value)](#setDuplicatedNameSeparator-java.lang.String-) | Pemisah antara nama objek dan penghitung duplikat, nilai default adalah "\_". |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Mengatur encoding default untuk file berbasis teks. |
| [setExportCamera(boolean value)](#setExportCamera-boolean-) | Mengatur apakah mengekspor semua kamera dalam adegan. |
| [setExportLight(boolean value)](#setExportLight-boolean-) | Mengatur apakah mengekspor semua lampu dalam adegan. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | Mencoba menyalin tekstur yang digunakan dalam adegan ke direktori output. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Nama file dari adegan ekspor/impor. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Izinkan pengguna mengatur cara mengelola dependensi eksternal selama muat/simpan. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Mengatur kelas pabrik untuk FileSystem. |
| [setFlipCoordinateSystem(boolean value)](#setFlipCoordinateSystem-boolean-) | Mengatur pembalikan sistem koordinat titik kontrol/normal selama impor/ekspor. |
| [setGammaCorrectedColor(boolean value)](#setGammaCorrectedColor-boolean-) | File 3ds dapat berisi warna asli dan warna yang dikoreksi gamma untuk atribut yang sama, Mengatur ini ke true akan menggunakan warna yang dikoreksi gamma jika memungkinkan, jika tidak Aspose.3D akan mencoba menggunakan warna asli. |
| [setHighPreciseColor(boolean value)](#setHighPreciseColor-boolean-) | Jika ini true, file 3ds yang dihasilkan akan menggunakan warna dengan presisi tinggi, artinya setiap saluran merah/hijau/biru berada dalam format float 32bit. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Beberapa file seperti OBJ bergantung pada file eksternal, jalur pencarian akan memungkinkan Aspose.3D mencari file eksternal untuk dimuat. |
| [setMasterScale(double value)](#setMasterScale-double-) | Mengatur skala utama yang digunakan saat mengekspor. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Discreet3dsSaveOptions() {#Discreet3dsSaveOptions--}
```
public Discreet3dsSaveOptions()
```


Konstruktor dari [Discreet3dsSaveOptions](../../com.aspose.threed/discreet3dssaveoptions)

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
### getDuplicatedNameCounterBase() {#getDuplicatedNameCounterBase--}
```
public int getDuplicatedNameCounterBase()
```


Penghitung yang digunakan untuk menghasilkan nama baru bagi nama yang duplikat, nilai default adalah 2.

**Returns:**
int - Penghitung yang digunakan untuk menghasilkan nama baru bagi nama yang duplikat, nilai default adalah 2.
### getDuplicatedNameCounterFormat() {#getDuplicatedNameCounterFormat--}
```
public String getDuplicatedNameCounterFormat()
```


Format penghitung duplikat, nilai default adalah string kosong.

**Returns:**
java.lang.String - Format penghitung duplikat, nilai default adalah string kosong.
### getDuplicatedNameSeparator() {#getDuplicatedNameSeparator--}
```
public String getDuplicatedNameSeparator()
```


Pemisor antara nama objek dan penghitung duplikat, nilai default adalah "\_". Ketika adegan berisi objek-objek yang menggunakan nama yang sama, ekspor 3DS Aspose.3D akan menghasilkan nama yang berbeda untuk objek tersebut. Misalnya ada dua node bernama "Box", node pertama akan memiliki nama "Box", dan node kedua akan mendapatkan nama baru "Box\_2" menggunakan konfigurasi default.

**Returns:**
java.lang.String - Pemisor antara nama objek dan penghitung duplikat, nilai default adalah "\_". Ketika adegan berisi objek-objek yang menggunakan nama yang sama, ekspor 3DS Aspose.3D akan menghasilkan nama yang berbeda untuk objek tersebut. Misalnya ada dua node bernama "Box", node pertama akan memiliki nama "Box", dan node kedua akan mendapatkan nama baru "Box\_2" menggunakan konfigurasi default.
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


Mendapatkan encoding default untuk file berbasis teks. Nilai default adalah null yang berarti pengimpor/pengekspor akan menentukan encoding yang akan digunakan.

**Returns:**
java.nio.charset.Charset - encoding default untuk file berbasis teks. Nilai default adalah null yang berarti pengimpor/pengekspor akan menentukan encoding yang akan digunakan.
### getExportCamera() {#getExportCamera--}
```
public boolean getExportCamera()
```


Mendapatkan apakah mengekspor semua kamera dalam adegan.

**Returns:**
boolean - apakah mengekspor semua kamera dalam adegan.
### getExportLight() {#getExportLight--}
```
public boolean getExportLight()
```


Mendapatkan apakah mengekspor semua lampu dalam adegan.

**Returns:**
boolean - apakah mengekspor semua lampu dalam adegan.
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
### getFlipCoordinateSystem() {#getFlipCoordinateSystem--}
```
public boolean getFlipCoordinateSystem()
```


Mendapatkan pembalikan sistem koordinat titik kontrol/normal selama impor/ekspor.

**Returns:**
boolean - membalik sistem koordinat titik kontrol/normal selama proses impor/ekspor.
### getGammaCorrectedColor() {#getGammaCorrectedColor--}
```
public boolean getGammaCorrectedColor()
```


File 3ds dapat berisi warna asli dan warna yang dikoreksi gamma untuk atribut yang sama, Mengatur ini ke true akan menggunakan warna yang dikoreksi gamma jika memungkinkan, jika tidak Aspose.3D akan mencoba menggunakan warna asli.

**Returns:**
boolean - Sebuah file 3ds dapat berisi warna asli dan warna yang dikoreksi gamma untuk atribut yang sama, Mengatur ini ke true akan menggunakan warna yang dikoreksi gamma jika memungkinkan, jika tidak Aspose.3D akan mencoba menggunakan warna asli.
### getHighPreciseColor() {#getHighPreciseColor--}
```
public boolean getHighPreciseColor()
```


Jika ini true, file 3ds yang dihasilkan akan menggunakan warna dengan presisi tinggi, artinya setiap saluran merah/hijau/biru menggunakan float 32bit. Jika tidak, file yang dihasilkan akan menggunakan warna 24bit, setiap saluran menggunakan byte 8bit. Nilai default adalah false, karena tidak semua aplikasi mendukung warna presisi tinggi.

**Returns:**
boolean - Jika ini true, file 3ds yang dihasilkan akan menggunakan warna dengan presisi tinggi, artinya setiap saluran merah/hijau/biru menggunakan float 32bit. Jika tidak, file yang dihasilkan akan menggunakan warna 24bit, setiap saluran menggunakan byte 8bit. Nilai default adalah false, karena tidak semua aplikasi mendukung warna presisi tinggi.
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
### getMasterScale() {#getMasterScale--}
```
public double getMasterScale()
```


Mendapatkan skala utama yang digunakan saat mengekspor.

**Returns:**
double - skala utama yang digunakan saat mengekspor.
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




### setDuplicatedNameCounterBase(int value) {#setDuplicatedNameCounterBase-int-}
```
public void setDuplicatedNameCounterBase(int value)
```


Penghitung yang digunakan untuk menghasilkan nama baru bagi nama yang duplikat, nilai default adalah 2.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Nilai baru |

### setDuplicatedNameCounterFormat(String value) {#setDuplicatedNameCounterFormat-java.lang.String-}
```
public void setDuplicatedNameCounterFormat(String value)
```


Format penghitung duplikat, nilai default adalah string kosong.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nilai baru |

### setDuplicatedNameSeparator(String value) {#setDuplicatedNameSeparator-java.lang.String-}
```
public void setDuplicatedNameSeparator(String value)
```


Pemisor antara nama objek dan penghitung duplikat, nilai default adalah "\_". Ketika adegan berisi objek-objek yang menggunakan nama yang sama, ekspor 3DS Aspose.3D akan menghasilkan nama yang berbeda untuk objek tersebut. Misalnya ada dua node bernama "Box", node pertama akan memiliki nama "Box", dan node kedua akan mendapatkan nama baru "Box\_2" menggunakan konfigurasi default.

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

### setExportCamera(boolean value) {#setExportCamera-boolean-}
```
public void setExportCamera(boolean value)
```


Mengatur apakah mengekspor semua kamera dalam adegan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

### setExportLight(boolean value) {#setExportLight-boolean-}
```
public void setExportLight(boolean value)
```


Mengatur apakah mengekspor semua lampu dalam adegan.

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

### setFlipCoordinateSystem(boolean value) {#setFlipCoordinateSystem-boolean-}
```
public void setFlipCoordinateSystem(boolean value)
```


Mengatur pembalikan sistem koordinat titik kontrol/normal selama impor/ekspor.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

### setGammaCorrectedColor(boolean value) {#setGammaCorrectedColor-boolean-}
```
public void setGammaCorrectedColor(boolean value)
```


File 3ds dapat berisi warna asli dan warna yang dikoreksi gamma untuk atribut yang sama, Mengatur ini ke true akan menggunakan warna yang dikoreksi gamma jika memungkinkan, jika tidak Aspose.3D akan mencoba menggunakan warna asli.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

### setHighPreciseColor(boolean value) {#setHighPreciseColor-boolean-}
```
public void setHighPreciseColor(boolean value)
```


Jika ini true, file 3ds yang dihasilkan akan menggunakan warna dengan presisi tinggi, artinya setiap saluran merah/hijau/biru menggunakan float 32bit. Jika tidak, file yang dihasilkan akan menggunakan warna 24bit, setiap saluran menggunakan byte 8bit. Nilai default adalah false, karena tidak semua aplikasi mendukung warna presisi tinggi.

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

### setMasterScale(double value) {#setMasterScale-double-}
```
public void setMasterScale(double value)
```


Mengatur skala utama yang digunakan saat mengekspor.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

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

