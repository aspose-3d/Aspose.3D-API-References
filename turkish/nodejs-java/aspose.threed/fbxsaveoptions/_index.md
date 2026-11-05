---
title: "FbxSaveOptions"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/fbxsaveoptions/
---
## FbxSaveOptions class

Fbx dosyası için kaydetme seçenekleri.


## Yöntemler

### constructor{#constructor}

| Ad | Açıklama |
| --- | --- |
| constructor(format) | Bir FbxSaveOptions başlatır |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| biçim | FileFormat | null |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Ad | Açıklama |
| --- | --- |
| constructor_overload(contentType) | En son desteklenen sürümü kullanarak bir FbxSaveOptions başlatın. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getReusePrimitiveMesh{#getReusePrimitiveMesh}

| Ad | Açıklama |
| --- | --- |
| getReusePrimitiveMesh() | Aynı parametrelere sahip primitifler için ağı yeniden kullan, bu, büyük bir primitif şekil kümesi (CAD dosyalarından içe aktarılan gibi) tarafından oluşturulan sahnenin FBX çıktısının boyutunu önemli ölçüde azaltır. Varsayılan değer false'tur. |

 **Result:**



---


### setReusePrimitiveMesh{#setReusePrimitiveMesh}

| Ad | Açıklama |
| --- | --- |
| setReusePrimitiveMesh(value) | Aynı parametrelere sahip primitifler için ağı yeniden kullan, bu, büyük bir primitif şekil kümesi (CAD dosyalarından içe aktarılan gibi) tarafından oluşturulan sahnenin FBX çıktısının boyutunu önemli ölçüde azaltır. Varsayılan değer false'tur. |

 **Result:**



---


### getEnableCompression{#getEnableCompression}

| Ad | Açıklama |
| --- | --- |
| getEnableCompression() | FBX dosyasındaki büyük ikili verileri sıkıştır (ör. animasyon verileri, kontrol noktaları, vertex eleman verileri, indeksler), varsayılan değer true'tur. |

 **Result:**



---


### setEnableCompression{#setEnableCompression}

| Ad | Açıklama |
| --- | --- |
| setEnableCompression(value) | FBX dosyasındaki büyük ikili verileri sıkıştır (ör. animasyon verileri, kontrol noktaları, vertex eleman verileri, indeksler), varsayılan değer true'tur. |

 **Result:**



---


### getFoldRepeatedCurveData{#getFoldRepeatedCurveData}

| Ad | Açıklama |
| --- | --- |
| getFoldRepeatedCurveData() | Tekrarlanan eğri verilerini, son verinin referans sayısını artırarak yeniden kullanıp kullanmayacağını alır veya ayarlar; tekrarlanan eğri verileri katlanıyorsa true, aksi takdirde false. |

 **Result:**



---


### getExportLegacyMaterialProperties{#getExportLegacyMaterialProperties}

| Ad | Açıklama |
| --- | --- |
| getExportLegacyMaterialProperties() | Legacy malzeme özelliklerini dışa aktarılıp aktarılmayacağını alır veya ayarlar, geriye uyumluluk için kullanılır. Bu seçenek varsayılan olarak açıktır. |

 **Result:**



---


### setExportLegacyMaterialProperties{#setExportLegacyMaterialProperties}

| Ad | Açıklama |
| --- | --- |
| setExportLegacyMaterialProperties(value) | Legacy malzeme özelliklerini dışa aktarılıp aktarılmayacağını alır veya ayarlar, geriye uyumluluk için kullanılır. Bu seçenek varsayılan olarak açıktır. |

 **Result:**



---


### getVideoForTexture{#getVideoForTexture}

| Ad | Açıklama |
| --- | --- |
| getVideoForTexture() | Dışa aktarırken bir Texture için Video örneği oluşturulup oluşturulmayacağını alır veya ayarlar (FBX olarak). |

 **Result:**



---


### setVideoForTexture{#setVideoForTexture}

| Ad | Açıklama |
| --- | --- |
| setVideoForTexture(value) | Dışa aktarırken bir Texture için Video örneği oluşturulup oluşturulmayacağını alır veya ayarlar (FBX olarak). |

 **Result:**



---


### getEmbedTextures{#getEmbedTextures}

| Ad | Açıklama |
| --- | --- |
| getEmbedTextures() | Doku'yu nihai çıktı dosyasına gömüp gömmeyeceğini alır veya ayarlar. FBX Exporter, dokunun ham verilerini FileSystem'den bulmaya çalışacak ve dosyayı nihai FBX dosyasına gömecektir. Varsayılan değer false'tur. |

 **Result:**



---


### setEmbedTextures{#setEmbedTextures}

| Ad | Açıklama |
| --- | --- |
| setEmbedTextures(value) | Doku'yu nihai çıktı dosyasına gömüp gömmeyeceğini alır veya ayarlar. FBX Exporter, dokunun ham verilerini FileSystem'den bulmaya çalışacak ve dosyayı nihai FBX dosyasına gömecektir. Varsayılan değer false'tur. |

 **Result:**



---


### getGenerateVertexElementMaterial{#getGenerateVertexElementMaterial}

| Ad | Açıklama |
| --- | --- |
| getGenerateVertexElementMaterial() | Ekli düğüm malzemeler içeriyorsa, geometriler için her zaman bir VertexElementMaterial oluşturulup oluşturulmayacağını alır veya ayarlar. Bu varsayılan olarak kapalıdır. |

 **Result:**



---


### setGenerateVertexElementMaterial{#setGenerateVertexElementMaterial}

| Ad | Açıklama |
| --- | --- |
| setGenerateVertexElementMaterial(value) | Ekli düğüm malzemeler içeriyorsa, geometriler için her zaman bir VertexElementMaterial oluşturulup oluşturulmayacağını alır veya ayarlar. Bu varsayılan olarak kapalıdır. |

 **Result:**



---


### getExportTextures{#getExportTextures}

| Ad | Açıklama |
| --- | --- |
| getExportTextures() | Sahnede kullanılan dokuları çıktı dizinine kopyalamayı dene. |

 **Result:**



---


### setExportTextures{#setExportTextures}

| Ad | Açıklama |
| --- | --- |
| setExportTextures(value) | Sahnede kullanılan dokuları çıktı dizinine kopyalamayı dene. |

 **Result:**



---


### getFileFormat{#getFileFormat}

| Ad | Açıklama |
| --- | --- |
| getFileFormat() | Mevcut Kaydet/Yükle seçeneğinde belirtilen dosya formatını alır. |

 **Result:**



---


### getEncoding{#getEncoding}

| Ad | Açıklama |
| --- | --- |
| getEncoding() | Metin tabanlı dosyalar için varsayılan kodlamayı alır veya ayarlar. Varsayılan değer null'dur, bu da içe aktarıcı/dışa aktarıcının hangi kodlamayı kullanacağını belirleyeceği anlamına gelir. |

 **Result:**



---


### getFileSystem{#getFileSystem}

| Ad | Açıklama |
| --- | --- |
| getFileSystem() | Kullanıcının yükleme/kaydetme sırasında dış bağımlılıkların nasıl yönetileceğini ele almasına izin verir. |

 **Result:**



---


### setFileSystem{#setFileSystem}

| Ad | Açıklama |
| --- | --- |
| setFileSystem(value) | Kullanıcının yükleme/kaydetme sırasında dış bağımlılıkların nasıl yönetileceğini ele almasına izin verir. |

 **Result:**



---


### getLookupPaths{#getLookupPaths}

| Ad | Açıklama |
| --- | --- |
| getLookupPaths() | OBJ gibi bazı dosyalar dış dosyalara bağımlıdır, arama yolları Aspose.3D'nin dış dosyayı yüklemek için aramasına izin verir. |

 **Result:**



---


### getFileName{#getFileName}

| Ad | Açıklama |
| --- | --- |
| getFileName() | Dışa/İçe aktarılan sahnenin dosya adı. Bu isteğe bağlıdır, ancak OBJ'nin materyali gibi dış varlıkları serileştirirken faydalıdır. |

 **Result:**



---


### setFileName{#setFileName}

| Ad | Açıklama |
| --- | --- |
| setFileName(value) | Dışa/İçe aktarılan sahnenin dosya adı. Bu isteğe bağlıdır, ancak OBJ'nin materyali gibi dış varlıkları serileştirirken faydalıdır. |

 **Result:**



---



