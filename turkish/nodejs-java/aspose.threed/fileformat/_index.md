---
title: "FileFormat"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/fileformat/
---
## FileFormat class

Dosya formatı tanımı  @hideconstructor


## Özellikler

| Ad | Açıklama |
| --- | --- |
| MAYA_BINARY | İkili formatta Autodesk Maya |
| STL_BINARY | İkili STL dosya formatı |
| STLASCII | ASCII STL dosya formatı |
| COLLADA | Collada dosya formatı |
| GLTF | Khronos Group'un glTF'i |
| GLTF_BINARY | Khronos Group'un ikili formatta glTF'i |
| PDF | Adobe'un Taşınabilir Belge Formatı |
| DXF | AutoCAD DXF |
| PLY | Poligon Dosya Formatı veya Stanford Üçgen Formatı |
| X_BINARY | Binary formatında DirectX X Dosyası |
| X_TEXT | Binary formatında DirectX X Dosyası |
| DRACO | Google Draco Mesh |
| RVM_TEXT | Metin formatında AVEVA Plant Design Management System Modeli |
| RVM_BINARY | Binary formatında AVEVA Plant Design Management System Modeli |
| ASE | 3D Studio Max'in ASCII Scene Exporter formatı. |
| IFC | ISO 16739-1 Industry Foundation Classes veri modeli. |
| AMF | Katmanlı imalat dosya formatı |
| VRML | Sanal Gerçeklik Modelleme Dili |
| ZIP | Diğer 3d dosya formatlarını içeren Zip arşivi. |
| USD | Evrensel Sahne Açıklaması |
| USDZ | Sıkıştırılmış Evrensel Sahne Açıklaması |
| XYZ | Xyz nokta bulutu dosyası |
| PCD | ASCII modunda PCL Point Cloud Data dosyası |
| PCD_BINARY | Binary modunda PCL Point Cloud Data dosyası |

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
| getFileFormatType() | Dosya formatı tipini alır. |

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
FileFormat


---


### detect{#detect}

| Ad | Açıklama |
| --- | --- |
| detect(fileName) | Dosya adından dosya formatını algıla, dosya okunabilir olmalı ki Aspose.3D dosya başlığından dosya formatını algılayabilsin. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| fileNam | String | null |

 **Result:**
FileFormat


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
| toString() | Formatları dizeye dönüştür. |

 **Result:**
String


---



