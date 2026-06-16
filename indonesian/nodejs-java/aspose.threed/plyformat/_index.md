---
title: "PlyFormat"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/plyformat/
---
## PlyFormat class

Format PLY.  @hideconstructor


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


### encode{#encode}

| Nama | Deskripsi |
| --- | --- |
| encode(entity, fileName) | Enkode entitas dan simpan hasilnya ke dalam file eksternal. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| entity | Entity | Entitas yang akan dienkode |
| fileName | String | File yang akan ditulisi |

 **Result:**



---


### encode{#encode}

| Nama | Deskripsi |
| --- | --- |
| encode(entity, fileName, opt) | Enkode entitas dan simpan hasilnya ke dalam file eksternal. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| entity | Entity | Entitas yang akan dienkode |
| fileName | String | File yang akan ditulisi |
| opt | PlySaveOptions | Opsi penyimpanan |

 **Result:**



---


### decode{#decode}

| Nama | Deskripsi |
| --- | --- |
| decode(fileName) | Dekode awan titik atau mesh dari aliran yang ditentukan. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | String | Aliran masukan |

 **Result:**
Geometri


---


### decode{#decode}

| Nama | Deskripsi |
| --- | --- |
| decode(fileName, opt) | Dekode awan titik atau mesh dari aliran yang ditentukan. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | String | Aliran masukan |
| opt | PlyLoadOptions | Opsi pemuatan format PLY |

 **Result:**
Geometri


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



