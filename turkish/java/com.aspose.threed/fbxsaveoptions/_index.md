---
title: "FbxSaveOptions"
second_title: "Aspose.3D for Java API Referansı"
description: "Fbx dosyası için kaydetme seçenekleri."
type: docs
weight: 63
url: /tr/java/com.aspose.threed/fbxsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class FbxSaveOptions extends SaveOptions
```

Fbx dosyası için kaydetme seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FbxSaveOptions(FileFormat format)](#FbxSaveOptions-com.aspose.threed.FileFormat-) | Bir [FbxSaveOptions](../../com.aspose.threed/fbxsaveoptions) başlatır |
| [FbxSaveOptions(FileContentType contentType)](#FbxSaveOptions-com.aspose.threed.FileContentType-) | En son desteklenen sürümü kullanarak bir [FbxSaveOptions](../../com.aspose.threed/fbxsaveoptions) başlatın. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEmbedTextures()](#getEmbedTextures--) | Doku dosyasının son çıktı dosyasına gömülüp gömülmeyeceğini alır. |
| [getEnableCompression()](#getEnableCompression--) | FBX dosyasındaki büyük ikili verileri sıkıştırma (örneğin |
| [getEncoding()](#getEncoding--) | Metin tabanlı dosyalar için varsayılan kodlamayı alır. |
| [getExportLegacyMaterialProperties()](#getExportLegacyMaterialProperties--) | Geri uyumluluk için kullanılan eski malzeme özelliklerinin dışa aktarılıp aktarılmayacağını alır. |
| [getExportTextures()](#getExportTextures--) | Sahnede kullanılan dokuları çıktı dizinine kopyalamayı dener. |
| [getFileFormat()](#getFileFormat--) | Mevcut Kaydet/Yükle seçeneğinde belirtilen dosya biçimini alır. |
| [getFileName()](#getFileName--) | Dışa aktarma/içeri aktarma sahnesinin dosya adı. |
| [getFileSystem()](#getFileSystem--) | Kullanıcının yükleme/kaydetme sırasında harici bağımlılıkları nasıl yöneteceğini ele almasına izin verir. |
| [getFileSystemFactory()](#getFileSystemFactory--) | FileSystem için fabrika sınıfını alır. |
| [getFoldRepeatedCurveData()](#getFoldRepeatedCurveData--) | Son verinin referans sayısını artırarak tekrarlanan eğri verisinin yeniden kullanılmasını alır. |
| [getGenerateVertexElementMaterial()](#getGenerateVertexElementMaterial--) | Ekli düğüm malzeme içeriyorsa, geometriler için her zaman bir [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) oluşturulup oluşturulmayacağını alır. |
| [getLookupPaths()](#getLookupPaths--) | OBJ gibi bazı dosyalar harici dosyalara bağımlıdır, arama yolları Aspose.3D'nin yüklemek için harici dosyayı bulmasına izin verir. |
| [getReusePrimitiveMesh()](#getReusePrimitiveMesh--) | Aynı parametrelere sahip primitifler için ağı yeniden kullanın, bu, CAD dosyalarından içe aktarılan büyük bir primitif şekil setiyle oluşturulan sahnenin FBX çıktısının boyutunu önemli ölçüde azaltacaktır. |
| [getVideoForTexture()](#getVideoForTexture--) | FBX olarak dışa aktarılırken bir [Texture](../../com.aspose.threed/texture) için Video örneği oluşturulup oluşturulmayacağını alır. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setEmbedTextures(boolean value)](#setEmbedTextures-boolean-) | Doku dosyasının son çıktı dosyasına gömülüp gömülmeyeceğini ayarlar. |
| [setEnableCompression(boolean value)](#setEnableCompression-boolean-) | FBX dosyasındaki büyük ikili verileri sıkıştırma (örneğin |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Metin tabanlı dosyalar için varsayılan kodlamayı ayarlar. |
| [setExportLegacyMaterialProperties(boolean value)](#setExportLegacyMaterialProperties-boolean-) | Geri uyumluluk için kullanılan eski malzeme özelliklerinin dışa aktarılıp aktarılmayacağını ayarlar. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | Sahnede kullanılan dokuları çıktı dizinine kopyalamayı dener. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Dışa aktarma/içeri aktarma sahnesinin dosya adı. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Kullanıcının yükleme/kaydetme sırasında harici bağımlılıkları nasıl yöneteceğini ele almasına izin verir. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | FileSystem için fabrika sınıfını ayarlar. |
| [setFoldRepeatedCurveData(Boolean value)](#setFoldRepeatedCurveData-java.lang.Boolean-) | Son verinin referans sayısını artırarak tekrarlanan eğri verisinin yeniden kullanılmasını ayarlar. |
| [setGenerateVertexElementMaterial(boolean value)](#setGenerateVertexElementMaterial-boolean-) | Ekli düğüm malzeme içeriyorsa, geometriler için her zaman bir [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) oluşturulup oluşturulmayacağını ayarlar. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | OBJ gibi bazı dosyalar harici dosyalara bağımlıdır, arama yolları Aspose.3D'nin yüklemek için harici dosyayı bulmasına izin verir. |
| [setReusePrimitiveMesh(boolean value)](#setReusePrimitiveMesh-boolean-) | Aynı parametrelere sahip primitifler için ağı yeniden kullanın, bu, CAD dosyalarından içe aktarılan büyük bir primitif şekil setiyle oluşturulan sahnenin FBX çıktısının boyutunu önemli ölçüde azaltacaktır. |
| [setVideoForTexture(boolean value)](#setVideoForTexture-boolean-) | FBX olarak dışa aktarılırken bir [Texture](../../com.aspose.threed/texture) için Video örneği oluşturulup oluşturulmayacağını ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FbxSaveOptions(FileFormat format) {#FbxSaveOptions-com.aspose.threed.FileFormat-}
```
public FbxSaveOptions(FileFormat format)
```


Bir [FbxSaveOptions](../../com.aspose.threed/fbxsaveoptions) başlatır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| format | [FileFormat](../../com.aspose.threed/fileformat) | [getFileFormat](../../com.aspose.threed/fbxsaveoptions\#getFileFormat) örneği, geçerli bir FBX formatı olmalıdır. |

### FbxSaveOptions(FileContentType contentType) {#FbxSaveOptions-com.aspose.threed.FileContentType-}
```
public FbxSaveOptions(FileContentType contentType)
```


En son desteklenen sürümü kullanarak bir [FbxSaveOptions](../../com.aspose.threed/fbxsaveoptions) başlatın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) | İkili veya ASCII |

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
### getEmbedTextures() {#getEmbedTextures--}
```
public boolean getEmbedTextures()
```


Doku dosyasının son çıktı dosyasına gömülüp gömülmeyeceğini alır. FBX Dışa Aktarıcı, doku ham verisini [IOConfig.getFileSystem](../../com.aspose.threed/ioconfig\#getFileSystem) üzerinden bulmaya çalışacak ve dosyayı son FBX dosyasına gömecektir. Varsayılan değer false'tur.

**Returns:**
boolean - doku dosyasının son çıktı dosyasına gömülüp gömülmeyeceği. FBX Dışa Aktarıcı, doku ham verisini [IOConfig.getFileSystem](../../com.aspose.threed/ioconfig\#getFileSystem) üzerinden bulmaya çalışacak ve dosyayı son FBX dosyasına gömecektir. Varsayılan değer false'tur.
### getEnableCompression() {#getEnableCompression--}
```
public boolean getEnableCompression()
```


FBX dosyasındaki büyük ikili verileri sıkıştırma (ör. animasyon verileri, kontrol noktaları, vertex eleman verileri, indeksler), varsayılan değer true'tır.

**Returns:**
boolean - FBX dosyasındaki büyük ikili verileri sıkıştırma (ör. animasyon verileri, kontrol noktaları, vertex eleman verileri, indeksler), varsayılan değer true'tır.
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


Metin tabanlı dosyalar için varsayılan kodlamayı alır. Varsayılan değer null'dır, bu da içe aktarıcı/dışa aktarıcının hangi kodlamayı kullanacağına karar vereceği anlamına gelir.

**Returns:**
java.nio.charset.Charset - metin tabanlı dosyalar için varsayılan kodlama. Varsayılan değer null'dır, bu da içe aktarıcı/dışa aktarıcının hangi kodlamayı kullanacağına karar vereceği anlamına gelir.
### getExportLegacyMaterialProperties() {#getExportLegacyMaterialProperties--}
```
public boolean getExportLegacyMaterialProperties()
```


Geri uyumluluk için kullanılan eski malzeme özelliklerinin dışa aktarılıp aktarılmayacağını alır. Bu seçenek varsayılan olarak açıktır.

**Returns:**
boolean - geri uyumluluk için kullanılan eski malzeme özelliklerinin dışa aktarılıp aktarılmayacağı. Bu seçenek varsayılan olarak açıktır.
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
### getFoldRepeatedCurveData() {#getFoldRepeatedCurveData--}
```
public Boolean getFoldRepeatedCurveData()
```


Son verinin referans sayısını artırarak tekrarlanan eğri verisinin yeniden kullanılmasını alır.

**Returns:**
java.lang.Boolean - son verinin referans sayısını artırarak tekrarlanan eğri verisinin yeniden kullanılmasını belirler
### getGenerateVertexElementMaterial() {#getGenerateVertexElementMaterial--}
```
public boolean getGenerateVertexElementMaterial()
```


Ekli düğüm malzeme içeriyorsa, geometriler için her zaman bir [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) oluşturulup oluşturulmayacağını alır. Bu, varsayılan olarak kapalıdır.

**Returns:**
boolean - ekli düğüm malzeme içeriyorsa, geometriler için her zaman bir [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) oluşturulup oluşturulmayacağı. Bu, varsayılan olarak kapalıdır.
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
### getReusePrimitiveMesh() {#getReusePrimitiveMesh--}
```
public boolean getReusePrimitiveMesh()
```


Aynı parametrelere sahip primitifler için ağı yeniden kullanın, bu, CAD dosyalarından içe aktarılan büyük bir primitif şekil setiyle oluşturulan sahnenin FBX çıktısının boyutunu önemli ölçüde azaltacaktır. Varsayılan değer false'tur.

**Returns:**
boolean - Aynı parametrelere sahip primitive'ler için ağı yeniden kullan, bu, CAD dosyalarından içe aktarılan büyük bir primitive şekil setiyle oluşturulan sahnenin FBX çıktısının boyutunu önemli ölçüde azaltacaktır. Varsayılan değer false
### getVideoForTexture() {#getVideoForTexture--}
```
public boolean getVideoForTexture()
```


FBX olarak dışa aktarılırken bir [Texture](../../com.aspose.threed/texture) için Video örneği oluşturulup oluşturulmayacağını alır.

**Returns:**
boolean - FBX olarak dışa aktarırken [Texture](../../com.aspose.threed/texture) için bir Video örneği oluşturulup oluşturulmayacağını belirler.
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


Doku dosyasının son çıktı dosyasına gömülüp gömülmeyeceğini ayarlar. FBX Exporter, dokunun ham verilerini [IOConfig.getFileSystem](../../com.aspose.threed/ioconfig\#getFileSystem) üzerinden bulmaya çalışacak ve dosyayı son FBX dosyasına gömecektir. Varsayılan değer false.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setEnableCompression(boolean value) {#setEnableCompression-boolean-}
```
public void setEnableCompression(boolean value)
```


FBX dosyasındaki büyük ikili verileri sıkıştırma (ör. animasyon verileri, kontrol noktaları, vertex eleman verileri, indeksler), varsayılan değer true'tır.

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

### setExportLegacyMaterialProperties(boolean value) {#setExportLegacyMaterialProperties-boolean-}
```
public void setExportLegacyMaterialProperties(boolean value)
```


Geri uyumluluk için kullanılan eski malzeme özelliklerinin dışa aktarılıp aktarılmayacağını ayarlar. Bu seçenek varsayılan olarak açıktır.

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

### setFoldRepeatedCurveData(Boolean value) {#setFoldRepeatedCurveData-java.lang.Boolean-}
```
public void setFoldRepeatedCurveData(Boolean value)
```


Son verinin referans sayısını artırarak tekrarlanan eğri verisinin yeniden kullanılmasını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Boolean | Yeni değer |

### setGenerateVertexElementMaterial(boolean value) {#setGenerateVertexElementMaterial-boolean-}
```
public void setGenerateVertexElementMaterial(boolean value)
```


Ekli düğüm malzemeler içeriyorsa, geometriler için her zaman bir [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) oluşturulup oluşturulmayacağını ayarlar. Bu, varsayılan olarak kapalıdır.

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

### setReusePrimitiveMesh(boolean value) {#setReusePrimitiveMesh-boolean-}
```
public void setReusePrimitiveMesh(boolean value)
```


Aynı parametrelere sahip primitifler için ağı yeniden kullanın, bu, CAD dosyalarından içe aktarılan büyük bir primitif şekil setiyle oluşturulan sahnenin FBX çıktısının boyutunu önemli ölçüde azaltacaktır. Varsayılan değer false'tur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setVideoForTexture(boolean value) {#setVideoForTexture-boolean-}
```
public void setVideoForTexture(boolean value)
```


FBX olarak dışa aktarılırken bir [Texture](../../com.aspose.threed/texture) için Video örneği oluşturulup oluşturulmayacağını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

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

