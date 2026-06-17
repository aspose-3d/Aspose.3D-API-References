---
title: "GltfSaveOptions"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/gltfsaveoptions/
---
## GltfSaveOptions class

glTF formatı için kaydetme seçenekleri.


## Yöntemler

### constructor{#constructor}

| Ad | Açıklama |
| --- | --- |
| constructor(contentType) | GltfSaveOptions sınıfının yapıcı metodu |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Ad | Açıklama |
| --- | --- |
| constructor_overload(format) | GltfSaveOptions sınıfının yapıcı metodu |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| forma | Dosya Biçimi | null |

 **Result:**



---


### getPrettyPrint{#getPrettyPrint}

| Ad | Açıklama |
| --- | --- |
| getPrettyPrint() | GLTF dosyasının JSON içeriği insan okuyuşu için girintilenmiştir, varsayılan değer false'tur. |

 **Result:**



---


### setPrettyPrint{#setPrettyPrint}

| Ad | Açıklama |
| --- | --- |
| setPrettyPrint(value) | GLTF dosyasının JSON içeriği insan okuyuşu için girintilenmiştir, varsayılan değer false'tur. |

 **Result:**



---


### getFallbackNormal{#getFallbackNormal}

| Ad | Açıklama |
| --- | --- |
| getFallbackNormal() | GLTF2 dışa aktarıcı geçersiz bir normal tespit ettiğinde, doğrulamadan geçmek için orijinal değeri yerine bu değer kullanılacaktır. Varsayılan değer (0, 1, 0)'dır. |

 **Result:**



---


### getEmbedAssets{#getEmbedAssets}

| Ad | Açıklama |
| --- | --- |
| getEmbedAssets() | Tüm dış varlıkları ASCII modunda tek bir dosyaya base64 olarak göm, varsayılan değer false'tur. |

 **Result:**



---


### setEmbedAssets{#setEmbedAssets}

| Ad | Açıklama |
| --- | --- |
| setEmbedAssets(value) | Tüm dış varlıkları ASCII modunda tek bir dosyaya base64 olarak göm, varsayılan değer false'tur. |

 **Result:**



---


### getImageFormat{#getImageFormat}

| Ad | Açıklama |
| --- | --- |
| getImageFormat() | Standart glTF yalnızca PNG/JPG'yi doku formatı olarak destekler, bu seçenek dış standart görüntülerin dışa aktarım sırasında Aspose.3D tarafından desteklenen formata nasıl dönüştürüleceğini yönlendirir. Varsayılan değer GltfEmbeddedImageFormat.PNG'dir. Özelliğin değeri GltfEmbeddedImageFormat tam sayı sabitidir. |

 **Result:**



---


### setImageFormat{#setImageFormat}

| Ad | Açıklama |
| --- | --- |
| setImageFormat(value) | Standart glTF yalnızca PNG/JPG'yi doku formatı olarak destekler, bu seçenek dış standart görüntülerin dışa aktarım sırasında Aspose.3D tarafından desteklenen formata nasıl dönüştürüleceğini yönlendirir. Varsayılan değer GltfEmbeddedImageFormat.PNG'dir. Özelliğin değeri GltfEmbeddedImageFormat tam sayı sabitidir. |

 **Result:**



---


### getMaterialConverter{#getMaterialConverter}

| Ad | Açıklama |
| --- | --- |
| getMaterialConverter() | Geometrinin malzemesini PBR malzemesine dönüştürmek için özel dönüştürücü. Eğer atanmazsa, glTF 2.0 dışa aktarıcı standart malzemeyi otomatik olarak PBR malzemesine dönüştürür. Varsayılan değer null'dır. Bu özellik bir sahneyi glTF 2.0 dosyasına dışa aktarırken kullanılır. |

 **Result:**



---


### setMaterialConverter{#setMaterialConverter}

| Ad | Açıklama |
| --- | --- |
| setMaterialConverter(value) | Geometrinin malzemesini PBR malzemesine dönüştürmek için özel dönüştürücü. Eğer atanmazsa, glTF 2.0 dışa aktarıcı standart malzemeyi otomatik olarak PBR malzemesine dönüştürür. Varsayılan değer null'dır. Bu özellik bir sahneyi glTF 2.0 dosyasına dışa aktarırken kullanılır. |

 **Result:**



---


### getUseCommonMaterials{#getUseCommonMaterials}

| Ad | Açıklama |
| --- | --- |
| getUseCommonMaterials() | Malzemeleri KHR ortak malzeme uzantılarını kullanarak serileştir, varsayılan değer false'tur. Bunu false olarak ayarlamak, Aspose.3D'nin bir dizi vertex/fragment gölgelendirici dışa aktarmasına neden olur eğer #Error Cref: P:Aspose.ThreeD.Formats.GltfSaveOptions.ExportShaders |

 **Result:**



---


### setUseCommonMaterials{#setUseCommonMaterials}

| Ad | Açıklama |
| --- | --- |
| setUseCommonMaterials(value) | Malzemeleri KHR ortak malzeme uzantılarını kullanarak serileştir, varsayılan değer false'tur. Bunu false olarak ayarlamak, Aspose.3D'nin bir dizi vertex/fragment gölgelendirici dışa aktarmasına neden olur eğer #Error Cref: P:Aspose.ThreeD.Formats.GltfSaveOptions.ExportShaders |

 **Result:**



---


### getExternalDracoEncoder{#getExternalDracoEncoder}

