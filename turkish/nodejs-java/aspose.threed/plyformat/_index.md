---
title: "PlyFormat"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/plyformat/
---
## PlyFormat class

PLY formatı.  @hideconstructor


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


### encode{#encode}

| Ad | Açıklama |
| --- | --- |
| encode(entity, fileName) | Varlığı kodlayın ve sonucu harici bir dosyaya kaydedin. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| varlık | Varlık | Kodlanacak varlık |
| fileName | String | Yazılacak dosya |

 **Result:**



---


### encode{#encode}

| Ad | Açıklama |
| --- | --- |
| encode(entity, fileName, opt) | Varlığı kodlayın ve sonucu harici bir dosyaya kaydedin. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| varlık | Varlık | Kodlanacak varlık |
| fileName | String | Yazılacak dosya |
| opt | PlySaveOptions | Kaydetme seçenekleri |

 **Result:**



---


### decode{#decode}

| Ad | Açıklama |
| --- | --- |
| decode(fileName) | Belirtilen akıştan bir nokta bulutu veya örgüyü çözümleyin. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| fileName | String | Giriş akışı |

 **Result:**
Geometri


---


### decode{#decode}

| Ad | Açıklama |
| --- | --- |
| decode(fileName, opt) | Belirtilen akıştan bir nokta bulutu veya örgüyü çözümleyin. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| fileName | String | Giriş akışı |
| opt | PlyLoadOptions | PLY formatının yükleme seçeneği |

 **Result:**
Geometri


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



