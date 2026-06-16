---
title: "RvmSaveOptions"
second_title: "Aspose.3D for Java API Referansı"
description: "Aveva PDMS RVM dosyası için kaydetme seçenekleri."
type: docs
weight: 158
url: /tr/java/com.aspose.threed/rvmsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class RvmSaveOptions extends SaveOptions
```

Avea PDMS RVM dosyası için kaydetme seçenekleri. **Örnek:** Aşağıdaki kod, RVM'de özelliğin nasıl dışa aktarılacağını gösterir.

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
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [RvmSaveOptions()](#RvmSaveOptions--) | [RvmSaveOptions](../../com.aspose.threed/rvmsaveoptions) yapıcı metodu |
| [RvmSaveOptions(FileContentType contentType)](#RvmSaveOptions-com.aspose.threed.FileContentType-) | [RvmSaveOptions](../../com.aspose.threed/rvmsaveoptions) yapıcı metodu |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttributeListFile()](#getAttributeListFile--) | Özellik listesi dosyasının dosya adını alır, bu özellik tanımsız olduğunda dışa aktarıcı .rvm dosya adına dayanarak bir ad oluşturur, varsayılan değer null'dır. |
| [getAttributePrefix()](#getAttributePrefix--) | Dışa aktarılacak özelliklerin önekini alır, dışa aktarılan özellik önek içermez, farklı önekli özel özellikler dışa aktarılmaz, varsayılan değer 'rvm:'dır. |
| [getAuthor()](#getAuthor--) | Yazar bilgisi, varsayılan değer '3d@aspose' |
| [getClass()](#getClass--) |  |
| [getCreationTime()](#getCreationTime--) | Bu dosyayı dışa aktaran zaman damgası, varsayılan değer geçerli zaman |
| [getEncoding()](#getEncoding--) | Metin tabanlı dosyalar için varsayılan kodlamayı alır. |
| [getExportAttributes()](#getExportAttributes--) | Özellik listesini harici bir .att dosyasına dışa aktarılıp aktarılmayacağını alır, varsayılan değer false. |
| [getExportTextures()](#getExportTextures--) | Sahnede kullanılan dokuları çıktı dizinine kopyalamayı dener. |
| [getFileFormat()](#getFileFormat--) | Mevcut Kaydet/Yükle seçeneğinde belirtilen dosya biçimini alır. |
| [getFileName()](#getFileName--) | Dışa aktarma/içeri aktarma sahnesinin dosya adı. |
| [getFileNote()](#getFileNote--) | Dosya başlığındaki dosya notu. |
| [getFileSystem()](#getFileSystem--) | Kullanıcının yükleme/kaydetme sırasında harici bağımlılıkları nasıl yöneteceğini ele almasına izin verir. |
| [getFileSystemFactory()](#getFileSystemFactory--) | FileSystem için fabrika sınıfını alır. |
| [getLookupPaths()](#getLookupPaths--) | OBJ gibi bazı dosyalar harici dosyalara bağımlıdır, arama yolları Aspose.3D'nin yüklemek için harici dosyayı bulmasına izin verir. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAttributeListFile(String value)](#setAttributeListFile-java.lang.String-) | Özellik listesi dosyasının dosya adını ayarlar, bu özellik tanımlı değilse dışa aktarıcı .rvm dosya adına göre bir ad oluşturur, varsayılan değer null. |
| [setAttributePrefix(String value)](#setAttributePrefix-java.lang.String-) | Dışa aktarılacak özelliklerin önekini ayarlar, dışa aktarılan özellik öneksiz olur, farklı önekli özel özellikler dışa aktarılmaz, varsayılan değer 'rvm:'. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Yazar bilgisi, varsayılan değer '3d@aspose' |
| [setCreationTime(String value)](#setCreationTime-java.lang.String-) | Bu dosyayı dışa aktaran zaman damgası, varsayılan değer geçerli zaman |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Metin tabanlı dosyalar için varsayılan kodlamayı ayarlar. |
| [setExportAttributes(boolean value)](#setExportAttributes-boolean-) | Özellik listesini harici bir .att dosyasına dışa aktarılıp aktarılmayacağını ayarlar, varsayılan değer false. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | Sahnede kullanılan dokuları çıktı dizinine kopyalamayı dener. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Dışa aktarma/içeri aktarma sahnesinin dosya adı. |
| [setFileNote(String value)](#setFileNote-java.lang.String-) | Dosya başlığındaki dosya notu. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Kullanıcının yükleme/kaydetme sırasında harici bağımlılıkları nasıl yöneteceğini ele almasına izin verir. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | FileSystem için fabrika sınıfını ayarlar. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | OBJ gibi bazı dosyalar harici dosyalara bağımlıdır, arama yolları Aspose.3D'nin yüklemek için harici dosyayı bulmasına izin verir. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RvmSaveOptions() {#RvmSaveOptions--}
```
public RvmSaveOptions()
```


[RvmSaveOptions](../../com.aspose.threed/rvmsaveoptions) yapıcı metodu

### RvmSaveOptions(FileContentType contentType) {#RvmSaveOptions-com.aspose.threed.FileContentType-}
```
public RvmSaveOptions(FileContentType contentType)
```


[RvmSaveOptions](../../com.aspose.threed/rvmsaveoptions) yapıcı metodu

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) | Metin mi yoksa ikili RVM dosyası mı? |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAttributeListFile() {#getAttributeListFile--}
```
public String getAttributeListFile()
```


Özellik listesi dosyasının dosya adını alır, bu özellik tanımsız olduğunda dışa aktarıcı .rvm dosya adına dayanarak bir ad oluşturur, varsayılan değer null'dır.

**Returns:**
java.lang.String - özellik listesi dosyasının dosya adı, bu özellik tanımlı değilse dışa aktarıcı .rvm dosya adına göre bir ad oluşturur, varsayılan değer null. **Örnek:** Aşağıdaki kod, RVM'de özelliğin nasıl dışa aktarılacağını gösterir.

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


Dışa aktarılacak özelliklerin önekini alır, dışa aktarılan özellik öneksiz olur, farklı önekli özel özellikler dışa aktarılmaz, varsayılan değer 'rvm:'. Örneğin bir özellik rvm:Refno=345 ise, dışa aktarılan özellik Refno = 345 olur, önek kaldırılır.

**Returns:**
java.lang.String - dışa aktarılacak özelliklerin önekini, dışa aktarılan özellik öneksiz olur, farklı önekli özel özellikler dışa aktarılmaz, varsayılan değer 'rvm:'. Örneğin bir özellik rvm:Refno=345 ise, dışa aktarılan özellik Refno = 345 olur, önek kaldırılır. **Örnek:** Aşağıdaki kod, RVM'de özelliğin nasıl dışa aktarılacağını gösterir.

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


Yazar bilgisi, varsayılan değer '3d@aspose'

**Returns:**
java.lang.String - Yazar bilgisi, varsayılan değer '3d@aspose' **Örnek:** Aşağıdaki kod, RVM'de özelliğin nasıl dışa aktarılacağını gösterir.

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


Bu dosyayı dışa aktaran zaman damgası, varsayılan değer geçerli zaman

**Returns:**
java.lang.String - Bu dosyayı dışa aktaran zaman damgası, varsayılan değer geçerli zaman
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


Metin tabanlı dosyalar için varsayılan kodlamayı alır. Varsayılan değer null'dır, bu da içe aktarıcı/dışa aktarıcının hangi kodlamayı kullanacağına karar vereceği anlamına gelir.

**Returns:**
java.nio.charset.Charset - metin tabanlı dosyalar için varsayılan kodlama. Varsayılan değer null'dır, bu da içe aktarıcı/dışa aktarıcının hangi kodlamayı kullanacağına karar vereceği anlamına gelir.
### getExportAttributes() {#getExportAttributes--}
```
public boolean getExportAttributes()
```


Özellik listesini harici bir .att dosyasına dışa aktarılıp aktarılmayacağını alır, varsayılan değer false.

**Returns:**
boolean - özellik listesini harici bir .att dosyasına dışa aktarılıp aktarılmayacağını, varsayılan değer false. **Örnek:** Aşağıdaki kod, RVM'de özelliğin nasıl dışa aktarılacağını gösterir.

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


Sahnede kullanılan dokuları çıktı dizinine kopyalamayı dener.

**Returns:**
boolean - sahnede kullanılan dokuları çıktı dizinine kopyalamayı dene.
### getFileFormat() {#getFileFormat--}
```
public FileFormat getFileFormat()
```


Mevcut Kaydet/Yükle seçeneğinde belirtilen dosya biçimini alır.

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - the file format that specified in current Save/Load option.
### getFileName() {#getFileName--}
```
public String getFileName()
```


Dışa aktarma/içe aktarma sahnesinin dosya adı. Bu isteğe bağlıdır, ancak OBJ'nin materyali gibi harici varlıkları serileştirirken faydalıdır.

**Returns:**
java.lang.String - Dışa aktarma/içe aktarma sahnesinin dosya adı. Bu isteğe bağlıdır, ancak OBJ'nin materyali gibi harici varlıkları serileştirirken faydalıdır.
### getFileNote() {#getFileNote--}
```
public String getFileNote()
```


Dosya başlığındaki dosya notu.

**Returns:**
java.lang.String - Dosya başlığındaki dosya notu. **Örnek:** Aşağıdaki kod, RVM'de özelliğin nasıl dışa aktarılacağını gösterir.

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


Kullanıcının yükleme/kaydetme sırasında harici bağımlılıkları nasıl yöneteceğini ele almasına izin verir.

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - Allow user to handle how to manage the external dependencies during load/save. **Example:** The default FileSystem is LocalFileSystem, it is not safe in environment like server side, But you can override the file system access by specifying a different implementation. Aspose.3D provides different FileSystem implementation like:

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

Ve ayrıca kendi uygulamanızı da kullanabilirsiniz.

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


FileSystem için fabrika sınıfını alır. Varsayılan fabrika, sunucu ortamı için uygun olmayan com.aspose.threed.LocalFileSystem'i oluşturur.

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


OBJ gibi bazı dosyalar harici dosyalara bağımlıdır, arama yolları Aspose.3D'nin yüklemek için harici dosyayı bulmasına izin verir.

**Returns:**
java.util.ArrayList<java.lang.String> - OBJ gibi bazı dosyalar harici dosyalara bağımlıdır, arama yolları Aspose.3D'nin yüklemek için harici dosyayı bulmasına izin verir. **Örnek:** Aşağıdaki kod, arama dokularını manuel olarak nasıl belirteceğinizi gösterir, böylece içe aktarıcı bulabilir

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


Özellik listesi dosyasının dosya adını ayarlar, bu özellik tanımlı değilse dışa aktarıcı .rvm dosya adına göre bir ad oluşturur, varsayılan değer null.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.String | Yeni değer **Örnek:** Aşağıdaki kod, RVM'de özelliğin nasıl dışa aktarılacağını gösterir. |

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


Dışa aktarılacak özelliklerin önekini ayarlar, dışa aktarılan özellik öneksiz olur, farklı önekli özel özellikler dışa aktarılmaz, varsayılan değer 'rvm:'. Örneğin bir özellik rvm:Refno=345 ise, dışa aktarılan özellik Refno = 345 olur, önek kaldırılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.String | Yeni değer **Örnek:** Aşağıdaki kod, RVM'de özelliğin nasıl dışa aktarılacağını gösterir. |

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


Yazar bilgisi, varsayılan değer '3d@aspose'

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.String | Yeni değer **Örnek:** Aşağıdaki kod, RVM'de özelliğin nasıl dışa aktarılacağını gösterir. |

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


Bu dosyayı dışa aktaran zaman damgası, varsayılan değer geçerli zaman

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


Metin tabanlı dosyalar için varsayılan kodlamayı ayarlar. Varsayılan değer null'dır, bu da içe aktarıcının/dışa aktarıcının hangi kodlamayı kullanacağına karar vereceği anlamına gelir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.nio.charset.Charset | Yeni değer |

### setExportAttributes(boolean value) {#setExportAttributes-boolean-}
```
public void setExportAttributes(boolean value)
```


Özellik listesini harici bir .att dosyasına dışa aktarılıp aktarılmayacağını ayarlar, varsayılan değer false.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | Yeni değer **Örnek:** Aşağıdaki kod, RVM'de özelliğin nasıl dışa aktarılacağını gösterir. |

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


Sahnede kullanılan dokuları çıktı dizinine kopyalamayı dener.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public void setFileName(String value)
```


