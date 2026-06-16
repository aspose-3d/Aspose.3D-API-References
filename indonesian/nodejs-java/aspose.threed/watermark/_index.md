---
title: "Watermark"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/watermark/
---
## Watermark class

Utilitas untuk mengkodekan/mendekode watermark buta ke/dari mesh.  @hideconstructor


## Metode

### encodeWatermark{#encodeWatermark}

| Nama | Deskripsi |
| --- | --- |
| encodeWatermark(input, text) | Menyandikan teks ke dalam watermark buta mesh. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| input | Mesh | Mesh untuk menyandikan watermark buta |
| text | String | Teks untuk disandikan ke mesh |

 **Result:**
Mesh


---


### encodeWatermark{#encodeWatermark}

| Nama | Deskripsi |
| --- | --- |
| encodeWatermark(input, text, password) | Menyandikan teks ke dalam watermark buta mesh. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| input | Mesh | Mesh untuk menyandikan watermark buta |
| text | String | Teks untuk disandikan ke mesh |
| password | String | Kata sandi untuk melindungi watermark, bersifat opsional |

 **Result:**
Mesh


---


### decodeWatermark{#decodeWatermark}

| Nama | Deskripsi |
| --- | --- |
| decodeWatermark(input) | Mendekode watermark dari mesh |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| input | Mesh | Mesh untuk mengekstrak watermark |

 **Result:**
String


---


### decodeWatermark{#decodeWatermark}

| Nama | Deskripsi |
| --- | --- |
| decodeWatermark(input, password) | Mendekode watermark dari mesh |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| input | Mesh | Mesh untuk mengekstrak watermark |
| password | String | Kata sandi untuk mendekripsi watermark |

 **Result:**
String


---



