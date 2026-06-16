---
title: "RvmLoadOptions"
second_title: "Aspose.3D for Java API Referansı"
description: "AVEVA Plant Design Management Systems RVM dosyası için yükleme seçenekleri."
type: docs
weight: 157
url: /tr/java/com.aspose.threed/rvmloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.LoadOptions](../../com.aspose.threed/loadoptions)
```
public class RvmLoadOptions extends LoadOptions
```

AVEVA Plant Design Management System'in RVM dosyası için yükleme seçenekleri. **Örnek:** Aşağıdaki kod, RvmLoadOptions kullanarak RVM dosyasından içe aktarılan ilkel geometriler için teselleştirme parametrelerini nasıl özelleştireceğini gösterir.

```
RvmLoadOptions opt = new RvmLoadOptions();
             opt.setRectangularTorusSegments(30);
             opt.setCylinderRadialSegments(20);
             opt.setDishLatitudeSegments(20);
             opt.setDishLongitudeSegments(20);
             opt.setCenterScene(true);
             var scene = Scene.fromFile("input.rvm", opt);
             scene.save("output.obj");
```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [RvmLoadOptions(FileContentType contentType)](#RvmLoadOptions-com.aspose.threed.FileContentType-) | Bir [RvmLoadOptions](../../com.aspose.threed/rvmloadoptions) örneği oluşturun |
| [RvmLoadOptions()](#RvmLoadOptions--) | Bir [RvmLoadOptions](../../com.aspose.threed/rvmloadoptions) örneği oluşturun |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttributePrefix()](#getAttributePrefix--) | Harici öznitelik dosyalarında tanımlanan özniteliklerin önekini alır, Önek isim çakışmalarını önlemek için kullanılır, varsayılan değer "rvm:" |
| [getCenterScene()](#getCenterScene--) | Yüklemeden sonra sahneyi ortala. |
| [getClass()](#getClass--) |  |
| [getCylinderRadialSegments()](#getCylinderRadialSegments--) | Silindirin radyal segment sayısını alır, varsayılan değer 16 |
| [getDishLatitudeSegments()](#getDishLatitudeSegments--) | Dish'in enlem segment sayısını alır, varsayılan değer 8 |
| [getDishLongitudeSegments()](#getDishLongitudeSegments--) | Dish'in boylam segment sayısını alır, varsayılan değer 12 |
| [getEncoding()](#getEncoding--) | Metin tabanlı dosyalar için varsayılan kodlamayı alır. |
| [getFileFormat()](#getFileFormat--) | Mevcut Kaydet/Yükle seçeneğinde belirtilen dosya biçimini alır. |
| [getFileName()](#getFileName--) | Dışa aktarma/içeri aktarma sahnesinin dosya adı. |
| [getFileSystem()](#getFileSystem--) | Kullanıcının yükleme/kaydetme sırasında harici bağımlılıkları nasıl yöneteceğini ele almasına izin verir. |
| [getFileSystemFactory()](#getFileSystemFactory--) | FileSystem için fabrika sınıfını alır. |
| [getGenerateMaterials()](#getGenerateMaterials--) | RVM dosyası içinde renk tablosu dışa aktarılmamışsa sahnedeki her nesne için rastgele renklerle malzemeler oluştur. |
| [getLookupAttributes()](#getLookupAttributes--) | Harici öznitelik listesi dosyasından(.att/.attrib/.txt) özniteliklerin yüklenip yüklenmeyeceğini alır, varsayılan değer true. |
| [getLookupPaths()](#getLookupPaths--) | OBJ gibi bazı dosyalar harici dosyalara bağımlıdır, arama yolları Aspose.3D'nin yüklemek için harici dosyayı bulmasına izin verir. |
| [getRectangularTorusSegments()](#getRectangularTorusSegments--) | Dikdörtgen torusun radyal segment sayısını alır, varsayılan değer 20 |
| [getTorusTubularSegments()](#getTorusTubularSegments--) | Torusun tübik segment sayısını alır, varsayılan değer 20 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAttributePrefix(String value)](#setAttributePrefix-java.lang.String-) | Harici öznitelik dosyalarında tanımlanan özniteliklerin önekini ayarlar, Önek isim çakışmalarını önlemek için kullanılır, varsayılan değer "rvm:" |
| [setCenterScene(boolean value)](#setCenterScene-boolean-) | Yüklemeden sonra sahneyi ortala. |
| [setCylinderRadialSegments(int value)](#setCylinderRadialSegments-int-) | Silindirin radyal segment sayısını ayarlar, varsayılan değer 16 |
| [setDishLatitudeSegments(int value)](#setDishLatitudeSegments-int-) | Dish'in enlem segment sayısını ayarlar, varsayılan değer 8 |
| [setDishLongitudeSegments(int value)](#setDishLongitudeSegments-int-) | Dish'in boylam segment sayısını ayarlar, varsayılan değer 12 |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Metin tabanlı dosyalar için varsayılan kodlamayı ayarlar. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Dışa aktarma/içeri aktarma sahnesinin dosya adı. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Kullanıcının yükleme/kaydetme sırasında harici bağımlılıkları nasıl yöneteceğini ele almasına izin verir. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | FileSystem için fabrika sınıfını ayarlar. |
| [setGenerateMaterials(boolean value)](#setGenerateMaterials-boolean-) | RVM dosyası içinde renk tablosu dışa aktarılmamışsa sahnedeki her nesne için rastgele renklerle malzemeler oluştur. |
| [setLookupAttributes(boolean value)](#setLookupAttributes-boolean-) | Harici öznitelik listesi dosyasından(.att/.attrib/.txt) özniteliklerin yüklenip yüklenmeyeceğini ayarlar, varsayılan değer true. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | OBJ gibi bazı dosyalar harici dosyalara bağımlıdır, arama yolları Aspose.3D'nin yüklemek için harici dosyayı bulmasına izin verir. |
| [setRectangularTorusSegments(int value)](#setRectangularTorusSegments-int-) | Dikdörtgen torusun radyal segment sayısını ayarlar, varsayılan değer 20 |
| [setTorusTubularSegments(int value)](#setTorusTubularSegments-int-) | Torusun tübik segment sayısını ayarlar, varsayılan değer 20 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RvmLoadOptions(FileContentType contentType) {#RvmLoadOptions-com.aspose.threed.FileContentType-}
```
public RvmLoadOptions(FileContentType contentType)
```


Bir [RvmLoadOptions](../../com.aspose.threed/rvmloadoptions) örneği oluşturun

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) |  |

### RvmLoadOptions() {#RvmLoadOptions--}
```
public RvmLoadOptions()
```


Bir [RvmLoadOptions](../../com.aspose.threed/rvmloadoptions) örneği oluşturun

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
### getAttributePrefix() {#getAttributePrefix--}
```
public String getAttributePrefix()
```


Harici öznitelik dosyalarında tanımlanan özniteliklerin önekini alır, Önek isim çakışmalarını önlemek için kullanılır, varsayılan değer "rvm:"

**Returns:**
java.lang.String - dış attribute dosyalarında tanımlanan özniteliklerin önekidir, Önek isim çakışmalarını önlemek için kullanılır, varsayılan değer "rvm:"
### getCenterScene() {#getCenterScene--}
```
public boolean getCenterScene()
```


Yüklemeden sonra sahneyi ortala.

**Returns:**
boolean - Sahne yüklendikten sonra ortala.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCylinderRadialSegments() {#getCylinderRadialSegments--}
```
public int getCylinderRadialSegments()
```


Silindirin radyal segment sayısını alır, varsayılan değer 16

**Returns:**
int - silindirin radyal bölümlerinin sayısı, varsayılan değer 16
### getDishLatitudeSegments() {#getDishLatitudeSegments--}
```
public int getDishLatitudeSegments()
```


Dish'in enlem segment sayısını alır, varsayılan değer 8

**Returns:**
int - çanak'ın enlem bölümlerinin sayısı, varsayılan değer 8
### getDishLongitudeSegments() {#getDishLongitudeSegments--}
```
public int getDishLongitudeSegments()
```


Dish'in boylam segment sayısını alır, varsayılan değer 12

**Returns:**
int - çanak'ın boylam bölümlerinin sayısı, varsayılan değer 12
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


Metin tabanlı dosyalar için varsayılan kodlamayı alır. Varsayılan değer null'dır, bu da içe aktarıcı/dışa aktarıcının hangi kodlamayı kullanacağına karar vereceği anlamına gelir.

**Returns:**
java.nio.charset.Charset - metin tabanlı dosyalar için varsayılan kodlama. Varsayılan değer null'dır, bu da içe aktarıcı/dışa aktarıcının hangi kodlamayı kullanacağına karar vereceği anlamına gelir.
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
### getGenerateMaterials() {#getGenerateMaterials--}
```
public boolean getGenerateMaterials()
```


RVM dosyası içinde renk tablosu dışa aktarılmadıysa sahnedeki her nesne için rastgele renklerle materyaller oluştur. Varsayılan değer true

**Returns:**
boolean - RVM dosyası içinde renk tablosu dışa aktarılmadıysa sahnedeki her nesne için rastgele renklerle materyaller oluştur. Varsayılan değer true
### getLookupAttributes() {#getLookupAttributes--}
```
public boolean getLookupAttributes()
```


Harici öznitelik listesi dosyasından(.att/.attrib/.txt) özniteliklerin yüklenip yüklenmeyeceğini alır, varsayılan değer true.

**Returns:**
boolean - dış attribute liste dosyasından (.att/.attrib/.txt) öznitelikleri yükleyip yüklemeyeceği, varsayılan değer true.
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
### getRectangularTorusSegments() {#getRectangularTorusSegments--}
```
public int getRectangularTorusSegments()
```


Dikdörtgen torusun radyal segment sayısını alır, varsayılan değer 20

**Returns:**
int - dikdörtgen torusun radyal bölümlerinin sayısı, varsayılan değer 20
### getTorusTubularSegments() {#getTorusTubularSegments--}
```
public int getTorusTubularSegments()
```


Torusun tübik segment sayısını alır, varsayılan değer 20

**Returns:**
int - torusun tübik bölümlerinin sayısı, varsayılan değer 20
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




### setAttributePrefix(String value) {#setAttributePrefix-java.lang.String-}
```
public void setAttributePrefix(String value)
```


Harici öznitelik dosyalarında tanımlanan özniteliklerin önekini ayarlar, Önek isim çakışmalarını önlemek için kullanılır, varsayılan değer "rvm:"

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

### setCenterScene(boolean value) {#setCenterScene-boolean-}
```
public void setCenterScene(boolean value)
```


Yüklemeden sonra sahneyi ortala.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setCylinderRadialSegments(int value) {#setCylinderRadialSegments-int-}
```
public void setCylinderRadialSegments(int value)
```


Silindirin radyal segment sayısını ayarlar, varsayılan değer 16

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Yeni değer |

### setDishLatitudeSegments(int value) {#setDishLatitudeSegments-int-}
```
public void setDishLatitudeSegments(int value)
```


Dish'in enlem segment sayısını ayarlar, varsayılan değer 8

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Yeni değer |

### setDishLongitudeSegments(int value) {#setDishLongitudeSegments-int-}
```
public void setDishLongitudeSegments(int value)
```


Dish'in boylam segment sayısını ayarlar, varsayılan değer 12

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Yeni değer |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


Metin tabanlı dosyalar için varsayılan kodlamayı ayarlar. Varsayılan değer null'dır, bu da içe aktarıcının/dışa aktarıcının hangi kodlamayı kullanacağına karar vereceği anlamına gelir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.nio.charset.Charset | Yeni değer |

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

### setGenerateMaterials(boolean value) {#setGenerateMaterials-boolean-}
```
public void setGenerateMaterials(boolean value)
```


RVM dosyası içinde renk tablosu dışa aktarılmadıysa sahnedeki her nesne için rastgele renklerle materyaller oluştur. Varsayılan değer true

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setLookupAttributes(boolean value) {#setLookupAttributes-boolean-}
```
public void setLookupAttributes(boolean value)
```


Harici öznitelik listesi dosyasından(.att/.attrib/.txt) özniteliklerin yüklenip yüklenmeyeceğini ayarlar, varsayılan değer true.

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

### setRectangularTorusSegments(int value) {#setRectangularTorusSegments-int-}
```
public void setRectangularTorusSegments(int value)
```


Dikdörtgen torusun radyal segment sayısını ayarlar, varsayılan değer 20

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Yeni değer |

### setTorusTubularSegments(int value) {#setTorusTubularSegments-int-}
```
public void setTorusTubularSegments(int value)
```


Torusun tübik segment sayısını ayarlar, varsayılan değer 20

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Yeni değer |

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