Dışa aktarma/içe aktarma sahnesinin dosya adı. Bu isteğe bağlıdır, ancak OBJ'nin materyali gibi harici varlıkları serileştirirken faydalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

### setFileNote(String value) {#setFileNote-java.lang.String-}
```
public void setFileNote(String value)
```


Dosya başlığındaki dosya notu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.String | Yeni değer **Örnek:** Aşağıdaki kod, RVM'de özelliğin nasıl dışa aktarılacağını gösterir. |

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


Kullanıcının yükleme/kaydetme sırasında harici bağımlılıkları nasıl yöneteceğini ele almasına izin verir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [FileSystem](../../com.aspose.threed/filesystem) | Yeni değer **Örnek:** Varsayılan FileSystem LocalFileSystem'dir, sunucu tarafı gibi ortamlarda güvenli değildir, ancak farklı bir uygulama belirterek dosya sistemi erişimini geçersiz kılabilirsiniz. Aspose.3D farklı FileSystem uygulamaları sağlar, örneğin: |

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

Ve ayrıca kendi uygulamanızı da kullanabilirsiniz.

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


FileSystem için fabrika sınıfını ayarlar. Varsayılan fabrika, sunucu ortamı için uygun olmayan com.aspose.threed.LocalFileSystem'i oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [FileSystemFactory](../../com.aspose.threed/filesystemfactory) | Yeni değer **Örnek:** SaveOptions/LoadOptions içindeki varsayılan FileSystem dizin tabanlı bir dosya sistemidir, IOConfig.FileSystemFactory aracılığıyla belirterek varsayılan uygulamayı geçersiz kılabilirsiniz: |

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


OBJ gibi bazı dosyalar harici dosyalara bağımlıdır, arama yolları Aspose.3D'nin yüklemek için harici dosyayı bulmasına izin verir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.util.ArrayList<java.lang.String> | Yeni değer **Örnek:** Aşağıdaki kod, arama dokularını manuel olarak nasıl belirteceğinizi gösterir, böylece içe aktarıcı bulabilir |

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

