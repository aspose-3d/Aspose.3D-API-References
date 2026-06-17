---
title: "PlySaveOptions"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/plysaveoptions/
---
## PlySaveOptions class

Sahneyi PLY dosyası olarak dışa aktarmak için kaydetme seçenekleri.


## Yöntemler

### constructor{#constructor}

| Ad | Açıklama |
| --- | --- |
| constructor() | PlySaveOptions yapıcı |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Ad | Açıklama |
| --- | --- |
| constructor_overload(contentType) | PlySaveOptions yapıcı |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getPointCloud{#getPointCloud}

| Ad | Açıklama |
| --- | --- |
| getPointCloud() | Sahneyi nokta bulutu olarak dışa aktar, varsayılan değer false. |

 **Result:**



---


### setPointCloud{#setPointCloud}

| Ad | Açıklama |
| --- | --- |
| setPointCloud(value) | Sahneyi nokta bulutu olarak dışa aktar, varsayılan değer false. |

 **Result:**



---


### getFlipCoordinate{#getFlipCoordinate}

| Ad | Açıklama |
| --- | --- |
| getFlipCoordinate() | Sahneyi kaydederken koordinatı ters çevir, varsayılan değer true |

 **Result:**



---


### setFlipCoordinate{#setFlipCoordinate}

| Ad | Açıklama |
| --- | --- |
| setFlipCoordinate(value) | Sahneyi kaydederken koordinatı ters çevir, varsayılan değer true |

 **Result:**



---


### getVertexElement{#getVertexElement}

| Ad | Açıklama |
| --- | --- |
| getVertexElement() | Vertex verisi için öğe adı, varsayılan değer "vertex" |

 **Result:**



---


### setVertexElement{#setVertexElement}

| Ad | Açıklama |
| --- | --- |
| setVertexElement(value) | Vertex verisi için öğe adı, varsayılan değer "vertex" |

 **Result:**



---


### getPositionComponents{#getPositionComponents}

| Ad | Açıklama |
| --- | --- |
| getPositionComponents() | Pozisyon verisi için bileşen adları, varsayılan değer ("x", "y", "z") |

 **Result:**



---


### getNormalComponents{#getNormalComponents}

| Ad | Açıklama |
| --- | --- |
| getNormalComponents() | Normal verisi için bileşen adları, varsayılan değer ("nx", "ny", "nz") |

 **Result:**



---


### getTextureCoordinateComponents{#getTextureCoordinateComponents}

| Ad | Açıklama |
| --- | --- |
| getTextureCoordinateComponents() | Doku koordinat verileri için bileşen adları, varsayılan değer ("u", "v") |

 **Result:**



---


### getColorComponents{#getColorComponents}

| Ad | Açıklama |
| --- | --- |
| getColorComponents() | Vertex rengi için bileşen adları, varsayılan değer ("red", "green", "blue") |

 **Result:**



---


### getFaceElement{#getFaceElement}

| Ad | Açıklama |
| --- | --- |
| getFaceElement() | Yüz verileri için öğe adı, varsayılan değer "face" |

 **Result:**



---


### setFaceElement{#setFaceElement}

| Ad | Açıklama |
| --- | --- |
| setFaceElement(value) | Yüz verileri için öğe adı, varsayılan değer "face" |

 **Result:**



---


### getFaceProperty{#getFaceProperty}

| Ad | Açıklama |
| --- | --- |
| getFaceProperty() | Yüz verileri için özellik adı, varsayılan değer "vertex_index" |

 **Result:**



---


### setFaceProperty{#setFaceProperty}

| Ad | Açıklama |
| --- | --- |
| setFaceProperty(value) | Yüz verileri için özellik adı, varsayılan değer "vertex_index" |

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



