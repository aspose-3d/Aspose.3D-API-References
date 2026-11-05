---
title: "UsdSaveOptions"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/usdsaveoptions/
---
## UsdSaveOptions class

USD/USDZ formatları için kaydetme seçenekleri.


## Yöntemler

### constructor{#constructor}

| Ad | Açıklama |
| --- | --- |
| constructor() | FileFormat.USD formatı ile yeni bir UsdSaveOptions başlatır. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Ad | Açıklama |
| --- | --- |
| constructor_overload(fileFormat) | Belirtilen USD/USDZ formatı ile yeni bir UsdSaveOptions başlatır. |

 **Result:**



---


### getPrimitiveToMesh{#getPrimitiveToMesh}

| Ad | Açıklama |
| --- | --- |
| getPrimitiveToMesh() | Dışa aktarım sırasında ilkel varlıkları mesh'e dönüştür. Ya da ilkel nesneleri doğrudan çıktı dosyasına kodla (Dish, Torus gibi resmi olmayan ilkel varlıklar için Aspose'un uzantı tanımını kullanır). Varsayılan değer true'tir. |

 **Result:**



---


### setPrimitiveToMesh{#setPrimitiveToMesh}

| Ad | Açıklama |
| --- | --- |
| setPrimitiveToMesh(value) | Dışa aktarım sırasında ilkel varlıkları mesh'e dönüştür. Ya da ilkel nesneleri doğrudan çıktı dosyasına kodla (Dish, Torus gibi resmi olmayan ilkel varlıklar için Aspose'un uzantı tanımını kullanır). Varsayılan değer true'tir. |

 **Result:**



---


### getExportMetaData{#getExportMetaData}

| Ad | Açıklama |
| --- | --- |
| getExportMetaData() | Düğümün özelliklerini USD'nin customData alanı üzerinden dışa aktar. |

 **Result:**



---


### setExportMetaData{#setExportMetaData}

| Ad | Açıklama |
| --- | --- |
| setExportMetaData(value) | Düğümün özelliklerini USD'nin customData alanı üzerinden dışa aktar. |

 **Result:**



---


### getMaterialConverter{#getMaterialConverter}

| Ad | Açıklama |
| --- | --- |
| getMaterialConverter() | Geometrinin malzemesini PBR malzemesine dönüştürmek için özel dönüştürücü. Eğer atanmazsa, USD dışa aktarıcı standart malzemeyi otomatik olarak PBR malzemesine dönüştürür. Varsayılan değer null'dır. |

 **Result:**



---


### setMaterialConverter{#setMaterialConverter}

| Ad | Açıklama |
| --- | --- |
| setMaterialConverter(value) | Geometrinin malzemesini PBR malzemesine dönüştürmek için özel dönüştürücü. Eğer atanmazsa, USD dışa aktarıcı standart malzemeyi otomatik olarak PBR malzemesine dönüştürür. Varsayılan değer null'dır. |

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



