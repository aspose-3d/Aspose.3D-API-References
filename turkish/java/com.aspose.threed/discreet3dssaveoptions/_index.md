---
title: "Discreet3dsSaveOptions"
second_title: "Aspose.3D for Java API Referansı"
description: "3DS dosyası için kaydetme seçenekleri."
type: docs
weight: 44
url: /tr/java/com.aspose.threed/discreet3dssaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class Discreet3dsSaveOptions extends SaveOptions
```

3DS dosyası için kaydetme seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Discreet3dsSaveOptions()](#Discreet3dsSaveOptions--) | [Discreet3dsSaveOptions](../../com.aspose.threed/discreet3dssaveoptions) sınıfının yapıcısı |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDuplicatedNameCounterBase()](#getDuplicatedNameCounterBase--) | Yinelenen adlar için yeni ad oluşturmakta kullanılan sayaç, varsayılan değer 2'dir. |
| [getDuplicatedNameCounterFormat()](#getDuplicatedNameCounterFormat--) | Yinelenen sayacın biçimi, varsayılan değer boş dizedir. |
| [getDuplicatedNameSeparator()](#getDuplicatedNameSeparator--) | Nesnenin adı ile yinelenen sayaç arasındaki ayırıcı, varsayılan değer "\\_". |
| [getEncoding()](#getEncoding--) | Metin tabanlı dosyalar için varsayılan kodlamayı alır. |
| [getExportCamera()](#getExportCamera--) | Sahnede tüm kameraların dışa aktarılıp aktarılmayacağını alır. |
| [getExportLight()](#getExportLight--) | Sahnede tüm ışıkların dışa aktarılıp aktarılmayacağını alır. |
| [getExportTextures()](#getExportTextures--) | Sahnede kullanılan dokuları çıktı dizinine kopyalamayı dener. |
| [getFileFormat()](#getFileFormat--) | Mevcut Kaydet/Yükle seçeneğinde belirtilen dosya biçimini alır. |
| [getFileName()](#getFileName--) | Dışa aktarma/içeri aktarma sahnesinin dosya adı. |
| [getFileSystem()](#getFileSystem--) | Kullanıcının yükleme/kaydetme sırasında harici bağımlılıkları nasıl yöneteceğini ele almasına izin verir. |
| [getFileSystemFactory()](#getFileSystemFactory--) | FileSystem için fabrika sınıfını alır. |
| [getFlipCoordinateSystem()](#getFlipCoordinateSystem--) | İçeri/dışarı aktarım sırasında kontrol noktalarının/normalin ters koordinat sistemini alır. |
| [getGammaCorrectedColor()](#getGammaCorrectedColor--) | Bir 3ds dosyası aynı öznitelik için orijinal renk ve gama düzeltilmiş renk içerebilir, bunu true olarak ayarlamak mümkün olduğunda gama düzeltilmiş rengi kullanır, aksi takdirde Aspose.3D orijinal rengi kullanmaya çalışır. |
| [getHighPreciseColor()](#getHighPreciseColor--) | Bu true ise, oluşturulan 3ds dosyası yüksek hassasiyetli renk kullanır, yani kırmızı/yeşil/mavi kanallarının her biri 32 bit float olarak olur. |
| [getLookupPaths()](#getLookupPaths--) | OBJ gibi bazı dosyalar harici dosyalara bağımlıdır, arama yolları Aspose.3D'nin yüklemek için harici dosyayı bulmasına izin verir. |
| [getMasterScale()](#getMasterScale--) | Dışa aktarımda kullanılan ana ölçeği alır. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDuplicatedNameCounterBase(int value)](#setDuplicatedNameCounterBase-int-) | Yinelenen adlar için yeni ad oluşturmakta kullanılan sayaç, varsayılan değer 2'dir. |
| [setDuplicatedNameCounterFormat(String value)](#setDuplicatedNameCounterFormat-java.lang.String-) | Yinelenen sayacın biçimi, varsayılan değer boş dizedir. |
| [setDuplicatedNameSeparator(String value)](#setDuplicatedNameSeparator-java.lang.String-) | Nesnenin adı ile yinelenen sayaç arasındaki ayırıcı, varsayılan değer "\\_". |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Metin tabanlı dosyalar için varsayılan kodlamayı ayarlar. |
| [setExportCamera(boolean value)](#setExportCamera-boolean-) | Sahnedeki tüm kameraların dışa aktarılıp aktarılmayacağını ayarlar. |
| [setExportLight(boolean value)](#setExportLight-boolean-) | Sahnedeki tüm ışıkların dışa aktarılıp aktarılmayacağını ayarlar. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | Sahnede kullanılan dokuları çıktı dizinine kopyalamayı dener. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Dışa aktarma/içeri aktarma sahnesinin dosya adı. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Kullanıcının yükleme/kaydetme sırasında harici bağımlılıkları nasıl yöneteceğini ele almasına izin verir. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | FileSystem için fabrika sınıfını ayarlar. |
| [setFlipCoordinateSystem(boolean value)](#setFlipCoordinateSystem-boolean-) | İçeri/dışarı aktarım sırasında kontrol noktalarının/normalin ters koordinat sistemini ayarlar. |
| [setGammaCorrectedColor(boolean value)](#setGammaCorrectedColor-boolean-) | Bir 3ds dosyası aynı öznitelik için orijinal renk ve gama düzeltilmiş renk içerebilir, bunu true olarak ayarlamak mümkün olduğunda gama düzeltilmiş rengi kullanır, aksi takdirde Aspose.3D orijinal rengi kullanmaya çalışır. |
| [setHighPreciseColor(boolean value)](#setHighPreciseColor-boolean-) | Bu true ise, oluşturulan 3ds dosyası yüksek hassasiyetli renk kullanır, yani kırmızı/yeşil/mavi kanallarının her biri 32 bit float olarak olur. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | OBJ gibi bazı dosyalar harici dosyalara bağımlıdır, arama yolları Aspose.3D'nin yüklemek için harici dosyayı bulmasına izin verir. |
| [setMasterScale(double value)](#setMasterScale-double-) | Dışa aktarmada kullanılan ana ölçeği ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Discreet3dsSaveOptions() {#Discreet3dsSaveOptions--}
```
public Discreet3dsSaveOptions()
```


[Discreet3dsSaveOptions](../../com.aspose.threed/discreet3dssaveoptions) sınıfının yapıcısı

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


Yinelenen adlar için yeni ad oluşturmakta kullanılan sayaç, varsayılan değer 2'dir.

**Returns:**
int - Yinelenen adlar için yeni ad oluştururken kullanılan sayaç, varsayılan değer 2'dir.
### getDuplicatedNameCounterFormat() {#getDuplicatedNameCounterFormat--}
```
public String getDuplicatedNameCounterFormat()
```


Yinelenen sayacın biçimi, varsayılan değer boş dizedir.

**Returns:**
java.lang.String - Yinelenen sayacın biçimi, varsayılan değer boş dizedir.
### getDuplicatedNameSeparator() {#getDuplicatedNameSeparator--}
```
public String getDuplicatedNameSeparator()
```


Nesnenin adı ile yinelenen sayac arasındaki ayırıcı, varsayılan değer "\_". Sahne aynı adı kullanan nesneler içerdiğinde, Aspose.3D 3DS dışa aktarıcı nesne için farklı bir ad oluşturur. Örneğin iki "Box" adlı düğüm varsa, ilk düğümün adı "Box" olur ve ikinci düğüm varsayılan yapılandırmayı kullanarak "Box\_2" adını alır.

**Returns:**
java.lang.String - Nesnenin adı ile yinelenen sayac arasındaki ayırıcı, varsayılan değer "\_". Sahne aynı adı kullanan nesneler içerdiğinde, Aspose.3D 3DS dışa aktarıcı nesne için farklı bir ad oluşturur. Örneğin iki "Box" adlı düğüm varsa, ilk düğümün adı "Box" olur ve ikinci düğüm varsayılan yapılandırmayı kullanarak "Box\_2" adını alır.
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


Metin tabanlı dosyalar için varsayılan kodlamayı alır. Varsayılan değer null'dır, bu da içe aktarıcı/dışa aktarıcının hangi kodlamayı kullanacağına karar vereceği anlamına gelir.

**Returns:**
java.nio.charset.Charset - metin tabanlı dosyalar için varsayılan kodlama. Varsayılan değer null'dır, bu da içe aktarıcı/dışa aktarıcının hangi kodlamayı kullanacağına karar vereceği anlamına gelir.
### getExportCamera() {#getExportCamera--}
```
public boolean getExportCamera()
```


Sahnede tüm kameraların dışa aktarılıp aktarılmayacağını alır.

**Returns:**
boolean - sahnedeki tüm kameraların dışa aktarılıp aktarılmayacağı.
### getExportLight() {#getExportLight--}
```
public boolean getExportLight()
```


Sahnede tüm ışıkların dışa aktarılıp aktarılmayacağını alır.

**Returns:**
boolean - sahnedeki tüm ışıkların dışa aktarılıp aktarılmayacağı.
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
### getFlipCoordinateSystem() {#getFlipCoordinateSystem--}
```
public boolean getFlipCoordinateSystem()
```


İçeri/dışarı aktarım sırasında kontrol noktalarının/normalin ters koordinat sistemini alır.

**Returns:**
boolean - içe/dışa aktarım sırasında kontrol noktalarının/normalin koordinat sistemini tersine çevir.
### getGammaCorrectedColor() {#getGammaCorrectedColor--}
```
public boolean getGammaCorrectedColor()
```


Bir 3ds dosyası aynı öznitelik için orijinal renk ve gama düzeltilmiş renk içerebilir, bunu true olarak ayarlamak mümkün olduğunda gama düzeltilmiş rengi kullanır, aksi takdirde Aspose.3D orijinal rengi kullanmaya çalışır.

**Returns:**
boolean - Bir 3ds dosyası aynı öznitelik için orijinal renk ve gama düzeltilmiş renk içerebilir, bunu true olarak ayarlamak mümkünse gama düzeltilmiş rengi kullanır, aksi takdirde Aspose.3D orijinal rengi kullanmaya çalışır.
### getHighPreciseColor() {#getHighPreciseColor--}
```
public boolean getHighPreciseColor()
```


Eğer bu true ise, oluşturulan 3ds dosyası yüksek hassasiyetli renk kullanır, yani kırmızı/yeşil/mavi kanallar 32 bit float olur. Aksi takdirde oluşturulan dosya 24 bit renk kullanır, her kanal 8 bit bayttır. Varsayılan değer false'tur, çünkü tüm uygulamalar yüksek hassasiyetli rengi desteklemez.

**Returns:**
boolean - Eğer bu true ise, oluşturulan 3ds dosyası yüksek hassasiyetli renk kullanır, yani kırmızı/yeşil/mavi kanallar 32 bit float olur. Aksi takdirde oluşturulan dosya 24 bit renk kullanır, her kanal 8 bit bayttır. Varsayılan değer false'tur, çünkü tüm uygulamalar yüksek hassasiyetli rengi desteklemez.
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
### getMasterScale() {#getMasterScale--}
```
public double getMasterScale()
```


Dışa aktarımda kullanılan ana ölçeği alır.

**Returns:**
double - dışa aktarmada kullanılan ana ölçek.
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


Yinelenen adlar için yeni ad oluşturmakta kullanılan sayaç, varsayılan değer 2'dir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Yeni değer |

### setDuplicatedNameCounterFormat(String value) {#setDuplicatedNameCounterFormat-java.lang.String-}
```
public void setDuplicatedNameCounterFormat(String value)
```


Yinelenen sayacın biçimi, varsayılan değer boş dizedir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

### setDuplicatedNameSeparator(String value) {#setDuplicatedNameSeparator-java.lang.String-}
```
public void setDuplicatedNameSeparator(String value)
```


Nesnenin adı ile yinelenen sayac arasındaki ayırıcı, varsayılan değer "\_". Sahne aynı adı kullanan nesneler içerdiğinde, Aspose.3D 3DS dışa aktarıcı nesne için farklı bir ad oluşturur. Örneğin iki "Box" adlı düğüm varsa, ilk düğümün adı "Box" olur ve ikinci düğüm varsayılan yapılandırmayı kullanarak "Box\_2" adını alır.

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

### setExportCamera(boolean value) {#setExportCamera-boolean-}
```
public void setExportCamera(boolean value)
```


Sahnedeki tüm kameraların dışa aktarılıp aktarılmayacağını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setExportLight(boolean value) {#setExportLight-boolean-}
```
public void setExportLight(boolean value)
```


Sahnedeki tüm ışıkların dışa aktarılıp aktarılmayacağını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

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

### setFlipCoordinateSystem(boolean value) {#setFlipCoordinateSystem-boolean-}
```
public void setFlipCoordinateSystem(boolean value)
```


İçeri/dışarı aktarım sırasında kontrol noktalarının/normalin ters koordinat sistemini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setGammaCorrectedColor(boolean value) {#setGammaCorrectedColor-boolean-}
```
public void setGammaCorrectedColor(boolean value)
```


Bir 3ds dosyası aynı öznitelik için orijinal renk ve gama düzeltilmiş renk içerebilir, bunu true olarak ayarlamak mümkün olduğunda gama düzeltilmiş rengi kullanır, aksi takdirde Aspose.3D orijinal rengi kullanmaya çalışır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setHighPreciseColor(boolean value) {#setHighPreciseColor-boolean-}
```
public void setHighPreciseColor(boolean value)
```


Eğer bu true ise, oluşturulan 3ds dosyası yüksek hassasiyetli renk kullanır, yani kırmızı/yeşil/mavi kanallar 32 bit float olur. Aksi takdirde oluşturulan dosya 24 bit renk kullanır, her kanal 8 bit bayttır. Varsayılan değer false'tur, çünkü tüm uygulamalar yüksek hassasiyetli rengi desteklemez.

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

### setMasterScale(double value) {#setMasterScale-double-}
```
public void setMasterScale(double value)
```


Dışa aktarmada kullanılan ana ölçeği ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

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

