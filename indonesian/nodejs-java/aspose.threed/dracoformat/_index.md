---
title: "DracoFormat"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/dracoformat/
---
## DracoFormat class

Format Google Draco  @hideconstructor


## Metode

### getVersion{#getVersion}

| Nama | Deskripsi |
| --- | --- |
| getVersion() | Mendapatkan versi format file |

 **Result:**



---


### getExtension{#getExtension}

| Nama | Deskripsi |
| --- | --- |
| getExtension() | Mendapatkan nama ekstensi dari tipe ini. |

 **Result:**



---


### getExtensions{#getExtensions}

| Nama | Deskripsi |
| --- | --- |
| getExtensions() | Mendapatkan nama-nama ekstensi dari tipe ini. |

 **Result:**



---


### getContentType{#getContentType}

| Nama | Deskripsi |
| --- | --- |
| getContentType() | Mendapatkan tipe konten format file Nilai properti adalah konstanta integer FileContentType. |

 **Result:**



---


### getFileFormatType{#getFileFormatType}

| Nama | Deskripsi |
| --- | --- |
| getFileFormatType() | Mendapatkan tipe format file |

 **Result:**



---


### decode{#decode}

| Nama | Deskripsi |
| --- | --- |
| decode(fileName) | Dekode awan titik atau mesh dari nama file yang ditentukan |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | String | Nama file berisi file drc |

 **Result:**
Geometri


---


### decode{#decode}

| Nama | Deskripsi |
| --- | --- |
| decode(data) | Dekode awan titik atau mesh dari data memori |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| data | byte[] | Byte drc mentah |

 **Result:**
Geometri


---


### encode{#encode}

| Nama | Deskripsi |
| --- | --- |
| encode(entity, fileName, options) | Enkode entitas ke file yang ditentukan |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| entity | Entity | Entitas yang akan dienkode |
| fileName | String | Nama file yang akan ditulis |
| opsi | DracoSaveOptions | Opsi tambahan untuk mengenkode awan titik |

 **Result:**
Geometri


---


### encode{#encode}

| Nama | Deskripsi |
| --- | --- |
| encode(entity, options) | Enkode entitas ke data mentah Draco |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| entity | Entity | Entitas yang akan dienkode |
| opsi | DracoSaveOptions | Opsi tambahan untuk mengenkode awan titik |

 **Result:**
byte[]


---


### createLoadOptions{#createLoadOptions}

| Nama | Deskripsi |
| --- | --- |
| createLoadOptions() | Buat opsi muat default untuk format file ini |

 **Result:**
LoadOptions


---


### createSaveOptions{#createSaveOptions}

| Nama | Deskripsi |
| --- | --- |
| createSaveOptions() | Buat opsi simpan default untuk format file ini |

 **Result:**
SaveOptions


---


### toString{#toString}

| Nama | Deskripsi |
| --- | --- |
| toString() | Format menjadi string |

 **Result:**
String


---



