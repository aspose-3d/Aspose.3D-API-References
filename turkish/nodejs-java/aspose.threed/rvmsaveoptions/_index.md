---
title: "RvmSaveOptions"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/rvmsaveoptions/
---
## RvmSaveOptions class

Aveva PDMS RVM dosyası için kaydetme seçenekleri.


## Yöntemler

### constructor{#constructor}

| Ad | Açıklama |
| --- | --- |
| constructor() | RvmSaveOptions'ın yapıcı yöntemi |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Ad | Açıklama |
| --- | --- |
| constructor_overload(contentType) | RvmSaveOptions'ın yapıcı yöntemi |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getFileNote{#getFileNote}

| Ad | Açıklama |
| --- | --- |
| getFileNote() | Dosya başlığındaki dosya notu. |

 **Result:**



---


### setFileNote{#setFileNote}

| Ad | Açıklama |
| --- | --- |
| setFileNote(value) | Dosya başlığındaki dosya notu. |

 **Result:**



---


### getAuthor{#getAuthor}

| Ad | Açıklama |
| --- | --- |
| getAuthor() |  |

 **Result:**



---


### setAuthor{#setAuthor}

| Ad | Açıklama |
| --- | --- |
| setAuthor(value) |  |

 **Result:**



---


### getCreationTime{#getCreationTime}

| Ad | Açıklama |
| --- | --- |
| getCreationTime() | Bu dosyayı dışa aktaran zaman damgası, varsayılan değer şu anki zamandır |

 **Result:**



---


### setCreationTime{#setCreationTime}

| Ad | Açıklama |
| --- | --- |
| setCreationTime(value) | Bu dosyayı dışa aktaran zaman damgası, varsayılan değer şu anki zamandır |

 **Result:**



---


### getAttributePrefix{#getAttributePrefix}

| Ad | Açıklama |
| --- | --- |
| getAttributePrefix() | Dışa aktarılacak özniteliklerin önekini alır veya ayarlar, dışa aktarılan özellik önek içermez, farklı önekli özel özellikler dışa aktarılmaz, varsayılan değer 'rvm:'dır. Örneğin bir özellik rvm:Refno=345 ise, dışa aktarılan öznitelik Refno = 345 olur, önek kaldırılır. |

 **Result:**



---


### setAttributePrefix{#setAttributePrefix}

| Ad | Açıklama |
| --- | --- |
| setAttributePrefix(value) | Dışa aktarılacak özniteliklerin önekini alır veya ayarlar, dışa aktarılan özellik önek içermez, farklı önekli özel özellikler dışa aktarılmaz, varsayılan değer 'rvm:'dır. Örneğin bir özellik rvm:Refno=345 ise, dışa aktarılan öznitelik Refno = 345 olur, önek kaldırılır. |

 **Result:**



---


### getAttributeListFile{#getAttributeListFile}

| Ad | Açıklama |
| --- | --- |
| getAttributeListFile() | Özellik listesi dosyasının dosya adını alır veya ayarlar, bu özellik tanımsız olduğunda dışa aktarıcı .rvm dosya adına göre bir ad oluşturur, varsayılan değer null'dur. |

 **Result:**



---


### setAttributeListFile{#setAttributeListFile}

| Ad | Açıklama |
| --- | --- |
| setAttributeListFile(value) | Özellik listesi dosyasının dosya adını alır veya ayarlar, bu özellik tanımsız olduğunda dışa aktarıcı .rvm dosya adına göre bir ad oluşturur, varsayılan değer null'dur. |

 **Result:**



---


### getExportAttributes{#getExportAttributes}

| Ad | Açıklama |
| --- | --- |
| getExportAttributes() | Özellik listesinin harici bir .att dosyasına dışa aktarılıp aktarılmayacağını alır veya ayarlar, varsayılan değer false'tur. |

 **Result:**



---


### setExportAttributes{#setExportAttributes}

| Ad | Açıklama |
| --- | --- |
| setExportAttributes(value) | Özellik listesinin harici bir .att dosyasına dışa aktarılıp aktarılmayacağını alır veya ayarlar, varsayılan değer false'tur. |

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



