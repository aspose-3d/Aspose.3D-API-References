---
title: "PdfFormat"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/pdfformat/
---
## PdfFormat class

Adobe'un Taşınabilir Belge Formatı  @hideconstructor


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


### extract{#extract}

| Ad | Açıklama |
| --- | --- |
| extract(fileName, password) | PDF dosyasından ham 3D içeriği çıkar. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| fileNam | String | null |
| parola | byte[] | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=b77a5c561934e089]]


---


### extractScene{#extractScene}

| Ad | Açıklama |
| --- | --- |
| extractScene(fileName) | PDF dosyasından 3D sahneleri çıkar. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| fileNam | String | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=f071c641d0b4582b]]


---


### extractScene{#extractScene}

| Ad | Açıklama |
| --- | --- |
| extractScene(fileName, password) | PDF dosyasından 3D sahneleri çıkar. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| fileNam | String | null |
| parola | byte[] | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=f071c641d0b4582b]]


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



