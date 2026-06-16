---
title: "GltfSaveOptions"
second_title: "Aspose.3D for Java API Referansı"
description: "glTF formatı için kaydetme seçenekleri."
type: docs
weight: 74
url: /tr/java/com.aspose.threed/gltfsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class GltfSaveOptions extends SaveOptions
```

glTF formatı için kaydetme seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [GltfSaveOptions(FileContentType contentType)](#GltfSaveOptions-com.aspose.threed.FileContentType-) | Yapıcı [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions) |
| [GltfSaveOptions(FileFormat format)](#GltfSaveOptions-com.aspose.threed.FileFormat-) | Yapıcı [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions) |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getApplyUnitScale()](#getApplyUnitScale--) | Mesh'e [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) uygula. |
| [getBufferFile()](#getBufferFile--) | İkili verileri depolamak için kullanılan dış tampon dosyasının dosya adı. |
| [getClass()](#getClass--) |  |
| [getDracoCompression()](#getDracoCompression--) | Draco sıkıştırmasının etkinleştirilip etkinleştirilmeyeceğini alır |
| [getEmbedAssets()](#getEmbedAssets--) | Tüm dış varlıkları ASCII modunda tek bir dosyaya base64 olarak göm, varsayılan değer false. |
| [getEncoding()](#getEncoding--) | Metin tabanlı dosyalar için varsayılan kodlamayı alır. |
| [getExportTextures()](#getExportTextures--) | Sahnede kullanılan dokuları çıktı dizinine kopyalamayı dener. |
| [getExternalDracoEncoder()](#getExternalDracoEncoder--) | Draco sıkıştırma hızını artırmak için dış draco kodlayıcıyı kullan. |
| [getFallbackNormal()](#getFallbackNormal--) | GLTF2 dışa aktarıcı geçersiz bir normal tespit ettiğinde, doğrulamadan kaçınmak için bu, orijinal değerinin yerine kullanılacaktır. |
| [getFileFormat()](#getFileFormat--) | Mevcut Kaydet/Yükle seçeneğinde belirtilen dosya biçimini alır. |
| [getFileName()](#getFileName--) | Dışa aktarma/içeri aktarma sahnesinin dosya adı. |
| [getFileSystem()](#getFileSystem--) | Kullanıcının yükleme/kaydetme sırasında harici bağımlılıkları nasıl yöneteceğini ele almasına izin verir. |
| [getFileSystemFactory()](#getFileSystemFactory--) | FileSystem için fabrika sınıfını alır. |
| [getFlipTexCoordV()](#getFlipTexCoordV--) | Doku koordinatı v(t) bileşenini ters çevir, varsayılan değer true. |
| [getImageFormat()](#getImageFormat--) | Standart glTF yalnızca PNG/JPG'yi doku formatı olarak destekler, bu seçenek dış standart görüntülerin dışa aktarım sırasında Aspose.3D tarafından desteklenen formata nasıl dönüştürüleceğini yönlendirir. |
| [getLookupPaths()](#getLookupPaths--) | OBJ gibi bazı dosyalar harici dosyalara bağımlıdır, arama yolları Aspose.3D'nin yüklemek için harici dosyayı bulmasına izin verir. |
| [getMaterialConverter()](#getMaterialConverter--) | Geometrinin malzemesini PBR malzemesine dönüştürmek için özel dönüştürücü. Eğer atanmazsa, glTF 2.0 dışa aktarıcı standart malzemeyi otomatik olarak PBR malzemesine dönüştürecektir. |
| [getPrettyPrint()](#getPrettyPrint--) | GLTF dosyasının JSON içeriği insan okunması için girintilenmiştir, varsayılan değer false'tur. |
| [getSaveExtras()](#getSaveExtras--) | Sahne nesnesinin dinamik özelliklerini oluşturulan glTF dosyasındaki 'extra' alanlarına kaydedin. |
| [getUseCommonMaterials()](#getUseCommonMaterials--) | Malzemeleri KHR ortak malzeme uzantılarını kullanarak serileştir, varsayılan değer false. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setApplyUnitScale(boolean value)](#setApplyUnitScale-boolean-) | Mesh'e [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) uygula. |
| [setBufferFile(String value)](#setBufferFile-java.lang.String-) | İkili verileri depolamak için kullanılan dış tampon dosyasının dosya adı. |
| [setDracoCompression(boolean value)](#setDracoCompression-boolean-) | Draco sıkıştırmasının etkinleştirilip etkinleştirilmeyeceğini ayarlar. |
| [setEmbedAssets(boolean value)](#setEmbedAssets-boolean-) | Tüm dış varlıkları ASCII modunda tek bir dosyaya base64 olarak göm, varsayılan değer false. |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Metin tabanlı dosyalar için varsayılan kodlamayı ayarlar. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | Sahnede kullanılan dokuları çıktı dizinine kopyalamayı dener. |
| [setExternalDracoEncoder(String value)](#setExternalDracoEncoder-java.lang.String-) | Draco sıkıştırma hızını artırmak için dış draco kodlayıcıyı kullan. |
| [setFallbackNormal(Vector3 value)](#setFallbackNormal-com.aspose.threed.Vector3-) | GLTF2 dışa aktarıcı geçersiz bir normal tespit ettiğinde, doğrulamadan kaçınmak için bu, orijinal değerinin yerine kullanılacaktır. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Dışa aktarma/içeri aktarma sahnesinin dosya adı. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Kullanıcının yükleme/kaydetme sırasında harici bağımlılıkları nasıl yöneteceğini ele almasına izin verir. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | FileSystem için fabrika sınıfını ayarlar. |
| [setFlipTexCoordV(boolean value)](#setFlipTexCoordV-boolean-) | Doku koordinatı v(t) bileşenini ters çevir, varsayılan değer true. |
| [setImageFormat(GltfEmbeddedImageFormat value)](#setImageFormat-com.aspose.threed.GltfEmbeddedImageFormat-) | Standart glTF yalnızca PNG/JPG'yi doku formatı olarak destekler, bu seçenek dış standart görüntülerin dışa aktarım sırasında Aspose.3D tarafından desteklenen formata nasıl dönüştürüleceğini yönlendirir. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | OBJ gibi bazı dosyalar harici dosyalara bağımlıdır, arama yolları Aspose.3D'nin yüklemek için harici dosyayı bulmasına izin verir. |
| [setMaterialConverter(MaterialConverter value)](#setMaterialConverter-com.aspose.threed.MaterialConverter-) | Geometrinin malzemesini PBR malzemesine dönüştürmek için özel dönüştürücü. Eğer atanmazsa, glTF 2.0 dışa aktarıcı standart malzemeyi otomatik olarak PBR malzemesine dönüştürecektir. |
| [setPrettyPrint(boolean value)](#setPrettyPrint-boolean-) | GLTF dosyasının JSON içeriği insan okunması için girintilenmiştir, varsayılan değer false'tur. |
| [setSaveExtras(boolean value)](#setSaveExtras-boolean-) | Sahne nesnesinin dinamik özelliklerini oluşturulan glTF dosyasındaki 'extra' alanlarına kaydedin. |
| [setUseCommonMaterials(boolean value)](#setUseCommonMaterials-boolean-) | Malzemeleri KHR ortak malzeme uzantılarını kullanarak serileştir, varsayılan değer false. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GltfSaveOptions(FileContentType contentType) {#GltfSaveOptions-com.aspose.threed.FileContentType-}
```
public GltfSaveOptions(FileContentType contentType)
```


Yapıcı [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions)

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) |  |

### GltfSaveOptions(FileFormat format) {#GltfSaveOptions-com.aspose.threed.FileFormat-}
```
public GltfSaveOptions(FileFormat format)
```


Yapıcı [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions)

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| format | [FileFormat](../../com.aspose.threed/fileformat) |  |

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
### getApplyUnitScale() {#getApplyUnitScale--}
```
public boolean getApplyUnitScale()
```


Mesh'e [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) uygula. Varsayılan değer false'tur.

**Returns:**
boolean - Mesh'e [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) uygula. Varsayılan değer false'tur.
### getBufferFile() {#getBufferFile--}
```
public String getBufferFile()
```


İkili verileri depolamak için kullanılan dış tampon dosyasının dosya adı. Bu dosya belirtilmezse, Aspose.3D sizin için bir ad oluşturur. Bu, glTF ikili modda dışa aktarılırken yoksayılır.

**Returns:**
java.lang.String - İkili verileri depolamak için kullanılan dış tampon dosyasının dosya adı. Bu dosya belirtilmezse, Aspose.3D sizin için bir ad oluşturur. Bu, glTF ikili modda dışa aktarılırken yoksayılır.
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


Draco sıkıştırmasının etkinleştirilip etkinleştirilmeyeceğini alır

**Returns:**
boolean - draco sıkıştırmasının etkinleştirilip etkinleştirilmeyeceği
### getEmbedAssets() {#getEmbedAssets--}
```
public boolean getEmbedAssets()
```


Tüm dış varlıkları ASCII modunda tek bir dosyaya base64 olarak göm, varsayılan değer false.

**Returns:**
boolean - Tüm dış varlıkları ASCII modunda tek dosyaya base64 olarak göm, varsayılan değer false.
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
### getExternalDracoEncoder() {#getExternalDracoEncoder--}
```
public String getExternalDracoEncoder()
```


Draco sıkıştırma hızını artırmak için dış draco kodlayıcıyı kullan.

**Returns:**
java.lang.String - Draco sıkıştırma hızını artırmak için dış draco kodlayıcıyı kullan. **Remarks:** Aspose.3D, ağı draco formatına kodlamak için yeni bir alt süreç oluşturacak, bunu kendi sorumluluğunuzda kullanın.
### getFallbackNormal() {#getFallbackNormal--}
```
public Vector3 getFallbackNormal()
```


GLTF2 dışa aktarıcı geçersiz bir normal tespit ettiğinde, doğrulamadan geçmek için orijinal değeri yerine bu kullanılacaktır. Varsayılan değer (0, 1, 0)'dır.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - When GLTF2 exporter detected an invalid normal, this will be used instead of its original value to bypass the validation. Default value is (0, 1, 0)
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
### getFlipTexCoordV() {#getFlipTexCoordV--}
```
public boolean getFlipTexCoordV()
```


Doku koordinatı v(t) bileşenini ters çevir, varsayılan değer true.

**Returns:**
boolean - doku koordinatı v(t) bileşenini ters çevir, varsayılan değer true.
### getImageFormat() {#getImageFormat--}
```
public GltfEmbeddedImageFormat getImageFormat()
```


Standart glTF yalnızca PNG/JPG'yi doku formatı olarak destekler, bu seçenek dış standart görüntülerin dışa aktarım sırasında Aspose.3D tarafından desteklenen formata nasıl dönüştürüleceğini yönlendirir. Varsayılan değer [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG)

**Returns:**
[GltfEmbeddedImageFormat](../../com.aspose.threed/gltfembeddedimageformat) - Standard glTF only supports PNG/JPG as its texture format, this option will guide how Aspose.3D convert the non-standard images to supported format during the exporting. Default value is [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG)
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
### getMaterialConverter() {#getMaterialConverter--}
```
public MaterialConverter getMaterialConverter()
```


Geometrinin malzemesini PBR malzemesine dönüştürmek için özel dönüştürücü. Eğer atanmazsa, glTF 2.0 dışa aktarıcı standart malzemeyi otomatik olarak PBR malzemesine dönüştürecektir. Varsayılan değer null'dur. Bu özellik bir sahneyi glTF 2.0 dosyasına dışa aktarırken kullanılır.

**Returns:**
[MaterialConverter](../../com.aspose.threed/materialconverter) - Custom converter to convert the geometry's material to PBR material If this is unassigned, glTF 2.0 exporter will automatically convert the standard material to PBR material. Default value is null This property is used when exporting a scene to a glTF 2.0 file.
### getPrettyPrint() {#getPrettyPrint--}
```
public boolean getPrettyPrint()
```


GLTF dosyasının JSON içeriği insan okunması için girintilenmiştir, varsayılan değer false'tur.

**Returns:**
boolean - GLTF dosyasının JSON içeriği insan okunması için girintilenmiştir, varsayılan değer false.
### getSaveExtras() {#getSaveExtras--}
```
public boolean getSaveExtras()
```


Sahne nesnesinin dinamik özelliklerini oluşturulan glTF dosyasındaki 'extra' alanlarına kaydedin. Bu, uygulamaya özgü veri sağlamak için kullanışlıdır. Varsayılan değer false.

**Returns:**
boolean - Sahne nesnesinin dinamik özelliklerini oluşturulan glTF dosyasındaki 'extra' alanlarına kaydedin. Bu, uygulamaya özgü veri sağlamak için kullanışlıdır. Varsayılan değer false.
### getUseCommonMaterials() {#getUseCommonMaterials--}
```
public boolean getUseCommonMaterials()
```


Malzemeleri KHR ortak malzeme uzantılarını kullanarak serileştir, varsayılan değer false. Bunu false olarak ayarlamak, Aspose.3D'nin [getExportShaders](../../com.aspose.threed/gltfsaveoptions\#getExportShaders) varsa bir dizi vertex/fragment gölgesi dışa aktarmasına neden olur.

**Returns:**
boolean - Malzemeleri KHR ortak malzeme uzantılarını kullanarak serileştir, varsayılan değer false. Bunu false olarak ayarlamak, Aspose.3D'nin [getExportShaders](../../com.aspose.threed/gltfsaveoptions\#getExportShaders) varsa bir dizi vertex/fragment gölgesi dışa aktarmasına neden olur. **Remarks:** Bu özellik yalnızca glTF 1.0 için çalışır.
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


Mesh'e [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) uygula. Varsayılan değer false'tur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setBufferFile(String value) {#setBufferFile-java.lang.String-}
```
public void setBufferFile(String value)
```


İkili verileri depolamak için kullanılan dış tampon dosyasının dosya adı. Bu dosya belirtilmezse, Aspose.3D sizin için bir ad oluşturur. Bu, glTF ikili modda dışa aktarılırken yoksayılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

### setDracoCompression(boolean value) {#setDracoCompression-boolean-}
```
public void setDracoCompression(boolean value)
```


Draco sıkıştırmasının etkinleştirilip etkinleştirilmeyeceğini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setEmbedAssets(boolean value) {#setEmbedAssets-boolean-}
```
public void setEmbedAssets(boolean value)
```


Tüm dış varlıkları ASCII modunda tek bir dosyaya base64 olarak göm, varsayılan değer false.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

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

### setExternalDracoEncoder(String value) {#setExternalDracoEncoder-java.lang.String-}
```
public void setExternalDracoEncoder(String value)
```


Draco sıkıştırma hızını artırmak için dış draco kodlayıcıyı kullan.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer **Remarks:** Aspose.3D, ağı draco formatına kodlamak için yeni bir alt süreç oluşturacak, bunu kendi sorumluluğunuzda kullanın. |

### setFallbackNormal(Vector3 value) {#setFallbackNormal-com.aspose.threed.Vector3-}
```
public void setFallbackNormal(Vector3 value)
```


GLTF2 dışa aktarıcı geçersiz bir normal tespit ettiğinde, doğrulamadan geçmek için orijinal değeri yerine bu kullanılacaktır. Varsayılan değer (0, 1, 0)'dır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Yeni değer |

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

### setFlipTexCoordV(boolean value) {#setFlipTexCoordV-boolean-}
```
public void setFlipTexCoordV(boolean value)
```


Doku koordinatı v(t) bileşenini ters çevir, varsayılan değer true.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setImageFormat(GltfEmbeddedImageFormat value) {#setImageFormat-com.aspose.threed.GltfEmbeddedImageFormat-}
```
public void setImageFormat(GltfEmbeddedImageFormat value)
```


Standart glTF yalnızca PNG/JPG'yi doku formatı olarak destekler, bu seçenek dış standart görüntülerin dışa aktarım sırasında Aspose.3D tarafından desteklenen formata nasıl dönüştürüleceğini yönlendirir. Varsayılan değer [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG)

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [GltfEmbeddedImageFormat](../../com.aspose.threed/gltfembeddedimageformat) | Yeni değer |

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

### setMaterialConverter(MaterialConverter value) {#setMaterialConverter-com.aspose.threed.MaterialConverter-}
```
public void setMaterialConverter(MaterialConverter value)
```


Geometrinin malzemesini PBR malzemesine dönüştürmek için özel dönüştürücü. Eğer atanmazsa, glTF 2.0 dışa aktarıcı standart malzemeyi otomatik olarak PBR malzemesine dönüştürecektir. Varsayılan değer null'dur. Bu özellik bir sahneyi glTF 2.0 dosyasına dışa aktarırken kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [MaterialConverter](../../com.aspose.threed/materialconverter) | Yeni değer |

### setPrettyPrint(boolean value) {#setPrettyPrint-boolean-}
```
public void setPrettyPrint(boolean value)
```


GLTF dosyasının JSON içeriği insan okunması için girintilenmiştir, varsayılan değer false'tur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setSaveExtras(boolean value) {#setSaveExtras-boolean-}
```
public void setSaveExtras(boolean value)
```


Sahne nesnesinin dinamik özelliklerini oluşturulan glTF dosyasındaki 'extra' alanlarına kaydedin. Bu, uygulamaya özgü veri sağlamak için kullanışlıdır. Varsayılan değer false.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setUseCommonMaterials(boolean value) {#setUseCommonMaterials-boolean-}
```
public void setUseCommonMaterials(boolean value)
```


Malzemeleri KHR ortak malzeme uzantılarını kullanarak serileştir, varsayılan değer false. Bunu false olarak ayarlamak, Aspose.3D'nin [getExportShaders](../../com.aspose.threed/gltfsaveoptions\#getExportShaders) varsa bir dizi vertex/fragment gölgesi dışa aktarmasına neden olur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer **Remarks:** Bu özellik yalnızca glTF 1.0 için çalışır. |

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

