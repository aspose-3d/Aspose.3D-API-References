---
title: "Dosya Biçimi"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/fileformat/
---
## FileFormat class

Dosya formatı tanımı  @hideconstructor


## Properties

| Ad | Açıklama |
| --- | --- |
| MAYA_BINARY | İkili formatta Autodesk Maya |
| STL_BINARY | İkili STL dosya formatı |
| STLASCII | ASCII STL dosya formatı |
| COLLADA | Collada dosya formatı |
| GLTF | Khronos Group'un glTF |
| GLTF_BINARY | Khronos Group'un ikili formatta glTF |
| PDF | Adobe'un Taşınabilir Belge Formatı |
| DXF | AutoCAD DXF |
| PLY | Poligon Dosya Formatı veya Stanford Üçgen Formatı |
| X_BINARY | İkili formatta DirectX X Dosyası |
| X_TEXT | İkili formatta DirectX X Dosyası |
| DRACO | Google Draco Mesh |
| RVM_TEXT | AVEVA Plant Design Management System Model metin formatında |
| RVM_BINARY | AVEVA Plant Design Management System Model ikili formatında |
| ASE | 3D Studio Max'in ASCII Sahne Dışa Aktarıcı formatı. |
| IFC | ISO 16739-1 Industry Foundation Classes veri modeli. |
| AMF | Katmanlı imalat dosya formatı |
| VRML | Sanal Gerçeklik Modelleme Dili |
| ZIP | Diğer 3d dosya formatlarını içeren Zip arşivi. |
| USD | Evrensel Sahne Tanımı |
| USDZ | Sıkıştırılmış Evrensel Sahne Tanımı |
| XYZ | Xyz nokta bulutu dosyası |
| PCD | PCL Nokta Bulutu Veri dosyası ASCII modunda |
| PCD_BINARY | PCL Nokta Bulutu Veri dosyası ikili modda |

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


### getFormatByExtension{#getFormatByExtension}

| Ad | Açıklama |
| --- | --- |
| getFormatByExtension(extensionName) | Dosya uzantı adından tercih edilen dosya formatını alır. Uzantı adı bir nokta ('.') ile başlamalıdır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| extensionNam | String | null |

 **Result:**
Dosya Biçimi


---


### detect{#detect}

| Ad | Açıklama |
| --- | --- |
| detect(fileName) | Dosya adından dosya formatını algıla, dosya okunabilir olmalı ki Aspose.3D dosya başlığı üzerinden dosya formatını algılayabilsin. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| fileNam | String | null |

 **Result:**
Dosya Biçimi


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



