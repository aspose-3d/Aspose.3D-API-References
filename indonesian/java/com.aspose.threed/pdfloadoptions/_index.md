---
title: PdfLoadOptions
second_title: Referensi API Aspose.3D untuk Java
description: Options for PDF loading
type: docs
weight: 124
url: /id/java/com.aspose.threed/pdfloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.LoadOptions](../../com.aspose.threed/loadoptions)
```
public class PdfLoadOptions extends LoadOptions
```

Options for PDF loading
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PdfLoadOptions()](#PdfLoadOptions--) | Konstruktor dari [PdfLoadOptions](../../com.aspose.threed/pdfloadoptions) |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEncoding()](#getEncoding--) | Mendapatkan encoding default untuk file berbasis teks. |
| [getFileFormat()](#getFileFormat--) | Mendapatkan format file yang ditentukan dalam opsi Simpan/Muat saat ini. |
| [getFileName()](#getFileName--) | Nama file dari adegan ekspor/impor. |
| [getFileSystem()](#getFileSystem--) | Izinkan pengguna mengatur cara mengelola dependensi eksternal selama muat/simpan. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Mendapatkan kelas pabrik untuk FileSystem. |
| [getLookupPaths()](#getLookupPaths--) | Beberapa file seperti OBJ bergantung pada file eksternal, jalur pencarian akan memungkinkan Aspose.3D mencari file eksternal untuk dimuat. |
| [getPassword()](#getPassword--) | Kata sandi untuk membuka file PDF terenkripsi. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Mengatur encoding default untuk file berbasis teks. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Nama file dari adegan ekspor/impor. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Izinkan pengguna mengatur cara mengelola dependensi eksternal selama muat/simpan. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Mengatur kelas pabrik untuk FileSystem. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Beberapa file seperti OBJ bergantung pada file eksternal, jalur pencarian akan memungkinkan Aspose.3D mencari file eksternal untuk dimuat. |
| [setPassword(byte[] value)](#setPassword-byte---) | Kata sandi untuk membuka file PDF terenkripsi. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfLoadOptions() {#PdfLoadOptions--}
```
public PdfLoadOptions()
```


Konstruktor dari [PdfLoadOptions](../../com.aspose.threed/pdfloadoptions)

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
### getPassword() {#getPassword--}
```
public byte[] getPassword()
```


Kata sandi untuk membuka file PDF terenkripsi.

**Returns:**
byte[] - Kata sandi untuk membuka file PDF terenkripsi.
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

### setPassword(byte[] value) {#setPassword-byte---}
```
public void setPassword(byte[] value)
```


Kata sandi untuk membuka file PDF terenkripsi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte[] | Nilai baru |

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