| Ad | Açıklama |
| --- | --- |
| getExternalDracoEncoder() | Draco sıkıştırma hızını artırmak için harici draco kodlayıcı kullanın. Aspose.3D, ağı draco formatına kodlamak için yeni bir alt süreç oluşturacak, bunu kendi sorumluluğunuzda kullanın. |

 **Result:**



---


### setExternalDracoEncoder{#setExternalDracoEncoder}

| Ad | Açıklama |
| --- | --- |
| setExternalDracoEncoder(value) | Draco sıkıştırma hızını artırmak için harici draco kodlayıcı kullanın. Aspose.3D, ağı draco formatına kodlamak için yeni bir alt süreç oluşturacak, bunu kendi sorumluluğunuzda kullanın. |

 **Result:**



---


### getFlipTexCoordV{#getFlipTexCoordV}

| Ad | Açıklama |
| --- | --- |
| getFlipTexCoordV() | Doku koordinatı v(t) bileşenini ters çevir, varsayılan değer true'tur. |

 **Result:**



---


### setFlipTexCoordV{#setFlipTexCoordV}

| Ad | Açıklama |
| --- | --- |
| setFlipTexCoordV(value) | Doku koordinatı v(t) bileşenini ters çevir, varsayılan değer true'tur. |

 **Result:**



---


### getBufferFile{#getBufferFile}

| Ad | Açıklama |
| --- | --- |
| getBufferFile() | İkili verileri depolamak için kullanılan harici tampon dosyasının dosya adı. Bu dosya belirtilmezse, Aspose.3D sizin için bir ad oluşturur. Bu, glTF'yi ikili modda dışa aktarırken yoksayılır. |

 **Result:**



---


### setBufferFile{#setBufferFile}

| Ad | Açıklama |
| --- | --- |
| setBufferFile(value) | İkili verileri depolamak için kullanılan harici tampon dosyasının dosya adı. Bu dosya belirtilmezse, Aspose.3D sizin için bir ad oluşturur. Bu, glTF'yi ikili modda dışa aktarırken yoksayılır. |

 **Result:**



---


### getSaveExtras{#getSaveExtras}

| Ad | Açıklama |
| --- | --- |
| getSaveExtras() | Sahne nesnesinin dinamik özelliklerini oluşturulan glTF dosyasındaki 'extra' alanlarına kaydet. Bu, uygulamaya özgü verileri sağlamak için faydalıdır. Varsayılan değer false'tur. |

 **Result:**



---


### setSaveExtras{#setSaveExtras}

| Ad | Açıklama |
| --- | --- |
| setSaveExtras(value) | Sahne nesnesinin dinamik özelliklerini oluşturulan glTF dosyasındaki 'extra' alanlarına kaydet. Bu, uygulamaya özgü verileri sağlamak için faydalıdır. Varsayılan değer false'tur. |

 **Result:**



---


### getApplyUnitScale{#getApplyUnitScale}

| Ad | Açıklama |
| --- | --- |
| getApplyUnitScale() | AssetInfo.UnitScaleFactor'ı mesh'e uygula. Varsayılan değer false'tur. |

 **Result:**



---


### setApplyUnitScale{#setApplyUnitScale}

| Ad | Açıklama |
| --- | --- |
| setApplyUnitScale(value) | AssetInfo.UnitScaleFactor'ı mesh'e uygula. Varsayılan değer false'tur. |

 **Result:**



---


### getDracoCompression{#getDracoCompression}

| Ad | Açıklama |
| --- | --- |
| getDracoCompression() | Draco sıkıştırmasını etkinleştirip etkinleştirmeyeceği alınır veya ayarlanır |

 **Result:**



---


### setDracoCompression{#setDracoCompression}

| Ad | Açıklama |
| --- | --- |
| setDracoCompression(value) | Draco sıkıştırmasını etkinleştirip etkinleştirmeyeceği alınır veya ayarlanır |

 **Result:**



---


### getExportTextures{#getExportTextures}

| Ad | Açıklama |
| --- | --- |
| getExportTextures() | Sahnede kullanılan dokuları çıktı dizinine kopyalamayı deneyin. |

 **Result:**



---


### setExportTextures{#setExportTextures}

| Ad | Açıklama |
| --- | --- |
| setExportTextures(value) | Sahnede kullanılan dokuları çıktı dizinine kopyalamayı deneyin. |

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
| getEncoding() | Metin tabanlı dosyalar için varsayılan kodlamayı alır veya ayarlar. Varsayılan değer null'dur, bu da içe aktarıcı/dışa aktarıcının hangi kodlamayı kullanacağına karar vereceği anlamına gelir. |

 **Result:**



---


### getFileSystem{#getFileSystem}

| Ad | Açıklama |
| --- | --- |
| getFileSystem() | Kullanıcının yükleme/kaydetme sırasında dış bağımlılıkları nasıl yöneteceğini ele almasına izin verir. |

 **Result:**



---


### setFileSystem{#setFileSystem}

| Ad | Açıklama |
| --- | --- |
| setFileSystem(value) | Kullanıcının yükleme/kaydetme sırasında dış bağımlılıkları nasıl yöneteceğini ele almasına izin verir. |

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
| getFileName() | Dışa aktarma/içe aktarma sahnesinin dosya adı. Bu isteğe bağlıdır, ancak OBJ'nin malzemesi gibi dış varlıkları serileştirirken faydalıdır. |

 **Result:**



---


### setFileName{#setFileName}

| Ad | Açıklama |
| --- | --- |
| setFileName(value) | Dışa aktarma/içe aktarma sahnesinin dosya adı. Bu isteğe bağlıdır, ancak OBJ'nin malzemesi gibi dış varlıkları serileştirirken faydalıdır. |

 **Result:**



---



