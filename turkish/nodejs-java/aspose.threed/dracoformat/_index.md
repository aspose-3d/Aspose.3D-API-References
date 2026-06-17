---
title: "DracoFormat"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/dracoformat/
---
## DracoFormat class

Google Draco formatı  @hideconstructor


## Yöntemler

### getVersion{#getVersion}

| Ad | Açıklama |
| --- | --- |
| getVersion() | Dosya formatı sürümünü alır |

 **Result:**



---


### getExtension{#getExtension}

| Ad | Açıklama |
| --- | --- |
| getExtension() | Bu tipin uzantı adını alır. |

 **Result:**



---


### getExtensions{#getExtensions}

| Ad | Açıklama |
| --- | --- |
| getExtensions() | Bu tipin uzantı adlarını alır. |

 **Result:**



---


### getContentType{#getContentType}

| Ad | Açıklama |
| --- | --- |
| getContentType() | Dosya formatı içerik tipini alır. Özelliğin değeri FileContentType tam sayı sabitidir. |

 **Result:**



---


### getFileFormatType{#getFileFormatType}

| Ad | Açıklama |
| --- | --- |
| getFileFormatType() | Dosya formatı tipini alır |

 **Result:**



---


### decode{#decode}

| Ad | Açıklama |
| --- | --- |
| decode(fileName) | Belirtilen dosya adından nokta bulutunu veya örgüyü çözümleyin |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| fileName | String | Dosya adı drc dosyasını içerir |

 **Result:**
Geometri


---


### decode{#decode}

| Ad | Açıklama |
| --- | --- |
| decode(data) | Bellek verisinden nokta bulutunu veya örgüyü çözümleyin |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| data | byte[] | Ham drc baytları |

 **Result:**
Geometri


---


### encode{#encode}

| Ad | Açıklama |
| --- | --- |
| encode(entity, fileName, options) | Varlığı belirtilen dosyaya kodlayın |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| varlık | Varlık | Kodlanacak varlık |
| fileName | String | Yazılacak dosya adı |
| seçenekler | DracoSaveOptions | Nokta bulutunu kodlamak için ek seçenekler |

 **Result:**
Geometri


---


### encode{#encode}

| Ad | Açıklama |
| --- | --- |
| encode(entity, options) | Varlığı Draco ham verisine kodlayın |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| varlık | Varlık | Kodlanacak varlık |
| seçenekler | DracoSaveOptions | Nokta bulutunu kodlamak için ek seçenekler |

 **Result:**
byte[]


---


### createLoadOptions{#createLoadOptions}

| Ad | Açıklama |
| --- | --- |
| createLoadOptions() | Bu dosya formatı için varsayılan yükleme seçeneklerini oluştur. |

 **Result:**
LoadOptions


---


### createSaveOptions{#createSaveOptions}

| Ad | Açıklama |
| --- | --- |
| createSaveOptions() | Bu dosya formatı için varsayılan kaydetme seçeneklerini oluştur. |

 **Result:**
SaveOptions


---


### toString{#toString}

| Ad | Açıklama |
| --- | --- |
| toString() | Biçimleri dizeye dönüştür |

 **Result:**
String


---



