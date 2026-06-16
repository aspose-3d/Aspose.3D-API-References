---
title: "PlySaveOptions"
second_title: "Aspose.3D for Java API Referansı"
description: "Sahneyi PLY dosyası olarak dışa aktarmak için kaydetme seçenekleri."
type: docs
weight: 131
url: /tr/java/com.aspose.threed/plysaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class PlySaveOptions extends SaveOptions
```

Sahneyi PLY dosyası olarak dışa aktarmak için kaydetme seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PlySaveOptions()](#PlySaveOptions--) | [PlySaveOptions](../../com.aspose.threed/plysaveoptions) yapıcısı |
| [PlySaveOptions(FileContentType contentType)](#PlySaveOptions-com.aspose.threed.FileContentType-) | [PlySaveOptions](../../com.aspose.threed/plysaveoptions) yapıcısı |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAxisSystem()](#getAxisSystem--) | Dışa aktarılan stl dosyasındaki eksen sistemini alır. |
| [getClass()](#getClass--) |  |
| [getColorComponents()](#getColorComponents--) | Vertex rengi için bileşen adları, varsayılan değer ("red", "green", "blue") |
| [getEncoding()](#getEncoding--) | Metin tabanlı dosyalar için varsayılan kodlamayı alır. |
| [getExportTextures()](#getExportTextures--) | Sahnede kullanılan dokuları çıktı dizinine kopyalamayı dener. |
| [getFaceElement()](#getFaceElement--) | Yüz verileri için öğe adı, varsayılan değer "face" |
| [getFaceProperty()](#getFaceProperty--) | Yüz verileri için özellik adı, varsayılan değer "vertex\_index" |
| [getFileFormat()](#getFileFormat--) | Mevcut Kaydet/Yükle seçeneğinde belirtilen dosya biçimini alır. |
| [getFileName()](#getFileName--) | Dışa aktarma/içeri aktarma sahnesinin dosya adı. |
| [getFileSystem()](#getFileSystem--) | Kullanıcının yükleme/kaydetme sırasında harici bağımlılıkları nasıl yöneteceğini ele almasına izin verir. |
| [getFileSystemFactory()](#getFileSystemFactory--) | FileSystem için fabrika sınıfını alır. |
| [getFlipCoordinate()](#getFlipCoordinate--) | Sahneyi kaydederken koordinatı ters çevir, varsayılan değer true |
| [getLookupPaths()](#getLookupPaths--) | OBJ gibi bazı dosyalar harici dosyalara bağımlıdır, arama yolları Aspose.3D'nin yüklemek için harici dosyayı bulmasına izin verir. |
| [getNormalComponents()](#getNormalComponents--) | Normal verileri için bileşen adları, varsayılan değer ("nx", "ny", "nz") |
| [getPointCloud()](#getPointCloud--) | Sahneyi nokta bulutu olarak dışa aktar, varsayılan değer false. |
| [getPositionComponents()](#getPositionComponents--) | Pozisyon verileri için bileşen adları, varsayılan değer ("x", "y", "z") |
| [getTextureCoordinateComponents()](#getTextureCoordinateComponents--) | Doku koordinat verileri için bileşen adları, varsayılan değer ("u", "v") |
| [getVertexElement()](#getVertexElement--) | Vertex verileri için öğe adı, varsayılan değer "vertex" |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAxisSystem(AxisSystem value)](#setAxisSystem-com.aspose.threed.AxisSystem-) | Dışa aktarılan stl dosyasında eksen sistemini ayarlar. |
| [setColorComponents(Tuple_3<String,String,String> value)](#setColorComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--) | Vertex rengi için bileşen adları, varsayılan değer ("red", "green", "blue") |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Metin tabanlı dosyalar için varsayılan kodlamayı ayarlar. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | Sahnede kullanılan dokuları çıktı dizinine kopyalamayı dener. |
| [setFaceElement(String value)](#setFaceElement-java.lang.String-) | Yüz verileri için öğe adı, varsayılan değer "face" |
| [setFaceProperty(String value)](#setFaceProperty-java.lang.String-) | Yüz verileri için özellik adı, varsayılan değer "vertex\_index" |
| [setFileName(String value)](#setFileName-java.lang.String-) | Dışa aktarma/içeri aktarma sahnesinin dosya adı. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Kullanıcının yükleme/kaydetme sırasında harici bağımlılıkları nasıl yöneteceğini ele almasına izin verir. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | FileSystem için fabrika sınıfını ayarlar. |
| [setFlipCoordinate(boolean value)](#setFlipCoordinate-boolean-) | Sahneyi kaydederken koordinatı ters çevir, varsayılan değer true |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | OBJ gibi bazı dosyalar harici dosyalara bağımlıdır, arama yolları Aspose.3D'nin yüklemek için harici dosyayı bulmasına izin verir. |
| [setNormalComponents(Tuple_3<String,String,String> value)](#setNormalComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--) | Normal verileri için bileşen adları, varsayılan değer ("nx", "ny", "nz") |
| [setPointCloud(boolean value)](#setPointCloud-boolean-) | Sahneyi nokta bulutu olarak dışa aktar, varsayılan değer false. |
| [setPositionComponents(Tuple_3<String,String,String> value)](#setPositionComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--) | Pozisyon verileri için bileşen adları, varsayılan değer ("x", "y", "z") |
| [setTextureCoordinateComponents(Tuple_2<String,String> value)](#setTextureCoordinateComponents-com.aspose.threed.Tuple-2-java.lang.String-java.lang.String--) | Doku koordinat verileri için bileşen adları, varsayılan değer ("u", "v") |
| [setVertexElement(String value)](#setVertexElement-java.lang.String-) | Vertex verileri için öğe adı, varsayılan değer "vertex" |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PlySaveOptions() {#PlySaveOptions--}
```
public PlySaveOptions()
```


[PlySaveOptions](../../com.aspose.threed/plysaveoptions) yapıcısı

### PlySaveOptions(FileContentType contentType) {#PlySaveOptions-com.aspose.threed.FileContentType-}
```
public PlySaveOptions(FileContentType contentType)
```


[PlySaveOptions](../../com.aspose.threed/plysaveoptions) yapıcısı

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) |  |

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
### getAxisSystem() {#getAxisSystem--}
```
public AxisSystem getAxisSystem()
```


Dışa aktarılan stl dosyasındaki eksen sistemini alır.

**Returns:**
[AxisSystem](../../com.aspose.threed/axissystem) - the axis system in the exported stl file. **Remarks:** FlipCoordinateSystem must be enabled to utilize this feature.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorComponents() {#getColorComponents--}
```
public Tuple_3<String,String,String> getColorComponents()
```


Vertex rengi için bileşen adları, varsayılan değer ("red", "green", "blue")

**Returns:**
com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> - Vertex rengi için bileşen adları, varsayılan değer ("red", "green", "blue")
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


Metin tabanlı dosyalar için varsayılan kodlamayı alır. Varsayılan değer null'dır, bu da içe aktarıcı/dışa aktarıcının hangi kodlamayı kullanacağına karar vereceği anlamına gelir.

**Returns:**
java.nio.charset.Charset - metin tabanlı dosyalar için varsayılan kodlama. Varsayılan değer null'dır, bu da içe aktarıcı/dışa aktarıcının hangi kodlamayı kullanacağına karar vereceği anlamına gelir.
### getExportTextures() {#getExportTextures--}
```
public boolean getExportTextures()
```


Sahnede kullanılan dokuları çıktı dizinine kopyalamayı dener.

**Returns:**
boolean - sahnede kullanılan dokuları çıktı dizinine kopyalamayı dene.
### getFaceElement() {#getFaceElement--}
```
public String getFaceElement()
```


Yüz verileri için öğe adı, varsayılan değer "face"

**Returns:**
java.lang.String - Yüz verileri için öğe adı, varsayılan değer "face"
### getFaceProperty() {#getFaceProperty--}
```
public String getFaceProperty()
```


Yüz verileri için özellik adı, varsayılan değer "vertex\_index"

**Returns:**
java.lang.String - Yüz verileri için özellik adı, varsayılan değer "vertex\_index"
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
### getFlipCoordinate() {#getFlipCoordinate--}
```
public boolean getFlipCoordinate()
```


Sahneyi kaydederken koordinatı ters çevir, varsayılan değer true

**Returns:**
boolean - Sahneyi kaydederken koordinatı ters çevir, varsayılan değer true
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
### getNormalComponents() {#getNormalComponents--}
```
public Tuple_3<String,String,String> getNormalComponents()
```


Normal verileri için bileşen adları, varsayılan değer ("nx", "ny", "nz")

**Returns:**
com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> - Normal verileri için bileşen adları, varsayılan değer ("nx", "ny", "nz")
### getPointCloud() {#getPointCloud--}
```
public boolean getPointCloud()
```


Sahneyi nokta bulutu olarak dışa aktar, varsayılan değer false.

**Returns:**
boolean - Sahneyi nokta bulutu olarak dışa aktar, varsayılan değer false.
### getPositionComponents() {#getPositionComponents--}
```
public Tuple_3<String,String,String> getPositionComponents()
```


Pozisyon verileri için bileşen adları, varsayılan değer ("x", "y", "z")

**Returns:**
com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> - Pozisyon verileri için bileşen adları, varsayılan değer ("x", "y", "z")
### getTextureCoordinateComponents() {#getTextureCoordinateComponents--}
```
public Tuple_2<String,String> getTextureCoordinateComponents()
```


Doku koordinat verileri için bileşen adları, varsayılan değer ("u", "v")

**Returns:**
com.aspose.threed.Tuple_2<java.lang.String,java.lang.String> - Doku koordinat verileri için bileşen adları, varsayılan değer ("u", "v")
### getVertexElement() {#getVertexElement--}
```
public String getVertexElement()
```


Vertex verileri için öğe adı, varsayılan değer "vertex"

**Returns:**
java.lang.String - Vertex verileri için öğe adı, varsayılan değer "vertex"
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




### setAxisSystem(AxisSystem value) {#setAxisSystem-com.aspose.threed.AxisSystem-}
```
public void setAxisSystem(AxisSystem value)
```


Dışa aktarılan stl dosyasında eksen sistemini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [AxisSystem](../../com.aspose.threed/axissystem) | Yeni değer **Remarks:** FlipCoordinateSystem bu özelliği kullanmak için etkinleştirilmelidir. |

### setColorComponents(Tuple_3<String,String,String> value) {#setColorComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--}
```
public void setColorComponents(Tuple_3<String,String,String> value)
```


Vertex rengi için bileşen adları, varsayılan değer ("red", "green", "blue")

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> | Yeni değer |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


Metin tabanlı dosyalar için varsayılan kodlamayı ayarlar. Varsayılan değer null'dır, bu da içe aktarıcının/dışa aktarıcının hangi kodlamayı kullanacağına karar vereceği anlamına gelir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.nio.charset.Charset | Yeni değer |

### setExportTextures(boolean value) {#setExportTextures-boolean-}
```
public void setExportTextures(boolean value)
```


Sahnede kullanılan dokuları çıktı dizinine kopyalamayı dener.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setFaceElement(String value) {#setFaceElement-java.lang.String-}
```
public void setFaceElement(String value)
```


Yüz verileri için öğe adı, varsayılan değer "face"

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

### setFaceProperty(String value) {#setFaceProperty-java.lang.String-}
```
public void setFaceProperty(String value)
```


Yüz verileri için özellik adı, varsayılan değer "vertex\_index"

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public void setFileName(String value)
```


Dışa aktarma/içe aktarma sahnesinin dosya adı. Bu isteğe bağlıdır, ancak OBJ'nin materyali gibi harici varlıkları serileştirirken faydalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

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

### setFlipCoordinate(boolean value) {#setFlipCoordinate-boolean-}
```
public void setFlipCoordinate(boolean value)
```


Sahneyi kaydederken koordinatı ters çevir, varsayılan değer true

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

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

### setNormalComponents(Tuple_3<String,String,String> value) {#setNormalComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--}
```
public void setNormalComponents(Tuple_3<String,String,String> value)
```


Normal verileri için bileşen adları, varsayılan değer ("nx", "ny", "nz")

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> | Yeni değer |

### setPointCloud(boolean value) {#setPointCloud-boolean-}
```
public void setPointCloud(boolean value)
```


Sahneyi nokta bulutu olarak dışa aktar, varsayılan değer false.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setPositionComponents(Tuple_3<String,String,String> value) {#setPositionComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--}
```
public void setPositionComponents(Tuple_3<String,String,String> value)
```


Pozisyon verileri için bileşen adları, varsayılan değer ("x", "y", "z")

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> | Yeni değer |

### setTextureCoordinateComponents(Tuple_2<String,String> value) {#setTextureCoordinateComponents-com.aspose.threed.Tuple-2-java.lang.String-java.lang.String--}
```
public void setTextureCoordinateComponents(Tuple_2<String,String> value)
```


Doku koordinat verileri için bileşen adları, varsayılan değer ("u", "v")

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | com.aspose.threed.Tuple_2<java.lang.String,java.lang.String> | Yeni değer |

### setVertexElement(String value) {#setVertexElement-java.lang.String-}
```
public void setVertexElement(String value)
```


Vertex verileri için öğe adı, varsayılan değer "vertex"

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

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

